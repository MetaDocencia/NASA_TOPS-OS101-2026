# Lección 3: Herramientas para Datos Abiertos

## Contenidos

-   [Introducción a los Datos Abiertos](#introducci%C3%B3n-a-los-datos-abiertos)
-   [Principios FAIR](#principios-FAIR)
-   [Herramientas para ayudar con la planificación de la creación de Datos Abiertos](#herramientas-para-ayudar-con-la-planificaci%C3%B3n-de-la-creaci%C3%B3n-de-datos-abiertos)
-   [Herramientas para ayudar con el uso y manejo de Datos Abiertos](#herramientas-para-ayudar-con-el-uso-y-manejo-de-datos-abiertos)
-   [Lección 3: Resumen](#lecci%C3%B3n-3-resumen)
-   [Lección 3: Evaluación](#lecci%C3%B3n-3-evaluaci%C3%B3n)


## Panorama general

En esta lección vas a repasar conceptos, consideraciones y herramientas para hacer que los datos y los resultados sean abiertos. A partir de una mirada más detallada a los principios FAIR, vas a aprender cómo validar y reproducir datos abiertos. También vas a conocer planes, herramientas, formatos de datos y otras consideraciones relacionadas con la generación de datos y la publicación de resultados. Además, la lección incluye ejemplos de repositorios y comunidades de datos abiertos. Conocer estos conceptos y herramientas te va a facilitar hacer que tu propia investigación sea accesible y reutilizable.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Definir los diferentes tipos de datos científicos.
- Definir qué significa el acrónimo FAIR y explicar cómo contribuye a compartir datos abiertos.
- Identificar prácticas de gestión de datos y herramientas para localizar datos en repositorios.
- Enumerar y explicar los recursos que se usan habitualmente al generar datos, incluidos formateo, inspección y evaluación del grado de “FAIR-dad” de los datos.

## Introducción a los Datos Abiertos

Los datos son una parte central de la investigación científica, y tiene sentido que así sea. Informan herramientas que usamos, historias que leemos y decisiones que tomamos a diario.

Por ejemplo, el [Copernicus Emergency Management Service](https://emergency.copernicus.eu/) (enlace externo), de acceso abierto y ejecutado por la Comisión Europea, produce datos abiertos las 24 horas del día. Esos datos se recolectan con satélites de la ESA y de la NASA para producir mapas que orientan tareas de preparación y respuesta ante desastres en todo el mundo. Este es solo un ejemplo, entre muchos otros, que muestra el valor de los datos (en especial los datos públicos y abiertos) en la vida cotidiana y para el bien público.

Los datos compartidos abiertamente en investigación científica aportan un valor enorme a la comunidad científica y más allá, desde comunidades pequeñas y aisladas hasta grandes centros urbanos. Antes de avanzar hacia el impacto amplio de los datos, veamos primero qué son los datos en el contexto de la investigación científica. En particular, vamos a hablar de la definición y las características de los datos abiertos.

### ¿Qué son los datos?

Los datos científicos son cualquier tipo de información que se recopila, observa o crea en el contexto de una investigación. Pueden ser:

- Primarios (datos crudos provenientes de mediciones o instrumentos).
- Secundarios (datos procesados a partir de análisis secundarios e interpretaciones).
- Publicados (formato final disponible para uso y reúso).
- Metadatos (datos sobre tus datos).

Incluyen todo lo que se necesita para validar o reproducir los resultados de tu investigación, además de lo que se requiere para comprender y manejar esos datos.

En las secciones siguientes vas a ver distintas maneras de asegurarte de que los datos se utilicen por completo y estén disponibles para la mayor cantidad posible de personas. Estas buenas prácticas se organizan en torno a marcos conceptuales comunitarios y herramientas que ayudan a quienes investigan a gestionar y compartir datos abiertos.

## Principios FAIR

<img src="../images/media/image28.png" style="width:100%;height:auto;" />

Al igual que cuando se maneja por una ruta, si todas las personas siguen un conjunto de reglas acordadas, todo funciona de manera mucho más fluida. Las reglas no tienen que ser idénticas en cada región, pero comparten prácticas generales basadas en lo que se sabe sobre seguridad y eficiencia.

Por ejemplo, se puede manejar por la izquierda o por la derecha. Ambas opciones pueden funcionar, y ese tipo de detalles se define en cada comunidad. Sin embargo, hay pautas generales que se comparten en distintos lugares, como manejar por la calzada y no por la vereda, usar las luces de giro cuando corresponde, respetar los semáforos en las intersecciones y cumplir con las velocidades máximas. Algunas comunidades pueden aplicar reglas más estrictas que otras o llevarlas adelante de manera diferente, pero esas pautas ayudan a que todas las personas se desplacen con seguridad a partir de un entendimiento común de cómo conducir.

Para los datos científicos, estas pautas se publicaron en 2016 en Wilkinson et al. y se conocen como los principios FAIR (Findable, Accessible, Interoperable, Reusable). Hacen exactamente lo que su nombre sugiere: permiten que otras personas (y vos mismo más adelante) puedan encontrar, obtener, comprender y usar correctamente los datos.

**Findable (Encontrables)**

Para que los datos sean [Findable](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/) (enlace externo):

- Los datos y resultados cuentan con un identificador único y persistente a nivel global.
- Los datos se describen con metadatos ricos.
- Los metadatos incluyen de manera clara y explícita el identificador de los datos que describen.
- Los datos y resultados se registran o indexan en un recurso que se puede buscar.

Tecnologías habilitantes actuales:

- [Esquema de metadatos de DataCite](https://schema.datacite.org/) (enlace externo).
- PIDs (identificadores persistentes, por sus siglas en inglés).
  - [Digital Object Identifier (DOI)](https://www.doi.org/) (enlace externo): un campo obligatorio de primer nivel en los metadatos de cada registro (para datos, código y publicaciones).
  - [Open Research and Contributor ID (ORCID)](https://orcid.org/) (enlace externo): un código que identifica de manera unívoca a autores y personas contribuyentes de productos de investigación y comunicación académica.

**Accessible (Accesibles)**

Para que los datos sean [Accessible](https://www.go-fair.org/fair-principles/metadata-retrievable-identifier-standardised-communication-protocol/) (enlace externo):

- Los datos y resultados se pueden recuperar mediante sus identificadores usando un protocolo de comunicación estandarizado.
- El protocolo es abierto, gratuito y de implementación universal.
- El protocolo permite un procedimiento de autenticación y autorización cuando sea necesario. Los datos y resultados son públicamente accesibles y tienen una licencia de dominio público.
  - Los metadatos siguen siendo accesibles incluso cuando los datos ya no están disponibles. Los datos y metadatos se mantienen durante toda la vida útil del repositorio.
  - Los metadatos se almacenan en servidores de bases de datos de alta disponibilidad.

Tecnologías habilitantes actuales:

- [File Transfer Protocol (FTP)](https://www.w3.org/Protocols/rfc959/) (enlace externo) y File Transfer Protocol Secure (FTPS).
- [Hypertext Transfer Protocol (HTTP)](https://www.w3.org/Protocols/) (enlace externo) y Hypertext Transfer Protocol Secure (HTTPS).

Tené en cuenta que Microsoft Exchange Server y Skype son ejemplos de protocolos propietarios. Como siempre, es necesario equilibrar accesibilidad con cuestiones de seguridad, lo que puede afectar el protocolo elegido.

**Interoperable (Interoperables)**

Para que los datos sean [Interoperable](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/) (enlace externo):

- Usan un lenguaje formal, accesible, compartido y ampliamente aplicable para representar conocimiento.
- Utilizan un formato de datos conocido y estandarizado.
- Emplean vocabularios que también siguen principios FAIR.
- Incluyen referencias calificadas a otros datos y metadatos.

Tecnologías habilitantes actuales:

- [Zenodo](https://zenodo.org/) (enlace externo) utiliza [JSON Schema](https://json-schema.org/) (enlace externo) como representación interna de los metadatos y ofrece exportar a otros formatos populares como [Dublin Core](https://www.dublincore.org/) (enlace externo) o [MARCXML](https://www.loc.gov/marc/marcxml.html) (enlace externo).
- Para ciertos términos se recurre a vocabularios abiertos externos, por ejemplo: licencias en [Open Definition](https://opendefinition.org/) (enlace externo), financiadores en [FundRef](https://www.crossref.org/services/funder-registry/) (enlace externo) y proyectos con financiación en [OpenAIRE](https://explore.openaire.eu/) (enlace externo).
- Cada fragmento de datos externos referenciado se identifica mediante una URL resolvible.

**Reusable (Reutilizables)**

Para que los datos sean [Reusable](https://www.go-fair.org/fair-principles/r1-metadata-richly-described-plurality-accurate-relevant-attributes/) (enlace externo):

- Se describen con un conjunto amplio de atributos precisos y relevantes.
- Se publican con una licencia de uso clara y accesible.
- Se asocian a información detallada sobre su procedencia.
- Cumplen con estándares comunitarios relevantes para cada disciplina.

Tecnologías habilitantes actuales:

- El registro de metadatos contiene como mínimo los campos obligatorios de [DataCite](https://schema.datacite.org/) (enlace externo), con la opción de incluir campos recomendados adicionales de DataCite y enriquecimientos propios de Zenodo.
- [Zenodo](https://zenodo.org/) (enlace externo) no es un repositorio específico de un dominio, pero al cumplir con el esquema de metadatos de DataCite, sus registros se ajustan a uno de los estándares transversales más amplios disponibles.

(Wilkinson et al., 2016)

Estos principios son pautas generales y, como sucede con la ciencia abierta, su implementación es matizada. A veces se necesita el esfuerzo coordinado de un grupo y/o un proceso de producción largo (incluida financiación) para que datos y resultados cumplan plenamente con FAIR. En otros casos, el proceso puede ser más sencillo. Para lograr un cumplimiento completo, se necesita un plan de gestión de datos bien coordinado, cuyos detalles se analizan con mayor profundidad en el Módulo 3, “Datos Abiertos”.

## Herramientas para ayudar con la planificación de la creación de Datos Abiertos

### Plan de gestión de datos

La lección anterior describe los requisitos de un plan de gestión de datos (Data Management Plan, DMP). A continuación se presentan dos recursos de ciencia abierta para empezar a elaborar un plan de gestión de datos:

**DMPTool**

El [DMPTool](https://dmptool.org/) (enlace externo), con sede en Estados Unidos, ayuda a quienes investigan mediante plantillas que listan los requisitos de las entidades financiadoras para solicitudes específicas de propuestas (Request for Proposals, RFP). DMPTool también publica otros planes de gestión de datos abiertos de proyectos financiados que pueden usarse como referencia para mejorar tu propio plan. Por ejemplo, el Research Data Management Organizer (RDMO) permite a instituciones y personas en Alemania planificar y llevar adelante la gestión de sus datos de investigación.

**ARGOS**

[ARGOS](https://argos.openaire.eu/home) (enlace externo) se utiliza para planificar actividades de gestión de datos de investigación en proyectos financiados por programas europeos o nacionales (por ejemplo, Horizon Europe, CHIST-ERA o la Fundação para a Ciência e a Tecnologia de Portugal, FCT). ARGOS produce y publica planes de gestión de datos FAIR y ejecutables por máquina, que contienen enlaces a otros productos (como publicaciones, datos y software). Esto reduce el esfuerzo de crear planes de gestión de datos desde cero al incluir automatizaciones en el proceso de escritura. OpenAIRE ofrece una guía para crear estos planes.

### Repositorios de datos

Un repositorio de datos es un espacio digital para alojar, curar y compartir productos de investigación. Los repositorios de datos surgieron para dar respuesta a necesidades de comunidades de investigación. Algunos ejemplos son:

- [Space Physics Data Facility de la NASA](https://spdf.gsfc.nasa.gov/): archivo permanente para datos de física espacial de misiones pasadas y actuales.
- [Heliophysics Digital Resource Library de la NASA](https://hdrl.gsfc.nasa.gov/): ofrece acceso abierto a miles de conjuntos de datos de misiones heliosfísicas actuales e históricas de la NASA.
- [High Energy Astrophysics Science Archive Research Center (HEASARC) de la NASA](https://heasarc.gsfc.nasa.gov/): archivo principal para misiones de la NASA (y de otras agencias espaciales) que estudian radiación electromagnética asociada a fenómenos cósmicos extremadamente energéticos. Incluye datos obtenidos por misiones espaciales, globos y observaciones desde tierra.
- [Planetary Data System (PDS) de la NASA](https://pds.nasa.gov/): archivo de largo plazo de productos de datos digitales provenientes de misiones planetarias de la NASA y otras adquisiciones de datos en vuelo y en tierra, incluidas experiencias de laboratorio.
- [Socioeconomic Data and Applications Center de la NASA](https://www.earthdata.nasa.gov/centers/sedac-daac): se centra en archivar y distribuir datos sobre las interacciones humanas con el ambiente.
- [RCSB Protein Data Bank](https://www.rcsb.org/) (enlace externo), que utiliza un repositorio de datos para catalogar estructuras tridimensionales de proteínas y ácidos nucleicos.
- [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) (enlace externo), del National Institutes of Health, que utiliza una base pública de secuencias genéticas anotadas de ácidos nucleicos.
- [Image Data Resource](https://idr.openmicroscopy.org/) (enlace externo), un repositorio público de conjuntos de datos de microscopía bio-imagen de estudios publicados.
- [Electron Microscopy Public Image Archive](https://idr.openmicroscopy.org/) (enlace externo), recurso público de imágenes crudas de crio-EM.
- [OpenNeuro](https://openneuro.org/) (enlace externo), una plataforma abierta para validar y compartir datos de neuroimagen. Las herramientas que ofrece facilitan el acceso, búsqueda y análisis de conjuntos de datos anotados.

Las herramientas de ciencia abierta, como los repositorios de datos, deberían aplicar principios FAIR, en especial en lo referido a atribución de identificadores persistentes (por ejemplo DOI), anotación de metadatos y legibilidad por máquinas.

Más ejemplos de repositorios de datos y otras herramientas de ciencia abierta incluyen, entre otros:

**Zenodo**

[Zenodo](https://zenodo.org/) (enlace externo) es un repositorio de datos que permite subir datos de investigación y asignar DOIs. Es muy popular en la comunidad científica porque tiene una interfaz simple, admite curaduría comunitaria y ofrece la posibilidad de depositar diversos tipos de productos de investigación: datos, informes, publicaciones, software y contenidos multimedia.

**Dataverse**

[The Dataverse Project](https://dataverse.org/) (enlace externo) es una aplicación en línea de código abierto para compartir, preservar, citar, explorar y analizar datos de investigación. Está disponible de forma gratuita para personas de todas las disciplinas.

**Dryad**

[The Dryad Digital Repository](https://datadryad.org/) (enlace externo) es un recurso en línea curado que hace que los datos de investigación sean descubribles, reutilizables y citables de manera libre. A diferencia de las herramientas mencionadas antes, funciona con un esquema de membresía para organizaciones como instituciones de investigación y editoriales.

**DataCite**

[DataCite](https://datacite.org/) (enlace externo) es una organización global sin fines de lucro que proporciona DOIs para datos de investigación y otros productos, sobre la base de membresías institucionales.

**OSF**

[Open Science Framework](https://osf.io/) (enlace externo) es una plataforma de código abierto para compartir, gestionar y colaborar en investigación.

Los servicios y recursos de datos que sostienen la investigación requieren infraestructura robusta, que a su vez se apoya en la colaboración. La [EUDAT Collaborative Data Infrastructure](https://www.eudat.eu/) (enlace externo), una red estable de más de veinte organizaciones europeas de investigación, es un ejemplo de iniciativa que coordina esfuerzos sobre infraestructuras de servicios de datos.

Empresas privadas también alojan y mantienen herramientas en línea para compartir datos y archivos de investigación. Figshare es un ejemplo de servicio de acceso abierto y gratuito operado por empresas. Proporciona DOIs para todo tipo de archivos y recientemente incorporó un modelo de publicación restringida para contemplar requisitos de propiedad intelectual (Intellectual Property, IP). Permite compartir los productos solo dentro de un grupo de Figshare personalizado (por ejemplo, tu equipo de investigación) o con personas dentro de un determinado rango de IP. Otros avances incluyen la integración con repositorios de código como GitHub, GitLab y Bitbucket.

Se pueden encontrar más repositorios de datos en el [Registro de Repositorios de Datos de Investigación](https://www.re3data.org/) (enlace externo). [OpenAIRE](https://explore.openaire.eu/search/find/dataproviders) (enlace externo), un motor de búsqueda hospedado, también ofrece una función potente para buscar datos y repositorios. Incluye filtros por país, tipo y área temática y permite descargar datos.

La cantidad de datos, repositorios y políticas puede resultar abrumadora. Si te cuesta decidir qué repositorio se adapta mejor a tus necesidades, podés consultar con personas bibliotecarias, gestoras de datos y/o data stewards en tu institución, o preguntar dentro de tu disciplina o comunidad de práctica.

### Actividad 3.1: Explorá Zenodo y registrate

Explorá repositorios abiertos para familiarizarte con su estructura y la información disponible sobre los productos. El repositorio más popular en este momento es Zenodo. Mirá el siguiente video de 4,5 minutos para tener una vista general de Zenodo y luego creá una cuenta. Podés usar tu cuenta de ORCID para registrarte si ya la tenés o si la creaste en la lección anterior.

[Ver video](https://www.youtube.com/watch?v=gEnq_RpVdAM) (enlace externo)

### Herramientas para ayudar con el uso y manejo de Datos Abiertos

### Formatos de datos

Un formato de archivo útil es aquel que puede ser leído en memoria por algún software. Se puede pensar el formato como una herramienta para hacer que los datos sean accesibles. Los formatos fáciles de usar suelen tener:

- Una estructura simple y fácil de comprender.
- Una especificación clara y abierta del formato, idealmente no atada a un producto de software específico.
- Bibliotecas de software abiertas y APIs que permitan analizar (parsear) el formato.

Los formatos más interoperables según estos criterios incluyen Comma Separated Values (CSV), Extensible Markup Language (XML) y JavaScript Object Notation (JSON). Otros formatos comunes para la investigación incluyen formatos binarios basados en arreglos como Network Common Data Form (NetCDF), Hierarchical Data Format (HDF), Geotiff, Flexible Image Transport System (FITS) y formatos diseñados para almacenamiento y acceso en la nube como [Zarr](https://zarr.dev/) (enlace externo), [Cloud Optimized GeoTIFF](https://www.cogeo.org/) (enlace externo) y [Parquet](https://parquet.apache.org/) (enlace externo). Muchos de estos formatos incluyen herramientas para verificar compatibilidad y legibilidad de conjuntos de datos.

### Inspección de datos

Los formatos de datos modernos permiten almacenar mucho más que simples puntos de datos. Cuando se adoptan estos estándares (por ejemplo NetCDF), descubrir el contenido de cada archivo puede ser asistido por una variedad de herramientas que ayudan a mapear datos primarios y mostrar metadatos asociados. Existen muchas herramientas para inspeccionar datos, demasiadas para enumerarlas todas aquí. Algunas de las más destacadas son:

**CSV, XML, JSON**  
Estos archivos pueden abrirse con editores de texto comunes. También existen herramientas que pueden generar visualizaciones más amigables, por ejemplo:

- csv: Microsoft Excel y Google Sheets.  
- xml: La mayoría de los navegadores web y editores de texto como Notepad, Microsoft Word o Google Docs.  
- json: [http://json.parser.online.fr/](http://json.parser.online.fr/) (enlace externo) y [https://jsonformatter.org/json-pretty-print](https://jsonformatter.org/json-pretty-print) (enlace externo).

**NetCDF, HDF, FITS**  
Estos formatos requieren herramientas específicas para visualizar su contenido. Muchas de estas herramientas también pueden graficar los datos.

- NetCDF y HDF: Se pueden visualizar fácilmente usando la biblioteca de software abierto [Xarray](https://docs.xarray.dev/en/stable/) (enlace externo) en Python o la biblioteca [ncdf4](https://cran.r-project.org/web/packages/ncdf4/index.html) (enlace externo) en R.  
- FITS: Hay muchas opciones; una lista se encuentra disponible en [https://fits.gsfc.nasa.gov/fits_viewer.html](https://fits.gsfc.nasa.gov/fits_viewer.html).

**Zarr, COG, Parquet**  
También requieren herramientas específicas para visualizarse. Muchas también permiten graficar los datos.

- Zarr: Se visualiza con [Xarray](https://docs.xarray.dev/en/stable/) (enlace externo) en Python o con la biblioteca [Pizzarr](https://github.com/keller-mark/pizzarr) (enlace externo) en R.  
- COG: Se visualiza con la biblioteca [rioXarray](https://corteva.github.io/rioxarray/html/index.html) (enlace externo) en Python o [terra](https://cran.r-project.org/web/packages/terra/index.html) (enlace externo) en R.  
- Parquet: Se visualiza con [Pandas](https://pandas.pydata.org/) (enlace externo) en Python o [Arrow](https://arrow.apache.org/docs/r/reference/read_parquet.html) (enlace externo) en R.

### Evaluación FAIR

¿Cómo saber cuán “FAIR” es tu conjunto de datos? Dos grupos, [FAIRsharing.org](https://fairsharing.org/) (enlace externo) y la [Research Data Alliance (RDA)](https://www.rd-alliance.org/) (enlace externo), desarrollaron los [FAIR Metrics](https://www.nature.com/articles/sdata2018118) (enlace externo) y el [FAIR Data Maturity Model](http://dx.doi.org/10.15497/RDA00050) (enlace externo) para evaluar el nivel de cumplimiento FAIR. Existen herramientas de código abierto para ayudar a realizar esta evaluación:

**Australian Research Data Commons (ARDC)**  
#### FAIR Data Self-Assessment Tool  
[FAIR Data Self-Assessment Tool](https://ardc.edu.au/resource/fair-data-self-assessment-tool/) (enlace externo) es un proceso manual mediante un cuestionario en línea.

Mejor para:  
- Generar conversaciones iniciales sobre implementación FAIR.  
- Identificar áreas para mejorar.

Resultados incluyen:  
- Barra de progreso para cada principio FAIR.  
- Barra agregada total.

**FAIR-Checker**  
[FAIR-Checker](https://fair-checker.france-bioinformatique.fr/) (enlace externo) es automático (vía sitio web o API).

Mejor para:  
- Escalar a muchos conjuntos de datos.  
- Identificar áreas de mejora.

Resultados incluyen:  
- Gráfico con puntajes y detalles.

**F-UJI**  
[F-UJI](https://www.f-uji.net/) (enlace externo) también es automático.

Mejor para:  
- Evaluar muchos conjuntos de datos.  
- Recibir documentación detallada de la herramienta.

Resultados incluyen:  
- Informe y gráfico con puntajes.

**FAIR Evaluation Services**  
[FAIR Evaluation Services](https://fairsharing.github.io/FAIR-Evaluator-FrontEnd/#!/) (enlace externo) es automático.

Mejor para:  
- Evaluar múltiples conjuntos de datos.  
- Crear evaluaciones personalizadas.

Resultados incluyen:  
- Informe detallado y gráfico.

## Lección 3: Resumen

En esta lección aprendiste:

- Los diferentes tipos de datos científicos, incluidos datos primarios, secundarios, publicados y metadatos.
- Prácticas de ciencia abierta para implementar principios FAIR que permiten que datos y resultados sean accesibles para una amplia variedad de personas.
- Herramientas digitales para planificar la creación y el intercambio de datos abiertos.

## Lección 3: Evaluación de conocimiento

**Pregunta 01/03**

Elegí los principios FAIR entre las opciones siguientes.  
Seleccioná todas las que correspondan.

- Reproducible  
- Reusable  
- Responsible  
- Findable  
- Interactive  
- Interoperable  
- Interspersed  
- Accessible  
- Authorizable  

**Pregunta 02/03**

¿Cuáles de las siguientes acciones pueden ayudar a que tus datos sean FAIR?  
Seleccioná todas las que correspondan.

- Obtener una licencia para tus datos  
- Hacer que tus metadatos sean accesibles solo mientras tus datos lo sean  
- Obtener un PID para tus datos  

**Pregunta 03/03**

¿Cuáles de las siguientes opciones son ejemplos de repositorios?  
Seleccioná todas las que correspondan.

- Zenodo  
- Dataverse  
- Dryad  
- Google  

## Referencias citadas

- Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship. *Scientific Data* 3:160018, [doi:10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18) (enlace externo) (2016).
