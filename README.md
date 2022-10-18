# repositorio-de-api-gateway-ciclo4
El presente proyecto se desarrolla en el marco del **Diplomado MISION TIC 2022** ofrecido por el **Ministerio de las TIC**
y desarrollado en nuestro caso por la **_UNIVERSIDAD NACIONAL DE COLOMBIA_**.

Esta presentacion tiene como objetivo documentar el Repositorio de Api Gateway el cual es un microservicio que hace parte del producto denominado **_Proyecto Registraduria_** que corresponde al ciclo 4A (_Profundizacion Desarrollo Web_) del diplomado;que pretende llevar a cabo el proceso de implementación del módulo de registro de resultados de las elecciones al senado bajo la modalidad de voto preferente.


_ _ _
A continuacion se relacionan los integrantes del equipo responsable del desarrollo e implementacion del proyecto.

| NOMBRES                          | RESPONSABLE DE       |
|---                               |---|
| Carlos Alberto	Espitia Diaz     |Api Gateway           |
| Carlos Eduardo	Naranjo Riascos  |Backend Resultados   |
| Angel Manuel	Alvarado Diaz      |Frontend             |
| Carlos Arturo	Cepeda             |Backend de Seguridad    |

_ _ _

La Api Gateway interconecta a todos los Microservicios : Backend de Seguridad, Backend de Resultados y el Frontend.
Se instala frente a todos los microservicios sin importaar la cantidad.
La Api Gateway intercepta todas las llamadas Api de los clientes y los enruta hacia el microservicio indicado. 
Se encarga de la autorización y autenticación de los APi consumer.
Monitoreo constante para obtener metricas de todas las llamadas y el trafico que se genera hacia el Api Gateway 
Se encarga de limitar las llamadas hacia el APi para evitar que personas con malas intenciones puedan cargar con millones de peticiones al sistema afectando la seguridad del mismo.
Se puede poner un maximo de llamadas a trvez de Api Gateway en un determinado lapso de tiempo.

***

En este microservicio trabajaremos con el Framework **Spring Boot**

***
Se utilizara el formato _JSON_ para las comunicaciones entre los diferentes modulos del sistema.


***
