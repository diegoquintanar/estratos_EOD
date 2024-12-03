# estratos_EOD
En este repositorio se calculan los tiempos promedio de viaje para los distritos de la ZMVM en los años 2007 y 2017. Posteriormente se calcula un estrato socioemográfico para los mismos distritos y se corre un modelo de regresión simple entre tiempo de viaje y estrato sociodemográfico.
Los datos de las encuestas origen destino pueden descargarse de las siguientes ligas:
EOD2007: https://drive.google.com/file/d/1iAhnNWIOwUSqOJ8uzUsETQ65MJeENQmr/view 
EOD2017: https://www.inegi.org.mx/programas/eod/2017/#datos_abiertos
Ambas bases de datos se unieron mediante los campos llave que se especifican en sus metodologías, de tal manera que las bases de viviendas, hogares, residentes, vehículos y viajes se unieron en un único dataframe para ambos años.
Los datos sobre el censo para 2010 y 2020 pueden descargarse de la siguientes ligas:
Censo resultados por ageb 2010: https://www.inegi.org.mx/app/scitel/default?ev=7
Censo resultados por ageb 2020: https://www.inegi.org.mx/app/scitel/Default?ev=10
