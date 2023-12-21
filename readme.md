# Conceptos para un correcto Análisis de datos

# Métrica:
Es una medición de datos única, específica y cruda.

# Indicadores 
Son valores que miden el logro de objetivos, genealmente en indices y porcentajes.

# KPIs
Indicadores orientados al éxito de la estrategia. Es un valor medible que demuestra la eficacia con la que una empresa esta logrando los objetivos claves.

Se requiere métricas para generar indicadores y algunos de esos indicadores que son claves se convierten en KPIs

# KPIs Significativo
Evalua lo que otros hacen bien. Es importante conocer si está entregando valor. Medir todo aquello que los clientes me piden que mida. Ejemplo:
- Si los clientes plantean qu elos productos tienen un defecto de calidad. Hay que medir el proceso de calidad

- Si los clientes plantean que le llega la información de su área muy tarde. Hay que la puntualidad en la entrega de la información.

# Precaución
- Hay que tener preocupación que si lo que estamos midiendo es lo que mas le interesa a la empresa. 

- Tratar que este soportado por las personas que van a estar afectados.

# KPIs claro pero no simple. Eficiencia general de la operación es la sumatoria de varios KPIs 
- Ej: Eficica general de la operación = Cuanto Tiempo estuvo trabajando + Eficiencia (cuanto a lo que debe hacer) + Calidad (cuanto de productos de calidad)

# Tener en cuenta que hay que evitar :
- No tener un vínculo claro entre la medición y la estrategía. Si esto ocurre no tenemos exito.
  
- Evitar tener KPIs irrelevantes que no se utilizan porque nadie los ve como relevante. Estos serían Indicadores pero no KPIs (Reportes innecesarios)
  
- Evitar tener ni idea de cómo medir sus objetivos. Lo que vamos a medir, cuales son los datos que lo definen, tener identificadas todas las condiciones que se deben de cumplir.
  
# Metodología de Árbol de KPIs
  - Estudiar y repasar
  
# Base de datos para crear tus KPIs
# Tabla de presentación: 
- Se utiliza para transmitir información de manera mas ágil posible para garantizar lecturas rápidas.

# Tabla de análisis: 
- Cada una de sus columnas representan una variable con un formato y debe tener un nombre. 

- Una fila va a representar un evento distribuido en varias variables. 

- Evitar columnas y filas vacías. 

- Mantener un solo valor por celdas es decir en una relación de uno a muchos repetir las filas de muchos.  

- Comsistencia en los textos, es decir mantener el formato por filas.

- Que sean fáciles de actualizar. Es decir en un ETL mantener el origen y trabajar lo obtenido con agrego de columnas de medidas, etc.

- Soft de hoy en día. MS Power Pivot, Power Query, Power BI.

# Tips para el análisis
- Lograr obtener un volumen histórico.

- Para buscar tendencias lo ideal es marcar un período mínimo de cinco años.

- Tener datos segmentados, es decir clasificados.

- Establecer cruces de información a partir de variables de enlaces verídicas.

- Fuente de datos fiables. 

# Formas de visualizar los KPIs (Es lo que hace que las personas esten mas interesadoas en ver el reporte)

- En tablas. No es la mejor manera.

- En gráficas. Lo mas recomendable.

- En textos. Algo visual que capte la atención del cliente. Los totales, cuanto hemos vendidos, cual ha sido el mayor precio. cantidad de dias en venta, etc.

- En porcentajes. Represnetado en circular, barras apiladas, anillos, punto deslizantes, línea de íconos, áreas proporcionadas, cuadrícula.

- En velocímetros.

- Gráfica de Bullets. Gráfica de barras donde cada barra representa un KPIs que se cruza con una línea que marca un objetivo o una meta pronóstico que se quiere cumplir. 
  es la mejor forma de mostrar resultados comparados con objetivos. 
  
- Marcas de estado.

- Arcos angulares.

- Círculos progresivos.

# Selección del tipo de gráfico.

# Comparación

  #Estáticos
  
  - barras
  
  - columnas
  
  - radar
  
  #Tiempo
  
  - + de una columna
  
  - línea
  
  - área

# Correlación

  # dos variables
  
   - dispersión 
  
  # tres variables
  
   - burbujas

