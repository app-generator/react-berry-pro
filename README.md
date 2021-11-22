# Berry React PRO

Berry is developer-friendly & highly customizable React Admin Template based on Material-UI. This modern design comes with plenty of ready-to-use Material-UI components that will help you to build your site faster and saves your development time. The product comes with a simple JWT authentication flow: login/register/logout.

<br />

-   [Full-stack React Berry PRO](https://appseed.us/full-stack/react-berry-dashboard) - product page
-   [Full-stack React Berry PRO](https://fullstack-react-berry-dashboard.appseed-srv1.com/) - LIVE Demo

<br />

> Features

- Modern aesthetics Material-UI design - Designed by [CodedThemes](https://codedthemes.com/)
- M-UI version: v5.0.0
- React, Redux, Redux-persist
- Authentication: JWT Login/Register/Logout
- For a complete full-stack experience, the product can be used with:
  - [Django API Server](https://docs.appseed.us/boilerplate-code/api-server/django) - open-source product
  - [Flask API Server](https://docs.appseed.us/boilerplate-code/api-server/flask) - open-source product
  - [Node JS API Server](https://docs.appseed.us/boilerplate-code/api-server/node-js) - open-source product / Typescript / SQLite / TypeORM / Joy for validation
  - [Node JS API Server PRO](https://github.com/app-generator/api-server-nodejs-pro) - **commercial product**
    - SQLite / TypeORM / Joy / Docker
    - MongoDB / Mongoose / Joy Docker (separate branch, same project)

<br />

## Quick Start in [Docker](https://www.docker.com/)

> Get the code

```bash
$ git clone https://github.com/app-generator/priv-react-berry-dashboard-pro.git
$ cd priv-react-berry-dashboard-pro
```

> Start the app in Docker

```bash
$ docker-compose pull  # download dependencies 
$ docker-compose build # local set up
$ docker-compose up    # start the app 
```

The React UI starts on port `3000` and expects an API server on port `5000` (saved in configuration).

<br />

![Full-stack Berry Dashboard PRO - Full-stack seed project crafted by CodedThemes and AppSeed.](https://user-images.githubusercontent.com/51070104/130806897-ee251104-94d2-4446-9ba0-be79a37030d6.jpg)

<br />

## How to use it

To use the product Node JS (>= 12.x) is required and GIT to clone/download the project from the public repository.

**Step #1** - Clone the project

```bash
$ git clone https://github.com/app-generator/priv-react-berry-pro.git
$ cd priv-react-berry-pro
```

<br >

**Step #2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

**Step #3** - Start in development mode

```bash
$ npm run start
// OR
$ yarn start
```

<br />

## Configure the backend server

The product comes with a usable JWT Authentication flow that provides only the basic requests: login/logout/register.

**API Server URL** - `src/config.js`

```javascript
const config = {
    ...
    apiServer: 'https://api-server-nodejs.appseed.us/api/'  // <-- The magic line
};
```

<br />

> **API Descriptor**

The product uses implements a **Unified API definition** exposed by all API servers crafted by AppSeed. For more information, please access the official documentation:

-   All [API Servers](https://docs.appseed.us/boilerplate-code/api-server) - the full index
-   [Unified API Definition](https://docs.appseed.us/boilerplate-code/api-server/api-unified-definition) - methods implemented accross all servers

<br />

---

Berry React PRO - Provided by [CodedThemes](https://codedthemes.com/) and **AppSeed [App Generator](https://appseed.us/app-generator)**.
