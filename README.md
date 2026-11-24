# EVALUACION-GRUPAL-FINAL


## Notebook

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19q5k0rcpKGw5EUdIh41VGTmj7KNir5gt)

## Página web
[Link Página Web](https://a20242914-alt.github.io/EVALUACION-GRUPAL-FINAL/)

## Datos

- **Censo 2022 (INDEC):** cuadro *"Cobertura de salud según departamento"*, un archivo por provincia (los 24 archivos `c2022_..._salud_c1_...xlsx` de este repositorio).
- **Mapa oficial de departamentos:** API Georef (datos.gob.ar), en base al Instituto Geográfico Nacional (IGN). Se descarga automáticamente desde el notebook.

## Método

Coroplético, 4 vecindarios (Queen, Perímetro, KNN y Kernel KNN), normalización de pesos, spatial lag, Moran global y mapas LISA (hotSpot, coldSpot, hotOutlier y coldOutlier).
