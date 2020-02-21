Hay 1 lenguaje y 6 sublenguajes
  * **DQL** (Data Query Language): SELECT
  * **DML** (Data Manipulation Language):INSERT, UPDATE, DELETE. Opera Sobre datos
  * **DDL** (Data Definition Language): CREATE, ALTER, DROP. Opera sobre os obxectos da BD
    * 
  * **TCL** (Transaction Control Language): COMMIT, ROLLBACK.
  * **DCL** (Data Control Languague): ALTER SESSION.
  

  
  Formulas
 * CREATE (SCHEMA|DATABASE)
 * [IF NOT EXISTS] <nome-da-BD>
 * [CHARACRER SET <nomeCoCharset>];
 * Restricciones:
 **3º Restriccion**
  * [CONSTRAINT <name-constriccion>] 
  * UNIQUE (<atributos>)
  **4º Restriccion**
  ```mysql
   [CONSTRAINT <>]
   CHECK Predicado (atributos)
   [[NOT] DEFERRABLE]
   [INITIALLY INMEDIATE 
   ```
