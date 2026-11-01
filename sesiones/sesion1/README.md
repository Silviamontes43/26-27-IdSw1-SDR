# Resumen de las tres opciones de proyecto planteadas por la universidad

## Introducción y contexto

Durante la reunión se presentan tres posibles líneas de trabajo para un
proyecto de desarrollo vinculado a necesidades reales de la universidad.
Las propuestas parten de tres ámbitos distintos de gestión de
información: la relación con antiguos alumnos (*alumni*), la generación
de certificados de actividad docente y el registro de actividades
extracurriculares del alumnado.

La intención no es que el equipo entregue necesariamente una herramienta
terminada ni que la universidad se comprometa a implantar el resultado.
El objetivo principal es que el alumnado trabaje sobre un caso práctico
y relativamente realista, similar a un encargo profesional de un
cliente. Por ello, se insiste en que el equipo debe escoger una opción
que pueda abordar con el tiempo y los recursos disponibles, y tener
presentes los requisitos que establezca Manuel, que será quien valore el
trabajo.

## Opción 1. Plataforma de relación y comunidad para antiguos alumnos (*alumni*)

### Qué es el proyecto *alumni*

La primera propuesta consiste en desarrollar una parte de una posible
plataforma *alumni*. El término se refiere a los antiguos alumnos de la
universidad y, en este contexto, a la red que permitiría mantener el
contacto entre esas personas y la institución una vez que hayan
terminado sus estudios.

La universidad ya cuenta con una asociación de antiguos alumnos a la que
los estudiantes podrían incorporarse al finalizar su titulación. La
plataforma planteada serviría para reforzar esa relación y ofrecer a los
egresados un espacio donde mantenerse vinculados con la universidad,
recibir información y acceder a oportunidades, como ofertas de empleo,
formación y otros servicios.

En un proyecto anterior se había estudiado esta idea de forma preliminar
y principalmente teórica. Aquel trabajo abordó cuestiones como la
definición de quién debe considerarse *alumni*, el momento en que una
persona pasa a formar parte de ese colectivo y la conexión entre los
datos del sistema de gestión de titulados de la universidad y una nueva
plataforma. También se trató la posible comunicación entre ambos
sistemas mediante una API, para trasladar los datos existentes y dar de
alta a los egresados en la futura herramienta. La propuesta actual no
exige recuperar aquel trabajo, que podría pertenecer a otro grupo o
promoción.

### Necesidad que se pretende cubrir

La universidad señala que cada año se gradúan aproximadamente entre 300
y 400 estudiantes presenciales de grado. Considera que este colectivo
constituye una red de personas con la que interesa mantener una relación
a largo plazo. Entre los posibles vínculos futuros se encuentran las
prácticas en empresas, la captación de estudiantes para másteres, las
relaciones profesionales y la difusión de la imagen de la universidad.

Para que los antiguos alumnos quieran seguir participando, la plataforma
tendría que proporcionarles utilidad real. No bastaría con que la
universidad quisiera mantener sus datos: los propios usuarios deberían
encontrar motivos para entrar, actualizar su información e interactuar
con otras personas.

### Funcionalidades e ideas planteadas

La parte concreta que se propone explorar es la dimensión social de la
red *alumni*. Entre las ideas mencionadas durante la reunión destacan:

-   Crear perfiles de antiguos alumnos para que puedan presentarse y
    mantener actualizada su información.
-   Facilitar el contacto entre egresados de distintas promociones y
    lugares del mundo.
-   Mostrar un mapa mundial que permita localizar comunidades o antiguos
    alumnos en diferentes países.
-   Permitir la creación de grupos locales o comunidades, por ejemplo,
    un club de antiguos alumnos en Guatemala que pueda organizar
    encuentros y eventos periódicos.
-   Ofrecer información y comunicaciones de interés, como noticias,
    anuncios o información sobre becas.
-   Incorporar un perfil orientado a la búsqueda de empleo, de modo que
    las empresas vinculadas a la red universitaria puedan encontrar
    candidatos y establecer contacto con ellos.
-   Favorecer conexiones entre antiguos alumnos, empresas y la propia
    universidad.

También se menciona la posibilidad de organizar actividades
conmemorativas, como el aniversario de una de las primeras promociones
de grado. Este tipo de eventos podría servir para activar las
comunidades y reforzar el sentimiento de pertenencia.

### Valor para los usuarios y para la universidad

Para los antiguos alumnos, el valor estaría en conservar una red de
contactos, acceder a oportunidades laborales y formativas, conocer a
otros egresados y participar en comunidades o eventos.

