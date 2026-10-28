El código cumple Abierto/Cerrado 

La clase Producto está cerrada a modificació, ya definida con sus atributos Nombre y Precio y métodos getNombre, setNombre, getPrecio y setPrecio, no necesitas tocar ni una sola línea de Producto.h ni de Producto.cpp para añadir nuevos tipos de productos al sistema

La clase Producto está abierta a extensión gracias a Fisico y Digital heredan de ella (class Fisico : public Producto y class Digital : public Producto), se puede crear tantas clases nuevas como se quiera