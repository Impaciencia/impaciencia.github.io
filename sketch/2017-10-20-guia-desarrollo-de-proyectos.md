# Guía de desarrollo de proyectos (How to do an awesome Impaciencia project)

Venga el primer paso es buscar a amigos e inscribíos en un equipo

Lo ideal es que en los equipos se junten estos perfiles:

- Estudiantes de humanidades o ciencias que planteen preguntas y formas de responderlas. Estas formas pueden ser por ejemplo un estudio o experimento.
- Estudiantes de ingenierías que puedan prestar apoyo técnico al análisis de los datos, la construcción de intrumental y a la comunicación.
- Estudiantes de comunicación que tomen los resultados y puedan comunicarlos a la sociedad de una forma original o quizás estudiantes de arte que tomen esos resultados como fuente de inspiración.

Pero oye, esto son solo perfiles ejemplo que la organización ha pensado. En la realidad queremos que nos sorprendáis, dejadnos como tontos y demostrad que la carrera que elijes no define lo que haces. Es en la mezcla dónde está el secreto de lo genuino.

## Ya tenemos un equipo y una idea, ¿Ahora qué?

Lo primero que tendréis que hacer es elegir un nombre chulo e incribiros en este formulario. Y ahora sí, a remangarse que vamos a ponernos manos a la obra.

Las investigaciones que búscamos en Impaciencia tienen que poder ser replicables, es decir, cualquier persona que repita exactamente lo mismo que vosotros (si es que puede) tiene que encontrar las mismas conclusiones o resultados. Esto es crucial si queremos que nuestros proyectos puedan ser utilizados por otras personas o que estas sean el punto de inicio de una exploración más profunda sobre el tema.

Es sorprendente pero estamos teniendo actualmente una crisis gordisisisisisisisma de reproducibilidad en investigación (ejem, ejem, ejem ejem) y hay muchos investigadores e iniciativas intentando  buscar una solución a esto. No nos gustaría que esto pasará a nuestros increibles proyectos después de dedicarle tanto esfuerzo. Por esto vamos a utilizar una metodología de documentación y trabajo en equipo basado en el control de versiones y repositorios que garantice la máxima reproducibilidad posible.

Ey Ey, oye colega a mi esto nunca me lo han enseñado en clase yo me piro de aquí. Espera, ya veras como es muy fácil y te resultará muy útil para cualquier tipo de proyecto que llevemos a cabo pero primero empecemos por la estructura ejemplo de un proyecto de investigación Impaciencia.

## La Estructura de los proyectos

Los proyectos Impaciencia se tienen que poder diseccionar en las siguientes partes:

- Parte teórica: Contiene el tema de investigación, la metodología utilizada, los datos en bruto, los resultados finales así como los análisis estadísticos necesarios.
- Parte técnica: Aquí encontraremos los instrumentos que hayamos tenido que usar o construir para poder realizar las mediciones así como los programas de análisis de datos utilizados. Todos los recursos tecnológicos que sean necesarios para poder reproducir la investigación tienen que estar definidos aquí.
- Parte comunicativa: Aquí encontraremos información de como vamos a comunicar nuestros resultados, ya sea el código de una web o el guión de un vídeo de youtube. Lo que sea que utilicéis para transmitir los resultados debería estar descrito aquí.

Definiendo bien la teórica y la técnica, cualquier persona con interés tiene que poder ser capaz de reproducir vuestros resultados. Es lógico, si se tiene acceso al diseño del estudio, a las herramientas utilizadas y a los análisis realizados se puede llevar a cabo nuevamente. No hay secretos, es un proceso transparente.

Esto es muy excítante porque nos servirá para muchas cosas además de documentar nuestra investigación. Por ejemplo, imaginad que a alguien se le ocurre que quiere poner a prueba vuestros resultados con otro tipo de análisis, o que quiere probar otra herramienta, o el mismo diseño pero en otras condiciones. Todo esto se podría hacer de forma rápida si las investigaciones estuvieran bien definidas en un forma común.

Vale, esto de forma abstracta y teórica suena muy bien pero ¿Cómo llevarlo a cabo en la práctica?

## El flujo de trabajo en una investigación

