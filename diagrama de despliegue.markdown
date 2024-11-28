# Diagrama de despliegue 
----------

## Proceso de uso en el diagrama 

El diagrama muestra la arquitectura de implementación de una aplicación web de animes, detallando sus componentes principales y las tecnologías utilizadas. A continuación, se explica cada nodo y su función:

1. Dispositivos de los Usuarios

•	Navegadores Web : Usados por los usuarios para acceder a la aplicación mediante una interfaz web.

•	Dispositivos Móviles : Incluye aplicaciones móviles o navegadores móviles que envían solicitudes REST al servidor.

•	Tecnología : Comunicación mediante HTTPS usando solicitudes REST para interactuar con el servidor web.

2. Servidor Web
   
•	Compuesto por dos capas principales:

o	Frontend : Utiliza tecnologías como HTML , CSS y JavaScript para crear la interfaz gráfica y gestionar la interacción del usuario.

o	Backend : Basado en Spring Boot para manejar la lógica de negocio y procesar las solicitudes REST.

3. Base de datos

•	MySQL : Sistema de gestión de bases de datos utilizadas para almacenar información de la aplicación
•	Conexión : Se utiliza JDBC (Java Database Connectivity) para que el backend acceda a los datos almacenados en MySQL.

4. API externa

•MyAnimeList / AniList : Servicios externos que proporcionan datos relacionados con animes, como títulos, descripciones y reseñas.

•	Conexión : El backend consume estas API a través de solicitudes HTTPS , integrando los datos en la aplicación.

Aplicaciones utilizadas para diseño:

•	Lucid.app : Herramienta utilizada para crear diagramas visuales como este.

•	PlantUML : Lenguaje y herramienta de modelado que permite generar diagramas a partir de texto.

Es una muestra un sistema que combina frontend dinámico, backend robusto y acceso a bases de datos y API externas para ofrecer una experiencia rica y funcional.

Resumen completo de proceso

1.	Usuario envía solicitud →

2.	Frontend la recibe y la envía al backend →

3.	Backend procesa la solicitud :

o	Consulta la base de datos , API externa , o ambos.

4.	Backend envía la respuesta al frontend →

5.	Frontend presenta la información al usuario .

Este flujo permite un sistema eficiente y modular, combinando datos locales y externos para brindar una experiencia rica en contenido y respuesta rápida.


## Imagen 

![image](https://github.com/user-attachments/assets/89528590-971a-4573-b71f-6b5741eb8f14)
platext.

![image](https://github.com/user-attachments/assets/d36c0639-b902-402e-869e-74aeadbd1634)
lucid.app
