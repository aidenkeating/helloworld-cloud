# Hello World Cloud App
[![Dependency Status](https://img.shields.io/david/feedhenry-templates/helloworld-cloud.svg?style=flat-square)](https://david-dm.org/feedhenry-templates/helloworld-cloud)

This is a blank 'Hello World' cloud app which can be used as a starting point for your API.

# Group Hello World API

There is only one endpoint in the application.

## `POST /hello`

Accepts an `application/json` body with the following structure:

```json
{
  "hello": "world"
}
```

Responds with the following `application/json` body:

```json
{
  "msg": "Hello world"
}
```
