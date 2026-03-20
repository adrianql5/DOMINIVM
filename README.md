# Dominivm

Proyecto de la asignatura Diseño de Software del Grado en Ingeniería Informática (GrEI), curso 2024/25.

Autores: Denís Díaz Otero, Víctor Fraga Izquierdo, Xabier Nóvoa Gómez, Adrián Quiroga Linares, Iván Gutiérrez García.

## Introducción

Dominivm es un trabajo académico centrado en el diseño de un videojuego de estrategia por turnos ambientado en la Edad Antigua. El objetivo del proyecto no es desarrollar una versión jugable, sino definir su arquitectura y su funcionamiento mediante modelos UML y decisiones de diseño de software.

## Objetivo

El proyecto busca construir una base sólida para un posible desarrollo futuro del juego. Para ello se describe tanto el comportamiento del sistema como su estructura interna, prestando atención a las responsabilidades de cada elemento y a las relaciones entre ellos.

## Alcance del trabajo

La documentación incluida en el proyecto recoge:

- Diagramas de casos de uso para representar las principales acciones disponibles para los jugadores.
- Diagramas de secuencia asociados a cada caso de uso, incluyendo escenarios alternativos y situaciones excepcionales.
- Un diagrama de clases que describe la organización estructural del sistema.
- La aplicación de varios patrones de diseño para mejorar la claridad, la extensibilidad y el mantenimiento del modelo.

## Patrones de diseño utilizados

En el diseño del sistema se han empleado los siguientes patrones:

- Factory Method
- Facade
- Strategy
- Observer
- Singleton
- Composite
- State

## Descripción general del sistema

El sistema modela una partida en la que hasta cuatro jugadores controlan distintos imperios históricos. A lo largo del juego pueden desplazarse por el mapa, recolectar recursos, construir y reparar estructuras, crear unidades civiles y militares, organizar grupos de ataque o defensa y enfrentarse a enemigos en posiciones adyacentes.

Todas estas mecánicas se describen a nivel de diseño. El proyecto no incluye implementación de la lógica del juego ni una interfaz gráfica.

## Conclusión

El trabajo presenta una propuesta de diseño completa para un videojuego de estrategia por turnos, con especial atención a la organización del sistema y al uso de patrones de diseño adecuados. Aunque no existe una implementación funcional, la documentación sirve como base para un desarrollo posterior.
