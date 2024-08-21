# Node.js PostgreSQL CRUD example with Express Rest APIs

Full Article with implementation:
> [Node.js PostgreSQL CRUD example with Express Rest APIs](https://www.bezkoder.com/node-express-sequelize-postgresql/)

We will build Rest Apis that can create, retrieve, update, delete and find Tutorials by title.

The following table shows overview of the Rest APIs that will be exported:

- GET     `api/tutorials`	            get all Tutorials
- GET     `api/tutorials/:id`         get Tutorial by id
- POST    `api/tutorials`             add new Tutorial
- PUT     `api/tutorials/:id`         update Tutorial by id
- DELETE  `api/tutorials/:id`         remove Tutorial by id
- DELETE  `api/tutorials`             remove all Tutorials
- GET     `api/tutorials/published`   find all published Tutorials
- GET     `api/tutorials?title=[kw]`  find all Tutorials which title contains 'kw'

Front-end that works well with this Back-end
> [Axios Client](https://www.bezkoder.com/axios-request/)

> [Angular 8](https://www.bezkoder.com/angular-crud-app/) / [Angular 10](https://www.bezkoder.com/angular-10-crud-app/) / [Angular 11](https://www.bezkoder.com/angular-11-crud-app/) / [Angular 12](https://www.bezkoder.com/angular-12-crud-app/) / [Angular 13](https://www.bezkoder.com/angular-13-crud-example/) / [Angular 14](https://www.bezkoder.com/angular-14-crud-example/) / [Angular 15](https://www.bezkoder.com/angular-15-crud-example/) / [Angular 16](https://www.bezkoder.com/angular-16-crud-example/)

> [Vue 2 Client](https://www.bezkoder.com/vue-js-crud-app/) / [Vue 3 Client](https://www.bezkoder.com/vue-3-crud/) / [Vuetify Client](https://www.bezkoder.com/vuetify-data-table-example/)

> [React Client](https://www.bezkoder.com/react-crud-web-api/) / [React Redux Client](https://www.bezkoder.com/react-redux-crud-example/)
## Project setup
```
npm install
```

### Run
```
node server.js
```
