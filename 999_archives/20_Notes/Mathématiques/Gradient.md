---
type: concept
domain: mathématiques
---

# Gradient

## Définition généralisée
Le gradient est un opérateur différentiel qui mesure la variation spatiale d'une grandeur. Mathématiquement, le gradient d'un tenseur d'ordre $n$ produit un tenseur d'ordre $n+1$.

Il transforme l'information locale en une **structure de variation**.

---

## 1. Gradient d'un scalaire (Ordre 0 → 1)
Pour un [[Champ scalaire]] $\phi$ (ex: température, pression), le gradient est un champ vectoriel :
$$
\nabla \phi = \left( \frac{\partial \phi}{\partial x_1}, \dots, \frac{\partial \phi}{\partial x_n} \right)
$$
**Sens physique :** Il pointe vers la direction de la plus forte augmentation de $\phi$. Sa norme représente la pente maximale.



---

## 2. Gradient d'un vecteur (Ordre 1 → 2)
Pour un champ vectoriel $\mathbf{v}$ (ex: vitesse d'un fluide), le gradient est un tenseur d'ordre 2, souvent appelé **tenseur gradient** ou matrice jacobienne :
$$
(\nabla \mathbf{v})_{ij} = \frac{\partial v_i}{\partial x_j}
$$
**Sens physique :** Il décrit comment le vecteur change de direction et de norme lorsqu'on se déplace dans l'espace. En mécanique des milieux continus, il se décompose en :
- une partie symétrique : le tenseur des taux de déformation (étirement/compression).
- une partie antisymétrique : le tenseur de rotation (vorticité).



---

## 3. Gradient d'un tenseur (Ordre $n \to n+1$)
Pour un tenseur $\mathbf{T}$, le gradient augmente la dimensionnalité de l'objet, capturant la complexité des variations de contraintes ou de propriétés anisotropes du milieu.

---

## Définition intrinsèque (Opérationnelle)
Le gradient est l'unique opérateur tel que la variation différentielle $d\mathbf{A}$ d'une grandeur $\mathbf{A}$ lors d'un déplacement $d\mathbf{r}$ soit :
$$
d\mathbf{A} = (\nabla \mathbf{A}) \cdot d\mathbf{r}
$$
Il est l'**encodeur universel de la linéarisation locale** : il dit comment "l'objet" $\mathbf{A}$ se comporte au voisinage immédiat d'un point.

---

## Sens physique profond : Le moteur des flux
Le gradient est la signature d'un **déséquilibre**. 
En physique, la nature cherche à effacer les gradients. Cela génère des [[Flux]] qui s'opposent à la pente (Lois de transport) :
$$
\mathbf{J} = -K \nabla \psi
$$
- loi de Fick (diffusion) : $\nabla c$ (gradient de concentration).
- loi de Fourier (thermique) : $\nabla T$ (gradient de température).
- loi d'Ohm : $\nabla V$ (gradient de potentiel électrique).

---

## Objets et identités liés
- **[[Laplacien]]** : $\Delta \phi = \nabla \cdot (\nabla \phi)$. Mesure la courbure locale (si le point est un "sommet" ou un "creux" par rapport à ses voisins).
- **[[Hessien]]** : $\nabla (\nabla \phi)$. Tenseur d'ordre 2 des dérivées secondes, décrivant la morphologie locale du paysage.
- **[[Divergence]]** : Trace du gradient d'un vecteur ($\nabla \cdot \mathbf{v}$).

---

## Applications au "Locomotion Lab"
- **Mécanobiologie** : Le gradient de déplacement des tissus active la [[Mécanotransduction]].
- **Hémodynamique** : Le gradient de vitesse du [[Sang]] crée le [[Cisaillement]] sur l'[[Endothélium]].
- **Signalisation** : Le neurone détecte les gradients de [[Potentiel chimique]] pour guider sa croissance.

## Liens conceptuels
- [[Flux]]
- [[Divergence]]
- [[Potentiel]]
- [[Tenseur]]

## Sources
- @