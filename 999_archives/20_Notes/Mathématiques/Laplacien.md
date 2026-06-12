---
type: concept
domain: mathématiques / physique
---

# Laplacien

## Définition
Le laplacien est un opérateur différentiel d'ordre 2 défini comme la divergence du gradient. 

Il mesure la différence entre la valeur locale d'une grandeur et sa moyenne aux alentours.

---

## Formalisme
Pour un [[Champ scalaire]] $\phi$ :
$$
\Delta \phi = \nabla \cdot (\nabla \phi) = \sum_{i=1}^{n} \frac{\partial^2 \phi}{\partial x_i^2}
$$
C'est également la trace du [[Hessien]].

---

## Sens physique profond : Diffusion et Lissage
Le laplacien est l'opérateur de la **conduction** et de l'**équilibre local** :
- **Diffusion** : il décrit comment une substance ou la chaleur se "propage" pour uniformiser les gradients ($\frac{\partial \phi}{\partial t} = D \Delta \phi$).
- **Courbure moyenne** : $\Delta \phi > 0$ indique un "creux" local (la valeur est inférieure à la moyenne de ses voisins), tandis que $\Delta \phi < 0$ indique une "bosse".
- **États stationnaires** : l'équation de Laplace ($\Delta \phi = 0$) définit les fonctions harmoniques, représentant des systèmes en équilibre parfait sans sources internes.

---

## Exemples universels
- **Équation de la chaleur** : $\frac{\partial T}{\partial t} - \alpha \Delta T = 0$.
- **Électrostatique** : $\Delta V = -\rho / \epsilon_0$ (équation de Poisson).
- **Ondes** : $\frac{\partial^2 u}{\partial t^2} - c^2 \Delta u = 0$.

---

## Applications au "Locomotion Lab"
- **Dissipation thermique** : gestion de la chaleur produite par l'effort musculaire.
- **Neurosciences** : propagation du potentiel d'action et diffusion des neurotransmetteurs dans la fente synaptique.
- **Morphogenèse** : modèles de réaction-diffusion de Turing (formation des motifs biologiques).

## Liens conceptuels
- [[Gradient]]
- [[Divergence]]
- [[Hessien]]
- [[Équation d'onde]]

## Sources
- @