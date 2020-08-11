# Express Backend Project Template

## Project setup
```bash
npm install
```

### Compiles and hot-reloads for development
```
npm run dev
```
### Setup a .env file in root
```env
# EXAMPLE FILE
NODE_ENV=development

SERVER_PORT=5050

JWT_SECRET=HeLlOTheRE-gEneRalKenoBI
JWT_EXP=10d

# SQL DATABASE
DB_HOST=
DB_USER=
DB_PASS=

# NOSQL DATABASE
MONGO_DBURL=
```
---
### TODO:
- Add branch with SequelizeORM
- Add branch with MongooseODM
- Add branch with TypeORM
---
### Dependencies
- express
- dotenv
- colors
- morgan
- bcrypt
- helmet
- hpp
- xss-clean
- jsonwebtoken
- validator

### Dev Dependencies
- babel
- eslint
- prettier
- nodemon
- rimraf