# Lección 3: Herramientas para Datos Abiertos

## Contenidos

-   [Introducción a los Datos Abiertos](#introducci%C3%B3n-a-los-datos-abiertos)
-   [Principios FAIR](#principios-FAIR)
-   [Herramientas para ayudar con la planificación de la creación de Datos Abiertos](#herramientas-para-ayudar-con-la-planificaci%C3%B3n-de-la-creaci%C3%B3n-de-datos-abiertos)
-   [Herramientas para ayudar con el uso y manejo de Datos Abiertos](#herramientas-para-ayudar-con-el-uso-y-manejo-de-datos-abiertos)
-   [Lección 3: Resumen](#lecci%C3%B3n-3-resumen)
-   [Lección 3: Evaluación](#lecci%C3%B3n-3-evaluaci%C3%B3n)


## Panorama general

Esta lección trata sobre los conceptos, consideraciones y herramientas para generar datos y resultados. Comienza con una mirada centrada en los principios FAIR y en su aplicación a los datos. La lección incluye una introducción a los planes, las herramientas, los formatos de datos y otras consideraciones asociadas a la creación de datos y a la difusión de los resultados de dichos datos. Además, la lección incluye ejemplos de repositorios y comunidades de datos abiertos. Conocer estos conceptos y herramientas te facilitará hacer que tu propia investigación sea accesible y reusable.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Definir los diferentes tipos de datos científicos.
- Definir qué significa el acrónimo FAIR y explicar cómo contribuye a compartir datos abiertos.
- Identificar prácticas de gestión de datos y herramientas para encontrar datos en repositorios.
- Enumerar y explicar los recursos que se usan habitualmente al generar datos,  incluyendo los formatos de datos, la inspección de datos y la evaluación del ajuste de los datos a los principios FAIR.

## Introducción a los Datos Abiertos

Los datos son una parte central de la investigación científica y tiene sentido que así sea. Informan sobre las herramientas que usamos, las historias que leemos y las decisiones que tomamos a diario.

Por ejemplo, el [Servicio de Gestión de Emergencias de Copernicus](https://emergency.copernicus.eu/) (en inglés, Copernicus Emergency Management Service) (enlace externo), de Acceso Abierto e implementado por la Comisión Europea, produce Datos Abiertos 24/7, que son recogidos por los satélites de la Agencia Espacial Europea (ESA, por las siglas en inglés de European Space Agency) y la NASA para producir mapas que informan sobre los esfuerzos en la preparación y la respuesta a desastres en todo el mundo. Este es sólo un ejemplo entre muchos otros que demuestran el valor de los datos, particularmente los datos públicos y abiertos, en nuestra vida cotidiana y en el bien público.

Los datos compartidos abiertamente en investigación científica aportan un valor enorme a la comunidad científica y, más allá, a comunidades pequeñas y aisladas y a grandes centros urbanos. Antes de avanzar hacia el impacto amplio de los datos, veamos primero qué son los datos en el contexto de la investigación científica. En particular, vamos a hablar de la definición y las características de los datos abiertos.

### ¿Qué son los datos?

Los datos científicos son cualquier tipo de información que se recopila, se observa o se crea en el contexto de una investigación. Pueden ser:

- Primarios -- Sin procesar, de mediciones o instrumentos
- Secundarios -- Procesados a partir de análisis e interpretaciones secundarias.
- Publicados -- Formato final disponible para uso y reutilización.
- Metadatos -- Datos sobre tus datos.

Es todo aquello que necesitas para validar o reproducir los resultados de tu investigación, así como lo necesario para la comprensión y el manejo de los datos.

En las siguientes secciones vas a ver distintas formas de asegurar que los datos sean plenamente utilizados y accesibles para la mayor cantidad de personas. Estas buenas prácticas se centran en marcos de trabajo comunitarios y herramientas que ayudan a quienes investigan a administrar y compartir Datos Abiertos.

## Principios FAIR

<img src="../images/media/image28.png" style="width:100%;height:auto;" />

Al igual que al conducir en una carretera, si todo el mundo sigue las normas acordadas, todo va mucho mejor. Las reglas no necesitan ser exactamente las mismas en todas las regiones, pero sí deben compartir prácticas comunes basadas en información sobre seguridad y eficiencia.

Por ejemplo, puede que conduzcas en el lado izquierdo o en el lado derecho de la carretera. Los dos están bien; esos detalles deben decidirse en las diferentes comunidades. Sin embargo, existen pautas generales compartidas por comunidades de todo el mundo, como la regla de conducir en la carretera y no en la acera, usar una señal de giro cuando sea apropiado, respetar los semáforos que dirigen el tráfico en los cruces de calles y seguir los límites de velocidad. Algunas comunidades pueden aplicar reglas de manera más estricta que otras, o aplicarlas de forma diferente, pero estas pautas ayudan a todo el mundo a moverse de forma segura mediante un acuerdo común sobre cómo conducir por las carreteras. 

Para los datos científicos, estas pautas se publicaron en 2016 por Wilkinson et al. y se conocen como los principios FAIR (Findable, Accessible, Interoperable, Reusable). Hacen exactamente lo que su nombre sugiere: permiten que otras personas (y vos mismo más adelante) encuentren, obtengan, comprendan y usen correctamente los datos.

**Fáciles de encontrar (Findable)**

Para que los datos sean [fáciles de encontrar](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/) (enlace externo):

- Se asigna a los datos y a los resultados un identificador único y persistente a nivel global.
- Los datos se describen mediante metadatos enriquecidos.
- Los metadatos incluyen, de forma clara y explícita, el identificador de los datos que describen.
- Los datos y los resultados se registran o se indexan en un recurso que permite realizar búsquedas.

Tecnología actual que lo permite:

- [Esquema de metadatos de DataCite (en inglés, DataCite's Metadata Schema)](https://schema.datacite.org/) (enlace externo).
- PIDs: siglas en inglés de Persistent IDentifiers, Identificadores persistentes (detalles adicionales en las siguientes secciones)
  - [Identificador de objeto digital (en inglés, Digital Object Identifier, DOI)](https://www.doi.org/) (enlace externo): Un campo de nivel superior y obligatorio en los metadatos de cada registro: para datos, código, publicaciones.
  - [Identificador abierto de investigación y contribuyente (en inglés, Open Research and Contributor ID, ORCiD)](https://orcid.org/) (enlace externo): un código que identifica de manera unívoca a las personas autoras y contribuyentes de productos de investigación y comunicación académica.

**Accesibles (Accessible)**

Para que los datos sean [Accesibles](https://www.go-fair.org/fair-principles/metadata-retrievable-identifier-standardised-communication-protocol/) (enlace externo):

- Los datos y los resultados son recuperables mediante sus identificadores usando un protocolo de comunicación estandarizado.
- El protocolo es abierto, libre y universalmente implementable.
- El protocolo permite un procedimiento de autenticación y autorización cuando sea necesario.
- Los datos y los resultados son accesibles al público y están bajo licencia de dominio público.
 - Los metadatos son accesibles, incluso cuando los datos ya no están disponibles. Los datos y los metadatos se conservarán durante toda la vida del repositorio.
 - Los metadatos se almacenan en servidores de bases de datos de alta disponibilidad.

Tecnología actual que lo permite:

- [Protocolo de transferencia de archivos (en inglés, File Transfer Protocol, FTP)](https://www.w3.org/Protocols/rfc959/) (enlace externo) y Protocolo seguro de transferencia de archivos (File Transfer Protocol Secure, FTPS)
- [Protocolo de transferencia de hipertexto (en inglés, Hypertext Transfer Protocol, HTTP)](https://www.w3.org/Protocols/) (enlace externo) y Protocolo seguro de transferencia de hipertexto (Hypertext Transfer Protocol Secure, HTTPS)

Tené en cuenta que Microsoft Exchange Server y Skype son ejemplos de protocolos propietarios. Como siempre, es necesario equilibrar la accesibilidad con cuestiones de seguridad, lo que puede afectar el protocolo elegido.

**Interoperables (Interoperable)**

Para que los datos sean [interoperables](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/) (enlace externo):

- Los datos emplean un lenguaje formal, accesible, compartido y ampliamente aplicable para la representación del conocimiento.
- Los datos usan un formato conocido y estandarizado.
- Los datos utilizan vocabularios que siguen los principios FAIR.
- Los datos incluyen referencias calificadas a otros (meta)datos.

Tecnología actual que lo permite:

- [Zenodo](https://zenodo.org/) (enlace externo) usa [JSON Schema](https://json-schema.org/) (enlace externo) como representación interna de los metadatos y permite exportar a otros formatos populares, como [Dublin Core](https://www.dublincore.org/) (enlace externo) o [MARCXML](https://www.loc.gov/marc/marcxml.html) (enlace externo).
- Para ciertos términos se recurre a vocabularios abiertos externos, por ejemplo: licencias en [Open Definition](https://opendefinition.org/) (enlace externo), financiadores en [FundRef](https://www.crossref.org/services/funder-registry/) (enlace externo) y proyectos con financiación en [OpenAIRE](https://explore.openaire.eu/) (enlace externo).
- Cada referencia a una pieza de datos externa está calificada con una URL que puede resolverse.

**Reusables (Reusable)**

Para que los datos sean [reusables](https://www.go-fair.org/fair-principles/r1-metadata-richly-described-plurality-accurate-relevant-attributes/) (enlace externo):

- Los datos se describen en detalle, con una pluralidad de atributos precisos y relevantes.
- Los datos se publican con una licencia de uso de datos clara y accesible.
- Los datos se asocian a una procedencia detallada.
- Los datos cumplen con los estándares comunitarios relevantes para el dominio.

Tecnología actual que lo permite:

- El registro de metadatos contiene como mínimo los campos obligatorios de [DataCite](https://schema.datacite.org/) (enlace externo), con la opción de incluir campos recomendados adicionales de DataCite y enriquecimientos propios de Zenodo.
- [Zenodo](https://zenodo.org/) (enlace externo) no es un repositorio específico de un dominio, pero al cumplir con el esquema de metadatos de DataCite (en inglés, DataCite Metadata Schema), los metadatos se ajustan a uno de los estándares interdominio más amplios disponibles.

(Wilkinson et al., 2016)

Estas pautas son de alto nivel y, al igual que la Ciencia Abierta, presentan matices en su aplicación. A veces se requiere un esfuerzo grupal y/o un proceso de producción y/o financiación prolongado para que los datos y los resultados sean FAIR. Para otros conjuntos de datos podría ser más sencillo. Se necesita un Plan de Gestión de Datos bien coordinado para cumplir plenamente con los principios FAIR y los detalles de ello se discutirán más en profundidad en el Módulo 3 - Datos Abiertos.

## Herramientas para ayudar con la planificación de la creación de Datos Abiertos

### Plan de Gestión de Datos

La lección anterior describe los requisitos de un Plan de Gestión de Datos (PGD, en inglés, Data Management Plan, DMP). Debajo encontrarás dos recursos científicos abiertos para empezar a crear un Plan de Gestión de Datos:

**DMPTool**

[DMPTool](https://dmptool.org/) (enlace externo) asiste a quienes investigan en EE.UU. mediante una plantilla que recopila los requisitos de una determinada financiadora para solicitudes de propuestas (en inglés, requests for proposals, RFP). La herramienta DMPTool también publica PGD abiertos de otros proyectos financiados que pueden servir de referencia para mejorar los propios. El Organizador de Gestión de Datos de Investigación (OGDI, por sus siglas en inglés, Research Data Management Organizer, RDMO) permite a las instituciones alemanas y sus equipos de investigación planificar y llevar a cabo la gestión de datos de investigación.

**ARGOS**

[ARGOS](https://argos.openaire.eu/home) (enlace externo) se usa para planificar las actividades de gestión de datos de investigación de proyectos financiados a nivel nacional y europeo (por ejemplo, Horizon Europe, CHIST-ERA, la Fundación Portuguesa de Ciencia y Tecnología - FCT). ARGOS produce y publica PGD compatibles con prácticas FAIR y procesables por máquina, que contienen enlaces a otros productos, por ej. publicaciones-datos-software, y minimiza el esfuerzo de crear PGD desde cero introduciendo automatizaciones en el proceso de escritura. OpenAIRE proporciona una guía para crear PGD.

### Repositorios de datos

Un repositorio de datos es un espacio digital para alojar, curar y compartir resultados de investigación. Los repositorios de datos se usaron originalmente para satisfacer las necesidades de las comunidades de investigación. Ejemplos de repositorios de datos incluyen:

- [Instalación de Datos de Física Espacial de la NASA (NASA Space Physics Data Facility)](https://spdf.gsfc.nasa.gov/): un repositorio permanente de datos de física espacial de misiones pasadas y actuales.
- [Biblioteca Digital de Recursos de Heliofísica de la NASA (NASA Heliophysics Digital Resource Library)](https://hdrl.gsfc.nasa.gov/): ofrece Acceso Abierto a miles de conjuntos de datos de misiones heliosfísicas actuales e históricas de la NASA.
- [Centro de Investigación del Archivo Científico de Astrofísica de Alta Energía de la NASA (NASA High Energy Astrophysics Science Archive Research Center, HEASARC)](https://heasarc.gsfc.nasa.gov/): el archivo principal para misiones de la NASA (y de otras agencias espaciales) que estudian la radiación electromagnética asociada a fenómenos cósmicos extremadamente energéticos. Incluye datos obtenidos mediante misiones espaciales, globos y observaciones desde tierra.
- [Sistema de Datos Planetarios de la NASA (NASA Planetary Data System, PDS)](https://pds.nasa.gov/): archivo de largo plazo de productos de datos digitales provenientes de misiones planetarias de la NASA y de otras adquisiciones de datos en vuelo y en tierra, incluidas experiencias de laboratorio.
- [Centro de Datos y Aplicaciones Socioeconómicas de la NASA (NASA Socioeconomic Data and Applications Center, SEDAC)](https://www.earthdata.nasa.gov/centers/sedac-daac): se centra en archivar y distribuir datos sobre las interacciones humanas con el ambiente.
- [Banco de Datos de Proteínas RCSB (RCSB Protein Data Bank)](https://www.rcsb.org/) (enlace externo): es un repositorio de datos que cataloga estructuras tridimensionales de proteínas y de ácidos nucleicos.
- [GenBank (GenBank)](https://www.ncbi.nlm.nih.gov/genbank/) (enlace externo): del Instituto Nacional de Salud de EEUU (en inglés, National Institutes of Health), utiliza una base pública de secuencias genéticas anotadas de ácidos nucleicos.
- [Repositorio de Datos de Imágenes (Image Data Resource)](https://idr.openmicroscopy.org/) (enlace externo): repositorio público de conjuntos de datos de microscopía bioimagen de estudios publicados.
- [Archivo Público de Imágenes de Microscopía Electrónica (Electron Microscopy Public Image Archive)](https://idr.openmicroscopy.org/) (enlace externo): recurso público de imágenes crudas de crio-microscopía electrónica (crio-EM).
- [OpenNeuro (OpenNeuro)](https://openneuro.org/) (enlace externo): plataforma abierta para validar y compartir datos de neuroimagen; ofrece herramientas que facilitan el acceso, la búsqueda y el análisis de conjuntos de datos anotados.

Las herramientas de Ciencia Abierta, como los repositorios de datos, deben implementar los principios FAIR, especialmente en lo que respecta a la atribución de identificadores persistentes (por ejemplo, DOI), la anotación de metadatos y la capacidad de ser leídos por computadoras.

Más ejemplos de repositorios de datos y otras herramientas de Ciencia Abierta incluyen, entre otros:

**Zenodo**

[Zenodo](https://zenodo.org/) (enlace externo) es un ejemplo de repositorio de datos que permite cargar datos de investigación y crear un DOI. Su popularidad entre la comunidad investigadora se debe a la sencillez de su interfaz, al apoyo a la gestión comunitaria y a la función que permite a los investigadores depositar diversos tipos de resultados de investigación, desde conjuntos de datos e informes hasta publicaciones, software y contenidos multimedia.

**Dataverse**

[The Dataverse Project](https://dataverse.org/) (enlace externo) es una aplicación en línea de Código Abierto para compartir, preservar, citar, explorar y analizar datos de investigación, disponible gratuitamente para investigadores de todas las disciplinas del mundo.

**Dryad**

[The Dryad Digital Repository](https://datadryad.org/) (enlace externo) es un recurso en línea curado que facilita que los datos de investigación sean fáciles de encontrar, reusar libremente y citables. A diferencia de las herramientas mencionadas anteriormente, opera bajo un esquema de membresía para organizaciones, como instituciones de investigación y editores.

**DataCite**

[DataCite](https://datacite.org/) (enlace externo) es una organización global sin fines de lucro que proporciona DOI a datos de investigación y otros resultados de investigación mediante suscripción.

**OSF**

[Open Science Framework](https://osf.io/) (enlace externo) es una plataforma de Código Abierto para compartir, administrar y colaborar en investigación.

Los servicios de datos y los recursos de apoyo a la investigación requieren una infraestructura sólida basada en la colaboración. Un ejemplo de iniciativa sobre infraestructuras de servicios de datos procede de la [EUDAT infraestructura de datos colaborativa (en inglés, Collaborative Data Infrastructure)](https://www.eudat.eu/) (enlace externo), una red sostenida de más de 20 organizaciones europeas de investigación.

Las empresas privadas también alojan y mantienen herramientas en línea para compartir datos y archivos de investigación. Por ejemplo, Figshare es un servicio de acceso libre y abierto operado por empresas privadas. Proporciona DOI para todo tipo de archivos y, recientemente, desarrolló un modelo de publicación restringida para adaptarse a los requisitos de derechos de propiedad intelectual. Permite compartir los productos sólo dentro de un grupo personalizado de Figshare (podría ser tu equipo de investigación) o con personas usuarias en un rango de IP específico. Los avances adicionales incluyen la integración con repositorios de código, como GitHub, GitLab y Bitbucket.

Se pueden encontrar más repositorios de datos en el [Registro de Repositorios de Datos de Investigación (en inglés, Registry of Research Data Repositories) ](https://www.re3data.org/) (enlace externo). [OpenAIRE](https://explore.openaire.eu/search/find/dataproviders) (enlace externo) es un motor de búsqueda alojado que también ofrece una potente función de búsqueda de datos y de repositorios. Dispone de un filtro por país, tipo y área temática, y permite la descarga de datos.

La cantidad de datos, repositorios y políticas diferentes puede resultar abrumadora. Si tienes dudas sobre qué repositorio es el más adecuado para ti, consulta a las personas responsables de la biblioteca, quienes gestionan los datos y/o administran los datos de tu institución, o consulta en tu disciplina específica u en otra comunidad de práctica.

### Actividad 3.1: Explora Zenodo y regístrate

Explora los repositorios abiertos para familiarizarte con su estructura y con la información disponible sobre sus productos. El repositorio más popular actualmente es Zenodo. Ve el siguiente vídeo de 4,5 minutos para obtener una visión general de Zenodo y, a continuación, regístrate para crear una cuenta. Puedes usar tu ORCID para inscribirte si ya tienes uno o lo creaste en la lección anterior.

[Ver video](https://www.youtube.com/watch?v=gEnq_RpVdAM) (enlace externo)

### Herramientas para ayudar con el uso y manejo de Datos Abiertos

### Formato de los datos

Un formato de archivo útil puede ser leído en memoria por algún software. Piensa en el formato como una herramienta para hacer accesibles tus datos.

Los formatos fáciles de usar tienen:

- Una estructura simple y fácil de entender.
- Una especificación clara y abierta del formato que, idealmente, no esté vinculada a un producto de software específico.
- Bibliotecas o librerías de software abiertas y APIs que pueden analizar el formato..

Los formatos que se consideran más interoperables según los criterios anteriores son los valores separados por comas (CSV), el lenguaje de marcado extensible (XML) y la notación de objetos JavaScript (JSON). Otros formatos habituales para las personas investigadoras son los basados en matrices binarias, como Network Common Data Form (NetCDF), Hierarchical Data Format (HDF), Geotiff, Flexible Image Transport System (FITS) y otros formatos diseñados para el almacenamiento y el acceso en la nube, como [Zarr](https://zarr.dev/) (enlace externo), [Cloud Optimized GeoTIFF](https://www.cogeo.org/) (enlace externo) y [Parquet](https://parquet.apache.org/) (enlace externo). Muchos de estos formatos cuentan con herramientas que verifican que los conjuntos de datos cumplen con los estándares y son legibles.

### Inspección de datos

Los formatos de datos modernos permiten almacenar mucho más que datos puntuales. Una vez que se adoptan estos estándares (por ejemplo, NetCDF), la búsqueda de contenidos en cada archivo puede ser asistida por una variedad de herramientas que, juntas, ayudan a mapear los datos primarios y/o a mostrar los metadatos asociados. Existen varias herramientas para inspeccionar datos, demasiadas como para mencionarlas todas aquí.

Herramientas recomendadas para comenzar:

**CSV, XML, JSON**  
Los archivos con estos formatos pueden abrirse con los editores de texto más comunes. Hay algunas herramientas que pueden crear vistas de los archivos que son más fáciles de usar, como:

- CSV: Hojas de cálculo de Microsoft Excel y de Google.
- XML: La mayoría de los navegadores de Internet y cualquier editor de texto como el Bloc de notas, Microsoft Word, LibreOffice o Google Docs.
- JSON: [http://json.parser.online.fr/](http://json.parser.online.fr/) (enlace externo) y [https://jsonformatter.org/json-pretty-print](https://jsonformatter.org/json-pretty-print) (enlace externo).

**NetCDF, HDF, FITS**  
Estos archivos requieren herramientas de software especiales para ver sus contenidos. Muchas de estas herramientas también permiten visualizar los datos.

- NetCDF y HDF: la mayoría de los archivos se visualizan fácilmente usando software de Código Abierto, como la librería [Xarray](https://docs.xarray.dev/en/stable/) (enlace externo) en Python o la biblioteca [ncdf4](https://cran.r-project.org/web/packages/ncdf4/index.html) (enlace externo) en R.  
- FITS: hay muchas opciones de software que permiten visualizar y trabajar con este formato de archivo. En [https://fits.gsfc.nasa.gov/fits_viewer.html](https://fits.gsfc.nasa.gov/fits_viewer.html) se ofrece una lista exhaustiva en inglés.

**Zarr, COG, Parquet**  
Estos archivos requieren herramientas de software específicas para ver su contenido. Muchas de estas herramientas también permiten visualizar los datos.

- Zarr: los archivos se visualizan fácilmente usando software de Código Abierto, como las librerías [Xarray](https://docs.xarray.dev/en/stable/) (enlace externo) en Python o con la biblioteca [Pizzarr](https://github.com/keller-mark/pizzarr) (enlace externo) en R.  
- COG: los archivos se visualizan usando la librería [rioXarray](https://corteva.github.io/rioxarray/html/index.html) (enlace externo) en Python o [terra](https://cran.r-project.org/web/packages/terra/index.html) (enlace externo) en R.  
- Parquet: los archivos se visualizan usando software de Código Abierto, como las librerías [Pandas](https://pandas.pydata.org/) (enlace externo) en Python o [Arrow](https://arrow.apache.org/docs/r/reference/read_parquet.html) (enlace externo) en R.

### Evaluación FAIR

¿Cómo saber cuán “FAIR” es tu conjunto de datos? Dos grupos, [FAIRsharing.org](https://fairsharing.org/) (enlace externo) y la [Research Data Alliance (RDA)](https://www.rd-alliance.org/) (enlace externo) (en español, Alianza para los Datos de Investigación), han desarrollado las [métricas FAIR](https://www.nature.com/articles/sdata2018118) (enlace externo) y el [Modelo de Madurez de Datos FAIR](http://dx.doi.org/10.15497/RDA00050) (enlace externo) para ayudar a evaluar que tan "FAIR" es un conjunto de datos. Existen herramientas de Código Abierto para ayudar a quienes investigamos a evaluar sus datos:

**Australian Research Data Commons (ARDC)**  
#### FAIR Data Self-Assessment Tool  
[FAIR Data Self-Assessment Tool](https://ardc.edu.au/resource/fair-data-self-assessment-tool/) (enlace externo) es un proceso manual que consiste en un cuestionario en línea.

Ideal para:  
- Desencadenar debates en las fases iniciales de estudio, considerando la implementación de los principios FAIR.
- Identificar áreas de mejora.

Los resultados incluyen:  
- Barra de progreso para cada principio FAIR.  
- Barra de progreso agregada a todos los principios.

**FAIR-Checker**  
[FAIR-Checker](https://fair-checker.france-bioinformatique.fr/) (enlace externo) Herramienta automatizada a través del sitio web o API. 

Ideal para:
- Escalabilidad a muchos conjuntos de datos.
- Identificar áreas de mejora.

Los resultados incluyen:  
- Gráfico con puntajes y detalles.

**F-UJI**  
[F-UJI](https://www.f-uji.net/) (enlace externo) Herramienta automatizada a través del sitio web o API. 

Ideal para:
- Escalabilidad a muchos conjuntos de datos.
- Documentación detallada de la herramienta.

Los resultados incluyen:  
- Informe y gráfico con puntajes y detalles.

**FAIR Evaluation Services**  
[FAIR Evaluation Services](https://fairsharing.github.io/FAIR-Evaluator-FrontEnd/#!/) (enlace externo) Herramienta automatizada a través del sitio web o API. 

Ideal para:
- Escalabilidad a muchos conjuntos de datos.
- Crear evaluaciones personalizadas.

Los resultados incluyen:  
- Informe detallado y gráfico.

## Lección 3: Resumen

En esta lección has aprendido:

- Los diferentes tipos de datos científicos, incluidos los primarios, secundarios, publicados y metadatos.
- Una lista de prácticas de Ciencia Abierta para aplicar los principios FAIR que hacen que los datos y resultados sean fácilmente accesibles a muchas personas.
- Herramientas digitales que facilitan la planificación, creación e intercambio de Datos Abiertos.

## Lección 3: Evaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

**Pregunta 01/03**

Selecciona los principios FAIR de la siguiente lista. 
Elige todas las opciones que correspondan.

- Reproducibilidad
- Reusable
- Responsable
- Fácil de encontrar
- Interactivo
- Interoperable
- Intercalado
- Accesible
- Autorizable 

**Pregunta 02/03**

¿Cuál de las siguientes opciones puede ayudar a que tus datos sean FAIR? 
Selecciona todas las opciones que correspondan.

- Obtener una licencia para tus datos  
- Hacer que tus metadatos sean accesibles solo mientras tus datos lo sean  
- Obtener un PID para tus datos  

**Pregunta 03/03**

¿Cuáles de las siguientes opciones son ejemplos de repositorios?  
Selecciona todas las opciones que correspondan.

- Zenodo  
- Dataverse  
- Dryad  
- Google  

## Referencias

- Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship. *Scientific Data* 3:160018, [doi:10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18) (enlace externo) (2016).
