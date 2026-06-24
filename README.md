# Apéndice C: Generación de Recursos Gráficos y Visualización

**Trabajo Fin de Grado:** Análisis tecno-económico del modelo de negocio del agregador en España  
**Autor:** Alberto Zafra Muñoz | Universidad de Sevilla (2026)  

Este repositorio aloja los *scripts* de Python utilizados para el análisis exploratorio de datos y la generación paramétrica de las figuras, gráficas y esquemas analíticos que ilustran la memoria de este TFG. 

*(Nota: El código responsable de generar las gráficas de resultados finales de optimización —Figuras 4.6 a 4.9— se encuentra integrado directamente en el algoritmo principal del **Apéndice B**).*

---

## 📂 Contenido del Repositorio

Los archivos `.ipynb` están categorizados en función del capítulo al que pertenecen dentro de la memoria, utilizando las librerías `matplotlib` y `pandas`:

### 📖 Capítulo 2: Estado del Arte (Contexto y Conceptos)
* `Fig_2_1_Curva_Pato.ipynb`: Genera la representación visual del impacto de la demanda neta frente a la inyección masiva de generación solar en España.
* `Fig_2_3_Impacto_UEM_vs_CEM.ipynb`: Modela conceptualmente el efecto rebote en la red local al comparar la gestión aislada frente a la gestión coordinada por un agregador.
* `Fig_2_4_Modelo_Shared_Savings.ipynb`: Representación gráfica de la frontera de Pareto teórica y la zona de viabilidad "Win-Win".
* `Fig_2_5_Zonotopo_Flexibilidad.ipynb`: Dibuja el modelo matemático de cuantificación geométrica (espacio multidimensional) de la flexibilidad distribuida.
* `Fig_2_7_Cooptimizacion_OMIE_aFRR.ipynb`: Ilustra la estrategia teórica de reserva de banda y activación de energía frente al programa base del mercado diario.

### 📊 Capítulo 4: Caso de Estudio (Parámetros de Entrada)
* `Fig_4_1_Perfiles_Demanda.ipynb`: Plotea las curvas base normalizadas correspondientes a los tres prosumidores del clúster piloto (residencial, comercial y agrícola).
* `Fig_4_2_Generacion_Solar.ipynb`: Dibuja el perfil en campana de la disponibilidad solar fotovoltaica para la jornada de estudio.
* `Fig_4_3_Precios_DAM.ipynb`: Representa la casación horaria del Mercado Diario (OMIE), evidenciando el hundimiento diurno y el pico nocturno.
* `Fig_4_4_Tarifa_PVPC.ipynb`: Genera la gráfica de la tarifa minorista de indexación (coste base para el prosumidor).
* `Fig_4_5_Precios_aFRR.ipynb`: Visualización en panel dual de los precios de disponibilidad de banda y los precios de energía activada en el mercado de regulación secundaria operado por REE.

---

## ⚙️ Notas de Ejecución

Para la correcta visualización de las gráficas relacionadas con el Capítulo 4 (Datos Reales), es imprescindible que los *scripts* tengan acceso a las bases de datos originales. Asegúrese de descargar los archivos de series temporales `.csv` alojados en el repositorio del **Apéndice A** y situarlos en el mismo directorio de ejecución antes de lanzar los *scripts*.