# Fraccionar

  # Estáticos
   
    - círculo
	
	- anillos

  # Tiempo

   - columnas apiladas  

   - áreas apiladas   
   
# Automatizar alertas con KPIs
Excel lo tiene en formato condicional. Investigar si Power BI lo tiene y como se implementa.
Criterios más comunes para alertas KPIs

- Comparativas con períodos anteriores donde calculamos si esta por debajo o por encima y en que %.

- Marcadores de valor único.

- % de desviación del objetivo.

- Intervalos (Semáforos)

- Método de los 4 umbrales 

- No dejes de visualizar

# Dashboard
Son una representación visual de la información más importante que se necesita para lograr uno o más objetivos y que ha sido consolidada en una sola pantalla para que sea monitoreada en un vistazo.

Permite a los usuarios:

- Evaluar que tan bien la organización está logrando sus objetivos.

- Identificar causas de bajo de desempeño.

- Identificar formas de mejorar el desempeño en el futuro.

Ayudarte a responder:

- ¿Estamos logrando nuestras metas?

- ¿Vamos mejor o peor que antes?

- ¿Cómo podemos mejorar en el futuro?
	
 
# Modelo semantico en Power BI
Un modelo semántico en Power BI es un marco lógico que proporciona una vista simplificada y fácil de entender de los datos dentro de la plataforma. 
Actúa como una capa intermedia entre las fuentes de datos sin procesar y las visualizaciones, lo que permite a los usuarios trabajar con los datos utilizando términos y relaciones familiares 12.
En Power BI, un modelo semántico se crea definiendo relaciones entre tablas y creando jerarquías y medidas. En comparación con otros métodos de modelado de datos, 
un modelo semántico proporciona una vista simplificada de los datos, lo que facilita el acceso y el análisis de los datos por parte del usuario final.

El proceso de creación de un modelo semántico complicado en Power BI es sencillo. Si los datos proceden de más de un sistema transaccional, antes de saberlo, 
puede tener docenas de tablas con las que tendrá que trabajar. La creación de un buen modelo semántico consiste en simplificar el desorden. 
En este módulo, obtendrá información sobre la terminología y la implementación de un esquema de estrella, que es una manera de simplificar un modelo semántico. 
También obtendrá información sobre por qué es importante elegir la granularidad de datos correcta para el rendimiento y la facilidad de uso de los informes de Power BI. 
Por último, aprenderá a mejorar el rendimiento con los modelos semánticos de Power BI.

Debemos saber como:

- Crear tablas de fechas comunes

- Configurar relaciones de varios a varios

- Resolver relaciones circulares

- Diseñar esquemas de estrella

La creación de un modelo semántico excelente es una de las tareas más importantes que un analista de datos puede realizar en Microsoft Power BI. 
Al hacer este trabajo de forma correcta, ayudará a los usuarios a comprender mejor los datos, lo que facilitará la creación de informes de Power BI útiles para ellos y para usted.

- Un buen modelo semántico ofrece las ventajas siguientes:

- La exploración de datos es más rápida.

- Las agregaciones son más fáciles de crear.

- Los informes son más precisos.

- La creación de informes tarda menos tiempo.

- Los informes son más fáciles de mantener en el futuro.

En resumen, al diseñar los modelos semánticos, el objetivo debe ser la simplicidad.

Power BI permite crear relaciones a partir de tablas con orígenes de datos diferentes, una función eficaz que permite extraer una tabla de Microsoft Excel y otra de una base de datos relacional. 
Después, tendrá que crear la relación entre esas dos tablas y las tratará como un modelo semántico unificado.

# Esquemas de estrella

Puede diseñar un esquema de estrella para simplificar los datos. No es la única manera de simplificarlos, pero es un método popular; por tanto, 
todos los analista de datos de Power BI deben comprenderlo.

