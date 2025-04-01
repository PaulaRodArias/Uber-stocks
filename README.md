# Análisis de Acciones de Uber en Tableau

[![Tableau Version](https://img.shields.io/badge/Tableau-2021%2B-blue)](https://www.tableau.com/)
[![Licencia MIT](https://img.shields.io/badge/Licencia-MIT-blue.svg)](LICENSE)

## Descripción General
Este proyecto presenta un **dashboard en Tableau** enfocado en el análisis de las acciones de Uber (UBER) desde **mayo de 2019** hasta **febrero de 2025**. El objetivo es ofrecer una visión completa del comportamiento de la acción, identificando tendencias de precio, fluctuaciones semanales, análisis de volumen y cálculo de medias móviles.

> **Nota:** Los datos mostrados pueden incluir valores proyectados o simulados a partir de información histórica. Es importante revisar las fuentes de datos y la fecha de actualización para interpretar correctamente los resultados.

---

## Contenido del Dashboard
1. **Tendencia del Precio de Cierre**  
   - Gráfica principal que muestra la evolución del precio de cierre ajustado (Adj Close) a lo largo del tiempo.  
   - Se puede observar la tendencia general del precio, incluyendo picos y caídas significativas.

2. **Fluctuaciones Semanales**  
   - Gráfica que ilustra la variación de la acción semana a semana, permitiendo identificar rangos de precios altos y bajos.  
   - Útil para medir la volatilidad y determinar periodos con mayor variación de la cotización.

3. **Análisis de Volumen Semanal**  
   - Muestra la cantidad de transacciones (volumen) ejecutadas cada semana.  
   - Permite correlacionar incrementos o disminuciones de volumen con movimientos relevantes en el precio.

4. **Cálculo de Media Móvil**  
   - Representa la media móvil (moving average) para atenuar fluctuaciones y visualizar tendencias de mediano plazo.  
   - Incluye un %DiffRef que mide el cambio porcentual con respecto a la referencia establecida.

---

## Objetivos del Proyecto
- **Visualizar Tendencias:** Conocer la evolución histórica de las acciones de Uber.
- **Identificar Patrones:** Localizar picos de volatilidad y relaciones entre volumen y variaciones de precio.
- **Soportar Decisiones:** Proveer información clave para inversores, analistas y curiosos del mercado bursátil.

---

## Herramientas y Tecnologías
- **[Tableau](https://www.tableau.com/):** Software de Business Intelligence utilizado para la creación de dashboards interactivos.
- **Fuentes de Datos:**  
  - Datos históricos de acciones de Uber (UBER) provenientes de sitios financieros o APIs (Yahoo Finance, por ejemplo).
  - Fechas y valores proyectados para extender el análisis a futuro (opcional o simulado).

---

## Uso e Interacción
1. **Explorar la Tendencia:**  
   - Pasa el cursor por la gráfica de precio de cierre para ver valores específicos en cada fecha.
2. **Filtrar Períodos:**  
   - Ajusta los filtros de fecha para centrarte en intervalos concretos (por ejemplo, 2020-2022).
3. **Examinar la Volatilidad Semanal:**  
   - Observa los rangos de máximos y mínimos en la sección de “Fluctuaciones semanales”.
4. **Analizar Volumen:**  
   - Cruza la información del volumen con los movimientos del precio para detectar patrones de compra/venta.
5. **Interpretar la Media Móvil:**  
   - Evalúa la tendencia general a mediano plazo, comparando la línea de la media móvil con el precio real.

---

## Consideraciones y Limitaciones
- La información mostrada es meramente ilustrativa y no constituye asesoramiento financiero.  
- Los datos históricos y las proyecciones futuras pueden estar sujetas a revisiones y correcciones.  
- El rendimiento pasado de una acción no garantiza rendimientos futuros.

---

## Instalación y Visualización
1. **Clonar el Repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/analisis-acciones-uber.git
