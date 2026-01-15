# Lección 3: Hacer Datos Abiertos

## Contenidos

- [Planificar para Datos Abiertos](#planificar-para-datos-abiertos)
- [Seleccionar formatos de datos y herramientas para la interoperabilidad](#seleccionar-formatos-de-datos-y-herramientas-para-la-interoperabilidad)
- [Hacer que los datos sean reusables mediante la documentación](#hacer-que-los-datos-sean-reusables-mediante-la-documentaci%C3%B3n)
- [Hacer que los datos sean reusables mediante las licencias](#hacer-que-los-datos-sean-reusables-mediante-las-licencias)
- [Lección 3: Resumen](#lecci%C3%B3n-3-resumen)
- [Lección 3: Evaluación](#lecci%C3%B3n-3-evaluaci%C3%B3n)

## Descripción general

¿Cómo te aseguras de que tus propios conjuntos de datos sean abiertos y reutilizables? En esta lección aprenderás los criterios y las tareas necesarias para que esto suceda. Primero aprenderás a crear un plan de gestión de datos para tu proyecto, lo que implica contemplar elementos de datos abiertos. Luego aprenderás cómo seleccionar formatos de datos abiertos, así como cómo incluir metadatos, archivos README y control de versiones para tus datos. Esta lección concluirá con una discusión sobre licencias abiertas para datos.

## Objetivos de aprendizaje

Luego de completar esta lección, deberías poder:

- Evaluar y seleccionar formatos de datos abiertos para tu trabajo.
- Agregar documentación que permita a otros investigadores evaluar la relevancia de tus datos para sus proyectos. Esto incluye metadatos, archivos README y control de versiones.
- Enumerar dos licencias abiertas comunes utilizadas para conjuntos de datos.

## Planificar para Datos Abiertos

Una buena práctica al comenzar tu recorrido de datos abiertos es crear un plan de gestión de datos (DMP). Este documento describe cómo gestionarás, preservarás y liberarás tus datos durante y después de un proyecto de investigación. Elementos comunes de los DMP relevantes para datos abiertos incluyen una descripción de lo siguiente:

|  |  |
|---|---|
| ¿Qué? | Formatos de datos y (cuando corresponda) estándares |
| ¿Cuándo? | Cuándo y si compartir datos |
| ¿Dónde? | Los repositorios previstos para datos archivados |
| ¿Cómo? | Cómo el plan habilita la reutilización de los datos |
| ¿Quién? | Roles y responsabilidades de los miembros del equipo para implementar el DMP |

En esta lección cubriremos algunos pasos comúnmente practicados para producir datos. En particular, nos enfocaremos en el "qué" de producir datos. Esto abarca qué formatos de datos deberías usar y qué estándares seguir para que los datos sean lo más abiertos y utilizables posible.

Retomaremos los DMP en la Lección 5, "De la teoría a la práctica". La Lección 5 proporciona ejemplos de DMP, plantillas que puedes usar en el futuro y una oportunidad para revisar un DMP real.

## Seleccionar formatos de datos y herramientas para la interoperabilidad

### Consideraciones sobre formatos de datos

Los formatos de datos preferidos son aquellos respaldados por la comunidad, legibles por máquinas, no propietarios, modificables y abiertos. ¡Puede parecer que existen tantos formatos de datos como tipos distintos de datos! Al pensar en la selección de un formato de datos, considera lo siguiente:

- ¿El formato es compatible con el tipo, la forma y el tamaño de tus datos?
- ¿El formato de datos tiene soporte adecuado para metadatos?
- ¿Existen herramientas disponibles para crear los archivos de datos?
- ¿Se requieren herramientas especializadas para leer el formato de datos?
- ¿El formato de datos se usa habitualmente en tu campo? Los estándares comunitarios aseguran compatibilidad, interoperabilidad y facilidad de uso al intercambiar o compartir datos entre investigadores u organizaciones de una misma comunidad científica.

<img src="../images/media/image31_es.png" style="width:100%;height:auto;" />
Crédito de la imagen: NASA

Investiga si tu agencia financiadora, institución y(o) repositorio de datos tiene requisitos adicionales u orientaciones sobre formatos de datos.

### Formatos de datos no abiertos

Un formato de datos no abierto (no soportado y cerrado(propietario)) se refiere a un formato de archivo que no es de libre acceso, no está estandarizado o no es ampliamente soportado por distintas aplicaciones de software. Algunos ejemplos de formatos de datos cerrados(propietarios) incluyen:

- **Adobe Photoshop (.psd):** El formato de archivo propietario predeterminado de Adobe Photoshop, un software popular de edición de imágenes.
- **AutoCAD Drawing (.dwg):** Un formato de datos propietario utilizado para diseño asistido por computadora.
- **Microsoft Word (.doc)(.docx):** Un formato de archivo propietario utilizado para almacenar documentos de procesamiento de texto.

Las aplicaciones de software que pueden leer pero no crear datos en formato DOC, PSD o DWG generalmente no soportan completamente todas las funciones, capas, especificaciones y mecanismos internos del archivo original.

Algunos desafíos de usar datos en formatos no abiertos incluyen:

- Dificultades para abrir el archivo debido a problemas de compatibilidad.
- Necesidad de instalar software adicional o conversores, lo que genera frustración e inconvenientes.
- El contratiempo inicial puede disminuir el entusiasmo por usar tus datos.
- Convertir los datos a un formato universal puede provocar que formatos o características específicas no se traduzcan bien, haciendo que los datos pierdan parte de su valor.
- La capacidad de compartir datos en formatos propietarios se verá limitada si los repositorios comunes de tu campo no soportan ese formato.

### Ejemplos de formatos de datos abiertos

Algunos ejemplos de formatos de datos abiertos incluyen:

*Selecciona cada tarjeta para ver más información.*

|  |  |
|---|---|
| Valores separados por comas (CSV) | Por su simplicidad, legibilidad, compatibilidad y facilidad de intercambio de datos. |
| Formato de Datos Jerárquico (HDF) | Para almacenamiento y recuperación eficientes de datos, compresión y soporte multidimensional. |
| Formato Común de Datos en Red (NetCDF) | Por ser auto-descriptivo y portable, permitir sub-selección eficiente de datos (extraer porciones específicas de grandes conjuntos de datos), estandarización e interoperabilidad. |
| Modelo Investigación-Estudio-Ensayo (ISA) para estudios en ciencias de la vida | Para organización estructurada de datos, integración de datos e interoperabilidad entre experimentos, reproducibilidad y transparencia. |
| Sistema Flexible de Transporte de Imágenes (FITS) | Como estándar para datos astronómicos, metadatos y encabezados de imagen flexibles y extensibles, compresión eficiente de datos y archivado de grandes conjuntos de datos. |
| Formato Común de Datos (CDF) | Por ser auto-descriptivo, legible en múltiples sistemas operativos, lenguajes de programación y entornos de software, soportar datos multidimensionales y metadatos. |

Al adoptar estándares abiertos, quienes producen datos pueden evitar barreras innecesarias y maximizar las posibilidades de que los datos sean útiles para sus comunidades científicas.

## Hacer que los datos sean reutilizables mediante documentación

### Agregar documentación y metadatos para la reutilización

Los metadatos y la documentación describen los datos para que nosotros y otras personas podamos usarlos y comprenderlos mejor. Aunque metadatos y documentación están relacionados, existe una distinción importante. Los metadatos son estructurados, estandarizados y legibles por máquinas. La documentación no es estructurada y puede adoptar cualquier formato (a menudo un archivo de texto que acompaña a los datos).

Para comprender mejor la documentación y los metadatos, tomemos el ejemplo de una receta en línea. Muchas recetas comienzan con una descripción extensa y la historia de la receta, y quizás consejos de cocina o repostería, antes de listar ingredientes e instrucciones paso a paso.

- Los ingredientes y las instrucciones son como los metadatos. Pueden indexarse y buscarse mediante Google y otros motores de búsqueda.
- El texto descriptivo que incluye contexto e información de fondo sobre la receta es como la documentación. Es más libre y no estandarizado.

Ya discutimos los metadatos anteriormente en este módulo, pero son lo suficientemente importantes como para repetirnos un poco. También discutiremos otros tipos de documentación, como los archivos README.

### Metadatos: para personas y máquinas

Los metadatos pueden facilitar la evaluación de la calidad de un conjunto de datos y el intercambio de datos al responder preguntas clave. También son la principal forma en que los usuarios encontrarán información sobre tu conjunto de datos. Incluyen información clave sobre aspectos como:

- Cómo se recolectaron y procesaron los datos.
- Qué variables(parámetros) se incluyen en el conjunto de datos.
- Qué variables se incluyen y con qué variables están relacionadas.
- Quién recolectó los datos (equipo científico, organización, etc.).
- Cómo y dónde encontrar los datos (por ejemplo, DOI).
- Cómo citar los datos.
- Qué región espacio-temporal(periodo) cubren los datos.
- Cualquier información legal, normativa o de estándares sobre los datos.

### ¿Por qué agregar metadatos?

Los metadatos mejoran la capacidad de búsqueda y encontrabilidad de los datos al permitir potencialmente que tanto personas como máquinas lean e interpreten conjuntos de datos. Los beneficios de crear metadatos sobre tus datos incluyen:

- Ayudan a que quienes usan los datos comprendan qué son los datos y si(cómo) pueden usarlos(citarlos).
- Ayudan a que los usuarios encuentren los datos, en particular cuando los metadatos son legibles por máquinas y estandarizados.
- Pueden facilitar el análisis mediante herramientas de software que interpretan metadatos estandarizados (por ejemplo, Xarray).

Para que los metadatos sean legibles por máquinas, deben estar estandarizados. Observa un ejemplo de un estándar aceptado por la comunidad para etiquetar conjuntos de datos climáticos con las [Convenciones CF](http://cfconventions.org/) (enlace externo).

Existen también paquetes de software que pueden leer metadatos y mejorar de manera significativa la experiencia de uso. Por ejemplo, [Xarray](https://docs.xarray.dev/en/stable/index.html) (enlace externo) es un paquete de software de código abierto desarrollado por la comunidad, ampliamente utilizado en los campos climático y biomédico, entre muchos otros. Según su sitio web, "Xarray hace que trabajar con arreglos multidimensionales etiquetados en Python sea simple, eficiente y agradable". Es la parte de "etiquetados" donde entran en juego los metadatos estandarizados. Xarray puede interpretar nombres de variables y dimensiones sin intervención del usuario, lo que hace que el flujo de trabajo sea más sencillo y menos propenso a errores (por ejemplo, no es necesario recordar qué eje es "tiempo", basta con llamar al eje con la etiqueta "tiempo").

Existen muchos estándares para campos y estructuras de metadatos que describen información general de los datos. Usa un estándar de tu dominio cuando corresponda, o aquel que sea solicitado por tu repositorio de datos.

### Buenas prácticas para etiquetado de metadatos

Metadatos útiles e informativos:

- Usan estándares que son comúnmente utilizados en tu campo.
- Cumplen con los Principios FAIR.
- Son lo más descriptivos posible.
- Son auto-descriptivos.

Recuerda: cuanto más metadatos agregues, más fácil será para quienes usen tus datos hacerlo de manera efectiva. En caso de duda:

- Busca y cumple con estándares del repositorio(la comunidad).
- Investiga recursos de ciencia abierta en línea sobre metadatos (por ejemplo, [The Turing Way](https://book.the-turing-way.org/reproducible-research/rdm/rdm-metadata)) (enlace externo).

**Anexo de etiquetado de metadatos de la NASA**

SPD-41a requiere campos de metadatos que validen las conclusiones científicas de las publicaciones. Los metadatos deberían:

- Ser robustos, cumplir con estándares y describir los datos de forma clara y explícita.
- Tener capacidad de replicación y(o) poder combinarse en distintos contextos.
- Incluir información sobre cómo se recolectaron los datos (por ejemplo, qué equipos(instrumentos) se usaron).
- Incluir información sobre qué variables(parámetros) se incluyeron en este conjunto de datos.

### Documentación complementaria

Al producir tus datos, además de agregar metadatos, es una buena práctica crear un documento de referencia para quienes los usen. Este documento puede presentarse como un archivo README, una guía de usuario o un inicio rápido (o incluso los tres).

Los archivos README y otros documentos pueden incluir información como:

- Información de contacto.
- Información sobre variables.
- Información sobre incertidumbre.
- Métodos de recolección de datos.
- Referencias a versiones y licencias.
- Información sobre la estructura y el nombrado de archivos de los datos.
- Referencias a publicaciones que describen el conjunto de datos y(o) su procesamiento.

La intención es ayudar a que quienes usen los datos comprendan rápidamente cómo podrían utilizarlos y responder preguntas frecuentes sobre los datos. Puedes leer más información y ver una plantilla de README junto con un ejemplo (particularmente relevante para ciencias médicas) en este [sitio de la Harvard Medical School](https://datamanagement.hms.harvard.edu/collect-analyze/documentation-metadata/readme-files) (enlace externo).

### Pautas para versionado de datos

Establece un esquema de versionado para tus datos. Este es un método para hacer seguimiento de iteraciones de datos que permite registrar cambios y volver a revisiones anteriores.

Un versionado adecuado genera una copia modificada de un objeto de datos que se etiqueta de forma única con un número de versión. Esto permite a quienes usan los datos rastrear cambios y corregir errores.

Además, un versionado adecuado preserva la calidad y la procedencia de los datos (el origen, la historia y los pasos de procesamiento que conducen al conjunto de datos) al:

- Proporcionar un registro de trazabilidad desde la fuente de los datos a través de todos los aspectos de su transmisión, almacenamiento y procesamiento hasta su forma final.
- Guardar archivos de datos en pasos clave del proceso.
- Apuntar a la verificación(validación) posterior de los hallazgos originales.

## Hacer que los datos sean reutilizables mediante licenciamiento

<img src="../images/media/image32_es.png" style="width:100%;height:auto;" />

Crédito de la imagen: XKCD con licencia CC BY-NC 2.5 DEEX.

---

Los datos son propiedad intelectual del(de los) investigador(es), o posiblemente de su(s) financiador(es) o institución(es) de apoyo. Los datos son propiedad intelectual, pero eso no significa que no puedan ser utilizados por otros investigadores, con la atribución adecuada, por supuesto.

<img style="width:100%;height:auto;" src="../images/media/applylicensetoyourwork_es.jpg">
Crédito de la imagen: "Black and Blue Framed Eyeglasses on Silver Laptop" por Alexandr Bricky, vía [Pexels](https://www.pexels.com/photo/black-and-blue-framed-eyeglasses-on-silver-laptop-393044/) (enlace externo)

"Al aplicar una licencia a tu trabajo, dejas en claro qué pueden hacer otros con lo que compartes, y también bajo qué condiciones lo estás ofreciendo. (DeHaven, 2020) También puedes requerir que quienes copien tu trabajo hagan algo a cambio."

---

Si no licencias tu trabajo, otros no pueden y no deberían reutilizarlo, incluso si tú quieres que lo hagan. Como se mencionó previamente en este módulo, una licencia es un documento legal que indica a los usuarios cómo pueden usar un conjunto de datos. Es importante comprender las condiciones de licenciamiento de un conjunto de datos antes de reutilizarlo, para evitar infracciones de copyright u otros problemas de propiedad intelectual.

Un conjunto de datos sin licencia no necesariamente significa que los datos sean abiertos. Usar un conjunto de datos sin licencia puede plantear un dilema ético. Contactar a quien creó los datos y obtener permiso explícito, sugiriendo a la vez que se aplique una licencia, es el mejor camino a seguir.

Comprender cuándo y dónde aplica una licencia es crucial. Por ejemplo, los datos creados con fondos públicos de investigación del gobierno de Estados Unidos están, por defecto, en el dominio público. Sin embargo, esto solo aplica a la jurisdicción de Estados Unidos. Para que esto aplique internacionalmente, quienes crean los datos deben seleccionar una licencia abierta.

<img src="../images/media/image34_es.png" style="width:100%;height:auto;" />
Crédito: NASA

Existen varios tipos de licencias que se construyen unas sobre otras. Las licencias Creative Commons (CC) se usan con frecuencia para conjuntos de datos. CC0 (también conocida como "dominio público") es la licencia que permite mayor reutilización porque impone la menor cantidad de restricciones sobre lo que los usuarios pueden hacer. Aunque la licencia CC0 no exige explícitamente citación, deberías seguir buenas prácticas comunitarias y citar la fuente de los datos. CC-BY es otra licencia común utilizada para datos científicos que requiere citación. A partir de allí, pueden agregarse restricciones sobre uso comercial, posibilidad de adaptar o modificar los datos, o requisitos de compartir bajo la misma licencia. Estas otras variantes reducen la usabilidad al agregar restricciones, de modo que otros científicos pueden verse imposibilitados de usar los datos debido a restricciones institucionales o legales. Las agencias financiadoras pueden requerir el uso de una licencia específica. En el caso de agencias públicas, suele tratarse de CC0 o CC-BY, maximizando así el retorno de la inversión y asegurando la reutilización más amplia posible.

### Ejemplo de licencias de datos y reutilización

A continuación se presenta un ejemplo de cómo una licencia de datos puede afectar la reutilización. El Coupled Model Intercomparison Project Phase 6 (CMIP6) consiste en "corridas" de alrededor de cien modelos distintos de patrones climáticos producidos por cuarenta y nueve grupos de modelado diferentes. Estos datos se utilizan para comprender cómo podrían ser los patrones climáticos futuros. Versiones previas de estos datos estaban licenciadas bajo CC-BY-NC-SA (requiere citación, solo uso no comercial, compartir igual).

<img src="../images/media/ipccm3l3_es.png" style="width:100%;height:auto;" />
Fuente de la imagen: "An IPCC Special Report" por ResearchGate

---

Esto significaba que cualquier uso comercial estaba restringido. Compañías de seguros, corporaciones globales y cualquier tipo de organización que quisiera usar estos datos con fines comerciales debía realizar su propio modelado, o incluso decidir no desarrollar recursos relacionados con proyecciones de patrones climáticos. Esto impactó directamente la reutilización de estos datos y generó trabajo adicional. La versión más reciente de los datos CMIP está migrando a CC-BY (PCMDI: Earth System Model Evaluation Project, 2022) debido a los impactos negativos de las restricciones NC-SA.

## Lección 3: Resumen

A continuación se presentan los principales aprendizajes de esta lección:

- Es una buena práctica crear un plan de gestión de datos abiertos. Asegúrate de incluir temas relacionados con apertura y usar lenguaje conciso.
- Un paso crítico para producir datos abiertos es evaluar y seleccionar formatos de datos abiertos. Elegir el formato adecuado para tus datos puede definir el éxito o el fracaso de tu trabajo.
- Agrega siempre documentación que permita a otros investigadores evaluar la relevancia y reutilización de tu producto. Esto incluye metadatos, archivos README y detalles de control de versiones.
- Es importante asignar una licencia abierta a tus datos para habilitar la reutilización. Existen distintos tipos de licencias abiertas que pueden adaptarse a tus necesidades.

## Lección 3: Autoevaluación

Responde las siguientes preguntas para evaluar lo que aprendiste hasta ahora.

*Pregunta*

**01/04**

¿Cuáles de los siguientes son pasos que deberías seguir al elaborar un Plan de Gestión de Datos?

- Evaluar distintos formatos de datos
- Probar tus metadatos para verificar cumplimiento
- Crear una pequeña colección de datos de prueba
- Todas las anteriores

*Pregunta*

**02/04**

¿Cuáles de las siguientes son consideraciones al elegir un formato de archivo?

- El formato tiene soporte adecuado para metadatos
- Existen herramientas disponibles para leer el formato de datos
- El formato de datos se usa ampliamente en tu comunidad
- Todas las anteriores

*Pregunta*

**03/04**

Lee la siguiente afirmación y decide si es verdadera o falsa.

*Los metadatos solo son útiles para usar datos en herramientas interoperables y no mejoran la capacidad de búsqueda y encontrabilidad de los datos.*

- Verdadero
- Falso

*Pregunta*

**04/04**

Lee la siguiente afirmación y decide si es verdadera o falsa.

*Cuando un conjunto de datos no requiere explícitamente citación, como en el caso de la licencia CC0, igualmente se recomienda citar la fuente de los datos.*

- Verdadero
- Falso

### Referencias citadas

- DeHaven, Alexander. (2020, marzo 18). Getting Started with OSF. Center for Open Science. [https://www.cos.io/blog/getting-started-osf](https://www.cos.io/blog/getting-started-osf) (enlace externo)
- PCMDI: Earth System Model Evaluation Project. (2022, octubre 12). CMIP6: Terms of Use. [https://pcmdi.llnl.gov/CMIP6/TermsOfUse/TermsOfUse6-2.html](https://pcmdi.llnl.gov/CMIP6/TermsOfUse/TermsOfUse6-2.html) (enlace externo)
