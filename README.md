# Creating a REST API with Next.js, Prisma and PostgreSQL

Repository used during the development of an article on DukesCode about ["Creating a REST API with Next.js, Prisma and PostgreSQL"](https://www.dukescode.com/building-a-rest-api-with-nextjs-and-prisma?utm_source=github&utm_medium=page&ref=github).

[![LinkedIn](https://img.shields.io/static/v1?label=LinkedIn&message=%20&color=blue&logo=LinkedIn&style=flat-square&logoColor=white)](https://www.linkedin.com/in/dukefullstack/)
[![Youtube](https://img.shields.io/static/v1?label=Youtube&message=%20&color=blue&logo=Youtube&style=flat-square&logoColor=white)](https://www.youtube.com/@DukesCode)
[![Twitter](https://img.shields.io/static/v1?label=Twitter&message=%20&color=blue&logo=Twitter&style=flat-square&logoColor=white)](https://twitter.com/dukefullstack)
[![DukesCode](https://img.shields.io/static/v1?label=Duke'sCode&message=%20&color=blue&logo=googlechrome&style=flat-square&logoColor=white)](https://dukescode.com?utm_source=github&utm_medium=page&ref=github)
[![Instagram](https://img.shields.io/static/v1?label=Instagram&message=%20&color=blue&logo=Instagram&style=flat-square&logoColor=white)](https://www.instagram.com/dukefullstack/)

## ![image](https://github.com/dukefullstack/store-app-castore/blob/assets/assets/octohub.png?raw=true) Menu Contents

- [Creating a REST API with Next.js, Prisma and PostgreSQL](#building-a-rest-api-with-nextjs-and-prisma)
  - [:bulb: Menu Contents](#-menu-contents)
  - [:pushpin: Motivation](#pushpin-motivation)
  - [:man_technologist: Technologies & Tools](#man_technologist-technologies--tools)
  - [:iphone: Final Application](#iphone-final-application)
  - [:heavy_check_mark: Installation](#heavy_check_mark-installation)
  - [:heavy_check_mark: Compilation & Test](#heavy_check_mark-compilation--test)
  - [:pencil: Author](#pencil-author)

## :pushpin: Motivation

When I started to study Next.js and Prisma I came across a lot of material presenting its use and possibilities in front-end development. Little has been seen about creating a back-end API layer or front-end BFF.

I decided to create this article precisely so that you can learn how to create a backend API layer or frontend BFF.

## :man_technologist: Technologies & Tools

- [Next.js](https://nextjs.org/)
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [TypeScript](https://www.typescriptlang.org/)

## :iphone: Final Application

By the conclusion of this article, we will have successfully generated a REST API with following endpoints.

- **POST: /api/articles** - Create a new article.
- **GET: /api/articles** - List all articles.
- **GET: /api/articles/:id** - List a specific article.
- **PUT: /api/articles/:id** - Update a specific article.
- **DELETE: /api/articles/:id** - Delete a specific article.

## :heavy_check_mark: Installation

- First, you need to have Node v18+ and Npm 8+, if you don't follow the instruction inside [this post](https://www.dukescode.com/a-complete-beginners-guide-to-solidity-part-ii?utm_source=github&utm_medium=readme&ref=github).

- Now clone the project via HTTPS through this command:</br>
  `$ git clone https://github.com/dukes-code/building-a-rest-api-with-nextjs-and-prisma.git`

- After cloning, enter the cloned repository directory:</br>
  `$ cd building-a-rest-api-with-nextjs-and-prisma`

- Once being inside the directory, download and install the dependencies using:</br>
  `$ npm i`

## :heavy_check_mark: Compilation & Test

- First install Prisma with:</br>
  `$ npm install -D prisma`

- Create initial configuration of Prisma with:</br>
  `$ npx prisma init`

- Update the environment variable `DATABASE_URL` inside the .env file following [these instructions](https://www.dukescode.com/building-a-rest-api-with-nextjs-and-prisma/configurando-o-prisma?utm_source=github&utm_medium=readme&ref=github).

- Now start the development server with:</br>
  `$ npm run dev`

- Then open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## :pencil: Author

- <a href="https://www.linkedin.com/in/dukefullstack/" target="_blank">LinkedIn</a>
- <a href="https://www.youtube.com/@DukesCode" target="_blank">Youtube</a>
- <a href="https://twitter.com/dukefullstack" target="_blank">Twitter</a>
- <a href="https://dukescode.com" target="_blank">Duke's Code</a>
- <a href="https://www.instagram.com/dukefullstack/" target="_blank">Instagram</a>

Made with :heart: by <a href="https://www.linkedin.com/in/dukefullstack/">**Thiago Santos Joaquim**</a>. MIT License
