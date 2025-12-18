---
type: concept
domain: math / mécanique des fluides
---

# Circulation

## Définition
La **circulation** d'un [[Champ vectoriel]] $\mathbf{F}$ le long d'une courbe fermée $C$
est l'intégrale de ligne du champ sur ce contour.

Elle mesure la "quantité de champ" qui s'aligne 
le long de la boucle.

---

## Définition mathématique
$$
\Gamma = \oint_C \mathbf{F} \cdot d\mathbf{l}
$$

- $\Gamma$ : circulation  
- $\mathbf{F}$ : champ vectoriel (ex: vitesse $\mathbf{v}$)  
- $d\mathbf{l}$ : élément de longueur tangent au contour

---

## Sens physique fondamental
La circulation quantifie le **mouvement macroscopique global** autour d'un obstacle ou d'une zone donnée.

Dans un fluide, elle est directement liée à la portance 
(Théorème de Kutta-Joukowski) : pas de circulation, pas de portance.

---

## Lien local ↔ global (Stokes)
La circulation sur un contour fermé est égale au flux 
du [[Rotationnel]] à travers la surface délimitée par ce contour :
$$
\oint_C \mathbf{F} \cdot d\mathbf{l} = \iint_S (\nabla \times \mathbf{F}) \cdot d\mathbf{S}
$$
La circulation est la **manifestation globale** de la rotation locale.

---

## Exemples universels
### 1) Aérodynamique
La circulation de l'air autour d'une aile d'oiseau ou d'un profil 
génère la force de sustentation.

### 2) Électromagnétisme (Ampère)
La circulation du champ magnétique $\mathbf{B}$ autour d'un fil 
est proportionnelle au courant électrique qui le traverse.

---

## Liens conceptuels
- [[Rotationnel]]
- [[Vorticité]]

## Sources
- @