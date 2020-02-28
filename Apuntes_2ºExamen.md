Hay 1 lenguaje y 6 sublenguajes
  * **DQL** (Data Query Language): SELECT
  * **DML** (Data Manipulation Language):INSERT, UPDATE, DELETE. Opera Sobre datos
  * **DDL** (Data Definition Language): CREATE, ALTER, DROP. Opera sobre os obxectos da BD
    * 
  * **TCL** (Transaction Control Language): COMMIT, ROLLBACK.
  * **DCL** (Data Control Languague): ALTER SESSION.
  Tipos de valores:
  * Integer
  * Decimal
  * Char: Longitud fija entre paréntesis la longitud máxima
  * Varchar: La longitud es variable entre parentesis el máximo.

  
  Formulas
  Crear tabla:
  ```mysql
  CREATE TABLE table_name (
   column_name TYPE column_constraint,
   table_constraint table_constraint
) INHERITS existing_table_name;
  ```
  Un ejemplo aplicando esto sería:
  ```mysql
  CREATE TABLE cuenta(
   user_id serial PRIMARY KEY,
   username VARCHAR (50) UNIQUE NOT NULL,
   password VARCHAR (50) NOT NULL,
   email VARCHAR (355) UNIQUE NOT NULL,
   created_on TIMESTAMP NOT NULL,
   last_login TIMESTAMP
);
  ```
  UPDATE para actualizar unformacion:
  ```mysql
  UPDATE table_name
  SET atributo1 = valor1,
      atributo2 = valor2,
      [WHERE predicato];
  ```
  
 * CREATE (SCHEMA|DATABASE) Crear unha base de datos
 * [IF NOT EXISTS] nome-da-BD Realizar comprobacions de existencia 
 * [CHARACRER SET<nomeCoCharset>];
 *FOREIGN KEY.
 * Restricciones:
 **3º Restriccion**
  * [CONSTRAINT <name-constriccion>] 
  * UNIQUE (<atributos>)
  **4º Restriccion**
  ```mysql
   [CONSTRAINT ]
   CHECK Predicado (atributos)
   [[NOT] DEFERRABLE]
   [INITIALLY INMEDIATE | DEFERRANLE]
   ```
 En los checks se pueden meter consultas
 *DROP SCHEMA:*Vale para borrar la base de datos entera pero por si acaso debemos comprobar si existe con *[IF EXISST] <nombre tabla>*
 Borrar la tabla *DROP TABLE* E igual que antes para comprobar IF EXIST <Table name>
 Usando CASCADE elimina todas las subtablas RESTRINCT lo restringe.
 * ALTER TABLE...(Opciones)
   * ADD [COLUMN] _atributo_ _dominio_ Añadir una columna
   * DROP COLUMN _atributo_ [CASCADE | RESTRICT] Eliminar una columna.
 * ADD _restriccion_
 * DROP _restriccion_
 ```mysql
  INSERT INTO table_name
       [ ( column_name [, ...] ) ]
       VALUES ( value [, ...] )

 ```
 | SELECT *Se puede insertar un SELECT para hacer una consulta de los datos que vamos a insertar, el select tiene que tener el mismo numero de columnas)
 * 
