Tutoriel SQLite

Lancer SQLite3

```bash
sqlite3
```

Obtenir de l’aide

```sqlit
.help
```

Quitter sqlite

```sqlite
.exit
```

Ouvrir une base de données

```sqlite
.open path/to/db
```

Ouvrir une session en créant une base de données qui n’existe pas encore

```sqlite
sqlite3 path/to/dbName.db
```

Lister les bdd

```
.databases
```

Créer une nouvelle base de données dans le contexte

```sqlite
ATTACH DATABASE "path/to/dbName.db" AS dbName;
```

Montrer les tables

```sqlite
.tables
```

Montrer la structure d’une table

```sqlite
.schema albums
```

Montrer toute la structure de données

```sqlite
.fullschema
```

## Requêtes

Enregistrer le résultat d’une requête dans un fichier

```sqlite
.output albums.txt
SELECT title FROM albums;
```

Exécuter une déclaration SQL contenue dans un fichier avec `.read`

```sqlite
.read path/to/sql.txt
```

## Créer une table

```sqlite
create table student(
id int not null,
firsName varchar(255),
lastName varchar(255),
subject varchar(255),
score int,
primary key (id)
);
```

Montrer le schéma

```sqlite
.schema
```

Voir la table créée

```sqlite
.table
```

Insérer des données

```
insert into students values(1, 'Chris', 'Baru', 'Histoire', 97);
insert into students values(2, 'Mark', 'Stern', 'Art', 93);
insert into students values(2, 'David', 'Glass', 'Art', 90);
```

Requêter

```sqlite
select * from students;
```

```sqlite
.headers on
```

```sqlite
.mode column
```



