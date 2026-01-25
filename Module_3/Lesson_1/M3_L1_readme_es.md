# Lección 1: Introducción a los Datos Abiertos

## Contenidos

- [Introducción](#introducci%C3%B3n)
- [Definiciones y consideraciones de los Datos Abiertos](#definiciones-y-consideraciones-de-los-datos-abiertos)
- [Beneficios de los Datos Abiertos](#beneficios-de-los-datos-abiertos)
- [Desafíos de los Datos Abiertos](#desaf%C3%ADos-de-los-datos-abiertos)
- [Aplicación de los principios FAIR](#aplicaci%C3%B3n-de-los-principios-fair)
- [Planificar la apertura: El sistema "usar, hacer, compartir" para los Datos Abiertos](#planificar-la-apertura-el-sistema-usar-hacer-compartir-para-los-datos-abiertos)
- [Lección 1: Resumen](#lecci%C3%B3n-1-resumen)
- [Lección 1: Evaluación](#lecci%C3%B3n-1-evaluaci%C3%B3n)

## Descripción general

En esta lección se definen los Datos Abiertos, sus beneficios y las prácticas que permiten que los datos sean abiertos y transparentes. Los Datos Abiertos son un pilar fundamental de la Ciencia Abierta y en la era digital es aún más importante que los datos sean accesibles y reproducibles. Además, observarás con más detalle cómo se aplican a los Datos Abiertos los Principios de ser Encontrables, Accesibles, Interoperables y Reutilizables (FAIR), así como el papel crítico de los metadatos en el ámbito científico. Por último, terminarás con una breve introducción a la planificación de Datos Abiertos en el flujo de trabajo científico, incluyendo tareas guiadas por el marco "".

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Definir qué son los Datos Abiertos y cómo los principios FAIR y CARE se utilizan para guiar las prácticas de Datos Abiertos
- Enumerar los beneficios de los Datos Abiertos
- Explicar cómo el sistema «» puede ser usado para modificar el plan científico para Datos Abiertos

## Introducción

Los datos hacen avanzar a la ciencia. Estos se almacenan electrónicamente para permitir su análisis e investigación posteriores. Las tecnologías digitales, integradas en cada aspecto de la investigación científica moderna, han propiciado la generación de grandes volúmenes de datos.

En muchos sentidos, los Datos Abiertos son una expansión natural de la Ciencia Abierta más allá de las publicaciones académicas, para incluir los resultados digitales de la investigación. Así se han convertido en una parte integral del movimiento de la Ciencia Abierta ya que los Datos Abiertos permiten que todas las personas vean, usen y verifiquen resultados publicados. Los Datos Abiertos hacen que la ciencia sea más accesible y reproducible. Para que esto funcione, es necesario que los datos estén disponibles en formatos que otras personas puedan usar, incluir metadatos que describan a los datos y contar con documentación útil. Una vez disponibles, los Datos Abiertos facilitan nuevos descubrimientos y usos.

###   Ejemplo: ¿Cómo vivirán los humanos en la Luna o viajarán a Marte si el entorno espacial amenaza la salud humana de múltiples maneras?

Pérdida de tejido óseo, vértigo, anemia, atrofia muscular, mayor riesgo de cáncer; estos son solo algunos de los efectos secundarios de viajar al espacio para los humanos. Para estudiar estos riesgos de viajar al espacio para la salud humana, las personas que investigan en el mundo usan la plataforma GeneLab de Código Abierto de la NASA. GeneLab recopila grandes cantidades de datos de biología espacial en el [Open Science Data Repository (OSDR)](https://www.nasa.gov/osdr/), que incluye datos sobre muestras humanas y de organismos modelo expuestas a condiciones de viaje espacial. Sus repositorios [digitales](https://osdr.nasa.gov/bio/repo/search?q=&data_source=cgene,alsda&data_type=study) y físicos incluyen información celular, así como ADN, ARN y proteínas. Al ser una plataforma abierta, los datos de GeneLab son públicamente accesibles y sin costo.

<img src="../images/media/image2_es.jpg" style="width:100%;height:auto;" alt="Imagen de un astronauta flotando en el espacio, con la Tierra al fondo. Sobre la imagen hay dos recuadros de texto. Uno indica: 'Las personas investigadoras identificaron un posible responsable de los cambios que se ven en el cuerpo en el espacio: el motor de la célula, llamada mitocondria'; el otro señala: 'Este análisis usa datos de la plataforma abierta GeneLab colectados durante décadas de experimentación en la Estación Espacial Internacional, incluyendo muestras de 59 astronautas'." />

Créditos de imagen: "Astronaut at spacewalk (en español, Astronauta en caminata espacial)" por Vadimsadovski vía [AdobeStock](https://stock.adobe.com/contributor/203529807/vadimsadovski?load_type=author&prev_url=detail&asset_id=132366202), licencia estándar (enlace externo).

### Ejemplo

Usando grandes cantidades de muestras de animales y humanas que volaron al espacio, así como datos biológicos de astronautas provenientes de GeneLab, un artículo reciente publicado en *Nature* encontró cuál podría ser la causa detrás de muchos de los efectos secundarios de viajar al espacio: el estrés mitocondrial. (Clyde, 2021)

Las mitocondrias son componentes de nuestras células que influyen en la función respiratoria y energética. Este descubrimiento podría ser crucial para superar los problemas de salud humana en el espacio. Comprender el origen de este problema podría ayudar a la comunidad científica a desarrollar soluciones y terapias para mantener a las personas sanas en el espacio durante períodos más prolongados.

Para obtener información adicional sobre el estudio del estrés mitocondrial en los cuerpos de astronautas, mira [Vivir y trabajar en el espacio: Estudio de los gemelos (en inglés, Living and Working in Space: Twins Study)](https://www.youtube.com/watch?v=c9moR-KQpDQ) (enlace externo) en el canal de YouTube de la NASA.

## Definiciones y consideraciones de los Datos Abiertos

### ¿Qué son los datos?

<img src="../images/media/image3_es.png" style="width:500px;height:auto;" alt="Ilustración de una persona caminando por un sendero mientras carga un gran cubo que dice: “DATA”. A la izquierda, un cartel indica: “REPOSITORIO DE DATOS” y debajo: “DEPÓSITOS BIENVENIDOS”, con una flecha apuntando hacia la izquierda." />
Créditos de imagen: The Turing Way Community. Ilustración creada por Scriberia con la comunidad de The Turing Way, licencia CC BY 4.0. DOI: [10.5281/zenodo.3332807](https://zenodo.org/records/3332808) (enlace externo).


---

Los datos son cualquier tipo de información que se recolecta, se observa o se crea en el contexto de una investigación. Hoy en día, los datos se almacenan cada vez más de manera electrónica en formato digital.

Los datos incluyen:

**Datos primarios (crudos)** – Los datos primarios son los recolectados o creados directamente por las personas que investigan. Las preguntas de investigación guían la recopilación de datos. Por lo general, quien investiga formulará una pregunta, desarrollará una metodología y comenzará a recopilar los datos. Algunos ejemplos de datos primarios incluyen:

- Respuestas a entrevistas, cuestionarios y encuestas.
- Datos obtenidos a partir de mediciones registradas, incluidos datos de teledetección.
- Los datos obtenidos a partir de muestras físicas y especímenes constituyen la base de muchos estudios.
- Los datos generados a partir de modelos y simulaciones.

**Datos secundarios y procesados** – Los datos secundarios son los que utiliza una persona distinta de quien los recopiló o generó. A menudo, esto puede incluir datos que han sido procesados a partir de su estado bruto para que sean más fácilmente usables por otras personas.

**Datos publicados** – Los datos publicados son aquellos compartidos para abordar un estudio científico en particular y/o para uso general. Aunque los datos publicados pueden coincidir con los tipos de datos primarios y secundarios, hemos incluido los «datos publicados» como categoría propia para destacar que, en lo ideal, estos conjuntos de datos estén bien documentados y sean fáciles de utilizar.

**Metadatos** – Los metadatos son un tipo especial de datos que describen otros datos u objetos (por ejemplo, muestras). Normalmente se utilizan para proporcionar información estándar sobre un conjunto de datos con el fin de facilitar su uso e interpretación.

El término "Datos Abiertos" se define en el manual de Datos Abiertos de la Open Knowledge Foundation (Fundación Conocimiento Abierto):
"Los Datos Abiertos son datos que cualquiera puede usar, reusar y redistribuir libremente, sujetos únicamente y como máximo al requisito de atribuir y compartir por igual" [¿Qué son los Datos Abiertos? (en inglés, What is Open Data?), s. f.](https://opendatahandbook.org/guide/en/what-is-open-data/)

<img style="width:100%;height:auto;" src="../images/media/opendatahandbookquote_es.jpg">
Créditos de imagen: Foto de Killian Cartignies en [Unsplash](https://unsplash.com/photos/person-wearing-silver-bracelet-holding-a-light-oKb2_15Uc8w) (enlace externo).


Al hablar de datos en el contexto de este módulo, nos centramos en los datos que estás preparando para compartir, como los asociados a una publicación científica, sin importar de qué tipo de datos se trate. Si bien podrías compartir (y muchas personas lo hacen) libretas de laboratorio, análisis preliminares, productos de datos intermedios, borradores de publicaciones científicas, planes para investigaciones futuras y otras cosas similares, estos normalmente no son requeridos por agencias o instituciones financiadoras y, por lo tanto, no serán el foco de este módulo.

Como señalan Hemphill et al. en un artículo sobre la reutilización de datos, quienes investigan suelen buscar datos que sean "completos, fáciles de obtener, fáciles de manipular y creíbles". Para que estos criterios se cumplan, los datos deberían:

- Estar suficientemente descritos con los metadatos adecuados, lo que afecta en gran medida su reuso. No hay una estructura única para los metadatos ya que su recopilación estará guiada por tus datos.
- Disponer de la información adecuada sobre licencias, derechos de autor y citas.
- Tener información de acceso apropiada.
- Ser fáciles de encontrar en una fuente acreditada o de confianza.
- Estar acompañados con un historial de cambios y versiones.
- Incluir detalles de todos los pasos de su procesamiento.

(Hemphill et al., 2022)

No todos los datos pueden compartirse ni con toda esta información. Hay diferentes razones por las que puede no ser posible. Sin embargo, cuanta más información se comparta sobre los datos, mayor será su fiabilidad y reuso.

## Beneficios de los Datos Abiertos

Los datos son la base de casi toda la ciencia. Compartir abiertamente los datos con otras personas facilita la reproducibilidad, la transparencia, la validación, el reuso y las colaboraciones. Entre los muchos beneficios de los datos abiertos se incluyen los siguientes:

---

**Bien mayor** – Los datos desempeñan un papel importante en nuestra vida cotidiana. Los Datos Abiertos, en particular, juegan un rol clave. Si haces una pausa y piensas en ello, puedes darte cuenta de que los Datos Abiertos no sólo son comunes en nuestra sociedad, sino que tú mismo te has beneficiado y has usado Datos Abiertos.

#### Ejemplo: Ejemplo: los Datos Abiertos ayudan a proporcionar información que salva vidas frente al cambio climático

Los tsunamis son olas oceánicas extremadamente grandes y de alta velocidad que pueden representar un peligro significativo para las poblaciones costeras. Estas olas pueden cruzar el océano a más de 500 mph. Una red de sensores de superficie oceánica y detectores de actividad sísmica, propiedad de varias organizaciones nacionales e internacionales, mide y recopila datos las 24 horas del día. Estos datos en tiempo real sobre posibles amenazas de tsunamis se ponen a disposición del público a través de plataformas de Datos Abiertos, lo que permite que cualquier persona acceda a información sobre las condiciones del océano, los peligros potenciales y las advertencias activas de tsunami. Los datos permiten respuestas más rápidas y medidas de preparación que ayudan a salvar vidas. Las personas en áreas de riesgo pueden recibir notificaciones sobre posibles amenazas, lo que permite implementar procedimientos de evacuación más rápidos.

Los Datos Abiertos están disponibles para cualquiera con acceso a Internet. Este nivel de transparencia permite que el público comprenda la base de las advertencias de tsunami. Una fuente importante de Datos Abiertos sobre tsunamis es la que recolecta y mantiene la Administración Nacional Oceánica y Atmosférica (National Oceanic and Atmospheric Administration, NOAA). Los datos están disponibles en el [Sistema de Alerta de Tsunamis de los Estados Unidos (U.S. Tsunami Warning System)](https://www.tsunami.gov/) (enlace externo).

**Información sobre los recursos naturales**

#### Ejemplo: Cambios en la composición de peces en la pesca recreativa de marlín en la costa este de Australia

Un estudio en Springer Nature incluyó datos del programa de etiquetado de peces deportivos de New South Wales (New South Wales game fish tagging program) (enlace externo) para ayudar a mapear los cambios en la composición de las capturas pesqueras. Los hallazgos ayudaron a enfatizar la necesidad de estrategias de gestión adaptativas y sostenibles para las prácticas pesqueras a escala local y global, con el fin de reducir los efectos de las prácticas actuales y de la aparición de nuevas tecnologías pesqueras sobre la disponibilidad de peces. (Guillemin et al., 2025) Este ejemplo muestra cómo los Datos Abiertos pueden conducir a cambios de política que impactan directamente en la vida de las comunidades.

**Respuesta global de emergencia**

#### Ejemplo: Huracán Ida

La preparación ante tsunamis no es la única forma en que los Datos Abiertos pueden ayudar a una comunidad. Pueden desempeñar un rol vital al proporcionar datos oportunos y accionables para asistir a las comunidades en la reducción del riesgo frente a desastres naturales, así como para ayudar en la respuesta y la recuperación tras un desastre a gran escala. En 2021, la NASA proporcionó datos como humedad del suelo, detección de inundaciones y cambios de vegetación para [apoyar esfuerzos de respuesta ante el Huracán Ida](https://science.nasa.gov/open-science/artificial-intelligence-hurricane-response/). Los datos se compartieron a través del [Portal de Mapeo de Desastres de la NASA (NASA Disasters Mapping Portal)](https://disasters-nasa.hub.arcgis.com/), donde se agregaron fotos subidas públicamente para aumentar la conciencia situacional y se utilizó Inteligencia Artificial para ayudar a evaluar los daños del huracán. Para mejorar aún más la respuesta ante desastres y la resiliencia, [la NASA colabora con IBM](https://science.nasa.gov/open-science/ai-model-weather-climate/) para desarrollar modelos base de Inteligencia Artificial de Código Abierto que puedan usarse para evaluar el riesgo de inundaciones e incluso pronosticar rendimientos de cultivos.

Compartir datos tiene muchos beneficios y puede facilitar el acceso al conocimiento. Hacer que grandes volúmenes de datos sean más accesibles y utilizables puede mejorar la toma de decisiones en la gestión de desastres y en la recuperación a largo plazo.

**Ciencia ciudadana**

#### Ejemplo: Pruebas de calidad del agua en Beirut

Una persona que hace ciencia ciudadana (puede ser aficionada a la ciencia) colabora con investigaciones profesionales para ayudar a recopilar o interpretar datos en una escala espacial y temporal más amplia de la que el equipo investigador podría lograr sin su colaboración. Esta externalización de la responsabilidad favorece que el público en general participe en actividades científicas que, en última instancia, los benefician y permiten que la investigación se realice en una escala mayor de la que podría ser posible solo con personas investigadoras. La Ciencia Ciudadana está ganando popularidad y reconocimiento como una valiosa contribución a los avances científicos.

Por ejemplo, se reclutaron en Beirut a 50 personas voluntarias de aldeas para ayudar a evaluar la calidad del agua; fuente: capítulo 5 de *Contextualizando la apertura: situando la Ciencia Abierta* (en inglés). Estas personas voluntarias se formaron para realizar las pruebas. No solo se recogieron datos para informar sobre los avances científicos, sino que quienes participaron en este proyecto de Ciencia Ciudadana tuvieron la oportunidad de aprender a gestionar mejor sus recursos hídricos y pudieron mejorar las condiciones, creando una interacción mutuamente beneficiosa. (Chan et al., 2019)

**Datos Abiertos e intercambio equitativo de conocimientos**

La libre distribución del conocimiento aumenta la participación en la ciencia.

En un ecosistema de investigación donde el conocimiento es una mercancía, con la moneda principal en forma de artículos publicados y conjuntos de datos acaparados, hacer que la investigación no esté disponible o sea difícil de obtener para la comunidad científica puede limitar el progreso científico y afectar negativamente los resultados.

#### Ejemplo: reconocimiento y compensación por el trabajo del equipo investigador africano del ébola


Durante el brote de ébola en África Occidental entre 2014 y 2016, el equipo de investigación de África Occidental trabajó activamente para recolectar muestras de sangre con el fin de comprender mejor el virus del ébola y ayudar a detener su rápida propagación. Sin embargo, la mayoría de las muestras de sangre se enviaron al extranjero, a EE. UU. y Europa, donde los grupos de investigación utilizaron esas muestras de datos para escribir artículos sobre el ébola. Como resultado, los datos tardaron mucho más en difundirse de regreso al público y los investigadores de África occidental recibieron poco crédito. Según un artículo de 2019 en *Nature*, "esto frustró a investigadores en los países devastados por el virus, que esperaban que estudiar aspectos de la epidemia fortaleciera su capacidad de responder a futuros brotes de enfermedades infecciosas". (Maxmen, 2019)

Al fomentar una cultura de investigación transparente, donde el trabajo sea reconocido adecuadamente, crearemos un modelo sostenible que incremente la transparencia y la calidad de la producción científica.

---

### Resumen de los beneficios de los Datos Abiertos

Los Datos Abiertos que están disponibles para el escrutinio benefician la innovación científica al permitir un proceso científico más robusto, que se nutre de múltiples perspectivas. Esta apertura también permite identificar a tiempo hallazgos erróneos, así como intervenir ante impactos negativos no previstos.

Los Datos Abiertos permiten a los equipos de investigación no tradicionales contribuir al desarrollo científico y aportar sus hallazgos particulares. Con estos beneficios en mente, debemos recordar siempre que los Datos Abiertos requieren una consideración cuidadosa de sus posibles desventajas. En la siguiente lección, “Uso de Datos Abiertos”, analizaremos consideraciones importantes para la gestión, recopilación y uso responsable de Datos Abiertos por parte de todas las partes interesadas.

### Beneficios para ti

Los Datos Abiertos también benefician a tu investigación y tu carrera. Para empezar, ¡eres quien colaborará contigo en el futuro!

Hacer Ciencia Abierta no sólo permite que otras personas entiendan y reproduzcan tus resultados, ¡sino que también te lo permite a ti! Implementar principios de Ciencia Abierta como la buena documentación y el control de versiones te ayuda a ti, a potenciales colaboradores y al resto de las personas a entender tus resultados. En 2 horas, 2 semanas o 2 años, todavía podrás entender lo que hiciste.

Beneficios específicos que tendrás si tus datos son abiertos:

- Nunca perderás el acceso a tu trabajo anterior, sin importar el instituto al que pertenezcas. Muchos investigadores se mueven por instituciones y organizaciones y, al tener sus datos accesibles públicamente en repositorios, siempre tendrán acceso a ellos.
- Cuando tus datos sean citados, obtendrás el crédito correspondiente.
- Según un estudio de 2020, las publicaciones que incluyen enlaces a datos se citan más. (Colavizza et al., 2020)

La implementación de buenas prácticas para la Ciencia Abierta puede fortalecer tus solicitudes de financiación. Las agencias de financiación se están dando cuenta de que compartir abiertamente la investigación proporciona un mayor retorno sobre su inversión. Los resultados de investigación bien documentados también demuestran la calidad de tu trabajo, lo que ayuda con la comunicación pública y también puede atraer colaboradores de calidad. Todo el mundo prefiere trabajar con personas confiables y que hagan un buen trabajo.

### Actividad 1.1 Revisión de Datos Abiertos

Tómate un momento para reflexionar sobre lo que significa para ti compartir datos.

<img style="width:100%;height:auto;" src="../images/media/image6_es.jpeg" alt="Nube de palabras" />
Créditos de imagen: Nube de palabras "Open Research Data - the FAIRest Data is the Future of Science - Estonia national OpenAIRE event" por OpenAIRE, licencia CC 4.0.


La imagen muestra una nube de palabras (en inglés) con mayor presencia de términos como FAIR (principios FAIR), Datos Abiertos de investigación (Open Research Data), Ciencia Abierta (Open Science), Datos Abiertos (Open Data), Planes de Gestión de Datos (Data Management Plans), DOI (identificador de objeto digital), almacenamiento (storage) y reuso (reuse). También, con menor presencia, personas investigadoras (researchers), repositorio (repository), archivo (archiving), publicación (publishing), DataCite y OpenAire, entre otras.

## Desafíos de los Datos Abiertos

Si bien los Datos Abiertos tienen muchos beneficios, su creación y uso también pueden plantear desafíos. A lo largo de este módulo analizaremos muchos de estos desafíos y sus posibles soluciones. En esta sección, abordamos algunas de las preocupaciones más comunes junto con acciones para mitigarlas.

### Restricciones para compartir datos

Algunos datos sólo deben compartirse con mucho cuidado o no compartirse en absoluto. Las razones para no compartir pueden incluir:

- Los datos incluyen secretos militares de un país o violaciones de intereses nacionales.
- Los datos incluyen información médica privada o datos de identificación personal de un individuo.
- Los datos incluyen propiedad intelectual.

Es importante adquirir familiaridad con las políticas que rigen el intercambio de datos y las políticas de tu agencia de financiación, institución o legislación en materia de protección de datos. Esto se analiza con más detalle en módulos posteriores.

### Preocupaciones comunes a la hora de compartir datos

#### NOTA: Analizaremos muchos de los conceptos mencionados en la columna de discusión/mitigación más adelante en este módulo.

|  |  |
|---|---|
| Preocupación: Apropiación. ¿Qué pasa si alguien reusa mis datos para publicar un resultado en el que yo estaba trabajando? | Sí, esto puede suceder. Pero en muchos ámbitos, si está claro que alguien está trabajando activamente en un problema, la decisión de otro de sacar provecho puede tener una ganancia a corto plazo pero una pérdida a largo plazo. En ciencia, la reputación es muy importante y la colaboración generalmente conduce a mayores éxitos profesionales. Si compartes tus datos, asegúrate de que tengan un identificador de objeto digital (DOI). Esto no impide que alguien use tus datos sin atribución, pero ayuda a que otros puedan citar tus datos más fácilmente. Hay un buen artículo (en inglés) sobre esto [aquí](https://datascience.codata.org/articles/10.5334/dsj-2017-029). |
| Preocupación: Mala Interpretación o Mal Uso | Para reducir este riesgo, puedes proporcionar suficiente información contextual (documentación) que permita a los demás comprender plenamente tus datos. |
| Preocupación: Mis datos serán usados, pero no citados | Si bien no es común que las personas en investigación citen datos, la ética científica exige citar si se utiliza tu trabajo. ¡Y recuerda citar los datos de los demás para no contribuir al problema! |
| Preocupación: Los datos son demasiado sensibles para compartirlos | Puedes usar el acceso controlado para ayudar a mantener la confidencialidad y la seguridad. |
| Preocupación: Mis datos no serán útiles para nadie más | Nunca se sabe cómo podrán usarse los materiales. Marineros en los años 1800 recolectaron datos de temperatura que, todavía hoy, siguen siendo una parte importante de nuestro registro climático oceánico. (NPR, 2019) |

Todas estas son preocupaciones válidas cuando se comparten datos abiertamente, pero como lo muestra el movimiento global hacia la Ciencia Abierta, los beneficios generales superan las preocupaciones.

En última instancia, eres libre de implementar los principios y recursos de los Datos Abiertos en tu investigación para maximizar su impacto y cumplir con las expectativas de quienes te patrocinan y de la comunidad, mientras reduces los costos.


## Aplicación de los Principios FAIR

<img src="../images/media/image9_es.jpg" style="width:100%;height:auto;" alt="Caricatura en trazo naranja titulada “PRINCIPIOS FAIR”. Presenta cuatro viñetas, cada una asociada a un principio: “FÁCIL DE ENCONTRAR” (una persona busca datos en una hoja), “ACCESIBLE” (otra persona accede a datos en un pizarrón donde aparece un DOI), “INTEROPERABLE” (una persona frente a una computadora se pregunta cómo abrir un archivo .xz) y “REUSABLE” (dos personas intercambian un paquete con el símbolo de Creative Commons, indicando permisos de reutilización). " />

Créditos de imagen: Caricatura sobre el intercambio de datos FAIR, por Patrick Hochstenbach, licencia CC0 1.0.

---

### FAIR: Fácil de encontrar, Accesible, Interoperable, Reusable

La gran mayoría de los datos actuales se comparten en línea. Los principios FAIR ayudan a las personas investigadoras a hacer un mejor uso de sus datos científicos y a interactuar con una audiencia más amplia de lo que permitirían las técnicas obsoletas. Los datos FAIR son más valiosos para la ciencia porque resultan más fáciles de usar. Los datos pueden ser FAIR independientemente de si se comparten abiertamente o no. Si los datos se comparten abiertamente, ser FAIR ayuda al reuso y amplía el impacto científico de los datos.

Los principios FAIR no incluyen instrucciones de aplicación exhaustivas para cada tipo de datos, pero ofrecen ideas generales para mejorar la capacidad de compartir y reusar. A veces se necesita un esfuerzo grupal y/o un largo proceso de producción para que los datos y los resultados sean FAIR. El proceso comienza en la etapa de planificación de un proyecto de investigación. A menudo se necesita un plan de gestión de datos y Ciencia Abierta bien coordinado para cumplir plenamente con FAIR, dependiendo del tamaño y el tipo de proyecto para el que se utilizan los datos.

**Puedes encontrar información actualizada sobre los principios FAIR en el sitio de la Iniciativa GO FAIR**

[HAZ CLIC PARA APRENDER (ENLACE EXTERNO)](https://www.go-fair.org/)

Repasemos cómo hacer que los datos sean FAIR para tu comunidad.

*Selecciona cada pestaña para ver más información.*

<table>
  <thead>
    <tr>
        <th>FÁCILES DE ENCONTRAR &#9745;</th>
        <th>ACCESIBLES</th>
        <th>INTEROPERABLES</th>
        <th>REUTILIZABLES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Para garantizar que los miembros de tu comunidad puedan encontrar los datos:</p>
            <ul>
            <li>Deposita los datos en repositorios para preservarlos a lo largo del tiempo.</li>
            <li>Asigna a tu conjunto de datos un identificador persistente (PID, por sus siglas en inglés), como por ejemplo un identificador de objeto digital (DOI).</li>
            <li>Agrega metadatos enriquecidos y autodescriptivos en tus archivos de datos y registra los metadatos en un catálogo de metadatos que permitirá que estos se seleccionen adecuadamente.</li>
                <ul>
                <li>Ten en cuenta que algunas imágenes o archivos binarios no se pueden indexar ni buscar fácilmente y necesitarán archivos de metadatos o diccionarios complementarios para garantizar que se puedan descubrir en una búsqueda.</li>
                </ul>
            <li>Automatiza el intercambio de tus metadatos con comunidades objetivo, si corresponde.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FÁCILES DE ENCONTRAR</th>
        <th>ACCESIBLES &#9745;</th>
        <th>INTEROPERABLES</th>
        <th>REUTILIZABLES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Para garantizar que los miembros de tu comunidad puedan acceder a los datos:</p>
            <ul>
                <li>Archiva en un repositorio de datos/centro de datos con protocolos de acceso estandarizados.</li>
                <li>Los protocolos de acceso al repositorio deben estar bien definidos e idealmente deberían admitir el acceso de máquina a máquina.</li>
                <li>Provee información sobre cómo pueden acceder las personas usuarias a tus datos, idealmente de forma automatizada y computacional.</li>
                <li>Si el contenido completo no puede estar disponible abiertamente por algún motivo (sensibilidad de los datos, acceso poco frecuente a los datos, problemas de almacenamiento de los archivos), los metadatos pueden ponerse a disposición del público para que las personas usuarias puedan averiguar a quién deben contactar para solicitar los datos (de ser posible).</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FÁCILES DE ENCONTRAR</th>
        <th>ACCESIBLES</th>
        <th>INTEROPERABLES &#9745;</th>
        <th>REUTILIZABLES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Para asegurar que los datos sean interoperables para quienes integran tu comunidad:</p>
            <ul>
                <li>Reporta los datos en un formato estándar de la comunidad.</li>
                <li>Usa metadatos estandarizados existentes, si están disponibles, para minimizar los problemas generados por mala comunicación de la información y para respaldar la legibilidad automática.</li>
                <li>El uso de terminologías controladas, vocabularios y ontologías es necesario para respaldar la interoperabilidad, pero puede que aún no estén disponibles en todos los campos de investigación.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FÁCILES DE ENCONTRAR</th>
        <th>ACCESIBLES</th>
        <th>INTEROPERABLES</th>
        <th>REUTILIZABLES &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Para asegurar que los datos sean reutilizables por quienes integran tu comunidad:</p>
            <ul>
                <li>Asegúrate de que los metadatos describan con precisión los datos y sus variables, así como cualquier particularidad o limitación.</li>
                <li>Especifica licencias de uso claras para tus datos.</li>
                <li>Proporciona información precisa sobre la procedencia en tus metadatos.</li>
                <li>Agrega suficiente información en los metadatos para que tus datos puedan ser citados correctamente cuando se utilicen.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

### El papel central de los metadatos en la aplicación de los principios FAIR

Los metadatos son importantes para que los motores de búsqueda encuentren datos y para que las personas puedan comparar fácilmente lo que se devuelve.

- Los metadatos son esenciales para la aplicación de los Principios FAIR y permiten que los datos sean utilizados por las máquinas de forma automatizada.
- Cuanto más ricos y autodescriptivos sean los metadatos, mejor serán manejados por cualquiera interesado en tus datos.

### Licenciar datos

Una licencia es un documento legal que indica a las personas usuarias cómo pueden utilizar un conjunto de datos en particular. Si no licencias tu trabajo, otros no podrán o no deberían reusarlo, ¡aunque lo quieras! Es imprescindible conocer las condiciones de licencia de un conjunto de datos antes de reusarlos. Sin una buena comprensión de lo que permite una licencia, las personas usuarias de los datos pueden enfrentarse a infracciones de derechos de autor u otros problemas de propiedad intelectual.

Para asegurar el reúso libre de tus datos, puedes recurrir a una licencia abierta. Una licencia abierta contiene un texto que describe la capacidad del usuario para acceder, reusar y redistribuir el conjunto de datos. Hay muchos tipos de licencias de datos que tienen distintos grados de apertura y que se tratarán con más detalle en la lección 3 de este mismo módulo "Hacer de Datos Abiertos".

## Planificar la apertura: El sistema "usar, hacer, compartir" para los Datos Abiertos

### Planificar proyectos de Ciencia Abierta y gestión de datos

La mayoría de las agencias y organismos de financiamiento científico solicitan un plan de difusión de resultados al presentar un proyecto de investigación. [Un ejemplo de un plan de Ciencia Abierta](https://science.nasa.gov/researchers/sara/faqs/osdmp) es el Plan de Ciencia Abierta y Gestión de Datos (OSDMP por sus siglas en inglés) de la Dirección de Misión de Ciencia de la NASA (SMD por sus siglas en inglés) que describe cómo se gestionará y pondrá a disposición del público la información producida a partir de las actividades científicas. El OSDMP incluye secciones sobre gestión de datos, gestión de software e intercambio de publicaciones; estas dos últimas se abordarán en los próximos módulos. Si tu estudio tiene otros tipos de resultados, como muestras físicas, hardware u otros, también debes incluirlos en el plan. Puedes encontrar más información y modelos en [OSDMP de la NASA](https://science.nasa.gov/researchers/sara/faqs/osdmp/) (en inglés).

Una buena práctica al comenzar tu viaje hacia los Datos Abiertos es crear un Plan de Gestión de Datos (PGD). En él se describe cómo se gestionarán, se preservarán y se publicarán los datos durante y después de un proyecto de investigación. Los elementos comunes a todos los Planes de Gestión de Datos (PGD) relevantes para Datos Abiertos incluyen una descripción teniendo en cuenta lo siguiente:

|  |  |
|---|---|
| ¿Qué? | Tipos de datos, volumen, formatos y (cuando corresponda) estándares. |
| ¿Cuándo? | El cronograma para archivar y compartir. |
| ¿Dónde? | Los repositorios destinados a datos archivados. |
| ¿Cómo? | Manera en que el plan permite la conservación a largo plazo de los datos. |
| ¿Quién? | Roles y responsabilidades de las personas que forman parte del equipo en la implementación del PGD. |

Consulta si tu institución o tu organismo de financiación dispone de pautas, normas o modelos para PGDs. Si no, hay entidades que también disponen de guías y muestras de PGD, como ser:

- [USGS](https://www.usgs.gov/data-management/data-management-plans) (enlace externo)
- [NOAA](https://marinedebris.noaa.gov/sites/default/files/DataManagementPlanGuidance%26Sample.pdf) (enlace externo)
- [NSF](https://new.nsf.gov/funding/data-management-plan) (enlace externo)

Se proporcionarán más detalles sobre cómo elaborar estos planes en la lección 5 de este mismo módulo, "De la teoría a la práctica".

### Flujo de trabajo científico

Hay una variedad de modelos de flujo de trabajo científico que aclaran y facilitan la comprensión de los principios y prácticas de la Ciencia Abierta. Los datos juegan un papel central en el flujo de trabajo, donde las personas usuarias pueden proponer la creación de nuevos datos, recopilar y empaquetar sus datos durante su proyecto y luego archivarlos para su almacenamiento, uso y reuso a largo plazo.

Para este plan de estudios, utilizamos el modelo de flujo de trabajo de Opensciency (en inglés). Se utiliza para ilustrar que, independientemente del modelo de flujo de trabajo que se utilice, la adopción de Datos Abiertos se realiza durante todo el flujo de trabajo y la producción de entregables asociados.

Si tu proyecto ya está en curso, es una buena idea actualizar futuras publicaciones de datos para adherirse a los principios de Datos Abiertos en la medida de lo posible. Para nuevos proyectos, tus propuestas deberían incluir la creación de Datos Abiertos desde el inicio de tu proyecto.

<img src="../images/media/image10_es.png" style="width:100%;height:auto;" alt="Diagrama del flujo de trabajo con hitos y productos asociados. Hitos: Ideación → producto: “Propuestas”. Planificación y Planificación del proyecto → productos: “Planes de Gestión de Datos, código de conducta”. Compromiso y formación → producto: “Tutoriales, pautas para colaboradores”. Recolección de datos → producto: “Datos sin procesar, metadatos”. Gestión de datos → producto: “Ciclos de análisis”. Exploración de datos → producto: “Código, cuadernos”. Preservación → producto: “Archivos”. Reporte y publicación → productos: “Artículos, conferencias, blogs, videos, tuits”." />

Créditos de imagen: Opensciency. Productos del flujo de trabajo de Ciencia Abierta.

En este plan de estudios, el contenido se organiza según cómo podrías usarlo, hacerlo y compartirlo. Una parte de la Ciencia Abierta consiste en construir sobre los materiales de otros (usar), crear materiales por ti mismo (hacer) y compartirlos para que otros puedan usar esos resultados (compartir). Las lecciones se organizan en torno a estos pasos del flujo de trabajo científico.

El sistema "Usar, Hacer, Compartir" clasifica las tareas más habituales en la práctica de la Ciencia Abierta.

<img src="../images/media/image11_es.png" style="width:100%;height:auto;" alt="Diagrama “Usar, Hacer, Compartir”. Tres columnas: USAR: “Descubrir productos existentes”; “Evaluar productos existentes”; “Usar productos existentes”. HACER: “Crear un plan de gestión”; “Seleccionar las bases de la creación (por ej. formatos, base de código)”; “Crear nuevos productos”. COMPARTIR: “¿Se pueden compartir los productos? (regulación)”; “¿Dónde se pueden compartir?” (subpunto: “Archivar”); “Asignar una licencia”; “Verificar identificadores” (subpuntos: “ORCID”, “DOI”); “Crear la cita”." />

### Roles en Usar, Hacer, Compartir

Las personas que interactúan con los datos en distintos puntos del flujo de trabajo científico pueden desempeñar diferentes roles. Es posible que estos roles se superpongan según los requisitos del proyecto, el tamaño de su equipo e incluso la financiación. Todos deben utilizar principios de Datos Abiertos para realizar sus tareas. Por lo general, los roles incluyen:

*Selecciona cada pestaña para ver más información.*

<table>
  <thead>
    <tr>
        <th>QUIENES USAN DATOS &#9745;</th>
        <th>QUIENES HACEN DATOS (PROVEEN DATOS)</th>
        <th>QUIENES SON RESPONSABLES DE COMPARTIR LOS DATOS (EDITAR DATOS)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Las personas usuarias de datos principalmente descubren, evalúan y usan datos en proyectos de investigación.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>QUIENES USAN DATOS</th>
        <th>QUIENES HACEN DATOS (PROVEEN DATOS) &#9745;</th>
        <th>QUIENES SON RESPONSABLES DE COMPARTIR LOS DATOS (EDITAR DATOS)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Las personas creadoras de datos suelen procesar los datos recogidos por un proyecto/actividad y empaquetarlos según los principios de la Ciencia Abierta.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>QUIENES USAN DATOS</th>
        <th>QUIENES HACEN DATOS (PROVEEN DATOS)</th>
        <th>QUIENES SON RESPONSABLES DE COMPARTIR LOS DATOS (EDITAR DATOS) &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Las personas que comparten los datos tienen la responsabilidad de difundirlos y darlos a conocer al público.</p>
        </td>
    </tr>
  </tbody>
</table>

Hacer que los datos sean abiertos (y cumplan con los principios FAIR) es un esfuerzo grupal: todas las personas en la cadena de datos tienen un papel que desempeñar.

## Lección 1: Resumen

En esta lección has aprendido:

- Los Datos Abiertos son un pilar esencial de la Ciencia Abierta. Compartir abiertamente los datos con otras personas permite la reproducibilidad, la transparencia, la validación, el reuso y la colaboración.
- Hay varios retos para la creación de Datos Abiertos, pero la mayoría tienen medidas sencillas de solución.
- Los principios FAIR pueden aplicarse a los datos para hacerlos más abiertos.
- Los principios y tareas relacionados con los Datos Abiertos se usan a lo largo de todo el flujo del trabajo científico.

## Lección 1: Evaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

*Pregunta*

**01/04**

Lee la siguiente afirmación y decide si es Verdadera o Falsa.

*Los Datos Abiertos pueden ser libremente utilizados, reusados y redistribuidos por cualquiera, sujeto, como mucho, al requisito de atribuir y compartir por igual.*

- Verdadero
- Falso

*Pregunta*

**02/04**

Termina la frase:

*Hacer que los datos estén abiertos te ayuda porque ____.*

- tus datos pueden ser citados y se te dará credito
- no perderás el acceso a tus datos, incluso si cambias de institución
- tus publicaciones tienen más probabilidades de ser citadas cuando se vinculan a Datos Abiertos
- todas las anteriores

*Pregunta*

**03/04**

Selecciona los principios FAIR de la siguiente lista. Selecciona todos los que correspondan.

- Reproducibles
- Reutilizables
- Responsables
- Fáciles de encontrar
- Interactivos
- Interoperables
- Intercalados
- Accesibles
- Autorizables

*Pregunta*

**04/04**

¿Cuál de las siguientes opciones puede ayudar a que tus datos sean FAIR? Selecciona todas los que correspondan.

- Obtener una licencia para tus datos
- Hacer que tus metadatos sean accesibles solo mientras tus datos estén disponibles
- Obtener un PID para tus datos

### Referencias citadas

- Chan, L., Okune, A., Hillyer, R., Albornoz, D., y Posada, A. (2019). *Contextualizing openness: Situating open science*. The University of Ottawa Press.
- Clyde, D. Spaceflight causes mitochondrial stress. *Nat Rev Genet* 22, 69 (2021). [https://doi.org/10.1038/s41576-020-00322-8](https://doi.org/10.1038/s41576-020-00322-8) (enlace externo)
- Colavizza G, Hrynaszkiewicz I, Staden I, Whitaker K, McGillivray B (2020) The citation advantage of linking publications to research data. *PLoS ONE* 15(4): e0230416. [https://doi.org/10.1371/journal.pone.0230416](https://doi.org/10.1371/journal.pone.0230416) (enlace externo)
- Guillemin, T.A., Pepperell, J.G., Schilling, H.T. et al. 90 years of catch data reveal changes in catch composition in the Australian east coast recreational marlin fishery. *Rev Fish Biol Fisheries* 35, 371-389 (2025). [https://doi.org/10.1007/s11160-024-09906-7](https://doi.org/10.1007/s11160-024-09906-7) (enlace externo)
- Hemphill L, Pienta A, Lafia S, Akmon D, Bleckley DA. How do properties of data, their curation, and their funding relate to reuse? *J Assoc Inf Sci Technol.* 2022 octubre;73(10):1432-1444. [doi: 10.1002/asi.24646](https://doi.org/10.1002/asi.24646) (enlace externo). Publicación electrónica 2022 marzo 23. PMID: 36246529; PMCID: PMC9542848.
- Maxmen, Amy. (2019, julio 24). Science under fire: Ebola researchers fight to test drugs and vaccines in a war zone. *Nature*, 572, 16-17. doi: [https://doi.org/10.1038/d41586-019-02258-4](https://doi.org/10.1038/d41586-019-02258-4) (enlace externo)
- NPR. (2009). 1800s-Era Sea Logs Chart Course Of Climate Change. [https://www.npr.org/2009/10/18/113916471/1800s-era-sea-logs-chart-course-of-climate-change](https://www.npr.org/2009/10/18/113916471/1800s-era-sea-logs-chart-course-of-climate-change) (enlace externo)
- OpenSciency Contributors (2023, febrero 22). Opensciency - A core open science curriculum by and for the research community. Zenodo. DOI 10.5281/zenodo.7392118 [https://doi.org/10.5281/zenodo.7392118](https://doi.org/10.5281/zenodo.7392118) (enlace externo)
- What is Open Data? (s. f.). Open Data Handbook. [https://opendatahandbook.org/guide/en/what-is-open-data/](https://opendatahandbook.org/guide/en/what-is-open-data/) (enlace externo)
- The Turing Way. (2024). *The Turing Way*. [https://book.the-turing-way.org/](https://book.the-turing-way.org/) (enlace externo)
