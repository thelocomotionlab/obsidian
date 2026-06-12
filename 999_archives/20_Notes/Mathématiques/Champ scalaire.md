---
type: concept
domain: math
---

# Champ scalaire

## Définition
Un **champ scalaire** est une application :
$$
\phi:\Omega\subseteq\mathbb{R}^n \to \mathbb{R}
$$
À chaque point $\mathbf{x}$ de l’espace (ou de l’espace-temps), il associe **un nombre**.

## Structure mathématique
- Domaine : $\Omega \subseteq \mathbb{R}^n$
- Codomaine : $\mathbb{R}$
- Régularité : typiquement $\phi \in C^k(\Omega)$ selon les besoins (dérivées d’ordre $k$).

## Objets liés
- Dérivée directionnelle : $\mathrm{D}_{\mathbf{u}}\phi$
- [[Gradient]] : $\nabla \phi$ (transforme scalaire → [[Champ vectoriel]])
- [[Hessien]] : $\nabla^2 \phi$ (transforme scalaire → [[Champ tensoriel]] d’ordre 2)
- [[Laplacien]] : $\Delta \phi = \nabla\cdot\nabla \phi$

## Interprétation physique fondamentale
Un champ scalaire représente une **densité** ou un **potentiel** : une quantité “intensive” définie point par point.
- Potentiel : “niveau” d’énergie / d’altitude / de pression.
- Densité : concentration, température, masse volumique.

## Exemples universels
- Température $T(\mathbf{x})$
- Pression $p(\mathbf{x})$
- Potentiel gravitationnel $\Phi(\mathbf{x})$
- Densité de charge $\rho(\mathbf{x})$
- Fonction de concentration $c(\mathbf{x})$

## Formules utiles
- Variation infinitésimale :
$$
\mathrm{d}\phi \approx \nabla\phi\cdot \mathrm{d}\mathbf{x}
$$
- Dérivée directionnelle (unitaire $\mathbf{u}$) :
$$
\mathrm{D}_{\mathbf{u}}\phi = \nabla\phi\cdot \mathbf{u}
$$
