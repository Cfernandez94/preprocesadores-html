#Preprocesadores de HTML

 ```
1.HAML
2.Jade
3.Slim
4.Twig
5.Handlebars```

##1.Haml

>HAML es un proyecto creado por Hampton Catlin, creador de Sass, la versión móvil de Wikipedia y Moovweb, una compañía de consultoría web. 

HAML está creado sobre Ruby, aunque actualmente posee varias implementaciones en diversos lenguajes, como Lua. Surge como una respuesta al estilo verboso de ERB, un generador de plantillas en HTML que empleaba una ḿecánica similar a la que usa HAML para generar contenido dinámico.

HAML **HTML abstraction markup language**.
Es un lenguaje basado en el principio de que un lenguaje de estructura debe ser hermoso. Sin embargo, no debe ser solo bello por si mismo, debe poder acelerar la creación de plantillas de estructura con una sintáxis bella y mantenible. HAML también enfatiza el principio de DRY **don’t repeat yourself** para definir documentos. 

>Solo por la cantidad de etiquetas de cierre ahorradas, un documento HAML pierde aproximadamente la mitad del tamaño y complejidad. HAML enfatiza la legibilidad del código, forzando a una correcta identación para definir la anidación de sus elementos.

**EJEMPLO** → 
```
1.(http://learn.shayhowe.com/advanced-html-css/preprocessors/)
```
##2.Jade

>Jade, por su parte, busca llevar el principio de DRY en HTML a otro nivel. 

Jade es un lenguaje inspirado por HAML e implementado con JavaScript sobre Node.js. 

Jade sigue principios de diseño similares a HAML: busca generar un documento con una estructura clara, sencilla y bella, enfatizando la legibilidad de su estructura y componentes. Sin embargo, Jade lleva la idea original de HAML un paso más lejos al presentar una forma completamente nueva de concebir la generación de documentos HTML: Jade permite fragmentar los documentos para que, empleando herencia por bloques, mixins (bloques de código con una estructura común pero contenido variable) e inferencia de propiedades, se creen documentos mucho más organizables, breves y mantenibles que lo que conseguirías con otros procesadores de HTML.

Jade simplifica la sintáxis de HAML, eliminando símbolos considerados innecesarios (como el símbolo de % antes de los elementos HTML), cambiando la sintáxis de los atributos de las etiquetas a algo más natural y menos verboso que HAML, e incorpora propiedades como extensión por bloques, inclusión de documentos, y el uso de mixins, o segmentos de código Jade con una estructura común pero con contenido o secciones distintas; para hacer de crear documentos HTML algo fácil de mantener, por más monolítica que sea la página final.

**EJEMPLO** → 
```
1.(http://jade-lang.com/)
```

##3.Slim

Slim es un lenguaje de plantillas , cuyo objetivo es reducir la sintaxis de las partes esenciales sin llegar a ser críptico .

>El diseño inicial de Slim es lo que se ve en la página principal . Comenzó como un ejercicio para ver cuánto podría ser eliminada de una plantilla estándar HTML ( < ,>, etiquetas de cierre , etc ... ).

Slim se esfuerzan por mantener la simplicidad, pero la definición de una sintaxis legible no siempre es la misma. La documentación le mostrará las opciones.

**Utiliza Templo y Tilt.**

**EJEMPLO** → 
```
1.(http://slim-lang.com/)
```
**MARKUP DE SLIM EN CSS3** →
```
1.(http://www.hongkiat.com/blog/keep-css3-markup-slim/)
```
##4.Twig

>Utiliza un objeto central llamado el medio ambiente (de clase Twig_Environment). Las instancias de esta clase se utilizan para almacenar la configuración y extensiones, y se utilizan para cargar plantillas desde el sistema de archivos o en otros lugares.

La mayoría de las aplicaciones van a crear un objeto Twig_Environment al iniciar la aplicación y al cargar plantillas.

##5.Handlebars

>Handlebars es un popular sistema de plantillas en Javascript que te permite crear y formatear código HTML de una manera muy sencilla. 

En lugar de hacer operaciones tediosas en librerías como jQuery para tocar el DOM insertando elementos de manera independiente con append o prepend, te permite crear bloques de código HTML, escritos directamente con HTML que poblarás con datos que te vengan de un JSON. Es tan sencillo como escribir HTML y tan potente que te permite realizar operaciones de recorrido de estructuras que encontramos en otros sistemas de plantillas en lenguajes como PHP.

Se trata de un complemento esencial para el desarrollo frontend y para la separación del frontend/backend, de modo que podamos hacer nuestros desarrollos dinámicos con uso intensivo de Javascript, generando el HTML desde este lenguaje con contenidos que probablemente vendrán de solicitudes Ajax, sin mayores complicaciones.

###Además de otros como:

Handlebars.js que es una extensión del lenguaje de plantillas Bigote creado por Chris Wanstrath. Handlebars.js y bigote son los dos idiomas de plantillas logicless que mantienen a la vista y el código separado como todos sabemos que deberían ser.

###Uso:

En general, la sintaxis de plantillas Handlebars.js es un superconjunto de las plantillas del bigote. Para conocer la sintaxis básica, echa un vistazo a la página de manual del bigote.

Una vez que tenga una plantilla, utilice el método Handlebars.compile para compilar la plantilla en una función. La función generada toma un argumento contexto, que se utiliza para representar la plantilla.

###Diferencias entre Handlebars.js y bigote
Handlebars.js añade un par de características adicionales para hacer plantillas de escritura más fácil y también cambia un pequeño detalle de cómo el trabajo parciales.

###Caminos
Handlebars.js soporta una sintaxis de expresión extendida que llamamos caminos. Caminos se componen de expresiones típicas y. personajes. Expresiones le permiten no sólo los datos de visualización en el contexto actual, pero para mostrar datos de contextos que son descendientes y ascendientes del contexto actual.

##Modo Escritura MarkDown
Markdown es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. 
>En principio, fue pensado para elaborar textos cuyo destino iba a ser la web con más rapidez y sencillez que si estuviésemos empleando directamenteHTML. Y si bien ese suele ser el mejor uso que podemos darle, también podemos emplearlo para cualquier tipo de texto, independientemente de cual vaya a ser su destino.

**Algunas Herramientas** → 
```
1.(http://markable.in/)
2.(http://dillinger.io/)
```

**Sintaxis de Ayuda para su Escritura** →
```
1.(http://markable.in/file/aa191728-9dc7-11e1-91c7-984be164924a/) 
2.(http://codehero.co/como-escribir-markdown-parte-i/)
```

**Ver más** → 
```
1.(http://www.genbeta.com/guia-de-inicio/que-es-markdown-para-que-sirve-y-como-usarlo)
```
