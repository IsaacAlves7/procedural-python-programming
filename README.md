# <img src="https://emojis.slackmojis.com/emojis/images/1516924249/3439/python_explode.gif?1516924249" height="30"> It's a repository of Python programming 🐍🔢
<blockquote>I created this repository for my Python language Full-Stack Development learning.</blockquote>

<a href="https://github.com/IsaacAlves7/python-programming"><img src="https://cdn.worldvectorlogo.com/logos/python-3.svg" heigth="177"/></a>

## 🎒 Prerequisites and repositories 📚:
<blockquote>⚠️ <b>WARNING:</b> It's important to install each one of components shown and to execute the codes on your own machine. Besides that, please note that repository is only focused in Python development, if you want to learn about HTML5, CSS3, JS or Python Frameworks i recommend to access another repositories, click on links bellow!</blockquote>

[![Web](https://img.shields.io/badge/-HTML5‍‍and‍‍css3‍‍development-3776AB?style=for-the-badge&logo=HTML5&logoColor=white)](https://github.com/IsaacAlves7/html5-and-css3-development)
[![Pypi](https://img.shields.io/badge/-Pypi-3776AB?style=for-the-badge&logo=PyPi&logoColor=white)](https://pypi.org/)
[![Django](https://img.shields.io/badge/-Django-3776AB?style=for-the-badge&logo=Django&logoColor=white)](https://pypi.org/)
[![Flask](https://img.shields.io/badge/-Flask-3776AB?style=for-the-badge&logo=Flask&logoColor=white)](https://pypi.org/)
[![Databases](https://img.shields.io/badge/-Databases-3776AB?style=for-the-badge&logo=PostgreSQL&logoColor=white)](https://github.com/IsaacAlves7/sql-language)
[![DevOps](https://img.shields.io/badge/-DevOps-3776AB?style=for-the-badge&logo=ReactOS&logoColor=white)](https://github.com/IsaacAlves7/systems-architecture)

<hr>

# 🐍 A abstração nas linguagens de programação 🔢
**Abstração** é o processo de identificação das qualidades e/ou propriedades relevantes para o contexto que está sendo analisado e desprezando o que seja irrelevante. Um **modelo** é uma _abstração_ da realidade.

Um **programa de computador** é um _modelo_, pois representa a solução de um problema em termos algorítmicos. Assim sendo, a _abstração_ permeia toda a atividade de programação de computadores.

A **linguagem de máquina** foi a primeira a ser criada para a prática de programação. Trata-se da _linguagem nativa do computador_, a única que ele, de fato, compreende. Uma linguagem muito complicada para ser entendida pelas pessoas, em que um comando que soma 2 números, é formado por uma sequência de 1 e 0, muito difícil de ser memorizada, usada e, mais ainda, de ser entendida por terceiros.

As primeiras linguagens de programação, porém, não reconheciam o papel crucial que a abstração desempenha na programação. Por exemplo, no início da década de 1950, o único mecanismo de abstração fornecido pela _linguagem de montagem_, ou **Assembly**, em relação às linguagens de máquina eram os **nomes simbólicos**.

<blockquote><b>Você sabia? :</b> O programador podia empregar termos relativamente <i>autoexplicativos</i> (nomes simbólicos) para nomear códigos de operação (<code>ADD = soma, SUB = subtração, M = multiplicação e DIV = divisão</code>) e <i>posições de memória</i>. A <b>linguagem de montagem</b> (<code><b>Assembly</b></code>) melhorou a vida do programador, porém obrigava-o a escrever 1 linha de código para cada instrução que a máquina deve executar, forçando-o a pensar como se fosse uma máquina.</blockquote>

Um pouco mais adiante, visando a aumentar o poder de abstração das linguagens de forma a permitir uma melhor performance dos programadores, surgem as linguagens de alto nível, próximas à linguagem humana e mais distantes das linguagens **Assembly** e de **máquina**.

A tabela, a seguir, exibe, à esquerda, um programa-fonte, escrito numa linguagem de alto nível, a **linguagem Python**. Ao centro, temos o código equivalente na **linguagem Assembly** para o sistema operacional Linux e, à direita, o respectivo código na **linguagem de máquina**, de um determinado processador. Observe:

<table>
  <tr>
    <td>Linguagem Python</td>
    <td>Linguagem Assembly</td>
    <td>Linguagem de Máquina</td>
  </tr>
  <tr>
    <td>
      <pre>
        def swap(self, v, k):
          temp = self.v[k];
          self.v[k] =
          self.v[k+1];
          self.v[k+1]= temp;
      </pre>
    </td>
    <td>
     <pre>
       swap:
        Muli $2,$5,4
        Add $2,$4,$2
        Lw $15,0($2)
        Lw $16,4($2)
        Sw $16,0($2)
        Sw $15,4($2)
        Jr $31
      </pre>
    </td>
    <td>
     <pre>
       00000000001111111111100000000001
       00011111111000000111000011111101
       11111000001100000111111110000000
       10000000100000001000000010000000
       00000000010000000001000000000010
       00000000000000001111000010010101
       00000000111000111111001111111111
      </pre>
    </td>
  </tr>
</table>

A imagem abaixo ilustra o conceito de abstração, em que a partir da linguagem de máquina, cria-se camadas (de abstração) para facilitar a vida do programador.

![img_11](https://user-images.githubusercontent.com/61624336/132106631-dc9bfee1-0706-4563-9a4a-ea19b2567dca.jpg)

<h4 align="center">Crescimento do nível de abstração.</h4>

1. É representado pelo **hardware**, conjunto de circuitos eletrônicos.
2. É representado pela **linguagem de máquina** (1 e 0), única que o hardware entende.
3. É representado pela **linguagem Assembly** (mneumônicos).
4. É representado pelas **linguagens de alto nível**, próximas à língua do usuário e distantes da linguagem computacional. **Python** e **Java** são linguagens de programação representativas da classe LP de alto nível (LP = Linguagem de Programação).

## Por que estudar linguagens de programação?

O estudante e/ou programador que se dispuser a gastar seu tempo aprendendo linguagens de programação terá as seguintes vantagens:

- Maior capacidade de desenvolver soluções em termos de programas — compreender bem os conceitos de uma LP pode aumentar a habilidade dos programadores para pensar e estruturar a solução de um problema.
- Maior habilidade em programar numa linguagem, conhecendo melhor suas funcionalidades e implementações, ajuda para que o programador possa construir programas melhores e mais eficientes. Por exemplo, conhecendo como as LPs são implementadas, podemos entender melhor o contexto e decidir entre usar ou não a recursividade, que se mostra menos eficiente que soluções iterativas.
- Maiores chances de acerto na escolha da linguagem mais adequada ao tipo de problema em questão, quando se conhece os recursos e como a linguagem os implementa. Por exemplo, saber que a linguagem C não verifica, dinamicamente, os índices de acesso a posições de vetores pode ser decisivo para sua escolha em soluções que usem frequentemente acessos a vetores.
- Maior habilidade para aprender novas linguagens. Quem domina os conceitos da orientação a objeto, tem mais aptidão para aprender Python, C++, C# e Java.
- Amplo conhecimento dos recursos da LP reduz as limitações na programação.
- Maior probabilidade para projetar novas LP, aos que se interessarem por esse caminho profissional: participar de projetos de criação de linguagens de programação.
- Aumento da capacidade dos programadores em expressar ideias. Em geral, um programador tem expertise em poucas variedades de linguagens de programação, dependendo do seu nicho de trabalho. Isso, de certa forma, limita sua capacidade de pensar, pois ele fica restrito pelas estruturas de dados e controle que a(s) linguagem(ns) de seu dia a dia permitem. Conhecer uma variedade maior de recursos das linguagens de programação pode reduzir tais limitações, levando, ainda, os programadores a aumentar a diversidade de seus processos mentais.

Quanto maior for o leque de linguagens que um programador dominar e praticar, maiores as chances de conhecer e fazer uso das propriedades superlativas da(s) linguagem(ns) em questão.

# 🐍 Classificação das linguagens de programação ✨
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
  <tr>
    <td>Características x Critérios de Avaliação de LPs</td>
  </tr>
</table>

# 🐍 The History of Python language 🐍
<div align="center"><img height="127" src="https://fanart.tv/fanart/tv/75853/hdtvlogo/monty-pythons-flying-circus-5176132ff29d3.png"/><img height="127" src="https://symbols.getvecta.com/stencil_296/27_python-bivittatus-burmese-python.ef91774c2c.svg"/><img src="https://symbols.getvecta.com/stencil_92/75_python-vertical.6c7f1f8721.svg" height="127"></div><br \>

A classificação das linguagens em paradigmas permite que entendamos qual é o melhor deles para solucionar determinado problema e, a partir daí, escolher a linguagem de programação (pertencente a esse paradigma) mais adequada, conforme características e especificidades do contexto em que se aplica o problema.

A linguagem Python foi escolhida como instrumento para o desenvolvimento desta disciplina, pois além de ser multiparadigma (possibilita escrever programas em diferentes paradigmas) e de uso geral, vem se destacando e sendo cada vez mais utilizada entre os novos desenvolvedores por vários motivos:

- Facilidade de aprendizado;
- Boa legibilidade de código;
- Boa facilidade de escrita;
- Produtividade e confiabilidade.
- Possui, ainda, comunidade de desenvolvedores crescente e vasta biblioteca, repleta de funções, aplicada a diversas áreas da ciência, assim como o crescente números de frameworks desenvolvidos para a linguagem.

<p>Surgiu em 1989, criado por <a href="https://github.com/gvanrossum">Guido Van Rossum</a>, em Amsterdã, na Holanda. A origem do nome foi inspirado na comédia inglesa "<i>Monty Python and the Flying Circus</i>", na década de 1970.

A linguagem <b>Python</b> é uma linguagem de programação, com características interessantes:
<ul>
  <li>É interpretada e compilada, ou seja, o interpretador Python executa o código fonte diretamente, traduzindo cada trecho para instruções de máquina;</li>
  <li>É de alto nível, ou seja, o interpretador se vira com detalhes técnicos do computador. Assim, desenvolver um código mais simples do que em linguagem de baixo nível, nas quais o programador deve se preocupar com detalhes da máquina;</li>
  <li>É de propósito geral, ou seja, podemos usar Python para desenvolver programas em diversas áreas. Ao contrário de linguagens de domínio específico, que são especializados e atendem somente a uma aplicação específica;</li>
  <li>Tem tipos dinâmicos, ou seja, o interpretador faz a magia de descobrir o que é cada variável;</li>
</ul>
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

## Principais áreas de atuação com a linguagem Python
<li>IA-Inteligência Artificial</li>
<li>IoT-Internet das Coisas</li>
<li>Big Data</li>
<li>Data Analysis</li>
<li>Data Science</li>
<li>Computação 3D</li>
<li>Biotecnologia</li>
<li>Desenvolvimento Web - (Back-end)</li>
