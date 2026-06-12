---
type: concept
domain: chimie
---

# Affinité chimique

## Définition
L'affinité chimique ($A$) est la grandeur thermodynamique qui mesure la tendance d'un système à évoluer par réaction chimique. 

Elle représente la **force motrice** qui pousse les réactifs à se transformer en produits.

---

## Définition mathématique (De Donder)
Pour une réaction chimique donnée, l'affinité est définie par l'opposé de la variation d'[[Enthalpie libre]] par rapport à l'avancement de la réaction $\xi$ :
$$
A = -\left( \frac{\partial G}{\partial \xi} \right)_{T, P} = \sum_{i} \nu_i \mu_i
$$

- $G$ : [[Enthalpie libre]].
- $\xi$ : avancement de la réaction.
- $\mu_i$ : [[Potentiel chimique]] de l'espèce $i$.
- $\nu_i$ : coefficients stoechiométriques (positifs pour les produits, négatifs pour les réactifs).

---

## Sens physique profond
L'affinité chimique est la **pression de transformation**. 

Tout comme une différence de pression mécanique génère un mouvement de fluide, une affinité non nulle génère un flux de transformation chimique. Un système est à l'équilibre chimique si et seulement si son affinité est nulle ($A = 0$). Si $A > 0$, la réaction progresse spontanément vers la droite.



---

## Relation avec l'Entropie
L'affinité est directement liée à la vitesse de production d'[[Entropie]] interne du système :
$$
\frac{dS_i}{dt} = \frac{A \cdot v}{T} \ge 0
$$

- $v$ : vitesse de la réaction ($d\xi / dt$).
- $T$ : température.

Cela montre que la dissipation chimique est le produit du [[Flux]] (vitesse) par la force associée (affinité).

---

## Rôle systémique
- couplage : dans la [[Cellule]], une réaction d'affinité négative (non spontanée) peut être "poussée" par un couplage avec l'hydrolyse de l'[[ATP]] qui possède une affinité très élevée.
- cinétique : bien que l'affinité indique la "volonté" de réaction, elle ne dit rien sur sa vitesse réelle, qui dépend des barrières d'activation.

---

## Liens conceptuels
- [[Enthalpie libre]]
- [[Potentiel chimique]]
- [[Entropie]]
- [[Dissipation entropique]]
- [[Effet de Bohr]]

## Sources
- De Donder, T. (1927). *L'Affinité*.
- @