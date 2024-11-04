# Java

Aqui vamos falar sobre o Java e seu universo.

## O que é o Java?

O Java é uma linguagem de programação com suas regras léxicas e sintáticas, mas também é uma plataforma de desenvolvimento e execução que contém sua API (bibliotecas internas) e um ambinete de execução do código escrito em Java.

## Histórico

O Java foi criado para resolver alguns problemas da época como:

- Ponteiros e gerenciamento de memória
- Portabilidade e a necessiadade de reescrever códigos dependendo do sistema operacional
- Possibilidade de utilização em diversos dispositivos
- Custo

Criada pela Sun Mycrosystems no meio da década de 1990, foi adquirida pela Oracle Corporation em 2010.

## Aspectos notáveis

O código Java é compilado para bytecode e executado na máquina virtual JVM (**J**ava **V**irtual **M**achine).

É uma platforma portável, segura e robusta, que roda em vários dispositivos e domina o mercado corporativo desde o fim do século 20.

## Edições do Java

- Java ME - Java Micro Edition: é uma edição mais enxuta do java usada em dispositivos embarcasdos e móveis, podemos citar a IoT.
- Java SE - Java Standard Edition: é a principal edição com java, é o core do Java, mais destinada para aplicações desktop e servidores mas também pode ser usada em aplicações web.
- Java EE - Java Enterprise Edition: é uma conjunto de especificações Java para o desenvolvimento de aplicações corporativas (Servlet, JPA, Web Services, etc).

## JVM - Java Virtual Machine

A máquina virtual do Java é necessária para executar códigos Java.

## Estrutura de uma aplicação Java

O Java é uma linguagem orienteada a objetos, e a unidade lógica básica de uma liguagem orientada a objetos é uma classe, todo código Java esta dentro de classes.

Temos também os pacotes (package), que é um agrupagemento lógico de classes relacionadas.

No Java 9+ foi introduzido o conceito de módulos que é um agrupamento lógico de pacotes relacionados.

Por fim, temos uma aplicação composta por um conjunto módulos relacionados.

## Iniciando uma aplicação Java

Como dito antes, todo código java deve estar dentro de uma classe, e para iniciar uma aplicação Java é necessário que haja um método **main** dentro de uma classe, a seguir temos um exemplo:

```java
// Main.java
public class Main {
	public static void main(String[] args) {
		System.out.println("Hello World!");
	}
}
```

No código acima, temos uma classe com o nome `Main` (o nome da classe pode ser outro, não é o obrigatório que o nome da classe seja esse), dentro da classe temos a declaração de um método `main`, esse método será o ponto de entrada da aplicação, o código dentro dele será executado ao iniciarmos a aplicação.

## Variáveis e tipos primitivos

Os dados de um programa em execução são armazanados em variáveis. As variáveis são uma porção da memória (RAM) utilizada para armazenar dados durante a execução dos programas.

Para um programa usar um variável, ela precisa ser declarada. A sintaxe usada para declarar uma variável no Java é:

`<tipo> <nome> = <valor inicial>;`

Sendo que o valor inicial é opcional. Portanto, uma variável possui um nome, um tipo, um valor e um endereço na memória.

### Tipos primitivos do Java

Os tipos primitivos são os valores mais básicos que a linguagem Java pode manipular. São usados para armazenar valores simples, como números inteiros e caracteres. Entre os tipos primitivos do Java temos:

- Tipos númericos inteiros
  - byte: Tem 8 bits, com valores indo de -128 a 127 e valor padrão igual a 0
  - short: Tem 16 bits, com valores indo de -32768 a 32767 e valor padrão igual a 0
  - int: Tem 32 bits, com valores indo de -2147483648 a 2147483647 e valor padrão igual a 0
  - long: Tem 64 bits, com valores indo de -9223372036854770000 a 9223372036854770000 e valor padrão igual a 0L
- Tipos númericos com ponto flutuante
  - float: Tem 32 bits, com valores indo de -1,4024E-37 a 1,4028E+38 e valor padrão igual a 0.0F
  - double: Tem 64 bits, com valores indo de -4,94E-307 a 1,79E+308 e valor padrão igual a 0.0
- Caracter
  - char: Tem 16 bits e armazena caracteres unicode, com valores indo de `\u0000` a `\uFFFF` e valor padrão igual a `\u0000`
- Booleano
  - boolean: Tem 1 bit, com valor podendo ser `true` ou `false`, e valor padrão sendo `false`

Além dos tipos primitivos também é importante falar sobre o tipo String, que é usado para armazenar cadeias de caracteres, ou seja, palavras ou textos.

### Nomes de veriáveis

Os nomes dados a variáveis seguem algumas regras:

- Não podem começar com dígitos, somente letras ou _
- Não podem conter espaço em branco
- Não podem conter acentos ou til
- Geralmente, o padrão seguido no Java é o camel case

## Operadores de atribuição cumulativa

São uma combinação entre os operadores matemáticos simples com o operador de atribuição:

- `x += y` é equivalente a  `x = x + y`
- `x -= y` é equivalente a  `x = x - y`
- `x *= y` é equivalente a  `x = x * y`
- `x /= y` é equivalente a  `x = x / y`
- `x %= y` é equivalente a  `x = x % y`

## Operadores comparativos

São operadores usados para comparar um valor com outro, retornando um valor verdade, ou seja, `true` ou `false`. No Java temos os seguintes operadores de comparação:

- maior que (`>`)
- menor que (`<`)
- maior ou igual que (`>=`)
- menor ou igual que (`<=`)
- igual (`==`)
- diferente (`!=`)

## Operadores lógicos

São operadores que auxiliam na avalição de expressões resultando em um valor verdade (`true` ou `false`). Dentre os operadores lógicos temos:

- E (`&&`)
- OU - (`||`)
- NÂO - (`!`)

## Estruturas condicionais

São estruturas de controle que definem se um certo bloco de código será executando dependendo de uma determinada condição.

### Estrurura condicional `if-else`

```java
// Estrutura simples
if(<condicao>) {
	<comando_1>;
	<comando_2>;
}
```

```java
// Estrutura composta
if(<condicao>) {
	<comando_1>;
	<comando_2>;
} else {
	<comando_3>;
	<comando_4>;
}
```

```java
// Estrutura composta encadeada
if(<condicao_1>) {
	<comando_1>;
	<comando_2>;
} else {
	if(<condicao_2>) {
		<comando_3>;
		<comando_4>;
	} else {
		<comando_5>;
		<comando_6>;
	}
}
// ou
if(<condicao_1>) {
	<comando_1>;
	<comando_2>;
} else if (<condicao_2>) {
	<comando_3>;
	<comando_4>;
} else {
	<comando_5>;
	<comando_6>;
}
```

**OBS**: Se hover só uma instrução dentro do bloco de código, tanto do `if` quanto do `else`, o par de chaves de definem o bloco de código a ser executado é opcional.

### Estrurura condicional `switch-case`

Um switch case é uma estrutura de controle que permite executar diferentes blocos de código com base no valor de uma variável. Esta é uma maneira consistente e eficiente de lidar com diversos valores. É uma opção ao uso de estrutura `if-else` encadeadas.

```java
switch(<expressao>) {
	case <valor_1>:
		<comando_1>;
		break;
	case <valor_2>:
		<comando_2>;
		break;
	case <valor_3>:
		<comando_3>;
		break;
	default:
		<comando_4>;
		break;
}
```
