# Primera-Entrega-Proyecto-Equipo-9
Primera entrega de Proyecto perteneciente al Equipo 9 de Programación II

**NOTAS DEL PROYECTO**

Funcionamientos extra: 
-Historial 
-Ranking 
-Partida amistosa 
-Modo de juego rápido 
-Ayudante de tiro 

Explicación del diagrama: 

En el diagrama, la clase admin se encarga de administrar todos los datos, es el que obtiene los datos que las otras clases precisan, y crea y actualiza el tablero. 
El perfil de usuario es la clase que almacena los datos de cada jugador. El mismo contiene los datos básicos de la persona, pero además contiene un NumeroDeJugador para identificar los distintos jugadores, un Oponenteenpartida para ver con que otro jugador está emparejada la persona, y la cantidad de ganadas y pérdidas totales de la persona, para simplificar el acceso al ranking. 
El historial de partidas es el almacenamiento de todas las partidas que se han jugado. 
El ranking se encarga de recorrer los perfiles de usuario para ver cuantas partidas ganadas tiene cada jugador a través de su atributo ganadas, y ordena a los jugadores en base a eso. 
La impresora por consola se encarga de imprimir los datos.
Tablero rapido hereda los mismos datos que tablero pero ademas posee otra tirada para que sea mas rapido.

 

 

Roles de clases: 
-admin: controller 
-impresora: interface 
-modos: coordinator 
-perfil: information holder 
-historial: information holder 
-partida: information holder 
-logica: structurer (editado) 
-impresoraConsola: service provider 
-emparejamiento: service provider 
-tablero: service provider 
-tableroRapido: service provider 
-jugador: controller 

 

Notas: 

Al comenzar con el diagrama de clases nos tomó tiempo en hacerlo, primero de todo, nos planteamos distintas formas para hacer el diagrama (UML simple), luego vimos e identificamos las clases del modelo que íbamos a incluir dentro de este, estuvimos mucho tiempo deduciendo acerca de qué clases que teníamos que hacer y analizarlas para ver que patrón o principio utilizar en caso de que estas las necesiten, luego hechas las clases en el diagrama fuimos pensando en cuál era su funcionamiento, es decir, cómo las hacíamos funcionar y que clases necesitaban de otra.  
Enfrentándonos a estas interrogantes aprendimos a representar correctamente las interacciones entre clases. 
También podemos decir que aprendimos a no quedarnos con la primera versión de lo que sea que hagamos, porque siempre puede haber un caso acerca de que lo que hayamos hecho que sea mejorable en distintos aspectos. 

 

Bibliografía: 

Wirfs-Brock, Rebeca y McKean, Alan; "Object Design: Roles, Responsibilities, and Collaborations"; Addison-Wesley Professional; ISBN 0201379430; 2002. 

(309) Cómo HACER Una MATRIZ En C# - MATRICES | Desarrollo en CSharp (C#) #28 - YouTube 

(309) Cómo RELLENAR Y LEER MATRICES En C# - Ejercicio | Desarrollo en CSharp (C#) #29 - YouTube  
