# Coronalab

Dépot de différents projets réalisés durant la pandémie du covid19.

# Lunette de protection CHUV
 
Réalisée sur la base des cotes réelles de celle utilisée (voir fichiers frame_scan.pdf et glasses_scan.pdf)

![Frame](frame.jpg "Frame rendering")

- Monture - 
	- fichier stl (unité: mm): [glasses_frame.stl](glasses_frame.stl)
	- code source du dessin, Alibre Design ou Atom3D: [glasses_frame.AD_PRT](glasses_frame.AD_PRT)
	- dessin au format STEP AP 242: [glasses_frame_step_ap_242.stp](glasses_frame_step_ap_242.stp)
	- fichier stl test (modélisation OpenSCAD): [glasses_frame_test.stl](glasses_frame_test.stl)

- Visière -
	- fichier svg (unité: mm): [glasses_lenses.svg](glasses_lenses.svg)
	- fichier dxf (unité: mm): [glasses_lenses.dxf](glasses_lenses.dxf)

Cette visière doit être découpée dans une feuille transparente de 0.20 mm d'épaisseur.

Nous cherchons la meilleure matière disponible pour cette réalisation (PETG ou Acrylique)

## Assemblage

<img src="glasses_assembled.jpg" width="400" />

## Données de fabrication reçu de la part de la centrale d'achat commune CHUV/HUG

- Le but actuel est de rester dans le modèle connu par le personnel médical (Safeview) et de ne pas rajouter une contrainte supplémentaire en changeant par des visière complète
- Le matériel n'est absolument pas stérile
- Les visières des lunettes sont traitées comme des consommables, sauf actuellement ou elles sont quelque peu réutilisées dans le temps
- Les montures elles sont conservées un peu plus mais tout de même consommées 
- Les chiffres nets en demande pour les HUG/CHUV sont : **3600 montures/sem. & 7400 visières de lunettes/sem**.
- Toutes les montures sont en taille unique
- La couleur n'importe pas du tout 
- Tous les traitement n'excède pas la température corporelle donc la fabrication en PLA est tout à fait acceptable
- Les matériaux compatibles avec le contact humain sont tous acceptés
- Nous partons à l'heure actuelle avec le modèle des lunettes, mais eux vont réétudier la question de passer sur le modèle shield voire un shield sur mesure (demi-visière p.ex.)

## Temps de fabrication estimés

https://github.com/FabLabRenens/Coronalab/blob/master/production_estimation.md

# Visière faciale

Nous pensions découper la visiere conçue par Konrad Klepacki et Mateusz Dyrda.
https://hackaday.io/project/170481-laser-cut-medical-shield

- Nous n'avons pas testé
	- VF/Assembly Instruction.pdf
	- VF/medical_shield_petg_05mm_SingleSheet.pdf
	


