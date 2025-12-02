<div align="center">

# 📊 Priorizar Hipótesis y Análisis de Test A/B

### Toma de decisiones basada en datos usando ICE, RICE y pruebas estadísticas

<img src="https://img.shields.io/badge/Proyecto-A%2FB%20Testing-green" />
<img src="https://img.shields.io/badge/Python-Data%20Analysis-blue" />
<img src="https://img.shields.io/badge/Frameworks-ICE%20%7C%20RICE-orange" />
<img src="https://img.shields.io/badge/Estado-Completado-brightgreen" />

---

### 👤 Autor  
**Yessid Diaz Gutierrez**

---

📈 Convierte datos en decisiones  
🧠 Prioriza con lógica  
✅ Valida con estadística

---

</div>

---

## 🧩 Parte 1. Priorización de Hipótesis con ICE y RICE

### 🎯 Objetivo
Priorizar ideas de negocio para invertir recursos en las hipótesis con mayor impacto potencial, utilizando los frameworks:

- ✅ ICE  
- ✅ RICE  

## 🔹 Framework ICE

**Fórmula:**

> ICE = (Impacto × Confianza) / Esfuerzo

Este modelo mide:
- 📈 Impacto esperado
- ✅ Nivel de confianza
- ⚙️ Esfuerzo requerido

### ✅ Ranking de hipótesis según ICE

| Prioridad | Hipótesis | ICE |
|-----------|-----------|-----|
| 1 | Promoción con descuentos | 16.2 |
| 2 | Nuevos canales de tráfico | 13.33 |
| 3 | Formulario de suscripción | 11.2 |
| 4 | Banners promocionales | 8.0 |
| 5 | Recomendaciones de productos | 7.0 |
| ... | | |
| Última | Cambio de color de fondo | 1.0 |

## 🔹 Framework RICE

**Fórmula:**

> RICE = (Reach × Impact × Confianza) / Esfuerzo

Este agrega el factor:
- 👥 Alcance de usuarios (*Reach*)

### ✅ Ranking de hipótesis según RICE

| Prioridad | Hipótesis | RICE |
|-----------|-----------|------|
| 1 | Formulario de suscripción | 112 |
| 2 | Recomendación de productos | 56 |
| 3 | Nuevos canales | 40 |
| 4 | Banners | 40 |
| 5 | Promoción | 16.2 |
| ... | | |
| Última | Cambio de color | 3 |

## 🔍 Comparación ICE vs RICE

### 📌 Resultados clave

- ICE favorece iniciativas con alto impacto y bajo esfuerzo.
- RICE prioriza ideas que afectan más usuarios.
- Algunas hipótesis suben o bajan en prioridad cuando se considera el alcance.

### 🧠 Conclusión
RICE es más adecuado cuando:
- Se impactan grandes volúmenes de usuarios.
- El negocio escala.
- Se busca retorno global.

## 🧪 Parte 2. Análisis del Test A/B

## 💰 Ingresos acumulados

### Conclusiones:
- Si B está sobre A → mejor rendimiento.
- Si las líneas se cruzan → no hay ganador claro.
- Picos extremos → posibles **outliers**

## 🛒 Tamaño promedio de pedido acumulado

### Conclusiones:
- Grupo B ligeramente superior
- No hay diferencia sostenida
- Curvas inestables → cuidado con usuarios atípicos

## 📉 Diferencia relativa del tamaño de pedido

### Interpretación:
- Línea > 0 → B mejor que A
- Cruces constantes → resultados inconclusos
- Valores extremos → distorsión

## 📈 Tasa de conversión diaria

### Conclusiones:
- B muestra mayor conversión varios días
- Diferencias pequeñas
- Muestra aún inestable

## 👥 Pedidos por usuario

### Resultados:
- La mayoría tiene un solo pedido
- Algunos usuarios con muchos pedidos distorsionan métricas
- Se recomienda filtrar outliers

## 🚨 Detección de Outliers

### Pedidos por usuario
- Percentil 95 → 2 pedidos  
- Percentil 99 → 4 pedidos  

✅ Usuarios con más de 4 pedidos se consideran anómalos

### Precio de pedidos
- Percentil 95 → 435.54  
- Percentil 99 → 900.90  

✅ Pedidos por encima son outliers

## 📐 Pruebas estadísticas

## 🧪 Conversión (Datos sin filtrar)

- A: 0.0268  
- B: 0.0310  
- ✅ p-value = 0.0167 (significativo)

## 🧪 Tamaño de pedido (Datos sin filtrar)

- A = 115.90  
- B = 145.06  
- ❌ p-value = 0.6915 (no significativo)

## ✅ Conversión (Datos filtrados)

- A = 0.0263  
- B = 0.0305  
- ✅ p-value = 0.0157 (sigue siendo significativo)

## ❌ Tamaño de pedido (Datos filtrados)

- A = 102.95  
- B = 101.37  
- ❌ p-value = 0.9332

## 🧠 Interpretación Final

- Conversión: pequeñas diferencias, no sólidas.
- Ticket promedio: diferencia desaparece sin outliers.
- Gráficos muestran variabilidad extrema.
- Datos crudos eran engañosos.

## 🎯 Decisión Final

✅ **Continuar la prueba**

### Motivos:
- Muestra insuficiente.
- Resultados inestables.
- Alto impacto de outliers.
- No hay ganador claro aún.

## ✅ Recomendaciones

- Extender el test A/B
- Monitorear métricas filtradas
- Segmentar usuarios
- Control continuo de outliers
- Evaluar impacto por cohortes

## 🛠️ Herramientas utilizadas

- 🐍 Python  
- 🧮 Pandas  
- 📊 Matplotlib  
- 📐 NumPy  
- 🔬 SciPy  
- 🧪 Estadística inferencial

## 🏁 Conclusión General

Este proyecto demuestra cómo:

✅ Priorizar estratégicamente  
✅ Evitar decisiones erróneas  
✅ Controlar sesgos  
✅ Validar hipótesis reales  
✅ Pensar como analista de datos real

---
