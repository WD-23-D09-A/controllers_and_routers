# Controllers & Routers

## Preparation

After cloning, install dependencies with

```
npm i
```

Open a branch with your name

```
git checkout -b myname_branch
```

Bitte, regelmäßig auf Github pushen. Man will nicht die Arbeit verlieren ;)

## 1.- Basic Structure

- Choose a \_.json file from the ones provided on the data directory, or make your own

- Create a controllers folder and a routers folder

- Call the express.json and cors middlewares

## 2.- Error Middleware

- Create an errorMiddleware
- Store the middleware outside of server.js
- call the errorMiddleware from the server.js
- the error middleware should contain the right parameters

## 3.- Controllers (Handlers)

- Create a handler (controller) for

  - Get One
  - Get All
  - Post One
  - Update One
  - Delete One

```
const getOneFilm
const getAllFilms
const postOneFilm
const updateOneFilm
const deleteOneFilm
```

- Each controller should:
  - be async
  - have req, res and next as parameters
  - contain a try / catch blocks
  - catch should call the next middleware on the chain

each controller's functionality is up to you

- Save all the controllers on it's own sepparated file inside the controllers directory

## 4.- Routers

- Create a router for the choosen data
- Create a route for every controller
- Save the router on it's own sepparated file inside the routers directory
- Call the router on the server.js file

## 5.- Trink was schönes, du hast es geschafft
