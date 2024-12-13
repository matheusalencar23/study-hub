# Algoritmos e programação

Aqui vamos discutir alguns conceitos interessantes sobre programação e algoritmos

## Computador

Um computador é uma máquina que manipula dados a partir de instruções. Eles podem ser analógicos ou digitais.

Um computador moderno pode ser caracterizado por três componentes distintos, a unidade central de processamento, a memória e os dispositivos de entrada e saída.

### Unidade central de processamento

A UCP ou CPU, do inglês **C**entral **P**rocessing **U**nit, é um conjunto de dispositivos eletrônicos responsável por operações lógicas e matemáticas. Ela é reponsável por buscar instruções na memória, interpretar essas instruções, executar operações representadas por essas instruções e por fim, gravar eventuais resultados desse processo.

### Memória

São dispositivos reponsáveis por armazenar dados. No geral, uma memória pode ser classificada de acordo com suas capacidade de leitura, escrita e volatilidade.

Tipos de memória:

- RAM (**R**andom **A**ccess **M**emory): a memória de acesso rápido é usada para leitura e escrita mas tem seu conteúdo perdido quando o computador é desligado. É mais usada para aplicativos e sistemas operacionais.
- ROM (**R**ead **O**nly **M**emory): a memória somente-leitura, é usada somente para leitura, após ter seu conteúdo gravado ele não pode ser alterado. Não se perde após o desligamento do computador.
- Secundária: são dispositivos usados para armezanar grandes quantidades de dados em caratér não volátil, ou seja, não se perde ao desligar o computador. No geral, são mais lentas que a RAM. Como exemplo tempos os discos rígidos.

### Dispositivos de entrada e saída

Os dispositivos de entrada e saída são a forma como o computador recebe ou devolve informação. Alguns dispositivos de entrada são o teclado, mouse, câmera e digitalizador. Já entre os dispositivos de saída temos monitor (que também pode ser usado como dispositivo de entrada, no caso dos monitores touchscreen), impressora e saída de som.

Esses dispositivos se comunicam com o computador através de conectores como porta paralela, porta serial, porta USB, porta SCSI, porta Firewire, porta PS/2, dentre outras. Além de um conector específico, essas portas compreendem um protocolo de comunicação entre o dispositivo e o computador.

Por padrão, o dispositivo de entrada de um computador é o teclado e o dispositivo de saída é um monitor, portanto, se não for expecíficado, os programas tentarão ler do teclado e escrever no monitor.

## Algoritmos

Um algoritmo pode ser definido por uma sequência finita de instruções para resolver um problema. Ele estabelece um padrão de comportamento a ser seguido para alcançar a resolução de um problema.

Os algoritmos são capazes de ler dados, avaliar expressões algébricas, relacionais e lógicas, tomar decisões com base nos resultados das expressões avaliadas e repetir um conjunto de ações com base em uma determinada condição.

Abaixo temos um exemplo simples de algoritmo com tomadas de decisão e repetições de ações com base em determinadas condições:

![Algoritmo 1](/assets/algoritmos_e_programacao/algoritmo_1.jpeg)

### Partes de um algoritmo

Um algoritmo é formado por três partes: entrada, processamento e saída de dados.

Na entrada de dados informações são fornecidas para execução do algortimo, essas informações pode ser fornecidas quando o programa já está sendo executado ou podem já estar embutidas nele.

No processamento as expressões são avaliadas as expressões algébricas, relacionais e lógicas, além das estruturas de controle, sejam elas de condição ou repetição.

Na saída, uma parte ou todos os resultados do processamento são enviados para algum dos dispositivos de saída, ou podem ser enviados para a memória.

## Linguagem

Para que informações sejam transferidas, processadas ou armazenadas é necessário que elas estajam em formas de linguagem. Existem diferentes tipos de linguagens, que nem sempre podem ser traduzidas diretamente entre si, pois são representadas de modos diferentes e se referem a coisas distintas.

