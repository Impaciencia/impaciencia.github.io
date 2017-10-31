---
title: ¿Cómo hacer un proyecto Impaciencia increíble?
date: 2017-10-27 18:00:53 Z
author: "impaciente-001"
categories:
- impaciencia
- tutorial
- investigación
thumbnail: /img/blog/rocket_launch.jpg
layout: post
---
Venga el primer paso es buscar a amigos e inscribíos en un equipo. Lo ideal es que en estos se junten estos perfiles:

{::nomarkdown}
<img src="{{ site.baseurl }}/img/equipos/sin.jpg">
<div class="piefoto"> Cuanto más diversos vuestros perfiles más original podrá ser vuestra investigación </div>
{:/nomarkdown}


- **Estudiantes de humanidades o ciencias** que planteen preguntas y formas de responderlas. Estas formas pueden ser por ejemplo un estudio o experimento.
- **Estudiantes de ingenierías** que puedan prestar apoyo técnico al análisis de los datos, la construcción de intrumental y a la comunicación.
- **Estudiantes de comunicación** que tomen los resultados y puedan comunicarlos a la sociedad de una forma original o quizás estudiantes de arte que tomen esos resultados como fuente de inspiración.

Pero oye, esto son solo perfiles ejemplo que la organización ha pensado. En la realidad queremos que nos sorprendáis, dejadnos como tontos y demostrad que la carrera que elijes no define lo que haces. **Es en la mezcla donde está el secreto de lo genuino**.

## Ya tenemos un equipo y una idea, ¿Ahora qué?

