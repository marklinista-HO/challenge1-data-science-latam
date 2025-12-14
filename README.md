
<h1>Reto "Alura Store"</h1>
El juego del Amigo Secreto consiste en que de una lista de nombres de amigos, el sistema haga un sorteo aleatorio y dé un nombre de la lista.  Este nombre será el  "Amigo Secreto".

<h2> Como se juega</h2>


<h2> ********************</h2>


# **¡Bienvenidos al primer desafío!**

Durante este desafío, ayudarás al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. Para ello, analizarás datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store. El objetivo es identificar la tienda menos eficiente y presentar una recomendación final basada en los datos.

## Lo que practicarás:

- Cargue y manipule datos CSV con la biblioteca Pandas.
- Cree visualizaciones de datos con la biblioteca Matplotlib.
- Analice métricas como ingresos, reseñas y rendimiento de ventas.

## Requisitos:

- **Analizar datos de la tienda:**
  - Debes evaluar información como los ingresos, las categorías más vendidas, las reseñas de los clientes, los productos más vendidos y el envío promedio.

‌

- **Crear gráficos para visualización:**
  - Decide qué tipos de gráficos utilizar para presentar los resultados de forma clara y visual.
  - Mínimo de 3 gráficos diferentes, que pueden incluir gráficos de barras, circulares, de dispersión y otros.

‌

- Enviar una recomendación:
  - Después del análisis, escriba un texto explicando a qué tienda debería vender el Sr. João y por qué, basándose en los datos presentados.

¡Éxito en tu proyecto!



<h2> **********************</h2>

Con base en los análisis realizados y los gráficos generados, es momento de sintetizar sus hallazgos en un **informe final**. Dentro de tu Colab, deberás redactar un texto explicando a qué tienda debe vender el Sr. Juan, teniendo en cuenta todos los factores analizados, como:

- Los **ingresos totales** de las tiendas.
- Las **categorías de productos** más y menos vendidas.
- Las **calificaciones promedio** de los clientes por tienda.
- Los **productos más y menos vendidos**.
- El **coste de envío promedio** para cada tienda.

En su informe, incluya la justificación de su decisión, respaldada por el análisis y las visualizaciones que generó. Explicar, de forma clara y objetiva, las razones por las que una tienda destaca (o no) en relación a las demás, considerando las fortalezas y debilidades de cada una.

Su informe debe estar bien estructurado, con una introducción que explique el propósito del análisis, un desarrollo con la presentación de datos y gráficos, y una conclusión recomendando la tienda que se debe vender y justificando la elección.


<h2> **********************</h2>

<h2>Conjunto de Datos</h2>

Antes de pasar a análisis detallados, es esencial explorar el conjunto de datos para comprender su estructura y contenido. Este paso le permite identificar patrones, inconsistencias y las columnas más relevantes para los siguientes pasos.

**Estructura de datos:**
El conjunto de datos incluye la siguiente información:

- **Producto y Categoría**: Artículos vendidos y sus calificaciones.
- **Precio y Envío**: Valores de venta y costos asociados.
- **Fecha y ubicación de compra**: Información temporal y geográfica.
- **Evaluación de compra**: Comentarios de clientes.
- **Tipo de Pago y Cuotas**: Métodos utilizados por los clientes.
- **Coordenadas Geográficas**: Ubicación de las transacciones.

💡¡Explorar y comprender bien estos datos es el primer paso hacia un análisis eficiente!


<h2> **********************</h2>


























En la pantalla habrá una casilla donde podrá ingresar nombres de amigos, los cuales se desplegaran en un listado.  Para ingresar un nombre, sólo debe escribirlo y oprimir el botón  ```[Adicionar]```.

<img width="659" height="144" alt="image" src="https://github.com/user-attachments/assets/fca0fb57-6548-4530-ba88-c88f6641879f" />

Puesto que más de un amigo puede tener el mismo nombre, el sistema le dejará ingresar nombres repetidos.  

Si no ingresa un nombre y oprime el botón de ```[Adicionar]```, el sistema le dará un mensaje indicándole que 'inserte' un nombre.
<img width="452" height="150" alt="image" src="https://github.com/user-attachments/assets/d7073578-d76c-46fe-af97-098dd0b16db6" />

Al terminar de ingresar nombres debe oprimir el botón de ```[Sortear Amigo]``` para que el sistema escoja un nombre de la lista.  Este nombre será el "Amigo Secreto".

<img width="402" height="89" alt="image" src="https://github.com/user-attachments/assets/0babf6d6-9738-4a16-b7d5-af6a8f931fe3" />

Si oprime el botón de ```[Sortear Amigo]``` y no ha añadido un nombre a la lista, el sistema le dará un mensaje indicando que no ha ingresado ningún nombre.
<img width="453" height="154" alt="image" src="https://github.com/user-attachments/assets/90dcb3d9-e6ed-46c2-8fca-b9b18811be92" />

Una vez se despliegue el amigo secreto, el sistema ya no le dejará ingresar otro nombre, pues el botón ```[Adicionar]``` será desabilitado,
<img width="632" height="81" alt="image" src="https://github.com/user-attachments/assets/cfb23e0b-0b02-47ba-b8cd-6348ced4e582" />

pero sí podrá oprimir el botón de ```[Sortear Amigo]``` para que le genere otro amigo secreto de la lista si lo desea.


<h2> Volver a jugar</h2>

Para reiniciar el juego, sólo vuelva a cargar la página, u oprima la tecla ```[F5]```.