Para la universidad, la plataforma permitiría mantener el vínculo con
quienes ya se han graduado, conocer mejor esa comunidad y facilitar
futuras relaciones con empresas, prácticas y potenciales estudiantes. La
universidad considera que la red podría generar conexiones profesionales
y contribuir a su imagen pública.

La propuesta se describe como una línea bastante abierta: el equipo
tendría que concretar qué parte de esa experiencia social y de
interacción abordaría.

## Opción 2. Herramienta configurable para generar certificados de actividad docente

### Qué es el proyecto

La segunda opción consiste en desarrollar una herramienta que permita
generar distintos tipos de certificados a partir de información que la
universidad ya gestiona sobre su actividad docente.

La universidad produce y administra continuamente datos relacionados con
su funcionamiento. Como ejemplo general, se mencionan asignaturas,
calificaciones y evaluaciones, aunque se aclara que el proyecto no se
centraría en los expedientes académicos del alumnado. El ámbito
propuesto es, en cambio, la actividad del personal docente.

### Información que podría utilizarse

La herramienta trabajaría con datos relativos a la actividad del
profesorado y de la universidad, por ejemplo:

-   Los grupos docentes en los que participa cada profesor o profesora.
-   Las horas lectivas impartidas.
-   El número de alumnos a los que da clase.
-   La información histórica de esa actividad.
-   Otros datos relacionados con docencia, investigación, publicaciones
    y acreditaciones del personal docente.

La reunión reconoce que este ámbito puede resultar menos cercano al
alumnado que la primera opción, porque se relaciona con procesos
internos de gestión académica y profesional del profesorado.

### Funcionamiento que se plantea

El punto de partida sería identificar y definir la base de datos que
contiene la información relevante. A partir de esa estructura, se
desarrollarían módulos capaces de consultar los datos necesarios y
generar diferentes certificados según el tipo de información que se
solicite.

Una característica importante sería que la herramienta no estuviese
limitada a un único modelo de certificado fijo. Se plantea que el
usuario pueda modificar las estructuras o plantillas de los certificados
para adaptarlas a nuevas necesidades. Esos cambios podrían incluir:

-   Añadir, quitar o modificar campos.
-   Cambiar los formatos.
-   Incorporar nuevos elementos.
-   Crear o adaptar modelos de certificados distintos.

Por tanto, el objetivo no sería únicamente automatizar la creación de un
documento, sino ofrecer una herramienta flexible que permita generar
diferentes certificados a partir de una fuente de datos y adaptar sus
formatos cuando cambien las necesidades.

### Finalidad y alcance

La finalidad es facilitar la consulta de información sobre la actividad
docente y convertirla en certificados adecuados para cada trámite o
necesidad. La propuesta implica trabajar tanto con la organización de
los datos como con la generación documental y la configuración de las
plantillas.

En comparación con las otras dos opciones, esta se presenta como una
alternativa más técnica y administrativa, y posiblemente menos familiar
para el equipo. La reunión no concreta un catálogo cerrado de
certificados ni define los requisitos detallados de cada uno; esos
aspectos tendrían que delimitarse si se escogiese esta línea.

## Opción 3. Registro y gestión de las actividades extracurriculares del alumnado

### Qué es el proyecto

La tercera opción se centra en registrar y gestionar la participación de
los estudiantes en la vida universitaria que tiene lugar fuera de las
asignaturas y del plan de estudios oficial.

La universidad recuerda que la experiencia universitaria no se limita a
asistir a clase. También incluye actividades culturales, deportivas,
asociativas y formativas organizadas dentro o en torno al campus.

Entre los ejemplos mencionados figuran los clubes de lectura, el aula de
teatro, los servicios deportivos, iniciativas o actividades de la
universidad y la delegación de alumnos. También se incluyen cursos,
seminarios, simposios, jornadas y otras actividades organizadas por la
institución.

### Relación con el reconocimiento de créditos

La universidad explica que la participación en determinadas actividades
extracurriculares puede acumularse para solicitar el reconocimiento de
créditos. Se menciona como referencia la posibilidad de alcanzar seis
créditos y se recomienda solicitar el reconocimiento con antelación,
incluso en cuarto curso, porque así puede resultar más sencillo reunir y
tramitar las actividades realizadas.

Según lo expuesto, el reconocimiento responde a dos motivos principales.
Por un lado, la universidad debe contemplar el reconocimiento de
actividades extracurriculares. Por otro, este sistema incentiva que los
estudiantes participen en la vida del campus y no limiten su experiencia
a la formación académica. La universidad entiende que la educación
también comprende el desarrollo personal y la interacción con la
comunidad universitaria.

