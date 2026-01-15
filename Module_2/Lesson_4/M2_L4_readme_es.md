# Lección 4: Herramientas para Código Abierto

## Contenidos

-   [Introducción al Código Abierto](#introducci%C3%B3n-al-c%C3%B3digo-abierto)
-   [Herramientas para el control de versiones](#herramientas-para-el-control-de-versiones)
-   [Herramientas para editar código](#herramientas-para-editar-c%C3%B3digo)
-   [Herramientas adicionales](#herramientas-adicionales)
-   [Lección 4: Resumen](#lecci%C3%B3n-4-resumen)
-   [Lección 4: Evaluación](#lecci%C3%B3n-4-evaluaci%C3%B3n)

## Descripción general

Ahora que comprendes los conceptos de Datos Abiertos, ¿qué herramientas se usan para el Código Abierto? En esta lección presentaremos algunos consejos y herramientas útiles para trabajar con código, para que puedas compartirlo y reutilizarlo. Aprenderemos acerca de las diversas herramientas disponibles para desarrollar, almacenar y compartir Código Abierto, desde el control de versiones hasta el software de edición de código y los contenedores. En definitiva, estas herramientas digitales existen para gestionar y alojar código y también para fomentar la colaboración.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Explicar los beneficios de usar herramientas para el desarrollo de Código Abierto.
- Definir el control de versiones y comprender cómo favorece la colaboración en el desarrollo y en la gestión del código.
- Listar algunas herramientas para editar software y sus características.
- Distinguir entre repositorios de software y archivos de software.


## Introducción al Código Abierto

En la Lección 3 aprendimos sobre herramientas útiles para trabajar con datos científicos. Ahora presentaremos un panorama general de herramientas de uso común que nos ayudan a escribir y ejecutar código para explorar, analizar y visualizar datos científicos. Más adelante, en el Módulo 4, "Código Abierto", discutiremos con mayor detalle qué significa hacer que el código sea abierto y recorreremos los pasos para encontrar, crear y compartir código.

Comprender cómo trabajar con código científico es esencial en el panorama actual de investigación basada en datos. Las herramientas presentadas en esta lección abarcan una amplia gama de recursos diseñados para simplificar, mejorar y optimizar el proceso de desarrollo, mantenimiento y colaboración en el desarrollo de código para la investigación científica. Permiten crear código robusto y eficiente, a menudo aprovechando la sabiduría colectiva de la comunidad de software de Código Abierto. En la búsqueda de reproducibilidad y transparencia, estas herramientas también pueden facilitar el intercambio y la difusión del código científico, fomentando la colaboración y asegurando que las bases de la investigación científica se mantengan abiertas y accesibles para todas las personas.

### Precedente histórico para crear Código Abierto: sistema operativo GNU/Linux

¿La idea de escribir código de forma abierta es un concepto nuevo? ¡No!

#### Contexto: Desarrollo del kernel (núcleo) Linux para sistema operativo

Historia de Linux  
[HAZ CLIC PARA CONOCER MÁS (ENLACE EXTERNO)](https://en.wikipedia.org/wiki/History_of_Linux)

- Comenzó en 1991 por Linus Torvalds.
- Casi de inmediato fue publicado para su revisión.
- Muchos ojos → Se encuentran muchos errores → Muchas correcciones.

## Herramientas para el control de versiones

### Control de versiones

El control de versiones (en inglés, *version control*) es la práctica de rastrear y gestionar cambios realizados en el código u otros tipos de archivos. Puede que nos resulte familiar si lo asociamos con el "seguimiento de cambios" en programas como Microsoft Word. Eso es una forma de control de versiones, aunque no está bien adaptada al trabajo con código. El control de versiones se considera una práctica estándar en la comunidad de desarrollo de software, lo que simplifica la gestión del código a lo largo del tiempo.

La forma general en que usamos el control de versiones comienza por crear una carpeta en tu plataforma informática con el sistema de control de versiones que estés usando. Un sistema de control de versiones rastrea automáticamente todos los cambios realizados por quienes contribuyen, lo que te permite trabajar sin conexión y volver más tarde con actualizaciones. Primero, escribes el código como lo harías normalmente en el editor de código que prefieras. Después de haber escrito algo de código o realizado algunas actualizaciones en el código existente, confirmas los cambios (lo que se conoce como hacer un *commit*) en el sistema de control de versiones para crear una especie de "punto de control" al que luego puedes volver si es necesario. Luego, agregas o actualizas más código y vuelves a hacer *commit*. Cada *commit* requiere que agregues un mensaje breve que describa los cambios realizados. Estos mensajes funcionan como metadatos que aseguran que colaboradores, futuros usuarios y tu yo del futuro entiendan tu proceso de desarrollo en un momento dado.

Esto puede sonar como un proceso simple y, en muchos sentidos, lo es. Entonces, ¿por qué es tan importante? Especialmente al programar, la posibilidad de crear una captura en el tiempo de un fragmento de código puede resultar muy útil. Por ejemplo, puedes tener un fragmento de código que produce el resultado esperado, pero luego quieres agregar una nueva función. Podrías copiar ese archivo de código para no perder el estado actual antes de trabajar en un nuevo archivo. Esto rápidamente puede resultar engorroso cuando existen varios archivos que son diferentes versiones de la misma pieza de código. O, en lugar de crear un nuevo archivo, puedes escribir el código de la nueva función directamente en el archivo original, pero ahora este arroja errores cuando intentas ejecutarlo, y es difícil recordar qué líneas se añadieron desde la última vez que el código se ejecutó sin errores. Usando el control de versiones, estos problemas se resuelven porque puedes volver al punto de control cuando el código se ejecutó correctamente, y así evitar la necesidad de crear múltiples copias para guardar el trozo de código original.

Hay muchas otras funciones de los sistemas de control de versiones, como el concepto de "ramas" (en inglés, *branches*) que te permiten trabajar en nuevas actualizaciones de un fragmento de código de manera independiente y en paralelo al código original. Una rama es una desviación del código original, pero puede fusionarse con él cuando se desee. Todos estos conceptos son aún más útiles cuando se colabora con otros usando plataformas de control de versiones, una práctica colaborativa que se discutirá más adelante en esta lección.

### Tipos de control de versiones de software

Hay dos estilos principales de sistemas de control de versiones de software:

<table>
  <thead>
    <tr>
        <th>CENTRALIZADO &#9745;</th>
        <th>DISTRIBUIDO (MÁS POPULAR)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <ul>
              <li>Una única copia "principal" de la base de código</li>
              <li>Debe interactuar con un servidor específico</li>
              <li>Ejemplo: Subversion (SVN)</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>CENTRALIZADO</th>
        <th>DISTRIBUIDO (MÁS POPULAR) &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Control:</p>
            <p>El sistema de cada persona que desarrolla puede conservar una copia del código base.<br>
            Ejemplos:</p>
            <ul>
              <li>Git</li>
              <li>Mercurial</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

Utilizar un sistema distribuido de control de versiones como Git te da más flexibilidad.

**Ejemplo: Git**

El sistema de control de versiones más popular para el desarrollo de software es Git. Git es un sistema de Código Abierto que se usa habitualmente junto con sitios web de alojamiento de software como GitHub y GitLab (más información sobre ellos en la siguiente sección), que permiten colaborar y compartir código. También puedes usarlo en tu computadora local cuando escribes tu propio código. Git suele ejecutarse en la línea de comandos, pero también existen otras interfaces para usar Git, incluyendo GitHub Desktop y algunos editores de código que ya incluyen integración con Git. Más adelante en esta lección se darán más ejemplos.

<img src="../images/media/image33_es.jpg" style="width:350px;height:auto;" />

[https://xkcd.com/1597/](https://xkcd.com/1597/)

---

Git es muy potente y ampliamente utilizado. Según una encuesta de desarrolladores de Stack Overflow (2022 Developer Survey, 2022), más del 87% de las personas que desarrollan software usan Git, pero eso no significa que sea sencillo de aprender. Si Git te resulta confuso al principio, ¡no estás solo! Para una capacitación en profundidad sobre Git, consulta la lección de Software Carpentry "[Control de versiones con Git: Resumen y configuración](https://swcarpentry.github.io/git-novice/)" (enlace externo, en inglés).

### Plataformas de control de versiones

Las plataformas de control de versiones, normalmente plataformas web de alojamiento de software, amplían la utilidad del control de versiones al ofrecer un lugar centralizado para almacenar y colaborar en el código. Estas plataformas también ofrecen muchas otras funciones útiles para el desarrollo y el intercambio de código.

Algunos ejemplos de plataformas de control de versiones:

- GitHub: plataforma basada en Git que permite la colaboración y el seguimiento del historial del código. Propiedad de Microsoft.
- GitLab: una plataforma basada en Git que también ofrece funcionalidades DevOps (de desarrollo y operaciones) y CI/CD (integración y despliegue continuo).
- BitBucket: una plataforma que puede alojar repositorios Git y Mercurial. Propiedad de Atlassian.

GitHub es una de las plataformas más populares, por lo que en el resto de esta sección daremos ejemplos de cómo utilizar GitHub. Es importante destacar que GitHub es donde se encuentra la mayoría de los paquetes de software de Código Abierto por lo que, para aquellas personas que están interesadas en involucrarse más con la comunidad de software de Código Abierto, ¡GitHub es una herramienta esencial para aprender a usar!

**Ejemplo: GitHub**

GitHub es un repositorio de software en línea basado en la nube que se integra con Git y ofrece muchas otras características que ayudan en el desarrollo de código en colaboración, su evaluación y publicación. Antes de avanzar en algunas de estas características, es importante entender cómo GitHub actúa como un repositorio remoto cuando utiliza sistemas de control de versiones como Git.

Si volvemos a la idea general de utilizar sistemas de control de versiones, GitHub puede incorporarse como un repositorio remoto que aloja código. Después de crear un "punto de control" (eninglés, checkpoint) en Git, es posible cargar a GitHub una copia de la fotografía actual del código. Hay varias razones para hacerlo:

- Para que funcione como copia de seguridad de tu trabajo (ahora se almacena en un servidor remoto al que puedes acceder incluso si tu computadora muere).
- Para compartir tu código con otra personas (más sobre esto más adelante en este curso).
- Para que otras personas colaboren con tu código. Subiéndolo a GitHub, tu código puede ser accesible para quienes quieran añadir mejoras.

Vamos a ampliar algunas de las herramientas de colaboración de GitHub. Algunas de estas funcionalidades incluyen:

<table>
  <colgroup>
    <col style="width: 49%" />
    <col style="width: 49%" />
  </colgroup>
  <thead>
    <tr class="header">
      <th>Término</th>
      <th>Descripción/Definición</th>
    </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td>Rastreo de problemas (issues)</td>
      <td>
        Realizar un seguimiento de las solicitudes de funciones, errores y otras actualizaciones a través de GitHub Issues. GitHub también permite utilizar etiquetas y asignar personas a las tareas para ayudar a organizarlas
      </td>
    </tr>
    <tr class="odd">
      <td>Foros de discusión del proyecto</td>
      <td>
        GitHub permite un foro de discusión en línea donde es posible hacer y responder preguntas y mantener discusiones comunitarias.
      </td>
    </tr>
    <tr class="odd">
      <td>Seguimiento de contribuciones</td>
      <td>
        GitHub tiene una forma sencilla de llevar un registro de las contribuciones de código sugeridas (llamadas "Pull Requests") por diferentes personas.
      </td>
    </tr>
    <tr class="odd">
      <td>Herramientas de revisión de código</td>
      <td>
        GitHub dispone de un amplio conjunto de herramientas para revisar y aceptar (o rechazar) las contribuciones de terceros (o las tuyas propias), como los comentarios en línea y los cambios fácilmente visibles en archivos individuales.
      </td>
    </tr>
    <tr class="odd">
      <td>Permisos personalizados</td>
      <td>
        Elige quién tiene autorización para actualizar el código. Esto ayuda a que tengas la seguridad de que solo quienes tienen permiso pueden actualizar el código que compartiste en GitHub, y también a que otras personas se sientan seguras para sugerir actualizaciones sin preocuparse de que puedan sobrescribir accidentalmente el código existente.
      </td>
    </tr>
  </tbody>
</table>

Todas estas funciones son excelentes para permitir la colaboración asíncrona entre equipos. La mayoría de los paquetes de Código Abierto científico utilizan GitHub para el desarrollo de su código principal. Ten en cuenta que hay muchas más funciones de GitHub en las que no profundizamos aquí y que permiten la colaboración, así como flujos de trabajo automatizados y mucho más. Para aprender más sobre GitHub, echa un vistazo a estas referencias:

-  [Cómo usar Git y GitHub: introducción para principiantes (freecodecamp.org)](https://www.freecodecamp.org/news/introduction-to-git-and-github/) (enlace externo)
-  [Primeros pasos con GitHub — Pythia Foundations (projectpythia.org)](https://foundations.projectpythia.org/foundations/getting-started-github.html) (enlace externo)

[Cita al Project Pythia: [https://foundations.projectpythia.org/preamble/how-to-cite.html](https://foundations.projectpythia.org/preamble/how-to-cite.html)]

### Resumen de las ventajas de utilizar el control de versiones y las plataformas de control de versiones

- Posibilita de retrotraer los cambios hasta cualquier punto.
- Facilita la colaboración con otras personas.
- Mantiene un directorio ordenado, sin necesidad de hacer varias copias de los archivos.
- Proporciona un sistema de copia de seguridad específico para tu trabajo.

## Herramientas para editar código

### Entorno de Desarrollo Integrado (IDE)

Un Entorno de Desarrollo Integrado (IDE, por sus siglas en inglés) desempeña un papel importante en el desarrollo de Código Abierto ya que ofrece un conjunto de herramientas a las personas investigadoras, científicas, y que desarrollan software para editar código. Se trata de una aplicación informática que agiliza todo el proceso de creación, comprobación y gestión de código para la investigación científica y el análisis de datos. Al proporcionar una plataforma todo en uno, un IDE permite a quienes investigan escribir, depurar y optimizar el código de forma más eficiente, fomentando la colaboración y la reproducibilidad en proyectos científicos de Código Abierto.

En la Ciencia Abierta, donde la transparencia y la accesibilidad son primordiales, los IDEs suelen incorporar sistemas de control de versiones como Git para facilitar la colaboración y garantizar que un código base de investigación esté disponible para que otras personas lo usen y mejoren. Además, muchos IDEs se integran con herramientas de análisis y visualización de datos. Esto facilita el análisis y la interpretación de datos y contribuye, en última instancia, al avance de las prácticas científicas de Código Abierto.

Si estuvieras en una sala con 10 personas que trabajan en desarrollo de software y le preguntaras a cada una cuál es su editor de código favorito, obtendrías muchas respuestas diferentes. En esta lección, repasaremos algunas de las opciones más conocidas.

### Kernels

Un *kernel* (en español, núcleo) es el código central que conforma la base del sistema operativo de una computadora. Gestiona los recursos del sistema e interactúa con el hardware. El *kernel* es un puente entre el hardware y el software.

 **Edición de código fuente y kernels: el valor de los IDE y los kernels**

Los IDEs pueden aportar muchas herramientas útiles a tus trabajos. Ya no se trata únicamente de editar código. Los IDEs modernos y robustos pueden hacer la mayoría de las cosas que se listan aquí, y aún más. Se puede usar un IDE sin ejecutar en un *kernel*; se puede usar un *kernel* sin haber desarrollado código en un IDE. Sin embargo, pueden trabajar de la mano.

<table>
  <thead>
    <tr>
        <th>Entorno de Desarrollo Integrado (IDE) &#9745;</th>
        <th>Kernel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Edición de código fuente:</p>
            <ul>
              <li>Resaltado de sintaxis</li>
              <li>Advertencias de errores (en inglés, bugs)</li>
            </ul>
            <p>Plugins</p>
            <ul>
              <li>Depuradores (en inglés, debuggers)</li>
              <li>Gestión de memoria</li>
              <li>Control de versiones</li>
              <li>Automatización de compilación</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>Entorno de Desarrollo Integrado (IDE)</th>
        <th>Kernel &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <ul>
              <li>Entorno de ejecución</li>
              <li>Como una máquina virtual</li>
              <li>Aísla el área de trabajo</li>
              <ul>
                  <li>Ajusta configuraciones</li>
                  <li>Fácilmente replicable</li>
              </ul>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

**Ejemplo de IDE: Visual Studio Code**

El IDE más popular hoy en día, Visual Studio Code de Microsoft (o VS Code), es muy completo sin ser pesado.

<img src="../images/media/image34_es.png" style="width:100%;height:auto;" />
pantalla de inicio del VS Code donde se muestran las principales combinaciones de teclas para las funciones de "Mostrar todos los comandos"; "Abrir archivo o carpeta"; "Abrir reciente" y "Crear un nuevo archivo sin título". [Captura de pantalla] (2023). Microsoft Virtual Studio. [https://visualstudio.microsoft.com/](https://visualstudio.microsoft.com/) (enlace externo)

- Dispone de una opción de "modo oscuro" que es más agradable a la vista para largas sesiones de codificación.
- Proporciona el resaltado de sintaxis y una ventana de terminal integrada.
- También cuenta con una gran cantidad de complementos para conectarse a servidores, sistemas de control de versiones y resolución de problemas. Dispone de varios complementos que pueden analizar el código en busca de fallas y errores, y contribuyen a que el equipo codifique con un "estilo" consistente. Esto facilita el mantenimiento del código en el futuro.
- Si la línea de código contiene un error obvio, el IDE mostrará una marca roja, igual a como si se hubiera escrito algo mal en un documento de Word.

A continuación hay un ejemplo de un desarrollador que, por accidente, escribió un signo igual cuando debía escribir dos puntos. VS Code detectó el error y, cuando el desarrollador pasó el cursor por encima del subrayado rojo, VS Code explicó cuál era el error y ofreció llevarlo a documentación adicional.

 <img src="../images/media/image35_es.png" style="width:100%;height:auto;" />
 Ejemplo de fragmento de código. La captura de pantalla muestra que VS Code detectó un error en el código y, al pasar el cursor sobre la indicación visual, explicó cuál era el error (colon expected) y ofreció llevarlo a una documentación adicional. [Captura de pantalla] (2023). Microsoft Virtual Studio. [https://visualstudio.microsoft.com/](https://visualstudio.microsoft.com/) (enlace externo)

Otra función útil en VS Code (así como en muchos otros editores de código) es la integración con Git. En lugar de usar una ventana de terminal, puedes integrar Git fácilmente en tu flujo de trabajo.

Desde VS Code puedes:

- advertir fácilmente las modificaciones en tu código.
- Crear una rama.
- Subir tus cambios directamente a GitHub.
- Descargar cambios de otros miembros del equipo a tu sistema local.

 **Ejemplo de IDE: RStudio – IDE**

Mientras que VS Code es un entorno de desarrollo integrado (en inglés, Integrated Development Environment, IDE) más genérico donde puedes utilizar complementos para especializarlo, también existen IDEs, como RStudio, que tienen características especializadas para lenguajes específicos desde el principio.

Las personas investigadoras que realizan análisis estadísticos tienden a utilizar los lenguajes de programación de R y Python. RStudio tiene herramientas integradas para ese mismo propósito, incluyendo la visualización de datos.

<img src="../images/media/image36_es.png" style="width:100%;height:auto;" />  
 Ejemplo de RStudio [Captura de pantalla] (2023). RStudio. [https://en.wikipedia.org/wiki/File:RStudio_IDE_screenshot](https://en.wikipedia.org/wiki/File:RStudio_IDE_screenshot) (enlace externo)

### Editores de texto plano para programar

La mayoría de los ordenadores portátiles o de escritorio que ejecutan sistemas operativos estándar (Windows, MacOS, Linux) tienen múltiples editores de texto plano preinstalados que se pueden utilizar para programar. Es beneficioso saber cómo utilizar al menos uno, porque hace que la edición de programas y archivos sea un proceso rápido.

<table>
  <colgroup>
    <col style="width: 49%" />
    <col style="width: 50%" />
  </colgroup>
  <thead>
    <tr class="header">
      <th><strong>VENTAJAS</strong></th>
      <th><strong>DESVENTAJAS</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td>
        <ul>
        <li>Ligeros</li>
        <li>Muchos se distribuyen nativamente con el sistema operativo (SO)</li>
        </ul>
      </td>
      <td>
        <ul>
        <li>No hay complementos que ayuden a encontrar fallas, errores, etc.</li>
        <li>Puede no tener resaltado de sintaxis</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### Cuadernos computacionales

Un cuaderno computacional es un entorno de computación virtual e interactivo que combina la ejecución de código, la documentación y la visualización de datos en una sola interfaz. Estos cuadernos se usan ampliamente en los campos de ciencias de datos y programación. Ejemplos populares son Jupyter Notebooks y R Notebooks. Permiten a los usuarios escribir y ejecutar código paso a paso, proporcionando una plataforma eficiente para el análisis de datos, la investigación y la programación colaborativa, con el beneficio añadido de integrar texto enriquecido (incluidas ecuaciones), imágenes y gráficos para una documentación y comunicación claras.

**Ejemplo: Jupyter Notebook y JupyterLab**

<img style="width:350px;height:auto;" src="../images/media/jupyterlogo.jpg">
Fuente de la imagen: "Jupyter" y los logos de Jupyter son marcas registradas o marcas comerciales de LF Charities, usadas por OS101 con permiso.

Los cuadernos de Jupyter son aplicaciones web de Código Abierto que se usan ampliamente para crear documentos computacionales. Pero antes de profundizar en Jupyter Notebooks, queremos dejar claro que Jupyter Notebooks es una de muchas plataformas en el ecosistema de Jupyter:
Jupyter Notebook es una aplicación web de Código Abierto ampliamente utilizada para la creación de documentos computacionales. Pero antes de sumergirnos en Jupyter Notebook, queremos dejar en claro que Jupyter Notebook es una de las muchas plataformas del ecosistema de Jupyter:

- Jupyter Notebook -- un intérprete de comandos de lenguaje contenido para programación interactiva, que muestra la salida en línea con las entradas
- JupyterLab -- una interfaz de usuario integrada en el navegador que muestra múltiples ventanas para cuadernos de notas, terminales y edición de código
- JupyterHub -- software intermediario (en inglés, middleware) para ejecutar entornos de computación interactivos compartidos, incluyendo JupyterLab y Jupyter Notebook, en infraestructura de computación compartida (como en la Nube)

Usaremos Jupyter Notebook como ejemplo de un cuaderno computacional y discutiremos cómo se relaciona JupyterLab con Jupyter Notebook. La siguiente sección sobre plataformas de cómputo hablará de JupyterHub.

Esta captura de pantalla muestra un ejemplo de un Jupyter Notebook que integra texto enriquecido (con encabezados y enlaces), ecuaciones, código y la salida interactiva de esas líneas de código, incluyendo un gráfico. Esta captura deja claro por qué se lo llama un cuaderno computacional: se parece a un cuaderno de laboratorio que podrías haber escrito a mano en la escuela.

<img src="../images/media/image38_es.png" style="width:100%;height:auto;" />
Ejemplos de Jupyter Notebook [Capturas de pantalla] (2023). [Project Jupyter | Home](https://jupyter.org/) (enlace externo)

Jupyter soporta muchos lenguajes de programación. Un dato curioso: el nombre "Jupyter" se refiere a los tres idiomas principales admitidos por Jupyter: Julia, Python, y R.

JupyterLab es un entorno de desarrollo interactivo basado en un navegador compatible con Jupyter Notebook y esta diseñado en un entorno más flexible que permite muchas características útiles. Una de estas características es la integración con Git, como vimos para otros IDEs como Visual Studio Code.

Dado que Jupyter Notebooks permite integrar código con visualizaciones y texto, puede servir como herramienta para llevar adelante proyectos de investigación y crear documentos computacionales fáciles de compartir para educación, colaboración o comunicación científica. Con capacidades de texto enriquecido, como encabezados, cursivas, enlaces y mucho más, puedes crear un documento legible que contenga código ejecutable. Estas son algunas de las razones por las que JupyterLab y Jupyter Notebooks se usan ampliamente en diversas disciplinas, incluida la investigación computacional y la ciencia de datos.

#### Para más información sobre los productos de Jupyter y su comunidad, consulta su sitio web.

[HAZ CLIC PARA APRENDER (ENLACE EXTERNO)](https://jupyter.org/)

Si quieres sumergirte en el tema, consulta la lección "Primeros pasos con Jupyter" del Proyecto Pythia, orientada a personas sin conocimientos previos de programación.

### Actividad 4.1: Ejecuta un Jupyter Notebook desde tu navegador

Usemos un ejemplo del Proyecto Pythia para mostrar cómo los cuadernos computacionales pueden ser usados en la ciencia. Proyecto Pythia es un centro educativo para la comunidad geocientífica. Tienen algunos grandes recursos de aprendizaje y ejemplos de cuadernos de investigación, desarrollados y mantenidos por la comunidad y de libre acceso.

En esta actividad, ejecutarás código Python ya escrito en un Jupyter Notebook desde tu navegador para generar gráficos relacionados con el fenómeno El Niño-Oscilación del Sur (o ENOS). Utilizarás el paquete de software de Código Abierto llamado Xarray para leer los datos de temperatura de la superficie del mar de un modelo climático global (Modelo Comunitario del Sistema Tierra, en inglés Community Earth System Model, CESM) y crear algunas visualizaciones de eventos ENOS a lo largo de los últimos 20 años. El objetivo es recrear el siguiente gráfico para los últimos aproximadamente 20 años. Esta figura muestra los años y la magnitud de los eventos de El Niño en rojo y de los eventos de La Niña en azul.

![](../images/media/image39.jpeg)  
Crédito de la imagen: "ONI: 1950-2018: Base:1960-1989". [https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni](https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni) (enlace externo)

---

Sigue estos pasos:

1. Navega a la lección “[Calculating ENSO with Xarray (Calculando ENOS con Xarray)](https://foundations.projectpythia.org/core/xarray/enso-xarray.html)” (enlace externo)
2. Localiza y selecciona la opción "Binder" que se encuentra dentro del desplegable del icono del cohete (en inglés, Rocket). Esto abrirá la lección como un Jupyter Notebook ejecutable que corre en la Nube. Ten en cuenta que el Cuaderno Computacional puede tardar varios minutos en configurarse.
![](../images/media/calculatingenso_es.png)  
Ejemplo de Notebook Paso 2. [Captura de pantalla] (2023). Calculating ENSO with Xarray [https://foundations.projectpythia.org/core/xarray/enso-xarray.html](https://foundations.projectpythia.org/core/xarray/enso-xarray.html) (enlace externo)
3. Después de cargar el Cuaderno Computacional, deberías encontrarte ahora en una interfaz de edición con un arbol de archivos y una sección de edición de los archivos del árbol.Nota -- ¡Esto realmente utiliza la vista de JupyterLab!
![](../images/media/calculatingenso2_es.jpg)  
Ejemplo de Notebook Paso 3. [Captura de pantalla] (2023). Calculating ENSO with Xarray [https://foundations.projectpythia.org/core/xarray/enso-xarray.html](https://foundations.projectpythia.org/core/xarray/enso-xarray.html) (enlace externo)
4. Puedes tomarte un poco de tiempo para repasar el texto y el código del Cuaderno Computacional, pero ten en cuenta que esta lección presupone muchos conocimientos previos. Está bien si no lo entiendes todo. ¡Aún puedes apreciar los bonitos gráficos que estás a punto de hacer!
5. ¡Ahora ya puedes ejecutar el Cuaderno Computacional! Para hacer eso, puedes ir al menú "Run" (Ejecutar) y elegir "Run All Cells" (Ejecutar todas las celdas)
![](../images/media/calculatingenso3_es.jpg)  
Ejemplo de Notebook Paso 5. [Captura de pantalla] (2023). Calculating ENSO with Xarray [https://foundations.projectpythia.org/core/xarray/enso-xarray.html](https://foundations.projectpythia.org/core/xarray/enso-xarray.html) (enlace externo)
6. Esto sólo debería tomar unos pocos segundos y aparecerán unas visualizaciones bonitas que acabas de crear:
Usa los botones "<" y ">" para navegar entre las imágenes.
![](../images/media/calculatingenso4_es.png)  
Salida del Notebook Ejemplo 1. [Captura de pantalla] (2023). Calculating ENSO with Xarray [https://foundations.projectpythia.org/core/xarray/enso-xarray.html](https://foundations.projectpythia.org/core/xarray/enso-xarray.html) (enlace externo)  
![](../images/media/image44.jpeg)  
Salida del Notebook Ejemplo 2. [Captura de pantalla] (2023). Calculating ENSO with Xarray [https://foundations.projectpythia.org/core/xarray/enso-xarray.html](https://foundations.projectpythia.org/core/xarray/enso-xarray.html) (enlace externo)
7. Tómate algo de tiempo para explorar un poco más de cerca el Cuaderno Computacional. Verás que hay texto (incluyendo encabezados, enlaces ¡e incluso una tabla justo al principio!), código y figuras integradas de manera conjunta. Este es sólo un ejemplo de cómo quienes hacen ciencia utilizan Cuadernos Computacionales para su investigación.

Puedes explorar más recursos de aprendizaje sobre Python de Project Pythia en su [Libro de Fundamentos](https://foundations.projectpythia.org/landing-page.html) (enlace externo). Para ejemplos más avanzados de flujos de trabajo de investigación en geociencias que usan cuadernos computacionales, revisa estos "[Cookbooks (Guías Rapidas)](https://cookbooks.projectpythia.org/)" (enlace externo) para ver cómo se usan cuadernos en ciencia. Si te interesan las geociencias, ¡puedes contribuir con tu propio Jupyter Notebook si lo tienes y quieres compartirlo!

### Plataformas de cómputo

Usamos el término "plataforma de cómputo" para referirnos a la máquina computacional usada para ejecutar código. Hay muchas plataformas de cómputo diferentes que puedes elegir y cada una tiene sus ventajas y desventajas. A continuación se ofrece una descripción general de tres opciones de plataformas:

#### Computadora personal (por ejemplo, una computadora portátil)

Ventajas:
- Es conveniente: puedes ejecutar cálculos cuando y donde tú elijas.
- Puedes adaptar el entorno de software para que sea exactamente lo que necesitas.
- No tienes que compartir tus recursos informáticos.

Desventajas:
- Tiene potencia computacional limitada.
- Requiere descargar datos y software.

#### Computación de Alto Desempeño (HPC, por sus siglas en inglés)

Ventajas:
- Alto poder computacional

Desventajas:
- Por lo general, es propiedad de una institución en particular y está administrada por ella; es posible que debas contar con una afiliación a dicha institución para acceder a su HPC.
- Es posible que tengas que esperar mucho tiempo para ejecutar el código, ya que normalmente se comparte entre muchas personas y grupos.
- Se necesitan fondos considerables para construir una HPC.

#### Computación en la nube (Cloud Computing)

Ventajas:
- Potencia computacional extremadamente alta.
- Tiempos de espera mínimos para ejecutar el código.
- Normalmente accesible para cualquier persona con conexión a Internet.
- Opciones de precios bajo demanda: solo tienes que pagar por lo que usas.

Desventajas:
- Alto costo por cálculo.
- Falta de transparencia en los costos. Por ejemplo leer datos de diferentes regiones de la nube puede costar mucho dinero, pero no siempre está claro en qué región se encuentran los datos y dónde se realizan los cálculos.
- Puede requerir algún conocimiento adicional sobre cómo funciona el cómputo en la nube.

 Ejemplos de proveedores de nube:
 - Amazon Web Services (AWS)
 - Google Cloud
 - Microsoft Azure

Muchos proveedores de datos, especialmente de conjuntos de datos grandes, están migrando sus datos a la nube para aumentar la accesibilidad y aprovechar la gran capacidad de almacenamiento que ofrece la nube. Por ejemplo, NASA Earthdata (que aloja todos los datos de ciencias de la Tierra de la NASA) ahora usa AWS para almacenar la mayoría de sus datos. Muchos proveedores de nube también tienen una serie de conjuntos de datos públicos disponibles, incluyendo [Google Cloud](https://cloud.google.com/storage/docs/public-datasets/#:~:text=Available%20public%20datasets%20on%20Cloud%20Storage%201%20ERA5%3A,from%202015%20through%20the%20present.%20...%20More%20items) (enlace externo) y [AWS](https://registry.opendata.aws/) (enlace externo).

Al elegir una plataforma de cómputo, es importante considerar dónde se almacenan los conjuntos de datos y qué tan grandes pueden ser. Por ejemplo, cuando se trabaja con conjuntos de datos pequeños, suele ser preferible utilizar una computadora personal, ya que la descarga de datos llevará un tiempo mínimo y probablemente no se necesiten grandes recursos informáticos. Sin embargo, cuando se trabaja con grandes conjuntos de datos, es mejor minimizar la cantidad de descarga y carga de datos, ya que esto puede consumir cantidades significativas de tiempo y ancho de banda de internet. Si tus grandes conjuntos de datos ya están almacenados en la nube, es mejor utilizar recursos de la nube, así como para el cálculo y el uso de HPC.

## Herramientas adicionales

### Repositorio de software vs archivo de software

Los repositorios y archivos de software proporcionan ubicaciones centralizadas para almacenar y compartir software. Existen algunas diferencias clave entre ellos, que analizaremos en esta sección.

Un repositorio de software es un espacio dinámico y colaborativo donde quienes desarrollan trabajan en el código más reciente, lo que lo convierte en el corazón del desarrollo continuo del software y del control de versiones. Alberga bases de código mantenidas activamente, lo que fomenta la colaboración y la mejora continua, a menudo impulsadas por la comunidad.

Por el contrario, un archivo de software es un almacenamiento estático donde se guardan versiones de software estables y minuciosamente probadas. Las personas usuarias acceden a estos archivos para obtener versiones confiables del software, lo que asegura la estabilidad y la confiabilidad de sus aplicaciones. Comprender la diferencia entre ambos es crucial para un desarrollo y distribución de software eficaces.

<img src="../images/media/image45_es.jpg" style="width:350px;height:auto;" />
Crédito de la imagen: NASA

Git/GitHub y Bitbucket son opciones populares para repositorios de software.

<table>
  <thead>
    <tr>
        <th>Repositorio &#9745;</th>
        <th>Archivo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <ul>
              <li>Es una ubicación para compartir código.</li>
              <li>A menudo usa sistemas de control de versiones como Git, Mercurial y Subversion para rastrear cambios</li>
              <li>Generalmente contiene la versión de desarrollo más reciente (a veces denominada "maestra", *master*, o "troncal", *trunk*) de un proyecto de software, sobre la cual los desarrolladores pueden trabajar activamente.</li>
              <li>Se usa para el desarrollo colaborativo de software y para compartir código entre un equipo o una comunidad de desarrollo.</li>
            </ul>
            <p><strong>Nota importante:</strong> Un repositorio no es más que un lugar para alojar código. Hoy en día, un sistema de control de versiones y un repositorio suelen ser lo mismo. Es importante entender la distinción. Sin embargo, algunos sitios web son puramente buzones (dropboxes) para archivos ejecutables o zip de código fuente.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>Repositorio</th>
        <th>Archivo &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <ul>
              <li>A menudo se usa para la distribución y preservación a largo plazo de software.</li>
              <li>Un sistema de almacenamiento que contiene lanzamientos o versiones específicas y estables de software, paquetes binarios compilados o versiones de código fuente.</li>
              <li>Los usuarios suelen descargar software desde un archivo para instalarlo y usarlo en sus sistemas.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

**Contenedores**

Un contenedor (container) de software es un paquete independiente y ejecutable que incluye todo lo necesario para ejecutar una pieza de software, como el código, el tiempo de ejecución, las herramientas del sistema, la configuración del entorno y las bibliotecas o librerías. Los contenedores son entornos aislados que contienen la aplicación y todo lo necesario para ejecutarla, lo que garantiza coherencia y portabilidad entre distintos entornos informáticos. Un contenedor es una herramienta útil que puede aportar eficiencia, escalabilidad y facilidad de implementación. Algunos ejemplos de herramientas de contenedores ampliamente utilizadas son Kubernetes, Docker y Apache Mesos.

### Actividad 4.2: Relaciona herramientas

Relaciona cada elemento con su descripción:

<table>
  <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
  </colgroup>
  <tbody>
    <tr>
      <td>
        Entorno de desarrollo integrado (IDE)
      </td>
      <td>
        Editor de texto mejorado para el código. Ayuda a identificar la sintaxis y las construcciones o desarrollos de código.
      </td>
    </tr>
    <tr>
      <td>
        Archivo de software
      </td>
      <td>
        Almacenamiento estático donde se guardan versiones de software estables y completamente probadas.
      </td>
    </tr>
    <tr>
      <td>
        Plataforma de control de versiones
      </td>
      <td>
        Herramienta que ayuda a quienes desarrollan software a gestionar y realizar un seguimiento de los cambios.
      </td>
    </tr>
  </tbody>
</table>

## Lección 4: Resumen

En esta lección has aprendido:

- La utilidad de herramientas digitales que gestionan, fomentan la colaboración y albergan Código Abierto.
- Cómo los sistemas de control de versiones, como Git, y plataformas como GitHub pueden aumentar la colaboración y la gestión del código.
- Algunas herramientas comunes para editar Código Abierto, incluidos entornos de desarrollo integrados (IDEs) como Visual Studio Code y Jupyter Notebooks.
- La diferencia entre repositorios y archivos de software y también cómo los contenedores de software pueden ayudar a compartir y reproducir código.

## Lección 4: Evaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

*Pregunta*

**01/03**

¿Cuál de las siguientes NO es una ventaja de utilizar plataformas de control de versiones?

- Capacidad de rastrear cambios que se hicieron
- No puedes volver atrás para hacer cambios
- Facilidad de colaboración en el código, con otras personas
- Directorio limpio y sin desorden: no hace falta tener múltiples copias de archivos
- Un sistema de respaldo muy específico para tu trabajo

*Pregunta*

**02/03**

Un entorno informático interactivo que combina ejecución de código, documentación y visualización de datos en una única interfaz se conoce como:
  
- Plataforma de control de versiones
- Repositorio de software
- Cuaderno computacional
- Contenedor (container)

*Pregunta*

**03/03**

Un repositorio de software y un archivo de software son lo mismo.

- Verdadero
- Falso

### Referencias
---
- 2022 Developer Survey. (2022, mayo). Stack Overflow. [https://survey.stackoverflow.co/2022/](https://survey.stackoverflow.co/2022/) (enlace externo)