Cuando pensamos en una investigación lo más normal es que nos la imaginemos de forma lineal. Definimos muy bien nuestro diseño de estudio, lo que vamos a necesitar y que clase de resultados vamos a obtener. La realidad es mucho más compleja, sucia e interesante. A medida que vamos avanzando y leyendo nos podemos dar cuenta de que quizás el diseño incial no es correcto del todo o puede que los datos que obtenemos en nuestro primer experimento no son los que esperabamos. La verdad es que la investigación es tan interesante y adictiva porque precisamente no podemos predecir que vamos a obtener y por esto necesitamos un sistema que vaya adaptandose a estos cambios.

TODO: Foto de nombres de archivos finales finales.

Además a todo esto hay que sumarle que las investigaciones se realizan normalmente en grupo y la organización entre todos puede llegar a ser un caos. La investigación ya es lo suficientemente compleja para que encima la dificultemos aún más no utilizando una forma de trabajar en grupo eficiente. ¿Qué ocurre si las herramientas para facilitar esto ya están creadas y se extán usando con éxito en otros campos? ¿Qué pasa si encima decimos que las herramientas son gratuitas? ¿Sería interesante usarlas, verdad?

El desarrollo de software ya se encontró este mismo problema hace mucho tiempo y lo resolvió desarrollando un programa que controla todos los archivos de un proyecto. Este sistema vigila todos los cambios que cualquier usuario hace sobre cualquier archivo, ya sea un documento de texto, una tabla con datos o un script de programación. Además estos cambios pueden ser reversibles en cualquier momento por lo que la información no se pierde. Y por si esto fuera poco nos permite de una forma muy fácil copiar y modificar cualquier proyecto público. Esto se conoce como control de versiones y uno de los programas más famosos que hace esto es Git.

TODO: GIF de el diagrama de un repositorio

Debido a que Git se originó en el desarrollo de aplicaciones quizás un primer vistazo a la web solo te devuelva resultados relacionados con esto. Pero no te asustes, cada vez más se está utilizando Git con los archivos de investigación e incluso los proyectos pueden recibir un DOI para que sean publicados en revistas acádemicas. Esto último es muy interesante pues cada vez más revistas están valorando que tanto los datos como el código que ha llevado a unos resultados esté disponible de forma online.

También todos proyectos con sus archivos pueden estar sincronizados en una web facilitanto el trabajo en grupo de forma remota (de hecho seguramente sea gracias a esto que tu amigo informático puede trabajar en calzoncillos desde su casa cada día). E incluso algunas de estas webs, por ejemplo Github, aparte de controlar tus archivos ofrecen unas funcionalidades muy interesantes como, por ejemplo, la de publicar una web con tu proyecto, publicar un libro, hacer una wiki o visualizar los informes de los análisis de datos directamente en tu navegador (y todo esto gratis).

Quizás nos estamos pasando pero podemos decir que usar Git y páginas como Github se está convirtiendo en una pieza central en el desarrollo de cualquier proyecto digital, incluidas las investigaciones.

## Los repostorios en investigación

A los proyectos en Git, es decir a las carpetas con todos los archivos a controlar, se les llama repositorios y estos pueden contener carpetas y archivos (es decir basicamente todo). En una investigación no existe una forma estándar de organizarlos los repositorios y se pueden muchos asociados, tantos como sean necesarios. No obstante, para simplificar las cosas, en Impaciencia os proponemos que los proyectos presentados estén compuestos por los siguientes:

- Un repositorio teórico
- Uno o Varios repositirios técnicos
- Uno o varios repositorios comunicativos

Si no sabes como usar Git o Github lo mejor es que busques a algún miembro que sepa para el equipo aunque también puedes esperar un poco a que publiquemos nuestro tutorial, o también puedes aventurarte e intentar aprenderlo por ti mismo (te recomendamos esta página). Aquí continuaremos explicando como se pueden organizar los proyectos para presentarlos a Impaciencia, si no te queda claro aún que son los repositorios imaginate que son carpetas con archivos.

### El repositorio teórico

