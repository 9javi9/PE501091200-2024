---
title: Aspecto Teórico
nav_order: 6
---

# Aspecto Teórico

- El método de aprendizaje empleado se basó en la propuesta **NNPU** desarrollada por **Kiriyo (2017)**, la cual plantea un enfoque de *aprendizaje positivo–no etiquetado* para clasificación binaria.  
  👉 [Ver publicación](https://arxiv.org/pdf/1703.00593)

  La función de costo fue adaptada de la siguiente manera:

$$
\tilde{R}(g)=
\max (
\tilde{R}_{pu}^{\text{NNPU}}(g);
\tilde{R}_{nu}^{\text{NNNU}}(g)
)
$$

- Para la etapa de clasificación se utilizó como *backbone* la arquitectura **ResNet-152**, reconocida por su profundidad y estabilidad en el entrenamiento de redes convolucionales profundas.  
  👉 [Ver referencia](https://ieeexplore.ieee.org/document/7780459)
