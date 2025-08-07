# OpenClassrooms Restaurant OhMyFood

Dans ce projet, vous allez développer l'interface mobile-first d'un site web pour une start-up en utilisant Sass. Vous intégrerez des maquettes pour mobile et desktop, en mettant l'accent sur la conception adaptative et réactive. Vous enrichirez l'expérience utilisateur avec des animations CSS.

## Objectifs du Projet

- **Développer un site "mobile first"** : Le site doit être optimisé pour les appareils mobiles, puis adapté pour les tablettes et les ordinateurs.
- **Intégrer des animations CSS** : Utiliser des animations et transitions CSS pour améliorer l'expérience utilisateur, sans recourir à JavaScript.
- **Respecter les maquettes** : Suivre rigoureusement les maquettes fournies par notre UX designer pour garantir une cohérence visuelle.
- **Utiliser Sass** : Structurer et organiser notre code CSS en utilisant le préprocesseur Sass.

## Ressources mises à disposition :
[Brief créatif](./BriefCreatif.pdf) <br/>
[Maquette figma](https://www.figma.com/design/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood--mobile-et-desktop-?node-id=0-1&p=f)

## Technologies

- **HTML et CSS** : Pour la structure et le style du site.
- **Sass** : Pour organiser et structurer notre code CSS.
- **Animations CSS** : Pour ajouter des effets visuels et améliorer l'interactivité.

## Choix Techniques

1. **Animation du Cœur** :
   - Une transition CSS a été utilisée pour l'animation du bouton "J'aime" en forme de cœur. Au survol, le cœur s'agrandit et se remplit progressivement de couleur grâce aux propriétés `transform` et `fill`.

2. **Sélecteur de Plat** :
   - Une animation de coulissage a été implémentée pour le sélecteur de plat. Au survol d'un plat, une coche apparaît à droite et se déplace de droite à gauche en utilisant la propriété `transform`.

3. **Loader de la Page d'Accueil** :
   - Un loader a été créé avec une animation CSS simple mais efficace. Il apparaît pendant 1 à 3 secondes et couvre tout l'écran. Le loader est cohérent avec la charte graphique.

4. **Approche Mobile First** :
   - Le développement a commencé par une optimisation pour les appareils mobiles. Des media queries ont été utilisées pour adapter le design aux tablettes et aux ordinateurs, garantissant ainsi une expérience utilisateur optimale sur tous les appareils.

## Organisation du Code CSS avec Sass

- **Variables** : Des variables Sass ont été utilisées pour définir les couleurs, les polices et les tailles, facilitant ainsi la maintenance et assurant la cohérence du code.

- **Mixins** : Des mixins ont été créés pour les animations et les transitions, permettant une réutilisation du code et le rendant plus modulaire.

- **Partials** : Le code CSS a été divisé en plusieurs fichiers partiels, chacun responsable d'une partie spécifique du site, comme `_header.scss`, `_menus.scss`, et `_animations.scss`.