create database db_generation_game_online;

use db_generation_game_online;

create table tb_classe(
	id bigint(5) auto_increment,
    classe varchar(30) not null,
    raça varchar (30) not null,
    habilidade varchar (30) not null,
    
    primary key (id)
);


insert into tb_classe (classe, raça, habilidade) values ("Ladino", "Goblin", "Furtivo");
insert into tb_classe (classe, raça, habilidade) values ("Paladino", "Tauren", "Pele De Ferro");
insert into tb_classe (classe, raça, habilidade) values ("Guerreiro", "Orc", "Berserk");
insert into tb_classe (classe, raça, habilidade) values ("Arqueiro", "Elfo", "Velocidade");
insert into tb_classe (classe, raça, habilidade) values ("Mago", "Undead", "Magia Negra");


select * from tb_classe;