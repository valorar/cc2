# Análisis y decisiones pedagógicas · Versión 3

## Decisión: seis temas

Se crean **seis temas teóricos**. Esta cantidad no se elige para imitar v1, sino para corregir dos desequilibrios de v2: su Tema 2 reúne demasiados conceptos físicos y su Tema 4 mezcla fundamentos de direccionamiento con procedimientos de configuración y diagnóstico.

La secuencia responde a seis preguntas consecutivas:

1. **¿Qué es una red y qué piezas la forman?** Fundamentos, componentes y evolución.
2. **¿Qué forma y alcance puede tener?** Tipos y topologías.
3. **¿Por dónde viajan físicamente los datos?** Señales, medios e infraestructura.
4. **¿Qué reglas organizan la conversación?** Modelos, protocolos y estándares.
5. **¿Cómo se identifica cada destino y qué servicios sostienen la red?** Direccionamiento y servicios.
6. **¿Cómo se diseña, configura y repara?** Configuración y diagnóstico.

## Qué se toma de cada versión

| Aportación | v1 | v2 | Tratamiento en v3 |
|---|:---:|:---:|---|
| Explicación breve y orientada a problemas | ✓ | | Se conserva en preguntas guía, ejemplos y resúmenes. |
| Señal analógica/digital, ruido y regeneración | ✓ | | Se incorpora al Tema 3. |
| Diagnóstico por capas | ✓ | parcial | Se refuerza en los Temas 4 y 6. |
| Cronología detallada | ✓ | ✓ | Se integra en el Tema 1, donde da contexto. |
| Componentes y electrónica de red | parcial | ✓ | Se adopta el desarrollo amplio de v2 en el Tema 1. |
| Topologías e infraestructura física | parcial | ✓ | Se divide entre los Temas 2 y 3. |
| OSI y TCP/IP, TCP/UDP y protocolos de aplicación | parcial | ✓ | Se reúne en el Tema 4. |
| MAC, IPv4/IPv6, subredes, DHCP y NAT | parcial | ✓ | Se reúne en el Tema 5. |
| Configuración y herramientas de diagnóstico | ✓ | ✓ | Se combina y ordena en el Tema 6. |

## Por qué no cuatro o cinco

- **Cuatro temas** reproducirían la estructura de v2, pero mantendrían dos unidades demasiado largas y heterogéneas.
- **Cinco temas** permitirían separar direccionamiento de configuración, pero aún dejarían tipos, topologías, señales, medios y cableado en un único tema desproporcionado.
- **Seis temas** ofrecen unidades con una idea central reconocible, una carga más equilibrada y transiciones naturales.

## Criterios editoriales

- Solo se incluye teoría: no hay prácticas, cuestionarios ni ponderaciones.
- Las páginas son autónomas, adaptables a móvil, imprimibles y navegables con teclado.
- Cada tema incluye pregunta guía, objetivos, conceptos desarrollados, ejemplos, glosario o resumen.
- Se eliminan los marcadores de imágenes todavía inexistentes de v2 para no presentar materiales incompletos.
- Se mantienen enlaces a fuentes curriculares y técnicas ya presentes en los originales.

## Bloque C — Decisión: cuatro temas

Se crean **cuatro temas teóricos**: fundamentos de imagen, edición de imágenes y gráficos vectoriales, audio y vídeo. Esta estructura conserva la separación de audio y vídeo de la versión 2 y evita que toda la representación y edición de imagen quede acumulada en una sola unidad.

La secuencia responde a cuatro preguntas consecutivas:

1. **¿Cómo se representa una imagen digital?** Píxeles, vectores, resolución, color, formatos y compresión.
2. **¿Cómo se crean y transforman recursos visuales?** Edición rasterizada con GIMP y creación vectorial con Inkscape.
3. **¿Cómo se representa y produce el sonido?** Digitalización, formatos, grabación y mezcla con Audacity.
4. **¿Cómo se integran imagen, texto y sonido en el tiempo?** Montaje y lenguaje audiovisual con Kdenlive.

### Qué se toma de cada versión

| Aportación | v1 | v2 | Tratamiento en v3 |
|---|:---:|:---:|---|
| Imagen rasterizada y vectorial, resolución, color y formatos | ✓ | ✓ | Se reúne en el Tema 10 como base común. |
| Edición rasterizada y creación vectorial | ✓ | ✓ | Se desarrolla en el Tema 11 con GIMP e Inkscape. |
| Audio y vídeo en un único tema | ✓ | | Se descarta para evitar una unidad demasiado heterogénea. |
| Audio como tema propio | | ✓ | Se adopta en el Tema 12 y se refuerzan digitalización, mezcla y exportación. |
| Vídeo y lenguaje audiovisual como tema propio | | ✓ | Se adopta en el Tema 13 como integración final de medios. |

### Por qué no tres o cinco

- **Tres temas** simplificarían la estructura por medios, pero convertirían imagen en una unidad desproporcionada que mezclaría representación digital, color, formatos, GIMP e Inkscape.
- **Cinco temas** permitirían separar GIMP e Inkscape, pero fragmentarían en exceso un mismo proceso de producción gráfica y darían a la imagen más peso del necesario.
- **Cuatro temas** equilibran la carga y establecen una progresión clara: comprender, crear recursos visuales, producir sonido e integrarlo todo en vídeo.

