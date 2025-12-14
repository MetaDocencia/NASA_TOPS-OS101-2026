# Lección 1: Introducción a los Datos Abiertos

## Contenidos

- [Introducción](#introducci%C3%B3n)
- [Definiciones y consideraciones de los Datos Abiertos](#definiciones-y-consideraciones-de-los-datos-abiertos)
- [Beneficios de los Datos Abiertos](#beneficios-de-los-datos-abiertos)
- [Desafíos de los Datos Abiertos](#desaf%C3%ADos-de-los-datos-abiertos)
- [Aplicación de los principios FAIR](#aplicaci%C3%B3n-de-los-principios-fair)
- [Planificar la apertura: El sistema Usar, Hacer, Compartir para los Datos Abiertos](#planificar-la-apertura-el-sistema-usar-hacer-compartir-para-los-datos-abiertos)
- [Lección 1: Resumen](#lecci%C3%B3n-1-resumen)
- [Lección 1: Evaluación](#lecci%C3%B3n-1-evaluaci%C3%B3n)

## Descripción general

Esta lección definirá qué son los datos abiertos, sus beneficios y las prácticas que permiten que los datos sean abiertos y transparentes. Los datos abiertos son un pilar fundamental de la ciencia abierta, y en la era digital es aún más importante que los datos sean accesibles y reproducibles. Además, observarás con más detalle cómo se aplican a los datos abiertos los Principios de ser Encontrables, Accesibles, Interoperables y Reutilizables (FAIR), así como el rol crítico de los metadatos en el mundo de la ciencia. Por último, terminarás con una breve introducción a la planificación de datos abiertos dentro del flujo de trabajo científico, incluyendo tareas guiadas por el marco "Usar, Producir, Compartir".

## Objetivos de aprendizaje

Luego de completar esta lección, deberías poder:

- Definir qué son los datos abiertos y cómo se usan los Principios FAIR para guiar prácticas de datos abiertos.
- Enumerar los beneficios de los datos abiertos.
- Explicar cómo el marco "Usar, Producir, Compartir" puede utilizarse para modificar el plan científico para datos abiertos.

## Introducción

Los datos impulsan el avance de la ciencia. Hoy en día, los datos se almacenan electrónicamente para permitir análisis e investigación adicionales. Como resultado, las tecnologías digitales integradas en todos los aspectos de la investigación científica moderna han llevado a la producción de grandes volúmenes de datos.

En muchos sentidos, los datos abiertos son una expansión natural de la ciencia abierta más allá de las publicaciones académicas, para incluir resultados digitales de investigación. Desde entonces, se han convertido en una parte integral del movimiento de ciencia abierta, porque los datos abiertos permiten que cualquier persona vea, use y verifique resultados publicados. Los datos abiertos hacen que la ciencia sea más accesible y reproducible. Para apoyar esto, los datos deben ponerse a disposición en formatos que otros puedan usar, y deberían proporcionarse metadatos que describan los datos y documentación útil. Cuando se ponen a disposición, ¡los datos abiertos habilitan nuevos descubrimientos y usos imprevistos!

### Ejemplo: ¿Cómo vivirán los seres humanos en la Luna o viajarán a Marte cuando el entorno espacial amenaza la salud humana de múltiples maneras?

Pérdida ósea, vértigo, anemia, atrofia muscular, mayor riesgo de cáncer: estos son solo algunos de los efectos secundarios para los seres humanos asociados a los viajes espaciales. Para estudiar estos riesgos para la salud humana de los viajes espaciales, científicos de todo el mundo usan la plataforma de código abierto GeneLab de la NASA. GeneLab agrega grandes volúmenes de datos de biología espacial en el [Open Science Data Repository (OSDR)](https://www.nasa.gov/osdr/), que incluye datos sobre muestras humanas y de organismos modelo expuestas a condiciones de vuelo espacial. Sus repositorios [digitales](https://osdr.nasa.gov/bio/repo/search?q=&data_source=cgene,alsda&data_type=study) y físicos incluyen información celular, así como ADN, ARN y proteínas. Como plataforma de código abierto, todos los datos de GeneLab son accesibles públicamente sin costo.

<img src="../images/media/image2.jpeg" style="width:100%;height:auto;" />
Crédito de la imagen: "Astronaut at spacewalk" por Vadimsadovski vía [AdobeStock](https://stock.adobe.com/contributor/203529807/vadimsadovski?load_type=author&prev_url=detail&asset_id=132366202), licencia estándar (enlace externo)

### Ejemplo

Usando grandes cantidades de muestras de animales y humanas que volaron al espacio, así como datos biológicos de astronautas provenientes de GeneLab, un artículo reciente publicado en *Nature* encontró cuál podría ser la causa detrás de muchos de los efectos secundarios de viajar al espacio: el estrés mitocondrial. (Clyde, 2021)

Las mitocondrias son componentes dentro de nuestras células que afectan funciones respiratorias y energéticas. Este hallazgo podría ser crucial para superar problemas de salud humana relacionados con el espacio. Comprender el origen de este problema podría ayudar a científicos a desarrollar contramedidas y terapias para mantener a las personas saludables en el espacio durante períodos más prolongados.

Para información adicional sobre el estudio del estrés mitocondrial en los cuerpos de astronautas, mira Living and Working in Space: Twins Study (enlace externo) en el canal de YouTube de la NASA.

## Definición y consideraciones sobre Datos Abiertos

### ¿Qué son los datos?

<img src="../images/media/image3.jpeg" style="width:350px;height:auto;" />
The Turing Way Community. Esta ilustración fue creada por Scriberia con la comunidad de The Turing Way y se usa bajo una licencia CC-BY 4.0. [DOI: 10.5281/zenodo.3332807](https://zenodo.org/records/3332808) (enlace externo)

---

Los datos son cualquier tipo de información que se recolecta, observa o crea en el contexto de una investigación. Hoy en día, los datos se almacenan cada vez más de manera electrónica en formato digital.

Los datos incluyen:

**Datos primarios (crudos)** – Los datos primarios se refieren a datos recolectados o creados directamente por investigadores. Las preguntas de investigación guían la recolección de los datos. Por lo general, un investigador formulará una pregunta, desarrollará una metodología y comenzará a recolectar datos. Algunos ejemplos de datos primarios incluyen:

- Respuestas a entrevistas, cuestionarios y encuestas.
- Datos obtenidos de mediciones registradas, incluyendo datos de teledetección.
- Datos obtenidos de muestras físicas y especímenes, que constituyen la base de muchos estudios.
- Datos generados a partir de modelos y simulaciones.

**Datos secundarios y procesados** – Los datos secundarios suelen referirse a datos utilizados por alguien distinto de quien recolectó o generó los datos. A menudo, esto puede incluir datos que han sido procesados desde su estado crudo para ser más utilizables por otros.

**Datos publicados** – Los datos publicados son datos que se comparten para abordar un estudio científico en particular y(o) para uso general. Si bien los datos publicados pueden superponerse con los datos primarios y secundarios, consideramos "datos publicados" como una categoría propia para enfatizar que esos conjuntos de datos idealmente están bien documentados y son fáciles de usar.

**Metadatos** – Los metadatos son un tipo especial de datos que describen otros datos u objetos (por ejemplo, muestras). Se utilizan a menudo para proporcionar un conjunto estándar de información sobre un conjunto de datos, con el fin de habilitar el uso y la interpretación de los datos de manera sencilla.

El término datos abiertos se define en el *Open Data Handbook* de la Open Knowledge Foundation:

<img style="width:100%;height:auto;" src="../images/media/opendatahandbookquote.jpg">

"Los datos abiertos son datos que pueden usarse libremente, reutilizarse y redistribuirse por cualquier persona, sujetos solo, como máximo, al requisito de atribuir y compartir bajo la misma licencia." [-What is Open Data?, s. f.](https://opendatahandbook.org/guide/en/what-is-open-data/)
Crédito de la imagen: Foto de Killian Cartignies en [Unsplash](https://unsplash.com/photos/person-wearing-silver-bracelet-holding-a-light-oKb2_15Uc8w) (enlace externo)

Al hablar de datos en el contexto de este módulo, nos enfocamos en los datos que estás preparando para compartir, sin importar de qué tipo sean, como los datos asociados a una publicación científica. Si bien podrías compartir (y muchos lo hacen) cuadernos de laboratorio, análisis preliminares, productos de datos intermedios, borradores de artículos científicos, planes de investigación futura y elementos similares, esto no suele ser requerido por agencias financiadoras o instituciones y, por lo tanto, no será el foco de este módulo.

Como señalan Hemphill et al. en un artículo sobre reutilización de datos, quienes investigan suelen buscar datos que sean "completos, fáciles de obtener, fáciles de manipular y creíbles". Para que estos criterios se cumplan, los datos deberían:

- Estar suficientemente descritos con metadatos apropiados, lo que afecta en gran medida la reutilización de datos abiertos. No existe un enfoque único para metadatos, ya que su recolección está guiada por tus datos.
- Tener la licencia, el copyright y la información de citación adecuados.
- Tener información de acceso apropiada.
- Ser encontrables en un recurso acreditado o confiable.
- Estar acompañados por un historial de cambios y versionado.
- Incluir detalles de todos los pasos de procesamiento.

(Hemphill et al., 2022)

No todos los datos pueden compartirse, o compartirse con toda esta información. Existen distintas razones por las que puede no ser posible. Sin embargo, mientras más información se comparta sobre los datos, más se incrementa la confiabilidad y reutilización de la información.

## Beneficios de los Datos Abiertos

Los datos sustentan casi toda la ciencia. Compartir datos abiertamente con otros habilita reproducibilidad, transparencia, validación, reutilización y colaboración. Entre los muchos beneficios de los datos abiertos se incluyen los siguientes:

---

**Bien común** – Los datos impactan de forma significativa nuestra vida cotidiana. Los datos abiertos, en particular, cumplen un rol clave. Si te detienes a pensarlo, puede que notes que los datos abiertos no solo son comunes en nuestra sociedad, sino que también es posible que te hayan beneficiado y que los hayas usado.

#### Ejemplo: Los datos abiertos ayudan a brindar información que salva vidas y a mejorar la preparación ante desastres

Los tsunamis son olas oceánicas extremadamente grandes y de movimiento rápido que pueden causar un peligro significativo para poblaciones costeras. Estas olas pueden cruzar el océano a velocidades de más de 500 mph. Una red de sensores de superficie oceánica y detectores de actividad sísmica, propiedad de varias organizaciones nacionales e internacionales, mide y recolecta datos las 24 horas del día. Estos datos en tiempo real sobre posibles amenazas de tsunamis se ponen a disposición del público a través de plataformas de datos abiertos, lo que permite que cualquier persona acceda a información sobre condiciones del océano, peligros potenciales y advertencias activas de tsunami. Los datos permiten respuestas más rápidas y medidas de preparación que ayudan a salvar vidas. Las personas en áreas de riesgo pueden recibir notificaciones sobre posibles amenazas, lo que habilita procedimientos de evacuación más rápidos.

Los datos abiertos están disponibles para cualquiera con acceso a Internet. Este nivel de transparencia permite que el público comprenda la base de las advertencias de tsunami. Una fuente importante de datos abiertos sobre tsunamis es la que recolecta y mantiene la National Oceanic and Atmospheric Administration (NOAA). Los datos están disponibles en el [sitio del Tsunami Warning System](https://www.tsunami.gov/) (enlace externo).

**Informar la gestión de recursos**

#### Ejemplo: Cambios en la composición de peces en la pesca recreativa de marlín en la costa este de Australia

Un estudio en Springer Nature incluyó datos del programa de etiquetado de peces deportivos de New South Wales (enlace externo) para ayudar a mapear cambios en la composición de capturas pesqueras. Los hallazgos ayudaron a enfatizar la necesidad de estrategias de gestión adaptativas y sostenibles para prácticas pesqueras a escala local y global, con el fin de reducir los efectos de prácticas actuales y de la aparición de nuevas tecnologías pesqueras sobre la disponibilidad de peces. (Guillemin et al., 2025) Este ejemplo muestra cómo los datos abiertos pueden conducir a cambios de política que impactan directamente la vida de las comunidades.

**Respuesta a emergencias a gran escala**

#### Ejemplo: Huracán Ida

La preparación ante tsunamis no es la única forma en que los datos abiertos pueden ayudar a una comunidad. Los datos abiertos pueden cumplir un rol vital al proporcionar datos oportunos y accionables para asistir a comunidades en la reducción del riesgo frente a muchos desastres naturales distintos, así como para ayudar en la respuesta y recuperación luego de un desastre a gran escala. En 2021, la NASA proporcionó datos como humedad del suelo, detección de inundaciones y cambios de vegetación para [apoyar esfuerzos de respuesta ante el Huracán Ida](https://science.nasa.gov/open-science/artificial-intelligence-hurricane-response/). Los datos se compartieron a través del [NASA Disasters Mapping Portal](https://disasters-nasa.hub.arcgis.com/), donde se agregaron fotos subidas públicamente para aumentar la conciencia situacional y se usó IA para ayudar a evaluar daños del huracán. Para mejorar aún más la respuesta ante desastres y la resiliencia, [la NASA colabora con IBM](https://science.nasa.gov/open-science/ai-model-weather-climate/) para desarrollar modelos base de IA de código abierto que puedan usarse para evaluar riesgo de inundaciones e incluso pronosticar rendimientos de cultivos.

Compartir datos tiene muchos beneficios y puede facilitar el acceso al conocimiento. Hacer que grandes volúmenes de datos sean más accesibles y utilizables puede mejorar la toma de decisiones en la gestión de desastres y en la recuperación a largo plazo.

**Ciencia ciudadana**

#### Ejemplo: Pruebas de calidad del agua en Beirut

Un científico ciudadano es una persona ciudadana o un científico aficionado que colabora con investigadores profesionales para ayudar a recolectar o interpretar datos en una escala espacial y temporal más amplia que la que los investigadores podrían alcanzar por sí mismos. Esta distribución de responsabilidades ayuda a que miembros del público participen en actividades científicas que finalmente los benefician, permitiendo que la investigación se realice a una escala más grande de lo que sería posible solo con investigadores profesionales. La ciencia ciudadana está ganando popularidad y reconocimiento como contribución valiosa a avances científicos.

Por ejemplo, como se reporta en el Capítulo 5 de *Contextualizing Openness: Situating Open Science*, se reclutaron voluntarios científicos ciudadanos en Beirut de 50 aldeas para ayudar a evaluar la calidad del agua local. Estos voluntarios recibieron formación para poder hacer las pruebas y, a su vez, no solo se recolectaron datos para informar avances científicos, sino que los científicos ciudadanos tuvieron la oportunidad de aprender a gestionar mejor sus recursos hídricos y mejorar condiciones, creando una interacción mutuamente beneficiosa. (Chan et al., 2019)

**Datos abiertos y el intercambio equitativo de conocimiento**

En última instancia, la distribución libre del conocimiento incrementa la participación en la ciencia.

En un ecosistema de investigación donde el conocimiento es una mercancía, con la moneda principal en forma de artículos publicados y conjuntos de datos acaparados, hacer que la investigación no esté disponible o sea difícil de obtener para la comunidad científica puede limitar el progreso científico y afectar negativamente los resultados.

#### Ejemplo: Reconocimiento del trabajo de investigadores africanos sobre ébola

Durante el brote de ébola de África occidental entre 2014 y 2016, investigadores de África occidental trabajaron activamente para recolectar datos de muestras de sangre, con el fin de comprender mejor el virus del ébola y ayudar a frenar la rápida propagación del virus. Sin embargo, la mayoría de las muestras de sangre se enviaron al extranjero, a Estados Unidos y Europa, donde investigadores usaron esos datos para escribir artículos sobre ébola. Como resultado, los datos tardaron mucho más en difundirse de regreso al público, y los investigadores de África occidental recibieron poco crédito. Según un artículo de 2019 en *Nature*, "esto frustró a investigadores en los países devastados por el virus, que esperaban que estudiar aspectos de la epidemia fortaleciera su capacidad de responder a futuros brotes de enfermedades infecciosas". (Maxmen, 2019)

Al fomentar una cultura de investigación transparente, donde el trabajo es reconocido adecuadamente, crearemos un modelo sostenible que incremente la transparencia y la calidad de la producción científica.

---

### Resumen de beneficios de los Datos Abiertos

Los datos abiertos que están disponibles para el escrutinio benefician la innovación científica al permitir un proceso científico más robusto, que se nutre de múltiples perspectivas. Esta apertura también permite la identificación temprana de hallazgos erróneos, así como la intervención temprana ante impactos negativos no previstos.

Los datos abiertos permiten que investigadores no tradicionales contribuyan al desarrollo científico y aporten sus hallazgos particulares. Con estos beneficios en mente, debemos recordar siempre que los datos abiertos requieren una consideración cuidadosa de sus posibles desventajas. Este módulo del currículo de Ciencia Abierta discute consideraciones importantes para la gestión responsable, la recolección y el uso de datos abiertos por parte de todos los actores involucrados.

### Beneficios para ti

Los datos abiertos también benefician tu investigación y tu carrera. Para empezar, eres tu propio colaborador futuro.

Hacer ciencia abierta no solo permite que otras personas comprendan y reproduzcan tus resultados, sino que también te permite hacer lo mismo. Implementar principios de ciencia abierta como buena documentación y control de versiones te ayuda a ti, a posibles colaboradores y a cualquier otra persona a comprender tus resultados. En 2 horas, 2 semanas o 2 años, todavía podrás entender lo que hiciste.

Beneficios específicos de abrir datos para ti como individuo:

- Nunca perderás acceso a tu trabajo previo, sin importar a qué institución estés afiliado. Muchos investigadores cambian de instituciones y organizaciones, y al tener tus datos accesibles públicamente en repositorios, siempre tendrás acceso a ellos.
- Tus datos pueden citarse y recibirás crédito.
- Según un estudio de 2020, las publicaciones que incluyen enlaces a datos se citan más. (Colavizza et al., 2020)

Además, implementar buenas prácticas de ciencia abierta puede fortalecer tus propuestas de financiamiento. Las agencias financiadoras están reconociendo que compartir investigación abiertamente genera mayor retorno de su inversión. Productos de investigación bien documentados también demuestran la calidad de tu trabajo, lo que ayuda en la comunicación pública y puede atraer colaboradores de calidad. A todo el mundo le gusta trabajar con personas confiables y que hacen bien su trabajo.

### Actividad 1.1 Revisión de Datos Abiertos

Tómate un momento para reflexionar sobre lo que significa para ti compartir datos.

<img style="width:100%;height:auto;" src="../images/media/image6.jpeg">

Fuente de la imagen: Nube de palabras "Open Research Data - the FAIRest Data is the Future of Science - Estonia national OpenAIRE event" por OpenAIRE, con licencia CC 4.0

La nube de palabras anterior muestra la variedad de significados e interpretaciones que las personas tienen sobre los datos abiertos. ¿Cuántos términos de la nube de palabras reconoces? ¿Hay alguno que sea nuevo para ti?

## Desafíos de los Datos Abiertos

Si bien los datos abiertos tienen muchos beneficios, también puede haber desafíos en su creación y uso. A lo largo de este módulo, discutimos muchos de estos desafíos y posibles soluciones. En esta sección veremos algunas de las preocupaciones más comunes junto con acciones para mitigarlas.

### Restricciones para compartir datos

Algunos datos solo deberían compartirse con mucho cuidado o directamente no compartirse. Razones para no compartir pueden incluir:

- Los datos incluyen secretos militares de un país o violaciones de intereses nacionales.
- Los datos incluyen información médica privada o datos personales identificables de un individuo.
- Los datos incluyen propiedad intelectual.

Es importante familiarizarse con requisitos, expectativas y limitaciones que afectarán el intercambio de tus datos, como políticas de tu agencia financiadora o institución, o leyes de protección de datos. Estos temas se discuten más adelante en otros módulos.

### Miedos comunes al compartir datos abiertos

#### NOTA: Discutiremos más adelante en este módulo muchos de los conceptos mencionados en la columna de discusión(mitigación).

|  |  |
|---|---|
| Miedo: Alguien reutilizará mis datos para publicar un resultado en el que estoy trabajando (por ejemplo, adelantarse) | Sí, esto puede pasar. Pero en muchos campos, si es claro que alguien está trabajando activamente en un problema, la decisión de otro de adelantarse puede traer una ganancia de corto plazo pero una pérdida de largo plazo. En ciencia, la reputación es muy importante y colaborar, por lo general, conduce a mayores éxitos de carrera. Si estás compartiendo tus datos, asegúrate de que tengan un identificador de objeto digital (DOI). Esto no impide que alguien use tus datos sin atribución, pero ayuda a que otros puedan citarlos fácilmente. Hay un artículo útil sobre esto [aquí](https://datascience.codata.org/articles/10.5334/dsj-2017-029). |
| Miedo: Interpretación errónea o mal uso | Proporciona información contextual suficiente (documentación) para permitir que otros comprendan plenamente tus datos y reducir este riesgo. |
| Miedo: Mis datos se usarán pero no se citarán | Si bien no es común que investigadores citen datos, la ética científica indica que deberías ser citado si se usa tu trabajo. Y recuerda citar datos de otros, para no contribuir al problema. |
| Miedo: Los datos son demasiado sensibles para compartir | Usa acceso controlado para ayudar a mantener sensibilidad y seguridad. |
| Miedo: Mis datos no serán útiles para nadie más | Nunca se sabe cómo pueden usarse los materiales. Marineros en los años 1800 recolectaron datos de temperatura que todavía hoy siguen siendo una parte importante de nuestro registro climático oceánico. (NPR, 2019) |

Estas son preocupaciones válidas al compartir datos abiertamente, pero como indica el movimiento global hacia la ciencia abierta, los beneficios generales superan las preocupaciones.

En última instancia, eres libre de implementar principios y recursos de datos abiertos en tu investigación para maximizar su impacto y cumplir con expectativas de patrocinadores y comunidad, a la vez que gestionas costos.

## Aplicación de los Principios FAIR

<img src="../images/media/image9.png" style="width:100%;height:auto;" />

Crédito de la imagen: Una caricatura que describe el intercambio de datos FAIR por Patrick Hochstenbach, con licencia CC0 1.0

---

### FAIR: Encontrables, Accesibles, Interoperables, Reutilizables

La gran mayoría de los datos hoy se comparten en línea. Aunque FAIR fue introducido en el Módulo 2, Lección 3, se ofrecen a continuación algunos detalles adicionales. Los Principios FAIR ayudan a que investigadores hagan un mejor uso de (y conecten a una audiencia más amplia con) sus datos científicos que lo que permitirían técnicas desactualizadas. Los datos FAIR son más valiosos para la ciencia porque son más fáciles de usar. Los datos pueden ser FAIR independientemente de si se comparten abiertamente o no. Si los datos se comparten abiertamente, ser FAIR ayuda con la reutilización y amplía el impacto científico de los datos.

Los Principios FAIR no abarcan instrucciones de implementación exhaustivas para cada tipo de datos, pero ofrecen ideas generales para mejorar la posibilidad de compartir y reutilizar. A veces se necesita un esfuerzo grupal y(o) un proceso largo de producción para que los datos y resultados sean FAIR. El proceso comienza en la etapa de planificación de un proyecto de investigación. Un Plan de Ciencia Abierta y Gestión de Datos (OSDMP, por sus siglas en inglés) bien coordinado suele ser necesario para el cumplimiento completo de FAIR, dependiendo del tamaño y del tipo de proyecto para el que se estén usando los datos.

**Información actualizada sobre los Principios FAIR puede encontrarse en el sitio de la Iniciativa GO FAIR**

[HAZ CLIC PARA APRENDER (ENLACE EXTERNO)](https://www.go-fair.org/)

Revisemos cómo hacer que los datos sean FAIR para tu comunidad.

*Selecciona cada pestaña para ver más información.*

<table>
  <thead>
    <tr>
        <th>ENCONTRABLES &#9745;</th>
        <th>ACCESIBLES</th>
        <th>INTEROPERABLES</th>
        <th>REUTILIZABLES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Para asegurar que los datos sean encontrables por quienes integran tu comunidad:</p>
            <ul>
            <li>Deposita los datos en repositorios para preservarlos a lo largo del tiempo.</li>
            <li>Asigna a tu conjunto de datos un identificador persistente (PID), como un identificador de objeto digital (DOI).</li>
            <li>Agrega metadatos ricos y autoexplicativos en tus archivos de datos y registra esos metadatos en un catálogo de metadatos, habilitando que tus datos queden correctamente curados.</li>
                <ul>
                <li>Ten en cuenta que algunas imágenes o archivos binarios no pueden indexarse o buscarse fácilmente y necesitarán archivos de metadatos complementarios o diccionarios para asegurar que puedan descubrirse en una búsqueda.</li>
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
        <th>ENCONTRABLES</th>
        <th>ACCESIBLES &#9745;</th>
        <th>INTEROPERABLES</th>
        <th>REUTILIZABLES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Para asegurar que los datos puedan ser accesibles para quienes integran tu comunidad:</p>
            <ul>
                <li>Archiva en un repositorio(centro) de datos con protocolos de acceso estandarizados.</li>
                <li>Los protocolos de acceso del repositorio deberían estar bien definidos y, de ser posible, soportar acceso entre máquinas.</li>
                <li>Proporciona información sobre cómo los usuarios pueden acceder a tus datos, idealmente de forma automatizada y basada en máquinas.</li>
                <li>Si el contenido completo no puede ponerse a disposición abierta por alguna razón (por ejemplo, sensibilidad de datos, acceso poco frecuente a los datos, problemas de almacenamiento), los metadatos igualmente pueden ponerse a disposición abierta para que los usuarios sepan a quién contactar para solicitar los datos (si es posible).</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>ENCONTRABLES</th>
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
                <li>Usa metadatos estandarizados existentes, si están disponibles, para minimizar problemas de "pérdida en la traducción" y soportar legibilidad por máquinas.</li>
                <li>El uso de terminologías, vocabularios y ontologías controladas es necesario para soportar interoperabilidad, pero puede que todavía no esté disponible en todos los campos de investigación.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>ENCONTRABLES</th>
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
                <li>Asegura que los metadatos describan con precisión los datos y sus variables, así como particularidades o limitaciones.</li>
                <li>Especifica licencias de uso claras para tus datos.</li>
                <li>Proporciona información precisa sobre procedencia en tus metadatos.</li>
                <li>Agrega suficiente información de metadatos para que tus datos puedan citarse adecuadamente cuando se usen.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

### El rol central de los metadatos al aplicar FAIR

Los metadatos son importantes para que motores de búsqueda encuentren datos y para que las personas puedan comparar fácilmente lo que se devuelve.

- Los metadatos son esenciales para implementar los Principios FAIR y habilitar que los datos puedan usarse por máquinas de forma automatizada.
- Mientras más ricos y autoexplicativos sean los metadatos, mejor podrán ser manejados por cualquiera que esté interesado en tus datos.

### Licenciar datos

Una licencia es un documento legal que le dice a los usuarios cómo pueden usar un conjunto de datos en particular. Si no licencias tu conjunto de datos, otros no pueden y no deberían reutilizarlo, incluso si tú quieres que lo hagan. Es imprescindible comprender las condiciones de licenciamiento de un conjunto de datos antes de reutilizarlo. Sin una buena comprensión de lo que una licencia permite, los usuarios pueden encontrarse con infracciones de copyright u otros problemas de propiedad intelectual.

Para asegurar la reutilización abierta de tus datos, puedes usar una licencia abierta. Una licencia abierta incluye lenguaje que describe la capacidad del usuario para acceder, reutilizar y redistribuir el conjunto de datos. Hay muchos tipos de licencias de datos que son abiertas en distintos grados, y se discutirán con mayor profundidad en la Lección 3, "Producir Datos Abiertos".

## Planificar para la apertura: usar el marco Usar, Producir, Compartir para Datos Abiertos

### Planes de Ciencia Abierta y Gestión de Datos

La mayoría de las agencias financiadoras y organizaciones científicas solicitan un plan de intercambio de investigación cuando se presenta una propuesta de proyecto. Un ejemplo de plan de ciencia abierta es el Plan de Ciencia Abierta y Gestión de Datos (Open Science and Data Management Plan, [OSDMP](https://science.nasa.gov/researchers/sara/faqs/osdmp)) de la NASA, para su Science Mission Directorate (SMD), que describe cómo se gestionará y se pondrá a disposición abierta la información científica que se producirá a partir de actividades científicas. El OSDMP incluye secciones sobre gestión de datos, gestión de software y el intercambio de publicaciones; las últimas dos se discutirán en módulos futuros. Si tu estudio tiene otros tipos de resultados, como muestras físicas, hardware u otros, deberías incluirlos en el plan también. Puede encontrarse más información y plantillas en [OSDMP en NASA](https://science.nasa.gov/researchers/sara/faqs/osdmp/).

Una buena práctica al comenzar tu recorrido de datos abiertos es crear un plan de gestión de datos (DMP), que va dentro del OSDMP. Este describe cómo gestionarás, preservarás y liberarás los datos durante y después de un proyecto de investigación. Elementos comunes de los DMP relevantes para datos abiertos incluyen una descripción de lo siguiente:

|  |  |
|---|---|
| ¿Qué? | Tipos de datos, volumen, formatos y (cuando corresponda) estándares. |
| ¿Cuándo? | El cronograma para archivado e intercambio de datos. |
| ¿Dónde? | Los repositorios previstos para datos archivados. |
| ¿Cómo? | Cómo el plan habilita la preservación a largo plazo de los datos. |
| ¿Quién? | Roles y responsabilidades de miembros del equipo para implementar el DMP. |

Investiga si tu institución de origen o tu fuente de financiamiento tiene orientación, estándares o plantillas para DMP. Otras organizaciones también tienen guías y ejemplos de DMP:

- [USGS](https://www.usgs.gov/data-management/data-management-plans) (enlace externo)
- [NOAA](https://marinedebris.noaa.gov/sites/default/files/DataManagementPlanGuidance%26Sample.pdf) (enlace externo)
- [NSF](https://new.nsf.gov/funding/data-management-plan) (enlace externo)

Se brindarán más detalles sobre cómo crear estos planes en la lección "De la teoría a la práctica".

### Flujo de trabajo científico

Existen diversos modelos de flujo de trabajo científico que explican la ciencia abierta. Los datos cumplen un rol central en el flujo de trabajo científico, donde los usuarios pueden proponerse crear nuevos datos, recolectar y empaquetar datos durante su proyecto y luego archivarlos para almacenamiento a largo plazo, uso y reutilización.

Para este currículo, usamos un modelo de flujo de trabajo derivado de Opensciency y The Turing Way. (OpenSciency Contributors, 2023; The Turing Way, 2024) Se utiliza para ilustrar que, independientemente del modelo de flujo de trabajo que uses, la adopción de datos abiertos se realiza a lo largo de todo el flujo de trabajo y de la producción de entregables asociados.

Si tu proyecto ya está en marcha, es una buena idea actualizar futuros lanzamientos de datos para adherir a principios de datos abiertos tanto como sea posible. Para proyectos nuevos, tus propuestas deberían incluir la creación de datos abiertos desde el inicio del proyecto.

<img src="../images/media/image10.jpeg" style="width:100%;height:auto;" />
Fuente de productos del flujo de trabajo de Ciencia Abierta: Opensciency.

En este currículo, el contenido está organizado según cómo podrías usarlo, producirlo y compartirlo. Parte de hacer ciencia abierta es construir sobre materiales de otros (usar), crear materiales propios (producir) y compartirlos para que otros puedan usar esos resultados (compartir). Las lecciones están organizadas alrededor de estos pasos en el flujo de trabajo científico.

El marco "Usar, Producir, Compartir" categoriza las tareas comúnmente usadas en la práctica de la ciencia abierta.

<img src="../images/media/image11.png" style="width:100%;height:auto;" />

### Roles en Usar, Producir, Compartir

Las personas que interactúan con datos en distintos puntos del flujo de trabajo científico pueden asumir diferentes roles. Es posible que estos roles se superpongan según requisitos del proyecto, el tamaño del equipo e incluso el financiamiento. Todos los miembros deberían usar principios de datos abiertos para realizar sus tareas. En general, los roles incluyen:

*Selecciona cada pestaña para ver más información.*

<table>
  <thead>
    <tr>
        <th>USUARIOS DE DATOS &#9745;</th>
        <th>PRODUCTORES DE DATOS (PROVEEDORES DE DATOS)</th>
        <th>QUIENES COMPARTEN DATOS (PUBLICADORES DE DATOS)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los usuarios de datos principalmente descubren, evalúan y utilizan datos en proyectos de investigación.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>USUARIOS DE DATOS</th>
        <th>PRODUCTORES DE DATOS (PROVEEDORES DE DATOS) &#9745;</th>
        <th>QUIENES COMPARTEN DATOS (PUBLICADORES DE DATOS)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los productores de datos a menudo procesan datos recolectados por un proyecto(actividad) y los empaquetan según principios de ciencia abierta.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>USUARIOS DE DATOS</th>
        <th>PRODUCTORES DE DATOS (PROVEEDORES DE DATOS)</th>
        <th>QUIENES COMPARTEN DATOS (PUBLICADORES DE DATOS) &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Quienes comparten datos tienen la responsabilidad de difundir los datos y generar conciencia sobre ellos hacia el público.</p>
        </td>
    </tr>
  </tbody>
</table>

Hacer que los datos sean abiertos (y FAIR) es un esfuerzo grupal: todos en la cadena de datos tienen un rol que cumplir.

## Lección 1: Resumen

En esta lección aprendiste:

- Los datos abiertos son un pilar esencial de la ciencia abierta. Compartir datos abiertamente con otros habilita reproducibilidad, transparencia, validación, reutilización y colaboración.
- Existen varios desafíos para crear datos abiertos, pero la mayoría tiene medidas de mitigación directas.
- Los Principios FAIR pueden aplicarse a datos para hacerlos más abiertos.
- Principios y tareas de datos abiertos se usan a lo largo de todo el flujo de trabajo científico.

## Lección 1: Autoevaluación

Responde las siguientes preguntas para evaluar lo que aprendiste hasta ahora.

*Pregunta*

**01/04**

Lee la afirmación y decide si es verdadera o falsa.

*Los datos abiertos pueden usarse libremente, reutilizarse y redistribuirse por cualquier persona, sujetos, como máximo, al requisito de atribuir y compartir bajo la misma licencia.*

- Verdadero
- Falso

*Pregunta*

**02/04**

Completa la oración:

*Hacer que los datos sean abiertos te ayuda a TI porque ____.*

- tus datos pueden citarse y recibirás crédito
- no perderás acceso a tus datos, incluso si cambias de institución
- es más probable que tus publicaciones se citen cuando incluyes enlaces a datos abiertos
- todas las anteriores

*Pregunta*

**03/04**

Elige los Principios FAIR de la lista a continuación. Selecciona todos los que correspondan.

- Reproducibles
- Reutilizables
- Responsables
- Encontrables
- Interactivos
- Interoperables
- Intercalados
- Accesibles
- Autorizables

*Pregunta*

**04/04**

¿Cuáles de las siguientes opciones pueden ayudar a que tus datos sean FAIR? Selecciona todos los que correspondan.

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
