<h1 align="center"> ForoHub-Challenger</h1>
<h1 align="center"> Desafio Alura</h1>

<p>Este proyecto consiste en crear una API REST para la gestion de un foro, esta aplicacion web nos permite crear y guardar topicos en una base de datos.
Este es un proyecto propusto por Alura latam, para poner en practica lo aprendido en el transcurso de sus cursos.

Se implementaron las opciones de CRUD para los tópicos del foro:

1. **Registro de tópicos y guardarlos en la base de datos topicos**
2. **Listar los tópicos que están en la base de datos**
3. **Mostrar los datos de un tópico seleccionado**
4. **Modificar el tópico seleccionado**
5. **Eliminar el tópico seleccionado de la base de datos**
   
Y todo esto únicamente con el acceso autorizado usando la forma STATELESS de autenticación con JWT (JSON Web Token)

## Caracteristicas de la aplicación y demostración a través de insomnia:

**POST http://localhost:8080/login (autenticación y autorización con el login y clave previamente incluido en la base de datos en la tabla usuarios). Se debe copiar el JWT que regresa el sistema y pegarlo a todas las otras actividades en la parte Auth/Bearer token.**

![image](https://github.com/JavierFSR/ForoHub-Challenger/assets/162364232/de4350e0-95c7-4846-a7b8-d8d2efff0abb)   ![image](https://github.com/JavierFSR/ForoHub-Challenger/assets/162364232/7d316cae-6c62-4bed-979b-852fe4ee93b4)


**POST http://localhost:8080/topicos (Registro de un tópico)** 

![image](https://github.com/JavierFSR/ForoHub-Challenger/assets/162364232/09b78720-298e-4ae4-acc1-6b8278d75f15)

  
**GET http://localhost:8080/topicos Listar los tópicos que están en la base de datos.**

![image](https://github.com/JavierFSR/ForoHub-Challenger/assets/162364232/db0886a7-3f01-468b-b962-e11ee6e86724)


**GET http://localhost:8080/topicos/{id} Mostrar los datos de tópico con "id" (se pone el id que se desea buscar )**

![image](https://github.com/JavierFSR/ForoHub-Challenger/assets/162364232/ead6aa58-6677-4857-a52b-9269a4e987a0)

  
**PUT http://localhost:8080/topicos/{id} Modificar el tópico con "id" (se pone el id que se desea modificar y el atributo que se desea modificar)**
  
![image](https://github.com/JavierFSR/ForoHub-Challenger/assets/162364232/b943cdf9-03ca-4220-ac8c-9c926f0625ac)


**DEL http://localhost:8080/topicos/2 Eliminar el tópico con "id" de la base de datos, (se pone el id del topico que se desea eliminar)**
  
![image](https://github.com/JavierFSR/ForoHub-Challenger/assets/162364232/4f9856e6-37d9-41a1-98a6-ca3b1fc068e0)



  
## Acceso Al Proyecto
1. **Copia este repositorio.**
2. **Abre el archivo `src.java` en tu editor de código y ejecuta.**
3. **Sigue las instrucciones en el archivo para realizar las busquedas.**   
4. **Descarque el programa de Mysql.**
5. **Descargue el programa d Insomnia.**

## Tecnologias Utilizadas Y Dependencias Utilizadas
- **Java 17: Lenguaje de programacion principal**
- **Intellij IDEA: Entorno de desarrollo**
- **Spring Boot**
- **MySQL**
- **Maven**
- **Lombok**
- **Spring Web**
- **Spring Boot DevTools**
- **Spring Data JPA**
- **Flyway Migration**
- **MySQL Driver**
- **Validation**
- **Spring Security**

## Personas-Desarrolladores Del Proyecto
**Francisco Javier Soto Ramírez.**
