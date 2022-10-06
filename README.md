<a href="https://github.com/IsaacAlves7/python-programming"><img src="https://user-images.githubusercontent.com/61624336/193806052-860b7136-6764-448d-91ef-a444427a26b3.png" width="100%"/></a>

# <img src="https://emojis.slackmojis.com/emojis/images/1516924249/3439/python_explode.gif?1516924249" height="30"> It's a repository of Python language 🐍
<blockquote>I created this repository for my Python language Full-Stack Development learning.</blockquote>

<a href="https://github.com/IsaacAlves7/python-programming"><div align="center"><img src="https://user-images.githubusercontent.com/61624336/193809777-0c363bd5-112a-4707-8292-7e77eba6d858.png" height="307"/></div></a>

# 🐒 Paradigmas de desenvolvimento de software
<div align="center"><img src="https://user-images.githubusercontent.com/61624336/112900537-065ce480-90ba-11eb-86f7-f9006445876a.png"></div>

Hoje em dia, o desenvolvimento de sistemas se baseia em vários e diferentes paradigmas, tais como os listados a seguir:

- **Imperativo (Procedural)**: Segue sequências de comandos ordenados segundo uma lógica.
- **Funcional**: Trabalha com a divisão de problemas através de funções, que resolvem separadamente problemas menores e que, ao serem organizados, resolvem o problema como um todo.
- **Lógico**: Voltado ao desenvolvimento de problemas de lógica e usado em sistemas de inteligência computacional.
- **Orientado a Objetos (OO)**: Define um conjunto de classes para dividir o problema e realiza a interação entre as diferentes classes para também resolver o problema como um todo.

## Como funciona um programa de computador
<img src="https://user-images.githubusercontent.com/61624336/194329066-1643411f-3b8e-418a-a1dc-e8f5a157dc9d.png" align="right" height="177">

Um programa torna um computador utilizável. Sem um programa, um computador, mesmo o mais poderoso, nada mais é do que um objeto. Da mesma forma, sem um pianista, um piano não é mais do que uma caixa de madeira.

Os computadores são capazes de executar tarefas muito complexas, mas essa capacidade não lhes é inata. A natureza de um computador é bastante diferente.

Ele só pode executar operações extremamente simples, por exemplo, um computador não pode avaliar o valor de uma função matemática complicada por si só, embora isto não esteja fora do âmbito das possibilidades num futuro próximo.

Computadores contemporâneos só podem avaliar os resultados de operações muito fundamentais, como adicionar ou dividir, mas podem fazê-lo muito rapidamente, e podem repetir estas ações virtualmente um qualquer número de vezes.

Imagine que quer saber a velocidade média que alcançou durante uma longa viagem. Sabe a distância, sabe o tempo, precisa da velocidade.

Naturalmente, o computador será capaz de calcular isto, mas o computador não está ciente de coisas como distância, velocidade ou tempo. Portanto, é necessário instruir o computador a:

- Aceitar um número que represente a distância;
- Aceitar um número que represente o tempo de viagem;
- Dividir o valor anterior pelo último e armazenar o resultado na memória;
- Exibir o resultado (representando a velocidade média) num formato legível.

Estas quatro simples ações formam um **programa**. É claro que estes exemplos não são formalizados, e estão muito longe do que o computador pode compreender, mas são suficientemente bons para serem traduzidos para uma linguagem que o computador possa aceitar.

**Linguagem (Language)** é a palavra-chave.

## Linguagens naturais vs. linguagens de programação
Uma linguagem é um meio (e uma ferramenta) para expressar e registar pensamentos. Há muitas linguagens ao nosso redor. Algumas delas não requerem nem a fala nem a escrita, como a linguagem corporal; é possível expressar os seus sentimentos mais profundos com muita precisão sem dizer uma palavra.

Outra linguagem que usa diariamente é a sua língua materna, que usa para manifestar a sua vontade e para pensar na realidade. Os computadores também têm a sua própria linguagem, chamada **linguagem de máquina**, que é muito rudimentar.

Um computador, mesmo o mais sofisticado tecnicamente, é desprovido até mesmo de um vestígio de inteligência. Pode-se dizer que é como um cão bem treinado - responde apenas a um conjunto pré-determinado de comandos conhecidos.

Os comandos que reconhece são muito simples. Podemos imaginar que o computador responde a ordens como "pega nesse número, divide-o por outro e guarda o resultado".

