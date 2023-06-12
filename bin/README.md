<div align="left">
<h1><img src="https://github.com/Roberthdj/Foro-Alura/blob/master/readme-img/Inicio.png" alt="hotel_alura" width="100" height="100"/>  FORO ALURA</h1> 
</div>

<hr>

<p align="center">
   <img src="http://img.shields.io/static/v1?label=STATUS&message=EN DESARROLLO%20&color=RED&style=for-the-badge" #vitrinedev/>
</p>

## Tópicos 

- [Descripción del proyecto](#descripción-del-proyecto)

- [Funcionalidades](#funcionalidades)

- [Aplicación](#aplicación)

- [Herramientas utilizadas](#herramentas-utilizadas)

- [Acceso al proyecto](#acceso-al-proyecto).

- [Abrir un proyecto local](#abrir-un-proyecto-local)

- [Desarrollado por](#desarrollado-por)

## Descripción del proyecto 

<p align="justify">
Este proyecto se desarrolla con la finalidad de llevar al campo práctico los contenidos estudiados durante el desarrollo del curso de formación Java del programa Oracle Next Education ONE.<br><br>
En el vamos a replicar a nivel de back end este proceso, y para eso crearemos una API REST usando Spring, nuestra API va a centrarse específicamente en los tópicos, y debe permitir a los usuarios:

- Crear un nuevo tópico
- Mostrar todos los tópicos creados
- Mostrar un tópico específico
- Actualizar un tópico
- Eliminar un tópico

Es lo que conocemos comúnmente como CRUD (CREATE, READ, UPDATE, DELETE) y es muy parecido con lo que desarrollamos en el Hotel Alura, pero ahora usando un framework que va a facilitar mucho nuestro trabajo un nuevo modelo de arquitectura de software conocido como REST.
</p>

## Funcionalidad
- <p align="justify"><strong>Funcionalidad general:</strong> <br>
   <p align="justify"> Foro-Alura consta de cuatro entidades (Usuario, Curso, Topico, Respuesta) en las cuales podemos realizar acciones como crear un nuevo registro,    mostrar uno o todos los registros, actualizar y eliminar un registro en particular, para realizar las acciones necesarias para la comunicación con la aplicación se    utiliza la herramienta Postman.
   </p>
</p>


   ### 
     EndPoints:
     - Post:   http://localhost:8080/path
     - Get:    http://localhost:8080/path
     - Get:    http://localhost:8080/path/id
     - Put:    http://localhost:8080/path
     - Delete: http://localhost:8080/path/id
     
    path:  usuario
           curso
           topico
           respuesta

## Aplicación

<div align="center">

  <img src="https://github.com/Roberthdj/Foro-Alura/blob/master/readme-img/estructura.png" alt="Estructura_proyecto" width="350" height="250"/>
  <img src="https://github.com/Roberthdj/Foro-Alura/blob/master/readme-img/PostTopico.png" alt="Registrar_un_topico" width="350" height="250"/>
  <img src="https://github.com/Roberthdj/Foro-Alura/blob/master/readme-img/GetRespuesta.png" alt="Mostrar_respuestas" width="350" height="250"/>  
  <img src="https://github.com/Roberthdj/Foro-Alura/blob/master/readme-img/GetUnUsuario.png" alt="Mostrar_un_usuario" width="350" height="250"/>  
  <img src="https://github.com/Roberthdj/Foro-Alura/blob/master/readme-img/PutCurso.png" alt="Actualizar_un_curso" width="350" height="250"/>  
  <img src="https://github.com/Roberthdj/Foro-Alura/blob/master/readme-img/DeleteRespuesta.png" alt="Eliminar_una_respuesta" width="350" height="250"/>  

</div>

###

## Herramentas utilizadas

- <a href="https://www.java.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> --> Ver. 17.0.6</a> 

- <a href="https://netbeans.apache.org/" target="_blank"> <img src="https://netbeans.apache.org/images/apache-netbeans.svg" alt="netbeans" width="40" height="40"/> --> NetBeans IDE 14</a>

- <a href="https://www.mysql.com/" target="_blank"> <img src="https://www.mysql.com/common/logos/logo-mysql-170x115.png" alt="netbeans" width="40" height="40"/> --> Ver. 8.0.32</a>

- <a href="https://www.postman.com/" target="_blank"> <img src="https://github.com/Roberthdj/Foro-Alura/blob/master/readme-img/postman.svg" alt="netbeans" width="40" height="40"/> --> Postman</a>

###

## Acceso al proyecto

Tu puedes acceder aqui [al codigo fuente](https://github.com/Roberthdj/Foro-Alura) del proyecto. 

## Abrir un proyecto local

Para correr `Foro Alura`en tu máquina local:

- Crea un nuevo proyecto de nombre Foro-Alura en el IDE que estes usando para trabajar.

- Abre una terminal de git en la ubicacion donde se aloja el nuevo proyecto que creaste

- Inicializa el proyecto en la teminal con la linea: git init

- Conectate al repositorio remoto con la linea: git remote add origin https://github.com/Roberthdj/Foro-Alura.git

- Luego la linea: git remote -v

- Finalmente ejecuta la linea: git pull origin master

Si todo va bien, tu nuevo proyecto se sincronizo correctamente con el repositorio y debes realizar los ajustes necesarios en tu IDE!


## Desarrollado por

[<img style ="border-radius: 20px" src="https://avatars.githubusercontent.com/u/120141795?v=4" width=115><br><sub>Roberth de Jesus Rodriguez Castro</sub>](https://github.com/roberthdj)
