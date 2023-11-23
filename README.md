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
- Criação de Pokémon (Create):
Um módulo de criação de Pokémon que permite a inserção de novos Pokémon na Pokedex. Pode incluir validações para garantir dados consistentes.
- Leitura de Pokémon (Read):
Um módulo de leitura que possibilita a busca de Pokémon com base em critérios como nome, tipo, ou número. Isso incluirá métodos para listar todos os Pokémon e obter detalhes específicos.
- Atualização de Pokémon (Update):
Um módulo de atualização que permite a modificação dos atributos de um Pokémon existente na Pokedex. Pode incluir validações para garantir consistência.
- Exclusão de Pokémon (Delete):
Um módulo de exclusão que remove um Pokémon específico da Pokedex. Pode incluir confirmações para evitar exclusões acidentais.

## Funcionalidade
- O primeiro método é o GET,que vai trazer todos os pokémons que foram salvos, no postman ira trazer os seguintes resultados:
  
![Screenshot 2023-11-23 165547](https://user-images.githubusercontent.com/149121429/285298715-79ac8672-030d-4977-ac15-95657fe3f6f8.png)

- Operação PUT para Atualizar um Pokémon: Atualiza os detalhes de um Pokémon existente com base no ID.

- Operação SET para Modificar Atributos de um Pokémon: : Modifica os atributos de um Pokémon existente com base no ID

- Operação deleted:
> ![Screenshot 2023-11-23 171919](https://user-images.githubusercontent.com/149121429/285301561-1e587197-1076-4c85-9409-cc55089b468d.png)

  
  
  
  
