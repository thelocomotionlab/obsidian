---
type: concept
domain: math
---

# Gradient

## Définition
Pour un [[Champ scalaire]] $\phi:\Omega\subseteq\mathbb{R}^n\to\mathbb{R}$,
le **gradient** est le champ vectoriel :
$$
\nabla \phi =
\left(\frac{\partial \phi}{\partial x_1},\dots,\frac{\partial \phi}{\partial x_n}\right)
$$
En 3D :
$$
\nabla\phi=
\left(\frac{\partial\phi}{\partial x},\frac{\partial\phi}{\partial y},\frac{\partial\phi}{\partial z}\right)
$$

## Propriété clé (définition opérationnelle)
Pour tout vecteur unitaire $\mathbf{u}$,
$$
\mathrm{D}_{\mathbf{u}}\phi = \nabla\phi\cdot \mathbf{u}
$$
Donc $\nabla\phi$ est le **vecteur qui encode toutes les dérivées directionnelles**.

## Sens physique fondamental
Le gradient pointe vers la **direction de la plus forte augmentation** de $\phi$,
et sa norme est la **pente maximale** :
$$
\max_{\|\mathbf{u}\|=1}\mathrm{D}_{\mathbf{u}}\phi = \|\nabla\phi\|
$$

## Gradient et flux
Les flux sont généralement proportionnels
au gradient d’une grandeur potentielle :
$$
\vec{J} = -K \nabla \psi
$$

- $\vec{J}$ : flux  
- $K$ : coefficient de transport  
- $\psi$ : potentiel (température, pression, concentration…)

---

## Objets liés
- [[Champ scalaire]] → (gradient) → [[Champ vectoriel]]
- [[Divergence]] du gradient : [[Laplacien]] $\Delta\phi=\nabla\cdot\nabla\phi$
- [[Hessien]] : $\nabla(\nabla\phi)=\nabla^2\phi$ (matrice des dérivées secondes)

## Exemples universels
### 1) Altitude / topographie
$\phi(x,y)$ = altitude.  
$\nabla\phi$ = direction de la montée la plus raide.

### 2) Diffusion / transport
Flux diffusif (loi de Fick isotrope) :
$$
\mathbf{J} = -D\,\nabla c
$$
Le flux va “vers la descente” de concentration.

### 3) Potentiel → force
Si $\Phi$ est un potentiel :
$$
\mathbf{F} = -\nabla \Phi
$$
(force comme descente de potentiel)

## Identités utiles
- Si $\phi$ est constante, $\nabla\phi=\mathbf{0}$.
- Produit :
$$
\nabla(\phi\psi)=\phi\nabla\psi+\psi\nabla\phi
$$
