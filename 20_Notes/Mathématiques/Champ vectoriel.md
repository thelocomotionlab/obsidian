---
type: concept
domain: math
---

# Champ vectoriel

## Définition
Un **champ vectoriel** est une application :
\[
\mathbf{F}:\Omega\subseteq\mathbb{R}^n \to \mathbb{R}^n
\]
À chaque point \(\mathbf{x}\), il associe un **vecteur** \(\mathbf{F}(\mathbf{x})\).

## Représentation
En coordonnées cartésiennes (\(n=3\)) :
\[
\mathbf{F}(x,y,z)=\big(F_x(x,y,z),\,F_y(x,y,z),\,F_z(x,y,z)\big)
\]

## Objets liés
- [[Divergence]] : \(\nabla\cdot\mathbf{F}\) (vectoriel → scalaire)
- [[Rotationnel]] : \(\nabla\times\mathbf{F}\) (vectoriel → vectoriel, en 3D)
- [[Jacobien]] : \(\nabla \mathbf{F}\) (vectoriel → [[Champ tensoriel]] ordre 2)
- [[Flux]] : \(\iint_S \mathbf{F}\cdot \mathrm{d}\mathbf{S}\)
- [[Circulation]] : \(\oint_C \mathbf{F}\cdot \mathrm{d}\mathbf{l}\)

## Interprétation physique fondamentale
Un champ vectoriel encode une **intensité + direction** locale.
- Vitesse d’un fluide \(\mathbf{v}(\mathbf{x})\)
- Champ électrique \(\mathbf{E}(\mathbf{x})\)
- Champ magnétique \(\mathbf{B}(\mathbf{x})\)
- Champ de force \(\mathbf{f}(\mathbf{x})\)

## Exemples universels
- Écoulement radial (source) :
\[
\mathbf{F}(\mathbf{x}) = \frac{\mathbf{x}}{\|\mathbf{x}\|^3}
\quad(\mathbf{x}\neq 0)
\]
- Rotation rigide autour de \(z\) :
\[
\mathbf{F}(x,y,z)=(-\omega y,\ \omega x,\ 0)
\]

## Mesures locales (liées aux opérateurs différentiels)
- “Tendance à sortir / entrer” : [[Divergence]]
- “Tendance à tourner” : [[Rotationnel]]
- “Variation directionnelle de chaque composante” : [[Jacobien]]
