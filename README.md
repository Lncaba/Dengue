# Análisis sobre los casos de dengue y la densidad poblacional del "Conurbano bonaerense" en el período 2025 y junio del 2026. 

Mi nombre es Lucas Caballero y desde la Tecnicatura Universitaria en Gestión por Evidencia e Inteligencia Territorial (UNIPE), este repositorio corresponde al Trabajo final integrador de la materia Ciencias de Datos II.

Se propone como objetivo analizar como se desarrolla la incidencia de casos de dengue, mediante la utilización de los datos recopilados de la población (a partir del Censo 2022) del área correspondiente al Conurbano Bonaerense; el mismo refiere a los 24 partidos de la provincia de Buenos Aires, sin la participación de la Ciudad Autónoma de Buenos Aires, en el período del año 2025 hasta la actualidad.

## El repositorio se compone de:

[data](./data):

`info_publica_dengue-1-2025-a-2026-06-15.csv`: corresponde a la Vigilancia de Dengue y Zika (Se 1 2025 - Se 22 2026), datos que son correspondientes al Registro del Sistema Nacional de Vigilancia de la Salud 2.0, por parte del Ministerio de Salud de la Nación Argentina. 

Fuente: Ministerio de Salud. Secretaría de Promoción de la Salud, Prevención y Control de Riesgos. Subsecretaría de Prevención y Control de Enfermedades Comunicables e Inmunoprevenibles. Dirección Nacional de Epidemiología y Análisis de la Situación de Salud. Área de Vigilancia (2026). Vigilancia de Dengue y Zika (Se 1 2025 - Se 22 2026). Recuperado el 20 de junio, 2026, de https://datos.salud.gob.ar/dataset/vigilancia-de-dengue-y-zika/archivo/33e12e9f-1d14-4bc7-b34c-a1f88ab7b990 

`Poblacion_2022_amba_departamentos.csv`: corresponde a Indicadores del Censo Nacional de Población, Hogares y Viviendas, 2022; para POBLACIONES (en conjunto con CONICET y ODSA-UCA). Se seleccionó el Área Metropolitana de Buenos Aires (AMBA) para luego ir modificando el dataset a la necesidad pretendida. 

Fuente: Pablo De Grande y Agustín Salvia (2024). Indicadores del Censo Nacional de Población, Hogares y Viviendas, 2022. Recuperado el 20 de junio, 2026, de https://poblaciones.org/@257701

[graficos](./graficos):

`grafico_cajas.jpg`: corresponde a un gráfico de boxplot utilizado para ver los outliers, o municipios que destacan en tasa de Incidencia o densidad poblacional. 

`grafico_correlacion.jpg`: gráfico de dispersion para cruzar Densidad y Tasa de Incidencia. 

`mapa_casos.jpg`: mapa destancando la cantidad bruta de casos de dengue por municipios.

`mapa_coropleta.jpg`: mapa destacando la tasa de Incidencia por municipios.

## Otras referencias:

Ministerio de Salud de la Nación. (2024). Resumen ejecutivo: Plan de preparación y respuesta integral a epidemias de dengue y otras enfermedades arbovirales. Argentina.gob.ar. https://www.argentina.gob.ar/sites/default/files/2024/08/2025-10-resumen-ejecutivo-plan-preparacion-arbovirus-1310.pdf

Programa de Estudios del Conurbano. (2016). Conurbano. Atlas del Conurbano Bonaerense; Universidad Nacional de Avellaneda. https://www.atlasconurbano.info/pagina.php?id=169

Ruiz Nicolini J, Del Boca P, Juara J (2024). geoAr: Argentina’s Spatial Data Toolbox. R package version 1.0.0, https://github.com/PoliticaArgentina/geoAr.
