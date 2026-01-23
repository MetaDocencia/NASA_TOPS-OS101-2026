# Lección 2: Usar Código Abierto

## Contenidos

- [Descubrir Código y Software Abiertos](#descubrir-c%C3%B3digo-y-software-abiertos)
- [Evaluar Código y Software Abiertos](#evaluar-c%C3%B3digo-y-software-abiertos)
- [Reusar Código Abierto](#reusar-c%C3%B3digo-abierto)
- [Citar y reconocer el uso de Código Abierto](#citar-y-reconocer-el-uso-de-c%C3%B3digo-abierto)
- [Lección 2: Resumen](#lecci%C3%B3n-2-resumen)
- [Lección 2: Evaluación](#lecci%C3%B3n-2-evaluaci%C3%B3n)

## Descripción general

En la lección anterior, aprendiste los principios centrales del Código Abierto y cómo puede acelerar el proceso científico. Aquí descubrirás cómo usar código abierto existente en tu propio trabajo. Esta lección explora dónde buscar Código Abierto y cómo evaluarlo según cualidades deseadas. Ten en cuenta la funcionalidad, la usabilidad y la seguridad del Código Abierto que encuentres. Luego, aprenderás cómo reutilizar Software Abierto y emplear su versión compatible más reciente, así como cómo probar el software. Finalmente, profundizarás en las buenas prácticas para citar y reconocer el uso de código abierto.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Describir el proceso de uso de Código Abierto y enumerar algunos elementos clave para encontrar código.
- Describir las cuatro consideraciones clave al evaluar el Software Abierto: funcionalidad, interoperabilidad, seguridad y licencias.
- Enumerar algunos problemas comunes que surgen al reusar Código Abierto y las mejores prácticas para resolverlos.
- Describir cómo, dónde y bajo qué circunstancias se debe reconocer (citar) el código.

## Descubrir Código y Software Abiertos

Mucha gente descubre el código a través de conversaciones con sus colegas o leyendo artículos de revistas y asistiendo a charlas en conferencias. Esta es una excelente forma de encontrar código que puede resultar útil para tu problema científico.

¿Cuáles son otras formas de buscar código abierto? Como primer paso, busca código que ya exista, porque es muy probable que alguien haya tenido un problema similar y haya publicado su código en línea. Una forma común de buscar código existente es usar un motor de búsqueda general. Los motores de búsqueda ofrecen indicadores de relevancia del código, de cuán recientemente fue actualizado y de cuán frecuentemente otras personas lo citan.

|  |  |
|---|---|
| Ejemplo | Soy estudiante de posgrado y recién comienzo a trabajar en el modelado de turbulencias en el Océano Austral para comprender mejor la temperatura de la superficie del mar (o la absorción de calor del océano) y el cambio climático. ¿Existe algún software disponible para modelar cómo los remolinos en el océano afectan la temperatura de la superficie del mar? |
| Ejercicio | Búsqueda general sobre el término "Software para modelado de turbulencias oceánicas" |
| Resultado | Modelo General de Turbulencia Oceánica (en inglés, General Ocean Turbulence Model GOTM) |

El éxito de esta búsqueda se debe a que quienes desarrollaron el modelo GOTM hicieron público su código.

### El acceso al Software Abierto depende de que quienes lo desarrollan sigan los principios FAIR

Descubrir Software Abierto depende de que las personas que lo desarrollen hagan que su software sea fácil de encontrar. Los principios Fácil de encontrar, Accesible, Interoperable y Reutilizable (FAIR) para software de investigación, sugieren:

- El software y sus metadatos asociados deben ser fáciles de encontrar para humanos y máquinas.
- El software debe ser descrito con metadatos enriquecidos, accesibles e indexables.
- El software debe poder encontrarse desde todos los puntos de búsqueda relevantes.

(Wilkinson et al., 2016)

Sin embargo, puedes tener necesidades más específicas. En las siguientes secciones se describen otras formas de descubrir software que satisfaga las necesidades específicas de la investigación.

### Cómo buscar Código Abierto

Una búsqueda exitosa de Código Abierto exige un propósito claramente definido. Las personas que desarrollan código primero deben determinar las tareas que esperan que este código realice. Los requisitos asociados a estas tareas pueden determinar el lenguaje de programación más adecuado.

A continuación, familiarízate con la terminología de otras personas que crearon Software Abierto con requisitos similares a los tuyos. Las palabras clave relacionadas con su propósito o con los requisitos de programación pueden servir como punto de partida para buscar código relevante. Estas palabras clave pueden encontrarse en foros de las comunidades sobre programación de Código Abierto y en artículos de revistas científicas relacionadas. Con la adopción de principios de Acceso Abierto por parte de muchas revistas académicas, quienes se ocuparán de programar pueden examinar artículos científicos de campos relacionados con su investigación para encontrar, y en ocasiones usar, el código existente que cumpla con sus requisitos.

### Conoce dónde buscar

El ecosistema de Código Abierto es vasto, orgánico, multifacético y altamente distribuido.

Si buscas software científico, los estándares comunitarios exigen cada vez más que el código se publique y se vincule a artículos científicos.

<img src="../images/media/image333_es.jpg" style="width:350px;height:auto;" />
Crédito de la imagen: NASA

Por lo tanto, la literatura científica y sus archivos de códigos auxiliares son, cada vez más, un excelente lugar para buscar Código Abierto científico.

La mayor parte del Código Abierto no está desarrollado por o para científicos. Sin embargo, el Código Abierto permite investigar todos los días.

### Dónde buscar depende de tu necesidad

Hay varios buscadores populares para buscar fragmentos de código. Primero, simplemente puedes buscar en Google. Otros motores de búsqueda comúnmente usados son GitHub Code Search y Stack Overflow. Estos motores de búsqueda te permiten buscar por fragmentos de código específicos, por lenguaje de programación, por palabra clave u otros criterios. GitHub Code Search desarrolla la búsqueda en GitHub, un popular repositorio de códigos para software científico. En tanto, Stack Overflow permite buscar en foros donde las personas discuten soluciones a problemas de programación.

#### Ejemplos de repositorios de código:

<table>
<colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
</colgroup>
<tbody>
    <tr>
        <td><img style="width:98%" src="../images/media/examplecoderepo1_es.png" alt="Logo GitHub" /></td>
        <td><img style="width:98%" src="../images/media/examplecoderepo2_es.png" alt="Logo GitLab" /></td>
        <td><img style="width:98%" src="../images/media/examplecoderepo3_es.png" alt="Logo Bitbucket" /></td>
    </tr>
    <tr>
        <td>GitHub</td>
        <td>GitLab</td>
        <td>Bitbucket</td>
    </tr>
</tbody>
</table>

**Créditos de logos:**

**GitHub** (GITHUB®, el diseño del logo GITHUB® y el logo INVERTOCAT son marcas registradas de GitHub, Inc.).  
**GitLab** (GITLAB y el logo GITLAB son marcas registradas de GitLab Inc.).  
**Bitbucket** (BITBUCKET y el logo BITBUCKET son marcas registradas de Atlassian Pty Ltd.).

**Ejemplo: búsqueda de código en GitHub**

En este ejemplo, practicaremos la búsqueda de código de Acceso Abierto en GitHub. Analicemos un escenario en el que te gustaría aplicar el método de Lomb-Scargle para estimar un espectro de potencia.

**Contexto del ejemplo**

GitHub permite a las personas usuarias colaborar en un proyecto compartido y seguir los cambios con el control de versiones. Las personas pueden crear un repositorio y otorgar acceso a otras personas o darle Acceso Abierto. GitHub cuenta con una gran comunidad de personas que ponen su código disponible de forma abierta.

**Instrucciones del ejemplo**

Comienza visitando el sitio web de GitHub para buscar paquetes de software disponibles abiertamente. Deberás crear una cuenta gratuita para realizar esta acción. Puedes ingresar tus términos de forma sencilla en la barra de búsqueda mientras estás en tu página de perfil. En la barra de búsqueda, ingresa las palabras clave relacionadas. Busca "Lomb Scargle" y aparecerán varios repositorios con código relevante en Python, Julia, R, entre otros, junto con miles de partes de código relacionadas. ¡Felicitaciones! Has comenzado tu viaje hacia el software de Acceso Abierto y ahora puedes ver el trabajo de miles de personas que alguna vez estuvieron donde tú estás. ¡Adelante!

<img src="../images/media/image335_es.png" style="width:100%;height:auto;" alt="Captura de pantalla de la página de resultados de búsqueda en GitHub. En la barra de búsqueda aparece el texto “Lomb Scargle”. A la izquierda se ve la sección “Filter by” con filtros como “Code”, “Repositories” (seleccionado, con “78”), “Issues”, “Pull requests”, “Discussions” y “Users”, y debajo el listado de “Languages” (Python, Jupyter Notebook, R, Julia, C++, Cuda, Java). En el panel central se lee “78 results (231 ms)”, con opciones “Sort by: Best match” y el botón “Save”. En los resultados se muestran repositorios como “jakevdp/PracticalLombScargle”, “JuliaAstro/LombScargle.jl” y “mzechmeister/GLS”, cada uno con su descripción, lenguaje y fecha de actualización, junto al botón “Star”." />
Fuente: GitHub. https://github.com/ (enlace externo)

<img src="../images/media/image496_es.jpg" style="width:100%;height:auto;" alt="Captura de pantalla de la página de resultados de búsqueda en GitHub. En la barra de búsqueda aparece el texto “Lomb Scargle”. A la izquierda se ve la sección “Filter by” con filtros como “Code” (seleccionado, con “6.3k”), “Repositories”, “Issues”, “Pull requests”, “Discussions” y “Users”, y debajo el listado de “Languages” (Python, Jupyter Notebook, R, Julia, C++, Cuda, Java). En el panel central se lee “6.3k results (215 ms)”, con muestras de fragmentos de códigos en los que figura “Lomb Scargle”." />
Fuente: GitHub. https://github.com/ (enlace externo)

---

Con el Software Abierto, saber dónde buscar y qué buscar puede resultar desafiante. Siempre puedes comenzar con una búsqueda en Google. Sin embargo, puede ser valioso reflexionar sobre algunas de las preguntas que guían el proceso de búsqueda. Si la persona usuaria carece de experiencia relevante, también puede resultar útil involucrar a colegas experimentados en esta etapa.

Revisa el diagrama de flujo a continuación, que ilustra cómo una búsqueda sigue la definición de la necesidad:

  <img
    src="../images/media/image128_es.jpg"
    alt="Diagrama de flujo para orientar la búsqueda de Software Abierto. En la parte superior: “Definir los requerimientos: tareas, interoperabilidad, aplicaciones integrales vs. específicas, etc.” conectado con una doble flecha a: “Discutir con colegas o integrantes de la comunidad con mayor experiencia” y “Leer antecedentes relevantes”. Desde allí se bifurca en tres ramas: (1) “¿Es específico de una disciplina o investigación” → “Literatura revisada por pares” y “Repositorios de software propios de la disciplina”. (2) “¿Es de Código Abierto?” → “¿Es de un lenguaje específico?” → “Sí, por ejemplo, PyPI para Python, CRAN para R, etc.” / “No, por ejemplo: GitHub”. (3) “¿Tiene requisitos de hardware, sistema operativo u otras dependencias de entorno?” → “Sí, por ejemplo: Debian/dpkg, apt para linux, etc.” / “No, por ejemplo: SourceForge”."
    style="width:100%;height:auto;"
  />
Crédito de la imagen: NASA

### El Software Abierto se agrega y se puede buscar en repositorios

Un repositorio de software es una colección en línea de paquetes de software independientes. Los repositorios normalmente controlan el acceso y rastrean las implementaciones/descargas de paquetes.

Los paquetes de software suelen proporcionarse como ejecutables sin código.

La colección normalmente incluye metadatos, documentación y restricciones de licencia para cada paquete. Puede incluir diferentes versiones de paquetes de software y las plataformas o entornos en los que pueden ejecutarse.

La mayoría de los códigos de investigación deberían ser software de Código Abierto, el cual se almacena en repositorios de código.    

#### Ejemplos de repositorios de software incluyen:

<table>
<colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
</colgroup>
<tbody>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo1_es.png" alt="Logo Software Heritage" /></td>
        <td><img style="width:98%" src="../images/media/softwarerepo2_es.png" alt="Logo Open Source Development Network" /></td>
    </tr>
    <tr>
        <td>Software Heritage</td>
        <td>Open Source Development Network (OSDN)</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo3_es.png" alt="Logo SourceForge" /></td>
        <td><img style="width:98%" src="../images/media/softwarerepo4_es.png" alt="Logo FOSSHUB" /></td>
    </tr>
    <tr>
        <td>SourceForge</td>
        <td>Free and Open Source Software Hub (FOSSHUB)</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo5_es.png" alt="Logo Google Open Source" /></td>
        <td><img style="width:98%" src="../images/media/softwarerepo6_es.png" alt="Logo CPAN" /></td>
    </tr>
    <tr>
        <td>Googlecode</td>
        <td>Comprehensive Perl Archive Network</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo7_es.png" alt="Logo python Package Index"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo8_es.jpg" alt="Logo R"></td>
    </tr>
    <tr>
        <td>PyPI</td>
        <td>CRAN</td>
    </tr>
</tbody>
</table>

**Créditos de logos:**  

**Software Heritage** – *Software Heritage* y el logotipo de *Software Heritage* son marcas registradas de Inria.  
**Open Source Development Network (OSDN)** – *OSDN* y su logotipo son marcas comerciales de Appirits Inc.
**SourceForge** – *SourceForge* y el logotipo de *SourceForge* son marcas comerciales o marcas registradas de Slashdot Media en los Estados Unidos y en otros países (las “Marcas de Slashdot Media”).  
**Free and Open-Source Software Hub (FOSSHUB)** – *Fosshub®* y el logotipo de *FossHub®* son marcas registradas de FossHub.  
**Google Open Source** – *Google Open Source* y el logotipo de *Google Open Source* son marcas comerciales de Google LLC, y este currículo no está respaldado ni afiliado a Google de ninguna manera.  
**Comprehensive Perl Archive Network** – El logotipo de *CPAN* fue creado por J. C. Thorpe y se distribuye bajo la Licencia Artistic o GPLv1+.  
**PyPl** – *PyPI*, *Python Package Index* y los logotipos de bloques son marcas comerciales o marcas registradas de la [Python Software Foundation](https://www.python.org/psf-landing/) (enlace externo), en referencia a los productos y servicios asociados con [pypi.org](https://www.python.org/psf-landing/) (enlace externo).  
**CRAN** – El logotipo de *R* es © 2016 de [The R Foundation](https://www.r-project.org/logo/) (enlace externo), bajo los términos de la licencia [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/) (enlace externo) (CC-BY-SA 4.0).


**Recursos de la NASA para encontrar Software Abierto**

Estos son algunos enlaces a repositorios específicos de la NASA que pueden ser de tu interés:

- https://code.nasa.gov/  
- https://api.nasa.gov/  
- https://sciencediscoveryengine.nasa.gov/app/nasa-sba-smd/  
- https://ui.adsabs.harvard.edu/ (enlace externo)  
- https://www.earthdata.nasa.gov/engage/open-data-services-and-software/api  
- https://emac.gsfc.nasa.gov/  

## Evaluar Código y Software Abiertos

Así que has descubierto un Código Abierto emocionante que puede ayudarte a resolver tu problema científico. ¿Puedes confiar en este código que descubriste en la red? ¿Será útil? ¿Cuánto tiempo llevará aprenderlo? ¿Podría el código contener un programa maligno? ¿Podrías tener problemas legales por usarlo?

**Ejemplo:** Has encontrado el Modelo General de Turbulencia Oceánica (en inglés,General Ocean Turbulence Model GOTM) en Internet y parece prometedor. O bien, acabas de encontrar muchos fragmentos de código y funciones relacionados con el espectro de potencia de Lomb-Scargle. Ahora te gustaría evaluar estas piezas de código para decidir si debes usarlas.

### Cuatro consideraciones generales para evaluar el Software Abierto

- **Funcionalidad:** ¿será útil para tu problema científico?
- **Interoperabilidad:** ¿qué tan difícil será usarlo?
- **Seguridad:** ¿es seguro? ¿su uso genera riesgos de seguridad?
- **Licencias y restricciones:** ¿está permitido su uso? ¿es legal usarlo en tu proyecto?

### Funcionalidad: Evaluación de la utilidad científica

**¿El software satisface tus necesidades científicas?**

- ¿Aborda tu pregunta científica específica?
- ¿Estudios similares al tuyo los usan?
- ¿Qué artículos lo citan y cómo lo usan?
- ¿Las personas que te asesoran o tus colegas tienen experiencia con él?

**Probar la compatibilidad científica**

- ¿El software contiene casos de prueba científicos? Si es así, reproduce un caso que sea aplicable a tu problema; asegúrate de que los resultados son los esperados.
- Si realizaste análisis científicos o demolados similares anteriormente, reproduce tus resultados previos con el nuevo software. ¿Son consistentes?
- Modifica gradualmente un caso de prueba dado para abordar nuevas preguntas científicas. Alternativamente, desarrolla tu propio caso, si es necesario, siguiendo ejemplos relevantes.

### Interoperabilidad: facilidad de uso

**¿El código está escrito en un lenguaje que conoces?**

Puede ser más fácil usar lenguajes de programación con los que estás familiarizado e importar el código en un software existente, en lugar de intentar usar un nuevo lenguaje. Por otro lado, el uso de paquetes y ejecutables existentes puede acelerar tu trabajo.

**Revisar la documentación**

Lee el archivo README (o LEEME). ¿Cumple el software con tus requerimientos funcionales? ¿Están bien definidas y razonables las dependencias del entorno o del ambiente de desarrollo?

**Comprueba la evidencia de interoperabilidad con otros proyectos y códigos**

Es una buena señal si puedes encontrar evidencia de que el código ha sido utilizado con éxito por otras personas que tienen necesidades científicas o técnicas similares.

### Factores para evaluar la calidad del software de Código Abierto

Para evaluar rápidamente el uso y la calidad del repositorio de software por parte de la comunidad, utiliza las herramientas del repositorio donde lo encontraste. GitHub, por ejemplo, permite un rápido escaneo de la actividad de desarrollo como lo demuestra el número de veces que el código ha sido descargado o “bifurcado” (en la jerga de GitHub). También puedes ver la cantidad de actividad de una comunidad. GitHub, además, proporciona información sobre la calidad del software.

<img src="../images/media/image291_es.jpg" style="width:100%;height:auto;" alt="Captura de pantalla de un repositorio en GitHub (astropy/astropy). Se resaltan indicadores usados para evaluar actividad y adopción del proyecto: pestaña “Pull requests” con 59, cantidad de “Fork” (1.6k), cantidad de “Star” (3.9k) y la sección “Releases” con 22. También se ve el listado de carpetas/archivos del repositorio y un panel lateral con información del proyecto." />
Búsqueda modificada en GitHub [captura de pantalla]. (2023). GitHub. https://github.com/astropy/astropy (enlace externo)

### La importancia del archivo README (LEEME)

- Es siempre el punto de partida cuando se evalúa un software.
- Explica qué hace el software, cómo instalarlo y usarlo, o apunta a archivos con esa información.
- Asume conocimientos previos limitados de la personas lectora o potencial usuaria.
- Incluye una descripción de la compatibilidad, por ejemplo, las dependencias.
- Incluye ejemplos de uso y/o casos de prueba.

### Seguridad: Consideraciones a tener en cuenta cuando se utiliza Código Abierto

Has encontrado un Código Abierto que te ayudará a resolver tu problema científico y parece fácil de usar. Sin embargo, es posible que todavía tenga algunas reservas. Por ejemplo, tal vez no estés seguro de si el código representa un riesgo para la seguridad.

Los riesgos son relativamente bajos para pequeños fragmentos de código que resultan fáciles de entender para ti. Sin embargo, es posible que no puedas entender completamente todos los componentes de un paquete de Software Abierto de gran tamaño.

Se considera que el Software Abierto tiene más riesgos para la seguridad. Esto generalmente es un problema menor para el código fuente abierto que los ejecutables porque el código puede ser auditado en búsquedas de vulnerabilidades de seguridad por la comunidad. ¿Cómo se puede evaluar la seguridad en este caso?

- Consulta con el personal de tecnología de la institución y ten en cuenta las políticas sobre software abierto.
- Utiliza fuentes confiables para minimizar los riesgos de seguridad.
- Establece reglas y estándares de seguridad estrictos al usar una dependencia.
- Usa herramientas de seguridad para comprobar si hay vulnerabilidades (por ejemplo, [Open Worldwide Application Security</u> Project®️](https://owasp.org/), en inglés).
- Evita el software de Código Abierto sin soporte. Cambia por componentes desarrollados activamente o desarrolla tus propios componentes.
- Comprueba tus políticas institucionales más recientes sobre el uso de las herramientas de aprendizaje automático (_machine learning_) e inteligencia artificial.
- Ten cuidado al usar herramientas externas con datos de acceso seguros o con datos cerrados. Puede ser posible que la herramienta externa comparta públicamente lo que debería ser información restringida.

### Licencias

Entonces, si quieres reusar algún Código Abierto que hayas descubierto, es fundamental comprobar las restricciones legales y los requisitos impuestos a las personas usuarias, cuestiones que generalmente se establecen en la licencia.

Aunque el licenciamiento es un tema con matices sobre el que aprenderás más en la lección 3 de este módulo, es útil saber que, generalmente, hay dos clases de licencia: permisiva y no permisiva. Las licencias permisivas (como Apache 2., MIT o BSD) generalmente te permiten usar el código para tu investigación científica con poca restricción, mientras que las licencias no permisivas, como las licencias de copyleft, imponen restricciones sustanciales a la forma en que se utiliza el código y requieren una consideración más cuidadosa.

## Reusar Código Abierto

El software puede reusarse de varias maneras. Un paquete de software puede ejecutarse por sí mismo para proporcionar un análisis completo o modelos de acuerdo con los parámetros de entrada. Alternativamente, el paquete podría importarse como parte de una biblioteca más amplia para proporcionar una funcionalidad específica. Además, los fragmentos de código pueden copiarse en el código existente, si se permite, o el código podría reescribirse e incorporarse a un nuevo software.

Si simplemente tienes la intención de reusar un fragmento de código, prueba siempre que el código seleccionado funciona como se espera. Si estás reusando un código más complejo, existen consideraciones adicionales.

### Seleccionar la versión adecuada para reusar

Ten en cuenta lo siguiente cuando selecciones entre múltiples versiones de un software de Código Abierto.

|                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Usa la última versión estable cuando sea posible | Al igual que ocurre con las actualizaciones de software del sistema operativo o de las aplicaciones del teléfono o del ordenador, es importante usar la última versión estable. Quienes programan suelen publicar versiones del desarrollo que incluyen nuevas funciones o correcciones de errores que no se han probado por completo. Por este motivo, en general, no se recomienda el uso de versiones aún en desarrollo. |
| Determina el origen de la versión que deseas usar | Determina si la versión que quieres usar procede de un proyecto de Código Abierto modificado o de su fuente original. Con esta información determina qué fuente es más apropiada para tu proyecto.                                                                                                                                                                                                                                                                             |
| Comprueba problemas y errores (_bugs_)                     | Comprueba si la versión que has seleccionado presenta problemas o errores de programación conocidos. Encuentra información actualizada al respecto consultando las notas adjuntas de la versión, el sistema de seguimiento de incidentes y los foros de las comunidades de desarrollo.                                                                                                                                                                                    |

### Resolver problemas en la reutilización de software 

- Implementa pruebas para verificar que el software funciona como esperas en tu aplicación.
- Si tienes problemas, consulta las notas de la versión adjuntas, el sistema de seguimiento de incidentes y/o los foros de personas usuarias y desarrolladoras.
- No tengas miedo de pedir ayuda a tus colegas con experiencia.
- Es mejor buscar y obtener ayuda en un foro público que en un medio privado (por ejemplo, por correo electrónico). Parte del propósito de la Ciencia Abierta consiste en trabajar de forma abierta. Muchas veces, a través de una búsqueda, puedes descubrir que otras personas tienen preguntas similares. Puede que alguien ya haya ofrecido una solución. Si no es el caso, es probable que otros se beneficien de la respuesta pública a tu pregunta. 


### Actividad 2.1: Formas de obtener ayuda usando software abierto

Actividad 2.1: Maneras de obtener ayuda al usar Software Abierto

En esta actividad te pedimos que reconozcas las formas de resolver algunos problemas habituales que surgen al usar Software Abierto.

#### Ejercicio 1

Selecciona cómo podrías resolver este problema que se presenta al usar Software Abierto: Dificultad para encontrar Software Abierto que satisfaga tus necesidades.

Selecciona todas las opciones que correspondan.

- Contacta a colegas y personas expertas
- Lee bibliografía revisada por personas expertas
- Realiza una búsqueda en varios repositorios populares
- Lee el archivo README
- Lee la licencia del archivo

#### Ejercicio 2

Selecciona cómo podrías resolver este problema que se presenta al usar Software Abierto: Dificultades de instalación.

Selecciona todas las opciones que correspondan.

- Contacta con quienes desarrollaron el software en un foro público
- Lee bibliografía revisada por personas expertas
- Realiza una búsqueda en varios repositorios populares
- Lee el archivo README
- Lee la licencia del archivo

#### Ejercicio 3

Selecciona cómo podrías resolver este problema que se presenta al usar Software Abierto: el software no funciona como se esperaba.

Selecciona todo lo que corresponda.

- Contacta con quienes desarrollaron el software en un foro público
- Lee bibliografía revisada por personas expertas
- Realiza una búsqueda en varios repositorios populares
- Lee el archivo README
- Lee la licencia del archivo
- Consulta las notas sobre la versión, los sistemas de seguimiento de incidentes y los foros públicos

#### Ejercicio 4

Después de responder las preguntas anteriores, puedes pensar en otros problemas concretos y plantear cómo los resolverías por tu cuenta. Por ejemplo, navega hasta el repositorio de GitHub que contiene el código de Astropy u otro repositorio de tu elección y busca los archivos README y LICENSE (LICENCIA). Determina cómo te pondrías en contacto con quienes desarrollaron el software para solicitar ayuda, etc.

## Citar y reconocer el uso de Código Abierto

Imagina haber usado Código Abierto encontrado en la web y que esto significó ser de gran ayuda para el desarrollo de tu proyecto de investigación. ¿Cómo deberías darle crédito?

**Ejemplo:** Has conseguido aplicar un Modelo General de Turbulencia Oceánica (GOTM, por sus siglas en inglés) para aprender algo nuevo sobre la turbulencia oceánica en el Océano Antártico, o has calculado un periodograma de Lomb-Scargle utilizando Astropy. Aquí te dejamos algunas cuestiones a tener en cuenta:

### ¿Debes citar el Código Abierto?

Cita cualquier código que consideres que contribuyó a tu investigación:

- ¿El código desempeñó un papel fundamental en tu investigación?
- ¿El código aportó algo novedoso?

En la mayoría de los casos, un fragmento de código, por ejemplo, encontrado en Stack Overflow no constituye una contribución de investigación citable. Sin embargo, la persona autora puede decidir citarlo si lo desea.

Entre los casos en que el código compartido repercute directamente en los resultados científicos y requiere una descripción detallada figuran:

- Simulación o modelado numérico
- Análisis automatizados, como el tratamiento de imágenes o el reconocimiento óptico

Consulta la revista en la que publicas u otra sobre el tema y busca si contiene instrucciones específicas sobre cómo citar software (por ejemplo, [AAS Software Citation Suggestions](https://journals.aas.org/news/software-citation-suggestions/), en inglés).

En algunos casos, los términos y condiciones de la licencia de uso de un software exigen que este sea citado en las referencias o bibliografía de cualquier publicación derivada de una investigación que haya hecho uso del programa.

### ¿Cómo citar?

Lo ideal es usar y citar código que esté archivado en un repositorio con políticas de preservación a largo plazo y que cuente con un DOI. Sigue los lineamientos de las normas de citación que se proporcionan en el repositorio y que pueden aparecer en el archivo README (LEEME) o en CITATION (CITA).

Los DOI proporcionan un identificador o enlace persistente para los resultados de investigación. Por ello, es preferible citar los códigos depositados en repositorios a largo plazo con DOI. Las URL, por ejemplo, en Stack Overflow, y las de los repositorios activos, por ejemplo, en GitHub, son mutables: pueden cambiar con el tiempo y dejar de estar activas, aunque pueden usarse si no hay alternativa.

Los paquetes también pueden ofrecer una manera de citar versiones individuales. Para fines de reproducibilidad, cita tanto el paquete general como la versión que usaste en tu trabajo. Dado que la funcionalidad de un paquete puede evolucionar con el lanzamiento de nuevas versiones, esto puede ayudar a proporcionar el contexto específico en el que se realizó tu trabajo.

Si estás escribiendo un software, también puedes citar en los comentarios y en la documentación el software que hayas usado.

## Lección 2: Resumen

En esta lección aprendiste que:

- El Código Abierto existe dentro de un ecosistema vasto, orgánico y distribuido. Descubrir Código Abierto depende de definir bien tus necesidades, saber dónde buscar y que las personas que lo desarrollan hayan utilizado los principios FAIR.
- Los artículos científicos también son un buen lugar para descubrir Código Abierto, ya que ahora muchas revistas científicas exigen que el código utilizado en el artículo se encuentre disponible y esté vinculado mediante un DOI.
- Antes de usarlo, es importante evaluar el Software Abierto en términos de funcionalidad, calidad, interoperabilidad, seguridad y restricciones de licencia o reutilización. Tu primer paso debería ser buscar un archivo llamado README.
- Al reusar Software Abierto, utiliza la versión más reciente que cuente con soporte y pruébalo para asegurarte de que funciona como esperas. Si surgen problemas, contacta a las personas que lo desarrollaron o a la comunidad usuaria, idealmente a través de un foro público.
- Es importante citar y reconocer el Software Abierto que contribuye significativamente a tu trabajo, así como compartir tus experiencias de uso, tanto con quienes desarrollan software, como con la comunidad usuaria.

## Lección 2: Autoevaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

_Pregunta_

**01/03**

El éxito en descubrir Software Abierto depende de lo siguiente:

Selecciona todas las opciones que apliquen.

- Requisitos bien definidos
- Saber dónde buscar
- El Software Abierto que aplica principios FAIR existe para satisfacer tus necesidades
- Todas las anteriores

_Pregunta_

**02/03**

Lee la afirmación y decide si es verdadera o falsa:

_Es mejor contactar a quienes desarrollan software de acceso abierto por comunicación privada si encuentras problemas._

- Verdadero
- Falso

_Pregunta_

**03/03**

Cuando se cita Código Abierto, la mejor práctica es citar:

- El repositorio principal de trabajo, por ejemplo, en GitHub. Tiene la versión más reciente del código, incluyendo cualquier actualización desde que escribiste tu artículo.
- Un repositorio de código a largo plazo vinculado a un DOI, por ejemplo, en Zenodo. Este repositorio contiene una versión persistente, es decir, una copia específica y estable del código, la cual no cambiará con el tiempo, del código que utilizaste.

### Referencias citadas

- Wilkinson, M. et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship. *Scientific Data*, 3, 160018. https://doi.org/10.1038/sdata.2016.18 (enlace externo)
