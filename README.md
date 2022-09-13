# consultas_1.sql

#CONSULTAS SQL


1. Para visualizar toda la informacion que contiene la tabla `usuario` se puede incluir con la instruccion SELECT el caracter '*' o cada uno de lo campos de la tabla

SELECT * FROM `usuario` 
![tabla usuario](img/consultas1.png "consulta1")


2. visualizar solamente la identificacion del usuario.

SELECT identificacion FROM `usuario`
![consulta2](img/tablausuario.png "consulta2")

3. se desea obtener los registros cuya identificacion sean mayoes o iguales a 150, se debe utilizar la claudala WHERE que especifica las condiciones que deben reunir los registro que se debe reunir los registros que se van a seleccionar.

SELECT * FROM `usuario` WHERE identificacion>='150'
![consulta3](img/consulta3.png "consulta3")

4. sii se desea obtener los registros cuyo sus apellidos sean vanegas o cetina se debe utilizar el operador IN que especifica los registros que se quieren visualizar de una tabla 

SELECT apellidos FROM `usuario` WHERE apellidos IN ('vanegas','celina');
![consulta4](img/consulta4.png "consulta4")

o se puede utilizar el operador OR.
SELECT apellidos FROM `usuario` WHERE apellidos='vanegas' OR apellidos='cetina';
![consulta4](img/consulta4-2.png "consulta4")




