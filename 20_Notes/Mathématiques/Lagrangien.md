---
type: concept
domain: math
---

# Lagrangien

## Définition
Le lagrangien est une fonction scalaire qui résume la dynamique complète d'un [[Système]] en encodant ses échanges énergétiques. 

Il constitue le noyau du formalisme variationnel, permettant de déduire les lois du mouvement non plus par des forces locales (Newton), mais par un principe d'optimisation globale.

---

## Définition mathématique
Pour un système mécanique classique à $n$ degrés de liberté, le lagrangien $\mathcal{L}$ est défini sur l'espace des configurations par :
$$
\mathcal{L}(q_i, \dot{q}_i, t) = T(q_i, \dot{q}_i, t) - V(q_i, t)
$$

- $q_i$ : coordonnées généralisées (position, angle, etc.).
- $\dot{q}_i$ : vitesses généralisées.
- $T$ : énergie cinétique (forme quadratique des vitesses).
- $V$ : énergie [[Potentiel]]le.

---

## Le Principe d'Action (Hamilton)
La dynamique réelle du système entre deux instants $t_1$ et $t_2$ est celle qui rend stationnaire l'**[[Action]]** $\mathcal{S}$ :
$$
\mathcal{S} = \int_{t_1}^{t_2} \mathcal{L}(q_i, \dot{q}_i, t) \, dt
$$



---

## Équations d’Euler-Lagrange
La condition de stationnarité de l'action ($\delta \mathcal{S} = 0$) conduit aux équations du mouvement :
$$
\frac{d}{dt}\left(\frac{\partial \mathcal{L}}{\partial \dot{q}_i}\right) - \frac{\partial \mathcal{L}}{\partial q_i} = 0
$$

Ces équations transforment un problème d'optimisation globale en un système d'équations différentielles locales.

---

## Sens physique profond
Le lagrangien exprime l'**économie de la nature**. 

Il révèle que la trajectoire d'un système n'est pas "poussée" par le passé, mais "tirée" par une configuration qui minimise le déséquilibre entre mouvement ($T$) et contrainte ($V$). C'est le cadre le plus puissant pour intégrer les [[Symétrie]]s : toute invariance du lagrangien par une transformation conduit directement à une loi de conservation ([[Théorème de Noether]]).

---

## Liens conceptuels
- [[Potentiel]]
- [[Action]]
- [[Symétrie]]
- [[Théorème de Noether]]
- [[Énergie]]

## Sources
- @