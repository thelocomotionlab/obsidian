---
type: concept
domain: mathématiques / optimisation
---

# Hessien

## Définition
Pour un [[Champ scalaire]] $\phi$, le hessien (ou matrice hessienne) est le tenseur d'ordre 2 constitué de toutes les dérivées partielles secondes. 

Il représente le **gradient du gradient** : $\mathbf{H}_\phi = \nabla (\nabla \phi)$.

---

## Formalisme
Dans un espace à $n$ dimensions :
$$
(H_\phi)_{ij} = \frac{\partial^2 \phi}{\partial x_i \partial x_j}
$$
Si $\phi$ est de classe $C^2$, la matrice est symétrique (théorème de Schwarz).

---

## Sens physique profond : Courbure et Stabilité
Le hessien décrit la **morphologie locale** du paysage énergétique :
- **Courbure** : il mesure comment la pente (gradient) change.
- **Approximation quadratique** : il permet de modéliser localement $\phi$ par une parabole.
- **Stabilité** : les valeurs propres du hessien déterminent la nature d'un point critique (où $\nabla \phi = 0$) :
    - toutes positives : minimum local (stabilité).
    - toutes négatives : maximum local (instabilité).
    - signes mixtes : point selle (instabilité directionnelle).

---

## Objets liés
- **[[Laplacien]]** : le laplacien est la trace du hessien ($\Delta \phi = \text{Tr}(\mathbf{H}_\phi)$).
- **Énergie potentielle** : en biophysique, le hessien d'un [[Potentiel]] définit la raideur locale d'un système au voisinage de son équilibre.

---

## Applications au "Locomotion Lab"
- **Optimisation du mouvement** : analyse de la "concavité" des fonctions de coût métabolique pour trouver le rendement optimal.
- **Repliement protéique** : détermination des états de stabilité des [[Protéine]]s par l'analyse des puits de potentiel.

## Liens conceptuels
- [[Gradient]]
- [[Laplacien]]
- [[Potentiel]]
- [[Stabilité]]

## Sources
- @