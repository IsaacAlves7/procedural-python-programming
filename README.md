<a href="https://github.com/IsaacAlves7/python-programming"><img src="https://cdn.worldvectorlogo.com/logos/python-3.svg" heigth="177"/></a>

# <img src="https://emojis.slackmojis.com/emojis/images/1516924249/3439/python_explode.gif?1516924249" height="30"> It's a repository of Python programming 🐍
<blockquote>I created this repository for my Python language Full-Stack Development learning.</blockquote>

<a href="https://github.com/IsaacAlves7/python-programming"><div align="center"><img src="https://poster.keepcalmandposters.com/6993577.jpg" height="307"/></div></a>

# 🐒 Paradigmas de desenvolvimento de software

<div align="center"><img src="https://user-images.githubusercontent.com/61624336/112900537-065ce480-90ba-11eb-86f7-f9006445876a.png"></div><br \>

Hoje em dia, o desenvolvimento de sistemas se baseia em vários e diferentes paradigmas, tais como os listados a seguir:

- **Imperativo (Procedural)**: Segue sequências de comandos ordenados segundo uma lógica.
- **Funcional**: Trabalha com a divisão de problemas através de funções, que resolvem separadamente problemas menores e que, ao serem organizados, resolvem o problema como um todo.
- **Lógico**: Voltado ao desenvolvimento de problemas de lógica e usado em sistemas de inteligência computacional.
- **Orientado a Objetos (OO)**: Define um conjunto de classes para dividir o problema e realiza a interação entre as diferentes classes para também resolver o problema como um todo.

# 🐍 Classificação das linguagens de programação ✨
<a href="https://github.com/IsaacAlves7/python-programming"><img src="https://www.visionnaire.com.br/en/dbimages/visionnaire-linguagens-de-programacao_14045_img.jpg" heigth="177"/></a>

Ao longo dos anos, os autores têm criado diferentes classificações para as linguagens de programação, usando critérios diferenciados e agrupando-as sob diferentes perspectivas.

Veremos a seguir as classificações das linguagens por nível, por gerações e por paradigmas.

## Classificação por nível
A **classificação por nível** considera a proximidade da linguagem de programação com as características da arquitetura do computador ou com a comunicação com o homem.

### Linguagem de baixo nível
São linguagens que **se aproximam da linguagem de máquina**, além da própria, que se comunicam diretamente com os componentes de hardware, como processador, memória e registradores. As linguagens de baixo nível estão relacionadas à arquitetura de um computador.

São linguagens escritas usando o conjunto de instruções do respectivo processador. Ou seja, cada processador diferente (ou família de processador, como os I3, I5 e I7 da Intel) tem um conjunto de instruções específicos (instructions set).

Abaixo, a imagem ilustra a representação de uma instrução em linguagem de máquina ou binária de um processador específico. A instrução tem palavras (unidade executada pelo processador) de 16 bits, sendo 4 bits para representar a instrução (código da instrução), 6 bits para representar cada operando.