Las tablas de hechos contienen valores de datos de eventos o de observación: pedidos de ventas, recuentos de productos, precios, fechas y horas de transacciones, y cantidades. 
Las tablas de hechos pueden contener varios valores repetidos. Por ejemplo, un producto puede aparecer varias veces en varias filas para diferentes clientes en fechas distintas. 
Estos valores se pueden sumar para crear objetos visuales. Por ejemplo, un objeto visual del total de pedidos de ventas es una suma de todos los pedidos de ventas en la tabla de hechos. 
Con las tablas de hechos, es habitual ver columnas rellenadas con números y fechas. Los números pueden ser unidades de medida, como el importe de venta, o pueden ser claves, 
como un identificador de cliente. Las fechas representan el tiempo que se registra, como la fecha del pedido o la del envío.

Las tablas de dimensiones contienen los detalles sobre los datos de las tablas de hechos: productos, ubicaciones, empleados y tipos de pedido. 
Estas tablas están conectadas a la tabla de hechos a través de columnas de clave. Las tablas de dimensiones se usan para filtrar y agrupar los datos de las tablas de hechos. 
Las tablas de hechos, por otro lado, contienen los datos medibles, como ventas e ingresos, y cada fila representa una combinación única de valores de las tablas de dimensiones. 
En el objeto visual de pedidos de ventas totales, puede agrupar los datos para ver los pedidos de ventas totales por producto, donde el producto son datos de la tabla de dimensiones.

Las tablas de hechos son mucho más grandes que las de dimensiones, porque en ellas se producen numerosos eventos, como ventas individuales. 
Las tablas de dimensiones suelen ser más pequeñas porque está limitado al número de elementos que puede filtrar y agrupar. 
Por ejemplo, un año contiene solamente un número fijo de meses y Estados Unidos se compone de un número concreto de estados.

Un buen ejercicio para la aplicación de este esquema sería identificar dentro del modelo cual es la tabla de hecho y cuales son la de dimensiones.

Las tablas de hechos son mucho más grandes que las de dimensiones, porque en ellas se producen numerosos eventos, como ventas individuales. 
Las tablas de dimensiones suelen ser más pequeñas porque está limitado al número de elementos que puede filtrar y agrupar.

Al crear esta relación, puede diseñar el objeto visual según los requisitos, como se muestra en la ilustración siguiente. 
Si no hubiera establecido esta relación, pero sin olvidar las similitudes entre las dos tablas, habría tenido más dificultades para crear el objeto visual.

Los esquemas de estrella y el modelo semántico subyacente son la base de los informes organizados; cuanto más tiempo dedique a crear estas conexiones y el diseño, 
más fácil será crear y mantener informes.

# Configuración del modelo semántico y creación de relaciones entre tablas
Al cargar los datos en Power BI, la característica Detección automática le ayudará a establecer relaciones entre columnas con nombres similares. 
Las relaciones pueden estar inactivas o activas. Solo puede existir una relación activa entre las tablas, como se describe en un módulo futuro.

Aunque la característica Administrar relaciones permite configurar las relaciones entre las tablas, también puede configurar propiedades de tabla 
y de columna para garantizar la organización en la estructura de tablas.
	
Las tablas a traves de sus propiedades se puede modificar la estructura de cada campo de la tabla en cuantoa formato, agrupamiento, ordenamiento, si se muestra, otro nombre, 
establecer una carpeta para mostrar.

Este proceso de formato y configuración de tablas también se puede realizar en Power Query.

# Creación de una tabla de fechas
Se puede crear una tabla de fechas común de estas formas:

- Datos de origen: Las tablas de datos de origen están consolidadas y listas para su uso inmediato. Identificar los días festivos de la empresa. Separar el calendario y el año fiscal. Identificar fines de semana y días laborables

- DAX: Puede usar las funciones de expresión de análisis de datos (DAX) CALENDARAUTO() o CALENDAR() para crear la tabla de fechas común.

- Power Query: Para definir una tabla de fechas común, puede utilizar M, el lenguaje de desarrollo que se usa para generar consultas en Power Query.

Marcado de la tabla de fechas como oficial

# Uso de dimensiones
# Uso de jerarquías(relaciones) de una columna
- Elementos primarios y elementos secundarios. Ej: 1 - varios

# Dimensiones realizadoras de roles
- Es lo que se conoce como tablas intermedias que establecen relaciones con 2 o mas tablas genralmente de hechos mediantes sus columnas.

# Definición de la granularidad de los datos


