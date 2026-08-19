# Zonificación de Amenaza y Susceptibilidad a Incendios – Rosario de Lerma, Salta, Argentina

**Elaborado por:** Sergio Daniel Paz

**Fecha:** Agosto 2026    

**Mapas interactivos:** 

- [Mapa de Susceptibilidad](https://danielpaz88.github.io/rosario-lerma-fire-risk/mapas/Susceptibilidad_Rosario_Lerma_interactivo.html)
- [Mapa de Amenaza](https://danielpaz88.github.io/rosario-lerma-fire-risk/mapas/Amenaza_Rosario_Lerma_interactivo.html)

---

## 1. Resumen Ejecutivo

Este informe presenta la metodología y los resultados de la zonificación de la **susceptibilidad** y la **amenaza** a incendios de la cobertura vegetal para el departamento de Rosario de Lerma (Salta, Argentina). Se utilizaron imágenes satelitales de acceso libre y se procesaron en Google Earth Engine.

**Resultados principales:**
- **Susceptibilidad:** el 60% del territorio es Muy Baja, el 37% Alta y el 3% Moderada. No se detectaron áreas de susceptibilidad Baja o Muy Alta.
- **Amenaza:** hay un predominio de la categoría Muy Baja (45%), luego sigue la clase Moderada (36%) y finalmente Baja (13%). Las categorías Alta (5%) y Muy Alta (1%) se concentran en áreas periurbanas y cercanas a vías principales.

Estos mapas constituyen una herramienta operativa para la prevención, la asignación de recursos y la planificación de la respuesta ante incendios.

---

## 2. Introducción

El departamento de Rosario de Lerma, ubicado en la provincia de Salta, presenta un relieve montañoso y un clima subtropical con estación seca, lo que lo hace propenso a incendios de cobertura vegetal. La creciente expansión urbana y agropecuaria, sumada a condiciones climáticas favorables, incrementa el riesgo.

Este estudio evalúa la amenaza a partir de factores ambientales y antrópicos, generando mapas de susceptibilidad (vegetación) y amenaza (integrando clima, topografía y accesibilidad). El objetivo es proporcionar a los cuerpos de bomberos y gestores de riesgo una base técnica para la planificación territorial y la respuesta operativa.

---

## 3. Marco Conceptual

- **Incendio de la cobertura vegetal:** fuego no controlado que se propaga sobre vegetación, no previsto.
- **Susceptibilidad:** característica intrínseca de la vegetación (tipo, carga, duración y humedad del combustible) que determina su probabilidad de ignición y propagación.
- **Amenaza:** probabilidad de que ocurra un incendio en un sitio y tiempo determinado, considerando factores ambientales y antrópicos.

## 🌿 Interpretación de las Categorías de Susceptibilidad y Amenaza

Para que los mapas sean una herramienta útil para bomberos, gestores de riesgo y tomadores de decisiones, es fundamental comprender qué significa cada categoría en términos prácticos. A continuación, se detalla el significado de cada nivel de **susceptibilidad** y **amenaza**, y cómo se relacionan con el territorio de Rosario de Lerma.

---

### Susceptibilidad de la Cobertura Vegetal a Incendios

La **susceptibilidad** mide la **predisposición natural de la vegetación a incendiarse, propagar y mantener el fuego**. Depende de características intrínsecas de la vegetación: **tipo de combustible** (pastos, arbustos, árboles), **carga de biomasa** (cantidad de material combustible) y **duración** (tiempo que tarda en secarse y arder). **No considera factores externos** como el clima o la actividad humana.

En Rosario de Lerma, la vegetación varía desde pastizales de altura y suelos desnudos en la Puna, hasta bosques montanos y arbustales en las laderas de los valles.

| Categoría | Significado práctico | Ejemplos en el territorio |
|-----------|----------------------|---------------------------|
| **Muy Baja** | Vegetación con **muy poca o nula capacidad de arder**. Son áreas donde el fuego no se propaga o se extingue rápidamente. | • Suelos desnudos, rocas, nieves perpetuas.<br>• Cuerpos de agua (lagunas, ríos).<br>• Zonas urbanas consolidadas (sin vegetación). |
| **Baja** | Vegetación con **baja carga de combustible y lenta capacidad de ignición**. Si se produce un incendio, avanza lentamente y es fácil de controlar. | • Pastizales dispersos en zonas de alta montaña.<br>• Cultivos herbáceos de baja densidad.<br>• Áreas con vegetación muy esporádica. |
| **Moderada** | Vegetación con **combustible intermedio** (arbustos y herbáceas) que puede arder con cierta intensidad, pero sin alcanzar gran virulencia. | • Arbustales abiertos con pastos.<br>• Mosaicos de cultivos y pastos con espacios naturales.<br>• Bosques de galería muy fragmentados. |
| **Alta** | Vegetación con **alta carga de combustible y fácil ignición**. Los incendios tienden a propagarse rápidamente y son difíciles de controlar. | • Bosques densos de queñoa y aliso.<br>• Arbustales densos con alta biomasa.<br>• Pastizales enmalezados (con matorrales). |
| **Muy Alta** | Vegetación con **máxima carga de combustible, altamente inflamable y de rápida propagación**. Los incendios son extremadamente intensos y peligrosos. | • Bosques secos de montaña con mucho material muerto.<br>• Plantaciones forestales de coníferas (pinos, eucaliptos).<br>• Pastizales secos y continuos en zonas de transición. |

---

### Amenaza de Incendios de la Cobertura Vegetal

La **amenaza** es un concepto más amplio. Integra la **susceptibilidad de la vegetación** con **factores externos** que aumentan la probabilidad de que ocurra un incendio:

- **Clima** (baja precipitación, altas temperaturas).
- **Topografía** (pendientes pronunciadas que aceleran la propagación).
- **Accesibilidad** (cercanía a carreteras y centros poblados, que facilita la ignición por actividades humanas).
- **Frecuencia histórica** (zonas con mayor recurrencia de incendios).

La amenaza representa, por lo tanto, la **probabilidad de que se produzca un incendio en un lugar y momento determinado**, considerando tanto las condiciones ambientales como las antrópicas.

| Categoría | Significado práctico | Implicaciones para la gestión |
|-----------|----------------------|-------------------------------|
| **Muy Baja** | Zonas donde **es muy poco probable que ocurra un incendio**. Si ocurre, será de baja intensidad y fácil de controlar. | • No requieren acciones preventivas prioritarias.<br>• Monitoreo ocasional. |
| **Baja** | Zonas con **baja probabilidad de incendio**, pero donde las condiciones pueden volverse favorables en épocas secas extremas. | • Mantener vigilancia en periodos de sequía.<br>• Realizar quemas prescritas controladas (si es necesario). |
| **Moderada** | Zonas con **probabilidad intermedia de incendio**. Las condiciones climáticas y de accesibilidad pueden desencadenar eventos de cierta importancia. | • Implementar medidas preventivas (cortafuegos, educación comunitaria).<br>• Tener recursos de extinción disponibles en la zona. |
| **Alta** | Zonas con **alta probabilidad de incendio**, especialmente en épocas secas y calurosas. Los incendios tienden a ser intensos y de rápida propagación. | • Priorizar la prevención (patrullajes, restricciones de quema).<br>• Mantener brigadas de primera respuesta en la zona.<br>• Establecer cortafuegos estratégicos. |
| **Muy Alta** | Zonas con **máxima probabilidad de incendio**, donde las condiciones son extremadamente favorables para la ignición y propagación. Los incendios pueden ser catastróficos. | • **Máxima prioridad** para prevención y respuesta.<br>• Implementar sistemas de alerta temprana.<br>• Tener planes de evacuación y recursos de extinción masivos disponibles.<br>• Restringir actividades humanas en épocas críticas. |

---

### ¿Cómo se combinan Susceptibilidad y Amenaza en el mapa?

Es importante entender que **una zona con alta susceptibilidad no necesariamente tendrá alta amenaza**, y viceversa. Por ejemplo:

- **Alta susceptibilidad + Baja accesibilidad** (zonas remotas de bosque denso): la amenaza puede ser **moderada** porque, aunque la vegetación arde fácilmente, es difícil que un humano llegue a encender un fuego.
- **Baja susceptibilidad + Alta accesibilidad** (pastizales cerca de una carretera): la amenaza puede ser **alta** porque, aunque la vegetación no arde con facilidad, la presencia humana (fogatas, colillas, quema de basura) aumenta la probabilidad de ignición.

**El mapa de amenaza integra todos estos factores**, mostrando las áreas donde **la combinación de vegetación inflamable, clima seco, pendientes pronunciadas y cercanía a vías o poblados** hace que el riesgo de incendio sea mayor.

---

### ¿Qué significa que un área sea de "Amenaza Muy Alta" en Rosario de Lerma?

En el contexto de este estudio, las áreas de **Amenaza Muy Alta** (1% del territorio) corresponden a:

- **Zonas periurbanas** (alrededor de Rosario de Lerma y Campo Quijano) donde hay vegetación seca y alta densidad de vías.
- **Corredores viales principales** (RN 51 y rutas departamentales) donde la actividad humana es constante.
- **Áreas de interfaz urbano-forestal**, donde los asentamientos humanos limitan con bosques o arbustales densos.

Estas son las zonas donde **los bomberos y los gestores de riesgo deben concentrar sus esfuerzos de prevención y respuesta**, ya que un incendio en estas áreas pondría en peligro vidas humanas, infraestructura y servicios esenciales.

---

## 4. Metodología

### 4.1. Área de Estudio

El departamento de Rosario de Lerma, Salta, con una superficie aproximada de **5.141 km²**, presenta un gradiente altitudinal desde los 1.000 hasta los 5.000 msnm, con ecosistemas de pastizales, arbustales y bosques montanos.

### 4.2. Procesamiento en Google Earth Engine

El flujo de trabajo se realizó en GEE.

**Factores de amenaza (ajustados para Salta):**
   - **Precipitación**
   - **Temperatura**
   - **Pendiente** (pendiente del terreno)
   - **Accesibilidad** (distancia a carreteras)

 Resolución	Espacial del Mapa interactivo de Susceptibilidad: 150 m
 Resolución	Espacial del Mapa interactivo de Amenaza: 150 m


### 4.3. Limitaciones

- La resolución gruesa de los productos satelitales puede suavizar gradientes climáticos locales.
- La red vial de OSM (Open Street Map) puede tener omisiones en caminos rurales no mapeados.

---

## 5. Resultados

### 5.1. Estadísticas Descriptivas

| Variable | Mínimo | Máximo | Media | Desviación |
|----------|--------|--------|-------|------------|
| Susceptibilidad | 1 | 4 | 2.18 | 1.44 |
| Amenaza ajustada | 1 | 5 | 2.04 | 1.05 |

**Tabla 1.** Estadísticas de los mapas raster.

### 5.2. Distribución de Áreas por Categoría

**Susceptibilidad:**

| Nivel | Área (km²) | Porcentaje (%) |
|-------|------------|----------------|
| Muy Baja | 3.382,03 | 59,7 |
| Baja | 0,00 | 0,0 |
| Moderada | 169,01 | 3,0 |
| Alta | 2.116,24 | 37,3 |
| Muy Alta | 0,00 | 0,0 |

**Tabla 2.** Distribución de la susceptibilidad.

**Amenaza:**

| Nivel | Área (km²) | Porcentaje (%) |
|-------|------------|----------------|
| Muy Baja | 2.546,41 | 44,9 |
| Baja | 730,95 | 12,9 |
| Moderada | 2.053,00 | 36,2 |
| Alta | 276,28 | 4,9 |
| Muy Alta | 60,64 | 1,1 |

**Tabla 3.** Distribución de la amenaza.

### 5.3. Mapas

![Mapa de Susceptibilidad](img/Susceptibilidad_CartoDB.png)
*Figura 1. Mapa de susceptibilidad a incendios de la cobertura vegetal.*

![Mapa de Amenaza ajustada](img/Amenaza_ajustado_CartoDB.png)
*Figura 2. Mapa de amenaza ajustada a incendios.*

![Comparativa espacial](img/comparativo_sus_amen_espacial_ajustado.png)
*Figura 3. Comparación espacial entre susceptibilidad y amenaza ajustada.*


### 5.4. Interpretación de los Resultados

- **Susceptibilidad:** la ausencia de categorías Baja y Muy Alta sugiere una vegetación con dos extremos: áreas con poca carga combustible (pastizales, suelos desnudos) y áreas con alta carga (bosques y arbustales densos). La categoría Moderada (3%) es marginal, indicando una transición abrupta entre ecosistemas.

- **Amenaza:** la distribución es mucho más equilibrada. La categoría Muy Baja (45%) refleja zonas de alta montaña con baja accesibilidad y temperaturas moderadas. La Baja (13%) y Moderada (36%) representan la mayor parte del territorio, donde la accesibilidad y los factores climáticos son intermedios. Las categorías Alta (5%) y Muy Alta (1%) se concentran en los centros poblados (Rosario de Lerma, Campo Quijano) y a lo largo de la ruta nacional 51, donde la cercanía a vías y la presencia de vegetación seca elevan el riesgo.

- **Comparación:** la amenaza es más severa que la susceptibilidad en las zonas periurbanas, mientras que en las áreas de alta montaña la baja accesibilidad reduce la amenaza, aunque la susceptibilidad pueda ser alta. Esto confirma que los factores antrópicos (accesibilidad) y climáticos (baja precipitación) son los principales impulsores del riesgo en la región.

---

## 6. Recomendaciones para Bomberos y Gestores de Riesgo

1. **Priorización de recursos:** las áreas de amenaza Alta (4.9%) y Muy Alta (1.1%) deben ser el foco de las acciones de prevención y respuesta. Estas zonas incluyen:
   - **Rosario de Lerma, Campo Quijano y localidades aledañas.**
   - **Corredores viales principales (RN 51 y rutas departamentales).**
   - **Zonas de interfaz urbano-forestal (bordes de los poblados).**

2. **Prevención estructural:**
   - Establecer **franjas cortafuego** de 100-200 m alrededor de los centros poblados y a lo largo de rutas principales.
   - Realizar **quemas prescritas** en áreas de alta susceptibilidad pero baja amenaza (zonas remotas) para reducir la carga de combustible, bajo condiciones meteorológicas seguras.

3. **Sistema de alertas tempranas:**
   - Implementar un **monitoreo continuo** de temperatura, humedad relativa y velocidad del viento en las estaciones meteorológicas de la zona (ej. Salta, Campo Quijano).
   - Integrar datos de **puntos calientes** para detección temprana de focos ígneos.

4. **Educación y concientización:**
   - Realizar talleres comunitarios en las áreas periurbanas para prevenir el uso de fuego en la quema de residuos, fogatas y prácticas agrícolas tradicionales.
   - Distribuir material didáctico (mapas de amenaza impresos y digitales) a las juntas de vecinos y escuelas.

5. **Accesibilidad operativa:**
   - Mantener y mejorar los caminos de acceso a las zonas de amenaza Alta y Muy Alta, especialmente las vías de penetración a las sierras, para garantizar la llegada de los equipos de emergencia.

6. **Actualización de los mapas:**
   - Revisar y actualizar los mapas cada 2 años estimativamente, o después de eventos extremos, incorporando datos de incendios recientes y cambios en el uso del suelo.

---

## 7. Conclusiones

- Se consiguió de manera exitosa generar mapas de susceptibilidad y amenaza.
- Se obtuvo una amenaza con distribución equilibrada y relevancia operativa, donde las categorías Alta y Muy Alta (6% del territorio) se concentran en zonas de interfaz urbano-forestal y ejes viales.
- La susceptibilidad es un factor importante, pero la amenaza está dominada por la accesibilidad y el clima, lo que refuerza la necesidad de acciones preventivas en áreas cercanas a carreteras y centros poblados.
- Estos mapas son una herramienta valiosa para la planificación territorial y la gestión del riesgo, pero deben complementarse con datos de vulnerabilidad (población, infraestructura crítica) para obtener el mapa de riesgo completo.

---

**Para consultas:** 

sergiodanielpaz13@gmail.com

https://www.linkedin.com/in/sergio-daniel-paz/
---

**Fin del informe**
