# Lección 1: Introducción al Código Abierto

## Contenidos

- [Historias de éxito](#historias-de-%C3%A9xito)
- [Definiciones y consideraciones del Código Abierto](#definiciones-y-consideraciones-del-c%C3%B3digo-abierto)
- [Principios, beneficios y desafíos](#principios-beneficios-y-desaf%C3%ADos)
- [Cuándo no compartir](#cu%C3%A1ndo-no-compartir)
- [Plan de Gestión de Software (PGS)](#plan-de-gesti%C3%B3n-de-software-pgs)
- [Lección 1: Resumen](#lecci%C3%B3n-1-resumen)
- [Lección 1: Evaluación](#lecci%C3%B3n-1-evaluaci%C3%B3n)

## Descripción general

Esta lección define los términos clave, los principios centrales, los beneficios y los desafíos del código abierto. La práctica de poner el código a disposición del público de forma abierta ocurre en un espectro que va de mayor a menor protección. Condiciones éticas y legales pueden limitar el grado de apertura que quienes investigan pueden permitir. Esta lección presentará las preguntas críticas a considerar al determinar la accesibilidad apropiada del código para personas usuarias externas, junto con buenas prácticas para superar restricciones comunes y maximizar la disponibilidad. La lección concluye con una discusión sobre el ciclo de vida del código y cómo se integra con el marco “Usar, Crear, Compartir”, así como su relación con un plan de gestión.

## Objetivos de aprendizaje

Luego de completar esta lección, deberías poder:

- Definir software de código abierto y distinguirlo de software de código cerrado.
- Enumerar beneficios y desafíos comunes de la producción de código abierto y describir cómo pueden responder quienes investigan a algunos de los desafíos, maximizando la apertura cuando corresponda.
- Describir la función y el propósito de un Plan de Gestión de Software y su utilidad como guía para todas las personas involucradas en un proyecto científico.

## Historias de éxito

¿Por qué la buena ciencia exige que quienes investigan hagan su código de acceso abierto? Compartir tu código (y tus datos) facilita que otras personas reproduzcan tus resultados, ayuda a validar hallazgos y reduce los recursos requeridos para duplicar experimentos. Como beneficio adicional, esta decisión puede conducir a nuevas colaboraciones posibles gracias a un conjunto de datos compartido y a un entendimiento común del material científico.

Muchas revistas y agencias financiadoras exigen que compartas tu código al momento de la publicación. Sin embargo, la posibilidad de abrir el código a críticas, de no recibir atribución o de perder un resultado que investigadores externos descubran puede desalentar a científicos a que su código sea de acceso abierto. ¿Qué pasa si alguien encuentra un error o critica tu estilo de programación? ¿Qué pasa si toman tu código y publican un resultado nuevo sin incluirte? Este módulo te ayudará a ganar confianza para compartir tu código, guiándote por los detalles básicos a considerar al practicar ciencia abierta.

Revisemos algunos ejemplos conocidos de grupos que compartieron su código y cuáles fueron los impactos:

Usa los botones para navegar entre los ejemplos.

<img src="../images/media/image394_es.jpg" style="width:350px;height:auto;" />
Crédito de la imagen: Event Horizon Telescope Collaboration

La primera imagen de un agujero negro no habría sido posible en esta década si todo el código requerido hubiera tenido que ser escrito únicamente por las personas científicas involucradas. Estas personas pudieron usar software de código abierto que era gratuito, robusto, bien probado y aceptado por la comunidad para realizar su análisis y crear esta imagen que hoy es famosa. El código utilizado para capturar esta imagen fue desarrollado por 21.485 contribuyentes. Los sofisticados pipelines y algoritmos iterativos de procesamiento de datos usados por el equipo de investigación fueron desarrollados y probados por la comunidad, haciendo posible una ciencia robusta y reproducible sin tener que reescribir cada pieza de software necesaria.

<img src="../images/media/image553_es.png" style="width:350px;height:auto;" />
Crédito de la imagen: NASA/JPL-Caltech

Este es el helicóptero Ingenuity, o como le dicen las personas ingenieras, Ginny. Llegó a Marte viajando junto al rover Perseverance y aterrizó en el cráter Jezero en 2021.

Este es un [video](https://science.nasa.gov/resource/first-video-of-nasas-ingenuity-mars-helicopter-in-flight/) del primer vuelo de Ginny. Despegó, subió cerca de diez pies, hizo un giro y aterrizó. Este vuelo pionero demostró que el vuelo propulsado en Marte es posible y abrió la puerta a una era completamente nueva de exploración.

Pero los logros de Ginny también reflejan otra era nueva: una era de ciencia verdaderamente abierta y colaborativa.

Detrás de ese helicóptero de cuatro libras hay más de 12.000 personas que contribuyeron con código, documentación, diseño y más gracias al software de código abierto que se utilizó para impulsarla. Todas las personas que contribuyeron a las bibliotecas de software de código abierto que Ginny usó recibieron una insignia en su página de GitHub que mostraba que ayudaron a volar el primer helicóptero en Marte.

Además, el software final de Ginny desarrollado en el Jet Propulsion Lab, llamado F prime, era en sí mismo de código abierto y desde entonces se ha usado en investigación de vuelo, drones y CubeSats. De hecho, F prime había sido copiado a repositorios de otras personas más de 1.200 veces.

<img src="../images/media/image408_es.jpg" style="width:350px;height:auto;" />
Crédito de la imagen: NASA GSFC/CIL/Adriana Marique Gutierrez

La mayoría de los datos de telescopios espaciales tienen un embargo de doce meses, y solo la persona científica principal y su equipo seleccionado pueden trabajar con los datos. En un caso particular, una pequeña porción de datos del nuevo Telescopio Espacial James Webb (JWST) de NASA ofreció un programa de liberación temprana. Estos datos del JWST estuvieron disponibles de manera inmediata.

¿Qué tan intimidante es eso? Todas las personas que conoces van a tener acceso exactamente al mismo tiempo. La ansiedad y el estrés de sentir que podrías no tener trabajo si no publicas primero, o de que podrías no obtener el próximo trabajo que quieres, podría ser enorme.

En un caso, un equipo decidió trabajar completamente en abierto y colaborar con estos datos de liberación temprana. ¿El resultado? Más de 20 artículos planificados y el primer descubrimiento de dióxido de carbono en otro planeta, lo que sugiere la posibilidad de descubrir nueva vida.

La coautora Dra. Natasha Batalha empleó principios de ciencia abierta para posibilitar este descubrimiento rápido usando los nuevos datos del JWST. En los años previos a la liberación del JWST, el equipo de la Dra. Batalha formó un grupo colaborativo de 341 integrantes. Una vez que los datos del JWST fueron públicos, la reducción de datos y la interpretación científica pudieron reproducirse mediante software abierto y luego archivarse. El primer artículo del equipo de investigación se puso a disposición como acceso abierto en un servidor de preprints archivado y fue publicado en *Nature*.

De forma destacada, el equipo de la Dra. Batalha publicó la primera identificación de CO2 en la atmósfera de un exoplaneta a partir de espectros tomados con el JWST. Esto se realizó con datos del Programa de Ciencia de Liberación Temprana del JWST, los primeros datos científicos tomados por la instalación. El equipo trabajó en un formato abierto durante todo el proceso de investigación, comenzando en la etapa de ideación y manteniendo el esfuerzo hasta la finalización, incluyendo publicación y comunicación.

Este ejemplo ilustra los beneficios de aplicar principios de ciencia abierta para producir investigación significativa con rapidez.

<img src="../images/media/image168_es.jpg" style="width:350px;height:auto;" />
Crédito de la imagen: NASA's Earth Observatory

Nuevos conjuntos de modelos climáticos de código abierto incorporan características que apuntan a hacer la investigación climática más colaborativa, eficiente y confiable. (Junker, 2018)

Científicos han publicado un marco de modelos climáticos de código abierto [(Isca)](https://execlim.github.io/IscaWebsite/) (enlace externo), que contiene modelos fáciles de obtener y completamente gratuitos, documentados, y que incluyen software para facilitar la instalación y la operación. Todos los cambios quedan documentados y pueden revertirse. Por lo tanto, cualquiera puede usar fácilmente los mismos modelos.

Aunque el modelo Isca se usó inicialmente para examinar la alta atmósfera tropical, investigadores de otras áreas de la ciencia lo han usado para estudiar el ciclo de vida de sistemas meteorológicos, el monzón de India y el efecto de erupciones volcánicas en el clima.

Nueva investigación en todos estos campos fue posible en solo un año desde la publicación de Isca. ¡Así es como queremos que funcione toda la ciencia!

## Definiciones y consideraciones del Código Abierto

Toda la ciencia se construye sobre lo que ya se logró. El código no es diferente. Muchas personas científicas usan código para analizar datos. Este proceso comienza con la adquisición de datos, ya sea ejecutando un experimento o un modelo que genera datos, o identificando datos observacionales que pueden ser útiles para poner a prueba una hipótesis. Luego, los datos se analizan. Es muy probable que el código requerido para leer o analizar un conjunto de datos nuevo ya haya sido creado por alguien. Aunque el código existente puede requerir cierto grado de modificación para ajustarse a los parámetros particulares de una persona investigadora. Incluso el desarrollo de un modelo nuevo puede incorporar elementos específicos de código existente de diferentes fuentes.

Comprender cómo encontrar y usar el código de otras personas, crear el propio y compartirlo es una parte importante de avanzar la ciencia abierta. Al igual que las buenas prácticas de gestión de datos, conocer algunos de los detalles sobre cómo compartirlo no solo te ayudará a usarlo más adelante, sino que también ayudará a que otras personas comprendan cómo usarlo y citarlo para que recibas crédito.

[IMG: https://drive.google.com/file/d/1Ry0NodPF_Tm_EKMqZUOrvehiKtG8vaQ4/view?usp=drive_link]
Búsqueda en deal.II [captura de pantalla]. (2023). deal.II. https://dealii.org/developer/doxygen/deal.II/grid_2tria_8h_source.html (enlace externo)

### ¿Qué es código vs. software?

<img src="../images/media/image109_es.png" style="width:350px;height:auto;" />
Crédito de la imagen: NASA

Cuando escribimos “software”, en realidad estamos escribiendo código en texto y usando un intérprete o compilador para traducirlo a un programa que la máquina pueda ejecutar. El código es un lenguaje que las personas pueden escribir y entender. El software suele ser una colección de programas, datos y otra información que un sistema informático usa para realizar tareas específicas. Un ejemplo es una biblioteca de software, que es un conjunto de datos y código de programación que se utiliza para desarrollar programas y aplicaciones.

En lugar de crear paquetes de software, a menudo las personas científicas escriben y publican código que ayuda a otras personas a reproducir sus resultados. Pero muchas personas científicas no comienzan su código desde cero. Existen grandes bibliotecas de software de código abierto que las personas científicas usan y a las que contribuyen, como SciPy, Astropy, Matplotlib y otras. Estas bibliotecas permiten que toda la comunidad haga ciencia más rápido y mejor porque han sido escritas, probadas y son usadas por miles, si no por cientos de miles, de personas. Estas bibliotecas se adoptaron ampliamente porque son de código abierto, lo que facilita colaborar con cualquiera, en cualquier lugar.

### Qué es software de código abierto

El **software de código abierto** se distribuye con su código fuente sin costo, haciéndolo disponible para que otras personas lo usen, lo modifiquen y lo distribuyan con sus derechos y permisos originales.

A menudo, el software de código abierto se comparte de forma transparente en un repositorio público y a veces se mantiene mediante colaboración. El desarrollo de software de código abierto es la base de una amplia gama de paquetes de software de investigación.

Hay una variedad de elecciones de licencias que se pueden hacer para software abierto y que pueden permitir que la persona creadora retenga distintos niveles de propiedad y derechos. La elección de la licencia impacta cómo otras personas pueden reutilizar el software. Pero primero, desarmemos los principales tipos de software que usan las personas científicas y brindemos ejemplos de cada tipo.

### Tipos de software

Las personas científicas usan y producen muchos tipos diferentes de software durante los proyectos. Mientras algunas personas investigadoras pueden usar ecuaciones en una planilla de cálculo, otras pueden usar bibliotecas de código abierto para desarrollo avanzado de modelos de aprendizaje automático y para graficar resultados, u otras pueden contribuir a bibliotecas de código abierto en su campo y aumentar así su reputación e impacto. Aquí hay ejemplos de diferentes tipos de software que podrías encontrar:

**Software de propósito general** – El software de propósito general se produce para uso amplio y no para fines científicos especializados. Esto incluye software comercial y software de código abierto. Muchos paquetes de software de productividad ampliamente usados son historias de éxito de código abierto:

- Kernel de Linux, espacio de usuario GNU y varias distribuciones de Linux y UNIX
- PostgreSQL (base de datos de grado empresarial de código abierto)
- WordPress y herramientas de alojamiento web Apache
- Firefox y Chrome

  - El motor de Chrome es Chromium, que es un fork de WebKit, que a su vez fue un fork de KHTML. Esto fue posible porque tenía una licencia que permitía este tipo de reutilización. Todos los navegadores principales hoy, excepto Firefox, pueden rastrearse hasta KHTML.
  
- Sistema operativo Android, entre otros

  - Puedes mirar el código fuente de Android, pero no puedes modificarlo e instalarlo en un dispositivo. Y aun si pudieras, no podrías usar ninguno de los servicios estándar (por ejemplo, Google Store) con eso. Entonces es “abierto” en el mismo sentido en que los números de la lotería de anoche son “abiertos”.

**Software operacional** –  
Software entregado a personas como parte de un programa o producto. Ejemplos incluyen: flujos de trabajo automatizados, consolidación de datos e interfaces y reportes basados en roles.

[F Prime](https://nasa.github.io/fprime/) (software de vuelo para misiones espaciales)

**Software de infraestructura** – Forma el marco central de los sistemas informáticos, también conocido como la base de configuración del sistema. Ejemplos incluyen: sistemas operativos, sistemas de gestión de bases de datos, servidores web, middleware y software de virtualización.

- [Fprime](https://nasa.github.io/fprime/) (software de vuelo para misiones espaciales)
- [PODAAC](https://github.com/podaac) (enlace externo) (software de archivado y procesamiento distribuido)
- [UFS](https://github.com/ufs-community) (enlace externo) (software de modelos operacionales de pronóstico del tiempo)
- Verificador de cumplimiento de metadatos, APIs, aplicaciones web, [Giovanni](https://www.earthdata.nasa.gov/technology/giovanni), [McIDAS](https://en.wikipedia.org/wiki/McIDAS) (enlace externo)

**Bibliotecas** – Las bibliotecas son herramientas genéricas para implementar algoritmos bien conocidos, brindar análisis estadístico o visualización, que se incorporan en otras categorías de software. Ejemplos incluyen:

- [NumPy](https://github.com/numpy) (enlace externo) (cómputo científico con Python)
- [scikit-image](https://github.com/scikit-image/) (enlace externo) (algoritmos de procesamiento de imágenes en Python)
- [deal.II](https://github.com/dealii/dealii) (enlace externo) (biblioteca de algoritmos para resolver ecuaciones diferenciales parciales con elementos finitos)

**Software de modelado y simulación** – El software de modelado y simulación implementa soluciones a ecuaciones matemáticas dado un conjunto de datos de entrada y condiciones de borde, o infiere modelos a partir de datos. A menudo usa bibliotecas. Ejemplos incluyen: modelos de primeros principios, herramientas de asimilación de datos, modelos empíricos, aprendizaje automático, planificación de misiones y herramientas de ingeniería, entre otros.

- [OpenFOAM](https://github.com/OpenFOAM) (enlace externo) (software de dinámica de fluidos computacional)
- [MOM6](https://github.com/mom-ocean/MOM6) (enlace externo) (modelo general de circulación oceánica)
- [ASPECT](https://github.com/geodynamics/aspect) (enlace externo) (software de convección planetaria)
- Transferencia radiativa atmosférica, evolución estelar, turbulencia del océano superior, predicciones de viento solar, propagación orbital (por ejemplo, OpenGGCM, MESA)

**Software de análisis** – El software de análisis se desarrolla para manipular mediciones o resultados de modelos con el fin de visualizar o comprender. Este software a menudo evoluciona desde utilidades de uso único y puede incorporar bibliotecas.

- [Photutils](https://photutils.readthedocs.io/en/stable/index.html) (enlace externo) (herramientas para detectar y realizar fotometría de fuentes astronómicas)

**Software utilitario de uso único** – El software utilitario de uso único se escribe para uso en instancias únicas, como hacer un gráfico para un artículo o manipular datos de una manera específica. Este código a menudo usa bibliotecas para análisis, graficación o lectura de datos. Este software es el tipo más común que se incluye en Planes de Ciencia Abierta y Gestión de Datos (OSDMP), de los que hablaremos en breve. Ejemplos incluyen:

- [Angus et al. 2019](https://ui.adsabs.harvard.edu/abs/2019AJ....158..173A/abstract) (enlace externo) ( [Ajuste de una relación de giro a Praesepe](https://github.com/RuthAngus/stardate/blob/master/paper/code/Fitting_Praesepe.ipynb) (enlace externo) )
- [El telescopio Webb detecta CO2 en un exoplaneta por primera vez: qué significa para encontrar vida alienígena](https://www.nature.com/articles/d41586-022-02350-2) (enlace externo). Todos los datos y modelos presentados en esta publicación pueden encontrarse [aquí](https://doi.org/10.5281/zenodo.6959427) (enlace externo).
- Código en: [https://doi.org/10.5281/zenodo.6288035](https://doi.org/10.5281/zenodo.6288035) (enlace externo) (2022)

## Principios, beneficios y desafíos

### Principios del código abierto

Según The open source way, los modelos exitosos de software de código abierto pueden usarse para derivar un conjunto de cinco principios para practicar código abierto. Establecen lineamientos que impulsan la ciencia abierta y buscan aumentar el valor y el impacto de la investigación.

|  |  |
|---|---|
| Transparencia | Ya sea que estés desarrollando código o resolviendo un problema de negocios, todas las personas tenemos acceso a la información y a los materiales necesarios para hacer nuestro mejor trabajo. Cuando estos materiales son accesibles, podemos construir sobre las ideas y descubrimientos de otras personas. Podemos tomar decisiones más efectivas y comprender cómo esas decisiones nos afectan. |
| Colaboración | Cuando somos libres de participar, podemos mejorar el trabajo de otras personas de maneras no anticipadas. Cuando podemos modificar lo que otras personas compartieron, abrimos nuevas posibilidades. Al iniciar proyectos nuevos en conjunto, podemos resolver problemas que nadie puede resolver solo. Y cuando implementamos estándares abiertos, habilitamos que otras personas contribuyan en el futuro. |
| Compartir temprano y a menudo | Prototipos rápidos pueden conducir a descubrimientos rápidos. Un enfoque iterativo conduce a mejores soluciones más rápido. Cuando eres libre de experimentar, puedes mirar problemas de maneras nuevas y buscar respuestas en lugares nuevos. |
| Las mejores ideas deberían ganar | Las buenas ideas pueden venir de cualquier parte y las mejores ideas deberían ganar. Solo incluyendo perspectivas variadas en nuestras conversaciones podemos estar seguros de que identificamos las mejores ideas, y quienes toman decisiones de forma efectiva buscan esas perspectivas de manera continua. Puede que no operemos por consenso, pero el trabajo exitoso determina qué proyectos reúnen apoyo y esfuerzo de la comunidad. |
| Comunidad | Las comunidades se forman cuando distintas personas se unen alrededor de un propósito común. Los valores compartidos guían la toma de decisiones, y los objetivos comunitarios se anteponen a intereses individuales y agendas personales. |

(The open source way, 2025)

[IMG: https://drive.google.com/file/d/1KA0MtQ1ZmJJEWuaAxhL5Vikqbw6Oq-OR/view?usp=drive_link]
Crédito de la imagen: NASA

Compartir código mejora la ciencia porque habilita reproducibilidad, reutilización y replicabilidad. La decisión de compartir código beneficia a la comunidad científica porque incrementa la transparencia, la participación y la colaboración. Compartir código en cualquier punto del proceso de investigación puede ser valioso.

En la mayoría de los casos, el código fuente usado para generar resultados en artículos revisados por pares debería publicarse, citarse y ser accesible.

### Beneficios de pasar a software abierto

La ciencia avanza más rápido cuando las personas investigadoras pueden trabajar juntas, ayudar a corregir errores, construir sobre resultados previos y compartir recursos. Compartir código es una parte clave de la ciencia abierta que:

- Acelera la ciencia al facilitar el uso y la construcción sobre código desarrollado en trabajos previos.
- Minimiza el tiempo y el costo del desarrollo repetido de código similar y de la reproducción de cálculos científicos.
- Incrementa la cantidad potencial de personas usuarias y desarrolladoras y, por lo tanto, ayuda a mejorar la calidad y la confianza en el código.
- Aumenta la probabilidad de que quienes desarrollan ganen visibilidad y sostenibilidad, produzcan código de alta calidad y mejoren su empleabilidad.

### Desafíos de pasar a software abierto

No es raro que grupos de investigación pasen años desarrollando código, escribiendo artículos con resultados y ganando influencia científica sin compartir el código. Cualquier persona nueva que quiera trabajar en un proyecto similar queda en una gran desventaja porque tendría que empezar desde cero. Además, cualquiera que quiera trabajar en ese campo se ve forzado a colaborar con el grupo original. Este grupo retiene una ventaja competitiva real al mantener el código cerrado. Sin embargo, este enfoque frena la innovación y perjudica el progreso científico. Muchas agencias financiadoras ahora exigen que el código se comparta al momento de la publicación, si no antes. Pero siguen existiendo desafíos y miedos:

- La apertura tiene costos: tiempo invertido en documentar, publicar, responder a personas usuarias (mantenimiento) y limpiar o mejorar la calidad.
- Se requiere esfuerzo para aprender a aprovechar herramientas y conocimiento nuevos (hay recursos disponibles para facilitar este esfuerzo).

| Miedo | Discusión (mitigación): |
|---|---|
| “Scooping”: ¿y si alguien reutiliza mi código para publicar un resultado en el que yo estaba trabajando? | Sí, esto puede pasar. Pero, en muchos campos, si está claro que alguien está trabajando activamente en un problema, la decisión de otra persona de “scoopear” puede tener una ganancia de corto plazo pero una pérdida de largo plazo. En la comunidad científica, las reputaciones funcionan como una moneda cultural y ser colaborativo por lo general conduce a mayores éxitos de carrera. Si compartes tu código, asegurate de que tenga un identificador de objeto digital (DOI) para recibir crédito. Esto no impide que alguien lo use o extienda tu análisis, pero sí asegura que recibas crédito por tu contribución. Hay un buen artículo sobre esto en [Data Science Journal](https://datascience.codata.org/articles/10.5334/dsj-2017-029) (enlace externo). |
| Mala interpretación o mal uso | Proporciona suficiente información contextual (documentación) para que otras personas comprendan tu código completamente y así reducir este riesgo. |
| Mi código se usará, pero no se citará | Aunque no es común que se cite código, datos u otros materiales no publicados como artículos, la ética científica establece que deberías ser citado si se usa tu trabajo. Recuerda citar de manera apropiada el material de otras personas para no contribuir al problema. |
| El código es demasiado sensible para compartirse | Usar acceso controlado para ayudar a mantener la sensibilidad y la seguridad. |
| No va a ser útil para nadie más | Nunca se sabe cómo pueden usarse materiales. Personas que contribuyeron a proyectos de software aparentemente no relacionados terminaron ayudando a NASA a aterrizar un rover en Marte. |

#### En última instancia, eres libre de aplicar los principios y recursos de software abierto en tu investigación para maximizar su impacto y cumplir las expectativas de tus patrocinadores y tu comunidad, mientras gestionas costos.

### Actividad 1.1: Relacionar principios con beneficios y desafíos
Determina si una afirmación es un beneficio o un desafío arrastrando cada una al recuadro correcto.

<table>
  <thead>
    <tr>
      <th colspan="2">Beneficios</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Facilita el uso y la construcción sobre software desarrollado en trabajos previos.</td>
      <td>Las personas usuarias son libres de usar y modificar software abierto, minimizando esfuerzo duplicado.</td>
    </tr>
    <tr>
      <td>Puede incrementar el uso del software, lo que puede ayudar a mejorar su calidad.</td>
      <td>Quienes desarrollan software abierto pueden ganar visibilidad y sostenibilidad de su código.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th colspan="2">Desafíos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Requiere tiempo adicional para actividades como documentar, publicar y mantener.</td>
      <td>Se requiere esfuerzo para aprender a aprovechar las nuevas herramientas y el conocimiento.</td>
    </tr>
  </tbody>
</table>

**Puntos clave: Relacionar principios con beneficios y desafíos**

- Hacer el software más abierto siguiendo los principios tiene beneficios y desafíos, y están relacionados.
- Mayores beneficios típicamente vienen con mayores desafíos.
- En la mayoría de los casos, tanto personas científicas como la sociedad se beneficiarán de más código abierto.

## Cuándo no compartir

Hay razones válidas que restringen la capacidad de una persona investigadora para compartir su código completo o paquetes de software. Algunas de estas razones pueden incluir:

- El código incorpora secretos militares de un país o su difusión viola intereses nacionales o preocupaciones de seguridad.
- El código incorpora propiedad intelectual o datos e información patentados.
- Políticas institucionales o regulaciones organizacionales no permiten compartir el código.
- Piensa qué estás compartiendo y las implicancias de compartirlo (por ejemplo, ¿tienes permiso de todas las personas involucradas?).

### Licenciar código

Sobre las restricciones a la compartición de código abierto, el manual colaborativo de ciencia de datos de The Turing Way dice: “Como con cualquier otra cosa en la sociedad, parte de lo que puedes y no puedes hacer en el desarrollo de software (o hardware) está determinado por la ley. Por lo tanto, el licenciamiento es un aspecto importante de compartir o publicar proyectos de código abierto, ya que brinda claridad a cualquiera que busque reutilizar un proyecto de código abierto. Sin licencias, cualquier persona que quiera reutilizarlo quedará con ambigüedad legal sobre el estado del uso de tu propiedad intelectual.” (Licensing (licenciamiento), The Turing Way, 2024)

Para que se considere de código abierto, el software requiere una licencia que cumpla con la Definición de Código Abierto. Un criterio de esta definición exige que las licencias de código abierto “deben permitir modificaciones y obras derivadas, y deben permitir que se distribuyan bajo los mismos términos que la licencia del software original.” (Licenses, 2024)

En las siguientes lecciones, las licencias se discutirán con más detalle. Mientras trabajas en un proyecto, podrías querer usar código desarrollado por otras personas o desarrollar tu propio código y luego compartirlo. Las licencias afectan todos los aspectos de este proceso y es importante comprender cómo diferentes licencias pueden afectar tu capacidad de compartir tu código al momento de la publicación. También es importante considerar cualquier requisito de tu financiador o institución respecto de cómo licenciar tu software.

### Planificar la apertura: usar el marco “Usar, Crear, Compartir” para Código Abierto

Agencias financiadoras y revistas están exigiendo cada vez más que quienes investigan compartan código.

Por ejemplo, ROSES de NASA, que convoca propuestas de investigación en ciencias de la Tierra, exige que quienes investigan pongan su código a disposición pública:

#### “Los datos y el software desarrollados usando financiamiento de Research Opportunities in Space and Earth Sciences (ROSES) para respaldar una publicación revisada por pares deberán ponerse a disposición pública al momento de la publicación.”
- ROSES Open Science and Data Management Plan, 2025

Planificar un proyecto de investigación requiere que quienes investigan determinen su modo de colaboración y su método para compartir código. Este paso a menudo se documenta en un plan de gestión de software (SMP) dentro de una propuesta de investigación. Un SMP detalla qué, cuándo, dónde, cómo y quién compartirá el código o el software.

## Planes de gestión de software (SMP)

Los planes de gestión de software abarcan tanto código como software.

|  |  |
|---|---|
| ¿Qué? | Descripción de tipos, gestión, preservación y liberación del software. |
| ¿Cuándo? | Cronograma para archivar y compartir el software. |
| ¿Dónde? | Ubicación donde el software se compartirá y se archivará a largo plazo. |
| ¿Cómo? | Habilitar la reutilización del software mediante la asignación de un DOI, una licencia, guías de contribución, etc. |
| ¿Quién? | Roles y responsabilidades de los integrantes del equipo. |

A medida que tu investigación empieza a usar, crear y compartir código, el SMP brinda una guía para todas las personas del proyecto que establece un entendimiento común.

¿Tu proyecto comparte todo el código públicamente o solo el código que entra en una publicación? ¿Tu equipo contribuirá de regreso a proyectos de código abierto o solo escribirá código que se apoya en ellos para producir resultados? Considerar estas preguntas temprano influirá en cuánto tiempo y energía quieres invertir en documentación y cómo planeas compartir el código.

### El código abierto es un espectro

Al igual que los datos, el código puede compartirse de muchas maneras distintas para aumentar la reutilización. El código puede compartirse sin documentación, solo como un artefacto de reproducibilidad, o puede estar bien escrito, documentado y con licencia abierta para maximizar la reutilización. Ambos enfoques tienen valor y dependen del tiempo, la energía y el financiamiento disponibles.

- Hay un espectro de apertura para el software abierto que va desde software de código abierto hasta software de código cerrado.
- Un ejemplo de algo “intermedio” podría ser un archivo ejecutable con documentación sobre cómo funciona el código.
- Algunos proyectos pueden ser abiertos desde el inicio y compartir continuamente todo el código durante el desarrollo. Otros pueden compartir parte del código al momento de la publicación. Otros proyectos pueden poner el código a disposición solo cuando finaliza el financiamiento. Varias razones válidas influyen en el enfoque de un proyecto para compartir.
- Aunque algunos factores restringen el grado de apertura que el código puede tener, cada paso hacia la compartición hace avanzar el movimiento de ciencia abierta.
- Al compartir más ideas y código, las comunidades han impulsado el avance creativo, científico y tecnológico más rápido que el ritmo restringido de la ciencia cerrada. La producción entre pares y la colaboración masiva crean un desarrollo de software más sostenible.

Aunque personas investigadoras e instituciones pueden no ser capaces de compartir todo su código, pueden hacer esfuerzos para moverse en el espectro de apertura desde código cerrado hacia código abierto y software de código abierto.

*En la actividad de abajo, arrastra cada control para explorar el espectro de apertura.*

<img src="../images/media/image110_es.png" style="width:100%;height:auto;" />

### La práctica de lo “abierto”

Revisa cómo se cubren las tareas clave del ciclo de vida de desarrollo de código en el flujo del marco “Usar, Crear, Compartir”.

<img src="../images/media/image290_es.png" style="width:100%;height:auto;" />

Al igual que con datos abiertos, distintos aspectos del código abierto se describen en términos de “Usar, Crear y Compartir” código abierto.

Una diferencia clave con el código es que el proceso típicamente es más cíclico y repetitivo que con datos o resultados. Por lo general, el código evoluciona de forma continua. Así, los límites entre “Usar, Crear, Compartir” son menos rígidos y el proceso suele ser más dinámico y circular que procesos preplanificados o fijos y secuenciales.

### Actividad 1.2: Cómo puedes usar código abierto en tu trabajo para impulsar la ciencia abierta

En esta actividad, se te pide reflexionar sobre cómo has usado y cómo puedes usar principios de código abierto para impulsar tu trabajo.

Considera las siguientes preguntas:

1. ¿Has usado principios de código abierto en tu trabajo?
2. ¿Cuáles son algunos de los éxitos y desafíos que has encontrado?
3. ¿Qué recursos te resultaron útiles para avanzar el código abierto en tu trabajo?

#### Puntos clave: Cómo puedes usar código abierto en tu trabajo para impulsar la ciencia abierta

- El software abierto es una actividad colaborativa.
- Todas las personas podemos aprender y beneficiarnos unas de otras al hacer nuestro código científico más abierto.

## Lección 1: Resumen

En esta lección, aprendiste que:

- En software de código abierto, cualquiera puede ver el código fuente subyacente.
- Los principios de código abierto promueven transparencia, colaboración, selección de las mejores ideas y compartición entre comunidades científicas.
- El código de código abierto acelera la ciencia, minimiza el tiempo y el costo del desarrollo repetido de software similar y de reproducir cómputos científicos, y puede mejorar la calidad y la confianza en la ciencia.
- Las licencias para software de código abierto determinan su capacidad de compartición y reutilización para quienes desarrollan y para potenciales contribuyentes. Entidades financiadoras e instituciones asociadas pueden imponer restricciones sobre cómo las personas desarrolladoras licencian su software.
- Un plan de gestión de software (SMP) es una guía del proyecto, desarrollada por el equipo de investigación, para documentar prácticas planificadas de gestión de datos durante el proyecto de investigación.

## Lección 1: Autoevaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

*Pregunta*

**01/03**

Lee la afirmación de abajo y decide si es verdadera o falsa:

*Se considera que el software es de código abierto cuando es accesible públicamente y cualquiera puede ver, modificar y distribuir el código según lo considere dentro de las restricciones establecidas por la licencia de software.*

- Verdadero
- Falso

*Pregunta*

**02/03**

¿Cuáles de las siguientes son razones válidas por las que personas científicas mantienen su código fuente cerrado? Selecciona todas las que correspondan.

- Preocupaciones de seguridad nacional
- Políticas institucionales
- Preocupaciones de privacidad de datos
- Preocupaciones sobre atribución
- Preocupaciones sobre calidad

*Pregunta*

**03/03**

¿Cuáles son las secciones principales de un plan de gestión de software?

- Tipos de código y software
- Cronograma para compartir software
- Dónde se compartirá y archivará el software o el código
- Qué licencia se le asignará
- Roles y responsabilidades de los integrantes del equipo
- Todas las anteriores

### Referencias citadas

- Jucker, M. (2018, 6 de marzo). Making climate models open source makes them even more useful. The Conversation. [https://theconversation.com/making-climate-models-open-source-makes-them-even-more-useful-90929](https://theconversation.com/making-climate-models-open-source-makes-them-even-more-useful-90929) (enlace externo)
- Licenses. (2024). Open Source Initiative. [https://opensource.org/licenses/](https://opensource.org/licenses/) (enlace externo)
- Licensing (licenciamiento), The Turing Way. (2024). The Turing Way. [https://book.the-turing-way.org/reproducible-research/licensing](https://book.the-turing-way.org/reproducible-research/licensing) (enlace externo)
- ROSES Open Science and Data Management Plan. (2025, 7 de febrero). National Aeronautics and Space Administration. [https://science.nasa.gov/researchers/sara/faqs/osdmp/](https://science.nasa.gov/researchers/sara/faqs/osdmp/)
- The open source way. (2025). Open Source. [https://opensource.com/open-source-way](https://opensource.com/open-source-way) (enlace externo)
