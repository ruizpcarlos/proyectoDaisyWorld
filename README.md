# Proyecto DaisyWorld
Para apoyar la teoría de Gaia, en 1983 James Lovelock y Andrew Watson publicaron el artículo 
*Biological homeostasis of the global environment: the parable of Daisyworld* en el cual mostraron la simulación 
por computadora de Daisyworld. Este proyecto pretende replicar el experimento, que modela un mundo que orbita alrededor 
de una estrella durante todo el periodo de vida de ésta (las estrellas al evolucionar van cambiando su emisión de radiación
la cual afecta la temperatura del planeta). En el planeta existen dos tipos de margaritas: negras y blancas. Las primeras absorben luz, las blancas la reflejan. La temperatura global del planeta (que depende de la luminosidad de la estrella) afecta como se reproducen estas especies.

Para reproducir esta simulación, nos basamos en los modelos matemáticos del proyecto *Daisyworld modeling and feedback mechanisms* (Wittwer, 2005), publicado por la Universidad de Australia Occidental (UWA). 

En el archivo `daisyworld_original.ipynb` se encuentra la simulación original: un mundo con dos especies de margaritas con diferentes albedos (proporciones de luz reflejada). Además se incluye un método que modela el mundo con condiciones iniciales aleatorias.

También se realizó un modelo que considera una tercera especie de margaritas grises (`cheats`), e incluye, además de un 
método que modela con condiciones iniciales aleatorias y el modelo espacial, un metodo interactivo en el que se pueden modificar arbitrariamente las condiciones iniciales del sistema. Éste se encuentra en el notebook `daisyworld_cheats.ipynb`.

Una tercer modelo, de mayor complejidad, simula un mundo donde, además de plantas, viven animales herbívoros y depredadores
(conejos y zorros). En el archivo `daisyworld_depredadores.ipynb` se puede encontrar ese modelo, en el que se puede interactuar modificando las condiciones iniciales del mundo con animales.
