# IMS
## ims-express
ims-express is a restful service.

Use `express-generator` to create skeleton of web site:
`express ims-express --view=pug`

Although we can use `nodemon` to restart server auotmatically when source files updated, still need refresh manually in browser. Following is snippet in package.json.
```
  "scripts": {
    "start": "node ./bin/www",
    "devstart": "nodemon ./bin/www"
  },
```
execute `SET DEBUG=ims-express:* & npm run devstart` in command prompt to start server.


## ims-react
ims-react is a react client.

Use `create-react-app` to create skeleton of front-end app.
