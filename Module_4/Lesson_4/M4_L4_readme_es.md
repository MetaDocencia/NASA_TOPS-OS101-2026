# Lección 4: Compartir Código Abierto

## Contenidos

- [Planificar para compartir tu código](#planificar-para-compartir-tu-c%C3%B3digo)
- [Cuestiones legales y de seguridad](#cuestiones-legales-y-de-seguridad)
- [Cuándo: El cronograma para archivar y compartir código](#cu%C3%A1ndo-el-cronograma-para-archivar-y-compartir-c%C3%B3digo)
- [Dónde: Dónde compartir Código Abierto](#d%C3%B3nde-d%C3%B3nde-compartir-c%C3%B3digo-abierto)
- [Cómo: Cómo habilitar la reusabilidad del código](#c%C3%B3mo-c%C3%B3mo-habilitar-la-reusabilidad-del-c%C3%B3digo)
- [Quién: Roles y responsabilidades de las personas del equipo en la implementación del PGS](#qui%C3%A9n-roles-y-responsabilidades-de-las-personas-del-equipo-en-la-implementaci%C3%B3n-del-pgs)
- [Lección 4: Resumen](#lecci%C3%B3n-4-resumen)
- [Lección 4: Evaluación](#lecci%C3%B3n-4-evaluaci%C3%B3n)

## Descripción general

En esta lección aprenderás el proceso para compartir el software o el código que desarrollaste. Antes de comenzar, es necesario determinar si está permitido compartir el software o el código. Tu institución o la agencia que financia tu trabajo puede tener lineamientos específicos sobre cómo compartir software, los cuales pueden limitar el grado de apertura del código o del software. También es importante considerar cuándo y dónde debe compartirse el software o el código, qué roles son necesarios durante el proceso de compartición y cómo habilitar a otras personas para reutilizar o mantener el código.

## Objetivos de aprendizaje

Luego de completar esta lección, deberías poder:

- Describir qué significa compartir código para archivado o para desarrollo de código.
- Evaluar si corresponde compartir tu código y enumerar consideraciones importantes de seguridad.
- Describir buenas prácticas sobre cuándo y dónde compartir código.
- Recordar prácticas comúnmente utilizadas para ayudar a otras personas a reutilizar tu código.
- Enumerar los roles y responsabilidades asociados a compartir y mantener código compartido.

## Planificar cómo compartir el código

<img src="../images/media/image540_es.png" style="width:350px;height:auto;" />

Imagina que has estado trabajando en un fragmento de código y que una posible persona colaboradora se acerca porque quiere usar tu código en su proyecto. ¿Cuál es la mejor forma de compartirlo? ¿Por correo electrónico? ¿Cuándo deberías compartir el código y qué deberías incluir para asegurarte de que la otra persona pueda usarlo con facilidad? Desarrollar un plan para compartir antes de iniciar el proyecto te ahorrará tiempo y esfuerzo más adelante.

### ¿Qué significa “compartir” tu código?

Existen dos grandes categorías de compartición: compartir para el desarrollo y proporcionar un registro de largo plazo.

### Desarrollo de código abierto

Escribir código científico suele ser un proceso dinámico y colaborativo en el que participan varias personas, lo que hace que el código evolucione con el tiempo. En este tipo de proyectos, resulta beneficioso desarrollar código abierto desde el inicio en una plataforma pública de alojamiento de repositorios, como GitHub, Bitbucket o GitLab. Esto asegura que todas las actualizaciones se compartan de forma abierta en la web y puedan llegar a potenciales personas colaboradoras y usuarias casi en tiempo real.

### Archivado de código abierto

El archivado garantiza que el código científico sea accesible a largo plazo y puede satisfacer requisitos de archivado establecidos por agencias financiadoras u organizaciones. La accesibilidad a largo plazo ayuda a que otras personas puedan reproducir tus resultados mucho tiempo después de la publicación. El archivado por sí solo no promueve el desarrollo continuo ni la colaboración; se trata de una preservación estática y de largo plazo del código, no de su evolución.

### ¿Deberías compartir tu software?

Existen varias consideraciones legales y de seguridad que deben tenerse en cuenta al crear o utilizar software abierto.

- Cualquier software que crees suele considerarse propiedad intelectual y puede estar sujeto a las políticas de tu organización.
- Estas políticas pueden influir en cuán abiertamente puede compartirse el software y, por lo tanto, en la licencia que debe utilizarse.
- Descargar y contribuir a proyectos de software abierto puede estar regulado por las políticas de seguridad informática de tu organización.

En contraste, si el software fue creado con financiamiento externo (por ejemplo, gubernamental), algunas agencias financiadoras pueden exigir que el software se comparta de manera abierta.

### Profundización: planes de gestión de software (SMP)

¿Qué necesitamos considerar al momento de compartir? A continuación se presenta una lista de elementos que deberían incluirse en un plan de gestión de software:

- **Qué:** descripción de la gestión, preservación y liberación del software.
- **Cuándo:** el cronograma para archivar y compartir el código.
- **Dónde:** el lugar donde el software será compartido y archivado a largo plazo.
- **Cómo:** cómo habilitar la reutilización del software mediante la asignación de un DOI, una licencia, lineamientos de contribución, etc.
- **Quién:** roles y responsabilidades de las personas integrantes del equipo.

## Aspectos legales y de seguridad

<table>
  <thead>
    <tr>
        <th>ASPECTOS LEGALES &#9745;</th>
        <th>ASPECTOS DE SEGURIDAD</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Cualquier persona que escriba código o software de investigación debería familiarizarse con las políticas de su organización sobre la compartición y publicación de software. Las agencias financiadoras, tanto públicas como privadas, pueden tener requisitos estrictos sobre la apertura del software. En otros casos, la organización puede no permitir que el software se comparta.</p>
            <p>Las consideraciones legales pueden incluir preguntas como:</p>
            <ul>
                <li>¿Quién es titular del código o del software, la persona desarrolladora o la institución?</li>
                <li>¿Compartir (o no compartir) el código o el software viola las políticas de la agencia financiadora?</li>
                <li>¿Existen leyes o regulaciones locales que gobiernen la compartición de propiedad intelectual?</li>
                <li>¿Qué licencia de software es obligatoria?</li>
            </ul>
            <p><strong>Una vez que decidas participar o iniciar un nuevo proyecto de software abierto, familiarízate con las políticas y prácticas de tu organización.</strong></p>
            <p>Más información sobre aspectos legales en <a href="https://opensource.guide/legal/">Open Source</a> (enlace externo).</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>ASPECTOS LEGALES</th>
        <th>ASPECTOS DE SEGURIDAD &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>La seguridad es una preocupación al compartir código o software. Actores malintencionados pueden adjuntar código malicioso al software con el objetivo de infiltrarse en sistemas informáticos mediante vulnerabilidades de seguridad, exponiendo información sensible o propietaria y generando potenciales pérdidas económicas significativas. Los riesgos de seguridad deben considerarse al compartir código o software.</p>
            <p>Las consideraciones de seguridad pueden incluir:</p>
            <ul>
                <li>¿La política de tecnología de la información de tu organización permite descargar y utilizar el código en tu equipo?</li>
                <li>¿Qué tan confiable es el repositorio al que deseas contribuir?</li>
                <li>¿Existen problemas de seguridad abiertos asociados al código?</li>
            </ul>
            <p><strong>Una vez que decidas participar o iniciar un nuevo proyecto de software abierto, familiarízate con las políticas de tecnología de la información de tu organización.</strong></p>
            <p>Más información sobre aspectos de seguridad en <a href="https://opensciency.github.io/sprint-content/open-software/lesson2-pros-cons.html#security-concerns">OpenSciency</a> (enlace externo).</p>
        </td>
    </tr>
  </tbody>
</table>

### Compartir código creado con financiamiento de agencias de Estados Unidos

Muchas agencias federales permiten, e incluso exigen, la compartición del código creado bajo sus programas de financiamiento. Por ejemplo:

- **NASA**: “...estamos contactando activamente a proyectos dentro de NASA para que utilicen recursos para publicar código abierto”.
- **Departamento de Comercio de Estados Unidos**: exige que las agencias desarrollen planes para liberar al menos el 20 por ciento del código fuente desarrollado a medida como software de código abierto.
- **USGS**: considera que los lanzamientos de software son activos de dominio público y generalmente se ponen a disposición sin restricciones.

Si tu proyecto está financiado mediante una subvención, revisa la convocatoria original para verificar si la publicación del código está permitida u obligatoria, y si existen requisitos específicos sobre la gestión del software. Ante la duda, consulta con tu organización.

### Actividad 4.1: identificar las políticas de publicación de software de tu organización

<img style="width:350px;height:auto;" src="../images/media/lightbulb_es.png">

Supón que deseas iniciar un nuevo proyecto de software de código abierto:

- Identifica las políticas de tu organización sobre la publicación de software.
- ¿Cuál es el proceso para liberar software?
- ¿Alguien en tu organización debe aprobar esa liberación?
- ¿Existen políticas sobre colaboraciones externas?
- ¿Tu organización exige una atribución o reconocimiento específico?

#### Ideas clave: identificar las políticas de publicación de software de tu organización

Las políticas de liberación de código varían entre organizaciones y cada pieza de código es diferente. Por lo tanto, es importante no hacer suposiciones basadas en experiencias previas.

## Cuándo: el cronograma para archivar y compartir código

Planificar la compartición del código desde el inicio del proyecto facilita el proceso cuando llega el momento de hacerlo. El momento exacto en el flujo de trabajo en que decides compartir públicamente el código depende de tu trabajo y de los requisitos de la agencia financiadora, la organización o la editorial.

Por ejemplo, ¿qué indica NASA?

Si desarrollas software científico para un proyecto financiado por la Dirección de Misiones Científicas de NASA (SMD), debes cumplir con sus requisitos:

> “El software científico necesario para validar las conclusiones científicas de manuscritos revisados por pares resultantes de actividades científicas financiadas por SMD deberá hacerse públicamente disponible, a más tardar, en la fecha de publicación del artículo correspondiente. Esto incluye el software necesario para derivar los resultados presentados en figuras, mapas y tablas, así como software científicamente útil de modelos y simulaciones”.
> — NASA Science Mission Directorate, 2025

Otras organizaciones pueden tener lineamientos diferentes, por lo que siempre es recomendable verificar los requisitos específicos de la agencia financiadora u organización.

## Dónde: dónde compartir código abierto

### Consideraciones generales

<img src="../images/media/image197_es.png" style="width:100%;height:auto;" />
Crédito de la imagen: NASA

Al igual que los datos, el código puede compartirse de diversas maneras, como por correo electrónico o en un sitio web personal, pero estos métodos no son recomendados. Entonces, ¿dónde debería compartirse el código abierto?

En primer lugar, considera las políticas de tu institución o agencia financiadora, que pueden dictar dónde debes compartir el código y dónde está permitido hacerlo. Algunas agencias exigen repositorios de largo plazo específicos para el archivado del código. Además, tu disciplina científica puede contar con repositorios específicos para código abierto.

### Buenas opciones y prácticas para archivar código

- Archivar el código junto con un artículo en una revista de acceso abierto.
- Si el código se desarrolla activamente en un repositorio en línea como GitHub, crear una versión y archivarla en un repositorio de largo plazo con DOI (por ejemplo, Zenodo).
- Archivar el código en otros repositorios públicos de largo plazo, como Software Heritage.

### Paquetes de software sustanciales

Si tu código constituye un paquete de software significativo y es de interés para personas usuarias de distintas disciplinas, también puedes:

- Desarrollar el software en un repositorio público.
- Publicarlo en repositorios utilizados por gestores de paquetes.
- Presentarlo en conferencias.
- Publicarlo en revistas dedicadas al software abierto.
- Someterlo a revisión por pares en comunidades especializadas.

Compartir en GitHub es un paso importante, pero puede no ser suficiente si tu organización exige un DOI proveniente de un repositorio de archivado de largo plazo.

## Cómo: cómo habilitar la reutilización del código

Una vez que compartiste el código de manera adecuada, es fundamental asegurarte de que otras personas, o tú mismo en el futuro, puedan reutilizarlo fácilmente.

### Asignar una licencia

Asignar una licencia adecuada es necesario para que otras personas sepan cómo pueden utilizar tu código. En GitHub, esto se realiza agregando un archivo llamado LICENSE y seleccionando una plantilla de licencia.

### Hacer que el código sea citable

Agregar código a un repositorio no es suficiente para archivarlo. Para que sea citable, es necesario asignarle un identificador persistente, como un DOI. Esto puede lograrse mediante una publicación revisada por pares o archivando el código en un repositorio de largo plazo, como Zenodo.

### Facilitar la citación del código

La información sobre cómo citar el código puede incluirse en el README u otra documentación. También es recomendable agregar un archivo CITATION al repositorio.

### Agregar lineamientos para contribuciones

Si esperas recibir aportes de la comunidad, es una buena práctica incluir archivos CONTRIBUTING y CODE_OF_CONDUCT que detallen expectativas y normas de interacción.

## Quién: roles y responsabilidades del equipo en la implementación del SMP

Al redactar un SMP, es importante definir los roles y responsabilidades necesarios para compartir y, si corresponde, mantener el código. Algunos roles posibles incluyen:

- Quién subirá el código a un repositorio público y asignará la licencia.
- Quién se encargará de la documentación.
- Quién ayudará con la reutilización del código.
- Quién mantendrá el código y responderá a aportes de la comunidad.

No todos estos roles son necesarios en todos los proyectos. Es importante contar con un proceso transparente para asignarlos.

### Responsabilidades posteriores a la compartición

Si el código está pensado para que otras personas lo utilicen, la persona desarrolladora debería aclarar si el código será mantenido.

- Informar si se planea mantener o no el código.
- Documentar el estado de desarrollo del proyecto.
- Considerar transferir la responsabilidad si no se cuenta con tiempo o financiamiento para el mantenimiento.
- Responder a solicitudes de mejoras y correcciones en la medida de lo posible.

## Lección 4: Resumen

En esta lección aprendiste los pasos clave para compartir software abierto:

- **¿Compartir o no?** Deben respetarse las políticas institucionales y de financiamiento.
- **¿Cuándo compartir?** Seguir las directrices de la organización, agencia financiadora o editorial.
- **¿Dónde compartir?** Depende de si se archiva o se busca colaboración activa.
- **¿Cómo habilitar la reutilización?** Asignando un DOI, una licencia e incluyendo información de citación y contribución.
- **¿Quién ayuda a compartir?** Definir roles y responsabilidades para compartir y mantener el código.

## Lección 4: Autoevaluación

Responde las siguientes preguntas para evaluar lo aprendido.

### Referencias citadas

- NASA Science Mission Directorate. (2025). [https://assets.science.nasa.gov/content/dam/science/cds/open-science/SMD%20Open-Source%20Science%20Guidance%20v2.2%2020250205.pdf](https://assets.science.nasa.gov/content/dam/science/cds/open-science/SMD%20Open-Source%20Science%20Guidance%20v2.2%2020250205.pdf)
