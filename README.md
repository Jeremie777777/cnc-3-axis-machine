# Fraiseuse CNC 3 axes — conception et prototype en préparation

Ce dépôt documente la conception d’une fraiseuse CNC artisanale à trois axes et la préparation de son premier prototype.

## Dimensions prévues

- **Zone de travail visée :** 450 × 450 mm.
- **Dimensions maximales relevées sur le socle du modèle Fusion 360 :** 540 × 638 mm.

## Limites et évolutions envisagées

La conception prévoit deux axes ronds de **8 mm de diamètre** pour guider le portique mobile de l’axe Y. Cette faible section présente un risque de flexion sous le poids du portique.

Pour améliorer la rigidité, les pistes envisagées sont de passer à des axes de **12 mm de diamètre** ou mieux, d’utiliser des **rails de guidage linéaire avec chariots à billes** sur tout les axes. C'est la meilleure option.

![Rails de guidage linéaire et chariots à billes (illustration)](https://imtekmotion.com/wp-content/uploads/2025/11/IMTEK-linear-ball-guides-group.png)

Image : [IMTEK — comparaison des guides linéaires](https://imtekmotion.com/linear-guides-vs-linear-bushings-comparison/)

## État d’avancement

- **Conception CAO :** modèle de la machine réalisé dans Autodesk Fusion 360.
- **Pièces de fabrication :** les éléments du dossier **CNC_Fabrique** sont des composants enfants de la conception principale, prévus pour l’usinage. Ils ne constituent pas un projet séparé.
- **Matériel :** des composants majeurs ont été acquis. Une vidéo présente les matériels disponibles pour la mise au point du premier prototype ; leurs références et caractéristiques restent à détailler et vérifier.
- **Fabrication :** la machine complète n’a pas encore été construite. L’assemblage et la validation du prototype restent à réaliser.

## Visualiser l’assemblage dans Autodesk Fusion 360

[Ouvrir l’assemblage dans Autodesk Fusion 360](https://a360.co/4swDDnh)

## Vues de la conception Fusion 360

Les images ci-dessous montrent différentes vues du modèle CAO. Elles illustrent la conception et ne représentent pas une machine assemblée.

![Vue générale du modèle Fusion 360](Pictures/Fusion%20view.png)

![Vue de dessus de la machine](Pictures/Machine%20vue%20de%20dessus.png)

![Vue de face de la machine](Pictures/Machine%20vue%20de%20face.png)

![Vue de droite de la machine](Pictures/Machine%20vue%20de%20droite.png)

![Vue en perspective de la machine](Pictures/Machine%20vue%20en%20perspective.png)

## Démarche

1. Concevoir la structure et les composants de la machine en CAO.
2. Préparer les pièces destinées à la fabrication et réunir les composants nécessaires.
3. Assembler le prototype.
4. Régler les axes et la commande, puis documenter les essais et les améliorations.

Les étapes d’assemblage et d’essais sont à venir ; ce dépôt ne prétend pas qu’elles ont déjà été effectuées.

## Expérience préalable avec GRBL : mini traceur artisanal

Avant cette machine, j’ai réalisé un petit traceur artisanal pour me familiariser avec les commandes GRBL. Il s’agit d’un montage distinct, qui m’a servi d’apprentissage et ne représente pas la fraiseuse 3 axes présentée ici.

![Mini traceur artisanal — première vue](Pictures/Machine%20artisanale%20de%20prise%20en%20main_1.jpg)

![Mini traceur artisanal — deuxième vue](Pictures/Machine%20artisanale%20de%20prise%20en%20main_2.jpg)

## Matériels disponibles

Les photos et la vidéo ci-dessous montrent les composants disponibles pour préparer le premier prototype. Les dimensions exactes, références et caractéristiques électriques restent à relever avant la conception finale et le câblage.

Éléments identifiables sur les photos :

- vis trapézoïdales T8 et écrous/supports associés ;
- arbres de guidage de 8 mm et paliers linéaires SCS8UU ;
- moteurs pas à pas et accouplements ;
- supports de vis à roulement, avec des étiquettes visibles « KP08 horizontal » et « KP08 vertical » ;
- adaptateur portant l’indication ER11, dont la compatibilité reste à confirmer.

Les références exactes et les caractéristiques de ces pièces restent à vérifier. Les pilotes de moteurs pas à pas ne sont pas encore acquis ; la commande et les autres éléments électriques restent à définir.

<video src="Materiels%20disponibles.mp4" controls width="720"></video>

[Ouvrir ou télécharger la vidéo des matériels disponibles](Materiels%20disponibles.mp4)

### Photos des composants

<p align="center">
  <img src="Pictures/T8_screw.jpg" width="30%" alt="Vis trapézoïdale T8">
  <img src="Pictures/nut_and_housing.jpg" width="30%" alt="Écrous et supports de vis">
  <img src="Pictures/screw_bearing.jpg" width="30%" alt="Supports de vis à roulement">
</p>
<p align="center">
  <img src="Pictures/SCS8UU.jpg" width="30%" alt="Paliers linéaires SCS8UU">
  <img src="Pictures/8UU_and_Housing.jpg" width="30%" alt="Paliers et supports">
  <img src="Pictures/Axis_motion.jpg" width="30%" alt="Éléments de guidage et mouvement d’axe">
</p>
<p align="center">
  <img src="Pictures/Steppers_motor.jpg" width="30%" alt="Moteurs pas à pas">
  <img src="Pictures/Stepper_motor_and_couplers.jpg" width="30%" alt="Moteur pas à pas et accouplements">
  <img src="Pictures/Couplers_and_stepper_motor.jpg" width="30%" alt="Accouplements et moteur pas à pas">
</p>
<p align="center">
  <img src="Pictures/Screw_bearing_and_ER11_adapter.jpg" width="30%" alt="Support à roulement et adaptateur ER11">
  <img src="Pictures/accessories.jpg" width="30%" alt="Accessoires disponibles">
</p>

## Contenu du dépôt

- captures de la conception Fusion 360 ;
- images du mini traceur utilisé pour la prise en main de GRBL ;
- photos des matériels disponibles ;
- vidéo des matériels disponibles ;
- nomenclature des composants avec références et caractéristiques vérifiées (à compléter) ;
- photos de l’assemblage, résultats d’essais et améliorations du prototype à ajouter après réalisation.
