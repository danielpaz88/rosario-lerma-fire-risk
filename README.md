# Zonificación de Amenaza de Incendios en Rosario de Lerma, Salta

Este proyecto tiene como misión generar mapas de **susceptibilidad** y **amenaza** a incendios de la cobertura vegetal en el departamento de Rosario de Lerma (Salta, Argentina). Los productos generados son herramientas operativas para bomberos y gestores de riesgo.

## 🎯 Objetivos
- Generar un mapa de susceptibilidad basado en la vegetación.
- Generar un mapa de amenaza integrando factores climáticos, topográficos y antrópicos.
- Proporcionar recomendaciones prácticas para la gestión del riesgo.

## 🛠️ Tecnologías utilizadas
- **Google Earth Engine**
- **Python**

## 📊 Resultados principales

| Factor | Categoría predominante | Área (km²) | Porcentaje |
|--------|------------------------|------------|------------|
| **Susceptibilidad** | Muy Baja | 3.382 | 59,7% |
| **Amenaza** | Muy Baja / Moderada | 2.546 / 2.053 | 44,9% / 36,2% |

[Mapa comparativo de Susceptibilidad y Amenaza de incendio](informe/img/comparativo_sus_amen_espacial_ajustado.png)

## 📂 Contenido del repositorio
- [`informe/informe.md`](informe/informe.md) – informe técnico completo.
- [`resultados/`](resultados/) – tablas CSV con áreas y estadísticas.

## 🔗 Mapas interactivos
- [Mapa de Susceptibilidad](https://danielpaz88.github.io/rosario-lerma-fire-risk/mapas/Susceptibilidad_Rosario_Lerma_interactivo.html)
- [Mapa de Amenaza](https://danielpaz88.github.io/rosario-lerma-fire-risk/mapas/Amenaza_ajustado_interactivo.html)

## 📖 Informe completo
[Leer informe técnico](informe/informe.md)

## ⚠️ Limitaciones
- Los rangos climáticos y pesos fueron adaptados para Salta; se recomienda validación de campo.
- La red vial puede tener omisiones en caminos rurales.
