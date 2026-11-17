# Deadlock News - Periódico Digital

* **Temática:** Periódico digital especializado en el videojuego de Valve *Deadlock*.
* **Autor:** Pablo
* **Módulo:** SMR (Sistemas Microinformáticos y Redes)

---

## Preguntas Teóricas

### 1. ¿Cuál es la diferencia entre un elemento de bloque y uno en línea?
* **Elemento de bloque:** Ocupa todo el ancho disponible de su contenedor de forma predeterminada y siempre provoca un salto de línea antes y después (ejemplos: `<div>`, `<p>`, `<h1>`).
* **Elemento en línea:** Ocupa únicamente el espacio necesario para su contenido y se coloca uno al lado del otro sin generar saltos de línea (ejemplos: `<span>`, `<a>`, `<strong>`).

### 2. ¿Qué diferencia existe entre class e id?
* **`id`:** Es un identificador único. Solo se puede utilizar una vez por página HTML en un único elemento y se selecciona en CSS utilizando el símbolo `#`.
* **`class`:** Es una clase reutilizable que se puede aplicar a tantos elementos diferentes como se quiera dentro del documento y se selecciona en CSS utilizando el símbolo `.`.

### 3. ¿Qué diferencia hay entre margin y padding?
* **`padding` (Relleno):** Es el espacio interior situado entre el contenido de la caja y su propio borde. El color de fondo del elemento se extiende por esta zona.
* **`margin` (Margen):** Es el espacio exterior que rodea a la caja, sirviendo para separarla de otros elementos circundantes en la página.

### 4. ¿Para qué sirve box-sizing: border-box?
La propiedad `box-sizing: border-box` cambia la forma en que los navegadores calculan el ancho y alto total de los elementos. Hace que el relleno (`padding`) y el borde (`border`) se incluyan dentro de las dimensiones totales especificadas en el ancho, evitando que las cajas crezcan de manera inesperada o des cuadren el diseño de la página.