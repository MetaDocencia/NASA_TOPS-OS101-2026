# Lección 2: Usar Código Abierto

## Contenidos

- [Descubrir Código y Software Abiertos](#descubrir-c%C3%B3digo-y-software-abiertos)
- [Evaluar Código y Software Abiertos](#evaluar-c%C3%B3digo-y-software-abiertos)
- [Reusar Código Abierto](#reusar-c%C3%B3digo-abierto)
- [Citar y reconocer el uso de Código Abierto](#citar-y-reconocer-el-uso-de-c%C3%B3digo-abierto)
- [Lección 2: Resumen](#lecci%C3%B3n-2-resumen)
- [Lección 2: Evaluación](#lecci%C3%B3n-2-evaluaci%C3%B3n)

## Descripción general

En la lección anterior, aprendiste los principios centrales del código abierto y cómo puede acelerar el proceso científico. Aquí descubrirás cómo usar código abierto existente en tu propio trabajo. Esta lección explora dónde buscar código abierto y cómo evaluarlo según cualidades deseadas. Ten en cuenta la funcionalidad, la usabilidad y la seguridad del código abierto que encuentres. Luego, aprenderás cómo reutilizar software abierto y emplear su versión compatible más reciente, así como cómo probar el software. Finalmente, profundizarás en las buenas prácticas para citar y reconocer el uso de código abierto.

## Objetivos de aprendizaje

Luego de completar esta lección, deberías poder:

- Describir el proceso para usar código abierto y enumerar algunos elementos clave para descubrir código.
- Describir las cuatro consideraciones clave al evaluar software abierto: funcionalidad, interoperabilidad, seguridad y licencias.
- Enumerar algunos problemas comunes que surgen al reutilizar código abierto y buenas prácticas para resolverlos.
- Describir cómo, dónde y en qué circunstancias se debe reconocer o citar código.

## Descubrir código y software abierto

Muchas personas descubren código a través de conversaciones con colegas, la lectura de artículos científicos o la asistencia a charlas en conferencias. Estas son excelentes maneras de encontrar código que puede tener aplicaciones para tu problema científico o pregunta de investigación.

¿Cuáles son otras formas de buscar código abierto? Como primer paso, busca código que ya exista, porque es muy probable que alguien ya haya tenido un problema similar y haya publicado su código en línea. Una forma común de buscar código existente es usar un motor de búsqueda general. Los motores de búsqueda ofrecen indicadores de relevancia del código, de cuán recientemente fue actualizado y de cuán frecuentemente otras personas lo referencian.

|  |  |
|---|---|
| Ejemplo | Soy una persona estudiante de posgrado que comienza a trabajar en el modelado de turbulencia en el Océano Austral para comprender mejor la temperatura de la superficie del mar (o la absorción de calor oceánico) y la dinámica oceánica. ¿Existe algún software disponible para modelar cómo los remolinos oceánicos afectan la temperatura de la superficie del mar? |
| Ejercicio | Búsqueda general del término “Software for ocean turbulence modeling” |
| Resultado | General Ocean Turbulence Model (GOTM) |

Esta búsqueda exitosa se basa en que las personas desarrolladoras de GOTM hicieron su código abierto.

### El descubrimiento de software abierto depende de que las personas desarrolladoras sigan los principios FAIR

La capacidad de descubrir software abierto depende de que las personas desarrolladoras hagan que su software sea fácil de encontrar. Los principios FAIR (Encontrable, Accesible, Interoperable y Reutilizable) para software de investigación sugieren que:

- El software y sus metadatos asociados deben ser fáciles de encontrar tanto para personas como para máquinas.
- El software debe describirse con metadatos ricos, buscables e indexables.
- El software debe poder encontrarse desde todos los puntos de búsqueda relevantes.

(Wilkinson et al., 2016)

Sin embargo, puedes tener necesidades más específicas. Las siguientes secciones cubren formas adicionales de ayudar a descubrir software relevante que satisfaga demandas de investigación particulares.

### Cómo buscar código abierto

Una búsqueda exitosa de código abierto requiere un propósito claramente definido. Las personas desarrolladoras deben determinar primero las tareas que esperan que su código realice. Los requisitos asociados a estas tareas pueden determinar el lenguaje de programación más adecuado.

Luego, si deseas encontrar código abierto con requisitos similares a los tuyos, es importante familiarizarte con la terminología que emplean otras personas. Las palabras clave asociadas a tu propósito o requisitos de programación pueden servir como punto de partida al buscar código relevante. Estas palabras clave pueden encontrarse en foros comunitarios sobre programación de código abierto y en artículos científicos relacionados. Con la adopción de principios de acceso abierto por muchas revistas académicas, quienes programan pueden revisar artículos científicos de campos relacionados con su investigación para encontrar, y a veces utilizar, código existente que satisfaga sus requisitos.

### Saber dónde buscar

El ecosistema de código abierto es vasto, orgánico, multifacético y altamente distribuido.

Si estás buscando código científico, los estándares comunitarios han exigido cada vez más que el código se publique y se vincule a artículos científicos.

<img src="../images/media/image333_es.jpg" style="width:350px;height:auto;" />
Crédito de la imagen: NASA

Por lo tanto, la literatura científica y sus archivos de código asociados son un excelente lugar para buscar código científico abierto.

La mayor parte del código abierto no es desarrollado por ni para personas científicas. Sin embargo, el código abierto habilita la investigación todos los días.

### Dónde buscar depende de lo que necesites

Existen varios motores de búsqueda populares para fragmentos de código. Primero, puedes simplemente buscar en Google. Otros motores de búsqueda comúnmente usados incluyen GitHub Code Search y Stack Overflow. Estos motores permiten buscar fragmentos de código específicos por lenguaje de programación, palabra clave u otros criterios. GitHub Code Search permite buscar dentro de GitHub, un repositorio popular de código científico. Stack Overflow permite buscar en foros donde las personas usuarias discuten soluciones a problemas de programación.

#### Ejemplos de repositorios de código:

<table>
<colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
</colgroup>
<tbody>
    <tr>
        <td><img style="width:98%" src="../images/media/examplecoderepo1_es.png"></td>
        <td><img style="width:98%" src="../images/media/examplecoderepo2_es.png"></td>
        <td><img style="width:98%" src="../images/media/examplecoderepo3_es.png"></td>
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

En este ejemplo, se practica la búsqueda de código de acceso abierto en GitHub. Se trabajará con un escenario en el que deseas buscar el método de Lomb y Scargle para estimar un espectro de potencia.

**Contexto del ejemplo**

GitHub permite a las personas usuarias colaborar en un proyecto compartido y rastrear cambios mediante control de versiones. Las personas pueden crear un repositorio y otorgar acceso a otras, o hacerlo de acceso abierto. GitHub cuenta con una gran comunidad de personas usuarias que ponen su código a disposición de forma gratuita.

**Instrucciones del ejemplo**

Comienza visitando el sitio web de GitHub para buscar paquetes de software disponibles abiertamente. Necesitarás crear una cuenta gratuita. Navega a la página de búsqueda de código para iniciar tu búsqueda. También puedes acceder a tutoriales sobre la interfaz y las capacidades del portal de búsqueda de GitHub. Alternativamente, puedes ingresar tus términos de búsqueda directamente en la barra de búsqueda desde tu perfil. Luego, introduce palabras clave relacionadas. Busca “Lomb Scargle” y encuentra varios repositorios con código relevante en distintos lenguajes, junto con miles de fragmentos relacionados. Felicitaciones: has comenzado tu recorrido por el código de acceso abierto y ahora puedes ver el trabajo de miles de personas que alguna vez estuvieron en tu lugar.

<img src="../images/media/image335_es.jpg" style="width:100%;height:auto;" />
Búsqueda en GitHub [captura de pantalla]. (2023). GitHub. https://github.com/ (enlace externo)

<img src="../images/media/image496_es.jpg" style="width:100%;height:auto;" />
Búsqueda en GitHub [captura de pantalla]. (2023). GitHub. https://github.com/ (enlace externo)

---

Con código abierto, saber dónde buscar y qué buscar puede ser un desafío. Siempre puedes comenzar con una búsqueda en Google. Sin embargo, puede ser valioso reflexionar sobre algunas preguntas que guían el proceso de descubrimiento. Si la persona usuaria carece de experiencia relevante, también puede ser útil interactuar con colegas con más experiencia en esta etapa.

Revisa el diagrama de flujo a continuación, que ilustra cómo una búsqueda sigue la definición de la necesidad:

<img src="../images/media/image128_es.jpg" style="width:6.23514in;height:3.24979in" />
Crédito de la imagen: NASA

### El software abierto se agrega y se puede buscar en repositorios

Un repositorio de software es una colección en línea de paquetes de software independientes. Los repositorios suelen controlar el acceso y rastrear despliegues o descargas de paquetes.

Los paquetes de software a menudo se proporcionan como ejecutables sin código.

La colección típicamente incluye metadatos, documentación y restricciones de licencia para cada paquete. Puede incluir diferentes versiones del software y las plataformas o entornos en los que puede ejecutarse.

La mayor parte del código de investigación debería ser software de código abierto, almacenado en repositorios de código.

#### Ejemplos de repositorios de software incluyen:

<table>
<colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
</colgroup>
<tbody>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo1_es.png"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo2_es.png"></td>
    </tr>
    <tr>
        <td>Software Heritage</td>
        <td>Open Source Development Network (OSDN)</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo3_es.png"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo4_es.png"></td>
    </tr>
    <tr>
        <td>SourceForge</td>
        <td>Free and Open Source Software Hub (FOSSHUB)</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo5_es.png"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo6_es.png"></td>
    </tr>
    <tr>
        <td>Googlecode</td>
        <td>Comprehensive Perl Archive Network</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo7_es.png"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo8_es.jpg"></td>
    </tr>
    <tr>
        <td>PyPI</td>
        <td>CRAN</td>
    </tr>
</tbody>
</table>

**Créditos de logos:**  
(Se mantienen según el original, sin modificaciones).

**Recursos de NASA para descubrir software abierto**

Algunos enlaces a repositorios específicos de NASA que pueden resultar de interés:

- https://code.nasa.gov/  
- https://api.nasa.gov/  
- https://sciencediscoveryengine.nasa.gov/app/nasa-sba-smd/  
- https://ui.adsabs.harvard.edu/ (enlace externo)  
- https://www.earthdata.nasa.gov/engage/open-data-services-and-software/api  
- https://emac.gsfc.nasa.gov/  

## Evaluar código y software abierto

Has descubierto código abierto prometedor para resolver tu problema científico. Sin embargo, hay preguntas clave que considerar: ¿puedes confiar en ese código? ¿Cuánto tiempo llevará aprenderlo? ¿Podría contener malware? ¿Podrías tener problemas legales por usarlo?

**Ejemplo:** encontraste el “General Ocean Turbulence Model (GOTM)” en internet, o múltiples fragmentos de código relacionados con el espectro de potencia Lomb Scargle. Ahora deseas evaluar ese código para decidir si usarlo.

### Cuatro consideraciones generales para evaluar software abierto

- **Funcionalidad:** ¿será útil para tu problema científico?
- **Interoperabilidad:** ¿qué tan difícil será usarlo?
- **Seguridad:** ¿es seguro? ¿su uso genera riesgos de seguridad?
- **Licencias y restricciones:** ¿está permitido su uso? ¿es legal usarlo en tu proyecto?

### Funcionalidad: evaluar la utilidad científica

**¿El software satisface tus necesidades científicas?**

- ¿Aborda tu pregunta científica específica?
- ¿Estudios similares al tuyo lo utilizan?
- ¿Qué artículos lo citan y cómo lo usan?
- ¿Personas asesoras o colegas tienen experiencia con él?

**Probar la compatibilidad científica**

- ¿Incluye casos de prueba científicos? Reproduce uno relevante para tu problema y verifica que los resultados sean los esperados.
- Si realizaste análisis o modelado similar previamente, reproduce esos resultados con el nuevo software. ¿Son consistentes?
- Modifica incrementalmente un caso de prueba para abordar nuevas preguntas científicas o desarrolla uno propio siguiendo ejemplos relevantes.

### Interoperabilidad: facilidad de uso

**¿El código está escrito en un lenguaje que conoces?**

Puede ser más sencillo usar lenguajes familiares e importar el código en software existente, aunque el uso de paquetes y ejecutables existentes también puede acelerar tu trabajo.

**Revisar la documentación**

Consulta el archivo README. ¿Cumple con tus requisitos funcionales? ¿Las dependencias del entorno están claramente definidas y son razonables?

**Evidencia de interoperabilidad**

Es una buena señal encontrar evidencia de uso exitoso por otras personas con necesidades científicas o técnicas similares.

### Factores para evaluar la calidad del software de código abierto

Para una evaluación rápida del uso comunitario y la calidad del software, utiliza las herramientas del repositorio donde lo encontraste. Por ejemplo, GitHub permite revisar actividad de desarrollo, número de descargas o bifurcaciones, y otros indicadores de calidad.

<img src="../images/media/image291_es.jpg" style="width:100%;height:auto;" />
Búsqueda modificada en GitHub [captura de pantalla]. (2023). GitHub. https://github.com/astropy/astropy (enlace externo)

### La importancia del archivo README

- Es el punto de partida universal al evaluar software.
- Explica qué hace el software, cómo instalarlo y usarlo, o indica dónde encontrar esa información.
- Asume conocimiento previo limitado de la persona lectora.
- Incluye descripción de compatibilidad y dependencias.
- Incluye ejemplos de uso o casos de prueba.

### Seguridad: consideraciones al usar código abierto

El riesgo suele ser bajo para fragmentos pequeños de código que puedes comprender completamente. En paquetes grandes, puede no ser posible entender todos los componentes.

El software abierto se percibe a veces como más riesgoso, pero suele ser menos problemático que ejecutables cerrados, ya que la comunidad puede auditar el código.

Buenas prácticas:

- Consultar políticas institucionales y equipos de IT.
- Usar herramientas de seguridad (por ejemplo, OWASP).
- Evitar software sin mantenimiento activo.
- Tener precaución al usar herramientas externas con datos sensibles.

### Licencias

Antes de reutilizar código abierto, revisa las restricciones legales indicadas en la licencia. En general existen licencias permisivas (Apache 2.0, MIT, BSD) y no permisivas (copyleft), que imponen mayores restricciones.

## Reutilizar código abierto

El software puede reutilizarse ejecutándolo directamente, importándolo como biblioteca, copiando fragmentos permitidos o reescribiéndolo.

### Seleccionar la versión adecuada

- Usar la versión estable más reciente.
- Verificar el origen de la versión.
- Revisar problemas y errores conocidos.

### Resolver problemas al reutilizar software

- Implementar pruebas.
- Revisar notas de versión y foros.
- Pedir ayuda en foros públicos.

### Actividad 2.1: Formas de obtener ayuda usando software abierto

(Se mantiene estructura y contenido del original).

## Citar y reconocer el uso de código abierto

Cita el código que contribuyó significativamente a tu investigación. Idealmente, utiliza versiones archivadas con DOI y sigue las indicaciones del repositorio.

## Lección 2: Resumen

En esta lección aprendiste que:

- El código abierto existe en un ecosistema vasto y distribuido.
- Los artículos científicos son una buena fuente para descubrir código abierto.
- Es clave evaluar funcionalidad, interoperabilidad, seguridad y licencias.
- Se debe usar la versión estable más reciente y probar el software.
- Es importante citar y reconocer el uso de código abierto.

## Lección 2: Autoevaluación

(Se mantienen preguntas y opciones del original).

### Referencias citadas

- Wilkinson, M. et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship. *Scientific Data*, 3, 160018. https://doi.org/10.1038/sdata.2016.18 (enlace externo)
