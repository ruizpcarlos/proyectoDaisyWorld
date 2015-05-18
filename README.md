# Proyecto DaisyWorld
Para apoyar la teoría de Gaia, en 1983 James Lovelock y Andrew Watson publicaron el artículo 
*Biological homeostasis of the global environment: the parable of Daisyworld* en el cual mostraron la simulación 
por computadora de Daisyworld. Este proyecto pretende replicar el experimento, que modela un mundo que orbita alrededor 
de una estrella durante todo el periodo de vida de ésta (las estrellas al evolucionar van cambiando su emisión de radiación
la cual afecta la temperatura del planeta). 

En el planeta existen dos tipos de margaritas: negras y blancas. Las primeras absorben luz, las blancas la reflejan. 
La temperatura global del planeta (que depende de la luminosidad de la estrella) afecta como se reproducen estas especies.

En el archivo `daisyworld_original` se encuentra la simulación original: un mundo con dos especies de margaritas con diferentes albedos (proporciones de luz reflejada). Además, se incluyen un método que modela el mundo con condiciones aleatorias y uno interactivo, en el que se pueden modificar arbitrariamente las condiciones iniciales del sistema.

También se realizó un modelo que considera una tercera especie de margaritas grises (`cheats`), e incluye, además de un 
método interactivo, la animación del desarrollo del mundo de manera espacial. Éste se encuentra en el notebook `daisyworld_cheats`.

Una tercer modelo, de mayor complejidad, simula un mundo donde, además de plantas, viven animales herbívoros y depredadores
(conejos y zorros). En el archivo `daisyworld_depredadores` se puede encontrar ese modelo, en el que se puede interactuar modificando las condiciones iniciales del mundo con animales.
