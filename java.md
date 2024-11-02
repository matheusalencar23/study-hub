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
