Se requiere un programa que modele el concepto de un automóvil. Un 
automóvil tiene los siguientes atributos:
u Marca: el nombre del fabricante.
u Modelo: año de fabricación.
u Motor: volumen en litros del cilindraje del motor de un automóvil.
u Tipo de combustible: valor enumerado con los posibles valores de 
gasolina, bioetanol, diésel, biodiésel, gas natural.
u Tipo de automóvil: valor enumerado con los posibles valores de 
carro de ciudad, subcompacto, compacto, familiar, ejecutivo, SUV.
u Número de puertas: cantidad de puertas.
u Cantidad de asientos: número de asientos disponibles que tiene el 
vehículo.
u Velocidad máxima: velocidad máxima sostenida por el vehículo 
en km/h.
u Color: valor enumerado con los posibles valores de blanco, negro, 
rojo, naranja, amarillo, verde, azul, violeta.
u Velocidad actual: velocidad del vehículo en un momento dado.


La clase debe incluir los siguientes métodos:
u Un constructor para la clase Automóvil donde se le pasen como 
parámetros los valores de sus atributos.
u Métodos get y set para la clase Automóvil.
u Métodos para acelerar una cierta velocidad, desacelerar y frenar 
(colocar la velocidad actual en cero). Es importante tener en cuenta que no se debe acelerar más allá de la velocidad máxima permitida para el automóvil. De igual manera, tampoco es posible 
desacelerar a una velocidad negativa. Si se cumplen estos casos, se 
debe mostrar por pantalla los mensajes correspondientes.
u Un método para calcular el tiempo estimado de llegada, utilizando 
como parámetro la distancia a recorrer en kilómetros. El tiempo 
estimado se calcula como el cociente entre la distancia a recorrer y 
la velocidad actual.
u Un método para mostrar los valores de los atributos de un Automóvil en pantalla.
u Un método main donde se deben crear un automóvil, colocar su 
velocidad actual en 100 km/h, aumentar su velocidad en 20 km/h, 
luego decrementar su velocidad en 50 km/h, y después frenar. Con 
cada cambio de velocidad, se debe mostrar en pantalla la velocidad 
actual.