### Herramienta propuesta y datos que gestionaría

El proyecto partiría de recopilar y organizar la información de las
actividades extracurriculares que ofrece o reconoce la universidad. Se
desarrollaría una herramienta en la que se pudiesen registrar
participaciones y asociarlas a una persona concreta.

Los registros estarían identificados por estudiante y, según se plantea,
el sistema podría admitir también a personas externas. De este modo, se
construiría un historial de la actividad no académica de cada
participante.

La información podría abarcar actividades muy diferentes, por lo que
sería necesario disponer de una forma organizada de registrar qué
actividad se ha realizado y quién ha participado en ella. La reunión no
especifica todavía el modelo de datos, los campos exactos ni los
procedimientos de validación de cada actividad.

### Simplificación del reconocimiento de créditos

Uno de los objetivos principales sería evitar que el estudiante tuviese
que reunir y presentar por separado certificados emitidos por cada
entidad o servicio en el que hubiese participado.

Por ejemplo, en lugar de tener que aportar un certificado del club o
actividad de debate y otro del aula de teatro, la universidad podría
consultar internamente el historial registrado en la herramienta. Así,
cuando el estudiante solicitase el reconocimiento de créditos de
formación extracurricular, la información necesaria estaría centralizada
y el procedimiento sería más sencillo.

### Historial personal o «pasaporte» de vida universitaria

Además de facilitar los trámites, el registro permitiría que cada
estudiante dispusiese de un historial de todo lo que ha hecho fuera de
su plan de estudios.

La universidad relaciona esta idea con un posible certificado de vida no
académica o «pasaporte inatlántico». Este documento o historial
recogería las distintas etapas y experiencias extracurriculares del
estudiante durante su paso por la institución.

Esta dimensión conecta parcialmente con la primera opción (*alumni*): la
información recopilada podría seguir teniendo valor una vez finalizados
los estudios, porque permitiría al antiguo alumno mostrar no solo su
formación reglada, sino también su participación en la vida
universitaria.

## Comparación de las tres opciones

Las propuestas responden a necesidades diferentes:

  | Opción                           | Ámbito principal                        | Objetivo central                                                                   | Tipo de herramienta                                   |
| -------------------------------- | --------------------------------------- | ---------------------------------------------------------------------------------- | ----------------------------------------------------- |
| 1. Alumni                        | Relación con antiguos alumnos           | Mantener una comunidad activa y facilitar contactos, oportunidades y comunicación. | Plataforma social y de comunidad.                     |
| 2. Certificados docentes         | Gestión de la actividad del profesorado | Consultar datos docentes y generar certificados adaptables.                        | Sistema de consulta de datos y generación documental. |
| 3. Actividades extracurriculares | Vida universitaria no académica         | Registrar la participación y simplificar el reconocimiento de créditos.            | Sistema de registro e historial de actividades.       |

La primera opción está más orientada a la interacción entre personas y a
la creación de una comunidad. La segunda se centra en procesos
administrativos y en la generación flexible de documentos a partir de
datos docentes. La tercera combina la gestión de información con un
servicio directo para el alumnado: centralizar sus actividades
extracurriculares y facilitar tanto el reconocimiento de créditos como
la elaboración de un historial personal.

## Orientación de la elección y condiciones del proyecto

Durante la conversación, la persona que presenta las propuestas
recomienda escoger una sola opción. Intentar abordar las tres supondría
un alcance excesivo y podría impedir que el equipo completase
adecuadamente cualquiera de ellas.

Se plantea inicialmente que las opciones que parecen resultar más
cercanas al grupo son la primera y la tercera. La segunda se percibe
como más técnica o alejada de su experiencia cotidiana. Cuando se
pregunta al grupo cuál le interesa, uno de los participantes manifiesta
una preferencia por la primera opción, porque considera que tienen más
conocimientos sobre redes sociales y que la tercera se parece en parte a
información académica que la universidad ya gestiona.

La universidad aclara que la elección corresponde al equipo y que no
espera recibir necesariamente un producto terminado ni se compromete a
utilizarlo. La finalidad de la actividad es que el alumnado practique
con un caso semejante a un encargo real de un cliente: comprender una
necesidad, delimitar el trabajo y desarrollar una solución viable.

Por ello, antes de decidir el alcance, el equipo debe tener muy
presentes el tiempo disponible y los entregables que Manuel haya
solicitado. La universidad que expone las opciones no será quien evalúe
el proyecto; la responsabilidad de responder a los requisitos y entregar
el trabajo corresponde al equipo en relación con las indicaciones de
Manuel Masías.
