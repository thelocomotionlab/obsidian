---
type: concept
domain: math
---

# Champ tensoriel

## Définition (idée)
Un **champ tensoriel** associe à chaque point \(\mathbf{x}\in\Omega\) un **tenseur** (objet multilinéaire).
Exemples : ordre 2 (matrice), ordre 3, etc.

## Cas le plus utilisé : tenseur d’ordre 2
Un champ tensoriel d’ordre 2 :
\[
\mathbf{T}:\Omega\subseteq\mathbb{R}^n \to \mathbb{R}^{n\times n}
\]
En 3D :
\[
\mathbf{T}(\mathbf{x}) =
\begin{pmatrix}
T_{11} & T_{12} & T_{13}\\
T_{21} & T_{22} & T_{23}\\
T_{31} & T_{32} & T_{33}
\end{pmatrix}
\]

## Interprétation physique fondamentale
Un tenseur d’ordre 2 encode une **relation linéaire locale** entre vecteurs.
- Contraintes (stress) : \(\boldsymbol{\sigma}\) (force surfacique = \(\boldsymbol{\sigma}\mathbf{n}\))
- Déformation (strain) : \(\boldsymbol{\varepsilon}\)
- Diffusivité anisotrope : \(\mathbf{D}\) dans \(\mathbf{J}=-\mathbf{D}\nabla c\)
- Inertie / métrique (selon contexte)

## Objets liés
- [[Champ scalaire]] → [[Gradient]] → [[Champ vectoriel]]
- [[Champ vectoriel]] → [[Jacobien]] → [[Champ tensoriel]] (ordre 2)
- [[Hessien]] d’un scalaire : \(\nabla^2\phi\) (ordre 2)

## Opérations différentielles typiques
Selon conventions (ex. en mécanique des milieux continus) :
- Divergence d’un tenseur (ordre 2 → vectoriel) :
\[
(\nabla\cdot \mathbf{T})_i = \sum_{j=1}^{n}\partial_j T_{ij}
\]
- Gradient d’un champ vectoriel (vectoriel → tenseur) :
\[
(\nabla \mathbf{F})_{ij}=\partial_j F_i
\]

## Exemples universels
- Jacobien d’un champ de vitesse \(\mathbf{v}\) :
\[
\nabla \mathbf{v}=
\begin{pmatrix}
\partial_x v_x & \partial_y v_x & \partial_z v_x\\
\partial_x v_y & \partial_y v_y & \partial_z v_y\\
\partial_x v_z & \partial_y v_z & \partial_z v_z
\end{pmatrix}
\]
- Hessien d’un potentiel \(\Phi\) (courbure locale) :
\[
\nabla^2\Phi=
\left[\partial_i\partial_j \Phi\right]
\]
