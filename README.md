# Coronalab

Dépot de différents projets réalisés durant la pandémie du covid19.

# Lunette de protection CHUV
 
Réalisée sur la base des cotes réelles de celle utilisée (voir fichiers frame_scan.pdf et glasses_scan.pdf)

![Frame](frame.jpg "Frame rendering")

- Monture - 
	- fichier stl (unité: mm): [glasses_frame.stl](glasses_frame.stl)
	- code source du dessin, Alibre Design ou Atom3D: [glasses_frame.AD_PRT](glasses_frame.AD_PRT)
	- dessin au format STEP AP 242: [glasses_frame_step_ap_242.stp](glasses_frame_step_ap_242.stp)
	- profil 2D: [dxf 14](glasses_frame.dxf) et [svg](glasses_frame.svg) (en cas de doutes sur l'échelle/les unités utilisées: largeur totale de l'objet réel 121.4 mm)
	- fichier stl test (modélisation OpenSCAD): [glasses_frame_test.stl](glasses_frame_test.stl)

- Visière -
	- fichier svg (unité: mm): [glasses_lenses.svg](glasses_lenses.svg)
	- fichier dxf (unité: mm): [glasses_lenses.dxf](glasses_lenses.dxf)

Cette visière doit être découpée dans une feuille transparente de 0.20 mm d'épaisseur.

Nous cherchons la meilleure matière disponible pour cette réalisation (PETG ou Acrylique)

## Assemblage

<img src="glasses_assembled.jpg" width="400" />

## Données de fabrication reçues de la part de la centrale d'achat commune CHUV/HUG

### Point du 01/04/2020

- Le besoin actuel en montures-visières a été revu à la baisse à 4500 unités chacunes en commande réel (point de ce jour avec la centrale d'achat) par semaine au lieu des 7400 précédemment évoqués.
- La raison principale est qu'ils ont acheté des nouvelles lunettes plus conséquente et stérilisable à plusieurs reprises.
- Les matériaux actuels des montures sont du PP et du PE pour la partie visière donc cela confirme que le PLA est acceptable d'un point de vue thermique.
- Les Shields ne sont définitivement pas envisagés au CHUV. Cependant, les HUG évaluent encore cette solution.
- Les prototypes de Renens seront amenés à une personne de contact très prochainement pour être validés par la centrale d'achat et autres personnes compétentes.
- D'un point de vue légal et pour répondre à la question d'un autre FabLab, la centrale d'achat des HUG/CHUV n'achète QUE du matériel conforme CE. Et doit donc encore se positionner sur ce point. Ceci est potentiellement le cas de beaucoup d'autres hôpitaux et centre de soins.
- Notre but n'étant pas de prendre des parts de marché, mais de faire fonctionner un système qui pourrait être/devenir dysfonctionnant (chaîne d'approvisionnement rompue, etc.) nous resterons en attente d'une demande formelle pour approvisionner en masse ces deux hôpitaux.

### Point du 26/03/2020

- Le but actuel est de rester dans le modèle connu par le personnel médical (Safeview) et de ne pas rajouter une contrainte supplémentaire en changeant par des visières complètes
- Le matériel n'est absolument pas stérile
- Les visières des lunettes sont traitées comme des consommables, sauf actuellement ou elles sont quelques fois réutilisées
- Les montures elles sont conservées un peu plus mais tout de même consommées 
- Les chiffres nets en demande pour les HUG/CHUV sont : **3600 montures/sem. & 7400 visières de lunettes/sem**.
- Toutes les montures sont en taille unique
- La couleur n'importe pas du tout 
- Tous les traitements n'excèdent pas la température corporelle donc la fabrication en PLA resterait acceptable
- Les matériaux compatibles avec le contact humain sont tous acceptés
- Nous partons à l'heure actuelle avec le modèle des lunettes, mais eux vont réétudier la question de passer sur le modèle shield voire un shield sur mesure (demi-visière p.ex.)

## Temps de fabrication estimés

https://github.com/FabLabRenens/Coronalab/blob/master/production_estimation.md

# Visières faciales

Nous pensions découper la visiere conçue par Konrad Klepacki et Mateusz Dyrda.
https://hackaday.io/project/170481-laser-cut-medical-shield
Cette visière présente l'avantage d'être produite uniquement par découpage de feuilles de PETG de 0.5 mm d'épaisseur.

- Nous ne l'avons pas testée : les fichiers sont dans le répertoire VF

Nous pouvons utiliser le même film de 130 ou 180 microns employé pour les lunettes avec ce modéle de structure :
https://www.myminifactory.com/fr/object/3d-print-115247?fbclid=IwAR2c9N3aFWIlBcmv_PWLbtqA287igzUk3-ZPRXvf5xEHGqIFypm60IjLfNA

- [newshieldsupport-org-notext.stl]
	


