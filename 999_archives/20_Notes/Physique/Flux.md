---
type: concept
domain: physique 
---

# Flux

## Définition
Grandeur décrivant le transfert d’une quantité 
(matière, énergie, charge) à travers une surface donnée 
par unité de temps.

Le flux est la **description dynamique du mouvement**, 
indépendamment de la nature de la grandeur transportée.

---

## Forme générale
Pour un champ vectoriel $\mathbf{J}$ (densité de flux) 
traversant une surface $S$ :

$$
\Phi = \iint_S \mathbf{J} \cdot d\mathbf{S}
$$

- $\Phi$ : flux scalaire (résultat global)
- $\mathbf{J}$ : vecteur densité de flux (quantité par unité de surface et de temps)
- $d\mathbf{S}$ : vecteur surface élémentaire, normal à l'interface

---

## Flux et gradients (Lois de transport)
Le flux est la réponse du système à une rupture d'équilibre. 
Il est presque toujours proportionnel au [[Gradient]] 
d'une grandeur potentielle :

$$
\mathbf{J} = -K \nabla \psi
$$

- diffusion : [[Lois de Fick]] (gradient de concentration)
- thermique : [[Loi de Fourier]] (gradient de température)
- électrique : [[Loi d'Ohm]] (gradient de potentiel électrique)
- biologique : [[Flux sanguin]] (gradient de pression)

---

## Flux et conservation
La variation temporelle d'une grandeur dans un volume 
est égale au flux net sortant, exprimé par la [[Divergence]] :

$$
\frac{\partial \rho}{\partial t} + \nabla \cdot \mathbf{J} = \sigma
$$

- $\rho$ : densité locale
- $\nabla \cdot \mathbf{J}$ : divergence du flux (création ou perte locale)
- $\sigma$ : terme source ou puits

---

## Sens physique profond
Le flux est le **moteur de la dissipation**. 

Il exprime la tendance universelle d'un système à détruire 
ses propres gradients pour atteindre l'état de probabilité 
maximale ([[Entropie]]). Un flux ne s'arrête que lorsque 
le potentiel est uniformisé.

---

## Dualité Flux / Force
Dans la thermodynamique des processus irréversibles :
- le flux est la **réponse** du système.
- le gradient est la **force généralisée** qui pousse le flux.

Le produit du flux par sa force associée définit la 
vitesse de production d'[[Entropie]].

---

## Portée transdisciplinaire
- physiologie : flux ioniques via le [[Gradient électrochimique]].
- métabolisme : flux d'[[Oxygène]] et de nutriments vers la [[Mitochondrie]].
- pratique : gestion du flux ventilatoire lors du [[Humming]].

---

## Liens conceptuels
- [[Gradient]]
- [[Divergence]]
- [[Interface]]
- [[Potentiel]]
- [[Dissipation énergétique]]
- [[Entropie]]

## Sources
- @