# pokedex

## Descrição do Projeto

- Este projeto tem como objetivo criar uma pokedex através de uma  aplicação Java no curso de Programação Orientada a Objetos na Universidade São Francisco.
  Será utilizado principalmente o CRUD (Create, Read, Update, Delete)
A aplicação visa fornecer informações de um pokemon,como seus atributos e suas caracteristicas. 

  ## Principais recursos
  - Adição,atualização e exclusão de algum pokemon específico
  
  - Informacoes de pokemons como: atributos, habilidades, e sua numeração.

  ## Desenvolvedor e RA
  - Andre Kenji Yanaguibashi Ito
  - Ra:202112001

## Tecnologia Empregada
- Linguagem de Programação: Java
- Framework: Spring Boot
- Outras Dependências: Spring Reactive Web,Spring Data Reactive MongoDB,Embedded MongoDB Database
- Ferramentas de Build: Maven

## Motivo da escolha
  - Spring Boot : O Spring Boot utiliza o conceito de "starter dependencies" que são conjuntos predefinidos de dependências relacionadas a determinados recursos. Isso facilita a inclusão de dependências comuns sem a necessidade de configurar manualmente cada uma delas.
  - Java : a linguagem tem um desempenho bastante sólido. Em particular, para APIs e aplicações empresariais, o desempenho do Java é muitas vezes mais do que adequado.

## Descrição da Arquitetura

- A classe PokemonController é um componente Spring Boot responsável por gerenciar as requisições relacionadas aos Pokémons.
- 
- Endpoints RESTful:

O controlador define vários endpoints RESTful para realizar operações CRUD (Create, Read, Update, Delete) em entidades Pokemon.
Exemplos de endpoints incluem:
GET /pokemons: Retorna todos os Pokémons.
GET /pokemons/{id}: Retorna um Pokémon específico por ID.
POST /pokemons: Cria um novo Pokémon.
PUT /pokemons/{id}: Atualiza um Pokémon existente por ID.
DELETE /pokemons/{id}: Exclui um Pokémon por ID.

- Reactive Programming:

O uso de tipos reativos (Mono e Flux do Reactor) sugere uma abordagem reativa para manipular assincronamente os dados.
A resposta do evento (/events) é um exemplo de um fluxo de eventos que emite atualizações a cada 5 segundos.
Integração com Banco de Dados:

O controlador interage com um repositório (PokemonRepository) para realizar operações de persistência no banco de dados.
Operações como salvar, buscar por ID, atualizar e excluir são mapeadas para endpoints RESTful.

## Funcionalidade
- O primeiro método é o GET,que vai trazer todos os pokémons que foram salvos, no postman ira trazer os seguintes resultados:
  
![Screenshot 2023-11-23 165547](https://user-images.githubusercontent.com/149121429/285298715-79ac8672-030d-4977-ac15-95657fe3f6f8.png)

- Operação PUT para Atualizar um Pokémon: Atualiza os detalhes de um Pokémon existente com base no ID.
 caso não há o pokemon desejado,surgirá notfound 

- Operação SET para Modificar Atributos de um Pokémon: : Modifica os atributos de um Pokémon existente com base no ID

- Operação deleted:
> ![Screenshot 2023-11-23 171919](https://user-images.githubusercontent.com/149121429/285301561-1e587197-1076-4c85-9409-cc55089b468d.png)

  
  
  
  
