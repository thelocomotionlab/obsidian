---
type: concept
domain: modélisation physique
---

# Oscillateur amorti

## Définition
Modèle d'oscillateur intégrant une force de friction (généralement visqueuse), entraînant une perte progressive de l'énergie mécanique du [[Système]].

---

## Équation différentielle
$$
\ddot{x} + 2\zeta\omega_0\dot{x} + \omega_0^2 x = 0
$$

- $\zeta$ : coefficient d’amortissement (sans dimension).
- $\dot{x}$ : vitesse (dérivée première).
- $2\zeta\omega_0$ : terme de dissipation lié à la friction.

---

## Régimes dynamiques
Le comportement dépend de la valeur de $\zeta$ :
- $\zeta < 1$ (sous-critique) : oscillations dont l'amplitude décroît exponentiellement.
- $\zeta = 1$ (critique) : retour à l'équilibre le plus rapide possible sans oscillation.
- $\zeta > 1$ (sur-critique) : retour lent et laborieux, dominé par la viscosité.

---

## Sens physique profond
L'amortissement traduit le **couplage avec un puits thermique**. 
L'énergie mécanique macroscopique est "dégradée" en agitation thermique microscopique. C'est une manifestation directe de l'[[Irréversibilité]] et de la création d'[[Entropie]].

---

## Importance biologique
Les tissus vivants (fascias, muscles, tendons) sont des oscillateurs fortement amortis. Cet [[Amortissement]] est vital : il protège les structures contre la [[Résonance]] destructrice et permet l'absorption des chocs lors de la locomotion.

---

## Liens conceptuels
- [[Amortissement]]
- [[Dissipation énergétique]]
- [[Impédance mécanique]]
- [[Absorption mécanique]]
- [[Oscillateur amorti]]

## Sources
- @