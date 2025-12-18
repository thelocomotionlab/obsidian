---
type: concept
domain: mécanique des fluides
---

# Vorticité

## Définition
La **vorticité** est un champ vectoriel qui décrit 
le mouvement de rotation local d'un élément de fluide 
autour d'un point donné.

C'est l'analogue de la vitesse angulaire pour un milieu continu.

---

## Définition mathématique
La vorticité $\mathbf{\omega}$ est définie comme le [[Rotationnel]] 
du champ de vitesse $\mathbf{v}$ :
$$
\mathbf{\omega} = \nabla \times \mathbf{v}
$$

Dans un écoulement 2D, elle est souvent traitée comme un scalaire 
perpendiculaire au plan de l'écoulement.

---

## Sens physique fondamental
La vorticité représente la **"micro-rotation"** :
elle indique à quelle vitesse et dans quelle direction 
un petit objet placé dans le flux tournerait sur lui-même.

Un écoulement peut avoir une trajectoire courbe (macro) 
tout en ayant une vorticité nulle (micro), et inversement.

---

## Dynamique (Équation de transport)
Dans un fluide visqueux, la vorticité se diffuse 
de la même manière que la chaleur ou la concentration :
$$
\frac{D\mathbf{\omega}}{Dt} = (\mathbf{\omega} \cdot \nabla)\mathbf{v} + \nu \Delta \mathbf{\omega}
$$
Elle est produite aux interfaces (parois) à cause de la viscosité.

---

## Exemples universels
### 1) Couche limite
La vorticité est maximale près des parois des vaisseaux sanguins, 
là où les gradients de vitesse sont les plus forts.

### 2) Sillage et Turbulence
Les tourbillons (vortex) sont des régions 
où la vorticité est concentrée. Leur détachement 
crée de la dissipation énergétique.

---

## Liens conceptuels
- [[Rotationnel]]
- [[Circulation]]
- [[Flux sanguin]]

## Sources
- @