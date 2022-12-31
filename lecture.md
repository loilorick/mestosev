В консоль проекта - 

npm install;
Set-ExecutionPolicy -ExecutionPolicy Bypass;
npm install -g sass;
npm install --save-dev typescript;
npm install --save-dev @types/node;
npm install --save-dev @types/react;
npm install --save-dev @types/react-dom;
npm install --save-dev @types/react-redux;
npm install --save-dev @types/react-router-dom;

Запуск проекта - 
node app.ts; или npm run dev;



В консоль базы данных для её установки - 

create database project;
use project;
create table items(id int primary key auto_increment, title varchar(255), image varchar(255), description text, date_creating varchar(32), author varchar(255), price int);
create table comments(id int primary key auto_increment, commentary text, date_creating varchar(32), author varchar(255), item_id int);
create table users(id int primary key auto_increment, username varchar(255), password varchar(32), role varchar(255));
