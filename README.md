# Demo arquitectura hexagonal con Java
Este proyecto es un ejemplo de desarrollo de una API REST aplicando Arquitectura Hexagonal.

鈿欙笍 Instalaci贸n del proyecto

Clonar el repositorio en tu equipo:

> git clone https://github.com/AmadorBF/demo.git

Importar el proyecto mediante IntelliJ IDEA

> Import Project y seleccionar la carpeta del proyecto.

Marcar Create Project from external model, elegir Maven.

馃敡 Configuraci贸n

No es necesario disponer de ning煤n gesto de base de datos, incluye H2

Puerto necesario para servicio rest 8080

馃殌 Ejecuci贸n

Mediante mvn (situado en la carpeta principal del proyecto):

> mvnw clean install
>  
> mvnw spring-boot:run 

Ejecuci贸n jar:

> java -jar target/demo-0.0.1-SNAPSHOT.jar

鉁旓笍 Testing

Ejecutar tests unitarios: 

> mvnw test

Ejecutar test unitario individual: 

> mvn test -Dtest="nombreClaseTest#metodoTest"

馃殌 Ejecuci贸n Rest

> http://localhost:8080/api/v1/products/price
> 
> Par谩metros tipo query:
> 
> brandId=rama
> 
> productId=c贸digo de producto
> 
> fechaAplicacion=yyyy-MM-dd HH:mm:ss

![ image](https://user-images.githubusercontent.com/17526730/205511984-d9735384-54cb-445c-a99c-41eacddc24ec.png)
