## Origen de los datos meteorologicos Power Larc NASA.
Son datos provenientes del *Power Project* de la Administración Nacional de Aeronáutica y el Espacio (**NASA** por sus siglas en inglés).
La obtencion de los mismos se realizó mediante descarga desde la pagina web https://power.larc.nasa.gov/data-access-viewer/ desde donde podes seleccionar el punto del planeta deseado y las variables a incluir y permite descargarlas en distintos formatos.

##### Diccionario de datos
| Variable | Descripción | Tipo de Dato |
|----------|------------|--------------|
| YEAR | Año del dato | Entero |
| DOY | Día del año (0-366) | Entero |
| ALLSKY_SFC_PAR_TOT | Radiación descendiente de onda corta total cielo completo (kW-hr/m²/día) | Real |
| CLRSKY_SFC_PAR_TOT | Radiación descendiente de onda corta total cielo despejado (kW-hr/m²/día) | Real |
| ALLSKY_SFC_SW_DWN | Radiación descendiente de onda corta total cielo completo (CERES SYN1deg) (kW-hr/m²/día) | Real |
| CLRSKY_SFC_SW_DWN | Radiación descendiente de onda corta total cielo despejado (CERES SYN1deg) (kW-hr/m²/día) | Real |
| ALLSKY_SFC_SW_DNI | Radiación descendiente directa normal de onda corta cielo completo (CERES SYN1deg) (kW-hr/m²/día) | Real |
| ALLSKY_SFC_SW_DIFF | Radiación difusa de onda corta cielo completo (CERES SYN1deg) (kW-hr/m²/día) | Real |
| ALLSKY_KT | Índice de claridad de insolación cielo completo (adimensional) | Real |
| ALLSKY_SFC_LW_DWN | Radiación descendiente de onda larga cielo completo (CERES SYN1deg) (kW-hr/m²/día) | Real |
| ALLSKY_SFC_UVA | Radiación UVA cielo completo (CERES SYN1deg) (kW-hr/m²/día) | Real |
| ALLSKY_SFC_UVB | Radiación UVB cielo completo (CERES SYN1deg) (kW-hr/m²/día) | Real |
| ALLSKY_SFC_UV_INDEX | Índice UV superficie cielo completo (CERES SYN1deg) (W m⁻² x 40) | Real |
| T2M | Temperatura a 2 metros (°C) | Real |
| T2MDEW | Punto de rocío/escarcha a 2 metros (°C) | Real |
| T2MWET | Temperatura de bulbo húmedo a 2 metros (°C) | Real |
| TS | Temperatura de la superficie de la tierra (°C) | Real |
| T2M_RANGE | Rango de temperatura a 2 metros (°C) | Real |
| T2M_MAX | Temperatura máxima a 2 metros (°C) | Real |
| T2M_MIN | Temperatura mínima a 2 metros (°C) | Real |
| QV2M | Humedad específica a 2 metros (g/kg) | Real |
| RH2M | Humedad relativa a 2 metros (%) | Real |
| PRECTOTCORR | Precipitación corregida (mm/día) | Real |
| PS | Presión de superficie (kPa) | Real |
| WS2M | Velocidad del viento a 2 metros (m/s) | Real |
| WS2M_MAX | Velocidad máxima del viento a 2 metros (m/s) | Real |
| WS2M_MIN | Velocidad mínima del viento a 2 metros (m/s) | Real |
| WS2M_RANGE | Rango de velocidad del viento a 2 metros (m/s) | Real |
| WD2M | Dirección del viento a 2 metros (°) | Real |
| WS10M | Velocidad del viento a 10 metros (m/s) | Real |
| WS10M_MAX | Velocidad máxima del viento a 10 metros (m/s) | Real |
| WS10M_MIN | Velocidad mínima del viento a 10 metros (m/s) | Real |
| WS10M_RANGE | Rango de velocidad del viento a 10 metros (m/s) | Real |
| WS50M | Velocidad del viento a 50 metros (m/s) | Real |
| WS50M_MAX | Velocidad máxima del viento a 50 metros (m/s) | Real |
| WS50M_MIN | Velocidad mínima del viento a 50 metros (m/s) | Real |
| WS50M_RANGE | Rango de velocidad del viento a 50 metros (m/s) | Real |



*El archivo contiene 730 instancias una por cada día de cada año (365 en 2021 y 365 en 2022).
