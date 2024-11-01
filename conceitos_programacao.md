# Conceitos de programação

Aqui vamos discutir alguns conceitos interessantes sobre programação, são assuntos inicias no universo da programação

## Algoritmos
  
Algoritmos são uma sequência de instruções usadas para resolver um problema.

## Automação
  
Automação é a realização de algoritmos feito por máquinas, sejam esses dispositivos mecânicos ou eletrônicos.

## Hardware

É a parte física do computador

## Software

É a parte lógica do computador, são os programas, sistemas operacionais, aplicativos, jogos, dentre outros.

## Programa e Algoritmo

De maneira geral e simples, programas são algoritmos executados pelo computador. O computador automatiza a execução dos algoritmos, como processamento de dados, cálculos.

## O que é preciso para construir um programa de computador?

### 1. Uma liguagem de programação

Um conjunto de regras **léxicas** (ortografia) e **sintáticas** (gramática) para se escrever programas.
     
A léxica diz respeito a correção de palavras isoladas.
     
A sintática diz respeito a correção de sentenças.
     
Alguns exemplos de linguagens de programação são C, Pascal, C++, Java, C#, Python, Ruby, PHP, JavaScript, etc.
     
### 2. Uma IDE
 
**I**ntegrated **D**evelopment **E**nvironment (Ambiente Indegrado de Desenvolvimento).
  
É um conjunto de softwares que são utilizados para construção de programas, como Code Blocks para C e C++, Eclipse e NetBeans para Java, Visual Studio para C#.
  
Dentre as funcionalidades de uma IDE temos a edição do código fonte, depuraçao, testes, build, templates e ajuda em algumas outras tarefas no projeto.
  
Também é possível construir programas usando editores de textos, como o Visual Studio Code, com o uso de algumas extensões eles tem tanto poder quanto uma IDE, podendo ajudar bastante no desenvolvimento de programas.
  
### 3. Um compilador
 
É um software que transforma o código fonte em código objeto.

O código fonte é o código escrito pelo programador em uma liguagem de programação, no entando, esse código não é entendido pelo computador, ele precisa ser convertido para que seja lido pelo computador.

É necessário que o código fonte passe pelo processo de compilação, onde o código fonte é convertido em código objeto, processo realizado pelo compilador. Durante a compilação é feita uma análise léxica e sintática do código fonte.

Essas são as linguagens compiladas.

### 4. Um gerador de código ou máquina virtual
 
Um software que permite que o programa seja executado.
  
Após a compilação o código objeto precisa passar pelo gerador de código, passando por uma construção ou build, que gera um código executavel. Exemplos de liguagens que usam essa abordagem são as liguagens C e C++,

No entanto, existem algumas linguagens que passam por um processo diferente, são liguagens interpretadas. Elas usam um interpretador para serem executadas. O interpretador faz a análise do código sob demanda e realizando a execução só quando aquele trecho de código é requisitado. Alguns exemplos de linguagens interpretadassão JavaScript, Python e PHP.

Também existe uma abordagem híbrida, onde o código fonte passa por uma pré-compilação, gerando um código objeto chamado de Bytecode, esse bytecode é interpretado por uma máquina virtual, que faz a execução do código sob demanda. Essa aboragem híbrida é adotada por liguagens como Java (JVM) e C# (Microssoft .NET Framework).

### Compilação e Interpretação

#### Vantagens da Compilaçao

Como todo o processo de compilação é feito previamente os programas tendem a serem mais rápidos

Além de um maior suporte do compilador, que faz toda a análise léxica e sintática previamente, evitando a execução de códigos com problemas.

#### Vantagens da  Interpretação

Uma maior facilidade de manutenção no código, pois não é necessário realizar todo o processo de compilação, a alteração pode ser feita pontualmente em um único arquivo.

Geralmente são linguagens mais expressivas, exigindo menos cógido para desenvolver algo funcional e elegante.

Não é necessário recompilar o código para cada plataforma, basta usar um interpretador que seja capaz de interpretas aquele código, independente do sistema operacional, seja ele Linux ou Windows.
