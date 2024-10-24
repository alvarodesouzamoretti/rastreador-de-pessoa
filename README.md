create database pesquisa_cliente;
use pesquisa_cliente;
create table cliente(
id_cliente int not null auto_increment,
nome varchar (100),
sexo char(1),
idade int,
cidade varchar(100),
primary key(id_cliente)
);

insert into cliente (nome, sexo,idade,cidade) values
('Pedro josé','m','35','Morretes');
insert into cliente (nome, sexo,idade,cidade) values
('Maria','f','26','Antonina');
insert into cliente (nome, sexo,idade,cidade) values
('Carla','f','34','Antonina');
insert into cliente (nome, sexo,idade,cidade) values
('Marcus','m','53','Curitiba');

select * from cliente;

select * from cliente where cidade = 'Antonina';
select * from cliente where sexo = 'm';
