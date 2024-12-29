# Maven

O Maven, ou Apache Mave, é uma ferramenta de automação e gerenciamento de projetos Java, porém, também pode ser usado para outra linguagens. Ela fornece formas padronizadas de automação, construção e publicação de aplicações, aumentando a agilidade e a qualidade da entrega final. É uma ferramenta muito flexível, que permite a adição de plugins para estender suas funcionalidades nativas.

A criação de projetos Java envolve, em geral, a criação de um diretório principal com diversos subdiretórios, a configuração de arquivos XML, a obtenção de diversas bibliotecas para o projeto, posteriormente, execução de testes unitários, criação de pacotes para publicação, geração de documentação javadoc, entre outras etapas. Isso tudo, implica em um estrutura diferente para cada projeto, diferentes formas de gerar pacotes e executar cada um desses passos para cada projeto. Em projetos mais complexos, com vários módulos, pode ser necessário que eles sejam compilados em uma determinada ordem para que o pacote final seja criado de fora correta.

Para resolver esses problemas surgiram algumas ferramentas, como o Apache Ant, porém, ele só solucionou parte das dores. Foi aí que surgiu o Maven, como uma melhoria das ferramentas lançadas anteriormente.

## O que é o Maven?

O Maven é uma ferramenta de genrenciamento e automação de construção (**build**) de projetos. Porém, também fornece diversas outras funcionalidades através dos plugins e estimula o emprego das melhores práticas de organização, desenvolvimento e manutenção de projetos, se tornando muito mais que uma ferramenta auxiliar.

Por exemplo, um desenvolvedor alocado em um projeto Java que usa o Maven não precisa saber de imediato quais dependências o projeto precisa para ser compilado e executado, nem precisa saber onde obter essas dependências. Através do comando `mvn install`, o desenvolvedor está dizendo ao maven para gerar o código extra necessário para o proejto, validar e compilar o projeto, executar os testes unitários e gerar o pacote com código compilado.

Além das vantagens citadas anteriormente, o Maven também estimula a adoção de boas práticas, pois usa o conceito de programação por convenção, assim, a ferramente assume que será adotada ideias de acordo com que ela recomenda, sendo essas ideias incorporadas as práticas aceitas pela comunidade Java. Com isso, o Maven evita a necessidade de declarações repetitivas e facilita os novatos no projeto a se situarem mais facilmente. Claro que essas configurações podem ser definidas manualmente, porém isso aumenta a carga inicial de configuração inicial do projeto.

## Criando um projeto simples

https://www.devmedia.com.br/introducao-ao-maven/25128