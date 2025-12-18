---
type: concept
domain: math
---

# Laplacien

## Définition (scalaire)
Pour un [[Champ scalaire]] $\phi$,
$$
\Delta\phi = \nabla\cdot(\nabla\phi)
$$
En 3D cartésien :
$$
\Delta\phi=\frac{\partial^2\phi}{\partial x^2}+\frac{\partial^2\phi}{\partial y^2}+\frac{\partial^2\phi}{\partial z^2}
$$

## Sens physique fondamental
Le laplacien mesure une **courbure / écart à la moyenne locale** :
- $\Delta\phi>0$ : $\phi$ est “en creux” (tendance à augmenter autour)
- $\Delta\phi<0$ : “en bosse”
C’est l’opérateur central des phénomènes de **diffusion** et des champs **harmoniques**.

## Objets liés
- [[Gradient]], [[Divergence]], [[Hessien]] :
$$
\Delta\phi = \mathrm{tr}(H_\phi)
$$

## Exemples universels
### 1) Diffusion / chaleur
$$
\frac{\partial T}{\partial t} = \alpha \Delta T
$$

### 2) Potentiel en région sans sources (harmonique)
$$
\Delta \Phi = 0
$$
