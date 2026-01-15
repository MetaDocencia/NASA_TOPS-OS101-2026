# Lección 3: Hacer Código Abierto

## Contenidos

- [¿Cómo planificar para crear código?](#c%C3%B3mo-planificar-para-crear-c%C3%B3digo)
- [Importancia del control de versiones](#importancia-del-control-de-versiones)
- [Describir nuestro código para otras personas](#describir-nuestro-c%C3%B3digo-para-otras-personas)
- [¿Qué licencia deberíamos elegir para nuestro código?](#qu%C3%A9-licencia-deber%C3%ADamos-elegir-para-nuestro-c%C3%B3digo)
- [Buenas prácticas de programación](#buenas-pr%C3%A1cticas-de-programaci%C3%B3n)
- [Lección 3: Resumen](#lecci%C3%B3n-3-resumen)
- [Lección 3: Evaluación](#lecci%C3%B3n-3-evaluaci%C3%B3n)

## Descripción general

En esta lección aprenderás los pasos prácticos para hacer que el código esté disponible de manera abierta. El software de gran volumen y bien establecido tiene necesidades distintas a las de un proyecto incipiente. Por ejemplo, un script escrito para crear un gráfico simple tiene requisitos diferentes a los de un paquete de software que modela el clima de la Tierra. El tamaño de un equipo de investigación también puede determinar los pasos necesarios para hacer que el código sea de acceso abierto. Esta lección cubre el proceso para hacer que el código sea utilizable por otras personas investigadoras a través de la documentación, consideraciones sobre licencias y buenas prácticas de desarrollo de software.

## Objetivos de aprendizaje

Luego de completar esta lección, deberías poder:

- Describir las consideraciones clave al planificar un nuevo proyecto de software abierto.
- Enumerar tres razones por las que los proyectos utilizan control de versiones.
- Explicar el propósito y recordar la información general que suele incluirse en un archivo README.
- Poder seleccionar una licencia para tu código y enumerar las diferencias entre licencias de software de código abierto permisivas y protectoras.
- Explicar buenas prácticas de desarrollo de software que apoyan la transparencia, la reproducibilidad y la colaboración.

## ¿Cómo planificamos la creación de código?

El código se escribe para resolver un desafío. Esto puede abarcar desde producir un gráfico, procesar observaciones de la Tierra, hasta modelar el Universo. Los desafíos asociados a escribir código también pueden variar en dificultad, desde tareas más simples como el uso de hojas de cálculo, hasta actividades más complejas como la creación de bibliotecas extensas y el uso de computación en la nube de alto rendimiento. El código puede desarrollarse de manera individual, en equipo o como comunidad. Una vez escrito, el código puede utilizarse durante décadas o solo para una consulta de investigación específica.

Al iniciar un proyecto de investigación, es útil considerar las siguientes preguntas:

1. ¿Qué problema estoy intentando resolver y otras personas de mi comunidad científica también lo enfrentan?
2. ¿Existen soluciones ya disponibles? (En la Lección 2 exploramos cómo buscar soluciones existentes).
3. ¿Encontraste código que se acercaba a lo que necesitabas pero no cumplía completamente con tus requisitos?
4. Podrías contribuir a código existente en lugar de escribir algo nuevo.

Sin embargo, incluso si ya existe una solución, puede haber buenas razones para desarrollar tu propio código. Algunos casos incluyen:

- El código está escrito en un lenguaje de programación con el que no tienes experiencia.
- La licencia no es lo suficientemente abierta como para adoptarlo.
- Quieres probar nuevas técnicas o desarrollar una comprensión más profunda del problema.

<img src="../images/media/image333_es.jpg" style="width:350px;height:auto;" />

Puede llevar más tiempo iniciar un proyecto nuevo o integrar el código de otra persona que escribir el tuyo propio. Esa decisión deberá tomarse en cada caso.

Para los fines de esta lección, supongamos que estamos trabajando en un proyecto de investigación y que ya buscamos código existente. Aunque encontramos algunas opciones disponibles, decidimos que nuestras necesidades son lo suficientemente específicas como para que ninguna de ellas respalde nuestro trabajo. Será necesario iniciar un proyecto nuevo.

### Iniciar un nuevo proyecto

Al comenzar un nuevo proyecto, considera estos elementos clave:

- Definir el alcance del proyecto, sus funcionalidades principales y cualquier limitación, así como la audiencia prevista.
- Considerar los recursos necesarios para que el código o software funcione. ¿Se ejecutará en una computadora personal, en un servidor de computación de alto rendimiento o en la nube?
- ¿Cómo será gestionado?

Esta lección se centra principalmente en la cuestión de cómo gestionar código de acceso abierto.

¿Quiénes trabajarán en el proyecto? ¿Cuáles son algunas de las buenas prácticas de desarrollo? ¿Cómo compartirás el proyecto de manera abierta? ¿Cómo se licenciará?

### Organización de un proyecto

<img src="../images/media/image353_es.png" style="width:250px;height:auto;" />
Crédito de la imagen: Foto de XKCD con licencia Creative Commons Attribution-NonCommercial 2.5

---

Los proyectos de software pueden organizarse de diversas maneras, cada una con consideraciones particulares sobre cómo comenzar. Muchos proyectos empiezan como un único script pensado solo para un uso puntual. Sin embargo, un script puede crecer y convertirse en un proyecto mucho más grande, con aplicaciones imprevistas en su campo original o en uno nuevo. Otros proyectos pueden comenzar con requisitos y estándares formales.

**Hacer público el código tiene muchas ventajas:**

- Permite la colaboración abierta.
- Invita a recibir retroalimentación constructiva que contribuye a la precisión y robustez del código.
- Personas con menor experiencia en programación pueden aprender de quienes tienen más experiencia mientras mejoran el código.
- Proporciona un producto intermedio que aún puede ser citado.

Al nombrar un proyecto, realiza una búsqueda rápida del nombre propuesto para ver qué aparece. Evita nombres con muchos otros usos, ya que dificultan que otras personas encuentren el código. Además, no elijas nombres vergonzosos, poco profesionales o protegidos por marcas registradas.

Alojar el producto en una plataforma con control de versiones garantiza la permanencia del proyecto. Si el código solo existe en tu computadora, puede perderse si esta se daña o se extravía.

Documentar la producción y gestión del código beneficia tanto a quien lo crea como a quienes puedan usarlo en el futuro. Eres tu mejor colaborador. La documentación puede ahorrarte problemas futuros si reutilizas el código dentro de seis meses o intentas recordar detalles minuciosos de tu proceso más adelante.

**Preguntas a considerar al elegir un lenguaje de programación:**

- ¿Potenciales colaboradores podrán contribuir en el lenguaje elegido?
- ¿Con qué lenguajes tienes mayor experiencia?
- ¿Existen limitaciones de tu entorno computacional que dificulten escribir o gestionar este código?
- Los lenguajes tienen fortalezas y debilidades, ¿cuáles son más importantes para tu proyecto?

**Antes de que otra persona pueda usar tu código, es probable que surjan algunas preguntas:**

- ¿Dónde puedo encontrar tu código?
- ¿Está documentado?
- ¿De qué formas puedo usarlo?
- ¿Aceptarás cambios en el código? Si encuentro un error, ¿qué debo hacer?
- ¿Cómo confío en que el código funciona?
- ¿Cómo sé si el código tendrá soporte a largo plazo?

## Importancia del control de versiones

Tu código cambiará significativamente a lo largo de la vida del proyecto. Así como valoramos poder rastrear versiones anteriores de documentos o versiones creadas por distintas personas, en algún momento será necesario revertir, comparar y sintetizar cambios en el código.

La herramienta más popular para control de versiones es Git, un sistema que rastrea cambios en archivos informáticos. Es similar a Google Docs o SharePoint, pero más adecuado para scripts de código. Git suele utilizarse junto con plataformas de control de versiones como GitHub, GitLab o Bitbucket, que se trataron en el Módulo 2 (Herramientas generales para Ciencia Abierta).

El control de versiones permite:

- Ayudar a las personas desarrolladoras a seguir los cambios en el código de un proyecto (así como archivos complementarios y documentación) a lo largo de toda su evolución.
- Rastrear revisiones de archivos del proyecto, incluidas contribuciones de distintas personas.
- Revertir cambios no deseados (como errores o fallas) en cualquier momento.

El control de versiones es una buena práctica incluso si no planeas compartir el código de inmediato. Puedes usarlo de forma privada en tu computadora o utilizar el modo privado de servicios de alojamiento. Configurarlo desde el inicio prepara tu código para usos futuros previstos e imprevistos.

**Recursos adicionales sobre control de versiones**

- Software Carpentry: Control de versiones con Git (enlace externo).
- The Turing Way: Control de versiones (enlace externo).
- Uso de repositorios públicos con control de versiones: recomendaciones para software FAIR (enlace externo).

## Describir nuestro código a otras personas

### README

El primer punto de contacto de una persona usuaria con un proyecto nuevo suele ser el archivo README. Este archivo contiene información de orientación que ayuda a comprender el propósito del proyecto, ofrece ejemplos de uso y enumera otra información relevante que la persona creadora considera pertinente.

Como mínimo, un README debe contener el nombre del proyecto y un párrafo muy breve que describa qué es el código. Idealmente debe limitarse a dos o tres oraciones en lenguaje claro, sin asumir conocimientos previos. Es, en definitiva, la presentación breve del proyecto.

|  |  |
|---|---|
| **Ejemplo de README deficiente** | “Este código recalcula el factor de permutación fundamental del flujo descendente (para J < 10, obviamente)”. |
| **Ejemplo de README adecuado** | “LeapKitten. Este paquete de software en Python toma cualquier imagen de un gatito (JPEG, PNG) y utiliza inteligencia artificial para mostrar cómo se vería saltando en el aire. Además, el código tiene en cuenta los años bisiestos en la marca temporal de la imagen”. |

Además, es útil incluir la siguiente información en el README, especialmente si no se encuentra en otro lugar:

- Lista de dependencias del software.
- Cómo instalarlo y una breve descripción de cómo ejecutarlo.
- Descripción detallada del software si no existe documentación externa.
- Ejemplos de uso.
- Reconocimiento a integrantes del equipo o fuentes de apoyo.

### Guías para personas colaboradoras

El archivo CONTRIBUTING brinda información sobre cómo contribuir al proyecto. Describe cómo funciona el proceso de contribución y qué tipo de aportes se necesitan. Aunque no todos los proyectos cuentan con este archivo, su existencia indica claramente que las contribuciones son bienvenidas.

### Código de conducta

El código de conducta establece reglas básicas de comportamiento y ayuda a facilitar un entorno amigable y acogedor. Aunque no todos los proyectos incluyen un archivo CODE_OF_CONDUCT, su presencia indica que se trata de un proyecto abierto a la colaboración.

### Documentación del código

La documentación a nivel de código debe incluir comentarios claros sobre la función de cada parte, pensados tanto para otras personas desarrolladoras como para quien lo escribió en el futuro.

### Programar y documentar

**Establecer un entorno de desarrollo** facilita escribir código limpio y mantener el proyecto en el tiempo.

**Estructurar archivos y carpetas** de forma organizada desde el inicio contribuye al éxito del proyecto.

## ¿Qué licencia deberíamos elegir para nuestro código?

Las licencias de software de código abierto determinan cómo se usa, modifica y comparte el código. Comprender sus diferencias es fundamental para decidir cómo licenciar y compartir un proyecto.

Existen licencias permisivas y licencias protectoras (copyleft), que difieren principalmente en cómo regulan el uso y la redistribución de trabajos derivados.

## Buenas prácticas de programación

Las buenas prácticas relacionadas con revisión de código, pruebas, seguridad y disponibilidad mejoran la calidad del código, la reproducibilidad de los resultados y la seguridad del proyecto.

### Revisión de código

El código se beneficia de la revisión por pares del mismo modo que la ciencia. Tener a otra persona revisando y probando el código es una de las mejores formas de mejorar su calidad.

### Pruebas

Las pruebas permiten evaluar si el código produce los resultados esperados y si es reproducible bajo distintas condiciones.

### Minimizar riesgos de seguridad

Considerar riesgos de seguridad es clave tanto en software abierto como cerrado.

### Crear software FAIR

El software FAIR es encontrable, accesible, interoperable y reutilizable.

## Lección 3: Resumen

En esta lección aprendiste que:

- Planificar un proyecto requiere definir un propósito claro, reconocer limitaciones de recursos y pensar en un plan de gestión.
- El control de versiones facilita el seguimiento de cambios y la colaboración.
- Un archivo README debe describir claramente el proyecto.
- Las licencias determinan cómo se puede reutilizar el software.
- Las pruebas, la documentación y la seguridad son buenas prácticas fundamentales.

## Lección 3: Autoevaluación

Responde las siguientes preguntas para evaluar lo aprendido.

### Referencias citadas

- Copyright in General. (s. f.). U.S. Copyright Office FAQ. https://www.copyright.gov/help/faq/faq-general.html (enlace externo)
