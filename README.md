<img src="https://github.com/jeaanca/fort-team/blob/master/app/src/assets/img/logo-full.png"><br>

### Fort Team is a real-time conversation project

## About
This project has the ambition to build a chat in real time using socket.io in javascript.

The appearance is related to several studies that I conducted where it resulted in a project with the following stacks:

The project organization is based on the MVC model.

**Vue.js**: Framework used in the view layer
**Node.js**: Used to build the other two layers, Controller and Model.

The data is stored in a **postgres** database and the entire cache is made by **redis**, in redis the database user Id is linked to the socket id.

## Configuration 
### server
  Add postgres configuration data to server <i>/src/connections/config-pg.js</i>

  npm install <br>
  npm start

### app
  npm install <br>
  npm run serve


## Autor
| [<img src="https://avatars3.githubusercontent.com/u/30236552?v=4" width="110"><br><sub>@JeaanCa</sub>](https://github.com/jeaanca) |
| :---: |
