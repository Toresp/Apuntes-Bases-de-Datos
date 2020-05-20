## INDICE
- 1.- [**Ejercicio 3**](#1)
   - 1.2.- [**Ejercicio 3 departamentos**](#1.1)
   - 1.3.- [**Ejercicio 3 naves**](#1.2)
- 2.- [**Ejercicio 4**](#2)
# Ejercicio 3 <a name="1"/>

## Creación de proxectos <a name="1.1"/>
* 1.- Empezamos creando la base de datos con un -Create Database proxectos;
* 2.- A continuación empezamos con la construcción de las tablas, constraints, etc... Se muestra todo el proceso paso a paso en las siguientes capturas.
### Creación tabla Sede
* ![1](https://user-images.githubusercontent.com/57723793/82446828-a663dd80-9aa7-11ea-8bf6-0d08d6188865.PNG)
### Creación tabla Departamento
* ![2](https://user-images.githubusercontent.com/57723793/82446829-a663dd80-9aa7-11ea-8a72-c02acc5ed1cf.PNG)
### Creación tabla Ubicacion
* ![3](https://user-images.githubusercontent.com/57723793/82446830-a6fc7400-9aa7-11ea-92a2-c2f383145485.PNG)
### Creación tabla Grupo
* ![4](https://user-images.githubusercontent.com/57723793/82446831-a6fc7400-9aa7-11ea-9f70-1bbc6d07dddb.PNG)
### Creación tabla Profesor
* ![5](https://user-images.githubusercontent.com/57723793/82446814-a4018380-9aa7-11ea-93ef-30ad78707d4e.PNG)
### Creación tabla Proxecto
* ![6](https://user-images.githubusercontent.com/57723793/82446816-a49a1a00-9aa7-11ea-87a0-fc6171161590.PNG)
### Modificación tabla Departamento
* ![7](https://user-images.githubusercontent.com/57723793/82446817-a49a1a00-9aa7-11ea-87b3-641cc3195c81.PNG)
### Modificación tabla Grupo
* ![8](https://user-images.githubusercontent.com/57723793/82446820-a532b080-9aa7-11ea-845f-7df184b727db.PNG)
### Creación tabla Participa
* ![9](https://user-images.githubusercontent.com/57723793/82446821-a532b080-9aa7-11ea-93a0-b3533e69479c.PNG)
### Creación tabla Programa
* ![10](https://user-images.githubusercontent.com/57723793/82446822-a5cb4700-9aa7-11ea-8413-24fc1eada567.PNG)
### Creación tabla Financia
* ![11](https://user-images.githubusercontent.com/57723793/82446823-a5cb4700-9aa7-11ea-835d-907c9b5a9f88.PNG)
Y con esta última captura finalizamos todo el proceso de creación de la base de datos.


## Creación de Naves <a name="1.2"/>
* 1.- Create Database Naves; --Se crea la base de datos.
* 2.- A continuacion muestro capturas de todo el proceso de creacion de tablas con todos sus datos y constraints.
### Creación tabla Tripulación
* ![1](https://user-images.githubusercontent.com/57723793/80109486-d63dc500-857d-11ea-84a1-a86ef8afd6bb.PNG)
### Creación tabla Dependencia
* ![2 0](https://user-images.githubusercontent.com/57723793/80109535-e5247780-857d-11ea-8165-9cbc0e9df63c.PNG)
### Creación tabla Camara
* ![2](https://user-images.githubusercontent.com/57723793/80109557-eb1a5880-857d-11ea-94c1-5fdeaaa650a5.PNG)
### Creación tabla Visita
* ![3](https://user-images.githubusercontent.com/57723793/80109558-ebb2ef00-857d-11ea-9a64-883ec2012381.PNG)
### Creación tabla Planeta
* ![4](https://user-images.githubusercontent.com/57723793/80109559-ebb2ef00-857d-11ea-8457-9245070c44af.PNG)
### Creación tabla Habita
* ![5](https://user-images.githubusercontent.com/57723793/80109562-ec4b8580-857d-11ea-998e-79bd03e1230c.PNG)
### Creación tabla Raza
* ![6](https://user-images.githubusercontent.com/57723793/80109548-ea81c200-857d-11ea-8584-1a8b7ae8a98d.PNG)
#### Alter Table a las distintas tablas para añadir las Foreign Keys y Primary Keys
* ![7](https://user-images.githubusercontent.com/57723793/80109554-eb1a5880-857d-11ea-8f0f-9b836e0405a2.PNG)

* ![8](https://user-images.githubusercontent.com/57723793/80109577-eeaddf80-857d-11ea-8f36-a3135949011c.PNG)

* ![9](https://user-images.githubusercontent.com/57723793/80109579-eeaddf80-857d-11ea-8de7-1fe8cd537426.PNG)

* ![10](https://user-images.githubusercontent.com/57723793/80109583-eeaddf80-857d-11ea-9175-8ba7b56690c0.PNG)

* ![11](https://user-images.githubusercontent.com/57723793/80109585-ef467600-857d-11ea-8f52-e3bde6c0067a.PNG)
Estas serian todas la ejecuciones realizadas para crear la base de datos, esta todo por orden de creacion segun nuestro esquema relacional y está hecho en MariaDB por lo que difiere de mi versión hecha en PostgreSQL




# Comandos para observar nuestras tablas <a name="2"/>
* Mediante los siguientes comandos podemos observar nuestras tablas creadas, sus columnas...
    * Show Databases: Nos muestra todas las bases de datos existentes.
* ![showD](https://user-images.githubusercontent.com/57723793/80111762-95937b00-8580-11ea-96ed-d1b7875322db.PNG)
    * Use **Nombre BaseDeDatos**: Accedemos a la base de datos que hemos elejido y en la cual comenzaremos a trabajar.
    * Show Tables: Nos muestra todas las tablas una vez nos encontremos usando una base de datos.
* ![show](https://user-images.githubusercontent.com/57723793/80111760-94fae480-8580-11ea-861b-8091529b7ebc.PNG)
    * describe **NombreTabla**: Nos permite ver el tipo de datos y otros datos adicionales de cada Columna en la tabla que hemos especificado  
* ![describe](https://user-images.githubusercontent.com/57723793/80111758-94624e00-8580-11ea-91a1-9dd47a0e18c5.PNG)

