# Quatrième projet du parcours "Intégrateur web" chez OpenClassrooms.
L'objectif étant d'intégrer puis de dynamiser une page web avec des animations CSS en utilisant le préprocesseur Sass.

# Lien vers GitPages :
[OhMyFood](https://epsilon-devweb.github.io/ohmyfood-main/dist/index.html)

# Ressources mises à disposition :
[Guide étapes.pdf](https://github.com/epsilon-devweb/OhMyFood/files/12297769/Guide.etapes.pdf)  
[Brief Créatif.pdf](https://github.com/epsilon-devweb/OhMyFood/files/12297768/Brief.Creatif.pdf) + images et textes.

# Objectifs
- Développer un site proposant le menu de 4 grands restaurants parisiens.  
- Permettre la réservation en ligne et la composition de menus.

# Technologies
- Le développement doit se faire en CSS avec Sass, sans JavaScript.  
- Le site devra être réalisé en adoptant le Mobile First.  
- Aucun framework ne devra être utilisé.  
- Aucun code CSS ne doit être appliqué via un attribut style dans une balise HTML.

# Identité graphique
- Polices des Logo & titres : Shrikhand  
Texte : Roboto  
- Couleurs  
Primaire : #9356DC  
Secondaire : #FF79DA  
Tertiaire : #99E2D0

# Compatibilité
Le site sera développé en utilisant l’approche mobile-first.  
Il devra donc être intégré en suivant les maquettes mobile, puis le responsive suivra pour les tablettes et ordinateurs en suivant les maquettes ordinateur données par notre designer.  https://www.figma.com/file/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?type=design&node-id=0-1&mode=design&t=1MILkCUgVw9kDXtT-0  
- L’ensemble du site devra être responsive sur mobile, tablette et desktop.  
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.  
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

# Effets graphiques et animations
Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie. Pour toutes les animations, afin de soigner le rendu du site, il est important que lorsque nous avons un effet au hover ou lors d’un clic, nous ayons l’effet inverse lorsque l’on quitte le survol.

# Boutons
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.  
L’ombre portée devra également être plus visible.  
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic.

# Page d’accueil
- Quand l’application aura plus de menus, un “loader” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

# Pages de menu
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront apparaître soit un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.  
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

# Livrables attendus
Page d’accueil (x1)  
- Affichage de la localisation des restaurants. À terme, il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.  
- Une courte présentation de l’entreprise.  
- Une section contenant les 4 menus sous forme de cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

Pages de menu (x4)  
- 4 pages contenant chacune le menu d’un restaurant.   
__Footer__  
- Le footer est identique sur toutes les pages.  
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.  
__Header__  
- Le header est présent sur toutes les pages.  
- Sur la page d’accueil, il contient le logo du site.  
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.


