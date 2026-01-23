# Lección 2: Usar Datos Abiertos

## Contenidos

- [Introducción](#introducci%C3%B3n)
- [Descubrir Datos Abiertos](#descubrir-datos-abiertos)
- [Evaluar los Datos Abiertos](#evaluar-los-datos-abiertos)
- [Usar Datos Abiertos](#usar-datos-abiertos)
- [Lección 2: Resumen](#lecci%C3%B3n-2-resumen)
- [Lección 2: Evaluación](#lecci%C3%B3n-2-evaluaci%C3%B3n)

## Descripción general

En esta lección aprenderás a descubrir, evaluar y citar un conjunto de Datos Abiertos. Al explorar repositorios, también aprenderás sobre los problemas y las consideraciones al buscar conjuntos de datos. Después, aprenderás a determinar si el conjunto de datos es adecuado para su uso y qué revisar en la documentación, las licencias y los formatos de archivo. La lección concluye con una discusión sobre la importancia de citar los conjuntos de datos y sobre cómo leer y seguir las instrucciones de citación.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Seleccionar fuentes de datos y usar técnicas de búsqueda para descubrir Datos Abiertos.
- Evaluar si un conjunto de datos incorpora elementos de Acceso Abierto que garantizan que sean fácilmente reusados.
- Explicar la importancia de citar Datos Abiertos, y encontrar y seguir las instrucciones de citación.

## Introducción

Los Datos Abiertos no siempre son fáciles de usar en tu investigación. A veces hay varias versiones del mismo conjunto de datos, así que aprender a descubrir y evaluar y luego usar los Datos Abiertos te ayudará a ahorrar tiempo.

Como ejemplo, veamos los datos mensuales promedio de dióxido de carbono del Observatorio "Mauna Loa" en Hawaii. Este conjunto de datos fundacional constituye el registro más extenso de mediciones directas de dióxido de carbono en la atmósfera terrestre. Estas observaciones se iniciaron con el trabajo de C. David Keeling de la Institución de Oceanografía "Scripps" en marzo de 1958, en una instalación de la Administración Nacional Oceánica y Atmosférica (Scripps CO2 Program, s. f.).

<img src="../images/media/image19_es.jpg" style="width:100%;height:auto;" alt="Gráfico de serie temporal titulado “Concentración de dióxido de carbono en el Observatorio Mauna Loa*”. Eje vertical: “Concentración de CO2 (ppm)”. Eje horizontal: años desde 1960 hasta 2020+. Una línea negra con oscilaciones estacionales muestra un aumento sostenido de CO2 a lo largo del tiempo. En la esquina inferior derecha aparecen los logos de UC San Diego y Scripps Institution of Oceanography." />
Fuente de la imagen: “Concentración de dióxido de carbono en el Observatorio de Mauna Loa (en inglés, Carbon Dioxide Concentration at Mauna Loa Observatory)”, de la Institución Scripps de Oceanografía de la Universidad de California en San Diego (Scripps Institution of Oceanography UC San Diego). Licencia CC BY 4.0

Si deseas hacer este gráfico tú mismo o usar los datos para algún otro fin, primero deberás encontrarlos. Si buscas este conjunto de datos o cualquier otro dato, es posible que encuentres varias fuentes. ¿Cómo decides qué datos usar?

Si comienzas en Google y buscas "datos de dióxido de carbono de Mauna Loa", encontrarás muchos resultados. Aquí se presentan algunos de ellos:

<img
  src="../images/media/image20_es.png"
  style="width:100%;height:auto;"
  alt="Imágenes de cinco pantallas comparando resultados de búsqueda para “datos de dióxido de carbono de Mauna Loa”. Pantalla 1: “Laboratorio de Monitoreo Global de la NOAA” (https://gml.noaa.gov/ccgg/trends/data.html) con el texto: “Sitio de la NOAA. Archivos en formato texto y csv. Las condiciones de uso requieren mencionar la autoría y menciona a alguien ¡que no es Keeling! Sin DOI.” Pantalla 2: “La Curva Keeling de UCSD” (https://keelingcurve.ucsd.edu/) con el texto: “¡La fuente de datos original! ¡Pero sólo está como un archivo csv! Buena declaración de reutilización, licencias y tiene DOI.” Pantalla 3: “CO2.earth” (https://www.co2.earth/) con el texto: “Otra fuente de los datos de Keeling.” Pantalla 4: “IRIDL KEELING MAUNA_LOA co2” (https://gml.noaa.gov/ccgg/trends/data.html) con el texto: “Los datos finalizan en 1995. Referencias las publicaciones de Keeling. Sin DOI. Sin link a los datos originales.” Pantalla 5: “DataHub CO2 PPM” (https://datahub.io/core/co2-ppm) con el texto: “Tiene link para comenzar a explorar los datos en una notebook interactiva. No está siendo actualizado.”"
/>
- Primer crédito de imagen: Modificado de "Trends in Atmospheric Carbon Dioxide CO2" Dr. Xin Lan, NOAA/GML y Dr. Ralph Keeling Scripps Institution of Oceanography  
- Segundo crédito de imagen: Modificado de "Carbon Dioxide Concentration at Mauna Loa Observatory" por Scripps Institution of Oceanography en UC San Diego, Licencia CC BY 4.0  
- Tercer crédito de imagen: Modificado de Earth's CO2 Home Page por CO2.earth  
- Cuarto crédito de imagen: Modificado de "Trends in Atmospheric Carbon Dioxide CO2" Dr. Xin Lan, NOAA/GML y Dr. Ralph Keeling Scripps Institution of Oceanography  
- Quinto crédito de imagen: Modificado de "Trends in Atmospheric Carbon Dioxide" DATA HUB Open Data Commons Public Domain Dedication and License

¿Cómo decides cuál usar? En esta lección cubriremos cómo encontrar datos abiertos, evaluar su relevancia y luego usarlos en tu propio trabajo.

---

## Descubrir Datos Abiertos

Los Datos Abiertos pueden descubrirse accediendo a una gran variedad de repositorios de datos, portales de búsqueda y publicaciones. Un paso clave es identificar los términos de búsqueda adecuados para tu solicitud. Aprender la nomenclatura y los estándares específicos de la comunidad puede acelerar tu búsqueda.

### Dónde comenzar tu búsqueda

Hay múltiples caminos para encontrar datos de investigación y deberías tener práctica en todos.

<img
  src="../images/media/image21_es.png"
  style="width:100%;height:auto;"
  alt="Infografía con un círculo central que dice “Datos” y flechas hacia cinco formas de comenzar a buscar datos de investigación. 1) “Búsqueda de revistas (ADS, PubMed)”: “El mejor lugar para comenzar cuando sabes lo que quieres estudiar; sigue los datos referenciados en los artículos.” 2) “Entornos de software (APIs, módulos de Python)”: “Muchos sitios que archivan datos tienen interfaces de programación (aunque no todos). La manera más fácil de integrar los datos a tu código.” 3) “Personas asesoras en investigación y colegas”: “Si recién comienzas a investigar, ¡este es el mejor lugar para comenzar! Aquí también es donde ‘aprendes el lenguaje’.” 4) “Búsqueda en internet”: “Probado y comprobado, pero tienes que hacer mucho más trabajo para asegurarte que los datos son confiables.” 5) “Repositorio de datos”: “Examinado por tu comunidad profesional; ésta es tu fuente de mejor.”"
/>

### Personas que conoces (en línea o en persona)

¿Cuál es la primera y mejor forma de encontrar datos de investigación? Preguntar a tu comunidad. Esto incluye a quien te asesora en la investigación, a colegas, a miembros del equipo y a personas en línea. Saber dónde encontrar datos confiables y de alta calidad es una habilidad tan importante como cualquier técnica de laboratorio. Esta habilidad se aprende trabajando con profesionales de tu campo. No existe una única fuente ideal ni un único método. Incluso puedes encontrar datos de personas que no esperabas.

<img src="../images/media/image22_es.jpeg" style="width:100%;height:auto;" />
Fuente de la imagen: NASA, Dominic Hart 2023

---

### Publicaciones

Los conjuntos de datos a menudo se adjuntan a publicaciones especializadas en forma de material complementario. Los motores de búsqueda de publicaciones pueden permitir el descubrimiento de publicaciones relevantes que se pueden usar para encontrar datos de una publicación en particular.

### Portales de búsqueda de datos

Los datos también se pueden encontrar usando una amplia variedad de portales de búsqueda, incluyendo:

*Selecciona cada pestaña para ver más información.*

<table>
  <thead>
    <tr>
        <th>PORTALES DE DATOS GENÉRICOS &#9745;</th>
        <th>PORTALES DE BÚSQUEDA DE DATOS POR DISCIPLINA ESPECÍFICA</th>
        <th>PORTALES NACIONALES E INTERNACIONALES DE DATOS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los portales de búsqueda de datos genéricos permiten el descubrimiento de una gran variedad de datos. No están diseñados para disciplinas específicas; sirven a un público más amplio. Este tipo de portal de búsqueda recopila y facilita la búsqueda de datos. No son fuentes de información científica. Se trata de servicios de agregación que hacen hincapié en la cantidad, no necesariamente en la calidad. Aquí es donde las personas que hacen ciencia ciudadana suelen acudir para encontrar datos y, para los no profesionales, es una gran manera de involucrarse en la ciencia.</p>
            <p>Ejemplos incluyen:</p>
            <ul>
                <li><a href="https://datasetsearch.research.google.com/">Google</a> (enlace externo)</li>
                <li><a href="https://www.kaggle.com/datasets">Kaggle</a> (enlace externo)</li>
                <li><a href="https://www.wikidata.org/wiki/Wikidata:Main_Page">Wikidata</a> (enlace externo)</li>
                <li><a href="https://github.com/awesomedata/awesome-public-datasets#readme">Impresionante conjunto de datos públicos (Awesome Public Datasets)</a> (enlace externo)</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>PORTALES DE DATOS GENÉRICOS</th>
        <th>PORTALES DE BÚSQUEDA DE DATOS POR DISCIPLINA ESPECÍFICA &#9745;</th>
        <th>PORTALES NACIONALES E INTERNACIONALES DE DATOS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los portales de búsqueda de datos por disciplina permiten descubrir tipos de datos específicos. Generalmente están diseñados para satisfacer las necesidades de su comunidad.</p>
            <p>Ejemplos incluyen:</p>
            <ul>
                <li><a href="https://www.earthdata.nasa.gov/">Datos de la tierra de la NASA (NASA Earthdata)</a></li>
                <li><a href="https://opendata.cern.ch/">CERN</a> (enlace externo)</li>
                <li><a href="https://www.ncbi.nlm.nih.gov/">Centro Nacional de Información sobre Biotecnología NCBI (NCBI National Center for Biotechnology Information)</a> (enlace externo)</li>
                <li><a href="https://www.ebi.ac.uk/">Instituto Europeo de Bioinformática (EMBL European Bioinformatics Institute)</a> (enlace externo)</li>
                <li><a href="https://www.icpsr.umich.edu/web/pages">ICPSR</a> (enlace externo)</li>
                <li><a href="https://www.ncdc.noaa.gov/cdo-web/datasets">NOAA Climate Data Online</a> (enlace externo)</li>
                <li><a href="https://earthexplorer.usgs.gov/">USGS EarthExplorer</a> (enlace externo)</li>
                <li><a href="https://www.opensciencedatacloud.org/">Nube de Datos de Ciencia Abierta (Open Science Data Cloud, OSDC)</a> (enlace externo)</li>
                <li><a href="https://pds.nasa.gov/">Sistema de datos planetarios de la NASA (NASA Planetary Data System)</a></li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>PORTALES DE DATOS GENÉRICOS</th>
        <th>PORTALES DE BÚSQUEDA DE DATOS POR DISCIPLINA ESPECÍFICA</th>
        <th>PORTALES NACIONALES E INTERNACIONALES DE DATOS &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los portales de búsqueda de datos nacionales e internacionales permiten descubrir datos producidos por organizaciones nacionales e internacionales o financiados por ellas.</p>
            <p>Ejemplos incluyen:</p>
            <ul>
                <li><a href="https://data.gov/">Datos federales de Estados Unidos (en inglés)</a> (enlace externo)</li>
                <li><a href="https://data.europa.eu/en">Portal de Datos de la Unión Europea</a> (enlace externo)</li>
                <li><a href="https://apps.who.int/gho/data/node.home">Organización Mundial de la Salud (OMS)</a> (enlace externo)</li>
                <li><a href="https://data.worldbank.org/">Banco Mundial</a> (enlace externo)</li>
                <li><a href="https://www.data.gov.uk/">data.gov.uk (en inglés)</a> (enlace externo)</li>
                <li><a href="https://data.unicef.org/">UNICEF (en inglés)</a> (enlace externo)</li>
                <li><a href="https://www.data.gouv.fr/en/">Plataforma abierta de datos públicos de Francia (en francés)</a> (enlace externo)</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

### Repositorios

Una forma común de compartir y encontrar Datos Abiertos es a través de repositorios de datos. Muchos repositorios albergan Datos Abiertos con identificadores persistentes, licencias claras y directrices de citación y metadatos estándar.

Ten en cuenta que algunos de nuestros portales de búsqueda, por ejemplo, también son repositorios, pero no siempre. Algunos de los portales de búsqueda son simplemente catálogos de información sobre los datos, en lugar de ubicaciones de almacenamiento de los datos.

*Selecciona cada pestaña para ver más información.*

<table>
  <thead>
    <tr>
        <th>REPOSITORIOS GENERALES &#9745;</th>
        <th>REPOSITORIOS DE DOMINIO ESPECÍFICO</th>
        <th>REPOSITORIOS INSTITUCIONALES</th>
        <th>REPOSITORIOS NACIONALES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Los repositorios generales no están diseñados para una comunidad específica y son accesibles para cualquier persona.</p>
            <p>Ejemplos incluyen:</p>
            <ul>
                <li><a href="https://zenodo.org/">Zenodo</a> (enlace externo)</li>
                <li><a href="https://data.mendeley.com/">Mendeley Data</a> (enlace externo)</li>
                <li><a href="https://figshare.com/">Figshare</a> (enlace externo)</li>
                <li><a href="https://datadryad.org/stash">Dryad</a> (enlace externo)</li>
            </ul>
            <p>Consulta el [cuadro comparativo de repositorios generalistas (Generalist Repository Comparison Chart)](https://fairsharing.org/collection/GeneralRepositoryComparison) (enlace externo) como herramienta para explorar repositorios adicionales y obtener orientación. Dataverse también ha publicado (en inglés) una [revisión comparativa](https://dataverse.org/blog/comparative-review-various-data-repositories) (enlace externo) de ocho repositorios de datos.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>REPOSITORIOS GENERALES</th>
        <th>REPOSITORIOS DE DOMINIO ESPECÍFICO &#9745;</th>
        <th>REPOSITORIOS INSTITUCIONALES</th>
        <th>REPOSITORIOS NACIONALES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Los repositorios especializados (generalmente para temas de datos específicos) brindan soporte e información sobre estándares requeridos para metadatos y otros aspectos.</p>
            <p>Algunos ejemplos son:</p>
            <ul>
                <li>Astronomía: <a href="https://archive.stsci.edu/">Datos del telescopio Hubble</a> (enlace externo)</li>
                <li>Biología espacial: <a href="https://genelab.nasa.gov/">NASA GeneLab: Ciencia Abierta para la vida en el espacio (NASA GeneLab: Open Science for Life in Space)</a></li>
                <li>Física espacial: <a href="https://heliophysicsdata.gsfc.nasa.gov/websearch/dispatcher">Portal de Datos de Heliofísica - Buscador de productos de física solar espacial (Heliophysics Data Portal, NASA)</a></li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>REPOSITORIOS GENERALES</th>
        <th>REPOSITORIOS DE DOMINIO ESPECÍFICO</th>
        <th>REPOSITORIOS INSTITUCIONALES &#9745;</th>
        <th>REPOSITORIOS NACIONALES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Muchas universidades y organizaciones apoyan la gestión de datos y software de investigación mediante repositorios, conocidos como repositorios institucionales, para ayudar a sus investigadores a cumplir con requisitos de políticas.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>REPOSITORIOS GENERALES</th>
        <th>REPOSITORIOS DE DOMINIO ESPECÍFICO</th>
        <th>REPOSITORIOS INSTITUCIONALES</th>
        <th>REPOSITORIOS NACIONALES &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Los repositorios nacionales agregan datos y los ponen a disposición del público.</p>
            <p>Los datos almacenados en estos repositorios suelen ser producidos por gobiernos.</p>
            <p>Ejemplos incluyen:</p>
            <ul>
                <li>Suecia: <a href="https://snd.se/en">https://snd.se/en</a> (enlace externo)</li>
                <li>Unión Europea: <a href="https://data.europa.eu/en">https://data.europa.eu/en</a> (enlace externo)</li>
                <li>Australia: <a href="https://www.naa.gov.au/">https://www.naa.gov.au/</a> (enlace externo)</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

### Desafíos con repositorios de datos

- Ningún repositorio, motor de búsqueda ni buscador de publicaciones tendrá acceso a todos los Datos Abiertos disponibles.
- Los términos de búsqueda pueden no ser consistentes entre todas las fuentes o campos de la ciencia.
- Es esencial familiarizarse con la nomenclatura estándar y los términos de metadatos apropiados.
- No existe una receta infalible. Es posible que debas probar numerosos términos y fuentes de datos antes de encontrar datos relevantes.

### Actividad 2.1: Descubrir Datos Abiertos

Unir el tipo de repositorio con la definición correcta.

|  |  |
|---|---|
| Repositorios generales | Diseñados para todas las comunidades y de fácil acceso para todas las personas |
| Repositorios específicos por dominio | Repositorios que habitualmente se destinan a datos específicos |
| Repositorios institucionales | Repositorios gestionados por universidades y organizaciones |
| Repositorios nacionales | Repositorios financiados por el gobierno |

## Evaluar los Datos Abiertos

<img
  src="../images/media/image24_es.png"
  style="width:100%;height:auto;"
  alt="Infografía titulada “Encontré los datos... ¿pero son buenos?” con una nube central verde y tres íconos (microscopio, símbolos de código y un átomo). Alrededor aparecen preguntas para evaluar un conjunto de datos: “¿Los datos son apropiados para mi proyecto?”, “¿Tienen metadatos?”, “¿Los datos están documentados?”, “¿Necesito software específico para usar los datos?”, “¿Están en un formato en el que puedo usarlos?”, “¿Cuál es la licencia? ¿Tengo permiso para usarlos?”, “¿Cómo debo citar los datos?”, “¿Son los datos originales o alguien los modificó?” y “¿Alguien más ha usado estos datos?”."
/>
Crédito: NASA

El uso de Datos Abiertos para un proyecto depende de una serie de factores, como la calidad de los datos, las condiciones de acceso y reúso, la facilidad para encontrar los datos, etc. Algunos elementos esenciales (adaptados de un curso de gestión de datos abiertos creado por GODAN Action) para evaluar la pertinencia y utilidad de los conjuntos de datos son:

**Preguntas prácticas**

- ¿Están bien descritos los datos?
- ¿Es clara la razón por la que se recogen los datos? ¿Es claro el uso que el editor hace de los datos?
- ¿Existen otros usos de los datos descritos?
- ¿Son accesibles los datos?
- ¿Los datos están actualizados o tienen fecha?
- ¿Estarán disponibles los datos durante al menos un año?
- ¿Se actualizarán los datos periódicamente?
- ¿Existe un proceso de control de calidad?

**Preguntas técnicas**

- ¿Están disponibles los datos en un formato adecuado al contenido?
- ¿Se dispone de los datos desde una ubicación consistente?
- ¿Están los datos bien estructurados y pueden ser leídos de forma automatizada?
- ¿Se describen los términos y acrónimos complejos que aparecen en los datos?
- ¿Usan los datos un esquema o estándar de datos?
- ¿Hay alguna API disponible para acceder a los datos?
- ¿Qué herramientas o programas informáticos se necesitan para usar estos datos?

**Preguntas sociales**

- ¿Existe una comunidad de usuarios de los datos?
- ¿Se trata de datos en los que ya confía un gran número de personas?
- ¿Están los datos respaldados oficialmente?
- ¿Existen acuerdos de nivel de servicio para los datos?
- ¿Está claro quién mantiene los datos y con quién se debe contactar?

(GODAN Action, s. f.)

Muchas de estas preguntas pueden responderse consultando la documentación y los metadatos de un conjunto de datos, así como su formato y su licencia, aspectos que se tratarán con más detalle en la próxima lección "Hacer Datos Abiertos".

## Usar Datos Abiertos

### La importancia de la citación

Los agradecimientos y las citas contribuyen a fomentar una cultura de intercambio de datos sin temor a que se roben ideas ni reconocimientos. Si una persona investigadora puede confiar en que su trabajo será citado y usado para impulsar el desarrollo de la ciencia, la idea de abrir los datos resulta más atractiva y beneficiosa para ambas partes. Se recomienda el uso de prácticas de citación estándar para garantizar el debido reconocimiento.

Citar los datos también contribuye a la transparencia en el uso que se hace de ellos. Al citar los datos, las personas autoras originales y los nuevos equipos de investigación pueden seguir fácilmente cómo se usan los datos para responder a diferentes preguntas.

### Revisar pautas de citación

Muchos conjuntos de datos y repositorios especifican cómo deben ser citados. La cita suele incluir:

- Las personas autoras y sus instituciones
- Título
- ORCiD
- DOI
- Versión
- URL
- Fecha de creación
- También pueden especificarse campos adicionales

<img
  src="../images/media/image25_es.png"
  style="width:100%;height:auto;"
  alt="Captura de pantalla de un ejemplo de código en un archivo CITATION.cff (formato YAML) que indica cómo citar un software. Incluye campos como versión del formato (cff-version), mensaje de citación, autores con nombres y ORCID, título del software, versión, identificador DOI y fecha de publicación."
/>
Fuente: GitHub (https://github.com/) (enlace externo)

---

La mayoría de los conjuntos de datos exigen (como mínimo) que al citarlos se indique la persona responsable de los datos, el nombre del archivo que los alberga, el nombre del conjunto de datos, la fecha del conjunto de datos y el DOI.

### Citar Datos Abiertos: Ejemplos (en inglés)

**Ejemplo de un Centro de Archivo Activo Distribuido de la NASA (Distributed Active Archive Center, DAAC)**

Matthew Rodell and Hiroko Kato Beaudoing, NASA/GSFC/HSL (08.16.2007), GLDAS CLM Land Surface Model L4 3 Hourly 1.0 x 1.0 degree Subsetted,version 001, Greenbelt, Maryland, USA: Goddard Earth Sciences Data and Information Services Center (GES DISC), Accessed on July 12th, 2018 at doi:10.5067/83NO2QDLG6M0

**Ejemplo del Sistema de Datos Planetarios de la NASA (NASA Planetary Data System, PDS)**

Justin N. Maki. (2004). MER 1 MARS MICROSCOPIC IMAGER RADIOMETRIC  
RDR OPS V1.0 [Conjunto de datos]. NASA Planetary Data System. [https://doi.org/10.17189/1520416](https://doi.org/10.17189/1520416)

## Lección 2: Resumen

Conclusiones principales de esta lección:

- Los datos relevantes pueden encontrarse en diversos lugares y puede ser necesario recurrir al método de ensayo y error para localizarlos. Usa repositorios en línea o conversa con colegas de la comunidad para comenzar.
- Es necesario evaluar cuidadosamente los datos antes de usarlos. Asegúrate de que los datos sean reutilizables, relevantes para tu trabajo y provengan de una fuente confiable.
- Es importante citar los datos cuando se usan para otorgar el crédito adecuado a quienes investigan.

## Lección 2: Evaluación

Responde las siguientes preguntas para evaluar lo que has aprendido hasta ahora.

*Pregunta*

**01/03**

¿Cuál de los siguientes métodos puede usarse para encontrar datos?

- Usar términos de búsqueda apropiados
- Investigar datos identificados por DOI en publicaciones
- Identificar repositorios de datos relevantes
- Todas las anteriores

*Pregunta*

**02/03**

¿Cuál o cuáles de los siguientes son puntos a considerar al evaluar si se puede usar un conjunto de datos?

- ¿Están bien descritos los datos?
- ¿Están los datos bien estructurados y pueden ser leídos de forma automatizada?
- ¿Existe una comunidad de personas usuarias de los datos?
- ¿Qué herramientas o programas informáticos se necesitan para usar estos datos?
- ¿Se actualizarán los datos periódicamente?
- ¿Es claro el uso que el editor hace de los datos?
- Todas las anteriores

*Pregunta*

**03/03**

¿Qué información suele incluirse en un archivo de citación?

- Personas autoras y sus instituciones
- Título
- ORCiD
- DOI
- Versión
- URL
- Fecha de creación
- Todas las anteriores

### Referencias citadas

- GODAN Action. (s. f.). Lesson 2.2: Quality and provenance. GODAN Action Open Data Management in Agriculture and Nutrition Course. [https://aims.gitbook.io/open-data-mooc/unit-3-using-open-data/lesson-2.2-quality-and-provenance](https://aims.gitbook.io/open-data-mooc/unit-3-using-open-data/lesson-2.2-quality-and-provenance) (enlace externo)
- Scripps CO2 Program. (s. f.). University of California San Diego. [https://scrippsco2.ucsd.edu/](https://scrippsco2.ucsd.edu/) (enlace externo)
