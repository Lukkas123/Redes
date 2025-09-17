## Topologías de red
La topología de red describe cómo se organizan los elementos de una red de comunicaciones. La estructura topológica se puede representar física o lógicamente.

En el caso de la topología lógica, los dispositivos de comunicación se modelan como nodos y las conexiones entre dispositivos se modelan como enlaces o líneas entre nodos.

La topología física describe la verdadera apariencia o diseño de la red. Las distancias entre nodos, interconexiones físicas, velocidades de transmisión o tipos de señales pueden diferir entre dos redes, pero sus topologías lógicas pueden ser idénticas.

Al mapear gráficamente estos enlaces, obtenemos algunas formas geométricas que se pueden usar para describir diferentes topologías. Cada tipo tiene ventajas y desventajas, ya que difieren en cómo los dispositivos pueden conectarse entre sí.

---

## Topología Estrella
Es el tipo de configuración más común. La red está organizada de modo que los nodos estén conectados a un dispositivo central (hub), que actúa como servidor y gestiona la transmisión de datos a través de la red. Cualquier dato enviado viaja a través del dispositivo central antes de llegar a su destino.

**Ventajas:**

- Gestión conveniente desde una ubicación central.
- Si un nodo falla, la red aún funciona.
- Los dispositivos se pueden agregar o apartar sin interrumpir la red.
- Más fácil identificar y aislar problemas de rendimiento.

**Desventajas:**

- Si el dispositivo central falla, toda la red dejará de funcionar.
- El rendimiento y el ancho de banda están limitados por el nodo central.
- Puede ser costoso de operar.

<div align="center">
  <img src="https://github.com/user-attachments/assets/684c7ba5-d5f7-48ab-9464-867c6e37e88b" width="350" height="339">
</div>

---

## Topología en Bus
También llamada topología troncal o línea, guía los dispositivos a lo largo de un solo cable que se extiende desde un extremo de la red hasta el otro. Los datos fluyen a lo largo del cable hasta su destino.

**Ventajas:**

- Económica para redes pequeñas.
- Diseño simple; todos los dispositivos conectados a través de un cable.
- Se pueden agregar más nodos alargando la línea.

**Desventajas:**

- La red es vulnerable a fallas de cables.
- Cada nodo agregado disminuye la velocidad de transmisión.
- Los datos solo se pueden enviar en una dirección a la vez.

<div align="center">
  <img src="https://github.com/user-attachments/assets/e2d6bcd4-da7a-4e9a-a95b-f7f97020e090" width="350" height="339">
</div>

---

## Topología en Anillo
Los nodos se configuran en un patrón circular. Los datos viajan a través de cada dispositivo a medida que circulan por el anillo. En redes grandes, pueden ser necesarios repetidores para evitar la pérdida de paquetes durante la transmisión. Se pueden configurar como anillo único (half-dúplex) o anillo doble (full-dúplex) para permitir tráfico en ambas direcciones simultáneamente.

**Ventajas:**

- Costo-beneficio adecuado.
- Barato de instalar.
- Problemas de rendimiento fáciles de identificar.

**Desventajas:**

- Si un nodo falla, puede afectar varios nodos.
- Todos los dispositivos comparten ancho de banda, limitando el rendimiento.
- Agregar o eliminar nodos requiere tiempo de inactividad.

<div align="center">
  <img src="https://github.com/user-attachments/assets/610980a8-f27f-446c-8105-99b620482bf7" width="350" height="325">
</div>

---

## Topología en Árbol
Un nodo central conecta hubs secundarios, que a su vez pueden conectar otros nodos en una relación de padre-hijo. El nodo central funciona como el tronco del árbol y las ramas son los concentradores secundarios, conectando los dispositivos finales.

**Ventajas:**

- Extremadamente flexible y escalable.
- Facilita la identificación de errores, ya que cada rama de la red puede diagnosticarse individualmente.

**Desventajas:**

- Si falla un hub central, los nodos conectados a él se desconectarán (aunque otras ramas pueden seguir funcionando de forma independiente).
- La estructura puede ser difícil de gestionar de forma eficaz.
- Utiliza más cableado que otros métodos.

<div align="center">
  <img src="https://github.com/user-attachments/assets/000b430a-01a5-4fc4-ae4d-2f709511353a" width="350" height="350">
</div>

---

## Topología de Malla
Los nodos están interconectados. En full-mesh, todos los dispositivos se conectan directamente; en malla parcial, la mayoría se conecta directamente. Esto proporciona múltiples rutas para la entrega de datos.

**Ventajas:**

- Confiable y estable.
- Ningún fallo de un solo nodo desconecta la red.

**Desventajas:**

- Complejidad alta de interconexión entre nodos.
- Mano de obra intensiva para instalar.
- Requiere mucho cableado para conectar todos los dispositivos.

<div align="center">
  <img src="https://github.com/user-attachments/assets/e5572e1f-cbdc-4b3b-aa29-33f7ee527e8c" width="350" height="322">
</div>

---

## Topología Híbrida
Utiliza varias estructuras de topología. Es común en organizaciones grandes donde cada departamento puede tener un tipo de topología diferente, con hubs departamentales conectados a un hub central.

**Ventajas:**

- Flexible y adaptable a diferentes necesidades.
- Permite personalización según la estructura de la organización.

**Desventajas:**

- La complejidad aumenta.
- Se requiere experiencia en múltiples topologías.
- Puede ser más difícil determinar problemas de rendimiento.