Um conjunto completo de comandos conhecidos é chamado de **lista de instruções**, por vezes abreviado para **IL** (do inglês, Instruction List). Os diferentes tipos de computadores podem variar em função do tamanho das suas IL, e as instruções podem ser completamente diferentes em diferentes modelos.

> Nota: as linguagens de máquina são desenvolvidas por humanos.

# Sistemas Híbridos
O **processo híbrido** de implementação de uma linguagem de programação combina a execução rápida dos tradutores (compiladores) com a portabilidade dos interpretadores. O segredo é a geração de um código intermediário mais facilmente interpretável, porém não preso a uma plataforma (SO/Hardware).

Esse código intermediário não é específico para uma plataforma, possibilitando aos programas já compilados para esse código serem portados em diferentes plataformas, sem alterar e nem fazer nada. Para cada plataforma desejada devemos ter um interpretador desse código.

<blockquote>Duas importantes linguagens implementaram essa solução, com diferentes formas usando máquinas virtuais: <b>Python</b> e <b>Java</b>.</blockquote>

## Sistema de implementação de Python
<div align="center"><a href="https://www.jython.org/"><img src="https://media.geeksforgeeks.org/wp-content/uploads/python_working.png"></a></div>

**Python** usa um sistema híbrido, uma combinação de interpretador e tradutor (compilador). O **compilador** converte o código-fonte Python em um código intermediário, que roda numa máquina virtual, a **PVM** (Python Virtual Machine).

# Jython
<div align="center"><img src="https://user-images.githubusercontent.com/61624336/169595807-6c1e4c7c-a063-46df-a9e9-fd013a2ce598.svg" height="177"></div><br />

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