![img_05](https://user-images.githubusercontent.com/61624336/132109668-589759b2-a4ec-4a48-bb3c-728a9583c199.jpg)

<h5 align="center">Instrução em linguagem de máquina.</h5>

Imagine, agora, uma sequência de 0 e 1 para que possamos dizer ao processador cada ação que deve ser realizada conforme ilustrado abaixo.

```
0001001010001111
1010010001000010
0010101110110111
0101010000000111
```

Era de fato muito complexa a programação na linguagem de máquina, a linguagem nativa dos processadores.

Essa complexidade motivou o desenvolvimento da linguagem **Assembly**, que deixava de ser a linguagem nativa dos processadores, mas usava das instruções reais dos processadores. Assim, a instrução na linguagem Assembly precisa ser convertida para o código equivalente em linguagem de máquina.

### Exemplo
As três linhas de código na linguagem Assembly, abaixo, que move o numeral 2 para o registrador AX (linha 1), move o numeral 1 para o registrador BX (linha 2) e soma o conteúdo dos 2 registradores (linha 3).

```assembly
MOV AX, 0002

MOV BX, 0001

ADD AX, BX
```

Não chega a ser o ideal em termos de uma linguagem, que é ainda próxima da máquina, mas já foi um grande avanço em relação à memorização da sequência de 0 e 1 de uma instrução de máquina.

Linguagens de baixo nível estão distantes da língua humana (escrita).

### Linguagem de alto nível
No outro extremo das linguagens de baixo nível, estão as linguagens de alto nível, na medida em que se afastam da linguagem das máquinas e se aproximam da linguagem humana (no caso, a linguagem escrita e a grande maioria em Inglês).

<blockquote><b>Você sabia:</b> Quem programa em uma linguagem de alto nível não precisa conhecer características dos componentes do hardware (processador, instruções e registradores). Isso é abstraído no pensamento computacional.</blockquote>

As instruções das linguagens de alto nível são bastante abstratas e não estão relacionadas à arquitetura do computador diretamente. **As principais linguagens são:**

**Python, ASP, C, C++, C#, Pascal, Delphi, Java, Javascript, Go, Scala, Clojure, Lua, MATLAB, PHP e Ruby, dentre outras.**

<blockquote>

Abaixo, o mesmo código expresso acima, escrito em Assembly, porém usando variáveis, como abstração do armazenamento e codificado na linguagem Python.

<pre>
def main():
    num1 = 2
    num2 = 1
    soma = num1 + num2
</pre>
  
Abaixo, o mesmo código na linguagem C:

<pre>
int num1, num2, soma;
int main()
{
  num1=2;
  num1=1;
  soma=num1+num2;
}  
</pre>  

</blockquote>

Cada comando de uma linguagem de alto nível precisa ser convertido e equivalerá a mais de uma instrução primária do hardware. Isso significa que, numa linguagem de alto nível, o programador precisa escrever menos código para realizar as mesmas ações, além de outras vantagens, aumentando consideravelmente a sua eficiência ao programar.

<blockquote><b>Saiba mais:</b> Há uma curiosidade: C e C++ são classificados por alguns autores como linguagem de médio nível, na medida que estão próximas da linguagem humana (linguagem de alto nível), mas também estão próximas da máquina (linguagem de baixo nível), pois possuem instruções que acessam diretamente memória e registradores. Inicialmente, a linguagem C foi criada para desenvolver o sistema operacional UNIX, que até então era escrito em Assembly.</blockquote>

Outro dado que merece ser comentado é que algumas pessoas consideram a existência de linguagens de altíssimo nível, como Python, Ruby e Elixir, por serem linguagens com uma enorme biblioteca de funções e que permitem a programação para iniciantes sem muito esforço de aprendizado.

## Classificação por gerações
Outra forma de classificar as linguagens, amplamente difundida, é por **gerações**. Não há um consenso sobre as gerações, alguns consideram `5`, outros `6`. A cada geração, novos recursos facilitadores são embutidos nas respectivas linguagens.

![img_18](https://user-images.githubusercontent.com/61624336/132680831-1c2dc53c-28d5-4d2e-924d-6f57aed9e78d.jpg)

### LINGUAGENS DE 1ª GERAÇÃO (LINGUAGEM DE MÁQUINA) [baixo-nível]
A 1ª geração de linguagens é representa pela **linguagem de máquina**, nativa dos processadores.

### LINGUAGENS DE 2ª GERAÇÃO (LINGUAGEM DE MONTAGEM – ASSEMBLY) [baixo-nível]
As linguagens de segunda geração são denominadas **Assembly** e são traduzidas para a linguagem de máquina por um programa especial (montador), chamado _Assembler_. A partir dessa geração, toda linguagem vai precisar de um processo de conversão do código nela escrito, para o código em linguagem de máquina.

Acompanhe o exemplo abaixo para uma CPU abstrata. Considere a seguinte sequência de 3 instruções em linguagem Assembly:

<table>
  <tr>
    <td><b>Código em Assembly</b></td>
    <td><b>O que faz cada linha de código</b></td>
  </tr>
  <tr>
    <td><code>Mov #8, A</code></td>
    <td>Lê um valor da posição de memória 8 para o registrador A</td>
  </tr>
  <tr>
    <td><code>Mov #9, B</code></td>
    <td>Lê um valor da posição de memória 9 para o registrador B</td>
  </tr>
  <tr>
    <td><code>ADD A,B</code></td>
    <td>Soma os valores armazenados nos registradores A e B</td>
  </tr>
</table>

Em linguagem de máquina, depois de traduzidas pelo _Assembler_, as instruções poderiam ser representadas pelas seguintes sequências de palavras binárias:

<table>
  <tr>
    <td><b>Código em Assembly</b></td>
    <td><b>Código em linguagem de máquina</b></td>
  </tr>
  <tr>
    <td><code>Mov #8, A</code></td>
    <td>01000011 11001000 01100001</td>
  </tr>
  <tr>
    <td><code>Mov #9, B</code></td>
    <td>01000011 11001001 01100010</td>
  </tr>
  <tr>
    <td><code>ADD A,B</code></td>
    <td>01010100 01100001 01100010</td>
  </tr>
</table>

Houve um aumento significativo no nível de abstração, mas parte da dificuldade permanece, pois o programador, além de necessitar memorizar os **mneumônicos**, precisa conhecer a arquitetura do computador como forma de endereçamento dos registradores e memória, além de outros aspectos.

### LINGUAGENS DE 3ª GERAÇÃO (LINGUAGENS PROCEDURAIS) [nível-médio]
São as, também, linguagens de alto nível, de aplicação geral, em que uma única instrução em uma linguagem próxima a do homem pode corresponder a mais de uma instrução em linguagem de máquina.

Caracterizam-se pelo suporte a variáveis do tipo simples (caractere, inteiro, real e lógico) e estruturados (matrizes, vetores, registros), comandos condicionais, comando de iteração e programação modular (funções e procedimentos), estando alinhadas à programação estruturada.

O processo de conversão para a linguagem de máquina ficou mais complexo e ficaram a cargo dos **interpretadores** e **tradutores**. As primeiras linguagens de 3ª geração que foram apresentadas ao mercado são: **Fortran, BASIC, COBOL, C, PASCAL, dentre outras.**

Esta geração de linguagens apresenta as seguintes propriedades em comum:

- Armazenar tipos de dados estaticamente: simples, estruturados e enumerados.
- Alocar memória dinamicamente, através de ponteiros, que são posições de memória cujo conteúdo é outra posição de memória.
- Disponibilizar: estruturas de controle sequencial, condicional, repetição e desvio incondicional.
- Permitir a programação modular, com uso de parâmetros.
- Operadores: relacionais, lógicos e aritméticos.
- Ênfase em simplicidade e eficiência.

### LINGUAGENS DE 4ª GERAÇÃO (LINGUAGENS APLICATIVAS) [alto-nível]
São, também, linguagens de alto nível, com aplicação e objetivos bem específicos.

Enquanto as linguagens de 3ª geração são procedurais, ou seja, especifica-se passo a passo a solução do problema, as de 4ª geração são não procedurais. O programador especifica o que deseja fazer e não como deve ser feito.

O melhor exemplo de linguagens de 4ª geração é a **SQL** (Structured Query Language), utilizada para consulta à manipulação de banco de dados. **PostScript** e **MATLAB** são outros dois exemplos de linguagens de 4ª geração.

### LINGUAGENS DE 5ª GERAÇÃO (VOLTADAS À INTELIGÊNCIA ARTIFICIAL) [alto-nível]
São linguagens declarativas e não algorítmicas. Exemplos: **Lisp** e **Prolog**. As linguagens de 5ª geração são usadas para desenvolvimento de **sistemas especialistas** (área da IA), de **sistemas de reconhecimento de voz** e **machine learning**.

A imagem a seguir ilustra as características de cada geração.

Alguns autores classificam a 6ª geração, como uma evolução da 5ª, em que prevalecem as aplicações de **redes neurais**, uma outra vertente da **Inteligência Artificial**.

![img_17](https://user-images.githubusercontent.com/61624336/132686146-628d18c7-781f-4b65-b4d7-a979a5ede411.jpg)

<blockquote><b>Resumindo:</b>A abstração traz facilidades ao programador que cada vez menos precisa conhecer o ambiente onde a linguagem opera (composto por sistema operacional e hardware); Um comando em uma linguagem de alto nível faz mais que uma operação primária do hardware.</blockquote>

Considerando as diversas linguagens de programação existentes hoje no mercado, atendendo a propósito comuns, vamos destacar neste módulo os domínios da programação, que são seis:

- Aplicações científicas
- Aplicações comerciais
- Aplicações com Inteligência Artificial
- Programação de sistemas
- Programação para web
- Programação mobile

Na sequência, apresentaremos critérios que podem ser usados para avaliação de linguagens de programação, claro, dentro do mesmo domínio de programação.

## DOMÍNIOS DA PROGRAMAÇÃO
O computador tem sido usado para diversos fins, na ciência, nas forças armadas, nas empresas públicas e privadas, pelos profissionais liberais, pelas pessoas em seus lazeres e onde mais possa ser aplicado. Seu uso vai desde controlar robôs que fazem a montagem de automóveis em suas linhas de montagem até jogos digitais. Em função desse uso adverso, surgiram linguagens de programação com diferentes objetivos. A seguir, discutiremos as principais áreas e as respectivas linguagens de programação em destaque.

### APLICAÇÕES CIENTÍFICAS (MÁQUINAS DE CALCULAR COM ALTA PRECISÃO)
O primeiro computador, o **ENIAC**, foi desenvolvido por 3 anos e ficou pronto no ano de 1946. Sua principal finalidade eram **cálculos balísticos**. Os computadores seguintes, nas décadas de 1940 e 1950, também focaram em cálculos científicos complexos.

As linguagens de programação nessa época eram a linguagem de máquina e Assembly. Na década de 1960 surgem as primeiras linguagens de programação de alto nível, com destaque para Fortran (iniciais de **FOR**mula **TRAN**slator) e posteriormente para **ALGOL60**. As principais características dessas linguagens eram:

- Estruturas de dados simples.
- Alto volume de cálculos com aritmética de ponto flutuante (precisão).
- Preocupação com a eficiência, pois sucederam a linguagem Assembly.

### APLICAÇÕES COMERCIAIS
A segunda onda de aplicativos foi para suprir as demandas das empresas a partir de meados da década de 1950. Em 1960, surge a linguagem que seria o ícone das aplicações comerciais de computadores de grande porte, naquele momento, o **COBOL**. As linguagens de programação que apoiaram o crescimento das aplicações comerciais têm como características:

- Facilidade para produzir relatórios, fundamentais nos controles das operações contábeis, bancárias, estoque e financeiras (primeiros focos da época).
- Precisão com números decimais e ponto flutuante, para representar as altas cifras das grandes empresas, as primeiras a investirem nessas aplicações.
- Capacidade de especificar operações aritméticas comerciais.

Cabe destacar que as linguagens destinadas a aplicações comerciais ganham força com a microcomputação a partir dos anos 1980, levando as aplicações comerciais aos médios e pequenos empresários.

### APLICAÇÕES COM INTELIGÊNCIA ARTIFICIAL
As linguagens que sustentam o desenvolvimento de aplicações apoiadas na Inteligência Artificial (IA) ganham força nos dias de hoje.

A grande ruptura no pensamento computacional é que as linguagens que apoiam a IA usam a computação simbólica e não numérica, como a maioria das linguagens da época. Em 1959, surge a linguagem **Lisp**, primeira linguagem projetada para apoio à computação simbólica, primeira referência da computação funcional. **Prolog**, criada em 1977, foi a primeira linguagem para apoio da computação lógica, essência dos sistemas especialistas (sistemas que usam IA para simular o comportamento humano).

### PROGRAMAÇÃO DE SISTEMAS
A programação de sistemas cabe a linguagens de programação que tenham comandos e estruturas para acessar, diretamente, o hardware. Tais linguagens são usadas para desenvolver softwares básicos, como sistemas operacionais, tradutores e interpretadores de linguagens de programação. Antes de surgir a linguagem **C**, usada para desenvolver o sistema operacional Linux, **Assembly** era a linguagem usada para esse fim. A linguagem **C++** também é usada com essa finalidade.

### PROGRAMAÇÃO PARA WEB
Com o crescimento da internet e tecnologias adjacentes, o uso dos sistemas se desloca do ambiente desktop (domínio dos anos 1980 e 1990) para o ambiente Web.

No contexto de programação para Web, temos 2 diferentes ambientes de desenvolvimento: a **camada de apresentação**, que roda no navegador (lado cliente) e a **camada de lógica do negócio**, que roda nos servidores web (lado servidor), juntamente com a **camada de persistência**, considerando o modelo de desenvolvimento em 3 camadas (apresentação, lógica do negócio e persistência de dados).

Para a **camada de apresentação**, usa-se as linguagens HTML (linguagem de marcação) e CSS (usada em conjunto com HTML para definir a apresentação da página web), além de JavaScript (programação de scripts), no lado cliente (navegadores).

Para o desenvolvimento das camadas de lógica do negócio, as principais LP são: **C#, PHP, ASP, .NET, Java, Ruby e Python.**

### PROGRAMAÇÃO MOBILE
Considerando que hoje em dia, grande parte da população, no Brasil e no Mundo, tem acesso à internet pelo celular, cresceu vertiginosamente a quantidade de apps (aplicativos) para uso de aplicações via celular. Os apps, na verdade, são interfaces que rodam no lado cliente.

As principais (não todas) linguagens que apoiam o desenvolvimento de apps para o mundo mobile, oficialmente indicadas por seus fabricantes, são:

- Android: Java e Kotlin.
- iOS: Swift (oficial da Apple) e Objective-C (código nativo para iOS).
- Windows: C#, Visual Basic (VB), C++, HTML, CSS, JavaScript e Java.

O desenvolvimento de APP para iOS é baseado numa IDE chamada **Xcode** que permite o desenvolvimento de APP em várias linguagens, como: **C**, **C++**, **Java** e **Python**, mas oficialmente orienta o **Swift** e **Objective-C**.

A **Google**, por sua vez, tem por base o **Android SDK**, orienta a usar as linguagens **Kotlin**, **Java** e **C++**, mas as linguagens **Python**, **Shell script**, **Basic4Android**, **LiveCode** (para **iOS** e **Windows** também), **App Inventor** (não necessita conhecer programação) e **Unity** (motor para games) e **GO**, também são usadas para desenvolver app para Android.

No contexto de desenvolvimento de APP para Windows, foi lançado no Windows 8.1 e atualizado para atender também ao Windows 10, o **App Studio**, que permite a qualquer pessoa criar em poucos passos um app Windows e publicá-lo na loja.

Importante destacar que hoje existem plataformas de desenvolvimento mobile conectadas a nuvem que fomentam o desenvolvimento de apps nativos para iOS, Android e Windows.

## AVALIAÇÃO DE LINGUAGENS DE PROGRAMAÇÃO
Segundo **Sebesta** (2018) são **quatro grandes critérios** para avaliação das linguagens de programação, dentro de um mesmo domínio de programação. Cada critério é influenciado por _algumas características_ da linguagem.

### Legibilidade
Um dos critérios mais relevantes é a “facilidade com que os programas podem ser lidos e entendidos” pelas pessoas que não necessariamente participaram do desenvolvimento.

### Facilidade de escrita
O quão facilmente uma linguagem pode ser usada para desenvolver programas para o domínio do problema escolhido.

### Confiabilidade
Um programa é dito confiável se ele se comporta conforme a sua especificação, repetidas vezes.

### Custo
O custo final de uma linguagem de programação é em função de muitas de suas propriedades e características.

A tabela a seguir exibe as características da linguagem que influenciam cada um dos três principais fatores de avaliação de linguagens.

<table>
  <tr>
    <td><b align="center">Critérios</b></td>
  </tr>
  <tr>
    <td><b>Características</b></td>
    <td>Legibilidade</td>
    <td>Facilidade escrita</td>
    <td>Confiabilidade</td>
  </tr>
  <tr>
    <td>Simplicidade</td>
    <td>xxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Ortogonalidade</td>
    <td>xxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Estruturas de controle</td>
    <td>xxxxxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Tipos de dados</td>
    <td>xxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Projeto de sintaxe</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Suporte para abstração</td>
    <td>&nbsp;</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Expressividade</td>
    <td>&nbsp;</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Verificação de tipos</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Tratamento de exceções</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
  </tr>
  <tr>
    <td>Aliasing</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
    <td>xxxxxxxxxxxxxxxxxx</td>
  </tr>
</table>

<p>Características x Critérios de Avaliação de LPs</p>

## Legibilidade
Um dos critérios mais relevantes para avaliar uma linguagem de programação diz respeito à capacidade com que os programas podem ser lidos e entendidos pela sintaxe e construção da linguagem, sem considerar as possíveis influências da má programação.

As características que influenciam a legibilidade de uma linguagem de programação são:

### SIMPLICIDADE
Quanto mais simples for uma linguagem, melhor será a legibilidade do código por ela produzido. Uma linguagem com número elevado de construções básicas é mais difícil de ser aprendida do que uma que tenha poucas. Tende a ser subutilizada.

Uma segunda característica que afeta negativamente a legibilidade é a multiplicidade de recursos. Por exemplo, em Python, o programador pode incrementar uma variável, de duas formas distintas:

- `cont = cont + 1`
- `cont += 1`

Nas linguagens **C** e **Java**, ainda podemos usar para incrementar variáveis as seguintes estruturas: `++cont` e `cont++`.

Muita simplicidade pode tornar menos legíveis os códigos escritos. Na linguagem **Assembly**, a maioria das sentenças são simples, porém não são altamente legíveis devido à ausência de estruturas de controle.

Uma terceira característica que afeta negativamente a legibilidade é a sobrecarga de operadores, como por exemplo o `+`, usado para somar **inteiros**, **reais**, **concatenar cadeias de caracteres** (strings), somar **vetores** (Arrays), dentre outras construções permitidas pela linguagem.

### ORTOGONALIDADE
A **ortogonalidade** de uma linguagem refere-se a um conjunto relativamente pequeno de construções primitivas que pode ser combinado em um número, também, pequeno de maneiras para construir as estruturas de controle e de dados de uma linguagem de programação.

Em outras palavras: possibilidade de combinar, entre si, sem restrições, as construções básicas da linguagem para construir estruturas de dados e de controle.

- **Boa ortogonalidade**: Permitir, por exemplo, que haja um vetor, cujos elementos sejam do tipo registro (estrutura heterogênea).
- **Má ortogonalidade**: Não permitir que um vetor seja passado como argumento para uma rotina (procedimento ou função). Ou que uma função não possa retornar um vetor.
Uma linguagem ortogonal tende a ser mais fácil de aprender e tem menos exceções.

A **falta de ortogonalidade** leva a muitas exceções às regras da linguagem e ao excesso, o contrário (menos exceções às regras). Menos exceções implicam um maior grau de regularidade no projeto da linguagem, tornando-a mais fácil de ler, entender e aprender.

### INSTRUÇÕES DE CONTROLE
Instruções como **Goto** (desvio incondicional) limitam a legibilidade dos programas, pois essa instrução pode levar o controle do código a qualquer ponto do programa, limitando o entendimento e, consequentemente, a legibilidade do código escrito na linguagem. As **linguagens modernas** não implementam desvio incondicional, assim sendo, o projeto de estruturas de controle é menos relevante na legibilidade do que anos atrás, quando surgiram as primeiras linguagens de alto nível.

### TIPOS E ESTRUTURAS DE DADOS
A facilidade oferecida pela linguagem para definir **tipos** e **estruturas de dados** é outra propriedade que aumenta a legibilidade do código escrito. Por exemplo, uma linguagem que permita definir **registros** e **vetores**, mas não permite que um vetor tenha registros como seus elementos, terá a legibilidade afetada.

A **linguagem C** não possui o tipo de dado _lógico_ ou _booleano_. Muitas vezes, usa-se variáveis inteiras, permitindo apenas que receba os valores `0` e `1` para conteúdo, simulando o tipo booleano. Por exemplo, para localizar um elemento em uma das posições de um vetor, usa-se uma variável lógica se a linguagem permitir e, assim, teríamos a instrução `achou=false` em determinado trecho de código. Em outra linguagem que não permita o tipo de dado lógico, a instrução poderia ser `achou=0`, em que achou seria uma variável inteira. Qual das duas sentenças é mais clara a quem lê o código? A primeira, não é? `achou=false`.

### SINTAXE
A **sintaxe** tem efeito sobre a legibilidade. Um exemplo é a **restrição do tamanho** (quantidade de caracteres) para um **identificador** (tipo, variável, constante, rotina – procedimento e função), impedindo que recebam nomes significativos sobre sua utilidade. Na linguagem **Fortran**, o nome do identificador pode ser até 6 caracteres.

Outra propriedade de sintaxe que afeta a legibilidade é o uso de palavras reservadas da linguagem. Por exemplo, em **Pascal**, os blocos de instrução são iniciados e encerrados com `BEGIN-END`, respectivamente. A **linguagem C** usa chaves para _iniciar_ e _encerrar_ blocos de instruções. Já a **linguagem Python** usa a endentação obrigatória para marcar blocos de comandos, aumentando a legibilidade, naturalmente.

## Facilidade de escrita (redigibilidade)
A **facilidade de escrita** é a medida do quão fácil a linguagem permite criar programas para um domínio da aplicação.

A maioria das características que afeta a legibilidade também afeta a **facilidade de escrita**, pois se a escrita do código não flui, haverá dificuldade para quem for ler o código.

As características que influenciam na facilidade de escrita são:

### SIMPLICIDADE E ORTOGONALIDADE
Quanto mais simples e ortogonal for a linguagem, melhor sua facilidade para escrever programas. O ideal são linguagens com poucas construções primitivas.

Imagina que uma linguagem de programação possui grande número de construções. Alguns programadores podem não usar todas, deixando de lado, eventualmente, as mais eficientes e elegantes.

### EXPRESSIVIDADE
Uma linguagem de programação com boa expressividade contribui para o aumento da facilidade de escrita dos códigos.

- **Assembly**: Baixa expressividade.
- **Pascal** e **C**, boa expressividade: Ricas estruturas de controle. Exemplo: o comando `FOR` mais adequado que `WHILE` e `REPEAT` para representar lações com número fixo de vezes. Da mesma forma que o **C**, em que o `FOR` é mais indicado que o `WHILE` e `DO-WHILE`. Na **linguagem Python**, ocorre o mesmo entre os comandos `FOR` e `WHILE`.
- Na **linguagem C**, temos construções diversas para incremento de variável: `i++` é mais simples e conveniente de usar do que `i=i+1`, sendo `i`, uma **variável inteira**.
Uma linguagem expressiva possibilita escrever linhas de código de uma forma mais conveniente ao invés de deselegante.

### SUPORTE PARA A ABSTRAÇÃO
O **grau de abstração** em uma linguagem é uma propriedade fundamental para aumentar a facilidade de escrita. Abstração pode ser de:

- **Processos**, como o conceito de subprograma.
- **Dados**, como uma árvore ou lista simplesmente encadeada.

## Confiabilidade
Dizemos que um programa é **confiável** se ele se comportar conforme sua especificação, sob todas as condições, todas as vezes em que for executado.

Abaixo, alguns recursos das linguagens que exercem efeito sobre a confiabilidade de programas.

### VERIFICAÇÃO DE TIPOS
Significa **verificar**, em tempo de **compilação** ou **execução**, se existem erros de tipo. Por exemplo, atribuir um valor booleano a uma variável do tipo inteira, vai resultar em erro. As linguagens fortemente tipadas, em tempo de compilação, como **Python** e **Java**, tendem a ser mais confiáveis, pois apenas valores restritos aos tipos de dados declarados poderão ser atribuídos e diminuem os erros em tempo de execução. Linguagens, como **C**, em que não é verificado se o tipo de dado do argumento é compatível com o parâmetro, em tempo de compilação, podem gerar erros durante a execução, afetando a confiabilidade. A verificação de tipos em tempo de compilação é desejável, já em tempo de execução é dispendiosa (mais lenta e requer mais memória), e mais flexível (menos tipada).

### TRATAMENTO DE EXCEÇÃO
O **tratamento de exceção** em uma linguagem de programação garante a correta execução, aumentando a confiabilidade. As linguagens **Python**, **C++** e **Java** possuem boa capacidade de tratar exceções, ao contrário da **linguagem C**. A linguagem deve permitir a identificação de eventos indesejáveis (estouro de memória, busca de elemento inexistente, overflow etc.) e especificar respostas adequadas a cada evento. O **comportamento do programa** torna-se previsível com a possibilidade de tratamento das exceções, o que tende a aumentar a confiabilidade do código escrito na linguagem de programação.

### ALIASING (APELIDOS)
**Aliasing** é o fato de ter dois ou mais nomes, referenciando a mesma célula de memória, o que é um recurso perigoso e afeta a confiabilidade. Restringir Aliasing é prover confiabilidade aos programas.

### LEGIBILIDADE E FACILIDADE DE ESCRITA
Ambos influenciam a confiabilidade. A **legibilidade** afeta tanto na fase de codificação como na fase de manutenção. Programas de difícil leitura são difíceis de serem escritos também.

Uma linguagem com boa legibilidade e facilidade de escrita gera códigos claros, que tendem a aumentar a confiabilidade.

## Custo
O **custo** de uma linguagem de programação varia em função das seguintes despesas: de **treinamento**, de **escrita do programa**, do **compilador**, de **execução do programa**, de **implementação da linguagem** e o de **manutenção do código**.

<table>
  <tr>
    <td><b>Custo de</b></td>
    <td><b>Características</b></td>
  </tr>
   <tr>
    <td>Treinamento</td>
    <td>Custo de Treinamento para programadores varia em função da expertise do programador, simplicidade e ortogonalidade da linguagem; F (simplicidade de escrita, ortogonalidade, experiência do programador).</td>
  </tr>
  <tr>
    <td>Escrever programa</td>
    <td>Custo para escrever programas na linguagem varia em função da facilidade de escrita. F(Facilidade de escrita).</td>
  </tr>
  <tr>
    <td>Compilar o programa</td>
    <td>Esse custo varia em função do custo de aquisição do compilador, hoje minimizado, em linguagens open source, como é o caso do Python. F (custo de aquisição do compilador).</td>
  </tr>
  <tr>
    <td>Executar o programa</td>
    <td>Custo para executar programas, varia em função do projeto da linguagem. F (Projeto da linguagem).</td>
  </tr>
   <tr>
    <td>Implementar a linguagem</td>
    <td>A popularidade da LP vai depender de um econômico sistema de implementação. Por exemplo, Python e Java possuem compiladores e interpretadores gratuitos.</td>
  </tr>
  <tr>
    <td>Confiabilidade</td>
    <td>O custo da má confiabilidade: se um sistema crítico falhar, o custo será elevado. Exemplos: sistema de controle de consumo de água e sistemas de usina nuclear.</td>
  </tr>
  <tr>
    <td>Manutenção</td>
    <td>Custo de manutenção: depende de vários fatores, mas principalmente da legibilidade, já que a tendência é que a manutenção seja dada por pessoas que não participaram do desenvolvimento do software.</td>
  </tr>
</table>

Os custos em treinamento e de escrever o programa podem ser minimizados se a linguagem oferecer bom ambiente de programação.

<blockquote>Python é uma linguagem com alta legibilidade, facilidade de escrita, além de confiável. Seu custo não é elevado, pois além de ser open source, é fácil de aprender.</blockquote>

<blockquote><b>ATENÇÃO!</b> Existem outros critérios, como por exemplo a portabilidade ou a capacidade que os programas têm de rodarem em ambientes diferentes (sistema operacional e hardware), o que é altamente desejável. A reusabilidade, ou seja, o quanto um código pode ser reutilizado em outros programas ou sistemas aumenta o nível de produtividade da linguagem. Além da facilidade de aprendizado, que é fortemente afetada pela legibilidade e facilidade de escrita.</blockquote>

## Agrupamento por paradigmas
O **agrupamento por paradigmas** é outra forma de classificar as linguagens de programação. Um paradigma agrupa linguagens com características semelhantes que surgiram em uma mesma época.

A imagem a seguir ilustra os **cinco paradigmas** nos quais as linguagens de programação são classificadas. Esses paradigmas são agrupados em **Imperativos** e **Declarativos**, de acordo com a forma com que os programas são estruturados e descritos.

![img_07](https://user-images.githubusercontent.com/61624336/132958354-b72162bf-4ede-40b0-86a7-0d14429cdaeb.jpg)

## PARADIGMA IMPERATIVO
O **paradigma imperativo** agrega três paradigmas: **estruturado**, **orientado a objeto** e **concorrente**, os quais possuem em comum o fato de especificarem passo a passo o que deve ser feito para a solução do problema. As **linguagens do paradigma imperativo** são dependentes da arquitetura do computador, pois especificam em seus programas como a computação é realizada.

Vamos explicar as características de cada um dos paradigmas do **subgrupo Imperativo**.

### Paradigma estruturado
Caracteriza as principais linguagens de programação da década de 1970 e 1980 que seguiram os princípios da programação estruturada:

1. Não usar desvios incondicionais (**Goto**, característico de linguagens como **BASIC** e versões iniciais do **COBOL**).
2. Desenvolver programas por refinamentos sucessivos (metodologia top down), motivando o desenvolvimento de rotinas (procedimentos e funções) e a visão do programa partindo do geral para o particular, ou seja, o programa vai sendo refinado à medida que se conhece melhor o problema e seus detalhes.
3. Desenvolver programas usando três tipos de estruturas: sequenciais, condicionais e repetição.
4. Visando eficiência, o paradigma estruturado baseia-se nos princípios da arquitetura de Von Neumann, onde:
  - Programas e dados residem, na memória (durante a execução).
  - Instruções e dados trafegam da memória para CPU e vice-versa.
  - Resultados das operações trafegam da CPU para a memória.

As **linguagens Pascal** e **C** caracterizam bem esse paradigma. A **linguagem Python**, multiparadigma, tem o estilo básico do paradigma estruturado.

### Paradigma orientado a objetos
Com o crescimento do tamanho do código e complexidade dos programas, o paradigma estruturado começou a apresentar limitações nos sistemas que passaram a ter dificuldade de manutenção e reuso de programas e rotinas padronizadas.

A orientação a objetos surge como solução a esses problemas, permitindo, através de propriedades como **abstração**, **encapsulamento**, **herança** e **polimorfismo**, **maior organização**, **reaproveitamento** e **extensibilidade de código** e, consequentemente, **programas mais fáceis** de serem escritos e mantidos.

<blockquote>O principal foco desse paradigma foi possibilitar o desenvolvimento mais rápido e confiável.</blockquote>

As **classes** são abstrações que definem uma estrutura que encapsula dados (chamados de **atributos**) e um conjunto de operações possíveis de serem usados, chamados **métodos**. Os **objetos** são instâncias das classes.

<blockquote><b>Exemplo:</b> Por exemplo, a classe ALUNO encapsula um conjunto de dados que os identifiquem: matrícula, nome, endereço (rua, número, complemento, bairro, estado e CEP) e um conjunto de métodos: Incluir Aluno, Matricular Aluno, Cancelar Matrícula, dentre outros.</blockquote>

O **paradigma orientado a objetos** (OOP - POO), por sua vez, usa os conceitos do paradigma estruturado na especificação dos comandos de métodos. Por isso, é considerado uma evolução do paradigma estruturado.

<blockquote><b>Atenção:</b> Python, Smalltalk, C++, Java, Delphi (oriundo do Object Pascal) são linguagens que caracterizam o paradigma orientado a objetos. Python é orientado a objeto, pois tudo em Python é objeto, permitindo a declaração de classes encapsuladas, além de possibilitar herança e polimorfismo.</blockquote>

### Paradigma concorrente
Caracterizado quando processos executam simultaneamente e concorrem aos recursos de hardware (processadores, discos e outros periféricos), características cada vez mais usuais em sistemas de informação.

O **paradigma concorrente** pode valer-se de apenas um processador ou vários.

- **Processador**: Os processos concorrem ao uso do processador e recursos.
- **Vários processadores**: Estamos caracterizando o paralelismo na medida em que podem executar em diferentes processadores (e de fato, ao mesmo tempo), os quais podem estar em uma mesma máquina ou distribuídos em mais de um computador. 

<blockquote>Ada e Java são as linguagens que melhor caracterizam esse paradigma, possibilitando suporte à concorrência.</blockquote>

<blockquote><b>Você sabia:</b> Ao contrário de Go, Python não foi originalmente projetada com foco em programação concorrente, muito menos paralela. 
  
O modo tradicional de programar concorrência em Python -- threads -- é limitado no interpretador padrão (CPython) por uma trava global (a GIL), que impede a execução paralela de threads escritas em Python. Isso significa que threads em Python são úteis apenas em aplicações I/O bound (Aplicações I/O bound são aquelas em que há predomínio de ações de entrada e saída de dados.) – em que o gargalo está no I/O (entrada e saída), como é o caso de aplicações na Internet.</blockquote>

### PARADIGMA DECLARATIVO
Diferentemente do paradigma imperativo, no **declarativo** o programador diz o que o programa deve fazer (qual a tarefa), ao invés de descrever como o programa deve fazer. O programador declara, de forma abstrata, a solução do problema.

Essas linguagens não são dependentes de determinada arquitetura de computador. As variáveis são **incógnitas**, tal qual na Matemática e não células de memória.

<blockquote>O paradigma declarativo agrega os paradigmas funcional e lógico.</blockquote>

Vamos explicar as características de cada um.

### Paradigma funcional
Abrange linguagens que operam tão somente funções que recebem um conjunto de valores e retornam um valor. O resultado que a função retorna é a solução do problema (foca o processo de resolução de problemas).

O programa resume-se em chamadas de **funções**, que por sua vez **podem usar outras funções**. Uma função pode invocar outra, ou o resultado de uma função pode ser argumento para outra função. Usa-se também chamadas **recursivas de funções**.

Naturalmente, esse paradigma gera **programas menores** (pouco código).

<blockquote>Linguagens típicas desse paradigma são: LISP, HASKELL e ML.</blockquote>

**LISP** é a **LP funcional** mais usada, especialmente em programas que usem os conceitos de Inteligência Artificial (sistemas especialistas, processamento de linguagem natural e representação do conhecimento), devido à facilidade de interpretação recursiva.

Exemplo: O código abaixo implementa em Python uma função que calcula quantos números inteiros existem de 0 a n.

```python
def conta_numeros(n):
  p = 0
  for num in range(n+1):
    if num%2 == 0:
     p += 1
  return p
```

Abaixo, o mesmo código usando o conceito de função recursiva. Repare que a função de nome conta_numeros chama ela mesma em seu código (isso é a recursão).

```python
def conta_numeros(n):
    if n == 0: return 1 # 0 é par
    elif n%2 == 0: return 1 + conta_numeros(n-1)
    else: return conta_numeros(n-1)
```
**Atenção:** Python não é uma linguagem funcional nativa, seria exagerado afirmar isso, porém sofreu influência desse paradigma ao permitir: **recursividade**, **uso de funções anônimas**, com a **função lambda**, dentre outros recursos, além, claro, de ser uma linguagem com enorme biblioteca de funções.

### Paradigma lógico
Um **programa lógico** expressa a solução da maneira como o ser humano raciocina sobre o problema: **baseado em fatos**, derivam-se **conclusões** e **novos fatos**.

Quando um novo questionamento é feito, através de um mecanismo inteligente de inferência, deduz novos fatos a partir dos existentes.

<blockquote>A execução dos programas escritos em linguagens de programação lógica segue, portanto, um mecanismo de dedução automática (máquina de inferência), sendo Prolog a linguagem do paradigma lógico mais conhecida.</blockquote>

O **paradigma lógico** é usado no desenvolvimento de linguagens de **acesso a banco de dados**, **sistemas especialistas** (IA), **tutores inteligentes** etc.

Python não tem características para implementar programas que atendam ao paradigma lógico.

## Métodos de implementação das linguagens
Todo programa, a menos que seja escrito em linguagem de máquina, o que hoje em dia está totalmente fora dos propósitos, precisará ser convertido para linguagem de máquina antes de ser executado.

<blockquote>Essa conversão precisa de um programa que receba o código-fonte escrito na linguagem e gere o respectivo código em linguagem de máquina.

Esse programa, que fará a tradução do código-fonte em linguagem de máquina, é que vai determinar como os programas são implementados e como vão executar.</blockquote>

Existem duas formas de realizar essa conversão: **tradução** e **interpretação**. É fundamental que se saiba e se entenda qual o processo de conversão usado na respectiva linguagem de programação.

## TRADUÇÃO
Nesse processo de _conversão_, o programa escrito em uma linguagem de alto nível é traduzido para uma versão equivalente em linguagens de máquina, antes de ser executado. O processo de tradução pode ser executado em várias fases, que podem ser combinadas e executadas em simultaneidade. O **processo de tradução** é erroneamente chamado de **compilação**, que na verdade é uma de suas fases.

As fases que compõem o tradutor, ou seja, iniciando na leitura do **programa-fonte** (linguagem de alto nível) e terminando com a geração do código executável (entendido pela máquina), são: **Compilação**, **Montagem**, **Carga** e **Ligação**. A imagem abaixo ilustra o processo de tradução.

![Sem Título-1](https://user-images.githubusercontent.com/61624336/132996547-664e672c-c757-4ffc-b434-ca4ccadc9403.png)

### Compilador
O **compilador** (detalhes adiante) analisa o código-fonte e estando tudo OK, o converte para um código **Assembly** (da máquina hospedeira).

### Montador
O **montador** traduz o código Assembly para o código de máquina intermediário (Código-objeto), que não é executável pelo computador. O código-objeto pode ser relocável, ou seja, carregado em qualquer posição de memória ou absoluto, carregado em um endereço de memória específico. A opção relocável é mais comum e mais vantajosa.

### Ligador
O **Ligador** liga (ou linka) o código-objeto relocável com as rotinas bibliotecas (outros objetos, rotinas do SO, DLLs etc.), usadas nos códigos-fontes. Essa ligação gera o código executável.

### Carregador
O **carregador** é que torna o código-objeto em relocável.

## Compilador
É o elemento central do processo de tradução, responsável pelo custo de compilação, visto no modulo anterior. Em função dessa relevância, muitas vezes o processo como um todo é erroneamente chamado de **compilação**, uma vez que o ambiente integrado das linguagens atuais já integra **todos os componentes** (montador, compilador, carregador e ligador) quando necessário.

O projeto da linguagem tem no compilador a sua figura central.

A imagem abaixo ilustra os componentes envolvidos na compilação de um programa fonte:

![img_29](https://user-images.githubusercontent.com/61624336/132996706-1aed9b24-f959-4421-9152-c7166da73bc6.jpg)

Abaixo, vamos entender cada fase da compilação:

### ANÁLISE LÉXICA
Identifica os **tokens** (elementos da linguagem), desconsidera partes do código-fonte, como espaços em branco e comentários e gera a Tabela de símbolos, com todos esses tokens, que são identificadores de variáveis, de procedimentos, de funções, comandos, expressões etc.

### ANÁLISE SINTÁTICA
Verifica se os tokens são estruturas sintáticas (exemplos: expressões e comandos) válidas, aplicando as regras gramaticais definidas no projeto da linguagem.

### ANÁLISE SEMÂNTICA
Verifica se as estruturas sintáticas possuem sentido. Por exemplo, verifica se um identificador de variável ou constante é usado adequadamente, se operandos e operadores são compatíveis. Monta a árvore de derivação conforme ilustrado abaixo para formação das expressões.

![img_08](https://user-images.githubusercontent.com/61624336/132999136-811e1b2d-097c-4d6a-b5bb-f19d69a0e45b.jpg)

### GERADOR DE CÓDIGO INTERMEDIÁRIO, OTIMIZADOR DE CÓDIGO E GERADOR DE CÓDIGO
Em distintas fases geram o **programa-alvo** ou **programa-objeto**.

- Gerador de código intermediário, que contém toda a informação para gerar o código-objeto.

Na imagem a seguir, o **código intermediário** está representado no último quadro – código em Assembly:

![img_09](https://user-images.githubusercontent.com/61624336/132999241-63d067b4-dded-4b83-ac9e-1b19f779be70.jpg)

- O otimizador tem por objetivo eliminar redundâncias do código intermediário e tornar o objeto mais enxuto e eficiente.

### TRATADOR DE ERROS
Em todas as fases existem erros: **léxicos**, **sintáticos** e **semânticos**. Um bom compilador apresenta uma boa tratativa de erros.

### GERENCIADOR DA TABELA DE SÍMBOLOS
Mantém a tabela de símbolos atualizada a cada passo do compilador.

<blockquote>
  <b>Atenção:</b>
As principais características dos compiladores são:

  <li>Gerar código-objeto mais otimizado.</li>
  <li>Execução mais rápida que o processo de interpretação.</li>
  <li>Traduz um mesmo comando apenas uma vez, mesmo que usado em várias partes do programa – tanto iterações como repetição de código.</li>
  <li>Processo de correção de erros e depuração é mais demorado.</li>
  <li>A programação final (código-objeto) é maior.</li>
<li>O programa-objeto gerado é dependente de plataforma — processador + SO (Sistema Operacional) — necessitando de um compilador diferente para cada família de processadores/sistema operacional.</li>
</blockquote>

### INTERPRETAÇÃO
A imagem abaixo ilustra o simples processo de Interpretação:

![img_10](https://user-images.githubusercontent.com/61624336/132999762-bec5a648-a708-4b4e-8fcd-e03c71c36627.jpg)

Na conversão por interpretação, cada comando do programa-fonte é traduzido e executado (um a um) imediatamente. O interpretador traduz um comando de cada vez e chama uma rotina para completar a sua execução.

O interpretador é um programa que executa repetidamente a seguinte sequência:

<pre>1 - Obter a próxima instrução do código-fonte. >> 2 - Interpretar a instrução (conversão para comandos em linguagem de máquina). >> 3 - Executar a instrução.</pre>

Perceba que o procedimento, acima descrito, é bastante similar àquele executado por computadores que implementam a máquina de Von Neumann, na execução de uma instrução, conforme a seguir:

- Obter a próxima instrução.
- CI → endereço da próxima instrução. CI = contador de instruções.
- RI → instrução a ser executada. RI = registrador de instruções.
- Decodificar a instrução.
- Executar a instrução.

### PRINCIPAIS CARACTERÍSTICAS DO INTERPRETADOR
Dentre as principais características do interpretador, podemos citar:

- Atua a cada vez que o programa precisa ser executado.
- Não produz programa-objeto persistente.
- Não traduz instruções que nunca são executadas.
- O resultado da conversão é instantâneo: resultado da execução do comando ou exibição de erro – interpretador puro.
- Útil ao processo de depuração de código devido a mensagens de erros em tempo de execução (tanto análise sintática como semântica).
- Execução mais lenta do que outros processos de tradução (compilação), pois toda vez que o mesmo programa é executado, os mesmos passos de interpretação são executados.
- Consome menos memória.
- O Código-fonte é portátil.
  - Não é gerado um código de máquina.
  - Pode executar o comando em alto nível diretamente ou gerar um código intermediário, que neste caso é interpretado por uma máquina virtual (VM). – Interpretador híbrido.
  - Se a máquina virtual foi desenvolvida para diferentes plataformas, temos a portabilidade do código-fonte. Este é o caso da linguagem Java.

## Tradução x interpretação

|            | Vantagens | Desvantagens |
| ---------- | --------- | ------------ |
| Tradutores |	1. Execução mais rápida 2. Permite estruturas de programas mais complexas. 3. Permite a otimização de código. | 1. Várias etapas de conversão. 2. Programação final é maior, necessitando de mais memória para sua execução. 3. Processo de correção de erros e depuração é mais demorado. |
| Interpretadores | 1. Depuração mais simples. 2. Consome menos memória. 3. Resultado imediato do programa (ou parte dele). | 1. Execução do programa é mais lenta. 2. Estruturas de dados demasiado simples. 3. Necessário fornecer o código fonte ao utilizador. |

## SISTEMAS HÍBRIDOS
O **processo híbrido** de implementação de uma linguagem de programação combina a execução rápida dos tradutores (compiladores) com a portabilidade dos interpretadores. O segredo é a geração de um código intermediário mais facilmente interpretável, porém não preso a uma plataforma (SO/Hardware).

Esse código intermediário não é específico para uma plataforma, possibilitando aos programas já compilados para esse código serem portados em diferentes plataformas, sem alterar e nem fazer nada. Para cada plataforma desejada devemos ter um interpretador desse código.

<blockquote>Duas importantes linguagens implementaram essa solução, com diferentes formas usando máquinas virtuais: <b>Python</b> e <b>Java</b>.</blockquote>

## Sistema de implementação de Python
<div align="center"><a href="https://www.jython.org/"><img src="https://media.geeksforgeeks.org/wp-content/uploads/python_working.png"></a></div><br \>

**Python** usa um sistema híbrido, uma combinação de interpretador e tradutor (compilador). O **compilador** converte o código-fonte Python em um código intermediário, que roda numa máquina virtual, a **PVM** (Python Virtual Machine).

## Jython
<div align="center"><a href="https://www.sprezzatech.com/wiki/images/1/10/Jython.svg" height="177"></a></div><br \>

<blockquote><b>Comentário:</b> Curioso saber que o código Python pode ser traduzido em <b>Bytecode Java</b> usando a implementação <b>Jython</b>.</blockquote>

## O interpretador
O **interpretador** converte para código de máquina, em tempo de execução. O **compilador** traduz o programa inteiro em código de máquina e o executa, gerando um arquivo que pode ser executado. O compilador gera um relatório de erros e o interpretador interrompe o processo na medida em que localiza um erro.

## CPython
<div align="center"><img src="https://upload.wikimedia.org/wikipedia/en/c/ce/Cython-logo.svg" height="177"></div><br \>

**CPython** é uma **implementação** da linguagem Python, um pacote com um compilador e um interpretador Python (Máquina Virtual Python - PVM), além de outras ferramentas para programar em Python.

![cpython1](https://user-images.githubusercontent.com/61624336/136308856-241076e0-15b9-475d-a561-016c75fd2731.png)

## VirtualEnv em Python
O **virtualenv** do Python é utilizado para isola a versão do Python e das bibliotecas usadas em um determinado sistema. Caso você não utilize o virtualenv, todas as bibliotecas necessárias para seu sistema seriam instaladas no ambiente do sistema operacional.

Em resumo, 

# 🐍 The History of Python language 🐍
<div align="center"><img src="https://symbols.getvecta.com/stencil_92/75_python-vertical.6c7f1f8721.svg" height="277"></div><br \>

Dentre as diversas linguagens de programação que existem, **Python** é considerada uma das principais. Por sua simplicidade de aprendizado, ela tem sido utilizada em diversos cursos universitários como a primeira linguagem com que os alunos têm contato ao programar. Atualmente, conta com ampla participação da comunidade, além de ter seu desenvolvimento aberto e gerenciado pela organização sem fins lucrativos Python Software Foundation.

Recentemente, a _IEEE Computer Society_ classificou-a como a linguagem mais indicada para aprender em 2020. Isso se deve à sua eficiência no desenvolvimento de **machine learning**, **inteligência artificial**, **ciência**, **gestão** e **análise de dados**.

<div align="center"><img height="177" src="https://symbols.getvecta.com/stencil_296/27_python-bivittatus-burmese-python.ef91774c2c.svg"/></div><br \>

**Python** é uma linguagem de programação de alto nível, que permite ao programador utilizar instruções de forma intuitiva, tornando seu aprendizado mais simples do que o aprendizado de uma linguagem de baixo nível.

Nas linguagens de baixo nível, o programador precisa se expressar de forma muito mais próxima do que o dispositivo “entende”, levando naturalmente a um distanciamento da linguagem utilizada para comunicação entre duas pessoas.

A classificação das linguagens em paradigmas permite que entendamos qual é o melhor deles para solucionar determinado problema e, a partir daí, escolher a linguagem de programação (pertencente a esse paradigma) mais adequada, conforme características e especificidades do contexto em que se aplica o problema.

A linguagem Python foi escolhida como instrumento para o desenvolvimento desta disciplina, pois além de ser multiparadigma (possibilita escrever programas em diferentes paradigmas) e de uso geral, vem se destacando e sendo cada vez mais utilizada entre os novos desenvolvedores por vários motivos:

- Facilidade de aprendizado;
- Boa legibilidade de código;
- Boa facilidade de escrita;
- Produtividade e confiabilidade.
- Possui, ainda, comunidade de desenvolvedores crescente e vasta biblioteca, repleta de funções, aplicada a diversas áreas da ciência, assim como o crescente números de frameworks desenvolvidos para a linguagem.

<div align="center"><img height="127" src="https://fanart.tv/fanart/tv/75853/hdtvlogo/monty-pythons-flying-circus-5176132ff29d3.png"/></div><br \>

<p>Surgiu em 1989, criado por <a href="https://github.com/gvanrossum">Guido Van Rossum</a>, em Amsterdã, na Holanda. A origem do nome foi inspirado na comédia inglesa "<i>Monty Python and the Flying Circus</i>", na década de 1970. No início dos anos 1990 e desde então tem aumentado sua participação no mundo da programação. Permite uma programação fácil e clara para escalas pequenas e grandes, além de enfatizar a legibilidade eficiente do código, notadamente usando espaços em branco significativos.
 
### Características da Linguagem Python
A linguagem **Python** é uma linguagem de programação, com características interessantes:

  - É **interpretada** e **compilada**, ou seja, o interpretador Python executa o código fonte diretamente, traduzindo cada trecho para instruções de máquina;
  - É de **alto nível**, ou seja, o interpretador se vira com detalhes técnicos do computador. Assim, desenvolver um código mais simples do que em linguagem de baixo nível, nas quais o programador deve se preocupar com detalhes da máquina;
  - É de propósito geral, ou seja, podemos usar Python para desenvolver programas em diversas áreas. Ao contrário de linguagens de domínio específico, que são especializados e atendem somente a uma aplicação específica;
  - Tem **tipos dinâmicos**, ou seja, o interpretador faz a magia de descobrir o que é cada variável;
  - É **multiparadigma**, apesar de suportar perfeitamente o paradigma de programação estruturada, Python também suporta programação orientada a objetos, tem características do paradigma funcional, com o amplo uso de bibliotecas, assim como permite recursividade e uso de funções anônimas.
  - É **interativa**, permite que os usuários interajam com o interpretador Python diretamente para escrever os programas, utilizando o prompt interativo. Esse prompt fornece mensagens detalhadas para qualquer tipo de erro ou para qualquer comando específico em execução, suporta testes interativos e depuração de trechos de código.
  - É **híbrida** quanto ao método de implementação. Python usa uma abordagem mista para explorar as vantagens do interpretador e do compilador. Assim como Java, utiliza o conceito de máquina virtual, permitindo a geração de um código intermediário, mais fácil de ser interpretado, mas que não é vinculado definitivamente a nenhum sistema operacional.
  - É **portável**, tem a capacidade de rodar em uma grande variedade de plataformas de hardware com a mesma interface. Ele roda perfeitamente em quase todos os sistemas operacionais, como **Windows**, **Linux**, **UNIX**, e **Mac OS**, sem nenhuma alteração.
  - É **extensível**, permite que os programadores adicionem ou criem módulos e pacotes de baixo nível / alto nível ao interpretador Python. Esses módulos e pacotes de ferramentas permitem que os desenvolvedores tenham possibilidades amplas de colaboração, contribuindo para a popularidade da linguagem.
  - **Suporta bancos de dados**, por ser uma linguagem de programação de uso geral, Python suporta os principais sistemas de bancos de dados. Permite escrever código com integração com **MySQL**, **PostgreSQL**, **SQLite**, **ElephantSQL**, **MongoDB**, entre outros.
  - **Suporta interface com usuário**, permite escrever código de tal maneira que uma interface do usuário para um aplicativo possa ser facilmente criada, importando bibliotecas como **Tkinter**, **Flexx**, **CEF Python**, **Dabo**, **Pyforms** ou **PyGUI wxPython**, **PyQT**, **Kivy**.
  - Pode ser usado como **linguagem de script**. Permite fácil acesso a outros programas, podendo ser compilado para **bytecode** a fim de criar aplicativos grandes.
  - Permite **desenvolvimento de aplicações Web**. Devido à escalabilidade já citada, Python oferece uma variedade de opções para o desenvolvimento de aplicativos Web. A biblioteca padrão do Python incorpora muitos protocolos para o desenvolvimento da web, como **HTML**, **XML**, **JSON**, **processamento de e-mail**, além de fornecer base para **FTP**, **IMAP** e outros **protocolos da Internet**.
  - Permite criação de **aplicações comerciais**. É desenvolvido sob uma licença de código aberto aprovada pela **OSI**, tornando-o livremente utilizável e distribuível, mesmo para uso comercial.
  
Por essas e várias outras características, o Python se torna uma linguagem simples, bela, legível e amigável. É uma linguagem muito utilizada por diversas empresas como Wikipédia, Google, Yahoo!, CERN, NASA, Facebook, AMAZON, Instagram, Spotify, Bitorrent Inc, Django e Dropbox.</p>  

<ul>
 <li>Orientada a objetos com uma semântica dinâmica;</li>
 <li>Possui licença compatível com Software livre;</li>
 <li>Linguagem de altíssimo nível (VHLL);</li>
 <li>Tipagem dinâmica;</li>
 <li>Multiparadigma (POO, funcional e procedural);</li>
 <li>Aumenta a produtividade do desenvolvedor;</li>  
 <li>A implementação oficial do Python é mantida pela PSF (Python Software Foundation) é escrita em C, e por isso, é também conhecida como CPython.</li>  
</ul>
<p>Para a plataforma Windows, basta executar o instalador. Para outras plataformas, como em Linux, geralmente o Python já faz parte do sistema, porém em alguns casos pode ser necessário compilador e instalar o interpretador a partir dos arquivos fonte.</p>
<ul>
 <li>Multiplataforma;</li>
 <li>Batteries Included;</li>
 <li>Livre;</li>
 <li>Organizada;</li>
 <li>Orientada a Objetos;</li>
 <li>Muitas Bibliotecas;</li>  
</ul>

### Principais áreas de atuação com a linguagem Python
<li>IA - Inteligência Artificial</li>
<li>Machine Learning</li>
<li>IoT - Internet das Coisas</li>
<li>Big Data</li>
<li>Data Analysis</li>
<li>Data Science</li>
<li>Computação 3D</li>
<li>Biotecnologia</li>
<li>Desenvolvimento Web - (Back-end)</li>
<li>Cybersecurity</li>
<li>Game Development</li>
<li>Mobile Development</li>
<li>Desktop Development</li>
<li>DevOps</li>
<li>Automação</li>
<li>Estudos científicos como: Geologia, Astronomia, Física, Química, Matemática e etc</li>

<hr>

# 🐍 Python Programming 🔢
<a href="https://github.com/IsaacAlves7/python-programming"><img src="https://br.renatocandido.org/wp-content/uploads/2020/10/7-python-code-examples-for-everyday-use-1200x350-c-default.jpg" heigth="177"/></a>

Vamos focar nos principais fundamentos para programar na linguagem python.

## UTILITÁRIOS E MÓDULOS
Apenas como exemplo, na área de Console clique no botão **Python Console**. No prompt interativo `>>>` que se abrirá, digite `x = 5` e pressione a tecla [ENTER] ou [RETURN] do seu teclado. Observe na figura 2 que, na área Árvore de exibição de variáveis, agora fica disponível a informação que a variável `x` é do tipo `int` e tem o valor `5`.

![figura02](https://user-images.githubusercontent.com/61624336/133014438-1af0799c-dc1a-4d2b-bfcb-bd1bbb544a0b.png)

Não se preocupe ainda com o conceito de variável, nem com o seu tipo. Veremos tudo isso com detalhes nos próximos módulos deste tema.

O utilitário **dir** apresenta todos os atributos e métodos disponíveis para determinado tipo de dado. No prompt interativo `>>>`, digite dir(x) e pressione a tecla [ENTER] ou [RETURN] do seu teclado.

No prompt interativo `>>>`, digite `dir(x)` e pressione a tecla [ENTER] ou [RETURN] do seu teclado.

![figura03](https://user-images.githubusercontent.com/61624336/133014701-4115d1d5-dac0-4260-81cf-6df3e3723127.png)

O utilitário `help` apresenta a documentação relativa a determinado tipo de dado. Caso você tenha alguma dúvida sobre o que é possível fazer com determinado tipo, os utilitários **dir** e **help** podem ser úteis.

## BLOCOS
Em **Python**, os **blocos** são definidos pela **indentação**. Diferente de **C** e **Java**, que usam as chaves `{` e `}` para delimitar os blocos, em Python todos os blocos são iniciados com o símbolo `:` (dois pontos) na linha superior e representados pelo acréscimo de 4 (quatro) espaços à esquerda. Sem se preocupar por enquanto com o significado das expressões `for`, `if`, `else` ou `range`, observe abaixo:

~~~python
a = 0
for i in range(30):
    if a%2 == 0:
    a += 1
    continue
else:
    if a % 5 == 0:
        break
    else:
        a += 3
print(a)
~~~

**Linha 1**
Está mais à esquerda, assim como as linhas 2 e 11.

**Linha 2**
Todas as linhas de 3 a 10 estão dentro do bloco do for da linha 2.

**Linha 3**
Observe que a linha 3 tem um if abrindo um bloco, dentro do qual estão as linhas 4 e 5.

**Linha 6**
Por sua vez, a linha 6 tem um else abrindo outro bloco, composto pelas linhas de 7 a 10. Os blocos do if (linha 3) e do else (linha 6) estão no mesmo nível.

**Linha 7**
Mostra outro if abrindo outro bloco – composto apenas pela linha 8 – que está no mesmo nível do bloco do else da linha 9 – composto apenas pela linha 10.

**Linha 11**
Como a linha 11 está no mesmo nível da linha 2, ela não faz parte do bloco do for.

## COMENTÁRIOS
Em Python, os **comentários** podem ser de **uma linha** ou de **várias linhas**. A tabela 1 mostra as formas de limitar um comentário, além de comparar essas formas em **Python** e **C**.

|            | Python | C |
| ---------- | --------- | ------------ |
| Comentários de 1 linha |	Iniciados com `#` | Iniciados com `//` |
| Comentários de várias linhas | Limitados por `“””` (três aspas duplas) no início e no fim	 | Iniciados com `/*` e encerrados com `*/` |

<blockquote>#️⃣ <b>ATENÇÃO:</b> É importante lembrar que os comentários não são instruções a serem executadas. Então, você pode escrever de forma simples e objetiva, sem obedecer às regras de sintaxe da linguagem.</blockquote>

## BOAS PRÁTICAS DE PROGRAMAÇÃO
Ao começar sua jornada como programador, é importante perceber que existem algumas práticas que não são obrigatórias, mas podem ajudar muito no seu aprendizado. Além disso, podem permitir que você corrija mais rapidamente erros que podem surgir no futuro e tornam seu código mais fácil de ser compreendido por outro programador, favorecendo o trabalho em equipe. Vamos conhecer algumas delas:

- Uma prática muito importante é utilizar comentários no seu programa, explicando o que aquele trecho resolve.

- Uma característica marcante da comunidade de desenvolvedores Python é manter uma lista de propostas de melhorias, chamadas **PEP** (Python Enhancement Proposals). Dentre as PEPs, destaca-se a **PEP8**, que estabelece um guia de estilo de programação.

## Variáveis em Python
As **variáveis** são abstrações para endereços de memória que permitem que os programas fiquem mais fáceis de codificar, entender e depurar. Podemos entender que ao nomear uma variável com o identificador `x`, determinado espaço em memória passará a ter esse apelido. Em outras palavras, será possível acessar esse espaço de memória sabendo o seu apelido e, consequentemente, recuperar o valor guardado nele, que no nosso exemplo é `10`.

Uma analogia possível com o mundo real é com aquelas caixas de correio que ficam em frente às casas.

Em Python, o operador de atribuição é o `=` (símbolo de igual). A instrução `x = 10` atribui o valor `10` à variável `x`.

No prompt interativo `>>>`, digite `x = 10` e pressione a tecla [ENTER] ou [RETURN] do seu teclado. Em seguida, digite `x` e pressione a tecla [ENTER] ou [RETURN].

![figura05](https://user-images.githubusercontent.com/61624336/133180044-a4cebb34-ac4e-4924-99f8-0b3ae55f3486.png)

<blockquote>Observe na figura 5 que o retorno do Python Console foi 10.</blockquote>

Se, posteriormente, você utilizar novamente o prompt interativo `>>>` para digitar `x = 20` e pressionar a tecla [ENTER], você alterará o valor da variável `x`. Ou seja, você estará mudando o valor armazenado naquele espaço de memória, mas sem alterar seu apelido. Observe a figura 6:

![figura06](https://user-images.githubusercontent.com/61624336/133180604-727c58f9-da21-4a86-b7f9-ab8996f82ab5.png)

<blockquote><b>Atenção:</b> Diferentemente de outras linguagens, como C ou Java, não é necessário declarar uma variável antes de utilizá-la em Python. Basta atribuir um valor inicial à variável e utilizá-la dali em diante. Embora não seja necessário declarar uma variável para utilizá-la, não é possível utilizar uma variável que não tenha recebido alguma atribuição de valor.</blockquote>

No prompt interativo, digite `b` e pressione a tecla [ENTER] ou [RETURN].

![figura07](https://user-images.githubusercontent.com/61624336/133181027-cf576469-58c4-4e80-bf89-2800e8362f5b.png)

Veja na figura 7 que a mensagem de erro informa que o nome `b` não foi definido. Ou seja, não é possível determinar o valor atribuído a esse nome.

## IDENTIFICADORES DE VARIÁVEIS
Os **identificadores das variáveis** podem ser compostos por **letras**, o **underline** (_) e, com **exceção** do primeiro caractere, números de `0` a `9`. Veja os exemplos:

**minhaVariavel**, **_variavel**, **salario1** e **salario1_2** são válidos.

**1variavel** e **salario-1** não são válidos.

**minhaVariavel** e **minhavariavel** são identificadores de duas variáveis distintas.

Mesmo que seja um identificador permitido, nem sempre um identificador é bom para uma variável. Tente utilizar nomes que ajudem a entender o significado da variável para ganhar tempo quando for entender o código posteriormente.

<blockquote><b>Exemplo:</b> <b>salario</b> é um nome de variável melhor que <b>s</b>.</blockquote>

Algumas palavras são consideradas reservadas e não podem ser usadas como identificadores de variáveis em Python. São elas: `and`, `as`, `assert`, `break`, `class`, `continue`, `def`, `del`, `elif`, `else`, `except`, `exec`, `finally`, `for`, `from`, `global`, `if`, `import`, `in`, `is`, `lambda`, `not`, `or`, `pass`, `print`, `raise`, `return`, `try`, `while`, `with` e `yield`.

## AMARRAÇÕES (binding)
Chamamos de **amarração** (binding) a **associação** entre entidades de programação. Veja alguns exemplos:

`Variável amarrada a um valor` `Operador amarrado a um símbolo` `Identificador amarrado a um tipo`

O tempo em que a amarração ocorre é chamado de **tempo de amarração**. Cada linguagem pode ter os seguintes tempos de amarração:

### TEMPO DE PROJETO DA LINGUAGEM
Os símbolos são amarrados ao operador, como `*` (multiplicação), ou à definição das palavras reservadas.

### TEMPO DE IMPLEMENTAÇÃO
Ocorre em geral nos **compiladores**, como a definição de faixa de valores para determinado tipo.

### TEMPO DE COMPILAÇÃO
Associação da variável ao seu tipo. Lembre-se de que Python associa a variável ao tipo, como foi explicado na seção anterior.

### TEMPO DE LIGAÇÃO
A ligação de vários módulos compilados previamente, como a chamada a uma função de um módulo importado. Em **C**, utilizamos a diretiva `#include` para termos permissão de utilizar as funções de determinada biblioteca. Em Python, utilizamos o `import` para isto.

### TEMPO DE CARGA
Quando o programa é carregado. Por exemplo: endereços de memória relativos são substituídos por **endereços absolutos**.

### TEMPO DE EXECUÇÃO
Associação de valores a variáveis que dependam de entradas do usuário, por exemplo. A variável é vinculada ao valor apenas durante a execução do programa.

O momento em que ocorre a ligação pode ser classificado como **cedo** (early binding) ou **tardio** (late binding). Quanto mais cedo ocorre a ligação, maior a eficiência de execução do programa, porém menor a flexibilidade das estruturas disponibilizadas.

### Amarração de tipo
As **amarrações de tipo** vinculam a variável ao tipo do dado. Elas podem ser:

#### Estáticas
Ocorrem antes da execução e permanecem inalteradas. Em **C**, declaramos `int a`.

#### Dinâmicas
Ocorrem durante a execução e podem ser alteradas. É o caso do Python.

Veja a figura 8:

![figura08](https://user-images.githubusercontent.com/61624336/133185547-6fcf6f2f-7e4f-4213-b97e-7da196919c03.png)

Perceba que a chamada **type** (parâmetro) retorna o tipo do parâmetro informado entre parênteses. Observe que a variável valor recebeu `10` e, com isso, ficou vinculada ao tipo `int`. Porém, ao receber o valor ‘a’, passou a estar vinculada ao tipo **str** (string).

### ESCOPO DE VISIBILIDADE
O escopo define em quais partes do programa uma variável é visível. Cada nome de variável em Python tem seu escopo e fora desse escopo o nome não existe, gerando um erro quando se tenta referenciar esse nome. Quanto ao escopo, chamamos as **variáveis de globais** ou **locais**.

### Variáveis globais
Todos os nomes atribuídos no prompt interativo ou em um módulo fora de qualquer função são considerados como de **escopo global**. Por exemplo, ao executar a instrução da figura 9, a variável `x` é uma variável global.

![figura08](https://user-images.githubusercontent.com/61624336/133186462-e611ec00-cf05-4c65-aa08-39b01e6286a5.png)

### Variáveis locais
Para exemplificar o uso de variáveis com **escopo local**, vamos utilizar uma função definida pelo desenvolvedor. Não se preocupe com esse tipo de função por enquanto, você aprenderá mais detalhes posteriormente. Observe a figura 10:

![figura10](https://user-images.githubusercontent.com/61624336/133186774-2723bffc-04d8-4ffa-ab3f-21ed1a386bb7.png)

As linhas **2**, **3** e **4** compõem o bloco interno à função chamada `multiplicador()`. Embora as variáveis das linhas 2 e 7 tenham o mesmo nome, elas são abstrações a endereços de memória diferentes. Dentro da função `multiplicador()`, a chamada ao nome a recupera o valor 2. Fora da função `multiplicador()`, a chamada ao nome a recupera o valor 3. Veja a execução na figura 11:

![figura11](https://user-images.githubusercontent.com/61624336/133186957-58a33e8a-35ae-4f47-9030-ccc9474b7c23.png)

Agora, observe a função `multiplicador()` com uma pequena alteração, em que retiramos a inicialização da variável `a` dentro da função.

![figura12](https://user-images.githubusercontent.com/61624336/133187100-b86a175a-d049-44d1-ba63-8e8745331dbf.png)

Na linha 6, ao se chamar a função `multiplicador()`, a variável a será procurada. Como não existe uma variável `a` no bloco interno da função, ela é procurada como **variável global**. Uma vez encontrada, o valor recuperado é `3`. Ao executar esse exemplo, você verá:

![figura11](https://user-images.githubusercontent.com/61624336/133187512-5ddcfd2c-6fca-4283-8ec5-fc85161a29ec.png)

Usamos este exemplo para mostrar que o interpretador Python pode procurar o mesmo nome de variável em diferentes escopos. A ordem utilizada para a procura é:

1. A chamada da função delimitadora

2. Variáveis globais

3. O módulo builtins

Perceba que, se a variável `a` é inicializada na função `multiplicador()`, qualquer chamada a esse nome dentro da função resultará na referência a essa variável local. Mas seria possível alterar a variável `a` global com uma instrução dentro da função `multiplicador()`? Sim, utilizando-se a palavra **reservada global**. Veja como isso poderia ser feito na figura 14 e o seu resultado na figura 15:

![figura14](https://user-images.githubusercontent.com/61624336/133187862-28eb033b-2d83-4ab5-adf3-fe1c4e4e9c00.png)

![figura15](https://user-images.githubusercontent.com/61624336/133187955-a319888d-32fc-49e3-9f72-36860e4ba1cb.png)

### Tipos de escopo
Os tipos de escopo são:

### ESTÁTICO
O escopo é baseado na descrição textual do programa e as amarrações são feitas em tempo de compilação. É o caso de **C**, **C++** e **Java**, por exemplo.

### DINÂMICO
O escopo é baseado na sequência de chamada dos **módulos** (ou funções). Por isso, as amarrações são feitas em tempo de execução. É o caso do Python.

O fato de Python ser de escopo dinâmico traz alguns problemas, como a **perda de eficiência** – uma vez que os tipos precisam ser verificados em tempo de execução – e a redução na legibilidade – porque é difícil determinar a sequência exata de todas as **chamadas de função**.

### TEMPO DE VIDA
Embora **escopo** e **tempo de vida** tenham uma relação próxima, eles são conceitos diferentes. Observe:

`Escopo é um conceito textual` x `Tempo de vida é um conceito temporal`

As **variáveis globais** têm o tempo de vida que é o de execução do programa, ao passo que as variáveis locais somente existem no intervalo de duração da função ou do bloco a que se limitam.

## CONSTANTES
Em Python, não existe o conceito de constante (Arrays). Se você precisar de uma constante ao longo de sua jornada como programador, atribua o valor a uma variável e tome cuidado para não mudar esse valor.

<blockquote><b>Dica:</b> Uma dica é iniciar o nome dessa variável com c_ ou utilizar todas as letras maiúsculas, o que vai diferenciar essa variável das outras. Por exemplo, é possível utilizar a expressão c_PI = 3.141592 para armazenar o valor de PI e agilizar o cálculo de área e perímetro de um círculo, ou utilizar a expressão PRECISION = 0.001 para armazenar a precisão a ser utilizada em qualquer cálculo matemático no seu programa.</blockquote>

É importante ficar atento ao uso correto das variáveis, especialmente observando as questões de **escopo** e **visibilidade**, para evitar que algum cálculo seja realizado corretamente, mas com resultado diferente do esperado por você ao programar.

~~~python
def func():
    x = 1
    print(x)
x = 10
func()
print(x)
~~~

## Os tipos de dados e as expressões em Python
Você será apresentado aos **tipos padrão incorporados** ao **interpretador** Python. Os principais tipos internos são **numéricos**, **sequenciais** e **dicionários**. **Classes**, **instâncias** e **exceções** também são _tipos padrão_, mas não entraremos em detalhes neste tema. Para ter nosso primeiro contato com expressões em Python, use o prompt interativo `>>>`.

Digite a expressão algébrica 5 + 8 e pressione a tecla [ENTER]. Observe o resultado na figura 16:

![figura16](https://user-images.githubusercontent.com/61624336/133260245-e0d13a52-d5aa-4ec9-9b15-bd9fb3adeebe.png)

O **Python Console** permite que você calcule expressões algébricas como uma **calculadora**, além de executar instruções básicas em Python.

## TIPOS NUMÉRICOS
Existem três tipos numéricos distintos em Python: **inteiros**, **números de ponto flutuante** e **números complexos**. Além disso, os **booleanos** são um subtipo dos inteiros.

### O tipo int
É o tipo usado para manipular números inteiros. Fazendo uma analogia com a Matemática, o tipo `int` é usado para elementos do conjunto dos inteiros (Z).

Diferentemente de outras linguagens, como **C** ou **Java**, a **linguagem Python** não limita o tamanho de uma variável de qualquer tipo, logo, não existe um valor inteiro máximo definido. O limite depende da quantidade de memória disponível no computador. De volta ao Python Console, veja algumas coisas interessantes.

Digite 1_000_000 e pressione a tecla [ENTER].

![figura18](https://user-images.githubusercontent.com/61624336/133261203-da26e2ac-befa-4663-b3ef-fe783af0c10f.png)

### O tipo float
É o tipo usado para manipular números com parte inteira e parte decimal, chamados de **números de ponto flutuante**. Fazendo uma analogia com a Matemática, o tipo **float** é usado para elementos do conjunto dos reais (R).

Para diferenciar um número real de um inteiro, é possível utilizar a parte decimal zerada. No prompt interativo `>>>`, digite `type(50.0)` e pressione a tecla [ENTER].

![figura20](https://user-images.githubusercontent.com/61624336/133261779-8db1954f-6b83-46ee-8225-c817cf7fa619.png)

<blockquote><b>Atenção:</b> Vale ressaltar que devemos usar o ponto para separar a parte inteira da parte decimal, e não a vírgula.</blockquote>

No prompt, digite **50.0** (com ponto) e pressione [ENTER]. Em seguida, digite **50,0** (com vírgula) e pressione a tecla [ENTER].

![figura20](https://user-images.githubusercontent.com/61624336/133343981-0aef241f-35d8-46d9-a720-23fc508fef4a.png)

Ao usar a vírgula como separador em Python, o que ocorre, na verdade, é a criação de uma tupla de dois elementos, e não o tipo _float_. Você verá mais detalhes sobre tuplas em um momento posterior.

Embora os tipos _int_ e _float_ sejam semelhantes, por tratarem de números, eles têm propriedades um pouco diferentes. Em expressões algébricas, sempre que **somamos**, **subtraímos** ou **multiplicamos** apenas elementos do tipo `int`, o resultado é `int`. Porém, basta um operando do tipo `float` para que o resultado seja `float`. Observe a figura 21:

![figura22](https://user-images.githubusercontent.com/61624336/133344221-6bdae2ec-517e-4a15-9f44-87f0711949e7.png)

Vamos analisar a **exponenciação**. Para realizar essa operação matemática, utilizamos o operador `**`. Veja a figura 22:

![figura22](https://user-images.githubusercontent.com/61624336/133344278-8c9d60f4-415e-4efc-adf4-bc1bb8569f49.png)

Veja que basta que a base seja `float` para que o resultado também o seja.

<blockquote><b>Atenção:</b> Diferentemente de outras linguagens, como <b>C</b>, a divisão de dois números inteiros não necessariamente tem resultado inteiro.</blockquote>

Digite 5/2 e pressione [ENTER].

![figura23](https://user-images.githubusercontent.com/61624336/133345150-22243f10-4ddc-4eb6-91a6-da2a3124c67e.png)

Para obter o **quociente inteiro** e o **resto**, quando dois inteiros são _divididos_, é necessário utilizar os operadores `//` e `%`, respectivamente. Ao dividir `21` por `2`, temos quociente `10` e resto `1`. Observe a figura 24:

![figura24](https://user-images.githubusercontent.com/61624336/133345395-26202e09-187f-41e7-a52f-01a43ac09d5a.png)

### O tipo complex
É o tipo utilizado para manipular **números complexos**, na forma `x + yj`, sendo `x` a **parte real** e `y` a **parte imaginária** do **complexo**.

Veja dois exemplos de variáveis do tipo complex nas figuras 25 e 26, em que a parte real é `2` e a parte imaginária é `5`:

![figura25](https://user-images.githubusercontent.com/61624336/133345607-c9e27b60-a39a-4aed-b81f-dba21be21db6.jpg)
![figura26](https://user-images.githubusercontent.com/61624336/133345615-4ce970ef-c848-4f6c-a872-c2b27c4366f7.jpg)

A chamada `r.conjugate()` retorna o conjugado do número complexo `r`, em que a _parte real_ é **mantida** e a _parte imaginária_ tem o seu **sinal trocado**.

### O tipo bool
Uma expressão algébrica, como vimos nos exemplos dos tipos `int` e `float`, é avaliada como um número, seja desses tipos ou de outro tipo numérico admitido em Python. Porém, utilizar **expressões não algébricas** também é bastante comum. E uma boa notícia é que Python pode avaliar expressões desse tipo também. Essa é uma diferença entre **Python** e outras linguagens, como **C**, por exemplo, em que não existe o tipo **bool**.

No prompt interativo `>>>`, digite a expressão `2 < 3` e pressione [ENTER]. Observe o resultado na figura 27:

![figura27](https://user-images.githubusercontent.com/61624336/133345820-5c5ab274-4751-49d2-aed4-49b07c255fe3.png)

Repare que o resultado dessa expressão não é um número, mas sim a palavra `True`. Caso você colocasse a expressão `2 > 3`, o resultado seria `False`, como pode ver na figura 28.

![figura28](https://user-images.githubusercontent.com/61624336/133346388-3b31df7a-ba34-4a03-9625-8541b9938a93.png)

<blockquote><b>Saiba mais:</b> As expressões que você viu nos dois exemplos são chamadas de <b>expressões booleanas</b>. Trata-se de expressões que podem ser avaliadas com um dos dois valores booleanos: <code>True</code> ou <code>False</code>. Assim, em Python, existe o tipo <code>bool</code>, utilizado para permitir o tratamento de expressões como essas.</blockquote>

Agora, vamos ver o operador `not`, que é um **operador unário**, ou seja, só precisa de **um operando**. Esse operador inverte o valor booleano, ou seja, se o valor original for `True`, `not(valor)` terá o valor `False`. **E vice-versa**.

No prompt interativo `>>>`, digite a expressão `not(2 < 3)` e pressione [ENTER].

![figura29](https://user-images.githubusercontent.com/61624336/133347017-7d5745e8-9436-4ef8-893c-456b624d6ed1.png)

É possível também escrever **expressões booleanas** compostas, utilizando conectivos como `E` `OU`. Vamos ver mais detalhes sobre essas expressões ainda neste módulo.

## Operadores numéricos

### Operadores matemáticos/ aritméticos
Os **operadores matemáticos** são muito semelhantes àqueles que vimos ao longo de nossa jornada como estudantes, aprendendo **Álgebra** e **Aritmética** na escola. Existem algumas pequenas diferenças, como a **divisão** (que pode ser a usual ou a divisão inteira). Mas é possível identificar operações que fizemos ao longo de toda nossa vida. A tabela 2 lista os operadores de expressão aritmética disponíveis em Python.

<table style="width:100%">
  <tr>
    <th rowspan="2">Operação matemática</th>
    <th rowspan="2">Símbolo usado</th>
    <th colspan="2">Exemplo</th>
  </tr>
  <tr>
    <td>Equação</td>
    <td>Resultado</td>
  </tr>
  <tr>
    <td>Soma</td>
    <td><code>+</code></td>
    <td><code>2.5 + 1.3</code></td>
    <td><code>3.8</code></td>
  </tr>
    <tr>
    <td>Subtração</td>
    <td><code>-</code></td>
    <td><code>2.5 - 1.3</code></td>
    <td><code>1.2</code></td>
  </tr>
  <tr>
    <td>Multiplicação</td>
    <td><code>*</code></td>
    <td><code>2.5 * 1.3</code></td>
    <td><code>3.25</code></td>
  </tr>
  <tr>
    <td>Divisão</td>
    <td><code>/</code></td>
    <td><code>2.5 / 1.3</code></td>
    <td><code>1.923076923076923</code></td>
  </tr>
  <tr>
    <td>Divisão inteira</td>
    <td><code>//</code></td>
    <td><code>9/2</code></td>
    <td><code>4</code></td>
  </tr>
   <tr>
    <td>Resto na divisão inteira</td>
    <td><code>%</code></td>
    <td><code>9 % 2</code></td>
    <td><code>1</code></td>
  </tr>
   <tr>
    <td>Valor absoluto</td>
    <td><code>abs(parâmetro)</code></td>
    <td><code>abs(-2.5)</code></td>
    <td><code>2.5</code></td>
  </tr>
   <tr>
    <td>Exponenciação</td>
    <td><code>**</code></td>
    <td><code>2**4</code></td>
    <td><code>16</code></td>
  </tr>
</table>

### Operadores de Comparação

Além das operações algébricas, é possível realizar **operações de comparação**. Os **operadores de comparação** têm como resultado um valor **booleano** (`True` ou `False`). Observe a tabela 3:

<table>
   <tr>
    <td>Símbolo usado</td>
    <td>Descrição</td>
  </tr>
  <tr>
    <td><code> <	</code></td>
    <td>Menor que</td>
  </tr>
   <tr>
    <td><code> <=	</code></td>
    <td>Menor ou igual a</td>
  </tr>
  <tr>
    <td><code> > </code></td>
    <td>Maior que</td>
  </tr>
  <tr>
    <td><code> >= </code></td>
    <td>Maior ou igual a</td>
  </tr> 
  <tr>
    <td><code> == </code></td>
    <td>Igual</td>
  </tr> 
  <tr>
    <td><code> != </code></td>
    <td>Não igual</td>
  </tr> 
</table>

<blockquote><b>Atenção!</b> Cabe observar que o operador utilizado para comparar se dois valores são iguais é o <code>==</code>, ou seja, duplo sinal de igual. Tome cuidado para não confundir com o operador de atribuição, que é representado pelo sinal de igual apenas uma vez <code>=</code>.</blockquote>

Existe outra lista de operadores que executam operações matemáticas, mas, além disso, atualizam o valor da variável utilizada. Eles são chamados de **operadores compostos**. Para mais funções matemáticas, você pode utilizar os módulos matemáticos <code>math</code> e <code>fractions</code>.

### Operadores booleanos
As **expressões booleanas** são aquelas que podem ter como resultado um dos valores booleanos: `True` ou `False`. É comum utilizarmos os **operadores de comparação** em expressões booleanas, mas não só eles.

Assim como é possível escrever expressões algébricas complexas _concatenando_ diversas expressões menores, podemos escrever expressões booleanas grandes, com os operadores `and`, `or` e `not`. Observe o comportamento dos operadores booleanos nas tabelas 4, 5 e 6.

#### Operador `not`
<table>
  <tr>
    <td>p</td>
    <td>not(p)</td>
  </tr>
  <tr>
    <td>True</td>
    <td>False</td>
  </tr>
   <tr>
    <td>False</td>
    <td>True</td>
  </tr>
</table>

#### Operador `and`
<table>
  <tr>
    <td>p</td>
    <td>q</td>
    <td>p or q</td>
  </tr>
  <tr>
    <td>True</td>
    <td>True</td>
    <td>True</td>
  </tr>
   <tr>
    <td>True</td>
    <td>False</td>
    <td>True</td>
  </tr>
   <tr>
    <td>False</td>
    <td>True</td>
    <td>True</td>
  </tr>
  <tr>
    <td>False</td>
    <td>False</td>
    <td>False</td>
  </tr>
</table>

#### Operador `or`
<table>
  <tr>
    <td>p</td>
    <td>q</td>
    <td>p and q</td>
  </tr>
  <tr>
    <td>True</td>
    <td>True</td>
    <td>True</td>
  </tr>
   <tr>
    <td>True</td>
    <td>False</td>
    <td>False</td>
  </tr>
   <tr>
    <td>False</td>
    <td>True</td>
    <td>False</td>
  </tr>
  <tr>
    <td>False</td>
    <td>False</td>
    <td>False</td>
  </tr>
</table>

## TIPOS SEQUENCIAIS
Existem três tipos sequenciais básicos em Python: **listas**, **tuplas** e **objetos range**. Além dos tipos básicos citados, existe um tipo especial criado para tratamento de dados textuais: o tipo `str` (string).

Assim como em **C** ou **Java**, a indexação dos itens é iniciada com `0` e cada item tem o seu índice incrementado uma unidade em relação ao item anterior. Porém, Python também permite a indexação com valores negativos. O valor `-1` é o índice do último item, e cada item anterior é decrementado de uma unidade em relação ao sucessor. Observe a tabela 7:

<table>
  <tr>
    <td>índice</td>
    <td><b>0</b></td>
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
  </tr>
  <tr>
    <td>s</td>
    <td><b>t</b></td>
    <td><b>e</b></td>
    <td><b>s</b></td>
    <td><b>t</b></td>
    <td><b>e</b></td>
  </tr>
   <tr>
    <td>índice negativo</td>
    <td>-5</td>
    <td>-4</td>
    <td>-3</td>
    <td>-2</td>
    <td><b>-1</b></td>
  </tr>
</table>

## Strings
Em uma variável do tipo `str`, é possível **armazenar letras, números, espaços, pontuação e diversos símbolos**. Diferentemente da **linguagem C**, _não existe_ o tipo `char`. **Cada caractere em Python é uma string**. Para delimitar uma string, podemos utilizar:

### Aspas simples
```python
‘uma string'
```

### Aspas duplas
```python
“uma string”
```

### Aspas simples triplas
```python
‘’’uma string’’’
```

### Aspas duplas triplas
```python
“””uma string”””
```

A Figura 30 ilustra um exemplo de delimitadores de strings:

![figura30](https://user-images.githubusercontent.com/61624336/133940623-b524ef49-5d89-4095-9bba-91f8d61efb0f.png)

Existem alguns métodos interessantes para **tratar strings em Python**. Entre eles, ressaltamos:

### `upper`
Transforma todas as letras em **maiúsculas**.

### `lower`
Transforma todas as letras em **minúsculas**.

### `split`
Quebra a string em **substrings**.

Veja os exemplos a seguir:

![figura31](https://user-images.githubusercontent.com/61624336/133940776-28b08988-4471-4e60-8db4-d9d865b16868.png)

<blockquote><b>Saiba mais:</b> A lista gerada com o método ,<code>split()</code> tem três elementos, porque a string original tinha três palavras.</blockquote>

## Listas
**Listas** são _sequências mutáveis_, normalmente usadas para **armazenar coleções de itens homogêneos**. Uma **lista** pode ser criada de algumas maneiras, tais como:

### []
Usando um par de colchetes `[]` para denotar uma **lista vazia**.

### [a], [a, b, c]
Usando colchetes, separando os itens por vírgulas.

### [x for x in iterable]
Usando a **compreensão de lista**.

### list() ou list(iterable)
Usando o **construtor** do tipo _list_.

<blockquote><b>Saiba mais:</b> <code>iterable</code> pode ser uma sequência, um container que suporte <b>iteração</b> ou um <b>objeto iterador</b>. Por exemplo, <code>list('abc')</code> retorna <code>['a', 'b', 'c']</code> e <code>list( (1, 2, 3) )</code> retorna <code>[1, 2, 3]</code>. Se nenhum argumento for passado, o construtor cria uma lista vazia: <code>[ ]</code>.</blockquote>

## Tuplas
**Tuplas** são _sequências imutáveis_, tipicamente usadas para **armazenar coleções de itens heterogêneos**. Elas são aplicadas também quando é necessário utilizar uma sequência imutável de dados homogêneos. Uma tupla pode ser criada de algumas maneiras, tais como:

- `()` Usando um par de parênteses para denotar uma tupla vazia.

- `a, b, c` ou `(a, b, c)` Separando os itens por vírgulas.

- `tuple()` ou `tuple(iterable)` Usando o construtor do tipo `tuple`.

Novamente, **iterable** pode ser uma sequência, um container que suporte **iteração** ou um **objeto iterador**. Por exemplo, `tuple('abc')` retorna `('a', 'b', 'c')` e `tuple( [1, 2, 3] )` retorna `(1, 2, 3)`. Se nenhum argumento for passado, o construtor cria uma tupla vazia: `()`.

<blockquote><b>Atenção</b>: Note que o uso das vírgulas é o que gera a tupla, e não o uso de parênteses. Os parênteses são opcionais, exceto no caso em que queremos gerar uma tupla vazia.</blockquote>

## Range
O tipo **range** representa uma _sequência imutável de números e frequentemente é usado em loops de um número específico de vezes_, como o `for`.

Ele pode ser chamado de maneira simples, apenas com **um argumento**. Nesse caso, a sequência começará em `0` e será incrementada de uma unidade até o limite do parâmetro passado (exclusive). Por exemplo, `range(3)` cria a sequência `(0, 1, 2)`.

Para que a sequência não comece em `0`, podemos informar o início e o fim como parâmetros, lembrando que o parâmetro fim não entra na lista (exclusive o fim). O padrão é incrementar cada termo em uma unidade. Ou seja, a chamada `range(2, 7)` cria a sequência `(2, 3, 4, 5, 6)`.

<blockquote><b>Saiba mais</b>: Também é possível criar sequências mais complexas, indicando os parâmetros de início, fim e passo, nessa ordem. O passo é o valor que será incrementado de um termo para o próximo. Por exemplo, <code>range(2, 9, 3)</code> cria a sequência <code>(2, 5, 8)</code>.</blockquote>

Para que a sequência não comece em 0, podemos informar o início e o fim como parâmetros, lembrando que o parâmetro fim não entra na lista (exclusive o fim). O padrão é incrementar cada termo em uma unidade. Ou seja, a chamada range(2, 7) cria a sequência (2, 3, 4, 5, 6).

## Operadores sequenciais comuns
Os **operadores sequenciais** permitem a _manipulação dos tipos sequenciais_, inclusive as **strings**. Vale ressaltar a sobrecarga dos operadores `+` e `*`, que realizam operações diferentes quando os operandos são **numéricos** ou **sequenciais**.

<blockquote><b>Exemplo</b>: O operador <code>==</code> verifica se as strings dos dois lados são iguais. Porém, os operadores <code><</code> e <code>></code> comparam as strings usando a ordem do dicionário.</blockquote>
  
A tabela a seguir traz um pequeno conjunto dos operadores disponíveis em Python para **manipulação de sequências**. Lembre-se de que você pode utilizar o utilitário `help` no Python Console para verificar a lista completa. Para isso, basta digitar `help(str)` e pressionar [ENTER] no teclado.

<table>
  <tr>
    <td><b>Uso</b></td>
    <td><b>Resultado</b></td>
  </tr>
   <tr>
     <td><code>x in s</code></td>
    <td><b>True</b> se <b>x</b> for um subconjunto de <b>s</b></td>
  </tr>
  <tr>
    <td><code>x not in s</code></td>
    <td><b>False</b> se <b>x</b> for um subconjunto de <b>s</b></td>
  </tr>
  <tr>
    <td><code>s + t</code></td>
    <td>Concatenação de s e t</td>
  </tr>
   <tr>
     <td><code>n*s</code></td>
     <td>Concatenação de <b>n</b> cópias de <b>s</b></td>
  </tr>
   <tr>
     <td><code>s[i]</code></td>
     <td>Caractere de índice <b>i</b> em <b>s</b></td>
  </tr>
   <tr>
     <td><code>len(s)</code></td>
     <td>Comprimento de <b>s</b></td>
  </tr>   
  <tr>
    <td><code>min(s)</code></td>
    <td>Menor item de <b>s</b></td>
  </tr>
  <tr>
    <td><code>max(s)</code></td>
    <td>Maior item de <b>s</b></td>
  </tr>
</table>

## DICIONÁRIOS
Os **dicionários** permitem que itens de uma sequência recebam índices definidos pelo usuário. Um dicionário contém pares de (chave, valor). O formato geral de um objeto dicionário é:
  
```python
{<chave 1>:<valor 1>, <chave 2>:<valor 2>, ..., <chave i>:<valor i>}
```
  
### Exemplo
Poderíamos criar um dicionário em que cada pessoa fosse representada pelo seu **CPF**, com **nome** e **sobrenome**. Para isso, teríamos:

![figura32](https://user-images.githubusercontent.com/61624336/135189834-c300d0a1-a345-444c-96f3-bbe980b68180.png)

Na figura 32, o dicionário tem **3 entradas**. Observe como foi possível recuperar **nome** e **sobrenome** de uma entrada, baseado na chave informada `111222333-44`.

## PRECEDÊNCIA DE OPERADORES
Ao escrever uma expressão algébrica, o programador pode utilizar a **precedência de operadores** existente em Python (implícita) ou **explicitar** a ordem em que ele deseja que a expressão seja avaliada.

### Exemplo
Por exemplo, a expressão `3 + 2 * 5` tem como resultado `25` ou `13`? Aprendemos no ensino fundamental que as operações de **produto** e **divisão** têm precedência sobre as operações de **soma** e **subtração**. Ou seja, **um produto** será realizado **antes de uma soma**, na mesma expressão. Assim, a expressão acima tem como resultado `13`. Isso ocorre sempre que não forem explicitadas outras relações de precedência com o uso de parênteses. Caso o programador quisesse forçar que a soma ocorresse primeiro, ele deveria escrever assim: `(3 + 2) * 5`.

Sempre que o programador quiser forçar a ocorrência de uma operação antes de outras, ele pode utilizar os parênteses para aumentar a prioridade sobre ela. A tabela a seguir traz as relações de precedência entre os operadores, com as linhas mais altas tendo prioridade sobre as linhas mais baixas. Ou seja, elas ocorrem primeiro. Dentro da mesma linha, a precedência é da esquerda para a direita.

<table>
  <tr>
    <td><b>Operador</b></td>
    <td><b>Descrição</b></td>
  </tr>  
   <tr>
     <td><code>[expressões ...]</code></td>
    <td>Definição de lista</td>
  </tr>
   <tr>
     <td><code>x[ ], x[índice : índice]</code></td>
    <td>Operador de indexação</td>
  </tr>
   <tr>
     <td><code>**</code></td>
    <td>Exponenciação</td>
  </tr>
   <tr>
     <td><code>+x, -x</code></td>
    <td>Sinal de positivo e negativo</td>
  </tr>
   <tr>
     <td><code>*, /, //, %</code></td>
     <td>Produto, divisão, divisão inteira, resto</td>
  </tr>
   <tr>
     <td><code>+, -</code></td>
    <td>Soma, subtração</td>
  </tr>
   <tr>
     <td><code>in, not in, <, <=, >, >=, <>, !=, ==	</code></td>
    <td>Comparações, inclusive a ocorrência em listas</td>
  </tr>
  <tr>
     <td><code>not x</code></td>
    <td>Booleano NOT (não)</td>
  </tr>
   <tr>
     <td><code>and</code></td>
     <td>Booleano AND (e)</td>
  </tr>
  <tr>
     <td><code>or</code></td>
     <td>Booleano OR (ou)</td>
  </tr>
</table>

### Atenção!
<blockquote>É importante ficar atento ao uso correto dos operadores, respeitando a precedência entre eles, para evitar que algum cálculo seja realizado corretamente, mas com resultado diferente do esperado por você ao programar.</blockquote>

### Exemplo
  <blockquote>Um número do tipo <code>int</code> pode ser visto como um <code>float</code> com a parte decimal nula. Porém, o inverso não é verdade. Ou seja, o conjunto dos inteiros (<code>int</code>) é um subconjunto do conjunto dos reais (<code>float</code>). Assim, a expressão <code>5 + 0.68</code> – que envolve um <code>int</code> e um <code>float</code> – tem como resultado <code>5.68</code>. O inteiro <code>5</code> é convertido pelo Python para o número de ponto flutuante <code>5.0</code> antes que a soma (de dois valores <code>float</code>) seja realmente efetuada.</blockquote>

### Conversão Implícita
Uma **conversão implícita não intuitiva** é a dos valores booleanos `True` e `False` em inteiros, respectivamente, `1` e `0`. Veja os exemplos a seguir:

![figura33](https://user-images.githubusercontent.com/61624336/135546575-8632668b-5639-41f5-8876-b60d0bdc6d6f.png)

Com isso, podemos perceber a seguinte relação entre os tipos `bool`, `int` e `float`:

![figura34](https://user-images.githubusercontent.com/61624336/135546748-bfdd145b-3ee7-4155-a232-a47a4e2d82b4.png)

### Conversão Explícita
Além das **conversões implícitas**, o programador também pode usar as **conversões explícitas**, quando ele força que o valor seja tratado como de determinado tipo. Para isso, é necessário usar o construtor do tipo desejado, com o valor passado como parâmetro (entre parênteses). Veja o exemplo a seguir:

![figura35](https://user-images.githubusercontent.com/61624336/135546878-6c6ce281-2d63-4a24-9b4e-20fded847fa8.png)

O `int 2` pode ser tratado naturalmente como o `float 2.0`, basta acrescentar a parte decimal nula. Porém, ao tentar tratar um `float` como `int`, ocorre a remoção da parte decimal.

### Atenção!
<blockquote>Fique atento, porque não é uma aproximação para o inteiro mais próximo, e sim o <b>truncamento</b>.</blockquote>

Agora que você já viu os principais tipos de dados suportados em Python, vamos exercitar e verificar o aprendizado.

1. Considere a expressão a seguir: `2 + 3 – 4 ** 2 + 5 / 2 – 5 // 2`

Assinale a opção com o valor correto dessa expressão em Python.

<pre><b>Resposta:</b> -10.5</pre>
<blockquote>Lembre-se que o operador <code>**</code> tem precedência maior do que os operadores <code>/</code> e <code>//</code>, os quais, por sua vez, têm precedência sobre <code>+</code> e <code>-</code>. Ou seja, primeiro será efetuada a exponenciação (<code>4**2</code>), depois as divisões, comum (<code>5/2</code>) e inteira (<code>5//2</code>), para posteriormente serem efetuadas as somas e subtrações.</blockquote>

2. (Adaptada de COMPERVE/2019/UFRN/Engenharia da Computação) Python é uma linguagem interpretada muito utilizada. Não requer tipagem de variáveis e sua sintaxe indentada favorece a organização do código. Uma das suas funcionalidades mais poderosas são as listas. Considere o código em Python do quadro abaixo:

![mod3p2](https://user-images.githubusercontent.com/61624336/135548998-533397a9-4fd6-4d9c-8e0f-f51b1c156753.png)

<pre><b>Resposta:</b> 2 e 4</pre>
<blockquote>O operador <code>+</code> realiza operações de soma para tipos numéricos e concatenação para tipos sequenciais. Assim, a variável a na linha 1 passa a ser composta dos itens ‘UF’ e ‘RN’. Assim, a chamada <code>len(a)</code> retorna o tamanho <code>2</code>, número de elementos de a. De forma semelhante, o operador <code>*</code> realiza operações de multiplicação para tipos numéricos e concatenação de cópias para tipos sequenciais. Assim, a variável b na linha 3 passa a ser a lista <code>['4', '4', '4', '4']</code>. E a chamada <code>len(b)</code> retorna o tamanho <code>4</code>, número de elementos de b.</blockquote>
  
## Entrada e saída de dados em Python
Já vimos, de maneira básica, como podemos atribuir valor a uma variável, no módulo 2. Vamos agora conhecer outras formas de atribuição.
  
## Sentenças de atribuição

### Atribuição simples
Chamamos de **atribuição simples** a forma que já utilizamos neste tema, com uma expressão parecida com `x = 10`. Nessa atribuição, a variável `x` recebe o valor `10`.

### Atribuição múltipla
Python também permite a **atribuição múltipla**, ou seja, mais de uma variável receber atribuição na mesma linha. Veja o exemplo na figura 36:

![figura36](https://user-images.githubusercontent.com/61624336/135550002-e383e5de-b764-4d09-b497-93ee47013575.png)

#### Atenção!
Observe que as variáveis `x` e `y` receberam atribuição na mesma instrução, com a variável `x` armazenando o valor `2`, e a variável `y` armazenando o valor `5`.

### Operadores de atribuição compostos
Os **operadores de atribuição compostos** executam operações matemáticas e atualizam o valor da variável utilizada. Por exemplo, veja a figura 37:

![figura37](https://user-images.githubusercontent.com/61624336/135550875-4cbba501-1415-4f7e-a99e-b34b35c9347a.png)

A variável `x` inicialmente recebeu o valor `10`. Em seguida, a instrução `x = x + 1`, que causa estranheza quando lembramos da matemática aprendida ao longo da vida, é muito comum quando estamos programando. Essa instrução significa “acrescente uma unidade ao valor de `x` e guarde este resultado na própria variável `x`”. Como `x` valia `10`, o resultado do lado direito do operador (`=`) é `11`. Esse resultado é, então, armazenado na própria variável `x`.

Essa **operação de acrescentar** determinado valor a uma variável e armazenar o resultado na própria variável poderia ser feita com o operador `+=` (mais igual). Veja a figura 38:

![figura38](https://user-images.githubusercontent.com/61624336/135552211-7684c2a5-1dd7-48e8-b387-cfa5731ad05e.png)
  
Na tabela 10, estão os operadores compostos disponíveis em Python. Considere a variável `x`, com o valor inicial `10`, para verificar os resultados.


<table style="width:100%">
  <tr>
    <th rowspan="2">Nome</th>
    <th rowspan="2">Símbolo usado</th>
    <th colspan="2">Exemplo</th>
  </tr>
  <tr>
    <td>Instrução</td>
    <td>Resultado</td>
  </tr>
  <tr>
    <td>Mais igual</td>
    <td><code>+=</code></td>
    <td><code>x += 2</code></td>
    <td>x passa a valer 12</td>
  </tr>
    <tr>
    <td>Menos igual</td>
    <td><code>-=</code></td>
    <td><code>x -= 2</code></td>
    <td>x passa a valer 8</td>
  </tr>
  <tr>
    <td>Vezes igual</td>
    <td><code>*=</code></td>
    <td><code>x *= 2</code></td>
    <td>x passa a valer 20</td>
  </tr>
  <tr>
    <td>Dividido igual</td>
    <td><code>/=</code></td>
    <td><code>x /= 2</code></td>
    <td>x passa a valer 5</td>
  </tr>
   <tr>
    <td>Módulo igual</td>
    <td><code>%=</code></td>
    <td><code>x %= 3</code></td>
    <td>x passa a valer 1</td>
  </tr>
</table>

#### Atenção!
<blockquote>Diferente de <b>C</b>, em <b>Python</b> não é possível incrementar ou decrementar uma variável com um operador unário, como o <code>++</code> ou <code>--</code>.</blockquote>
  
## Troca de variáveis
Um dos problemas iniciais que envolvem atribuição de valores a variáveis é a troca entre duas delas. Suponha que as variáveis `a` e `b` armazenem, respectivamente, os valores `1` e `2`. Caso quiséssemos inverter os valores em linguagens como **C** ou **Java**, seria necessário usar uma variável auxiliar, com uma sequência de instruções exibida na figura a seguir:
 
![figura39](https://user-images.githubusercontent.com/61624336/135555036-17ad052e-35b6-4138-b852-52896b5b38eb.png)
  
Em Python, é possível fazer essa troca de uma maneira muito mais fácil. Veja o uso da atribuição múltipla, nesse caso, na figura a seguir:
  
![figura40](https://user-images.githubusercontent.com/61624336/135555122-4a80fd61-9d9b-4b9b-a867-748b293ccd98.png)

## 🐍 O PRIMEIRO PROGRAMA EM PYTHON 🖥️

Para escrever um programa em Python, será essencial utilizar as formas de **saída de dados** para exibir ao usuário mensagens e resultados de operações. Caso você deseje que o usuário informe algum dado para que seu programa processe, será necessário utilizar as formas de entrada de dados.

### Saída de dados com a função `print()`
A função `print()` em Python atua de forma semelhante à `printf()` em **C**. Para um programador iniciante, as maiores diferenças entre elas são:

- Duas chamadas da `print()` em Python são impressas na tela em linhas diferentes, sem a necessidade do uso do caractere `\n` para pular a linha, como ocorre na `printf()` em **C**.
  
- Uma chamada da `print()` em Python permite a impressão de valores de variáveis sem a indicação do formato, como ocorre na `printf()` em **C**, quando precisamos escrever `%c`, `%d` ou `%f`, por exemplo.

Para escrever seu **Hello, World!** em Python, digite a seguinte linha, exatamente como está escrita:

~~~python
print(“Hello, World!”)
~~~

ou 
  
~~~python
print('Hello, World!')
~~~

Para divulgar a mensagem no terminal ou prompt de comando, basta ir até a pasta onde está localizado o arquivo e inserir o comando:

```
python hello-world.py
```
 
Veja que foi impresso no **console** exatamente o que colocamos entre aspas, ao chamar a função `print()`. Essa é a primeira forma de saída de dados: usar a função `print()` com uma string sendo passada como parâmetro (entre os parênteses). É importante perceber que a função `print()`, além de imprimir a string, também salta o cursor para a próxima linha.

Como você deve ter percebido, o que a função `print()` recebeu entre parênteses foi uma string. Ou seja, poderíamos ter passado para ela uma string definida anteriormente, como no exemplo a seguir:

![figura45](https://user-images.githubusercontent.com/61624336/135556658-5327f51b-cd98-4e9d-93e4-ca1449a41cac.png)

Também poderíamos ter passado como parâmetro uma variável definida anteriormente. A função `print()` vai trabalhar com o valor dessa variável. Observe as figuras 46 e 47:

<div align="center"><img src="https://user-images.githubusercontent.com/61624336/135556758-165cc082-c33b-49a2-92c3-0a5b18f5713a.png" height="307"><img src="https://user-images.githubusercontent.com/61624336/135556807-a18d4902-a2b8-4da5-b7b5-e19c8a3e6df5.png" height="307"></div>
  
## ENTRADA DE DADOS COM A FUNÇÃO `INPUT()`
Quando o programador quiser que o usuário entre com algum valor, ele deverá exibir na tela o seu pedido. Em **C**, é necessário utilizar a função `printf()` para escrever a solicitação ao usuário e a função `scanf()` para receber a entrada e armazenar em uma variável. Em Python, é possível utilizar a função `input()`. Ela tanto exibe na tela o pedido, como permite que o valor informado pelo usuário seja armazenado em uma variável do seu programa. Analise a figura 48:

![figura48](https://user-images.githubusercontent.com/61624336/135557070-e2632f21-e632-4ed8-8e01-3a0ba88e4694.png)

A **linha 1** fará com que a frase Entre com seu nome: seja exibida no console, mas a execução do programa fica travada até que o usuário aperte [ENTER] no teclado. Tudo o que foi digitado até o [ENTER] vai ser armazenado na variável nome. A linha 2 fará a exibição do conteúdo da variável nome. Veja o resultado no console, com o usuário tendo digitado `Fulano de Tal`.

![figura49](https://user-images.githubusercontent.com/61624336/135557120-0a3212eb-c88d-4bce-bf43-368ba46ebeb7.png)

### Atenção!
É importantíssimo perceber que a função `input()` trata **tudo o que for digitado** pelo usuário como uma `string`, armazenando na variável designada pelo programador para isso. Mesmo que o usuário entre com apenas uma letra ou um número, isso será armazenado como uma string na variável.
  
Vamos analisar o exemplo a seguir:

![figura50](https://user-images.githubusercontent.com/61624336/135557245-cbb1e7e4-57d5-48e0-8062-9906350d4707.png)
  
Veja o console quando o programa é executado:

![figura51](https://user-images.githubusercontent.com/61624336/135557287-6b51b6ed-1854-44f1-bdc7-03461b850344.png)

O usuário digitou `3` e [ENTER]. Mesmo sendo um valor, a variável numero trata como a string ‘3’. Isso impede que seja realizada a operação de soma com o inteiro `2`, por exemplo. Poderíamos também usar a instrução `print(type(numero))` na **linha 2** para confirmar. Veja:

<div align="center"><img src="https://user-images.githubusercontent.com/61624336/135557447-50f69aed-92e9-4555-a971-318ec71a34a3.png" height="307"><img src="https://user-images.githubusercontent.com/61624336/135557459-3e9bdfe4-ca8b-4944-b182-8c1b783bfb20.png" height="307"></div>

### A função `eval()`
A função `eval()` recebe uma string, mas trata como um valor numérico. Veja o exemplo a seguir:
  
![figura54](https://user-images.githubusercontent.com/61624336/135561204-f9edca85-9c7c-41be-9d26-9ffc439c84ff.png)
  
Mesmo tendo recebido a string `'1+2'` como parâmetro, a função `eval()` efetuou a soma de `1` com `2`. Observe que confirmamos que `s` é uma string com a instrução `type(s)`.

Para tratar a entrada do usuário como um número e, com isso, realizar operações algébricas, por exemplo, é necessário utilizar a função `eval()` em conjunto com a `input()`. Veja o próximo exemplo:

<div align="center"><img src="https://user-images.githubusercontent.com/61624336/135561379-c1e94f7d-403d-43b0-aefb-d5a53776e960.png" height="307"><img src="https://user-images.githubusercontent.com/61624336/135561395-39265870-5f81-4b17-9d4e-be2bb0a17926.png" height="307"></div>

## SAÍDA FORMATADA DE DADOS
Quando desejamos que a saída siga determinado padrão – por exemplo, de hora ou de data – existem algumas possibilidades para usar a função `print()`. É sempre possível utilizar a concatenação de strings, com o operador `+`, para montar a frase como quisermos. Suponha que tenhamos as seguintes variáveis:
`hora = 10 minutos = 26 segundos = 18`

Poderíamos chamar a função `print()` com o separador `:` da seguinte forma:

![figura59](https://user-images.githubusercontent.com/61624336/135562269-f0d87927-e31b-447b-bf04-3c5e5949e718.png)

Porém, existe outra possibilidade, usando o método `format()`. Ele permite que a chamada à função `print()` fique muito parecida com as chamadas à função `printf()` em **C**, com passagem de parâmetros a serem colocados em ordem na string. Com o método `format()`, podemos montar a string com as chaves `{}` indicando onde entrarão valores, passados como parâmetros separados por vírgulas.

![figura60](https://user-images.githubusercontent.com/61624336/135564853-cfe792e0-5ca1-471c-8287-cce8be38626d.png)
  
É importante observar que a quantidade de chaves precisa ser igual à quantidade de variáveis passadas como parâmetros no método `format()`. Seria muito bom se não precisássemos nos preocupar com essa correspondência para evitar erros bobos. E isso é possível! Para tornar a saída formatada ainda mais intuitiva, basta utilizar a letra ‘f’ no início dos parâmetros da função `print()` e colocar cada variável dentro das chaves na posição em que deve ser impressa. Veja como fica ainda mais fácil entender:

![figura61](https://user-images.githubusercontent.com/61624336/135564963-eb56ae84-9186-4506-8d01-59c8e29db2eb.png)
  
Também é possível especificar a largura de campo para exibir um inteiro. Se a largura não for especificada, ela será determinada pela quantidade de dígitos do valor a ser impresso. Veja a figura 62:
  
![figura62](https://user-images.githubusercontent.com/61624336/135565052-006829ba-5624-4ca2-892a-8808cec44e57.png)
  
Observe que os valores `10` e `100` foram impressos com espaços em branco à esquerda. Isso ocorreu porque definimos que a primeira variável deveria ser impressa com `4` espaços com `{:4}` (`2` foram ocupados e `2` ficaram em branco), e que a segunda variável deveria ser impressa com `5` espaços com `{:5}` (`3` foram ocupados e `2` ficaram em branco).

### Saiba mais
Também é válido perceber que o padrão é alinhar os valores à direita do espaço reservado para a impressão da variável.
  
O método `format()` também pode ser usado para imprimir valores de ponto flutuante com a precisão definida. Veja a figura 63:

![figura63](https://user-images.githubusercontent.com/61624336/135565295-50303a92-2571-434f-a5d2-deb9862f6b9e.png)
  
Ao usar `{:8.5}`, estamos determinando que a impressão será com `8` espaços, mas apenas `5` serão utilizados.

### Impressão de sequências
**Python** também permite a impressão de sequências com mais possibilidades que **C**, incluindo as strings. Para imprimir um vetor em **C**, por exemplo, precisamos chamar a `printf()` tem o item. Em Python, basta chamar a função `print()` passando como parâmetro a sequência. Veja a figura 64:
  
![figura64](https://user-images.githubusercontent.com/61624336/135565470-873c3eaf-c533-4c6b-8460-898358f0350f.png)
  
Para imprimir uma **substring**, por exemplo, basta utilizar os colchetes `[]` para indicar o intervalo de índices que deve ser impresso. Vale lembrar que o primeiro caractere da string é indexado com `0`. Veja a figura 65:

![figura65](https://user-images.githubusercontent.com/61624336/135565532-f6321141-e722-4414-9ca7-721ac7c6b3b3.png)

### Atenção
Usar `[0:4]` provoca a impressão dos índices `0, 1, 2 e 3`, **mas não** do índice 4. Analogamente, usar `[2:8]` provoca a impressão dos índices de `2 a 7`, mas não do `8`.

Também é possível imprimir a string como lida da direita para a esquerda. Para isso, deve-se utilizar `[: : -1]`. Esse valor `-1` indica que a leitura dos caracteres será feita no sentido oposto ao tradicional. Observe a figura 66:
  
![figura66](https://user-images.githubusercontent.com/61624336/135565755-38814479-bcf7-4711-a96d-eed7c616be39.png)
  
### Atenção
Fique atento quando utilizar o intervalo na impressão no sentido inverso, porque os limites do intervalo devem respeitar esse sentido.

# 🐍 Estruturas de decisão e repetição em Python ✔️❌🔁
As **estruturas de controle** permitem selecionar quais partes do código serão executadas – chamadas de **estruturas de decisão** – e **repetir blocos de instruções** com base em algum critério, como **uma variável de controle** ou a **validade de alguma condição** – chamadas de **estruturas de repetição**. Neste módulo, vamos conhecer as **estruturas de decisão** e de **repetição em Python**.

## TRATAMENTO DAS CONDIÇÕES
As **estruturas de decisão** e de **repetição** possuem sintaxes bastante semelhantes em **C** e em **Python**. Mesmo com essa grande semelhança, existe uma diferença crítica no tratamento das condições. Diferentemente da linguagem **C**, **Python** oferece o tipo `bool`. Por isso, cabe ressaltar a diferença de comportamento das duas linguagens nesse tratamento.
  
<table>
  <tr>
    <td><b>Python</b></td>
    <td><b>C</b></td>
  </tr>
  <tr>
    <td>Existe o tipo bool</td>
    <td>Não existe o tipo bool</td>
  </tr>
  <tr>
    <td>True</td>
    <td>Qualquer valor diferente de 0 (zero)</td>
  </tr>
  <tr>
    <td>False</td>
    <td>0 (zero) ou vazio</td>
  </tr>
</table>

### Atenção!
Observe que o fato de haver o tipo `bool` em Python permite que as condições sejam tratadas como **verdadeiras** ou **falsas**, o que não é exatamente igual em **C**.

## AS ESTRUTURAS DE DECISÃO `IF`, `IF-ELSE` E `ELIF`
Em Python, é possível utilizar as estruturas de decisão `if` e `if-else` da mesma forma que em **C**. A diferença principal é o modo de delimitar os blocos de instruções relativos a cada parte da estrutura. Observe a Tabela 2 e a Tabela 3:
  
<table>
  <tr>
    <td><b>Python</b></td>
    <td><b>C</b></td>
  </tr>
  <tr>
    <td>if <condição>:	</td>
    <td>if <condição>{</td>
  </tr>
  <tr>
    <td>Instruções com 4 espaços de indentação</td>
    <td>A indentação não é exigida</td>
  </tr>
  <tr>
    <td>Instrução fora do if</td>
    <td>}</td>
  </tr>
</table>
  
<table>
  <tr>
    <td><b>Python</b></td>
    <td><b>C</b></td>
  </tr>
  <tr>
    <td>if <condição>:	</td>
    <td>if <condição>{</td>
  </tr>
  <tr>
    <td>Instruções com 4 espaços de indentação (caso a condição seja verdadeira)</td>
    <td>Bloco 1 (caso a condição seja verdadeira). A indentação não é exigida</td>
  </tr>
  <tr>
    <td>else:</td>
    <td>} else {</td>
  </tr>
  <tr>
    <td>Instruções com 4 espaços de indentação (caso a condição seja falsa)</td>
    <td>Bloco 2 (caso a condição seja falsa). A indentação não é exigida</td>
  </tr>
  <tr>
    <td>Instrução fora do if</td>
    <td>}</td>
  </tr>
</table>

Python também oferece a estrutura `elif`, que permite o teste de duas condições de forma sequencial. Essa estrutura não existe em **C**, sendo necessário o encadeamento de estruturas `if-else`. Em geral, o formato da estrutura `elif` é:

```python
1     """
2     if <condição 1>:
3     Bloco de código que será executado caso condição seja True
4     elif <condição 2>:
5     Bloco de código que será executado caso condição 1 seja False e condição 2 seja True
6     else:
7     Bloco de código que será executado caso condição 1 seja False e condição 2 seja False
8     Instrução fora do if
9     """  
```
  
Veja uma implementação possível com a estrutura `elif` na Figura 1:

```python
  idade = eval(input('Informe a idade da criança: '))
  if idade < 5:
  print('A criança deve ser vacinada contra a gripe.')
  print('Procure o posto de saúde mais próximo.')
  elif idade == 5:
  print('A vacina estará disponível em breve.')
  print('Aguarde as próximas informações.')
  else:
  print('A vacinação só ocorrerá daqui a 3 meses.')
  print('Informe-se novamente neste prazo.')
  print('Cuide da saúde sempre. Até a próxima.')
```

Perceba que a indentação precisa ser ajustada, uma vez que o último else é relativo ao `elif`. Por isso, eles precisam estar alinhados.

## ESTRUTURA DE REPETIÇÃO `FOR`
A **estrutura de repetição** `for` tem funcionamento muito semelhante nas linguagens **C** e **Python**. Porém, a sintaxe é diferente nas duas linguagens. Além disso, em Python existe maior flexibilidade, já que a repetição pode ser controlada por uma variável não numérica.

Antes de detalhar o for, vamos conhecer uma função de Python que gera uma lista de valores numéricos. Essa lista ajudará a verificar a repetição e deixará mais claro o entendimento do laço.

### As listas do tipo `range()`
Ao chamar o método `range()`, Python cria uma sequência de números inteiros, de maneira simples à mais complexa. Veja a seguir:
    
#### Simples
Ela pode ser chamada de maneira **simples**, apenas com um argumento. Nesse caso, a sequência começará em `0` e será incrementada de uma unidade até o limite do parâmetro passado (exclusive).

Por exemplo: `range(3)` cria a sequência (`0, 1, 2`).
     
#### Não iniciadas em 0
Para que a sequência não comece em 0, podemos informar o início e o fim como parâmetros, lembrando que o parâmetro fim não entra na lista (exclusive o fim). O padrão é incrementar cada termo em uma unidade. Ou seja, a chamada `range(2, 7)` cria a sequência (`2, 3, 4, 5, 6`).
                 
#### Indicando início, fim e passo
Também é possível criar sequências mais complexas, indicando os parâmetros de início, fim e passo, nessa ordem. O passo é o valor que será incrementado de um termo para o próximo.

Por exemplo, `range(2, 9, 3)` cria a sequência (`2, 5, 8`).
                 
### A sintaxe da estrutura `for`
A estrutura `for` tem a seguinte sintaxe em Python:
                 
```python
1 for <variável> in <sequência>:
2 Bloco que será repetido para todos os itens da sequência
3 Instrução fora do for                 
```

Cabe ressaltar a diferença de sintaxe entre as linguagens **C** e **Python**. Veja a Tabela 4:

  
<table>
  <tr>
    <td><b>Python</b></td>
    <td><b>C</b></td>
  </tr>
  <tr>
    <td>for <variável> in <sequência>:	</td>
    <td>for (inicialização; condição; incremento ou decremento){</td>
  </tr>
  <tr>
    <td>Instruções com 4 espaços de indentação</td>
    <td>Bloco de instruções a ser repetido. A indentação não é exigida</td>
  </tr>
  <tr>
    <td>Instrução fora do for</td>
    <td>}</td>
  </tr>
</table>

Vamos analisar um exemplo simples em Python: **imprimir todos os elementos de uma sequência criada com a chamada `range()`**. Veja uma possível implementação desse exemplo na Figura 2:

```python
for item in range(2, 9, 3):
  print(item)
```
  
- A **linha 1** mostra a criação do laço, com a variável item percorrendo a sequência (`2, 5, 8`), criada pela chamada `range(2, 9, 3)`;
- A **linha 2** indica a instrução que será executada para cada repetição deste laço. O laço for executa a instrução da linha 2 três vezes, uma para cada elemento da sequência (2, 5, 8); o resultado está exemplificado na Tabela 5.

<table>
  <tr>
    <td></td>
    <td>sequência</td>
    <td>2</td>
    <td>5</td>
    <td>8</td>
  </tr>
  <tr>
    <td>Iteração 1 do laço</td>
    <td>item =</td>
    <td><code>2</code></td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td>Iteração 2 do laço</td>
    <td>item =</td>
    <td>&nbsp;</td>
    <td><code>5</code></td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td>Iteração 3 do laço</td>
    <td>item =</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
    <td><code>8</code></td>
  </tr>
</table>

## O laço `for` com uma string
Python também permite que a repetição aconteça ao longo de uma string. Para isso, basta lembrar que a string é uma sequência de caracteres individuais. Suponha que você queira soletrar o nome informado pelo usuário. Uma possível implementação está na Figura 3:

```python
nome = input("Entre com seu nome: ")
 for letra in nome:
 print(letra)
```

- A **linha 1** faz com que a palavra inserida pelo usuário seja armazenada na variável nome;
- A **linha 2** mostra a criação do **laço**, com a variável letra percorrendo a sequência de caracteres armazenada na variável nome;
- A **linha 3** indica a instrução que será executada para cada repetição desse laço. O laço `for` executa a instrução da linha 3 tantas vezes quantos forem os elementos da sequência que está na variável nome.
  
<pre>
1 Entre com o seu nome: Laura
2 L
3 a
4 u
5 r
6 a
</pre>

# Uso do laço `for` com qualquer sequência
Até agora, estudamos o uso do laço `for` com **iterações** sobre **strings** e sobre **sequências numéricas**, mas **Python** permite ainda mais que isso!
  
<blockquote>Podemos utilizar o laço <code>for</code> com iterações sobre qualquer sequência, não somente as <b>numéricas</b> e as <b>strings</b>.</blockquote>
  
Observe o exemplo da Figura 5:

```python
nomes = ['Laura', 'Lis', 'Guilherme', 'Enzo', 'Arthur']
for nome in nomes:
 print(nome)
```  

Veja o resultado da execução na Figura 6:

<pre>
1 Laura
2 Lis
3 Guilherme
4 Enzo
5 Arthur
</pre>
  
## ESTRUTURA DE REPETIÇÃO `WHILE`
A estrutura de repetição `while` tem funcionamento e sintaxe muito semelhantes nas linguagens **C** e **Python**. Observe a comparação entre as duas linguagens na Tabela 6:
  
<table>
<tr>
  <td><b>Python</b></td>
  <td><b>C</b></td>
<tr>
<tr>
  <td>while <condição>:	</td>
  <td>while <condição>{</td>
<tr>
<tr>
  <td>Instruções com 4 espaços de indentação</td>
  <td>Bloco de instruções a ser repetido. A indentação não é exigida</td>
<tr>
<tr>
  <td>Instrução fora do while</td>
  <td>}</td>
<tr>
</table>

Como exemplo inicial do uso do laço `while`, vamos analisar um programa em que o usuário precisa digitar a palavra “sair” para que o laço `while` seja encerrado.

Uma possível implementação desse exemplo em Python está na Figura 7:
  
```python
palavra = input('Entre com uma palavra: ')
while palavra != 'sair':
palavra = input('Digite sair para encerrar o laço: ')
print('Você digitou sair e agora está fora do laço')
```

- A **linha 1** representa a solicitação ao usuário para que ele insira uma palavra, que será armazenada na variável palavra;
- A **linha 2** cria o laço `while`, que depende da condição <valor da variável palavra ser diferente de ‘sair’>;
- A **linha 3** será repetida enquanto a condição for verdadeira, ou seja, enquanto o valor da variável palavra for diferente de ‘sair’. Quando esses valores forem iguais, a condição do laço `while` será falsa e o laço será encerrado;
- A **linha 4** representa a impressão da mensagem fora do laço `while`.
  
Veja uma execução desse programa na Figura 8:
  
<pre>
1 Entre com uma palavra: teste
2 Digite sair para encerrar o laço: Oi?
3 Digite sair para encerrar o laço: Estou tentando...
4 Digite sair para encerrar o laço: Aff...
5 Digite sair para encerrar o laço: Blz, entendi...
6 Digite sair para encerrar o laço: Sair
7 Digite sair para encerrar o laço: Ah! o 'S' foi maiúsculo
8 Digite sair para encerrar o laço: sair
9 Você digitou sair e agora está fora do laço
</pre>
  
Observe agora outra execução do mesmo programa na Figura 9:

<pre>
1 Entre com uma palavra: sair
2 Você digitou sair e agora está fora do laço
</pre>
  
Perceba que ao digitar ‘sair’ logo na primeira solicitação, a linha 3 do nosso programa não é executada nenhuma vez. Ou seja, o programa nem chega a entrar no laço `while`.

Em **C**, existe outra estrutura muito semelhante ao `while`, chamada `do-while`. A diferença básica entre elas é o momento em que a condição é testada, como vemos a seguir:
  
  <table>
    <tr>
      <td>No laço while, a condição é testada antes da iteração.
        O laço <code>while</code> testa e executa caso a condição seja verdadeira.
        No laço <code>do-while</code>, a condição é testada após a iteração.
        O laço <code>do-while</code> executa e testa.</td>
      <td>X</td>
      <td>No laço <code>do-while</code>, a condição é testada após a iteração. O laço <code>do-while</code> executa e testa.</td>
    </tr>
  </table>

Infelizmente, a estrutura `do-while` não existe em Python. Isso não chega a ser um grande problema, porque podemos adaptar nosso programa e controlar as repetições com o laço `while`.

## O laço `while` infinito
**Laços infinitos** são úteis quando queremos executar um bloco de instruções indefinidamente.

O laço `while` infinito tem o seguinte formato:
  
```python
 while True:
   Bloco que será repetido indefinidamente
```

### Exemplo
<blockquote>Suponha que você deseje criar uma aplicação que permaneça por meses ou anos sendo executada, registrando a temperatura ou a umidade de um ambiente. Logicamente, estamos supondo que você tenha essa informação disponível a partir da leitura de algum sensor.

Deve-se tomar cuidado e ter certeza de que seu uso é realmente necessário para evitar problemas de consumo excessivo de memória.</blockquote>

# AS INSTRUÇÕES AUXILIARES `BREAK`, `CONTINUE` E `PASS`

## A instrução `break`
A instrução `break` funciona da mesma maneira em **C** e em **Python**. Ela interrompe as repetições dos laços `for` e `while`. Quando a execução do programa chega a uma instrução `break`, a repetição é encerrada e o fluxo do programa segue a partir da primeira instrução seguinte ao laço.

Para exemplificar o uso da instrução `break`, vamos voltar ao primeiro exemplo do laço `while`, utilizando o laço infinito. O laço será encerrado quando o usuário inserir a palavra ‘sair’. Veja a Figura 10:
  
```python
while True:
  palavra = input('Entre com uma palavra: ')
  if palavra == 'sair':
  break
print('Você digitou sair e agora está fora do laço')
```

Caso haja **vários laços aninhados**, o `break` será relativo ao laço em que estiver inserido. Veja a Figura 11:

```python
while True:
  print('Você está no primeiro laço.')
  opcao1 = input('Deseja sair dele? Digite SIM para isso. ')
  if opcao1 == 'SIM':
  break # este break é do primeiro laço
 else:
  while True:
   print('Você está no segundo laço.')
   opcao2 = input('Deseja sair dele? Digite SIM para isso. ')
    if opcao2 == 'SIM':
      break # este break é do segundo laço
    print('Você saiu do segundo laço.')
    print('Você saiu do primeiro laço')
```
  
## A instrução `continue`
A instrução `continue` também funciona da mesma maneira em **C** e em **Python**. Ela atua sobre as repetições dos laços `for` e `while`, como a instrução `break`, mas não interrompe todas as repetições do laço. A instrução `continue` **interrompe apenas a iteração corrente**, fazendo com que o **laço passe para a próxima iteração**.

O exemplo a seguir imprime todos os números inteiros de `1` até `10`, pulando apenas o `5`. Veja sua implementação na Figura 12:
  
```python
 for num in range(1, 11):
  if num == 5:
   continue
  else:
   print(num)
   print('Laço encerrado')
```

Para ressaltar a diferença entre as instruções `break` e `continue`, vamos alterar a linha 3 do nosso programa, trocando a instrução `continue` pela instrução `break`. Veja a nova execução na Figura 13:
  
<pre>
1
2
3
4
Laço encerrado
</pre>
  
## A INSTRUÇÃO `PASS`
A instrução `pass` atua sobre a estrutura `if`, permitindo que ela seja escrita sem outras instruções a serem executadas caso a condição seja verdadeira. Assim, podemos concentrar as instruções no caso em que a condição seja falsa. Suponha que queiramos imprimir somente os números ímpares entre `1` e `10`. Uma implementação possível está na Figura 14:
  
```python
for num in range(1, 11):
  if num % 2 == 0:
      pass
  else:
      print(num)
print('Laço encerrado')
```

Veja a execução desse programa na Figura 15:

<pre>
1
3
5
7
9
Laço encerrado
</pre>

Claramente, seria possível reescrever a condição do `if-else` para que pudéssemos transformá-lo em um `if` simples, sem `else`. Porém, o objetivo aqui é mostrar o uso da instrução `pass`.

Agora que já vimos os principais conceitos relativos às estruturas de decisão e de repetição, vamos testar seus conhecimentos.
  
### 1. Considere o seguinte trecho de um programa escrito em Python:

```python
s = 0
  for i in range(5):
    s += 3*i
print(s)
```  
Parabéns! A alternativa "C" está correta.

O laço for vai ser repetido 5 vezes, já que range(5) retorna a sequência (`0, 1, 2, 3, 4`). Vale observar que a instrução `print(s)` está fora do laço `for`, o que a leva a ser executada apenas uma vez quando o laço se encerrar. Isso elimina as opções A e B. A variável s começa com valor zero e é acrescida, a cada iteração, do valor `3*i`, sendo que `i` pertence à sequência (`0, 1, 2, 3, 4`). Ou seja, s recebe os acréscimos: `0 + 3 + 6 + 9 + 12`. Assim, ela termina o laço com o valor `30`, que será impresso pela instrução `print(s)`.
  
### 2. Considere o seguinte trecho de um programa escrito em Python:
```python
s = 0
a = 1
  while s < 5:
     s = 3*a
     a += 1
print(s)
```
             
Parabéns! A alternativa "B" está correta.

Ao ser testada pela primeira vez, a condição do while é verdadeira, já que s vale zero. Assim, a variável s recebe o valor 3 (3x1) e a variável a é acrescida de uma unidade, ficando com o valor 2. Em seguida, é impresso o valor de s (3). A condição do while é, então, testada novamente, sendo mais uma vez verdadeira, porque s tem o valor 3 (menor que 5). Nessa iteração, a variável s recebe o valor 6 (3x2) e a variável a é acrescida de uma unidade, ficando com o valor 3. Em seguida, é impresso o valor de s (6). A condição do while é, então, testada novamente e é falsa, já que s tem o valor 6, maior que 5. Com isso, o laço while é encerrado e nada mais é impresso. Logo, foram impressos os valores 3 e 6.
              
## Subprogramas
<div align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Python.svg" height="277"></div><br \>
             
Os **subprogramas** são elementos fundamentais dos programas e por isso são importantes no estudo de linguagens de programação. Neste módulo, abordaremos os conceitos de subprogramas, como características gerais, passagem de parâmetros e recursividade, além da utilização de subprogramas em Python.

### CARACTERÍSTICAS GERAIS DOS SUBPROGRAMAS
Todos os subprogramas estudados neste módulo, com base em Sebesta (2018), têm as seguintes características:

- Cada subprograma tem **um único ponto de entrada**.
- A unidade de programa chamadora é suspensa durante a execução do subprograma chamado, o que significa que existe apenas um subprograma em execução em determinado momento.
- Quando a execução do subprograma termina, o controle sempre retorna para o chamador.

### DEFINIÇÕES BÁSICAS
As definições básicas, conforme Sebesta (2018), estabelecem que:

1. Um subprograma é definido quando o desenvolvedor descreve a **interface** e as **ações da abstração** desse subprograma.
2. O subprograma foi chamado quando uma instrução traz um **pedido explícito para sua execução**.
3. O subprograma está ativo após o **início de sua execução**, a partir da sua chamada e enquanto ele não foi concluído.

O cabeçalho do subprograma é a primeira parte da definição, em que podem ser especificados o **nome**, os **parâmetros** e o **tipo de retorno do subprograma**.

Em **C**, o cabeçalho dos subprogramas – sendo chamados de funções – traz, em ordem: o **tipo de retorno**, o **nome** e a **lista de parâmetros**, como a seguir:

```c
float calculaIMC (int peso, float altura)
```
  
Em Python, as funções definidas pelo desenvolvedor devem ser precedidas pela palavra reservada `def`. Não são especificados o tipo de retorno nem os tipos dos parâmetros, como no exemplo a seguir:

```python
def calculaIMC (peso, altura)  
```

Em Python, as sentenças de função `def` são executáveis. Isso implica que a função só pode ser chamada após a execução da sentença `def`. Veja o exemplo na Figura 16:

```python
escolha = input("Escolha uma opção de função: 1 ou 2")
 if escolha == 1:
   def func1(x):
     return x + 1
 else:
   def func2(x):
    return x + 2

s = func1(10)
print(s)  
```
  
A função `func1()` só pode ser chamada caso a variável escolha seja igual a `1`. Ou seja, o usuário deverá inserir `1` quando solicitado (na linha 1), para que a linha 9 possa ser executada sem que seja gerado um erro.
  
### PARÂMETROS
Usualmente, um subprograma executa cálculos e operações a partir de dados que ele deve processar. Existem duas maneiras de o subprograma obter esses dados: acessando variáveis não locais, mas visíveis para o subprograma, ou pela passagem de parâmetros.

Quando o subprograma recebe os parâmetros adequados, ele pode ser executado com quaisquer valores recebidos. Porém, quando ele manipula variáveis não locais, uma forma de evitar alterações indevidas nessas variáveis é fazendo cópias locais delas. De acordo com Sebesta (2018), o acesso sistemático a variáveis não locais pode diminuir a confiabilidade do programa.

São denominados parâmetros formais aqueles do cabeçalho do subprograma.

Quando o subprograma é chamado, é necessário escrever o nome do subprograma e a lista de parâmetros a serem vinculados aos parâmetros formais dele, que são denominados parâmetros reais ou argumentos.

No exemplo da Figura 16, existe o cabeçalho da função func1 na linha 3, com o parâmetro formal x. Na linha 9, a função func1 é chamada com o parâmetro real 10.

Em Python, é possível estabelecer valores padrão para os parâmetros formais. O valor padrão é usado quando a chamada da função ocorre sem nenhum parâmetro real. Veja o exemplo de definição e chamada da função taxímetro na Figura 17:

```python
def taximetro(distancia, multiplicador=1):
  largada = 3
  km_rodado = 2
  valor = (largada + distancia * km_rodado) * multiplicador
  return valor 
 
pagamento = taximetro(3.5)
print(pagamento)
```
  
Observe que mesmo com a definição da linha 1 de dois parâmetros formais, a chamada da função na linha 8 ocorre apenas com um parâmetro real.
  
A palavra reservada `return` indica que a função **retorna** algum valor. Isso implica que o valor retornado seja armazenado em uma variável do programa chamador (como ocorre na linha 8), ou utilizado como parâmetro para outra função.
  
### Atenção!
Retornar um valor é diferente de imprimir na tela. Ao utilizar a função `print()`, ocorre apenas a impressão de algo na tela, o que não significa que tenha havido retorno de qualquer função definida pelo usuário.
  
## PROCEDIMENTOS E FUNÇÕES
Os **subprogramas** podem ser, distintamente, **procedimentos** e **funções**. De acordo com Sebesta (2018):
  
<table>
  <tr>
    <td><b>Procedimentos</b></td>
    <td><b>Funções</b></td>
  </tr>
   <tr>
    <td>São aqueles que não retornam valores.</td>
    <td>São aquelas que retornam valores.</td>
  </tr>
</table>

Na maioria das linguagens que não explicita a diferença entre eles, as funções podem ser definidas sem retornar qualquer valor, tendo comportamento de procedimento. Esse é o caso de Python. Veja o exemplo da Figura 18:

```python
def func1(x):
  x = 10
  print(f'Função func1 - x = {x}')

def func2(x):
  x = 20
  print(f'Função func2 - x = {x}')

x = 0
 func1(x)
 func2(x)
print(f'Programa principal - x = {x}')  
```
  
As funções `func1(x)` e `func2(x)` não possuem qualquer retorno. Ou seja, são funções com **comportamento de procedimentos**.

## AMBIENTES DE REFERENCIAMENTO LOCAL
  
### Variáveis locais
Quando um subprograma define suas **próprias variáveis**, estabelece ambientes de referenciamento local. Essas variáveis são chamadas de **variáveis locais**, com seu escopo usualmente sendo o corpo do subprograma. As variáveis locais podem ser:

#### Dinâmicas da pilha
São vinculadas ao armazenamento no início da execução do subprograma e desvinculadas quando essa execução termina. As variáveis locais dinâmicas da pilha têm diversas vantagens, e a principal delas é a **flexibilidade**. Suas principais desvantagens são o **custo do tempo** – para alocar, **inicializar** (quando necessário) e **liberar tais variáveis para cada chamada ao subprograma** – e o fato de que os **acessos a essas variáveis locais devem ser indiretos**, enquanto os acessos às variáveis estáticas podem ser diretos.
  
#### Atenção!
Nas linguagens **C** e **C++**, as **variáveis locais** são _dinâmicas da pilha_, a menos que sejam especificamente declaradas como **static**. **Todas as variáveis locais em Python são dinâmicas da pilha**. As **variáveis globais** são declaradas em definições de método, e qualquer variável declarada global em um método precisa ser definida fora dele. Caso haja uma atribuição à variável local com mesmo nome de uma variável global, esta é implicitamente declarada como local.
  
Voltando ao exemplo da Figura 18, vamos detalhar as funções func1(x) e func2(x):

- As linhas 1, 2 e 3 definem a função `func1(x)`, que recebe o parâmetro `x`, mas tem uma variável local de nome `x`, cujo valor atribuído é `10`;
- Analogamente, a função `func2(x)` – definida nas linhas 6, 7 e 8 – que recebe o parâmetro `x` e tem uma variável de mesmo nome, mas com valor atribuído `20`;
- O programa principal tem uma variável global de mesmo nome `x`, cujo valor atribuído é `0`, na linha 11;
- Veja que as chamadas às funções `func1(x)` e `func2(x)` ocorrem nas linhas 12 e 13, quando a variável `x` global já recebeu o valor `0`. Porém, ao serem executadas, cada uma dessas funções tem a sua própria variável local, a quem todas as referências internas são feitas.
  
Confira a execução desse exemplo na Figura 19:
  
```python
Função func1 - x = 10
  
Função func2 - x = 20

Programa principal - x = 0  
```
  
Mesmo com a variável global tendo valor nulo, cada variável local das funções `func1(x)` e `func2(x)` tem seu próprio valor, e não ocorrem alterações na variável global mesmo com as atribuições das linhas 2 e 7.
  
Para alterar a variável global `x`, seria necessário explicitar dentro de cada função que o nome `x` é referente a ela. Isso pode ser feito com a palavra reservada global. Além de explicitar a referência à variável global, as funções `func1(x)` e `func2(x)` não recebem mais os parâmetros de mesmo nome, já que fazem referência à variável global. Veja como ficaria o nosso exemplo com essa pequena alteração na Figura 20:
  
```python
def func1():
  global x
  x = 10
  print(f'Função func1 - x = {x}')

def func2():
  global x
  x = 20
   print(f'Função func2 - x = {x}')

13 x = 0
14 func1()
15 func2()
12 print(f'Programa principal - x = {x}')
```
  
Observe agora a execução desse exemplo alterado na Figura 21:

```python
Função func1 - x = 10
Função func2 - x = 20
Programa principal - x = 20  
```
  
Percebe-se que o `print()` do programa principal está na linha 16, depois da chamada à função `func2(x)`. Dessa forma, a variável global `x` foi alterada na execução da `func2(x)` e fica com o valor `20` quando a execução volta ao programa principal.

## Subprogramas aninhados
Em Python, e na maioria das linguagens funcionais, é permitido aninhar subprogramas. Porém, as linguagens **C** e **C++** não permitem essa prática. Veja o exemplo da Figura 22:
  
```python
 def func1():
   global x
   x = 10
   print(f'Função func1 - x = {x}')
 
  
def func2():
  global x
  x = 20
  print(f'Função func2 - x = {x}')

  
x = 0
func1()
func2()
print(f'Programa principal - x = {x}')  
```
  
Observe agora a execução desse exemplo alterado na Figura 21:

```python
Função func1 - x = 10
Função func2 - x = 20
Programa principal - x = 20
```
  
Percebe-se que o `print()` do programa principal está na linha 16, depois da chamada à função `func2(x)`. Dessa forma, a variável global `x` foi alterada na execução da `func2(x)` e fica com o valor `20` quando a execução volta ao programa principal.

## Subprogramas aninhados
Em Python, e na maioria das linguagens funcionais, é permitido aninhar subprogramas. Porém, as linguagens **C** e **C++** não permitem essa prática. Veja o exemplo da Figura 22:

```python
def taximetro(distancia)::
   def calculaMult():
     if distancia < 5:
         return 1.2
     else:
        return 1
   multiplicador = calculaMult()
   largada = 3
   km_rodado = 2
   valor = (largada + distancia * km_rodado) * multiplicador
   return valor

                      
dist = eval(input("Entre com a distancia a ser percorrida em km: "))
pagamento = taximetro(dist)
print(f'O valor a pagar é R$ {pagamento}')  
```
                      
A função `taximetro()` tem, dentro de sua definição, a definição de outra função denominada `calculaMult()`. Na linha 7, a função `calculaMult()` é chamada e o seu retorno é armazenado na variável **multiplicador**.

## MÉTODOS DE PASSAGENS DE PARÂMETROS
Os **métodos de passagem de parâmetros** são as maneiras que existem para transmiti-los ou recebê-los dos subprogramas chamados. Os parâmetros podem ser passados principalmente por:
                      
### Valor
O **parâmetro formal** funciona como uma variável local do subprograma, sendo inicializado com o valor do parâmetro real. Dessa maneira, não ocorre alteração na variável externa ao subprograma, caso ela seja passada como parâmetro.
                      
### Referência
Em vez de passar o valor do **parâmetro real**, é transmitido um caminho de acesso (normalmente um endereço) para o subprograma chamado. Isso fornece o caminho de acesso para a célula que armazena o parâmetro real. Assim, o subprograma chamado pode acessar o parâmetro real na unidade de programa chamadora.
                      
### Saiba mais +
Na **linguagem C**, utilizamos ponteiros para fazer a passagem de parâmetros por referência. As **transmissões de parâmetros** que não sejam ponteiros utilizam a passagem por valor.
                      
O método de passagem de parâmetros de Python é chamado **passagem por atribuição**. Como todos os valores de dados são objetos, toda variável é uma referência para um objeto. Ao se estudar orientação a objetos, fica mais clara a diferença entre a passagem por atribuição e a passagem por referência. **Por enquanto, podemos entender que a passagem por atribuição é uma passagem por referência, pois os valores de todos os parâmetros reais são referências**.

## RECURSIVIDADE
Uma **função recursiva** é aquela que chama a si mesma. Veja o exemplo da função `regressiva()`, como mostrado na Figura 23:

```python
 def regressiva(x):
  print(x)
  regressiva(x - 1)
```
Na implementação da função `regressiva()`, tendo `x` como parâmetro, ela própria é chamada com o parâmetro `x – 1`. Vamos analisar a chamada regressiva(2):

1. Ao chamar regressiva(2), o valor 2 é exibido na tela pela linha 2, e ocorre uma nova chamada da função regressiva() na linha 3, com o parâmetro 1. Vamos continuar com esse caminho de execução da regressiva(1).

2. Ao chamar regressiva(1), o valor 1 é exibido na tela pela linha 2, e ocorre uma nova chamada da função regressiva() na linha 3, com o parâmetro 0.

3. Ao chamar regressiva(1), o valor 1 é exibido na tela pela linha 2, e ocorre uma nova chamada da função regressiva() na linha 3, com o parâmetro 0.
 
### Atenção
Conceitualmente, essa execução será repetida indefinidamente até que haja algum erro por falta de memória. Perceba que não definimos adequadamente uma condição de parada para a função `regressiva()`, o que leva a esse comportamento ruim.
                      
Em Python, o interpretador pode interromper a execução indefinida, mas essa não é uma boa prática. Uma forma de contornar esse problema é definir adequadamente uma condição de parada, como no exemplo da Figura 24:

```python
def regressiva(x):
     if x <= 0:
          print("Acabou")
     else:
          print(x)
          regressiva(x-1)
```
  
Uma **função recursiva** que termina tem:

- Um ou mais casos básicos, que funcionam como condição de parada da recursão.

- Uma ou mais chamadas recursivas, que têm como parâmetros valores mais próximos do(s) caso(s) básico(s) do que o ponto de entrada da função.
  
Alguns exemplos clássicos de funções que podem ser implementadas de forma recursiva são **o cálculo do fatorial de um inteiro não negativo** e a **sequência de Fibonacci**, que serão explorados a seguir.

### A função recursiva fatorial
A `função matemática fatorial de um inteiro não negativo n` é calculada por:
  
![função recursiva fatorial](https://user-images.githubusercontent.com/61624336/138567412-761c5bad-3216-4e3e-a59a-99a7706c8343.png)

Além disso, ela pode ser definida recursivamente por:

![função recursiva fatorial](https://user-images.githubusercontent.com/61624336/138567565-ae25867c-7f2a-4236-bb05-90b0c2280896.png)

Uma implementação recursiva da função fatorial em Python está na Figura 25:

```python
  def fatorial(n): 
       if n == 0 or n == 1:
           return 1
       else:
           return n*fatorial(n-1)  
```  

Vale ressaltar que a função fatorial também poderia ter sido implementada de forma **não recursiva**, como mostrado na Figura 26:

```python
 def fatorial(n):
      fat = 1
      if n == 0 or n == 1:
           return fat
      else:
          for x in range(2, n + 1):
                fat = fat*x
          return fat
```    
  
Porém, neste tópico, o intuito principal é explorar a recursividade.

### A sequência de Fibonacci
A **sequência de Fibonacci** é: `1, 1, 2, 3, 5, 8, 13, 21...` Os dois primeiros termos são `1` e, a partir do 3º termo, cada termo é a soma dos dois anteriores.

Uma possível implementação recursiva de função que determina o **n-ésimo** termo da sequência de Fibonacci está na Figura 27:

```python
 def fibo(n):
      if n == 1 or n == 2:
           return 1
      else:
          return fibo(n - 1) + fibo(n - 2)
```
  
- A **linha 2** traz as condições de parada.
- A **linha 5** traz as chamadas recursivas para calcular os dois termos anteriores da sequência.
  
## DOCSTRINGS
**Em Python, é possível definir uma string que serve como documentação de funções definidas pelo desenvolvedor**. Ao chamar o utilitário `help()` passando como parâmetro a função desejada, essa string é exibida. Veja a Figura 28 e a Figura 29:
  
```python
def fibo(n):
     'Determina o n-ésimo termo da sequência de Fibonacci'
          if n == 1 or n == 2:
          return 1
     else:
          return fibo(n - 1) + fibo(n - 2)

print(help(fibo))  
```
  
~~~python
 fibo(n)
  Determina o n-ésimo termo da sequência de Fibonacci
~~~
  
- Na Figura 28, a **linha 2** mostra a declaração da docstring.
- A **linha 8** mostra a impressão na tela da chamada `help(fibo)`. Na Figura 29, está o resultado da execução desse programa.
  
Python oferece, em seu núcleo, algumas funções que já utilizamos, como `print()` e `input()`, além de classes como `int`, `float` e `str`. Logicamente, o núcleo da linguagem Python disponibiliza muitas outras funções (ou métodos) e classes além das citadas. Mas, ainda assim, ele é pequeno, com objetivo de simplificar o uso e ganhar eficiência. Para aumentar a disponibilidade de funções, métodos e classes, o desenvolvedor pode usar a biblioteca padrão Python. Apresentaremos alguns dos principais recursos dessa biblioteca e a forma de utilizá-los.

# 🐍 BIBLIOTECA PADRÃO PYTHON 📚
A **biblioteca padrão Python** consiste em milhares de **funções**, **métodos** e **classes** relacionados a determinada finalidade e organizados em componentes chamados **módulos**. São **mais de 200 módulos** que dão suporte, entre outras coisas, a:
  
- Operações matemáticas;
- Interface gráfica com o usuário (GUI);
- Funções matemáticas e geração de números pseudoaleatórios.
  
<blockquote><b>Atenção!</b> É importante lembrar dos conceitos de classes e objetos, pois eles são os principais conceitos do paradigma de programação orientada a objeto. As classes são fábricas, que podem gerar instâncias chamadas objetos. Uma classe <b>Pessoa</b>, por exemplo, pode ter como atributos nome e CPF. Ao gerar uma instância de <b>Pessoa</b>, com nome João da Silva e CPF 000.000.000-00, temos um objeto.</blockquote>

<blockquote><b>Saiba+</b> Para melhor compreensão dos conceitos de classe e objeto, pesquise sobre paradigma orientado a objeto.</blockquote>
  
## COMO USAR UMA FUNÇÃO DE MÓDULO IMPORTADO
Para usar as **funções** e os **métodos** de **um módulo**, são necessários dois passos:
  
- Fazer a importação do módulo desejado com a instrução:
```python
import nome_modulo
```
  
- Chamar a função desejada, precedida do nome do módulo, com a instrução:
```python
nome_modulo.nome_funcao(paramêtros)
```
  
Como exemplo, vamos importar o módulo **math** (dedicado a operações matemáticas) e calcular a **raiz quadrada** de 5, por meio da função `sqrt()`. Observe a Figura 30:

<pre>
>>>import math
>>>math.sqrt(5)
2.23606797749979
</pre>

A partir desse ponto, serão apresentados os principais aspectos dos seguintes módulos:

- `math` usado para operações matemáticas;
- `random` usado para gerar números pseudoaleatórios;
- `smtplib` usado para permitir envio de e-mails;
- `time` usado para implementar contadores temporais;
- `tkinter` usado para desenvolver interfaces gráficas.
  
## MÓDULO `MATH`
Esse módulo provê acesso a **funções matemáticas de argumentos reais**. As funções **não podem ser usadas com números complexos**.

O módulo `math` tem as funções listadas na Tabela 7, entre outras:
  
<table>
  <tr>
    <td><b>Função</b></td>
    <td><b>Retorno</b></td>
  </tr>
  <tr>
    <td><code>sqrt(x)</code></td>
    <td>Raiz quadrada de x</td>
  </tr>
  <tr>
    <td><code>ceil(x)</code></td>
    <td>Menor inteiro maior ou igual a x</td>
  </tr>
  <tr>
    <td><code>floor(x)</code></td>
    <td>Maior inteiro menor ou igual a x</td>
  </tr>
  <tr>
    <td><code>cos(x)</code></td>
    <td>Cosseno de x</td>
  </tr>
  <tr>
    <td><code>sin(x)</code></td>
    <td>Seno de x</td>
  </tr>
  <tr>
    <td><code>log(x,b)</code></td>
    <td>Logaritmo de x na base b</td>
  </tr>
  <tr>
    <td><code>pi</code></td>
    <td>Valor de Pi (3.141592...)</td>
  </tr>
  <tr>
    <td><code>e</code></td>
    <td>Valor de e (2.718281...)</td>
  </tr>
</table>
  
<blockquote><b>Saiba+</b> Para mais informações sobre o módulo <code>math</code>, visite a biblioteca Python.</blockquote>  

## MÓDULO `RANDOM`
Esse módulo implementa geradores de números pseudoaleatórios para várias distribuições.

- **Números inteiros**: Para inteiros, existe uma seleção uniforme a partir de um intervalo.
  
- **Sequências**: Para sequências, existem:
  - Uma seleção uniforme de um elemento aleatório;
  - Uma função para gerar uma permutação aleatória das posições na lista;
  - Uma função para escolher aleatoriamente sem substituição.
  
## Distribuições de valores reais
A Tabela 8 mostra algumas das principais funções disponíveis para distribuições de valores reais no módulo `random`. 
  
# 📦 `pip` - Package Installer for Python
<div align="center"><img src="https://cloudo3.com/ArticleIMG/image-0724071013041.jpg" height="277"></div><br \>

## Autor
| [<img src="https://avatars.githubusercontent.com/u/61624336?v=4" width="110"><br><sub>@IsaacAlves7</sub>](https://github.com/IsaacAlves7) |
| :---: |
