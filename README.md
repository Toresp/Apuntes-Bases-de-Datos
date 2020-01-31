# Apuntes-Bases-de-Datos
Apuntes Para SQL:
    • SELECT: Escoge la tabla que se va a mostrar.
        ◦ AS: Sirve para que al mostrar en la tabla se cambie el nombre de la tabla que se va a mostrar. 
    • FROM: La tabla de la que se van a coger los datos.
    • WHERE: Función básica para las consultas le precede el conjunto de datos que se va a comparar.
        ◦ LIKE: Sirve para comparar que algo sea igual a algo que declaremos.
        ◦ IN: en ()* Conjunto de valores.
        ◦ CONCAT: Concatena 2 o mas valores se escribe de forma: CONCAT(v1,v2,…).
        ◦ BETWEEN: Entre valores dados.
        ◦ XOR: Excluye un conjunto de valores.
        ◦ IS: el valor da es.
        ◦ NULL: La tupla no tiene ningún valor.
        ◦ ALL: todos los valores dados.
        ◦ <>:Indica que los valores a ambos lados están negados (Que estos dos valores sean diferentes).
    • REPLACE:  Substituye de una tabla un valor dado por otro dado de forma: REPLACE(Tabla, vp,vs).
    • ROUND: redondea los valores datos añadiendo una coma al final del numero que divide para indicar el numero de decimales indicados. ROUND(VALORES/NUMERO,NºDec).
    • DISTINC:Para que un valor solo es exprese una vez y no se repita, Se coloca luego del SELECT(Se recomienda no usarlo).
    • SUM(): Suma los valores dados.
    • COUNT():Cuenta la cantidad de veces que se repite el el valor dado.
    • GROUP BY: Agrupa según el criterio escrito.
    • HAVING: Teniendo en cuenta que, se usa para comprobar lo que se tiene por ejemplo HAVING SUM(Something)>=1000000, Teniendo en cuenta que la suma de algo sea superior a un millón 
      NOTA: Having va siempre despues de GROUP BY().
    • JOIN: su uso es para juntar dos tablas o mas de manera que se escribira t1 JOIN t2 ON “(Los dos valores clave de cada tabla separados con un = )” t1 JOIN t2 ON (idt1 = idt2)
        ◦ Hay distintos tipos de JOIN esta el INNER JOIN que coge los valores en común de ambas tablas, el LEFT JOIN que coge los valores Comunes de ambas tablar y los valores de la tabla de la izquiera y el RIGHT JOIN que hace lo mismo que el LEFT JOIN pero coge en este caso los valores de la derecha
        ◦ Se pueden hacer JOIN de 3 tablas de manera que solo habria que añadir un JOIN al lado del JOIN de la tabla que tenga valores iguales de ambas tablas para correlacionarlas.
    • CASE se usa para comparar valores e indicar lo que se quere mostrar de manera siguiente
      CASE WHEN v1=x //Cuando el valor equivale a x
              THEN ‘Pepe’ //Entonces escribe pepe
              WHEN v1 = y 
              THEN ‘Pedro’ 
              ELSE ‘algo’ //En caso de que no se cumpla nada de lo anterior escribe “Algo”
  	END 		//Finaliza el CASE.
-%Substituye cualquier cantidad de caracteres(También valen números y espacios).
- _ Substituye un solo carácter.
- 

SELECT name
  FROM world
 WHERE population >= ALL(SELECT population
                           FROM world
                          WHERE population>0)
En este codigo Para evitar el Problema de los Null y que pete al comparar substituimos E

En consultas con selects dobles para querer comparar dos Tablas de las que vienen siendo la misma tabla se le añade una nomeclatura diferente a la propia tabla.




















Preparar Git con GitHub
Para empezar usando la consola del ordenador (Desde Linux) los comandos para la instalación de Git, primero añadimos el repositorio: 
> sudo add-apt-repository ppa:git-core/ppa
> sudo apt update
> sudo apt install git

Comprobación de que Linux detecta git:
> git –version

Devuelve la version de Git.

Ahora se configura el nombre de la cuenta el email y el editor (Opcional) Navegamos a la raiz y ejecutamos:
> git config --global user.name (Nombre)
> git config --global user.email (El Email)
> git config --global core.editor (Editor)

