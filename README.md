![wp](Wompi.png)
# **Prueba Técnica - Especialista analítica de negocio**
## Prueba Analítica: *Análisis de segmentación de comercios*
### Cientifico de Datos:

* Daniel Felipe Pérez Grajales . dfperezg@unal.edu.co<br>

<br><br>


---
<br>

**Objetivo:**

Realizar un análisis de segmentación de comercios a partir de datos transaccionales, identificando grupos con comportamientos similares y detectando oportunidades comerciales dentros de la industria.

**Instrucciones**

Se te entrega un archivo *payments_datasets.csv* con información de transacciones de pago Deberás:

1. Construir métricas a nivel de comercio como: número de transacciones, ticket promedio, tasa de aprobación y distribución de medios de pago.

2. Preparar el conjunto de datos para clustering, estandarizando variables y seleccionando las más relevantes para la segmentación.

3. Aplicar una técnica de clustering.

4. Analizar y describir los clusters, resaltando similitudes y diferencias entre ellos.

5. Detectar oportunidades comerciales dentro de cada industrial(merchant_ciiu), comparando comercios con caracteristicas similares pero diferencias marcadas en el uso de medios de pago.

**Entregable**

Archivo Jupyter Notebook (Prueba_tecnica_Wompi_Especialista_Negocio.ipynb) funcional con el siguiente contenido:


* Carga del dataset.  
* Cálculo de métricas por comercio.
* Ejecución del algoritmo de clustering y elección del número óptimo de clusters.
* Tabla de oportunidades comerciales mostrando pares de comercios comparables con brechas significativas en uso de medios de pago.
* Conclusiones y recomendaciones orientadas a negocio.

## Conclusiones Finales del Análisis:

- Se identificaron 4 clusters de comercios con comportamientos similares en cuanto al número de transacciones y la tasa de aprobación de las transacciones.

#### sus principales caracteristicas son:

- **cluster 0:** el Tipo de comercio de predomina es el G4711, con un ticket promedio de 45415.53 centavos,el medio de pago que predomina es el CASH con un 85,95% de las transacciones, Se pueden considerar como **Tradicionales** en medio de pago.

- **cluster 1:** el Tipo de comercio de predomina es el G4741, con un ticket promedio de 79681.74 centavos,el medio de pago que predomina es el CARD con un 28,11% de las transacciones, Se pueden considerar como **Multicanales** en medio de pago.

- **cluster 2:** el Tipo de comercio de predomina es el G4751, con un ticket promedio de 139151,64 centavos el más alto de todos los grupos,el medio de pago que predomina es NEQUI con un 84,19% de las transacciones, Se pueden considerar como **Digitales Nequí** en medio de pago.

- **cluster 3:** el Tipo de comercio de predomina es el G4761, con un ticket promedio de 38556.63 centavos,el medio de pago que predomina es BANCOLOMBIA con un 85,11% de las transacciones, Se pueden considerar como **Digitales Bancolombia** en medio de pago.

- Se recomienda enfocar estrategias comerciales en comercios con baja adopción de medios Digitales(Bancolombia,Nequi,PSE), como los comercios del cluster 0 , tipos de comercio G4711.

-----------
