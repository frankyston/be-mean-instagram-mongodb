# MongoDB - Aula 01 - Exercício
autor: Frankyston Lins

## Importando os restaurantes
mongoimport --db be-mean --collection restaurantes --drop --file restaurantes.json
2015-11-09T21:28:16.308-0200	connected to: localhost
2015-11-09T21:28:16.309-0200	dropping: be-mean.restaurantes
2015-11-09T21:28:17.186-0200	imported 25359 documents

## Escolhendo o banco de dados
use be-mean;

## Contando os restaurantes
db.restaurantes.find({}).count();
25359
