## Desafio Front end Brisalabs :computer:

- O desafio consiste no desenvolvimento de uma aplicação Web a ser desenvolvida utilizando as tecnologias especificadas abaixo. É importante que você possa enviar toda a aplicação, mas se não conseguir, pode enviar só o que der tempo terminar que será bem avaliado.
- Crie um repositório público no github e envie o link para o e-mail `maxmiller@grupobrisanet.com.br` com assunto `Desafio Front end Brisalabs`.
- Na página de login pode ser criada uma função que será responsável por gerar e validar um token de sessão, por exemplo uma função usando o `crypto`.
- O layout está disponível no link abaixo :point_down:

## Layout :bookmark:
  - [Layout da aplicação](https://www.figma.com/file/o91t40vYqx9cmQL4nvf9PC/Desafio-Dev-Brisalabs?node-id=6%3A44).

## Tecnologias :rocket:

  - [ReactJS](https://reactjs.org/)
  - [TypeScript](https://www.typescriptlang.org/)
  - [Styled Components](https://styled-components.com/)
  - [Context API](https://pt-br.reactjs.org/docs/context.html)
  - Requisições a API
  - [PokéAPI](https://pokeapi.co)

## Níveis :pushpin:

- **Básico**

   - Login (Página Login);
   - Realizar login e armazenar o token no localstorage;
   - Verificar se já existe uma sessão salva (token no localstorage), caso sim, redirecionar para a página de "Ver todos", caso não deve retornar para o login;
   - Listagem completa (Página Ver todos)
   - Deve listar registros da API limitando apenas 20 itens;

- **Intermediário**
  
  - Deve ser possível filtrar através dos botões(Página Ver todos);
  - Busca e Listagem (Página Procurar)
  - Deve ser possível realizar a busca por um pokémon específico;
  - Deve listar, abaixo, todos os registros encontrados;
  - Deve ser posível ver os detalhes do pokémon em um modal, exibindo as informações contidas no layout;

- **Avançado**

  - Favoritar pokémons e exibir na página "Favoritos"
  - Exibir a quantidade de pokémons no menu e na página de favoritos
  - Tema escuro (ficaria muito show :sunglasses:)

## Critérios de avaliação :memo:
- Componentização
- Clean code
- Organização de pastas
- Ser fiel ao layout
