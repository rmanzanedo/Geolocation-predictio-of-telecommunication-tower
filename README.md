El set de datos proporcionado (data1) proviene de datos generados por “smartphones” de diversas personas en Madrid capital. Cada registro se genera bajo determinadas condiciones y contiene la geolocalización GPS del móvil y una serie de indicadores de calidad de red que se tienen en ese momento.

### Dataset
**_data1:_** datos asociados a las mediciones previamente descritas

* **cell_id:** identificador único de la celda (antena) a la que el móvil está conectado. Concatenado de los ids de país, operador, torre y celda.
* **cell_network_type:** tecnología de la red (4G, 3G, 2G...)
* **cell_frequency_band:** banda de frecuencia de la celda (Megahercios)
* **enodeb:** identificador único de la torre en la que se aloja la celda a la que se está conectado. Cada torre puede albergar varias celdas.
* **ci:** identificador de la celda.
* **signal_strength:** potencia de señal de la red (decibelios/milivatio)
* **rssnr:** relación señal-ruido de la red (decibelios/milivatio)
* **timing_advance:** tiempo que tarda la señal de red en ir de la celda al móvil (microsegundos). Por cada 3.69 µs, timing_advance se incrementa en 1. 
* **connection_type:** tipo de conexión (wifi, móvil...)
* **environment:** tipo de entorno (interior, exterior, vehículo)
* **gps_accuracy:** precisión de la señal GPS (metros)
* **gps_speed:** velocidad GPS (metros/segundo)
* **latitude:** latitud GPS(grados decimales)
* **longitude:** longitud GPS(grados decimales)


**_data2:_** relación entre las celdas, bandas de frecuencia y sectores.

* **ci:** identificador de la celda.
* **cell_frequency_band:** banda de frecuencia de la celda (Megahercios)
* **sector:** región espacial a la que da cobertura la celda.


### Cuestiones:

1. Realizar un análisis exploratorio de los datos (EDA). 

2. Hallar un método para calcular de forma más o menos precisa la geolocalización de las torres de telefonía, y demostrar los resultados obtenidos de tal método.