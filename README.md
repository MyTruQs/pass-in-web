# pass.in - Gerenciamento de Eventos

O pass.in é uma aplicação desenvolvida para facilitar o gerenciamento de participantes em eventos presenciais. Com esta ferramenta, organizadores podem cadastrar eventos, abrir páginas públicas de inscrição e permitir que participantes emitam credenciais para check-in no dia do evento.

## Principais Características:

- **Cadastro de Eventos:** Organizadores podem facilmente cadastrar novos eventos, fornecendo informações como título, detalhes e número máximo de participantes.

- **Páginas de Inscrição Pública:** A aplicação gera páginas públicas de inscrição para cada evento, permitindo que os participantes se inscrevam facilmente.

- **Gestão de Participantes:** Organizadores têm acesso a uma lista detalhada de participantes inscritos em cada evento, podendo visualizar seus dados e status de check-in.

- **Check-in com QRCode:** O sistema de check-in é realizado de forma simples através de um QRCode, proporcionando uma experiência rápida e eficiente no dia do evento.

## Tecnologias Utilizadas:

- **Backend (Python):** O backend da aplicação foi desenvolvido em python. Utilizando Python como linguagem de programação, Flask como framework web, preparação de ambiente e boas práticas de projeto com Virtualenv, Pylint e versionamento de código usando pre-commit, boas práticas de código com entidades, services e repositories + testes automatizados com Pytest. E do lado do banco de dados fomo de SQLite como banco de dados relacional.
- **Se desejar acompanhar o projeto backend esse é o link para o repositorio:** https://github.com/MyTruQs/nlw-unite-python
  
- **Frontend (React.js):** O frontend foi construído utilizando React.js, onde houve a aplicação dos conceitos de Propriedades, Estados e Componentes, tipagem com Typescript, tooling com Vite, interface responsiva com TailwindCSS, consumo de API Node.js, uso de URL states. Assim proporcionando uma interface dinâmica e responsiva para os usuários.

## Documentação da API:

A documentação da API está disponível no Swagger, permitindo uma fácil compreensão dos endpoints e suas funcionalidades. [Documentação da API](https://nlw-unite-nodejs.onrender.com/docs)

## Como Contribuir:

1. Faça um fork do repositório.
2. Clone o fork para sua máquina local.
3. Instale as dependências utilizando `npm install`.
4. Faça as alterações desejadas e teste-as.
5. Envie um pull request com suas alterações.

## Executando o Projeto Localmente:

1. Clone o repositório para sua máquina local.
2. No diretório raiz do projeto, execute `npm install` para instalar as dependências.
3. Execute `npm start` para iniciar o servidor backend.
4. Abra um novo terminal e navegue até o diretório `frontend`.
5. Execute `npm install` para instalar as dependências do frontend.
6. Execute `npm start` para iniciar o servidor de desenvolvimento do frontend.
7. Acesse a aplicação em seu navegador através do endereço `http://localhost:3000`.

## Feedback e Sugestões:

Se você tiver alguma sugestão de melhoria ou encontrar algum problema na aplicação, sinta-se à vontade para abrir uma issue ou enviar um pull request. Seu feedback é sempre bem-vindo!

Esperamos que o pass.in seja útil para facilitar a gestão de eventos e proporcionar uma experiência agradável tanto para organizadores quanto para participantes.
