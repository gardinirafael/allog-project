# ALLOG Development Test
Rafael Angelo Gardini - gardini.rafael@gmail.com
Obrigado pela oportunidade!!!

# Frameworks
- Angular 4
- Node JS

# Database
- MySQL

# Alterar dados de conexão
-cd backend
-edit app.js

app.use(
  connection(mysql, {
    host: 'localhost',
    user: 'root',
    password: 'password',
    port: 3306,
    database: 'db_weather'
  }, 'request')
);

# Módulos do Angular
-cd frontend
-npm install

# Instalar express Node Js
cd backend
npm install -g express-generator

# Iniciar aplicação usando proxy devido ao CORS
ng serve --open --proxy-config proxy.config.js