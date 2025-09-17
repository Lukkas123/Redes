## Topologias de red

## Topologia estrella
Es el tipo de configuración más común. La red está organizada de modo que los nodos estén conectados a  un dispositivo central (un hub),  que actúa como servidor. El hub gestiona la transmisión de datos a través de la red. Es decir, cualquier dato enviado a través de la red viaja a través del dispositivo central antes de terminar en su destino

Ventajas:

Gestión conveniente desde una ubicación central

Si un nodo falla, la red aún funciona

Los dispositivos se pueden agregar o apartaer sin interrumpir la red

Más fácil de identificar y aislar los problemas de rendimiento

Desventajas:

Si el dispositivo central falla, toda su red dejará de funcionar.

El rendimiento y el ancho de banda están limitados por el nodo central

Puede ser costoso de operar
<img width="350" height="339" alt="image" src="https://github.com/user-attachments/assets/684c7ba5-d5f7-48ab-9464-867c6e37e88b" />


## Topologia en Bus
También llamada topología de red troncal, bus o línea, guía los dispositivos a lo largo de un solo cable que se extiende desde un extremo de la red hasta el otro. Los datos fluirán a lo largo del cable a medida que viaja a su destino.

Ventajas:

Económico para redes más pequeñas

Diseño simple; todos los dispositivos conectados a través de un cable

Se pueden agregar más nodos alargando la línea

Desventajas:

La red es vulnerable a fallas de cables.

Cada nodo agregado disminuye la velocidad de transmisión

Los datos solo se pueden enviar en una dirección a la vez.
<img width="949" height="918" alt="image" src="https://github.com/user-attachments/assets/cf632043-8c7e-4e5e-83f1-e0d9477be518" />

## Topología en Anillo

Los nodos se configuran en un patrón circular. Los datos viajan a través de cada dispositivo a medida que viajan a través del anillo. En una red grande, es posible que se necesiten repetidores para evitar la pérdida de paquetes durante la transmisión. Las topologías de anillo se pueden configurar como anillo único (half-dúplex) o anillo doble (full-dúplex) para permitir que el tráfico fluya en ambas direcciones simultáneamente.

Ventajas:

Costo beneficio

Barato de instalar

Problemas de rendimiento fáciles de identificar

Desventajas:

Si un nudo cae, puede caer varios nudos con él.

Todos los dispositivos comparten ancho de banda, lo que puede limitar el rendimiento de trasferencias. 

Agregar o eliminar nodos significa tiempo de inactividad para toda la red
<img width="350" height="325" alt="image" src="https://github.com/user-attachments/assets/610980a8-f27f-446c-8105-99b620482bf7" />

## Topologia en Arbol
Un nodo central conecta los hub secundarios. Estos hubs tienen una relación de padres-hijos con los dispositivos. O eixo central é como o tronco da árvore.El eje central es como el tronco del árbol. Donde las ramas se conectan son los concentradores secundarios o los nodos de control y luego los dispositivos conectados se conectan a los branches.

Ventajas:

Extremadamente flexible y escalable

Facilidad para identificar errores, ya que cada branch de la red puede diagnosticarse individualmente.

Desventajas:

Si falla un hub central, los nodos se desconectarán (aunque las ramas pueden seguir funcionando de forma independiente)

La estructura puede ser difícil de gestionar de forma eficaz

Utiliza mucho más cableado que otros métodos
<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/000b430a-01a5-4fc4-ae4d-2f709511353a" />

## Topología de Malla

Los nodos están interconectados. Los modos full-mesh  conectan todos los dispositivos en la red directamente. En una topología de malla parcial, la mayoría de los dispositivos se conectan directamente. Esto proporciona múltiples rutas para la entrega de datos. Los datos se envían a la distancia más corta disponible para la transmisión.

Ventajas:

confiable y estable

Ningún fallo de un solo nodo desconecta la red

Desventajas:

Grado complejo de interconectividad entre nodos.

Mano de obra intensiva para instalar

Utiliza mucho cableado para conectar todos los dispositivos.
<img width="350" height="322" alt="image" src="https://github.com/user-attachments/assets/e5572e1f-cbdc-4b3b-aa29-33f7ee527e8c" />


## Topología Híbrida

Utiliza varias estructuras de topología. Esto es más común en organizaciones grandes donde cada departamento puede tener un tipo de topología, como estrella o línea, con el hub del departamento conectando a um hub central.

Ventajas:

Flexibilidad

Puede personalizarse según las necesidades del cliente.

Desventajas:

La complejidad aumenta

Se requiere experiencia en múltiples topologías

Puede ser más difícil determinar los problemas de rendimiento.






