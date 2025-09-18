## Topologías de red
La topología de red describe cómo se organizan los elementos de una red de comunicaciones. La estructura topológica se puede representar física o lógicamente.

En el caso de la topología lógica, los dispositivos de comunicación se modelan como nodos y las conexiones entre dispositivos se modelan como enlaces o líneas entre nodos.

La topología física describe la verdadera apariencia o diseño de la red. Las distancias entre nodos, interconexiones físicas, velocidades de transmisión o tipos de señales pueden diferir entre dos redes, pero sus topologías lógicas pueden ser idénticas.

Al mapear gráficamente estos enlaces, obtenemos algunas formas geométricas que se pueden usar para describir diferentes topologías. Cada tipo tiene ventajas y desventajas, ya que difieren en cómo los dispositivos pueden conectarse entre sí.

---

## Topologia punto a punto
Una red punto a punto, o una topología de puntos, es la red más fácil de entender y el tipo más básico de topología de red. Son simplemente dos nodos que están conectados por un solo enlace. Los datos viajan de un lado a otro entre estos dos endpoints. Aunque este es el tipo de red más fácil de configurar, su simplicidad es su propio inconveniente. Una topología punto a punto no es aplicable para la mayoría de los casos de uso modernos.

---

## Topología Estrella
En una red en estrella, todos los nodos están conectados a un concentrador central. Los nodos se colocan alrededor de ese eje central en una forma que se asemeja aproximadamente a una estrella.

Este tipo de topología facilita la resolución de problemas con un nodo en particular. Si falla un solo nodo, el resto de la red no se ve afectada. Dicho esto, si el concentrador central se cae, toda la red se cae con él. En una red en estrella, el rendimiento de toda la red depende del concentrador central y de las conexiones a él.

<div align="center">
  <img src="https://github.com/user-attachments/assets/684c7ba5-d5f7-48ab-9464-867c6e37e88b" width="350" height="339">
</div>

---

## Topología en Bus
Toda la transmisión de datos fluye a través de una única conexión central. Como todo está conectado en línea recta desde un cable central, es una topología rentable y fácil de configurar y añadir nuevos nodos.

Sin embargo, un enlace central compartido tiene inconvenientes. En un sistema que tiene un enlace central con muchas dependencias, un fallo de ese enlace central hace que todas las dependencias fallen. Las redes de bus tampoco son tan seguras como otros tipos debido a este enlace central compartido. Además, cuantos más nodos comparten un cable central, más lenta es una red.
<div align="center">
  <img src="https://github.com/user-attachments/assets/e2d6bcd4-da7a-4e9a-a95b-f7f97020e090" width="350" height="339">
</div>

---

## Topología en Anillo
En una red en anillo, los nodos y enlaces se organizan en un anillo. Cada nodo tiene exactamente dos vecinos. En una red de este tipo, los repetidores se utilizan para garantizar que los datos puedan llegar a los nodos que están más alejados entre sí en el anillo. Los datos suelen fluir unidireccionalmente en una red en anillo.

La instalación y ampliación de este tipo de redes es barata, y los datos fluyen rápidamente dentro de la red. Pero el fallo de un solo nodo puede hacer caer toda la red. Las redes de doble anillo se utilizan para protegerse contra este tipo de fallos.

Una red de doble anillo presenta dos anillos concéntricos en lugar de uno, y los anillos envían datos en direcciones opuestas. El segundo anillo se utiliza cuando se produce un fallo en el primero y este tipo de red se utiliza a menudo para dar soporte a infraestructuras cruciales.
<div align="center">
  <img src="https://github.com/user-attachments/assets/610980a8-f27f-446c-8105-99b620482bf7" width="350" height="325">
</div>

---

## Topología en Árbol
Es útil pensar en una topología de árbol como una combinación de una red de bus y una red en estrella. En una topología de árbol, sigue habiendo un concentrador central que lo conecta todo, pero en lugar de nodos individuales que se ramifican desde ese nodo raíz central, se trata de otras redes en estrella. Esta topología permite que más dispositivos se conecten a un centro de datos central, lo que acelera el flujo de datos. Al igual que en una red en estrella, identificar problemas con nodos individuales es relativamente fácil.

Las topologías en árbol tienen los mismos inconvenientes que las redes en bus y en estrella, a saber, la vulnerabilidad a un único punto de fallo. Si esa conexión central se cae, todo se cae.
<div align="center">
  <img src="https://github.com/user-attachments/assets/000b430a-01a5-4fc4-ae4d-2f709511353a" width="350" height="350">
</div>

---

## Topología de Malla
En una red de malla, cada dispositivo está conectado al menos a otro nodo de la red. En una red de malla completa, cada nodo está conectado a todos los demás nodos. En una red de malla parcial, sólo algunos de los nodos se conectan directamente entre sí, mientras que otros tienen que pasar por nodos adicionales para llegar al nodo objetivo.

Dado que los nodos pueden comunicarse directamente entre sí, en lugar de a través de un concentrador central, la comunicación en una red de malla suele ser muy rápida. Un gran ejemplo de red mallada es la propia Internet, donde cada ordenador es un nodo de una red proporcionada por distintos proveedores de servicios de Internet que también se conectan entre sí.

Dado que las redes en malla tienen múltiples rutas por las que puede viajar la información, son más resilientes que muchas otras topologías y pueden seguir funcionando si falla un nodo o una conexión. Las redes en malla también ofrecen mayor seguridad: si un nodo es atacado o comprometido, puede ser reemplazado.
<div align="center">
  <img src="https://github.com/user-attachments/assets/e5572e1f-cbdc-4b3b-aa29-33f7ee527e8c" width="350" height="322">
</div>

---

## Topología Híbrida
Una topología de red híbrida es cualquier tipo de red que utilice una combinación de topologías. Una red en árbol que combina una red en estrella y una red en bus es un tipo de topología híbrida.

Las redes híbridas ofrecen flexibilidad y ayudan a las organizaciones a diseñar una topología que satisfaga específicamente sus necesidades. Sin embargo, crear una arquitectura de red personalizada puede resultar complicado y requerir más cableado y dispositivos de red, lo que eleva los costes de mantenimiento.






