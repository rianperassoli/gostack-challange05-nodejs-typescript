# gostack-challange05-nodejs-typescript

NodeJS with typescript back-end based on challenge 5 from BootCamp goStack by Rocketseat. (https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-nodejs)



> To install the project dependencies: `$ yarn`

> To run: `$ yarn dev:server`

> To test: `$ yarn test`

Api routes
* **POST /transactions** *(add a transaction)*
```
body: {
  "title": "Title",
  "value": 2000,
  "type": "outcome" || "income" 
}
```

* **GET /transactions** *(list all transactions and a balance of transactions)*
