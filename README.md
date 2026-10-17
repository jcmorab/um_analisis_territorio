# Análisis socioeconómico del territorio · Universidad de Manizales

Dashboard interactivo de apoyo al curso de Análisis socioeconómico del territorio de la Universidad de Manizales. Permite explorar las diferencias entre crecimiento económico, producción, empleo, dinámica poblacional y bienestar mediante preguntas que orientan la lectura de los datos en clase.

Cada sección reúne una visualización principal, filtros de comparación e indicadores clave.

## ¿Qué se puede explorar?

| Sección | Pregunta orientadora |
| --- | --- |
| [PIB nacional](index.html#pib) | ¿Cambia nuestra lectura del crecimiento si miramos desde 1980? |
| [Colombia en el mundo](index.html#mundo) | ¿Colombia creció o también redujo su distancia frente a otras economías? |
| [Cambio de referente](index.html#referente) | ¿La posición de Colombia cambia cuando elegimos otro referente? |
| [PIB departamental](index.html#departamentos) | ¿Qué departamentos crecieron más y cuáles quedaron rezagados? |
| [Empleo y producción](index.html#empleo) | ¿Las actividades que más producen son también las que más empleo generan? |
| [Población](index.html#poblacion) | ¿Estamos organizando los servicios para la población actual o para la de hace cuarenta años? |
| [Producción y pobreza](index.html#municipios) | ¿Más valor agregado por habitante se asocia con menos pobreza multidimensional? |
| [Mercado laboral](index.html#laboral) | ¿Una menor desocupación significa siempre un mejor mercado laboral? |
| [Competitividad y bienestar](index.html#competitividad) | ¿La competitividad se relaciona con mayor producción y menor pobreza? |
| [Perspectivas de pobreza](index.html#perspectivas) | ¿Las distintas medidas de pobreza cuentan la misma historia? |

Las vistas permiten comparar periodos de crecimiento, seleccionar referentes internacionales por grupos, contrastar crecimiento y tamaño económico departamental, consultar valores absolutos de empleo y producción, comparar pirámides de hasta tres territorios y explorar brechas laborales por sexo o área.

En competitividad, selecciona IDC, ICC o Índice de Ciudades Modernas, el indicador de bienestar y un territorio para destacar. En perspectivas de pobreza, compara dos territorios con las seis medidas visibles: cinco filas de barras porcentuales y un apartado separado para el Gini, en escala de 0 a 1. La selección inicial es Bogotá y Sucre. Los colores identifican los territorios; los valores se leen directamente y la interpretación cambia con la selección. La matriz de correlaciones de los 24 territorios queda como apoyo desplegable.

## Cómo usarlo

Abre `index.html` en un navegador o accede a la versión publicada. Elige una sección en el menú y ajusta sus filtros. Al pasar el cursor sobre las gráficas puedes consultar valores y detalles. El botón de restablecer recupera la selección inicial.

El tablero funciona sin conexión una vez descargado y no requiere instalación. Las fuentes, definiciones y notas de lectura se encuentran en el apartado desplegable al final del tablero.

## Datos y alcance

El contenido procede de la base de datos suministrada para el curso, con información del DANE y del Banco Mundial según las referencias incorporadas en el tablero.

Las dos vistas adicionales incorporan fuentes oficiales descargadas el 16 de octubre de 2026: Consejo Privado de Competitividad y Universidad del Rosario, DNP y DANE.

- PIB nacional y departamental: series desde 1980, con la cobertura territorial disponible en la base.
- PIB por habitante internacional: selección de países y agregados, expresado en PPA constante de 2021.
- Empleo y producción: comparación de 2015 y 2025. El total disponible corresponde a 23 departamentos; no es el total nacional.
- Población: contraste de 1985, 2026 y 2050, distinguiendo estimaciones y proyecciones. El corte de 1985 se conserva de una versión anterior de la base del curso.
- Producción y pobreza municipal: exploración de la asociación entre valor agregado por habitante e IPM. Las correlaciones no demuestran causalidad; los años no informados en la fuente no se imputan.
- Mercado laboral: participación, ocupación y desocupación, con comparaciones por sexo o área.
- Competitividad y bienestar: corte analítico 2024. IDC y PIB por habitante para departamentos; ICC e ICM con valor agregado por habitante para ciudades y municipios. Se comparan también IPM, pobreza monetaria y Gini. La cobertura varía según el indicador y se indica en pantalla; el Gini municipal solo está disponible para 23 capitales. El ICM incorpora variables de pobreza y producción, por lo que estos cruces no son validaciones independientes.
- Perspectivas de pobreza: corte común 2018, para incorporar el NBI censal junto con pobreza monetaria, IPM, déficit habitacional, pobreza subjetiva y Gini. La comparación usa los mismos 24 territorios con información completa. Las medidas no son intercambiables: unas se expresan sobre personas, otras sobre hogares y el Gini mide desigualdad de ingresos.

El archivo contiene una copia de los datos preparada para el curso. No se actualiza automáticamente cuando cambian las fuentes o el Excel original.