Lo primero que tendréis que hacer es elegir un nombre chulo e [incribiros en este formulario](https://docs.google.com/forms/d/e/1FAIpQLSdblWB1HK-2-p4KuRDd1DRa_NgdwSXpf2lREJjGGd-2gGNVkw/viewform?usp=send_form). Y ahora sí, a remangarse que vamos a ponernos manos a la obra.

Las investigaciones que buscamos en Impaciencia tienen que poder ser replicables, es decir, **cualquier persona que repita exactamente lo mismo que vosotros (si es que puede) tiene que encontrar las mismas conclusiones o resultados**. Esto es crucial si queremos que nuestros proyectos puedan ser utilizados por otras personas o que estas sean el punto de inicio de una exploración más profunda sobre el tema.

{::nomarkdown}
<img src="{{ site.baseurl }}/img/blog/phd010708s.gif">
<div class="piefoto"> El desorden en la investigación no se lleva muy bien con la reproducibilidad, oh, sorpresa :O </div>
{:/nomarkdown}


Es sorprendente pero estamos teniendo actualmente una crisis gordísisisisisisima de reproducibilidad en investigación ([ejem](https://www.nature.com/news/reproducibility-1.17552), [ejem](http://science.sciencemag.org/content/349/6251/aac4716), [ejem ejem](http://www.nature.com/nature/journal/v483/n7391/full/483531a.html)) y hay muchos investigadores e [iniciativas](https://osf.io/) intentando encontrar una solución a esto. No nos gustaría que esto pasará a nuestros increibles proyectos después de dedicarle tanto esfuerzo. Por esto vamos a utilizar una metodología de documentación y trabajo en equipo basado en el control de versiones y repositorios que garantice la máxima reproducibilidad posible.

Ayuda de rápideo:
> - **Control de Versiones**: Llevar la cuenta de todos los cambios que tienen vuestros archivos, desde documentos de texto hasta tablas de datos o scripts.
> - **Documentación**: Escribir que es lo que se ha hecho en una forma que cualquier persona pueda entender que es lo que se ha hecho.

Ey Ey, oye colega a mí esto nunca me lo han enseñado en clase, yo me piro de aquí. Espera, ya verás como es muy fácil y te resultará muy útil para cualquier tipo de proyecto que lleves a cabo, pero primero empecemos por la estructura ejemplo de un proyecto de investigación Impaciencia.

## La Estructura de los proyectos

Los proyectos Impaciencia se tienen que poder diseccionar en las siguientes partes:

- **Parte teórica**: contiene el tema de investigación, la metodología utilizada, los datos en bruto, los resultados finales así como los análisis estadísticos necesarios.
- **Parte técnica**: aquí encontraremos los instrumentos que hayamos tenido que usar o construir para poder realizar las mediciones así como los programas de análisis de datos utilizados. Todos los recursos tecnológicos que sean necesarios para poder reproducir la investigación tienen que estar definidos aquí.
- **Parte comunicativa**: aquí encontraremos información de cómo vamos a comunicar nuestros resultados, ya sea el código de una web o el guión de un vídeo de youtube. Lo que sea que utilicéis para transmitir los resultados debería estar descrito aquí.

Definiendo bien la teoría y la técnica, cualquier persona con interés tiene que poder ser capaz de reproducir vuestros resultados. Es lógico, si se tiene acceso al diseño del estudio, a las herramientas utilizadas y a los análisis realizados se podrá llevar a cabo nuevamente. No hay secretos, es un proceso transparente.

Esto es muy excitante porque nos servirá para muchas cosas, además de documentar nuestra investigación. Por ejemplo, imaginad que a alguien se le ocurre que quiere poner a prueba vuestros resultados con otro tipo de análisis, o que quiere probar otra herramienta, o el mismo diseño pero en otras condiciones. Todo esto se podría hacer de forma rápida si las investigaciones estuvieran bien definidas en un formato común.

Vale, esto de forma abstracta y teórica suena muy bien, pero ¿cómo llevarlo a cabo en la práctica?

## El flujo de trabajo en una investigación

Cuando pensamos en una investigación lo más normal es que nos la imaginemos de forma lineal. Definimos muy bien nuestro diseño de estudio, lo que vamos a necesitar y qué clase de resultados vamos a obtener. La realidad es mucho más compleja, sucia e interesante. **A medida que vamos avanzando y leyendo nos podemos dar cuenta de que quizás el diseño inicial no es correcto del todo o puede que los datos que obtenemos en nuestro primer experimento no son los que esperábamos**. La verdad es que la investigación es tan interesante y adictiva porque precisamente no podemos predecir qué vamos a obtener y por esto necesitamos un sistema que vaya adaptándose a estos cambios.

{::nomarkdown}
<img src="{{ site.baseurl }}/img/blog/archivos_caos.png">
<div class="piefoto"> ¡Qué pesadilla! Esto, desgraciadamente, nos ha pasado demasiadas veces a todos U.u </div>
{:/nomarkdown}

Además a todo esto hay que sumarle que las investigaciones se realizan normalmente en grupo y la organización entre todos puede llegar a ser un caos. **La investigación ya es lo suficientemente compleja para que encima la dificultemos aún más no utilizando una forma de trabajar en grupo eficiente**. ¿Qué ocurre si las herramientas para facilitar esto ya están creadas y se están usando con éxito en otros campos? ¿Qué pasa si encima decimos que las herramientas son gratuitas? ¿Sería interesante usarlas, verdad?

El desarrollo de software ya se encontró este mismo problema hace mucho tiempo y lo resolvió desarrollando un programa que controla todos los archivos de un proyecto. **Este sistema vigila todos los cambios que cualquier usuario hace sobre cualquier archivo, ya sea un documento de texto, una tabla con datos o un script de programación. Además estos cambios pueden ser reversibles en cualquier momento por lo que la información no se pierde**. Y por si esto fuera poco nos permite de una forma muy fácil copiar y modificar cualquier proyecto público. Esto se conoce como control de versiones y uno de los programas más famosos que hace esto es Git.

{::nomarkdown}
<img src="{{ site.baseurl }}/img/blog/gource_git_visualization.gif">
<div class="piefoto"> Visualización de las personas que modifican los archivos de un programa a través de git </div>
{:/nomarkdown}

Debido a que Git se originó en el desarrollo de aplicaciones, quizás un primer vistazo a la web solo te devuelva resultados relacionados con esto. Pero no te asustes, cada vez más se está utilizando Git con los archivos de investigación e incluso los proyectos pueden recibir un [DOI para que sean publicados en revistas acádemicas](https://zenodo.org/). Esto último es muy interesante pues cada vez más revistas están valorando que, tanto los datos como el código que ha llevado a unos resultados, esté disponible de forma online.

También **todos los proyectos con sus archivos pueden estar sincronizados en una web facilitando el trabajo en grupo de forma remota** (de hecho, seguramente sea gracias a esto que tu amigo informático puede trabajar en calzoncillos desde su casa cada día). E incluso algunas de estas webs, por ejemplo Github, aparte de controlar tus archivos ofrecen unas funcionalidades muy interesantes como; por ejemplo, la de publicar una web con tu proyecto, publicar un libro, hacer una wiki o visualizar los informes de los análisis de datos directamente en tu navegador (y todo esto gratis).

Quizás nos estamos pasando pero podemos decir que usar Git y páginas como Github se está convirtiendo en una pieza central en el desarrollo de cualquier proyecto digital, incluidas las investigaciones.

## ¿ Cómo usar los repostorios en una investigación Impaciencia?

A los proyectos en Git; es decir, a las carpetas con todos los archivos a controlar, se les llama repositorios y estos pueden contener carpetas y archivos (básicamente todo). En una investigación no existe una forma estándar de organizar los repositorios y se pueden muchos asociados, tantos como sean necesarios. No obstante, para simplificar las cosas, en Impaciencia os proponemos que los proyectos presentados estén compuestos por los siguientes:

- **Un repositorio teórico**
- **Uno o Varios repositorios técnicos**
- **Uno o varios repositorios comunicativos**

{::nomarkdown}
<img src="{{ site.baseurl }}/img/blog/guia_proyectos.png">
<div class="piefoto"> Un esquema de como se pueden utilizar distintos repositorios para organizar vuestra investigación </div>
{:/nomarkdown}

Si no sabes cómo usar Git o Github lo mejor es que busques a algún miembro que sepa para o también puedes aventurarte e intentar aprenderlo por ti mismo ([te recomendamos esta página](https://programminghistorian.org/es/lecciones/introduccion-control-versiones-github-desktop)). Aquí continuaremos explicando como se pueden organizar los proyectos para presentarlos a Impaciencia, si no te queda claro aún que son los repositorios imagínate que son carpetas con archivos.

### El repositorio teórico

Intentad pensad en vuestra investigación de la siguiente forma. Por un lado, tenemos toda la información que describe la investigación (el tema o hipótesis, los métodos, una descripción del diseño del estudio o experimento, etc.), luego tendremos los datos que hemos ido recogiendo, los recursos digitales que hemos utilizado (sonidos, imágenes, etc.), la bibliografía utilizada y también podremos tener los análisis estadísticos que pueden haberse realizado con R. Si esto fuera un repositorio podría tener esta organización:

```
Repositorio_teórico
├── datos
│   ├── mediciones_grupo1_condicionA.csv
│   ├── mediciones_grupo2_condicionA.csv
│   ├── mediciones_grupo1_condicionB.csv
│   └── mediciones_grupo2_condicionB.csv
├── recursos
│   ├── cancion_chulaA.mp3
│   └── cancion_chulaB.mp3
├── bibliografía
│   ├── artículos.bib
│   └── articulo_open.pdf
├── análisis
│   ├── Script_figura002.py
│   ├── figura002.jpg
│   └── medicion_automática.ipnb
├── estadistica
│   ├── test_estadistico.R
│   ├── Script_figura001.R
│   ├── figura001.jpg
│   └── informe_test.pdf
├── articulo
│   ├── articulo.tex
│   ├── figura001.jpg
│   ├── figura002.jpg
│   └── articulo_final.pdf
└── README.md (o README.txt)
```

El último archivo, llamado **README.md**, es algo común en todos los repositorios. Se utiliza para describir de qué trata el mismo, quien lo ha hecho y en muchas ocasiones para enseñar a utilizar la información o el programa que contiene el repositorio.

Nosotros esperamos que ese README sea utilizado para describir la información que permita a cualquier otra persona repetir vuestro experimento; es decir, **debería contener información sobre el tema o hipótesis, las variables, la muestra, la descripción de vuestro diseño de estudio, cómo ha sido realizado (esto se puede hacer en modo diario en otro archivo si os resulta más cómodo), los materiales utilizados, los programas usados y las conclusiones finales.**

Este archivo puede estar escrito en .txt, aunque recomendamos usar markdown pues os permitirá meter imágenes, vídeos, tablas, ecuaciones, etc. Este tipo de archivos tienen una ventaja respecto a los .doc y es que se pueden editar muy fácilmente y gratuitamente, además permiten hacer páginas webs y presentaciones de forma muy sencilla. Pronto publicaremos un tutorial de cómo escribir en markdown, mientras tanto puedes empezar a usarlo aquí (te avisamos, es muy útil para tomar apuntes en clase).

También podéis escribir un artículo de tipo más clásico utilizando Latex, para esto recomendamos usar la web [Overleaf](http://www.overleaf.org)

### El (o los) repositorio técnico

**Es muy probable que durante la investigación tengamos que utilizar algún tipo de instrumento o programa**. Si alguien ya las ha hecho y publicado en github estos pueden ser descargadas y utilizados en vuestra investigación (aquí tenéis una lista con muchos recursos abiertos). Es incluso posible que las modifiquéis para adaptarlas a vuestro problema específico. Vuestra investigación puede hacer uso de tantos repositorios técnicos como os sean necesarios,aquí pondremos el ejemplo de un repositorio de un instrumento y otro de un programa.

Imaginad que nuestro experimento consiste en comprobar si las plantas crecen más con un tipo de música u otro. Para esto ponemos a cultivar un conjunto de plantas con dos canciones en bucle y realizamos mediciones sobre el tallo cada día. Podríamos hacerlo a mano, acudir cada día y medir todas las plantas a mano. Claro que sí, esto sería factible si fueran pocas y si le tuvieramos poco aprecio a nuestra vida social. Pero supongamos que nos gusta hacer otras cosas aparte de ir al laboratorio un domingo por la mañana, **¿se podría realizar esto automáticamente de alguna manera?**. Y lo que es más importante, **¿se podría realizar sin tener que vender un riñón O.o?**

Nuestro miembro del equipo que estudia ingeniería dice que sí, que con un aparato que tome fotos y con un programa que te analice la diferencia de las fotos es posible. Que se montan dos repositorios, un para cada parte y PIM PAM!, ya puedes disfrutar de este finde.

#### Repositorio ejemplo de un instrumento de medición por cámara.

**La idea es diseñar un aparato que tome fotografías de las plantas cada tiempo que nosotros queramos**. Esto se puede hacer con una webcam, una raspberry Pi que esté conectada y una estructura que permita ponerla en la mejor posición para fotografiar a nuestras plantas.

{::nomarkdown}
<img src="{{ site.baseurl }}/img/blog/raspberryPi-camera.jpg">
<div class="piefoto"> Con una raspberry Pi y su cámara ya tendréis un dispositivo de captación chulo y barato </div>
{:/nomarkdown}

El código puede ser un pequeño programa de Linux (script de bash) que tome fotografías cada día y la estructura que coge la cámara se ha diseñado con un programa de edición 3D (almacenado en formato CAD) e impreso con una impresora 3D. Si ponemos todos estos archivos en un repositorio, cualquier persona podrá construir este mismo instrumento. Un ejemplo de cómo quedaría el repositorio podría ser:

```
Repositorio_Instrumento
├── estructura
│   ├── soporte_camara.CAD
│   └── carcasa_raspberryPI.CAD
├── código
│   └── capturar_fotografias.sh
└── README.md
```

En este caso el **README.md contendría información sobre qué hace este instrumento, cómo montarlo, qué partes han sido necesarias, qué modelo de Raspberry Pi y cámara se han utilizado, etc.**

El utilizar un repositorio para almacenar este instrumento hace que si en un futuro alguien quiera mejorarlo y utilizar, por ejemplo, un sistema de control de la iluminación o de riego simplemente lo copiaría y le añadiría esa parte.

#### Repositorio ejemplo de análisis de las fotos.

{::nomarkdown}
<img src="{{ site.baseurl }}/img/blog/phd031214s.gif">
<div class="piefoto"> Intentemos evitar justamente esto </div>
{:/nomarkdown}

Una vez que tenemos las fotos hay que sacar la medición; es decir, necesitamos obtener un número. **Esto se puede realizar a mano pero también se podría automatizar con un pequeño programa en Python que le aplique un filtro a la imagen y sea capaz de extraer de ahí cuánto ha crecido esa planta**. Nuevamente esto nos regala más tiempo que gastar haciendo cosas más interesantes, aumenta la reproducibilidad y es escalable. Esto último significa que al programa le da lo mismo medir 10 que 10000 plantas, en cambio a nosotros sí que suele importarnos un poquito.

Este repositorio puede tener la siguiente estructura:

```
Repositorio_Instrumento
├── dataset_ejemplo
│   ├── 100_fotos_de_plantas_sexy.zip
│   └── resultados_esperados.csv
├── código
│   ├── procesador_de_imagen.py
│   └── medidor_de_crecimiento.py
└── README.md
```

En este **README.md se espera que venga especificado cómo usar este programa de Python, para qué versión de Python fue hecho, como utilizar el dataset de ejemplo y las dependencias que tenga**.

Estos son solo dos ejemplos muy generales para que os hagáis una idea de cómo organizar las herramientas pero tened siempre en mente que cada investigación es un mundo y que esto condicionará el cómo organicéis vuestras herramientas. Sin embargo, no lo olvidéis tenéis que dejar las cosas lo suficientemente claras como para que cualquier otra persona las pueda utilizar ;)

### El repositorio de comunicación.

Finalmente nos queda una parte muy importante que hacer. Por muy increibles que sean nuestros resultados si no son comunicados correctamente pasarán desapercibidos. Necesitamos realizar ese último esfuerzo e intentar que quede lo más claro posible lo que queremos comunicar. Aquí los estudiantes de comunicación tienen mucho que decir pues también se puede innovar en la forma de comunicar.

[Ejemplo de visualización interactiva con los diálogos de los personajes de Los Miserables](https://codepen.io/nfnm/pen/VLRzpa?q=les%20miserables&order=popularity&depth=everything&show_forks=false)

Actualmente es posible visualizar o escuchar los datos de maneras que nos resulten más intuitivos o construir páginas webs que nos permitan interactuar con la información (como en las explicaciones explorables). Incluso un pequeño videojuego puede servir para divulgar la información. Estamos muy interesados en ver qué nuevas formas de comunicar utilizáis.

<iframe width="551" height="315" src="https://www.youtube.com/embed/ndLkP-bNL1s" frameborder="0" allowfullscreen></iframe>
<div class="piefoto"> Mediante la sonificación de datos podemos convertir valores numéricos en sonidos. ¿Esto será útil en tu investigación? </div>

También algo clásico como un artículo divulgativo o una práctica puede funcionar bien. Además es posible también que los resultados den lugar a algunas obras artísticas que podrían englobarse dentro del código creativo con lo que su ejecución quedaría contenida en un repositorio.

**NOTA**: Es posible que algunos formatos de comunicación no se adapten a un repositorio, por ejemplo: un vídeo subido a youtube o actividad de divulgación presencial o en redes sociales. En estos casos se podría crear un repositorio con un README.md que describa la estrategia de comunicación seguida y enlace al vídeo, al guión, etc. Ante la duda consultad con la organización.

## La organización de los repositorios

Estos repositorios deberán estar todos asociados a una *organizción github* que lleve el nombre de vuestro equipo. Aquí podréis haceros una: [Github Organization](https://github.com/organizations/new). Elejid el plan free, en principio. Debido a que sois estudiantes Github os concederá una cuenta premium totalmente gratuita. Entrad en este [formulario para que os concedan repositorios privados vinculados](https://education.github.com/discount_requests/new) a vuestra organización. Solicitad tantos como veáis necesarios.

{::nomarkdown}
<img src="{{ site.baseurl }}/img/blog/github-organization.png">
<div class="piefoto"> Un ejemplo de como quedará la página con vuestros repositorios en Github </div>
{:/nomarkdown}

Mantened los repositorios en privado hasta el día que nos presentéis la versión final de ellos.

Lo ideal sería que vuestra organización en github también tuviera una página web con el siguiente dominio: www.NOMBRE-DEL-EQUIPO.github.io. [Aquí podréis aprender como hacerlo](http://www.evaristogz.com/pagina-web-estatica-github-pages/).

## Conclusión

Sabemos que pedimos quizás muchas cosas que no nos han enseñado en la carrera pero es justamente por eso por lo que lo hacemos. La investigación está cambiando día a día y a veces las metodologías que nos enseñan en la carrera están desactualizadas y son poco eficientes. Este proyecto más que ser un concurso con un premio monetario está pensado para que aprendamos los unos de los otros a utilizar las herramientas que nos permitan conocer el mundo de una manera eficiente y segura.

**Los proyectos Impaciencia no son solo para desarrolladores, ni solo para científicos, ni gente de humanidades, ni solo para comunicadores o artistas. Estos proyectos son para todos, utilizar lo digital; es decir los repositorios, no lo dirige hacia una disciplina u otra**. Tú mismo nos estás leyendo a través de un medio digital ¿acaso lo que esté en libros es solo para gente de letras y lo que esté en un ordenador es solo para gente de ingenierías? Claramente no.

Dejemos de lado las restricciones que nos ~~han impuesto~~ hemos impuesto y encontremos en la colaboración el medio principal para responder las preguntas que nos hacemos sobre el mundo.

**¡A investigar señor@s!**

{::nomarkdown}
<img src="{{ site.baseurl }}/img/blog/madpersonlaughting.gif">
<div class="piefoto"> Muahahahhaha! </div>
{:/nomarkdown}

## Anexo: Referencias Interesantes

- [Preservar Datos de Investigación](https://programminghistorian.org/es/lecciones/preservar-datos-de-investigacion)
- [Introducción al control de versiones con Github Desktop](https://programminghistorian.org/es/lecciones/introduccion-control-versiones-github-desktop)
- [Ten Simple Rules for Taking Advantage of Git and GitHub](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004947)
- [We need a github for academic research](http://www.slate.com/articles/technology/future_tense/2017/04/we_need_a_github_for_academic_research.html)
- [A quick guide to organizing Computational Biology Projects, Aunque vale para cualquier disciplina :) ](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424)
- [A Reproducible Workflow por Ignasi Bartomeus y Francisco Rodríguez-Sánchez](https://www.youtube.com/watch?v=s3JldKoA0zw)
