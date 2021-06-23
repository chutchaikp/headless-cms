# Strapi application

- Install strapi

```s
$ yarn create strapi-app my-project
# select custom - mongo
```

- Install graphql plugin

```s
$ npm run strapi install graphql
```

- Install documentation (Swagger UI) plugin

```s
$ strapi install documentation
```

- Deploy to Heroku [more detail](https://devcenter.heroku.com/articles/deploying-nodejs)
```b
$ git add .
$ git commit -m "Init commit"
$ git push heroku master
```
