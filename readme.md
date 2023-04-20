<h1 align="center"># Bases de datos relacionales – DDL</h1>
<h2 align="center">Desarrollo</h2>

<img align='right' src="https://raw.githubusercontent.com/Cristian-Trureo/Modulo3-abpro-5/main/mysql2.png" width="250">


<h3>Parte 1: Crear entorno de trabajo</h3>
- Crear una base de datos
- Crear un usuario con todos los privilegios para trabajar con la base de datos recién creada.
<h3>Parte 2: Crear dos tablas.</h3>
- La primera almacena a los usuarios de la aplicación (id_usuario, nombre, apellido,
contraseña, zona horaria (por defecto UTC-3), género y teléfono de contacto).
- La segunda tabla almacena información relacionada a la fecha-hora de ingreso de los
usuarios a la plataforma (id_ingreso, id_usuario y la fecha-hora de ingreso (por defecto la
fecha-hora actual)).
<h3>Parte 3: Modificación de la tabla</h3>
- Modifique el UTC por defecto.Desde UTC-3 a UTC-2.
<h3>Parte 4: Creación de registros.</h3>
- Para cada tabla crea 8 registros.
<h3>Parte 5: Justifique cada tipo de dato utilizado</h3> 
¿Es el óptimo en cada caso?
<h3>Parte 6: Creen una nueva tabla llamada Contactos</h3>
debe contener `id_contacto, id_usuario, numero de telefono, correo electronico`
<h3>Parte 7: Modifique la columna teléfono de contacto, para crear un vínculo entre la tabla Usuarios y la tabla Contactos</h3>
El ejercicio debe ser subido a github y al Nodo Virtual.
