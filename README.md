# Caracterización TerriData

Tablero público en Power BI que reúne **todos los indicadores de [TerriData](https://terridata.dnp.gov.co/)**, el sistema de estadísticas territoriales del Departamento Nacional de Planeación (DNP), para que cualquier persona pueda consultar, comparar y entender los datos de su municipio o departamento sin descargar archivos ni saber de bases de datos.

**[Abrir el tablero](https://app.powerbi.com/view?r=eyJrIjoiMTRiMDExZjktMzViNC00MTBhLTllZDYtMWJkMTVhYWJhMTE0IiwidCI6IjE2YWY2YjQ1LTAwYzUtNGJhMy05ZDRjLThiZmExNmU0MzYwMyIsImMiOjR9)**

Elaborado por Cristian Ortega - [@CristianMDE](https://x.com/CristianMDE)

## Para qué sirve

La información sobre el Estado colombiano en los territorios es pública, pero está repartida en cientos de indicadores, decenas de fuentes y un archivo por departamento. Este tablero la pone en un solo lugar y la convierte en mapas, tablas y comparaciones que se leen de un vistazo. Con él, la ciudadanía, periodistas, estudiantes, investigadores y funcionarios pueden:

- Ver cómo está su municipio o departamento en cualquier tema: finanzas, pobreza, salud, educación, seguridad, ambiente y más.
- Compararlo con los demás municipios del departamento, con otros departamentos y con el total nacional.
- Seguir la evolución de un indicador año por año.
- Ubicar en el mapa dónde están los valores más altos y más bajos del país.

## Qué contiene

**1.750 indicadores**, organizados en **24 dimensiones** y **128 subcategorías**, para los municipios y departamentos del país y el total nacional, con series anuales desde el año 2000 hasta 2025; las proyecciones de población llegan hasta 2027.

| Dimensión | Indicadores | Subcategorías |
|---|---:|---:|
| Economía | 524 | 23 |
| Demografía y población | 219 | 11 |
| Finanzas públicas | 146 | 15 |
| Censo 2005 y proyecciones DANE | 136 | 8 |
| Pobreza | 134 | 6 |
| Ambiente | 84 | 19 |
| Justicia y derecho | 65 | 5 |
| Vivienda y acceso a servicios públicos | 56 | 1 |
| Salud | 50 | 2 |
| Convivencia y seguridad ciudadana | 46 | 2 |
| Ordenamiento Territorial | 46 | 10 |
| Seguridad integral marítima y fluvial | 45 | 3 |
| Educación | 37 | 5 |
| Medición de desempeño municipal | 32 | 3 |
| Mercado laboral | 30 | 9 |
| Administración pública | 27 | 1 |
| Índice de Ciudades Modernas (ICM) | 21 | 1 |
| Paz y víctimas | 20 | 3 |
| Descripción general | 11 | 1 |
| Turismo | 8 | 1 |
| Cultura | 7 | 3 |
| Medición de desempeño departamental | 3 | 1 |
| Presupuesto general de la nación | 2 | 1 |
| Ciencia, Tecnología e Innovación | 1 | 1 |

Algunos de los indicadores que se pueden consultar:

- **Finanzas públicas**: porcentaje de ingresos que corresponden a transferencias, porcentaje del gasto destinado a inversión, capacidad de ahorro, indicador de desempeño fiscal, ingresos tributarios per cápita, recursos asignados del SGP por sector.
- **Pobreza**: incidencia de la pobreza monetaria extrema, privaciones del Índice de Pobreza Multidimensional, necesidades básicas insatisfechas, hacinamiento crítico.
- **Educación**: cobertura bruta en educación básica y media, tasa de analfabetismo, puntaje promedio en las Pruebas Saber 11.
- **Salud**: afiliados al régimen subsidiado, partos atendidos por personal calificado, tasa de fecundidad en mujeres de 15 a 19 años.
- **Convivencia y seguridad ciudadana**: tasa de homicidios por cada 100.000 habitantes, tasa de violencia intrafamiliar.
- **Vivienda y servicios públicos**: déficit habitacional, cobertura de acueducto rural, cobertura de energía eléctrica rural.
- **Economía**: contribución al PIB nacional, valor agregado, rendimiento de los cultivos, principales cultivos de cada entidad.
- **Ambiente**: área de manglares, deforestación, vulnerabilidad y riesgo por cambio climático, personas afectadas por desastres.
- **Paz y víctimas**: iniciativas PDET con ruta de implementación activada, restitución de tierras, víctimas de desplazamiento que superan la situación de vulnerabilidad.
- **Demografía y población**: población por sexo y grupos de edad, población étnica, migración, información del SISBEN IV.

## Cómo está organizado el tablero

El tablero tiene cuatro páginas:

1. **Mapa Municipios**: un mapa de Colombia por municipio, coloreado en cuatro grupos (cuartiles) según el valor del indicador, junto a una tabla con la serie histórica de cada municipio. Indica cuántos municipios tienen dato y cuántos no.
2. **Mapa Departamentos**: el mismo mapa y la misma tabla a nivel departamental.
3. **Tabla y comparativo**: un ranking en barras de las entidades seleccionadas, con la entidad más alta, la más baja y la brecha entre ambas, y el valor de Colombia como referencia.
4. **Datos**: una tabla de consulta con todos los indicadores de una dimensión para cada entidad y año, con filtros por fuente, dimensión, año, nivel y entidad.

## Cómo se usa

1. Elija la **dimensión** (por ejemplo, Finanzas públicas).
2. Elija el **indicador** en la lista, que tiene buscador. Cada opción muestra el indicador, su dimensión, su subcategoría y su fuente.
3. Elija el **año**.
4. Si quiere, elija uno o varios **departamentos** para acercar el mapa y limitar la comparación.

Al pasar el cursor sobre el mapa o las barras aparece el valor exacto de cada entidad.

## Fuente de los datos

Todos los datos provienen de TerriData (DNP), que a su vez recoge información de entidades como el DANE, los ministerios de Educación, Salud, Agricultura, Justicia y Defensa, la UPRA, el IDEAM, el IGAC y Migración Colombia, entre otras. El tablero muestra la fuente de cada indicador junto a su nombre.

## Archivos del repositorio

- `Tablero Caracterización Terridata Publico2.pbix`: el tablero, para abrir con Power BI Desktop.
- `Homologación indicadores.csv`: el listado completo de indicadores con su dimensión, subcategoría y fuente.

## Licencia

© 2026 Cristian Ortega. Este repositorio se publica bajo la licencia [Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es): puede usarse, compartirse y adaptarse, incluso con fines comerciales, siempre que se dé crédito al autor.

Cita sugerida:

> Ortega, Cristian (2026). *Caracterización TerriData* [tablero de Power BI]. [@CristianMDE](https://x.com/CristianMDE).

La licencia cubre el tablero y el material propio de este repositorio. Los datos de TerriData son del DNP y se rigen por sus propias condiciones de uso.