Para que um ser humano possa programar, armazenar e buscar informações em um computador, é necessário que saiba instruí-lo em usa linguagem de máquina ou em uma linguagem intermediária, que possa ser facilmente traduzida para a linguagem do computador. Essa linguagem intermediária seria a linguagem de programação.

### Linguagem natural

A linguagem natural é a forma como nos expressamos e trocamos informação, podendo ser a linguagem falada, gestos e posturas, que não podem ser diretamente compreendidas pelas máquinas. As máquinas são projetadas para executar ações bem determinadas, só sendo capaz de realizar as tarefas que lhe foram delegadas, assim, é necessário entender os tipos de instruções que podem ser executadas por um computador para que seja possível programá-los.

### Linguagem de máquina

As instruções que são passadas para o computador devem estar em uma linguagem específica, conhecida como linguagem de máquina. Ela é composta somente por números binários. A linguagem de máquina é muito difícil de ser compreendida por humanos, assim, existe uma linguagem de montagem, conhecida como assembly, que é representada por comandos que reproduzem as tarefas a serem executadas pelo computador, porém a linguagem de montagem também é difícil de programar e os programas feitos para um determinado processador, por conterem instruções específicas deste, não funcionarão em um processador de outro tipo.

### Linguagens de programação

As linguagens de programação foram criadas para facilitar a tarefa de programar. Elas são uma maneira de tornar a escrita de tarefas a serem realizadas pelo computador mais parecidas com a linguagem natural. Podemos dizer que elas são um meio termo entre a linguagem natural e a linguagem de máquina. Mesmo sendo um pouco complexa as vezes, elas facilitam muito o proceso de implementação, compreensão e modificação.

As linguagens de programação podem ser classificadas de acordo com o seu nível entre linguagem natural e linguagem de máquina. As linguagens de baixo nível são mais parecidas com a linguagem de máquinas, por outro lado, as linguagens de alto nível são mais parecidas com a linguagem natural.
A linguagem de montagem, assembly, é um exemplo de linguagem de baixo nível. Como exemplo de linguagens de alto nível temos Pascal, C, Java, Python, PHP, entre outras.

Já que os processadores não entendem as linguagens de programção, elas precisam ser convertidas em linguagem de máquina, esse processo é conhecido como compilação.

Um programa escrito em linguagem de máquina contém instruções específicas para um processador, portanto só poderá ser usado em processadores daquele tipo. Já as linguagens de programação possuem instruções abstratas, que podem ser compiladas para diferentes processadores sem necessidade de alterar o código, e sim só usando um compilador específico.

### Pseudocódigo

Pseudocódigo é uma forma intermediária entre a linguagem natual e a linguagem de programação muito útil para fins de estudo. Ela é menos rígida sintáticamente, contendo somente algumas palavras-chave e, em geral, é usada na linguagem nativa do programador. É muito usada para iniciantes e ajuda a se familiarizar com a lógica de programação, e a medida que o programador evolui começa a migrar para uma linguagem de programação.

![Pseudocódigo 1](/assets/algoritmos_e_programacao/pseudo_codigo_1.jpeg)

## Dados

Para armazenar e manipular dados em um computador é necessários representá-los de alguma forma. Nós humanos usamos o sistema decimal, já os computadores usam o sistema binário, representados por 0/1, ligado/desligado ou verdadeiro/falso.

Devido a grande quantidade de algarismos necessários para representar um número no sistem binário, os computadores também podem usar outras formas de representar os números, como o sistema octal, que usa 8 dígitos (0 1 2 3 4 5 6 7), e o hexadecimal, que usa 16 dígitos (0 1 2 3 4 5 6 7 8 9 A B C D E F).

