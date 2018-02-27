---
layout: post
title: Sonar Lint - Buenas prácticas
feature-img: "assets/img/pexels/computer.jpeg"
tags: [Coding, Javier Cazallas]
avatar: "assets/img/users/jcazallas.png"
---

## Our team takes it very seriosly the quality of the produced code and for that, a good method to perform a constant inspection of our code.

You have to bear in mind thtat almost 70% of our effort spent during the cycle life of our product is to maintain. And maintenance is significatively more simple and faster if it's performed over a good code.
<br>

Here is where Sonar Lint comes in:
<br>
>SonarLint is a tool that provides an information 
>to the user about the quality code

<br>
En muchas ocasiones, Sonar Lint puede dar falsos positivos ya que en ocasiones las reglas que comprueba no son aplicables al caso en cuestión. Por eso, es importante saber interpretar la información que devuelve.

A lot of the times, SonarLint can give us false positives due do sometimes the rules that check aren't applied in that case. For that reason it's important to know how to interpret the information that is returned.

<br>
To generate a code that acomplish our aceptance rules is imperative that this code doesn't contain any common faults:

* Variables should not be used: When variables are defined but aren't in use.
* Control structures should use curly braces: When the braces aren't added to the control structure.

* Names should comply with a naming convention: Constant names must be in uppercase, class names must start in capital letters and variable names must follow the camelcase style.

* Cognitive Complexity should not be too high: Functions and methods musn't reach a number of lines. The "SPAGUETTI CODE" is a sign that it has to be refactorized. 

* Functions should not contain too many return statements

* Local variables should not be declared and then immediately returned or thrown.

* Code style generated must follow PSR-2 standard.

<br>

Interesting links:
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
