---
layout: post
title: Sonar Lint - Buenas prácticas
feature-img: "assets/img/pexels/computer.jpeg"
tags: [Coding, Javier Cazallas]
avatar: "assets/img/users/jcazallas.png"
---

## Nuestro equipo se toma muy en serio la calidad del código que produce y para ello, un buen método es realizar una inspección continua y constante de nuestro código.
Hay que tener en cuenta que casi el 70% del esfuerzo invertido durante el tiempo de vida de un producto se destina a mantenimiento. Y el mantenimiento es significativamente más simple y rápido si se realiza sobre un buen código.
<br>

Aquí es donde entra Sonar Lint:
<br>
>SonarLint es una herramienta que proporciona
>información al usuario sobre la calidad del código

<br>
En muchas ocasiones, Sonar Lint puede dar falsos positivos ya que en ocasiones las reglas que comprueba no son aplicables al caso en cuestión. Por eso, es importante saber interpretar la información que devuelve.

<br>
Para generar un código que cumpla nuestras normas de aceptación es imperativo que no contenga ninguno de los fallos más comunes:

* Variables should not be used: Cuando se han definido variables pero no se están usando.
* Control structures should use curly braces: Cuando no se añaden llaves a las estructuras de control.
* Names should comply with a naming convention: Los nombres de las constantes deben ir en mayúsculas, los nombres de las clases deben de comenzar en mayúscula, los nombre de las variables deben seguir el estilo camelCase, ...
* Cognitive Complexity should not be too high: Las funciones/métodos no deben superar un número de líneas. El código espagueti es indicativo de que hay que refactorizar.
* Functions should not contain too many return statements
* Local variables should not be declared and then immediately returned or thrown
* El estilo del código generado debe seguir el estándar PSR-2

<br>

Enlaces de interés:
<br>

[Sonar Lint Official WebPage](https://www.sonarlint.org/)
<br>
[Sonar Lint Rules](https://www.sonarsource.com/sproducts/codeanalyzers/sonarphp/rules.html)
<br>
[PSR-2 Standar PHP](http://www.php-fig.org/psr/psr-2/)
<br>
<br>
<br>

<img class="avatar" src="{{ site.baseurl }}/{{ page.avatar }}" />
<br>
[Javier Cazallas](mailto:javier.cazallas@ticketea.com)
##### Developer at Travel by Ticketea
<br>
