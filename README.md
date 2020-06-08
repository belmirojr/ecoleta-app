<h1 align="center">
    <img src="https://ik.imagekit.io/vnstq13zag/logo_An8fV0S6W.svg">
</h1>

# Indice
- [Sobre](#-sobre)
- [Principais tecnologias e bibliotecas utilizadas](#-principais-tecnologias-e-bibliotecas-utilizadas)
- [Como baixar o projeto](#-como-baixar-o-projeto)

## 🔖📌 Sobre
Projeto multiplataforma, web e mobile, desenvolvido durante a **Next Level Week #1**, promovida pela Rocketseat. Inspirado na semana do meio ambiente, o projeto tem por objetivo ajudar pessoas a encontrarem pontos de coleta de resíduos de forma eficiente. Foi desenvolvido um APIRestfull para alimentar os dados do front-end. A aplicação consome dados da API do IBGE para listar estados e cidades por estado, bem como consome a API do Leaflet para exibição do mapa.

<h1 align="center">
    <img src="https://ik.imagekit.io/vnstq13zag/mobile_Z1ee1JKry.jpg">
</h1>
<h1 align="center">
    <img src="https://ik.imagekit.io/vnstq13zag/web-landingpage-ecoleta_Au82F6r2I.jpg">
</h1>
<h1 align="center">
    <img src="https://ik.imagekit.io/vnstq13zag/web-cadastro-ecoleta__NCe4_LHB.jpg">
</h1>

---

## 🚀 Principais tecnologias e bibliotecas utilizadas

O Projeto foi desenvolvido com as seguintes tecnologias.
### Back-end
- TypeScript
- NodeJS
- Express
- SQLite
- Celebrate
- Cors
- Knex (migrations)
- Multer

### Front-end Web
- TypeScript
- ReactJS
- Axios
- Leaflet
- React DOM
- React Dropzone
- React Icons
- React Router DOM

### Front-end mobile
- TypeScript
- ReactJS
- React Native
- Axios
- Expo
- Expo Location
- Expo Mail Composer
- React DOM
- React Native Maps
- React Native Location

---
# Layout
Layout de todas as telas disponível no [Figma](https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/).

---

## 📁 Como usar
Para clonar e usar o este projeto será necessário ter Git, Node.js e Yarn instalados.

### Instalação da API (server)

```bash
# Clonar o repositório
$ git clone https://github/piiiiva/ecoleta-app

# Entrar no diretório
$ cd ecoleta-app/server

# Instalar as dependências
$ npm install

# Rodar os migrates
$ npm knex:migrate

# Rodar os seeds
$ npm knex:seed

# Iniciar o servidor
$ npm run dev

# Rodando na porta 3333
# Disponível em http://localhost:3333

```

### Instalação front-end (web)

```bash
# Clonar o repositório
$ git clone https://github/piiiiva/ecoleta-app

# Entrar no diretório
$ cd ecoleta-app/web

# Instalar as dependências
$ npm install

# Iniciar a aplicação
$ npm start

# Rodando na porta 3333
# Disponível em http://localhost:3333

```

### Instalação front-end (mobile)

```bash
# Clonar o repositório
$ git clone https://github/piiiiva/ecoleta-app

# Entrar no diretório
$ cd ecoleta-app/mobile

# Instalar as dependências
$ npm install

# Iniciar a aplicação
$ npm start

# Escanear o QRcode do Expo no terminal ou na página web

# Rodando na porta 3333
# É preciso verificar o seu IP e alterar o arquivo mobile/src/services/api.ts conforme o seu IP
# Disponível em http://seuIP:3333

```
---

## Passo a passo de como construir
Documentação dos principais pontos da NLW e da construção passo a passo da aplicação [aqui](https://www.notion.so/Next-Level-Week-2637ed1ec02443a3b4ba44e46ee05ce7)!

---

Desenvolvido com 💚 por Rodrigo Diego Piva