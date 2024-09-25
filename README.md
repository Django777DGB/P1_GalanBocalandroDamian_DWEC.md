# **Proyecto de Aplicación Web para Rutinas de Entrenamiento en el Gym**

![portada](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX1-Q1o7EOGmXr_ufKGCaPz73OC6G8mgh5XA&s)

### **Autor:**

- Damián Galán Bocalandro

---

## **Índice**

1. [Idea de la Aplicación](#idea-de-la-aplicación)
2. [Audiencia Objetivo](#audiencia-objetivo)
   - [Principiantes en el ejercicio](#principiantes-en-el-ejercicio)
   - [Atletas Intermedios](#atletas-intermedios)
   - [Personas con Objetivos Específicos](#personas-con-objetivos-específicos)
   - [Personas con Poco Tiempo](#personas-con-poco-tiempo)
   - [Personas con Movilidad Reducida](#personas-con-movilidad-reducida)
3. [Análisis de Mercado](#análisis-de-mercado)
4. [Tecnologías Empleadas](#tecnologías-empleadas)
5. [Compatibilidad con Navegadores](#compatibilidad-con-navegadores)
6. [Modelos de Ejecución](#modelos-de-ejecución)
   - [Importancia del Modelo Cliente-Servidor](#importancia-del-modelo-cliente-servidor)
   - [Ejemplos de Modelo Cliente-Servidor](#ejemplos-de-modelo-cliente-servidor)
7. [Conclusiones](#conclusiones)

## Idea de la aplicación:

La aplicación permitira a los usuarios personalizar su rutina de entrenamiento basada en sus datos físicos y objetivos personales. Al registrarse, los usuarios introducen **información** como edad, peso, altura, nivel de experiencia y **objetivos** (por ejemplo, pérdida de peso, ganancia muscular, mejora de resistencia).

A partir de estos datos, la aplicación genera un plan de entrenamiento adaptado que incluye ejercicios específicos, repeticiones, series y recomendaciones de descanso. Además, ofrece seguimiento del progreso y ajustes automáticos en la rutina conforme el usuario avanza. La interfaz es intuitiva y permite a los usuarios acceder fácilmente a su plan, así como recibir consejos nutricionales y motivación personalizada.

## Audiencia objetivo:

**1. Principiantes en el ejercicio**:

Reciben rutinas estructuradas adaptadas a su nivel, lo que les ayuda a evitar lesiones y a mantener la motivación.

**2. Atletas intermedios**:

Obtienen un plan optimizado para avanzar hacia objetivos específicos y desafiantes, mejorando su rendimiento general.

**3. Personas con objetivos específicos**:

Acceden a un enfoque centrado en metas como pérdida de peso, tonificación muscular o mejora de resistencia, facilitando un progreso efectivo.

**4. Personas con poco tiempo**:

Encuentran entrenamientos rápidos y eficientes que maximizan resultados en menos tiempo, adaptándose a su estilo de vida ajetreado.

**5. Personas con movilidad reducida**:

Disfrutan de rutinas adaptadas y ejercicios de rehabilitación que mejoran su movilidad y funcionalidad, así como motivación y seguimiento de progreso.

_"Esta diversidad de usuarios resalta la importancia de la personalización y la inclusión abarcando las cosas buenas de otras ya existentes y añadiendo lo que otras carecen en la aplicación, promoviendo un estilo de vida activo y saludable para todos."_

## Análisis de mercado:

Existen gran variedad de aplicaciones de este tipo en el mercado esta es una lista de las mas usadas y gratuitas. [Referencia](https://www.xataka.com/basics/14-apps-para-disenar-tu-rutina-semanal-rastrear-tus-ejercicios-casa-gimnasio).

| Aplicación                                            | Ventajas                                                       | Desventajas                                                                           |
| ----------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| [Aim Harder: WODs en casa](https://www.aimharder.com) | Gran variedad de videos explicando los ejercicios              | No sirve para entrenamientos en el gimnasio                                           |
| [FitNotes](https://www.fitnotesapp.com/)              | Te permite registrar tu entrenamiento y tus medidas corporales | Solo disponible para Android                                                          |
| [Seven](https://seven.app)                            | Es útil para las personas que no tienen mucho tiempo al día    | No está enfocada para personas que quieran llevar su entrenamiento al siguiente nivel |
| [Strong](https://strong.app)                          | Te ofrece un registro de tus récords personales y su historial | No está pensada para principiantes                                                    |
| [Virtuagym Fitness](https://virtuagym.com/es/)        | cuentas con más de 4.000 ejercicios explicados                 | Interfaz complicada para algunos usuarios                                             |

## Tecnologias empleadas:

| Tecnología                                                                                                                                          | Uso principal                                                          | Ventajas                                                                                                                                                           | Desventajas                                                                                                                                                    |
| --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![HTML y CSS](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSs8GyhMQ4phTYnEqiG8IMTGZSV1Sy7Eckse-QmBTEqXvZrX-ywDHanWqX-GMHDZPqjoDc&usqp=CAU) | Diseño de la estructura y el estilo de la aplicación                   | - Facilitan la creación de interfaces web accesibles. <br> - Amplio soporte en navegadores. <br> - CSS permite diseños visualmente atractivos.                     | - CSS puede volverse complejo en proyectos grandes. <br> - HTML por sí solo es estático, sin funcionalidad interactiva.                                        |
| ![JavaScript](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSV3o1lNT312vBu3muG2I9WNdynKMFadA5Bbg&s)                                         | Añadir eventos, dinamismo y animaciones                                | - Interactividad y dinamismo en tiempo real. <br> - Compatible con todos los navegadores. <br> - Amplia cantidad de librerías y frameworks (React, Angular, etc.). | - Puede generar vulnerabilidades de seguridad si no se usa correctamente. <br> - Su rendimiento puede verse afectado en dispositivos de bajos recursos.        |
| ![PHP](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTYKrhhZUQ_aVUKZgLAstA1x8OymxlyvIETdQ&s)                                                | Desarrollo de la lógica de la página web y recopilación de formularios | - Fácil integración con HTML. <br> - Excelente para desarrollo de backend en páginas dinámicas. <br> - Amplio soporte en servidores web y bases de datos.          | - Su rendimiento puede ser inferior a otras tecnologías más modernas. <br> - Código desordenado en aplicaciones grandes si no se sigue una arquitectura clara. |

### Compatibilidad con los navegadores:

Que una web sea compatible con todos los navegadores significa que se vea igual (o muy similar) en todos ellos.

Obviamente esto es bastante complicado, podremos estar satisfechos si conseguimos que se vea igual de bien en los más importantes, como **Chrome Explorer, Firefox, Opera, Safari y Mozilla**.

Validar el código de tu web en base a los [estándares del W3C](https://www.w3.org/WAI/standards-guidelines/es) es un buen hábito que conviene que cojas cuanto antes mejor.

Básicamente consiste en escanear tu web en busca de errores de programación para una vez detectados poder corregirlos.

## Modelos de ejecución:

### Importancia del modelo cliente servidor:

La arquitectura cliente servidor tiene dos partes claramente diferenciadas, por un lado la parte del servidor y por otro la parte de cliente o grupo de clientes donde lo habitual es que un servidor sea una máquina bastante potente con un hardware y software específico que actúa de depósito de datos y funcione como un sistema gestor de base de datos o aplicaciones.

## ¿Qué significa lado del cliente?

Hace referencia a todo lo que en una aplicación web se muestra o tiene lugar en el cliente (dispositivo del usuario final). Esto incluye lo que ve el usuario, como texto, imágenes y el resto de la interfaz de usuario, junto con cualquier acción que una aplicación lleve a cabo en el navegador del usuario.

Los lenguajes de marcado como **HTML** y **CSS** son interpretados por el navegador en el lado del cliente. Además, muchos desarrolladores actuales están incluyendo procesos del lado del cliente en la arquitectura de sus aplicaciones y dejando de hacer todo en el lado del servidor; la lógica de negocio para las páginas web dinámicas\*, por ejemplo, suele ejecutarse en el lado del cliente en una aplicación web moderna. Los procesos del lado del cliente se escriben casi siempre en JavaScript.

## ¿Qué significa lado del servidor?

Se refiere a todo lo que ocurre en el servidor, en lugar de en el cliente. En el pasado, casi toda la lógica empresarial se ejecutaba en el lado del servidor, y esto incluía la representación de páginas web dinámicas, la interacción con las bases de datos, la autenticación de identidades y las notificaciones push.

El problema que hay con alojar todos estos procesos en el lado del servidor es que cada solicitud que implique a uno de ellos tiene que recorrer todo el camino desde el cliente hasta el servidor, y eso cada vez. Esto produce una gran cantidad de latencia. Por esta razón, las aplicaciones actuales ejecutan más código en el lado del cliente; un caso de uso es la representación de páginas web dinámicas en tiempo real mediante la ejecución de scripts en el navegador, que hacen cambios en el contenido que ve el usuario.
[Referencia](https://www.cloudflare.com/es-es/learning/serverless/glossary/client-side-vs-server-side/)

![Esquema Cliente/Servidor](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQh88fRpMd38wW1quxDhAXo20wJgjAiIJTtaA&s)

### Ejemplos de modelo cliente-servidor:

- **Navegación web**: Funciona basándose en un cliente web (navegador) y un servidor web como Apache, Nginx o LiteSpeed.

- **Juegos en red**: Existen clientes que permiten a jugadores online jugar desde sus casas conectándose a servidores de juegos remotos.

- **Servidor de correo**: Los clientes de correo (en móvil o computadora de escritorio) consultan el correo al servidor de correo remoto.
  [Referencia](https://blog.infranetworking.com/modelo-cliente-servidor/)

## Conclusiones:

La idea es reunir en una sola aplicacion todas las ventajas de las principales del sector y evitar las desventajas tomando como rasgos diferenciadores la accesibilidad y la variedad adaptativa para cualquier tipo de publico y circunstancias.
Para ello pienso usar los lenguajes y tecnologias anteriormente nombrados que espero aprender a manejar durante este curso.
