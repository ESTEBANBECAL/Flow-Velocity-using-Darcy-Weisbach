# Flow-Velocity-using-Darcy-Weisbach
INTRODUCCIÓN 
El transporte de hidrocarburos por tubería es de vital importancia para la economía global y el suministro energético. Las tuberías proporcionan una forma eficiente y segura de transportar grandes volúmenes de petróleo, gas natural y gasolinas a largas distancias, conectando regiones productoras con centros de consumo. Esta infraestructura es fundamental para satisfacer la demanda de energía de industrias, hogares y transporte, contribuyendo al desarrollo económico y la estabilidad energética de los países. Además, el transporte por tubería reduce la dependencia de otros medios más costosos y menos seguros, como el transporte por carretera o marítimo, y minimiza los riesgos ambientales asociados con posibles derrames y emisiones de gases de efecto invernadero.

Cuando una empresa de transporte de hidrocarburos recibe un combustible en un punto A, que suele ser una refinería, con el propósito de transportarlo al punto B, típicamente centros de distribución, se establece legalmente un volumen y producto en custodia. Esto implica que la empresa transportista se compromete con el cliente a entregar la misma cantidad en volumen y calidad de producto en el punto B como la recibida en el punto A.
La importancia del sistema de medición radica en su capacidad para asegurar que la empresa no sufra pérdidas ni obtenga ganancias injustificadas en relación con el cliente. En el caso de Ecopetrol y según la normativa del American Petroleum Institute (API), el sistema de medición utilizado para la transferencia de custodia debe seguir un esquema específico que incluye: válvula de corte, sistema de filtración, válvula reguladora de presión, enderezador de flujo, medidor tipo turbina, válvula reguladora de caudal y válvula de corte. Este riguroso proceso garantiza una medición precisa y confiable en todas las etapas del transporte de hidrocarburos.

El medidor tipo turbina es un dispositivo utilizado para medir el flujo de líquidos a través de tuberías, consiste en un rotor o una serie de rotores dispuestos en serie dentro de un tubo de flujo. Estos rotores están conectados a un eje central que, a su vez, está vinculado a un sistema de medición. Cuando el fluido pasa a través del medidor, los rotores son impulsados por el flujo, lo que genera una rotación proporcional a la velocidad del flujo. Esta rotación se convierte en una señal eléctrica que se puede utilizar para determinar la tasa de flujo del líquido.
La precisión del medidor tipo turbina puede ser afectada por diversos factores, como la viscosidad y densidad del líquido, así como la presencia de partículas sólidas en suspensión que pueden adherirse a los rotores, generando desequilibrios en su funcionamiento. Además, el tipo de flujo también ejerce influencia en la calidad de la medición de la turbina, es crucial que el flujo del fluido sea lo más laminar posible para asegurar una medición precisa, evitando así el flujo turbulento, dado que el medidor utiliza la velocidad del flujo para determinar el caudal con exactitud. 

Un enderezador de flujo, también conocido como acondicionador de flujo, se emplea para mejorar la uniformidad y estabilidad del flujo de un fluido antes de su medición. Su función es reducir la turbulencia y las fluctuaciones en el flujo, lo que conduce a un perfil de flujo más homogéneo o laminar. Esto se logra al suavizar el flujo y permitir que el fluido se desplace de manera más uniforme y controlada, aunque esto implica una disminución en la velocidad del flujo y un aumento en la contrapresión aguas arriba, mejora la precisión de las mediciones y optimiza el número de Reynolds.


PLANTEAMIENTO DEL PROBLEMA
Se tiene la intención de investigar el efecto que un enderezador de flujo tiene en la velocidad y el número de Reynolds para determinar los beneficios que aporta a la estabilidad del flujo y, consecuentemente, al sistema de medición en la Estación Manizales de Ecopetrol.


METODOLOGÍA
Se emplearán datos reales del sistema de medición de la Estación Manizales para simular un escenario real. Se aplicarán diversas ecuaciones, como la ecuación de continuidad, la ecuación de Darcy-Weisbach y la ecuación de Reynolds, entre otras, y se apoyarán en un sistema de programación como Python. Este sistema facilitará la realización de cálculos numéricos, como el método de Runge-Kutta, el método de Lagrange, entre otros, lo que permitirá una mayor precisión y eficiencia en el análisis.

LIBRERÍAS
moviepy.editor
matplotlib.pyplot 
matplotlib.image 
math
numpy