| Decimal  | Binário | Octal | Hexadecimal |
| -------- | ------- | ----- | ----------- |
| 0        | 0000    | 0     | 0           |
| 1        | 0001    | 1     | 1           |
| 2        | 0010    | 2     | 2           |
| 3        | 0011    | 3     | 3           |
| 4        | 0100    | 4     | 4           |
| 5        | 0101    | 5     | 5           |
| 6        | 0110    | 6     | 6           |
| 7        | 0111    | 7     | 7           |
| 8        | 1000    | 10    | 8           |
| 9        | 1001    | 11    | 9           |
| 10       | 1010    | 12    | A           |
| 11       | 1011    | 13    | B           |
| 12       | 1100    | 14    | C           |
| 13       | 1101    | 15    | D           |
| 14       | 1110    | 16    | E           |
| 15       | 1111    | 17    | F           |

Um único algarismo binário é chamado de bit, uma sequência de 8 bits é chamado de byte e uma sequência de 16 bits é uma palavra.

### Tipos primitivos

Os dados que são armazenados devem ter um tipo definido, isso é definido com base no tipo de informação que se deseja representar e nas operações que serão realizadas com o ele. Isso permite uma otimização dos recursos computacionais e uma aceleração no processamento.

Alguns dos tipos de dados mais comuns são:

- **Inteiro**: números pertencentes ao conjunto dos inteiros, tanto positivos, nulos ou negativos.
- **Real**: números pertencentes ao conjunto dos reais. Também são conhecidos como ponto flutuante, devido a maneira como o computador o armazena.
- **Caractere**: são valores que percencem ao conjunto de caracteres numéricos (0...9), alfabéticos (a...zA...Z) e especiais (! @ # $ % - & *). Esse conjunto é conhecido como conjunto de caracteres alfanuméricos. Esses caracteres são armazenados pelo computador na forma numérica binária usando o padrão definido pela tabela ASCII. No caso dos caracteres, também existem as cadeias de caracteres, que podem formar uma frase.
- **Lógico**: é usado para informações que só podem possuir dois valores, o valor verdadeiro e o valor falso. Também são entendidos como ligado/desligado, 1/0, alto/baixo, fechado/aberto, etc.

### Constantes e variáveis

Os dados podem ser de duas classes diferentes, contantes e variáveis. Os dados contantes são aqueles não não tem seu valor alterado, permanecendo com o mesmo valor durante toda a execução do algoritmo. Os dados variáveis são aqueles que podem ter seu valor alterado.

### Manipulação de dados

#### Identificação

Para que os dados possam ser utilizados no computador, é necessário que eles sejam associados a um nome, um identificador, onde o conteúdo desse identificador será o dado em si e seu nome será usado para acessar o dado e realizar operações.

Uma analigia interessante para isso é o conceito de que o identificador seria uma placa de sinalização que indica um determinado espaço na memória onde o dado está armazenado, assim, quando é necessário acessar a informação armazenada naquele espaço de memória, usamos essa placa sinalizadora para saber onde encontrar esse dado.

Para nomearmos um dados, é comum usarmos nomes que lembrem o caráter do conteúdo armazenado, isso facilita a leitura do código.

#### Definição

O primeiro passo antes de começar a usar um dado é a nomeação do seu identificador e a definição do seu tipo, e em casos de constantes, a definição do seu valor. Essa definição do dado também é conhecida como declaração.

A definição de uma variável é feita da seguinte forma:

```
var <identificador_1> [, <identificador_2>,...]: <tipo_1>;
    <identificador_3> [, <identificador_4>,...]: <tipo_2>;
```

Já a definição de uma constante é feita assim:

```
constante <identificador_1> = <valor_1>;
          <identificador_2> = <valor_2>;
          <identificador_3> = <valor_3>;
```

Abaixo temos um exemplo de declaração dos dois tipos de identificadores:

![Declaração 1](/assets/algoritmos_e_programacao/declaracao_1.jpeg)

Quando declaramos um indetificador, estamos reservando um espaço na memória onde só podemos armazenar valores do mesmo tipo do definido na declaração. Podemos comparar a memória a um armário cheio de gavetas etiquetadas, onde cada etiqueta é equivalente ao nome do identificador e o conteúdo da gaveta seria referente ao seu valor.

#### Atribuição