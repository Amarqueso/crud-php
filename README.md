# Projeto CRUD em PHP
Este projeto é um sistema CRUD (Create, Read, Update, Delete) desenvolvido em PHP utilizando o XAMPP como servidor local e o phpMyAdmin para gerenciar o banco de dados.

Descrição
O sistema permite o cadastro e a gestão de transações financeiras através de uma interface web simples e intuitiva. Os dados são armazenados em um banco de dados MySQL.

Banco de Dados
Database: cadastro
Tabela: transacao
Estrutura da Tabela transacao
Campo	Tipo	Características	Nullable	Padrão
id	INT(10) UNSIGNED	Chave primária, auto-incremento	Não	Nenhum
valor	FLOAT	Valor da transação	Não	Nenhum
tipo	VARCHAR(255)	Tipo da transação (ex: despesa, receita)	Não	Nenhum
despesa_receita	VARCHAR(255)	Classificação da transação	Não	Nenhum
Tecnologias Utilizadas
PHP
MySQL
XAMPP
phpMyAdmin