# 🏆 Certificações em Python
![3b74900cebc980b0fa8bcf4bb86c85488d6987c8](https://user-images.githubusercontent.com/61624336/194156459-aa30790d-bcb5-4966-af03-d2fb3acaa607.png)

- https://pythoninstitute.org/pcep
- https://pythoninstitute.org/pcap

## Cursos que oferecem certificações
- https://pythoninstitute.org/

# 🐍 The History of Python language
<div align="center"><img src="https://cdn.worldvectorlogo.com/logos/python-5.svg" height="177"></div><br \>

Dentre as diversas linguagens de programação que existem, **Python** é considerada uma das principais. Por sua simplicidade de aprendizado, ela tem sido utilizada em diversos cursos universitários como a primeira linguagem com que os alunos têm contato ao programar. Atualmente, conta com ampla participação da comunidade, além de ter seu desenvolvimento aberto e gerenciado pela organização sem fins lucrativos Python Software Foundation.

Recentemente, a _IEEE Computer Society_ classificou-a como a linguagem mais indicada para aprender em 2020. Isso se deve à sua eficiência no desenvolvimento de **machine learning**, **inteligência artificial**, **ciência**, **gestão** e **análise de dados**.

**Python** é uma linguagem de programação de alto nível, que permite ao programador utilizar instruções de forma intuitiva, tornando seu aprendizado mais simples do que o aprendizado de uma linguagem de baixo nível.

Nas linguagens de baixo nível, o programador precisa se expressar de forma muito mais próxima do que o dispositivo “entende”, levando naturalmente a um distanciamento da linguagem utilizada para comunicação entre duas pessoas.

A classificação das linguagens em paradigmas permite que entendamos qual é o melhor deles para solucionar determinado problema e, a partir daí, escolher a linguagem de programação (pertencente a esse paradigma) mais adequada, conforme características e especificidades do contexto em que se aplica o problema.

A linguagem Python foi escolhida como instrumento para o desenvolvimento desta disciplina, pois além de ser multiparadigma (possibilita escrever programas em diferentes paradigmas) e de uso geral, vem se destacando e sendo cada vez mais utilizada entre os novos desenvolvedores por vários motivos:

- Facilidade de aprendizado;
- Boa legibilidade de código;
- Boa facilidade de escrita;
- Produtividade e confiabilidade.
- Possui, ainda, comunidade de desenvolvedores crescente e vasta biblioteca, repleta de funções, aplicada a diversas áreas da ciência, assim como o crescente números de frameworks desenvolvidos para a linguagem.

<div align="center">

| [<img src="https://avatars.githubusercontent.com/u/2894642?v=4" width="177"><br><sub>Guido Van Rossum</sub>](https://github.com/gvanrossum) 
|:-:|
 
</div>

<p>Surgiu em 1989, criado por <a href="https://github.com/gvanrossum">Guido Van Rossum</a> como um hobby onde a ideia era dar continuidade a linguagem ABC que era desenvolvida no Centro de Pesquisa Holandês (CWI), em Amsterdã, na Holanda. 
 
O Python foi influenciada por ABC, que era uma linguagem pensada para iniciantes, devido a sua facilidade de aprendizado e utilização. Um dos objetivos de Van Rossum para a linguagem Python eram: 
 
- Uma linguagem fácil e intuitiva;
- Código aberto, para que todos possam contribuir;
- Código tão inteligível quanto o inglês;
- Adequado a tarefas diárias, e produtiva.
 
<img height="177" src="https://user-images.githubusercontent.com/61624336/193808960-f34bbd86-45e8-4208-955e-f0bfecbeebf1.jpg" align="right"/>

> A origem do nome foi inspirado na comédia inglesa "Monty Python and the Flying Circus", na década de 1970. 

No início dos anos 1990 e desde então tem aumentado sua participação no mundo da programação. Permite uma programação fácil e clara para escalas pequenas e grandes, além de enfatizar a legibilidade eficiente do código, notadamente usando espaços em branco significativos.
 
> Para a plataforma Windows, basta executar o instalador. Para outras plataformas, como em Linux ou macOS, geralmente o Python já faz parte do sistema, porém em alguns casos pode ser necessário compilador e instalar o interpretador a partir dos arquivos fonte.
 
## Características da Linguagem Python
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
 
### Resumindo as características
- Orientada a objetos com uma semântica dinâmica;
- Possui licença compatível com Software livre;
- Linguagem de altíssimo nível (VHLL);
- Tipagem dinâmica e forte;
- Aumenta a produtividade do desenvolvedor;
- A implementação oficial do Python é mantida pela PSF (Python Software Foundation) é escrita em C, e por isso, é também conhecida como CPython;
- Multiplataforma e multiparadigma (POO, funcional e procedural);
- Batteries Included;
- Organizada;
- Comunidade gigante e ativa;
- Curva de aprendizado baixa;
- Muitas Bibliotecas.

Por essas e várias outras características, o Python se torna uma linguagem simples, bela, legível e amigável. É uma linguagem muito utilizada por diversas empresas como Wikipédia, Microsoft, Google, Yahoo!, CERN, NASA, Facebook, AMAZON, Instagram, Spotify, Bitorrent Inc, Django e Dropbox.

### Principais áreas de atuação com a linguagem Python
<li>IA - Inteligência Artificial</li>
<li>Machine Learning</li>
<li>Deep Learning</li>
<li>IoT - Internet das Coisas</li>
<li>Big Data</li>
<li>Data Analysis</li>
<li>Data Science</li>
<li>Computação 3D</li>
<li>Biotecnologia</li>
<li>Bioinformática</li>
<li>Web Development (Back-end)</li>
<li>Cybersecurity</li>
<li>Game Development</li>
<li>Mobile Development</li>
<li>Desktop Development</li>
<li>DevOps</li>
<li>Automação</li>
<li>Cloud Computing</li>
<li>Estudos científicos como: Geologia, Astronomia, Física, Química, Matemática e etc</li>

## Python 3
<div align="center"><A href="https://python.org"><img src="https://cdn.worldvectorlogo.com/logos/python-4.svg" height="177"></a></div><br \>

Em 2008, é lançada a versão 3.0, que resolveu muitos problemas de design da linguagem e melhorou a performance. Algumas mudanças foram muito profundas dessa forma a versão 3.x não é retrocompatível.

Atualmente, estamos na versão **3.10.7** do Python.

# 📦 `pip` - Package Installer for Python
<div align="center"><img src="https://pypi.org/static/images/logo-small.95de8436.svg" height="177"></div><br \>

# 👹 Python-Ogre
<div align="center"><img src="https://upload.wikimedia.org/wikipedia/en/0/01/PythonOgreLogo.svg" height="177"></div><br \>

# 🦕 Django
<div align="center"><img src="https://cdn.worldvectorlogo.com/logos/django-community.svg" height="177"></div><br \>

# ⚗️ Flask
<div align="center"><img src="https://cdn.worldvectorlogo.com/logos/flask.svg" height="177"></div><br \>

