# Taller-7
# TALLER 7 — CONSULTORÍA FONDO DE INVERSIÓN

**Proyecto del curso *Doing Economics*, Facultad de Economía, Universidad del Rosario.**

El equipo actúa como un equipo consultor contratado por un fondo de inversión. La consultoría busca comparar la evolución de tres sectores de la economía global entre 2015 y 2025, con especial atención a las diferencias entre el periodo previo al COVID y el periodo posterior. Para ello, se construyen índices transparentes a partir de datos de mercado, se evalúa cómo distintas reglas de ponderación cambian la lectura de los resultados, se comparan retornos y volatilidad y se presenta una interpretación de las implicaciones para el seguimiento de las inversiones. El producto final debe ser un archivo de Excel organizado, verificable y reproducible.

## Equipo consultor

* **Tannia Matallana → Líder del proyecto y enlace con el fondo**
* **Sara Vásquez → Especialista en datos y reproducibilidad**
* **Alejandro Cotrino → Analista cuantitativo**
* **Valery Lizarazo→ Especialistas en visualización y comunicación**

## Aportes de cada integrante

### Tannia Matallana

### Sara Vásquez


### Alejandro Cotrino


### Valery Lizarazo


## Organización del análisis

El análisis se organiza en tres bloques:

### 1. Construcción de los índices

En primer lugar, se seleccionan tres sectores diferentes de la economía y se construye para cada uno un universo de 10 acciones. Para estas acciones se recopilan los precios de cierre diarios y los volúmenes de transacción entre 2015 y 2025, documentando las empresas, los sectores y las fuentes de información.

Posteriormente, se construyen dos tipos de ponderaciones iniciales: una basada en el volumen de transacciones de enero de 2015 y otra basada en el precio inicial de cada acción. Se comparan ambas reglas de ponderación para analizar cómo la metodología utilizada puede modificar la lectura del índice.

### 2. Resumen y comportamiento de los datos

En segundo lugar, se describe la naturaleza de cada índice, identificando los sectores, industrias y tipos de empresas representados y señalando las principales limitaciones de utilizar únicamente 10 acciones.

Después, se calculan los retornos aritméticos diarios de cada activo y los retornos diarios ponderados de los tres índices para el periodo 2015–2025. Para analizar su comportamiento se utilizan gráficos de cajas y bigotes, histogramas y gráficos de línea de los índices normalizados con base 100 en enero de 2015. Estas herramientas permiten comparar la dispersión, los valores atípicos, la forma de las distribuciones y la evolución acumulada de los tres índices.

### 3. Comparación antes y después del COVID: 2015 vs. 2025

Finalmente, se compara el comportamiento de los tres índices entre 2015 y 2025. Para cada índice se calcula la desviación estándar y el número de observaciones de los retornos ponderados, además de intervalos de confianza del 95 % utilizando `CONFIDENCE.T`.

Los resultados se presentan mediante gráficos de barras que permiten comparar ambos años e incorporar los intervalos de confianza. A partir de estos resultados se analiza si existen cambios relevantes en los retornos o en la dispersión y qué implicaciones podrían tener para el fondo de inversión. Es importante distinguir lo que muestran directamente los datos de cualquier explicación causal atribuida al COVID.

Por último, el equipo integra la evidencia de los tres índices para formular una recomendación de inversión para el fondo, considerando el desempeño acumulado, los retornos, la dispersión, los valores extremos y las diferencias observadas entre 2015 y 2025. La recomendación debe incluir además una cautela metodológica que limite el alcance de las conclusiones.
