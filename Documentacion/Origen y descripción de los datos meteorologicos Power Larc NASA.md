## Origen de los datos meteorologicos Power Larc NASA.
Son datos provenientes del *Power Project* de la Administración Nacional de Aeronáutica y el Espacio (**NASA** por sus siglas en inglés).
La obtencion de los mismos se realizó mediante descarga desde la pagina web https://power.larc.nasa.gov/data-access-viewer/ desde donde podes seleccionar el punto del planeta deseado y las variables a incluir y permite descargarlas en distintos formatos.

##### Diccionario de datos
| Variable | Descripción | Tipo de Dato |
|---|---|---|
| YEAR | Año del dato | Entero |
| DOY | Día del año (0-366) | Entero |
| ALLSKY_SFC_SW_DWN | CERES SYN1deg Irradiancia descendiente de onda corta en superficie cielo completo (kW-hr/m²/día) | Real |
| CLRSKY_SFC_SW_DWN | CERES SYN1deg Irradiancia descendiente de onda corta en superficie cielo despejado (kW-hr/m²/día) | Real |
| ALLSKY_SFC_SW_DNI | CERES SYN1deg Irradiancia normal directa descendiente de onda corta en superficie cielo completo (kW-hr/m²/día) | Real |
| ALLSKY_SFC_SW_DIFF | CERES SYN1deg Irradiancia difusa de onda corta en superficie cielo completo (kW-hr/m²/día) | Real |
| ALLSKY_KT | CERES SYN1deg Índice de claridad de insolación cielo completo (adimensional) | Real |
| ALLSKY_SFC_LW_DWN | CERES SYN1deg Irradiancia descendiente de onda larga en superficie cielo completo (kW-hr/m²/día) | Real |
| ALLSKY_SFC_PAR_TOT | CERES SYN1deg PAR total en superficie cielo completo (kW-hr/m²/día) | Real |
| CLRSKY_SFC_PAR_TOT | CERES SYN1deg PAR total en superficie cielo despejado (kW-hr/m²/día) | Real |
| ALLSKY_SFC_UVA | CERES SYN1deg Irradiancia UVA en superficie cielo completo (kW-hr/m²/día) | Real |
| ALLSKY_SFC_UVB | CERES SYN1deg Irradiancia UVB en superficie cielo completo (kW-hr/m²/día) | Real |
| ALLSKY_SFC_UV_INDEX | CERES SYN1deg Índice UV en superficie cielo completo (W m-2 x 40) | Real |
| WS2M | MERRA-2 Velocidad del viento a 2 metros (m/s) | Real |
| T2M | MERRA-2 Temperatura a 2 metros (C) | Real |
| T2MDEW | MERRA-2 Punto de rocío/escarcha a 2 metros (C) | Real |
| T2MWET | MERRA-2 Temperatura de bulbo húmedo a 2 metros (C) | Real |
| TS | MERRA-2 Temperatura de la superficie de la tierra (C) | Real |
| T2M_RANGE | MERRA-2 Rango de temperatura a 2 metros (C) | Real |
| T2M_MAX | MERRA-2 Temperatura máxima a 2 metros (C) | Real |
| T2M_MIN | MERRA-2 Temperatura mínima a 2 metros (C) | Real |
| QV2M | MERRA-2 Humedad específica a 2 metros (g/kg) | Real |
| RH2M | MERRA-2 Humedad relativa a 2 metros (%) | Real |
| PRECTOTCORR | MERRA-2 Precipitación corregida (mm/día) | Real |
| PS | MERRA-2 Presión de superficie (kPa) | Real |
| WS10M | MERRA-2 Velocidad del viento a 10 metros (m/s) | Real |
| WS10M_MAX | MERRA-2 Velocidad máxima del viento a 10 metros (m/s) | Real |
| WS10M_MIN | MERRA-2 Velocidad mínima del viento a 10 metros (m/s) | Real |
| WS10M_RANGE | MERRA-2 Rango de velocidad del viento a 10 metros (m/s) | Real |
| WD10M | MERRA-2 Dirección del viento a 10 metros (Grados) | Real |
| WS50M | MERRA-2 Velocidad del viento a 50 metros (m/s) | Real |
| WS50M_MAX | MERRA-2 Velocidad máxima del viento a 50 metros (m/s) | Real |
| WS50M_MIN | MERRA-2 Velocidad mínima del viento a 50 metros (m/s) | Real |
| WS50M_RANGE | MERRA-2 Rango de velocidad del viento a 50 metros (m/s) | Real |
| WD50M | MERRA-2 Dirección del viento a 50 metros (Grados) | Real |


*El archivo contiene 1461 instancias una por cada día de cada año (365 en 2021, 365 en 2022, 365 en 2023 y 366 en 2024 ).
