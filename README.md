# Taller_4_y_5_JAVA_WEB
***
Taller 4 y 5 de java avanzado, en el cual pusimos en practica la conexion con bases de datos (Mysql) a un formulario login realizado en java.
****

## Tabla de contenidos 

1. [Info-General](#info-general)
2. [Descripcion](#descripcion)
3. [Resultados](#resultados)


## Info-General
***
Proyecto creado para realizar un formulario de ingreso de un usuario y un login, usando Html 5, css y bootstrap.
En el, creamos varias clases en nuestra  carpeta util de nuestro proyecto, las cuales son la base para que nuestra conexion se logre exitosamente.
Adicionalmente, lograremos visualizar si nuestra conexion se realizo en una de estas clases.
Por ultimo, crearemos una base de datos con una sola tabla, la cual conectaremos.

## Descripcion
***
Luego de haber realizado el login usando html 5 y lo demas, en la carpeta Util del proyecto crearemos 6 clases fundamentales para lograr la conexion.
Nos dirigimos a nuestro archivo pom.xml y le agregamos la dependencia 8.0.33 (Mysql).
Entramos a Mysql y creamos un usuario diferente a root, en el cual crearemos una base de datos que contenga una sola tabla llamada users_tbl con los siguientes campos:
user_id INT, user_firstname, user_lastname, user_email, user_password, cada uno con su tipo de dato y sin olvidar que la llave primaria es el Id y es  auto_increment.
En nuestra base de datos realizamos un Alter table para modificar el campo de la contraseña del usuario (user_password), tambien realizamos un insert añadiendo la funcion AES_ENCRYPT que nos codifica los datos con una longitud de clave de 128 bits y por ultimo realizamos la sentencia SELECT.
```
$ clonar git (https://github.com/200ximena/Taller_4_y_5_JAVA_WEB.git)
```

## Resultados
***
![image](https://user-images.githubusercontent.com/128264476/236561360-d0fb8884-e87a-442c-9599-9725df3daa92.png)

![image](https://user-images.githubusercontent.com/128264476/236561406-bcf03967-526c-4128-9121-606d58ac60b6.png)

![image](https://user-images.githubusercontent.com/128264476/236560872-c1752b42-c5d7-44cf-a2a5-af103f17994a.png)





