# Proyecto Final - Fundamentos de Data Science (CC216)
sección CC53

**Universidad Peruana de Ciencias Aplicadas**  
2024-2  

### Objetivo del Proyecto
El objetivo principal de este proyecto es analizar las tendencias de videos de YouTube en México, aplicando la metodología CRISP-DM para generar conocimiento accionable que permita a una empresa de marketing digital tomar decisiones estratégicas basadas en datos. El análisis incluye identificar categorías populares, evaluar la interacción (likes, dislikes, comentarios) y explorar patrones geográficos, además de construir un modelo predictivo sobre la popularidad de los videos.

### Participantes
- **Alejandra Gallo** (Business Project Sponsor)  
- **---** (Data Scientist)  
- **----** (Data Engineer)  
- **----** (Data Analyst)
- **----** (Data Analyst Assistant)
- 
### Descripción del Conjunto de Datos
El conjunto de datos utilizado para este proyecto corresponde a las estadísticas de videos en tendencia de YouTube para México.  
- **Fuente Original**: Kaggle (Trending YouTube Video Statistics)  
- **Características Adicionales**: Incluye columnas modificadas como `state` (Estado de México), `lat`, `lon`, y `geometry` para análisis geográfico.  
- **Formato**: Archivos CSV y JSON.  

Este dataset contiene información sobre los videos en tendencia durante varios meses, como vistas, likes, dislikes, comentarios, categorías, entre otros. Es crucial para entender cómo los usuarios mexicanos interactúan con los contenidos de YouTube.

### Conclusiones
1. Las categorías de entretenimiento y música tienen el mayor número de vistas y engagement en México.
2. Los videos en tendencia no siempre tienen la mejor proporción de "likes" a "dislikes", destacándose categorías específicas como deportes.
3. El volumen de videos en tendencia muestra un crecimiento constante, con picos en eventos relevantes como festividades nacionales.
4. Las predicciones basadas en las métricas actuales pueden ayudar a identificar futuros videos con alto potencial de popularidad.
5. Las diferencias geográficas en la interacción de usuarios destacan la necesidad de estrategias localizadas para campañas de marketing.

### Licencia
Este proyecto está bajo la **MIT License**, lo que permite su uso, modificación y distribución siempre que se otorgue el debido crédito a los autores originales.

### Descripción del Dataset

El conjunto de datos utilizado en este proyecto se compone de dos archivos principales relacionados con las tendencias de videos de YouTube en México:

1. **MXvideos_cc50_202101.csv**:  
   - Este archivo contiene información diaria sobre los videos en tendencia en YouTube México, incluyendo las siguientes variables:  
     - **Título y canal del video.**  
     - **Métricas de interacción** como vistas, "me gusta", "no me gusta" y comentarios.  
     - **Fecha** en la que el video estuvo en tendencia.  
     - **Categorías** asociadas a cada video.  
   - Este archivo es clave para realizar análisis temporales y métricas de engagement.

2. **MX_category_id.json**:  
   - Un archivo JSON que detalla las categorías de contenido de YouTube con sus respectivos identificadores.  
   - Ejemplos de categorías incluyen:  
     - Música.  
     - Entretenimiento.  
     - Deportes.  
     - Ciencia y tecnología.  

#### **Importancia del Dataset**  
Este conjunto de datos nos permite responder preguntas sobre tendencias de consumo de contenido en México, como:
- Identificar qué tipos de videos generan mayor engagement (vistas, likes, comentarios).  
- Analizar el comportamiento de las tendencias a lo largo del tiempo y por categorías.  
- Explorar cómo las audiencias mexicanas interactúan con diferentes géneros de contenido.  

Además, estas métricas son fundamentales para diseñar estrategias de marketing digital basadas en datos y crear modelos predictivos que anticipen futuros comportamientos en la plataforma.  

