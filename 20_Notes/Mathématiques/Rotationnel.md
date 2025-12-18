---
type: concept
domain: math
---

# Rotationnel

## Définition
Pour un [[Champ vectoriel]] $\mathbf{F}=(F_x, F_y, F_z)$ dans $\mathbb{R}^3$,
le **rotationnel** est le champ vectoriel :
$$
\nabla \times \mathbf{F} = 
\left( \frac{\partial F_z}{\partial y} - \frac{\partial F_y}{\partial z}, \quad 
\frac{\partial F_x}{\partial z} - \frac{\partial F_z}{\partial x}, \quad 
\frac{\partial F_y}{\partial x} - \frac{\partial F_x}{\partial y} \right)
$$

On l'écrit souvent via le produit vectoriel formel avec l'opérateur nabla : $\text{rot}\,\mathbf{F} = \nabla \times \mathbf{F}$.

---

## Sens physique fondamental
Le rotationnel mesure la **vorticité** ou la "tendance à la rotation" 
locale d'un champ autour d'un point :
- Si $\mathbf{v}$ est la vitesse d'un fluide, $\nabla \times \mathbf{v}$ indique 
la vitesse angulaire locale.
- Il quantifie la non-conservativité d'un champ.

---

## Lien local ↔ global
Rotationnel = **circulation par unité de surface** (intuition).
Formellement lié au **Théorème de Stokes**, 
qui relie l'intégrale de surface du rotationnel 
à la circulation du champ sur le contour de cette surface.

---

## Objets liés
- [[Champ vectoriel]] → (rotationnel) → [[Champ vectoriel]]
- Rotationnel du [[Gradient]] : $\nabla \times (\nabla \phi) = \mathbf{0}$ 
(un champ de gradient ne tourne pas).
- [[Divergence]] du rotationnel : $\nabla \cdot (\nabla \times \mathbf{F}) = 0$ 
(ce qui tourne ne "sort" pas).

---

## Exemples universels
### 1) Dynamique des fluides
Un écoulement avec $\nabla \times \mathbf{v} \neq 0$ présente des **vortex** ou des tourbillons. 
Un écoulement avec $\nabla \times \mathbf{v} = 0$ est dit **irrotationnel**.

### 2) Électromagnétisme (Loi de Maxwell-Faraday)
$$
\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t}
$$
Une variation de champ magnétique crée un "tourbillon" de champ électrique.

### 3) Rotation de corps rigide
Pour un corps tournant à vitesse angulaire $\mathbf{\omega}$, 
le champ des vitesses $\mathbf{v} = \mathbf{\omega} \times \mathbf{r}$ donne :
$$
\nabla \times \mathbf{v} = 2\mathbf{\omega}
$$

---

## Identités utiles
- Produit scalaire–vecteur :
$$
\nabla \times (\phi \mathbf{F}) = \nabla \phi \times \mathbf{F} + \phi (\nabla \times \mathbf{F})
$$
- Rotationnel du rotationnel :
$$
\nabla \times (\nabla \times \mathbf{F}) = \nabla(\nabla \cdot \mathbf{F}) - \Delta \mathbf{F}
$$

---

## Liens conceptuels
- [[Circulation]]
- [[Vorticité]]

## Sources
- @