## Projeto Flask de Perguntas e Respostas

![Captura de ecrã_selecione a área_20220325102124](https://user-images.githubusercontent.com/84031272/160128662-521bf7d4-1a5b-4c9b-bd30-e6c4fb814125.png)

Projeto criado para conclusão do desafio do Bootcamp da DIO Cognizant

## SQL

```
create table users (
    id integer primary key autoincrement,
    name text not null,
    password text not null,
    expert boolean not null,
    admin boolean not null
);

create table questions (
    id integer primary key autoincrement,
    question_text text not null,
    answer_text text,
    asked_by_id integer not null,
    expert_id integer not null
);

```
