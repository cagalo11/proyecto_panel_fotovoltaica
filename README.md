# proyecto_panel_fotovoltaica
## Proyecto módulo desarrollo web con Python
### Autores:
* Camilo García López
* Yamid Andrés Melgarejo
* Juan Esteban de la Calle
* Esperanza Cortés
* Victor Manuel Hincapié


## Descripción:

La aplicación desarrollada indica la potencia máxima de una panel fotovoltaico Solar Sunset tomando como entrada el nivel de irradiancia (en Watts) y la temperatura (en grados Celsius). La interacción con la aplicación se da a través de la selección de una zona geográfica en el mapa, para la cual se muestran los niveles de irradiancia y temperatura correspondientes y, una vez seleccionada por el usuario, se muestra la potencia máxima para un panel fotovoltaico instalado en tal lugar y la correspondiente gráfica I-V para el panel Solar Sunset.

La estimación de la potencia máxima se hace con el *Modelo de los Cinco Parámetros*, para  cual se tomó como base la tésis de maestría *Control por modos deslizantes
aplicado a un inversor de fuente de corriente monof´asico conectado a la red*, la cual se puede leer  [en este documento](https://repositorio.unal.edu.co/bitstream/handle/unal/79905/1086362120.2021.pdf?sequence=4&isAllowed=y). El desarrollo de la aplicación de hizo usando el módulo de *flask* en Python, donde utilizamos *html* para el diseño de la interfaz y datos geospaciales de la NASA tratados en *Arcgis*.
