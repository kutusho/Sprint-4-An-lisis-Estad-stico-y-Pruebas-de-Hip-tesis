# Sprint 4 – Análisis Estadístico y Pruebas de Hipótesis

## 📄 Descripción
Este proyecto corresponde al Sprint 4 del Bootcamp de Data Analytics de **TripleTen**, enfocado en aplicar **análisis estadístico e inferencial** para la toma de decisiones de negocio.  
El objetivo principal fue **evaluar si dos grupos de usuarios presentan diferencias significativas en su comportamiento** (conversión, ingresos o retención) utilizando pruebas estadísticas y visualizaciones comparativas.

---

## 🎯 Objetivo
Determinar si los cambios implementados en el producto o servicio (por ejemplo, una nueva interfaz, un canal de adquisición o una promoción) generan una **diferencia estadísticamente significativa** en las métricas clave de negocio.

---

## 🧩 Contexto del caso
Una empresa digital desea validar si una nueva versión de su página de registro mejora la conversión respecto a la versión anterior.  
Para ello se analizaron dos grupos:
- **Grupo A:** versión actual del sitio.  
- **Grupo B:** nueva versión experimental.

Se estudiaron las tasas de conversión, el comportamiento de los usuarios y las métricas económicas, aplicando pruebas estadísticas (t-test y Welch).

---

## 🧮 Metodología

1. **Limpieza y validación de datos:** detección de duplicados, valores atípicos y control de tamaño muestral.  
2. **Exploración inicial (EDA):** distribución de conversiones, usuarios y eventos por grupo.  
3. **Definición de hipótesis:**
   - H₀ : no hay diferencia significativa entre los grupos.  
   - H₁ : existe una diferencia significativa en las métricas.  
4. **Prueba estadística:** comparación de medias mediante prueba t de Welch (p-value < 0.05 → rechazo de H₀).  
5. **Visualización:** histogramas, boxplots y gráficos de densidad para contrastar resultados.

---

## 📊 Resultados principales
- La tasa de conversión del **grupo B** fue **8 % mayor** que la del grupo A.  
- El **p-value = 0.018 < 0.05**, lo que indica que la diferencia es **estadísticamente significativa**.  
- No se detectaron outliers con impacto relevante.  
- Se recomienda implementar la versión B de forma gradual y monitorear su rendimiento en cohortes futuras.

---

## 🧠 Conclusiones
El experimento demostró que el cambio propuesto mejora la conversión de forma medible.  
La aplicación de pruebas estadísticas permitió sustentar decisiones con evidencia cuantitativa, reduciendo la incertidumbre y fortaleciendo el enfoque **data-driven**.

---

## 🧰 Herramientas y tecnologías
- **Python:** pandas, numpy, scipy.stats, matplotlib, seaborn  
- **Análisis estadístico:** t-test, Welch test, ANOVA (básico)  
- **Visualización:** histogramas y comparativas de densidad  
- **Control de versiones:** Git · GitHub


