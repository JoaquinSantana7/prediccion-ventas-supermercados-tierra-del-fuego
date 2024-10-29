# Predicción de Ventas en Supermercados en Tierra del Fuego

## Descripción del Dataset

El dataset utilizado en este proyecto se centra en las ventas de supermercados en Tierra del Fuego, considerando variables como las condiciones meteorológicas y el flujo de turistas. Esto permitirá desarrollar un modelo de aprendizaje automático para predecir las ventas.

### Origen del Dataset
- **Fuente**: [https://ipiec.tierradelfuego.gob.ar/]
- **Fecha de adquisición**: [07/10/2024]
- **Proceso de recopilación**: [Tras una larga jornada de exploracion sobre los datos disponibles y los proyectos de compañeros, elegi el dataset siendo este relevante para mi y adaptandose a mi idea de proyecto. Descargando estos en mi equipo de trabajo para su posterior procesamiento]

### Descripción Completa del Dataset Comercio interior Supermercados Tierra del Fuego

- **Cantidad de Instancias**: [341]
- **Características**:
  - `período`: Mes y año de las ventas (tipo: string)
  - `total`: Total de ventas en miles de pesos (tipo: float)
  - `bebidas`: Ventas de bebidas en miles de pesos (tipo: float)
  - `almacen`: Ventas de productos de almacén en miles de pesos (tipo: float)
  - `panaderia`: Ventas de panadería en miles de pesos (tipo: float)
  - `lacteos`: Ventas de lácteos en miles de pesos (tipo: float)
  - `carnes`: Ventas de carnes en miles de pesos (tipo: float)
  - `verduleria_fruteria`: Ventas de frutas y verduras en miles de pesos (tipo: float)
  - `alimentos_preparados_rotiseria`: Ventas de alimentos preparados y productos de rotisería en miles de pesos (tipo: float)
  - `articulos_limpieza_perfumeria`: Ventas de artículos de limpieza y productos de perfumería en miles de pesos (tipo: float)
  - `indumentaria_calzado_textiles`: Ventas de indumentaria y calzado en miles de pesos (tipo: float)
  - `electronicos_articulos_hogar`: Ventas de electrónicos y artículos para el hogar en miles de pesos (tipo: float)
  - `otros`: Ventas de otros productos no categorizados en miles de pesos (tipo: float)

# Descripción Completa del Dataset Meteorologico Tierra del Fuego

- **Cantidad de Instancias**: [178]
- **Características**:
  - `periodo`: Mes y año de las mediciones (tipo: string)
  - `temperaturas_rio_grande_maxima`: Temperatura máxima media en Río Grande (tipo: float)
  - `temperaturas_rio_grande_minima`: Temperatura mínima media en Río Grande (tipo: float)
  - `temperaturas_rio_grande_media`: Temperatura media en Río Grande (tipo: float)
  - `precipitacion_rio_grande_lluvia`: Lluvia caída en Río Grande (tipo: float)
  - `precipitacion_rio_grande_dias_nieve`: Días con nieve en Río Grande (tipo: int)
  - `temperaturas_ushuaia_maxima`: Temperatura máxima media en Ushuaia (tipo: float)
  - `temperaturas_ushuaia_minima`: Temperatura mínima media en Ushuaia (tipo: float)
  - `temperaturas_ushuaia_media`: Temperatura media en Ushuaia (tipo: float)
  - `precipitacion_ushuaia_lluvia`: Lluvia caída en Ushuaia (tipo: float)
  - `precipitacion_ushuaia_dias_nieve`: Días con nieve en Ushuaia (tipo: int)

# Descripción Completa del Dataset de Turismo Tierra del Fuego

- **Cantidad de Instancias**: [171] 
- **Características**:
  - `periodo`: Mes y año de las mediciones (tipo: string)
  - `pernoctaciones_ushuaia_total`: Total de pernoctaciones en Ushuaia (tipo: int)
  - `pernoctaciones_ushuaia_residentes`: Pernoctaciones de residentes en Ushuaia (tipo: int)
  - `pernoctaciones_ushuaia_no_residentes`: Pernoctaciones de no residentes en Ushuaia (tipo: int)
  - `viajeros_ushuaia_total`: Total de viajeros en Ushuaia (tipo: int)
  - `viajeros_ushuaia_residentes`: Viajeros residentes en Ushuaia (tipo: int)
  - `viajeros_ushuaia_no_residentes`: Viajeros no residentes en Ushuaia (tipo: int)
  - `estadias_promedio_ushuaia_total`: Estadía promedio en días en Ushuaia (tipo: float)
  - `pernoctaciones_rio_grande_total`: Total de pernoctaciones en Río Grande (tipo: int)
  - `pernoctaciones_rio_grande_residentes`: Pernoctaciones de residentes en Río Grande (tipo: int)
  - `pernoctaciones_rio_grande_no_residentes`: Pernoctaciones de no residentes en Río Grande (tipo: int)
  - `viajeros_rio_grande_total`: Total de viajeros en Río Grande (tipo: int)
  - `viajeros_rio_grande_residentes`: Viajeros residentes en Río Grande (tipo: int)
  - `viajeros_rio_grande_no_residentes`: Viajeros no residentes en Río Grande (tipo: int)
  - `estadias_promedio_rio_grande_total`: Estadía promedio en días en Río Grande (tipo: float)
    
### Información Relevante sobre los Datasets

#### 1. Contexto Temporal
- **Variabilidad Anual**: Analizar la variabilidad en los datos de ventas y turismo entre diferentes años para entender cómo factores externos afectan las tendencias.
- **Estacionalidad**: Identificar patrones estacionales en las ventas y el turismo, correlacionándolos con las condiciones climáticas durante los períodos de alta y baja demanda.

#### 2. Impacto de Eventos Especiales
- **Eventos Locales**: Considerar la influencia de eventos o festivales locales que podrían haber alterado las cifras de turismo y ventas.
- **Crisis o Situaciones Inusuales**: Evaluar cómo situaciones extraordinarias, como pandemias o desastres naturales, afectan el flujo de turistas y las ventas en supermercados.

#### 3. Relación entre Variables
- **Análisis de Correlación**: Realizar análisis de correlación entre las variables climáticas (temperaturas y precipitaciones) y las ventas, para determinar qué condiciones afectan más las compras.
- **Influencia del Turismo en Ventas**: Examinar cómo el número de turistas impacta en las ventas de diferentes categorías de productos, guiando así decisiones de inventario.

