# Lección 4: Compartir Datos Abiertos

## Contenidos

- [Cuándo compartir los datos y consideraciones sobre si se debe hacerlo](#cu%C3%A1ndo-compartir-los-datos-y-consideraciones-sobre-si-se-debe-hacerlo)
- [Dónde compartir datos](#d%C3%B3nde-compartir-datos)
- [Cómo habilitar el reuso de datos](#c%C3%B3mo-habilitar-el-reuso-de-datos)
- [Quién es responsable de compartir datos](#qui%C3%A9n-es-responsable-de-compartir-datos)
- [Lección 4: Resumen](#lecci%C3%B3n-4-resumen)
- [Lección 4: Evaluación](#lecci%C3%B3n-4-evaluaci%C3%B3n)


## Descripción general

En esta lección aprenderás las buenas prácticas para compartir tus datos con una audiencia más amplia. La discusión comienza con una revisión del proceso para compartir y evaluar si tus datos pueden compartirse. Luego aprenderás cómo asegurar que tus datos estén disponibles públicamente mediante una lección sobre repositorios y el ciclo de vida de la accesibilidad de los datos. Desde la selección de un repositorio hasta el archivado de tus datos, estas prácticas aseguran que tus datos se mantengan y sean buscables. Finalmente, recorrerás los pasos para hacer que tus datos sean lo más reutilizables posible y concluyes con una sección sobre a quién considerar para ayudar en el proceso de compartirlos.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Reconocer las variables institucionales, las cuestiones de seguridad y el tiempo que puedan afectar tu decisión de compartir datos.
- Recordar las características, responsabilidades inherentes, consideraciones de financiamiento y requisitos de los patrocinadores que las personas que investigan deberían tener en cuenta al seleccionar un repositorio para compartir datos.
- Describir las herramientas y enumerar algunas buenas prácticas que optimizan la práctica de compartir datos.

## Descripción general del proceso de compartir datos

Compartir datos es una parte crítica para mejorar la reproducibilidad de los resultados. Tanto si se trata de datos nuevos que recolectamos por nuestra parte como de datos que procesamos para realizar nuestro análisis, terminamos compartiendo algún tipo de dato. Tenemos que pensar qué datos vamos a compartir y cuál es la mejor manera de asegurar que sean de forma abierta y sean usables por otras personas.

Generalmente, el intercambio de datos debe hacerse a través de un centro de datos estable o de un repositorio que será responsable de ingestar, curar y distribuir o publicar tus Datos Abiertos. Tú eres responsable de proporcionar información y metadatos para facilitar que tus datos sean fáciles de encontrar, acceder y citar. También debes considerar el costo de archivar y publicar los datos.

### La conclusión es que quieres compartir tus datos

Una vez que hayas decidido compartir tus datos, hay una serie de preguntas que tendrás que responder para ayudarte a planificar y que deben incluirse en tu Plan de Gestión de Datos (PGD):

|  |  |
|---|---|
| ¿Qué? | Formato y (si es relevante) estándares de datos |
| ¿Cuándo? | Cuándo compartir datos y si hacerlo |
| ¿Dónde? | Los repositorios destinados a datos archivados |
| ¿Cómo? | Cómo permite el plan el reuso de los datos |
| ¿Quién? | Roles y responsabilidades de las personas que forman parte del equipo en la implementación del PGD |

En esta lección, explicaremos algunos pasos hacia la obtención de datos. Específicamente, nos enfocaremos en las secciones "cuándo", "dónde", "cómo" y "quién" de un PGD.

### Proceso de compartición de datos abiertos

En general, compartir tus Datos Abiertos requiere de los siguientes pasos:

1. Asegúrate de que tus datos puedan ser compartidos
2. Selecciona o identifica un repositorio para alojar tus datos
3. Trabaja junto con tu repositorio para seguir su proceso y cumplir con sus requerimientos
4. Asegúrate de que tus datos sean fáciles de encontrar y accesibles a través del repositorio y que sean mantenidos y archivados
5. Solicita un DOI para tu conjunto de datos para que pueda ser citado fácilmente
6. Elije una licencia de datos

A veces, puede que trabajes con un repositorio bien preparado que gestione muchos de estos pasos (por ejemplo, si trabajas con los datos de la misión de la NASA). De lo contrario, es tu responsabilidad seguir los pasos anteriores para compartir tus datos de forma abierta.

## Cuándo compartir los datos y consideraciones sobre si se debe hacerlo

### ¿Cuándo compartir datos?

La decisión sobre cuándo compartir datos debería discutirse con todas las personas del equipo y documentarse en el Plan de Gestión de Datos. Las agencias de financiamiento y organizaciones pueden tener requerimientos específicos sobre cuándo deben compartirse los datos, pero aquí te animamos a pensar si es posible compartir tus datos antes de que te lo exija tu patrocinador. Hay distintos momentos en que los datos pueden ser compartidos:

- **Compartir de forma anticipada:** Compartir al momento de la recolección o poco después. Algunas agencias de financiamiento requieren que así sea o permiten un pequeño período de "embargo", pero normalmente se requiere una razón (control de calidad, calibración, etc). Esto maximiza el reuso de los datos y el impacto, y puede resultar en un aumento de las colaboraciones.
- **Compartir de forma intermedia:** Al momento de la publicación. Muchas revistas (y algunas agencias de financiamiento) requieren compartir los datos necesarios para replicar los resultados al momento de la publicación.
- **Compartir de forma mínima** Fin del subsidio. Todos los datos científicamente relevantes deben compartirse al final del subsidio de investigación.
- **No compartir:** Hay muchos motivos por los que los datos pueden ser restringidos o no compartidos en absoluto.
  
Como ya comentamos anteriormente en este curso, hay muchos beneficios de compartir los datos lo antes posible. Compartir temprano puede llevar a nuevos e inesperados descubrimientos y a la expansión de tu red de colaboraciones. Recuerda que, aun cuando compartes tus datos, tú sigues siendo la persona experta a nivel mundial en ellos. Es muy probable que, cuando las personas quieran trabajar con tus datos, se pongan en contacto contigo para colaborar.

### ¿Se deben compartir los datos?

Antes de compartir los conjuntos de datos, es importante que tengas en cuenta cualquier restricción de permisos de compartido y que te asegures de que quienes contribuyen contigo, incluidos los donantes de muestras y datos, aprueben su publicación.

Los datos deben ser tan abiertos como sea posible y tan cerrados como sea necesario. Abrir los datos es una forma poderosa de fomentar el descubrimiento, la transparencia y el progreso científico. Sin embargo, es importante considerar algunos puntos antes de compartirlos:

- Algunos datos están sujetos a leyes y regulaciones que limitan su divulgación.
- Tu institución local puede tener políticas y recursos adicionales; investígalos lo antes posible y regularmente

Algunas consideraciones específicas que pueden impedir que compartas tus datos son:

- Secretos militares de un país o violaciones de los intereses nacionales
- Información médica privada o datos personales de un individuo
- Consideraciones culturales o de conservación.
- Propiedad intelectual, patentes
- Otras: por favor, piensa en lo que estás compartiendo y en cuáles son las implicancias de hacerlo (por ejemplo, ¿tienes el permiso de todas las personas involucradas?)

En el primer módulo de este curso, enumeramos varias razones por las que ciertos productos de investigación no deben ser compartidos. Repasaremos algunas de estas razones y profundizaremos en aquellas que resultan especialmente relevantes para los datos.

### Consideraciones de exportación y seguridad

Leyes y regulaciones relevantes que pueden evitar la publicación de datos incluyen, entre otras:

- [Regulación Internacional de Tráfico de Armas (International Traffic in Arms Regulation)](https://www.pmddtc.state.gov/?id=ddtc_public_portal_itar_landing) (ITAR, por su nombre en inglés), que regula la fabricación, venta, distribución y exportación de artículos y servicios relacionados con la defensa en Estados Unidos.
- [Regulaciones de Administración de Exportación (Export Administration Regulations)](https://www.bis.gov/regulations) (EAR por su nombre en inglés), que regulan la manufactura, venta, distribución y exportación de artículos comerciales y de doble uso, tecnología e información no cubiertos por ITAR.

**Ejemplo: Estándar de Protección del Sistema Espacial de la NASA**

NASA STD 1006.1 [Estándar de Protección del Sistema Espacial (Space System Protection Standard)](https://standards.nasa.gov/standard/NASA/NASA-STD-1006) el cual establece los requisitos de protección para asegurar que las misiones de la NASA sean resistentes a amenazas intencionales.

### Consideraciones sobre información controlada

Leyes y regulaciones relevantes que pueden evitar la publicación de datos incluyen, pero no están limitadas a:

- [Ley de portabilidad y responsabilidad del seguro médico (Health Insurance Portability and Accountability Act)](https://www.hhs.gov/hipaa/for-professionals/index.html) (HIPAA por su nombre en inglés), que establece estándares para proteger la información sensible de los pacientes de la divulgación.
- [Información no clasificada controlada (Controlled Unclassified Information)](https://www.archives.gov/cui) (enlace externo) proporciona estándares para manejar información no clasificada que requiere salvaguardas o controles de divulgación acordes con las leyes, las regulaciones federales y las políticas.
- Leyes y reglamentos federales que rigen la información clasificada o los requisitos de seguridad.

### Consideraciones de propiedad intelectual

Los datos pueden estar sujetos a derechos de propiedad intelectual, derechos de autor y licencias. Algunas de las regulaciones y políticas relevantes incluyen leyes de propiedad intelectual y patentes, como la Ley [Bayh-Dole Act](https://www.govinfo.gov/content/pkg/USCODE-2011-title35/html/USCODE-2011-title35-partII-chap18.htm) (enlace externo), que permite a las universidades, instituciones de investigación sin fines de lucro y pequeñas empresas poseer, patentar y comercializar invenciones desarrolladas bajo programas de investigación con fondos federales.


**Ejemplo: Suplemento FAR de la NASA 1852.227**

El [Suplemento FAR 1852.227 (NASA FAR Supplement 1852.227)](https://prod.nais.nasa.gov/far/far0595-nfs012617/5227.htm) describe los derechos de patentes y los datos para contratos gubernamentales.

---

Muchas instituciones de investigación tienen personas residentes expertas en propiedad intelectual, derechos de autoría y derecho de patentes. Pueden ser un gran recurso si tienes alguna pregunta o preocupación.

## Dónde compartir datos

Los datos pueden compartirse en una enorme variedad de lugares. Si bien es común compartir datos a través de correos electrónicos o sitios web, estos no son medios recomendados, ya que no cumplen con los requisitos de que sean fáciles de encontrar o de ser archivados a largo plazo. Compartir datos como parte del material complementario de una publicación revisada por pares, especialmente para conjuntos de datos pequeños, es aceptable en algunos campos. Un repositorio a largo plazo que proporcione un identificador permanente es la mejor opción para compartir datos.

### Seleccionar un repositorio de datos

Si aún no tienes un repositorio de datos en mente, ten en cuenta lo siguiente para acotar tus opciones:

- ¿Quien te financia requiere un repositorio de datos específico?
- ¿Quien te financia requiere un repositorio de datos específico?
- ¿Tu organización o institución recomienda un repositorio de datos específico?
- ¿Existe un repositorio de dominio específico ampliamente usado en tu área de investigación?
- ¿El repositorio provee Acceso Abierto a los datos?
- ¿Crees que las herramientas que ofrece el repositorio para el descubrimiento y la distribución de datos son apropiadas para tus datos y los principios FAIR?
- ¿El repositorio requiere financiamiento de tu proyecto, se ajusta a tu presupuesto y requiere soporte constante más allá del ciclo de vida del proyecto?

Encuentra y compara los servicios, beneficios y limitaciones de los repositorios que estás considerando. Cada repositorio tendrá sus propios procesos y requerimientos para aceptar y albergar tus datos, de acuerdo con el nivel de financiamiento, el propósito y la base de personas usuarias.

Los datos con preocupaciones de privacidad pueden requerir procesos adicionales de anonimización, aprobación o restricciones de acceso.

La Casa Blanca presenta una buena descripción general de las [características deseables](https://doi.org/10.5479/10088/113528) (enlace externo, en inglés).

### Asegurar la accesibilidad

Los buenos repositorios compartirán (u ofrecerán) los Datos Abiertos mediante protocolos estándar, como HTTPS o SFTP. Las formas más habituales de hacerlo son:

- Permitir a las personas usuarias ver una lista de archivos y descargarlos mediante una interfaz intuitiva.
- Crear una Interfaz de Programación de Aplicaciones (en inglés, Application Programming Interface, API) documentada para que quienes usan la herramienta generen una lista de enlaces de archivos que cumplan con los criterios de búsqueda y que se puedan descargar de forma automatizada (es decir, acceso a datos de máquina a máquina).

Adicionalmente, los repositorios pueden requerir autorización y autenticación (por ejemplo, iniciar sesión con nombre de usuario y contraseña) para acceder a los datos. Si bien esto está permitido según los principios FAIR (Fácil de encontrar, Accesible, Interoperable y Reusable), puede violar los principios de la Ciencia Abierta si no todas las personas pueden registrarse.

### Trabajar con un repositorio

<table>
  <thead>
    <tr>
        <th>COMENZAR A TRABAJAR CON UN REPOSITORIO &#9745;</th>
        <th>MANTENER DATOS EN EL REPOSITORIO</th>
        <th>ARCHIVAR DATOS EN EL REPOSITORIO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los requisitos del repositorio pueden variar ampliamente. Revisa siempre los requisitos del repositorio para ver qué acciones necesitas realizar una vez que consideres empezar a trabajar con ellos. También ten en cuenta que algunos repositorios cuentan con personal que ayuda con el proceso de compartir datos, mientras que otros dependen de que sepas cómo compartir tus propios datos.</p>
            <p>Si usas un repositorio que tiene personal para ayudarte con el proceso, podrían solicitar revisar y comentar tu Plan de Gestión de Datos.</p>
            <p>El repositorio puede solicitar que realices algunas pruebas de tu muestra de datos para evaluar:</p>
            <ul>
                <li>Que el formato de datos que pretendes usar sea compatible.</li>
                <li>Que las variables del conjunto de datos estén nombradas como se espera.</li>
                <li>Que el vocabulario de metadatos sea correcto.</li>
                <li>Que se cumplan los requisitos específicos del repositorio.</li>
            </ul>
            <p>Esta serie de comprobaciones permite identificar errores tempranamente y dar como resultado un envío final de tus datos al repositorio sin inconvenientes.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>COMENZAR A TRABAJAR CON UN REPOSITORIO</th>
        <th>MANTENER DATOS EN EL REPOSITORIO &#9745;</th>
        <th>ARCHIVAR DATOS EN EL REPOSITORIO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>A medida que avanzas en el ciclo de vida de tu proyecto, usa los procesos de actualización, revisión y reenvío de tu repositorio para mantener actualizados los productos de datos archivados. Cualquier nueva versión de los datos que desees compartir a través del repositorio tendrá que pasar por un proceso similar al del conjunto de datos inicial.</p>
            <p>Todas las nuevas versiones del conjunto de datos que quieras compartir a través del repositorio deben someterse al mismo proceso de revisión del PGD, verificación de cumplimiento y procedimiento de carga que el conjunto de datos inicial.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>COMENZAR A TRABAJAR CON UN REPOSITORIO</th>
        <th>MANTENER DATOS EN EL REPOSITORIO</th>
        <th>ARCHIVAR DATOS EN EL REPOSITORIO &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Cuando tu proyecto finalice, asegúrate de haber actualizado y subido cualquier documentación complementaria (discutida en la lección anterior "Hacer Datos Abiertos") con tu versión final (incluso si sólo se hizo una versión única de los datos).</p>
            <p>Asegúrate que el repositorio mantendrá tus datos (o al menos tus metadatos) en línea durante un período de tiempo razonable luego de que tu proyecto termine.</p>
            <p>Si se encuentra algún problema con los datos después de la finalización de tu proyecto, asegúrate de que el repositorio aceptará revisiones de la base de datos si son necesarias.</p>
        </td>
    </tr>
  </tbody>
</table>

## Cómo habilitar el reuso de datos

### Obtener un DOI

Por lo general, las personas no pueden solicitar un identificador de objeto digital (DOI, por sus siglas en inglés) por sí mismas, sino que deben acudir a una organización autorizada que pueda enviar la solicitud, como por ejemplo:

- El repositorio de datos
- Tu organización
- Quien realiza la edición (si el conjunto de datos es parte de una publicación)

Las personas responsables de los datos deberán facilitar información resumida para la página de inicio de DOI, si es necesario. Quienes comparten datos deben tener en cuenta las sugerencias de quienes se responsabilizan de los datos, cumplir las reglas de DOI y así crear las páginas de destino. Si es posible, debes reservar un DOI antes de generar tus datos.

### Garantizar la facilidad de búsqueda

Los repositorios se encargan de compartir, distribuir y conservar los datos. Algunos servicios adicionales que pueden ofrecer incluyen:

- La asignación de un identificador persistente (como un DOI) a tu conjunto de datos.
- La indexación y/o el registro de tus datos y metadatos en diversos servicios para que puedan buscarse y encontrarse en línea (es decir, a través de motores de búsqueda).
- La provisión de retroalimentación a quienes crearon los datos para ayudarles a optimizar sus metadatos y facilitar la búsqueda.
- La coordinación con las personas responsables de datos para garantizar que los metadatos hagan referencia al DOI.
- Asegurarse de que el DOI está asociado a un sitio o página con información sobre sus datos.

### Facilitar la cita de tus datos

El objetivo es facilitar la citación de tus datos. Las mejores prácticas incluyen:

- Incluir una referencia de cita que incluya tu DOI.
- Incorporar un archivo .CFF si el repositorio lo recomienda.
- Identificar claramente a quienes crean los datos y/o su institución.
  - Incluir el ORCiD siempre que sea posible.

Ahora que tus datos están en un repositorio y tienen una referencia de cita y un DOI, publícalo entre las personas usuarias y recuérdales que citen tus datos en sus trabajos.

## Quién es responsable de compartir datos

Compartir datos abiertamente es un esfuerzo en equipo. Una parte importante de la planificación de los Datos Abiertos consiste en definir y acordar las funciones y responsabilidades de quien garantizará la implementación del plan.

### ¿Quién se encargará de almacenar los datos en un repositorio?

Determina quién se encargará de:

- Proporcionar información sobre el volumen de datos, el número de archivos y su naturaleza (por ejemplo, archivos revisados).
- Verificar que el nombre del archivo cumpla con buenas prácticas.
- ¿Cómo se moverán los datos? (especialmente cuando los archivos son grandes)
- Verificar la integridad de los datos, los metadatos y la transferencia de la documentación.

### ¿Quién desarrollará la documentación y los metadatos?

Determina quién:

- Organizará el contenido.
- Desarrollará metadatos.
- Elaborará documentación (por ejemplo, el archivo README (LEEME)).
- Extraerá metadatos de archivos y documentación.

### ¿Quién ayudará con el reuso de los datos?

Identifica quién:

- Verificará accesibilidad y facilidad de encontrar.
- Colaborará con el repositorio para optimizar herramientas.
- Evaluará los protocolos de acceso.

### ¿Quién desarrollará una guía sobre privacidad y sensibilidad cultural de los datos?

Decide quién:

- Identificará preocupaciones de privacidad.
- Definirá procesos de aprobación.
- Desarrollará pautas de interpretación.
- Evaluará restricciones necesarias para una compartición respetuosa.

## Lección 4: Resumen

Conclusiones principales de esta lección:


- Cuándo y si compartir datos: definir el momento adecuado y reconocer que no todos los datos pueden compartirse.
- Dónde compartir datos: se recomienda usar repositorios públicos de datos.
- Cómo habilitar su reuso: usar metadatos adecuados, asignar un DOI y facilitar la citación.
- Quién ayuda a compartir datos: definir roles claros para cada etapa del proceso.

## Lección 4: Evaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

*Pregunta*

**01/04**

Los datos no se pueden compartir si son:

- Controlados por el ITAR (Regulación Internacional de Tráfico de Armas).
- Clasificados como información no clasificada controlada
- Sujetos a propiedad intelectual, derechos de autor o licencias
- Todas las anteriores

*Pregunta*

**02/04**

Selecciona la opción que consideras correcta para completar la oración.

Es una buena práctica empezar a trabajar con un repositorio _____.

- Lo más pronto posible
- Cuando se tienen datos de prueba listos
- Después de obtener un DOI
- Cuando estés listo para publicar tus datos

*Pregunta*

**03/04**

¿Cuál de las siguientes opciones puede ayudarte a obtener un DOI para tus datos?

- El repositorio con el que estás trabajando.
- Tu organización de origen.
- Una revista a la que enviaste un manuscrito y los datos.
- Todas las anteriores.

*Pregunta*

**04/04**

¿Cuáles de los siguientes son roles a considerar al compartir datos? Selecciona todas opciones que correspondan.

- Desarrollar una guía sobre la privacidad y sensibilidad cultural de los datos.
- Desarrollar la documentación de datos y los metadatos.
- Asignar un DOI a los datos.
- Verificar la integridad de los datos, metadatos y gestión de la documentación.
