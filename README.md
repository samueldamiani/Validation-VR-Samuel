# Validation-VR-Samuel

# Plage astrale

Ce projet de validation interne vise à créer une scène en réalité virtuelle sur A-frame. Mon projet a pour base une île entouré d'un océan où le joueur peut utiliser des pierres pour bouger une lune artificielle. Deux animations sont possible grâce aux pierres et une dernière est possible grâce au poulpe qui est caché dans l'océan. La lune s'abbat sur le poulpe afin de le terrasser. 

Ce projet a pour objectif d'utiliser premièrement le nouveau componenet a-ocean et d'utiliser divers modèles gltf pour créer un environement crédible. Le deuxième est d'utiliser le principe d'animation et de bouger des objets en en regardant d'autres. 

<img width="1406" alt="Capture d’écran 2022-06-14 à 13 46 33" src="https://user-images.githubusercontent.com/107631097/174089270-435771f0-9cfa-448f-b65a-4de59c151025.png">
<img width="1512" alt="Capture d’écran 2022-06-16 à 15 58 54" src="https://user-images.githubusercontent.com/107631097/174089281-ed1a7f80-2180-4631-8681-0d079b3e5e61.png">
<img width="1420" alt="Capture d’écran 2022-06-16 à 16 00 58" src="https://user-images.githubusercontent.com/107631097/174089337-0ae702c8-6784-4fe6-b4e7-b09e3ffa417d.png">

# Nouveaux components

J'ai eu recours à des nouveaux components créer par d'autres utilisateurs pour faire ma scène. Le premier est le component a-ocean (https://github.com/Dante83/a-water) qui m'a servi à créer un océan animé infini pour ma scène. Le deuxième à été le component a-sun-sky que j'ai repris d'un exemple utilisé pour a-ocean qui m'a permis à poser un ciel avec un soleil que j'ai couché en changeant sa position pour avoir un effet de début de soirée. Le troisième à été le component event-set (https://github.com/supermedium/superframe/tree/master/components/event-set) pour pouvoir attribuer des animations aux objets en intéragissant avec d'autres. 

Pour créer ma scène, j'ai également téléchargé des modèles gltf dont l'île que j'ai modifié sur blender pour enlever l'eau présent sur le modèle 3d qui empechait de bien s'adapter au milieu de mon océan.

# Contexte de développement

Ce projet a été développé par Samuel Damiani (Prorgamme à option; Bachelor en lettres) dans le cadre du cours "Réalité virtuelle et augmenté (2022)" dispensé par Isaac Pante (UNIL). 
