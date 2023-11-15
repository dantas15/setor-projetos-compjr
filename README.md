# Slides

- [Markdown da apresentação](./src/deck.mdx)

## Roteiro

### Cargos

- back-end
  - lado do servidor
  - lida com banco de dados
  - valida as requisições
- front-end
  - lado do cliente
  - estilização
  - modela os dados vindos do lado do servidor
  - garante a experiência do usuário baseado no design
- mobile
  - desenvolve aplicativos utilizando tecnologias multiplataforma (React Native ou Flutter)
- PO (Product Owner)
  - estabelecer a visão do produto
  - definir metas e objetivos claros
  - manter um backlog de itens do produto (lista de funcionalidades, bugs, melhorias, etc...)
  - manter uma comunicação clara e eficaz com todos os membros da equipe e partes interessadas

### Fluxo de um projeto

- prospecção > análise da viabilidade > doc de requisitos > contrato fechado
  - análise de viabilidade
    - pode ser feito por qualquer um que tenha experiência na área para que o app será desenvolvido
    - em alguns casos, o diretor de projetos deve auxiliar em relação ao conhecimento do time, quantidade de pessoas disponíveis
- preparando para o desenvolvimento
  - concepção/design
    - muitas vezes, deixamos explícito no contrato que o tempo de desenvolvimento começa só quando o design estiver pronto, já que é uma parte em que o cliente começa a clarear a mente em relação às suas próprias ideias, fluxo do programa, etc...
- início do desenvolvimento
  - no início, nos preocupamos bastante em entender todo o fluxo enquanto programamos, por exemplo, (não temos um time, fazemos normalmente o PO ou algum outro que saiba) fazemos alguns diagramas que ajudam (e muito) o desenvolvedor:
  - [Diagrama ER](https://www.lucidchart.com/pages/pt/o-que-e-diagrama-entidade-relacionamento)
    - Extremamente essencial para modelar os bancos de dados que temos!
    - Ajuda a entender quais entidades vamos ter no banco de dados e como elas se relacionam
  - [Diagrama de sequência](https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-sequencia-uml)
    - "Um diagrama de sequência é uma espécie de diagrama de interação, pois descreve como, e em qual ordem, um grupo de objetos trabalha em conjunto"
    - Não utilizamos esse aqui com tanta frequência, porque são mais utilizados para entender e documentar projetos mais complexos

### Depois de entender o fluxo: continuar documentando

- na verdade, esse é o passo que fizemos "inconscientemente" até agora, mas que, se não prestarmos atenção agora, começamos a programar (ou seja, começamos a criar problemas)
  - Não me entenda mal: o trabalho de nós, desenvolvedores, é criar bugs para que possamos resolvê-los (e criar mais bugs), e ta tudo bem!
  - O problema é ir avançando sem ir documentando, pois já dizia o sábio:
   >*Mês passado eu e Deus entendíamos o código, hoje só Deus...*
- por isso, temos algumas práticas aqui na Comp que temos que seguir para que possível continuarmos entendendo o código sem precisar de auxílio divino
- Tecnologias para documentação durante o desenvolvimento
  - GitHub
    - Versionamento de código
    - Use uma nomenclatura que seja fácil de entender
      - Um padrão muito aceito no mercado e que utilizamos aqui na Comp, é o [conventional commits](https://www.conventionalcommits.org/pt-br/v1.0.0/) (garanto que se você lançar essa nos seus projetos do GitHub e falar pro entrevistador, vai ganhar uns pontos a mais com eles)
  - GitHub Projects
    - É uma ferramenta que podemos utilizar como kanban
    - Por ser do github, se relaciona muito bem com as funcionalidades que já estamos acostumados, como criar as task como issues no repositório, definir usuário específico para uma issue, gerenciar pull requests, etc..

### SCRUM

- "O Scrum é uma estrutura ágil de gestão de projetos que ajuda as equipes a estruturar e gerenciar o trabalho por meio do conjunto de valores, princípios e práticas" - [Atlassian](https://www.atlassian.com/br/agile/scrum)
- Utilizamos o Scrum para garantir a qualidade da entrega dos nossos projetos
- POs (donos do produto em tradução livre) são os responsáveis por garantir isso durante o desenvolvimento

### Funçoes de gerência

- Dir. projetos
  - planejamento estratégico
    - isso será muito melhor explicado na formação de liderança (para os que escolheram participar) ou com os cursos da norteia que serão (ou já foram?) disponibilizados pra vocês
  - identifica a viabilidade de novos projetos
  - trazer/Avaliar novas tecnologias p/ dentro da Comp
- Gerente de projetos
  - organiza e direciona as squads
  - garante a qualidade das entregas dos projetos
- possíveis gerências (futuramente)
  - gerente de qualidade
  - gerente de infraestrutura