### Cobertura curricular

- El Tema 10 cubre tipos de imagen, resolución, tamaño, profundidad de color, digitalización, modos de color y formatos.
- El Tema 11 cubre las modificaciones rasterizadas y la creación y edición vectorial.
- El Tema 12 cubre digitalización, formatos, conversión, grabación, edición y mezcla de audio.
- El Tema 13 cubre edición de vídeo, sonido, títulos, filtros, transiciones, efectos y lenguaje audiovisual.
- Los cuatro temas incorporan creación, compresión y exportación y, en conjunto, cubren los criterios 3.1 y 3.2.

## Bloque D — Decisión: cinco temas obligatorios y uno voluntario

Se crean **cinco temas obligatorios**, del 14 al 18, y un **Tema 19 voluntario** para desarrollar un proyecto personal. La estructura evita repetir como unidades completas la sintaxis, las estructuras de control y las funciones ya estudiadas en Ciencias de la Computación I, pero reserva una reactivación práctica al comienzo.

La secuencia responde a seis preguntas:

1. **¿Cómo retomamos Python y estructuramos una solución?** Código ejecutable, funciones y casos de prueba en Google Colab.
2. **¿Cómo organizamos y conservamos datos?** Colecciones, procesamiento y ficheros.
3. **¿Cómo modelamos entidades con estado y comportamiento?** Clases y objetos.
4. **¿Cómo encontramos fallos y demostramos que una corrección funciona?** Depuración, excepciones y pruebas.
5. **¿Cómo cambia la programación en otros entornos?** Google Colab y Thonny, panorama de aplicaciones móviles y una introducción breve al software adaptativo, la inteligencia artificial, el aprendizaje automático y los agentes.
6. **¿Cómo integramos o ampliamos lo aprendido?** Proyecto personal voluntario.

### Qué se toma de cada versión

| Aportación | v1 | v2 | Tratamiento en v3 |
|---|:---:|:---:|---|
| Reactivación de Python y funciones | ✓ | desarrollada en tres temas | Se concentra en el Tema 14 sin repetir CC I. |
| Colecciones y ficheros | unidos | separados | Se reúnen en el Tema 15 como ciclo de tratamiento y persistencia de datos. |
| Clases y objetos | ✓ | ✓ | Se conserva como Tema 16 propio y de alcance introductorio. |
| Depuración, pruebas y mejora | ✓ | ✓ | Se sistematiza en el Tema 17 y se practica desde el inicio. |
| Entornos móviles y software adaptativo | mención | ✓ | Se conocen y comparan en el Tema 18, sin exigir una aplicación móvil completa; el software adaptativo se trata de forma breve y se relaciona con IA, aprendizaje automático y agentes. |
| Proyecto final | obligatorio | obligatorio | Se transforma en el Tema 19, ampliación voluntaria. |

### Por qué cinco temas obligatorios

- **Cuatro temas** obligarían a mezclar contenidos nuevos y distintos, o a dejar entornos móviles y software adaptativo como menciones marginales.
- **Cinco temas** permiten una progresión práctica y cubren todo el currículo sin depender del proyecto personal.
- **Seis o más temas obligatorios** reproducirían la fragmentación de la versión 2 y dedicarían demasiado espacio a contenidos básicos ya estudiados en CC I.

### Decisiones metodológicas

- Python se utiliza desde la primera sesión y Google Colab es el entorno principal.
- Thonny se utiliza brevemente como segundo entorno Python para comparar el trabajo con cuadernos y programas y practicar la depuración paso a paso.
- No se incluye pseudocódigo. El profesor explica oralmente los algoritmos y la planificación se concreta con ejemplos, entradas, salidas, casos de prueba, funciones y código incremental.
- Colecciones y ficheros se estudian juntos, pero en secciones diferenciadas.
- Depuración y pruebas aparecen desde el Tema 14 y se formalizan en el Tema 17.
- El Tema 18 presenta y compara entornos para aplicaciones móviles, pero no exige desarrollar una aplicación móvil ni aprender otro lenguaje.
- Los fundamentos del software adaptativo se reducen a una introducción y se conectan con conceptos actuales de inteligencia artificial, *machine learning* y agentes.
- El Tema 19 solo amplía o integra aprendizajes ya cubiertos; no es necesario para completar el bloque.

### Cobertura curricular

- El Tema 14 cubre el uso de Google Colab, la elaboración de programas sencillos y su planificación y estructuración.
- El Tema 15 cubre estructuras de almacenamiento y lectura y escritura de datos.
- El Tema 16 cubre clases, objetos y organización modular.
- El Tema 17 cubre elaboración, depuración, pruebas y mejora de programas.
- El Tema 18 cubre el uso breve de Thonny como segundo entorno, el conocimiento y valoración de entornos para aplicaciones móviles y los fundamentos del software adaptativo.
- Los temas obligatorios 14 a 18 cubren los criterios 4.1, 4.2 y 4.3; el proyecto voluntario no es la única evidencia de ningún contenido ni criterio.