Intentad pensad en vuestra investigación de la siguiente forma. Por un lado tenemos todo la información que describe la investigación (el tema o hipótesis, los métodos, una descripción del diseño del estudio o experimento, etc), luego tendremos los datos que hemos ido recogiendo, los recursos digitales que hemos utilizado (sonidos, imágenes, etc ), la bibliografía utilizada y también podremos tener los análisis estadísticos que pueden haberse realizado con R. Si esto fuera un repositorio podría tener esta organización:

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
│   └── medicion_automática.ipnb
├── estadistica
│   ├── test_estadistico.R
│   └── informe_test.pdf
├── articulo
│   ├── articulo.tex
│   └── articulo_final.pdf
└── README.md (o README.txt)
```

El último archivo, llamado README.md, es algo común en todos los repositorios. Se utiliza para describir de que trata el mismo, quien lo ha hecho y en muchas ocasiones para enseñar a utilizar la información o el programa que contiene el repositorio.

Nosotros esperamos que ese README sea utilizado para describir la información que permita a cualquier otra persona repetir vuestro experimento. Es decir debería contener información sobre el tema o hipótesis, las variables, la muestra, la descripción de vuestro diseño de estudio, como ha sido realizado (esto se puede hacer en modo diario en otro archivo si os es más cómodo), los materiales utilizados, los programas usados y las conclusiones finales.

Este archivo puede estar escrito en .txt, aunque recomendamos usar markdown pues os permitirá meter imágnees, vídeos, tablas, ecuaciones, etc. Este tipo de archivos tienen una ventaja respecto a los .doc en que se pueden editar muy fácilmente y gratuitamente y además permiten que a partir de ellos se puedan hacer páginas webs, presentaciones muy facilmente. Pronto publicaremos un tutorial de como escribir en markdown, mientras puedes empezar a usarlo aquí (te avisamos, es muy útil para tomar apuntes en clase).

Si queréis también podéis escribir un artículo de tipo más clásico utilizando Latex, para esto recomendamos usar la web [Overleaf](http://www.overleaf.org)

### El (o los) repositorio técnico

Es muy probable que durante la investigación tengamos que utilizar algún tipo de instrumento o programa. Si alguien ya las ha hecho y publicado en github estos pueden ser descargadas y utilizados en vuestra investigación (aquí tenéis una lista con muchos recursos abiertos). Es incluso posible que las modifiquéis para adaptarlas a vuestro problema específico. Vuestra investigación puede hacer uso de tantos repositorios técnicos como os sean necesarios aquí, seguiremos pondremos el ejemplo de un repositorio de un instrumento y de otro de un programa.

Imaginad que nuestro experimento consiste en comprobar si las plantas crecen más con un tipo de música u otro. Para esto ponemos cultivamos un conjunto de plantas con dos canciones en bucle y realizamos mediciones sobre el tallo cada día. Podríamos hacerlo a mano, acudir cada día y medir todas las plantas a mano. Claro que sí, esto sería factible si fueran pocas y si le tuvieramos poco aprecio a nuestra vida social. Pero supongamos que nos gusta hacer otras cosas aparte de ir al laboratorio un domingo por la mañana, ¿se podría realizar esto automáticamente de alguna manera?. Y lo que es más importante, ¿se podría realizar sin tener que vender un riñon O.o?

Nuestro miembro del equipo que estudia ingeniería dice que sí, que con un aparato que tome fotos y con un programa que te análice la diferencia de las fotos es posible. Que se montan dos respositorios uno para cada parte y pim pam toma ya este finde a disfrutar.

#### Repositorio ejemplo de un instrumento de medición por cámara.

La idea es diseñar un aparato que tome fotografías de las plantas cada tiempo que nosotros queramos. Esto se puede hacer con una webcam, una raspberry Pi que esté conectada y una estructura que permita ponerla en la mejor posición para fotografíar a nuestras plantas.

El código puede ser un pequeño programa de linux (script de bash) que tome fotografías cada día y la estructura que coje la cámara se ha diseñado con un programa de edición 3D (almacenado en formato CAD) e impreso con una impresora 3D. Si ponemos todos estos archivos en un repositorio, cualquier persona podrá construir este mismo instrumento. Un ejemplo de como quedaría el repositorio podría ser:

```
Repositorio_Instrumento
├── estructura
│   ├── soporte_camara.CAD
│   └── carcasa_raspberryPI.CAD
├── código
│   └── capturar_fotografias.sh
└── README.md
```

En este caso el README.md contendría información sobre que hace este instrumento, como montarlo, que partes han sido necesarias, que modelo de Raspberry Pi y cámara s han utilizado, etc.

El utilizar un repositorio para almacenar este instrumento hace que si en un futuro alguien quiera mejorarlo y utilizar, por ejemplo, un sistema de control de la iluminación o de riego simplemente lo copiaría y le añadiría esa parte.

#### Repositorio ejemplo de análisis de las fotos.

Una vez que tenemos las fotos hay que sacar la medición, es decir, necesitamos obtener un número. Esto se puede realizar a mano pero también se podría automátizar con un pequeño programa en python que le aplique un filtro a la imagen y sea capaz de extraer de ahí cuanto a crecido esa planta. Nuevamente esto nos regala más tiempo que gastar haciendo cosas más interesantes, aumenta la reproducibilidad y es escalable. Esto último significa que al programa da lo mismo medir 10 que 10000 plantas, en cambio a nosotros si que suele importarnos un poquito.

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

En este README.md se espera que venga específicado como usar este programa de python, para que versión de python fue hecho, como utilizar el dataset de ejemplo y las dependencias que tenga.

Estos son solo dos ejemplos muy generales para que os hagáis una idea de como organizar las herramientas pero tened siempre en mente que cada investigación es un mundo y que esto condicionará el como organicéis vuestras herremientas. Sin embargo, no lo olvidéis tenéis que dejar las cosas lo suficientemente claras como para que cualquier otra persona las pueda utilizar ;)

### El repositorio de comunicación.

Finalmente nos queda una parte muy importante que hacer. Por muy increíbles que sean nuestros resultados si no son comunicados correctamente pasarán desapercibidos. Necesitamos realizar ese último esfuerzo e intentar que quede lo más claro posible lo que queremos comunicar. Aquí los estudiantes de comunicación tienen mucho que decir pues también se puede innovar en la forma de comunicar.

Actualmente es posible visualizar los datos de maneras que nos resulten más intuitivos (Aquí tenéis un ejemplo) o construir páginas webs que nos permitan interactuar con la información (como en las explicaciones explorables). Incluso un pequeño vídeojuego puede servir para divulgar la información. Estamos muy interesados en ver que nuevas formas de comunicar utilizáis.

También algo clásico como un artículo divulgativo o una práctica puede funcionar bien. Además es posible también que los resultados den lugar a algunas obras artisticas que podrían englobarse dentro del código creativo con lo que su ejecución quedaría contenida en un repositorio.

NOTA: Es posible que algunos formatos de comunicación no se adapten a un repositorio, por ejemplo: un vídeo subido a youtube o actividad de divulgación presencial o en redes sociales. En estos casos se podría crear un repositorio con un README.md que describa la estrategía de comunicación seguida y enlace al vídeo, al guión, etc. Ante la duda consulten con la organización.


## Conclusión

Sabemos que pedimos quizás muchas cosas que no nos han enseñado en la carrera pero es justamente por eso por lo que lo hacemos. La investigación está cambiando día a día y a veces las metodologías que nos enseñan en la carrera están desactualizadas y son poco eficientes. Este proyecto más que ser un concurso con un premio monetario está pensado para que aprendamos los unos de los otros a utilizar las herramientas que nos permitan conocer el mundo de una manera eficiente y segura.

Los proyectos Impaciencia no son solo para desarrolladores, ni solo para científicos, ni gente de humanidades, ni solo para comunicadores o artistas. Estos proyectos son para todos, el utilizar lo digital, es decir los repositorios, no lo dirige hacía una disciplina u otra. Tu mismo nos estás leyendo a través de un medio digital, de una pantalla ¿es que acaso lo que esté en libros es solo para gente de letras y lo que esté en un ordenador es solo para gente de ingenierías? Claramente no.

Dejemos de lado las restricciones que nos han impuesto (TODO:tachado) hemos impuesto y encontremos en la colaboración el medio principal para responder las preguntas que nos hacemos sobre el mundo.

¡A investigar señor@s!
