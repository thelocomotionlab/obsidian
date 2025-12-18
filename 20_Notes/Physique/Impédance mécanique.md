---
type: concept
domain: physique
---

# Impédance mécanique

## Définition
Grandeur caractérisant la résistance d'une structure ou d'un milieu à un mouvement périodique (vitesse) sous l'effet d'une force harmonique imposée.

Elle quantifie la "difficulté" avec laquelle un [[Système]] se laisse mettre en mouvement.

---

## Définition mathématique
Dans le domaine fréquentiel, pour une pulsation $\omega$, l'impédance complexe $Z$ est le rapport :
$$
Z(\omega) = \frac{F(\omega)}{v(\omega)}
$$

Elle se décompose en une partie réelle et une partie imaginaire :
$$
Z = R + jX
$$

- $R$ : résistance mécanique (liée à la dissipation d'énergie par [[Amortissement]])
- $X$ : réactance mécanique (liée au stockage d'énergie par l'[[Inertie]] et l'élasticité)

L'expression complète pour un [[Oscillateur harmonique]] simple est :
$$
Z = c + j\left(m\omega - \frac{k}{\omega}\right)
$$

---

## Sens physique profond
L'impédance mécanique régit le **transfert d'énergie** entre deux milieux :
- matching d'impédance : le transfert d'énergie est maximal lorsque les impédances de la source et du récepteur sont égales.
- rupture d'impédance : une différence brutale entre deux milieux (ex: interface air/peau) provoque la réflexion de l'onde et une faible pénétration tissulaire.

---

## Rôle conceptuel
L'impédance est une **fonction de la fréquence**. 
- à basse fréquence : le système est "contrôlé par la raideur" ($k/\omega$ domine).
- à haute fréquence : le système est "contrôlé par la masse" ($m\omega$ domine).
- à la [[Fréquence propre]] : la réactance s'annule ($X=0$), l'impédance est minimale et purement dissipative.

---

## Portée transdisciplinaire
- locomotion : impédance du membre inférieur ("stiffness") pour optimiser le stockage d'énergie élastique et le rebond.
- acoustique : rôle des [[Sinus paranasaux]] comme résonateurs modifiant l'impédance du conduit vocal lors du [[Humming]].
- biophysique : impédance des tissus mous déterminant l'efficacité des vibrations thérapeutiques ou des ondes de choc.

---

## Liens conceptuels
- [[Vibration mécanique]]
- [[Résonance]]
- [[Amortissement]]
- [[Oscillateur harmonique]]
- [[Flux]]

## Sources
- @