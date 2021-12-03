### Prerequisites

1. **node**@_12.21.0+_
2. **npm**@_6.14.11+_
3. **mysql**@_5.5.7+_

### To start project

Set the following database variables in `server/config/config.json` file for your development environment:

```
"development": {
  "username": "root", // Need to update your own username
  "password": "password", // Need to update your own password
  "database": "apartments_db",
  "host": "127.0.0.1",
  "dialect": "mysql"
},
```

### client

- yarn install
- yarn start

### server

- yarn install
- yarn db:migrate
- yarn db:seed
- yarn start

### admin credentials

- email: admin@example.com
- password: password

### realtor credentials

- email: realtor01@exmaple.com
- password: password

### client credentials

- email: client01@exmaple.com
- password: password
