# Factory-Method
adjunnto se encuentra el diagrama UML

1. SodaFactory: Esta es una clase abstracta que define el método createSoda(). Las subclases concretas de SodaFactory implementarán este método para crear instancias de Soda.

2. Soda: Esta es una clase abstracta que representa una gaseosa genérica. Puede contener propiedades comunes a todas las gaseosas, como el nombre (name).

3. ColaSoda, LemonLimeSoda y OrangeSoda: Estas son subclases concretas de Soda que representan tipos específicos de gaseosas con implementaciones particulares. Cada una de ellas puede tener su propia lógica y atributos.


En este diagrama, SodaFactory es la clase que define el Factory Method, y las subclases concretas de SodaFactory (por ejemplo, una fábrica para gaseosa de cola, una para gaseosa de lima-limón, etc.) son responsables de implementar ese método y crear objetos Soda específicos, como ColaSoda, LemonLimeSoda y OrangeSoda. Esto permite la creación de diferentes tipos de gaseosas a través del mismo Factory Method, manteniendo así la flexibilidad y la extensibilidad en la creación de productos.

