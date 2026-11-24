# EVALUACION-GRUPAL-FINAL

**Autocorrelación espacial y Mapa LISA de Argentina**
Curso: Introducción a la Ciencia de Datos Espaciales

**Integrantes:** (completar)

## Notebook

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19q5k0rcpKGw5EUdIh41VGTmj7KNir5gt)

## Descripción

Se analiza el **porcentaje de población sin cobertura de salud** en los **527 departamentos** de Argentina, para saber si los departamentos con mucha población sin cobertura están rodeados de otros en la misma situación (autocorrelación espacial).

## Datos

- **Censo 2022 (INDEC):** cuadro *"Cobertura de salud según departamento"*, un archivo por provincia (los 24 archivos `c2022_..._salud_c1_...xlsx` de este repositorio).
- **Mapa oficial de departamentos:** API Georef (datos.gob.ar), en base al Instituto Geográfico Nacional (IGN). Se descarga automáticamente desde el notebook.

## Método

Coroplético, 4 vecindarios (Queen, Perímetro, KNN y Kernel KNN), normalización de pesos, spatial lag, Moran global y mapas LISA (hotSpot, coldSpot, hotOutlier y coldOutlier).
