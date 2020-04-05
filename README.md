# Coronalab

**Dépot de différents projets réalisés durant la pandémie du covid19.**

## Lunettes de protection | _Protective glasses_

Lunettes de protection utilisées en milieu hospitalier. Modèle réalisé à la demande des hôpitaux universitaires afin d'assurer la continuité de l'approvisionnement avec l'aide des fablab, makerspace et tiers-lieux en mesure de contribuer.

Le modèle est composé d'une **monture** à imprimer en 3D (FDM) ainsi que d'une **visière** découpée dans un film en polyester d'une épaisseur comprise entre 0.130 et 0.200 mm.


<img src="media/frame.jpg" width="200" />*+*
<img src="media/thumb_frame_lenses.png" width="200" />*=*
<img src="media/glasses_assembled.jpg" title="prototype imprimé et découpé par Matthieu Borgognon" width="200" />


Après une phase initiale de récolte d'informations, de prototypage et de test (lire [l'historique des points de situation](https://github.com/FabLabRenens/Coronalab/wiki/Historique)), il est temps de passer à la **production**.

## Pourquoi ce projet ?

Ces lunettes répondent à une demande précise et donc à un besoin avéré des responsables du CHUV (Lausanne-Vaud) et des HUG (Genève), qui sont confrontés à la menace d'une pénurie puisque en ce moment l'approvisionnement par les canaux habituels est fortement perturbé voire impossible.
Elles sont utilisées par presque tous les services, au delà de ceux qui sont directement confrontés aux cas avérés de COVID-19. La situation actuelle menace d'aboutir à une pénurie qui affecterait l'ensemble des services.

Cet [article sur le site du fablab Renens](http://www.fablab-renens.ch/news/covid19-que-faisons-nous/) illustre le chemin qui nous a amené jusqu'ici.

## En quoi consiste notre engagement ?

Les besoins évoluent sans cesse, mais actuellement ils sont chiffrés à 700 montures et 4500 visières **par semaine**.


Pour la découpe des **visières** nous essayons en priorité d'avoir recours à de l'**équipement industriel** (découpeuses à lames), capable de produire plus aisément dans les volumes requis. En fonction de l'évolution des besoins, difficile à anticiper, une mise à contribution des découpeuses laser de nos labs et spaces pourrait être envisageable. Les fichiers pour la découpe sont disponibles en [svg](glasses/glasses_lenses.svg) et [dxf](glasses/glasses_lenses.dxf) (unité: mm)



### Impression en 3D des **montures**

Le modèle est ici: [glasses_frame.stl](glasses/glasses_frame.stl) (unité: mm).
Nous l'avons testé en PETG et PLA. Le modèle en PETG a été validé par le CHUV, celui en PLA pas encore.
En principe l'ABS doit aussi être possible.
Sur la plupart des machines FDM les plus courantes il est possible d'arranger jusqu'à 4 montures par batch d'impression.

Il y a aussi des [fichiers avec profiles prêts à l'emploi](https://github.com/FabLabRenens/Coronalab/wiki/Print-profiles). La liste est destinée à s'étouffer, merci de nous envoyer vos profiles à fablab_renens_su@googlegroups.com.

Les fichiers suivants sont également disponibles:

- code source du dessin, Alibre Design ou Atom3D: [glasses_frame.AD_PRT](glasses/glasses_frame.AD_PRT), et dessin 2D y relatif [glasses_frame.AD_DRW](glasses/glasses_frame.AD_DRW).

- profil 2D: [dxf 14](glasses/glasses_frame.dxf) et [svg](glasses/glasses_frame.svg) (en cas de doutes sur l'échelle/les unités utilisées: largeur totale de l'objet réel 121.4 mm)
- dessin au format STEP AP 242: [glasses_frame_step_ap_242.stp](glasses/glasses_frame_step_ap_242.stp)

| 👉 | Pour toute question contactez-nous:  fablab_renens_su@googlegroups.com |
|----| :-------:|


## Visières faciales intégrales

Nous pensions découper la visiere conçue par Konrad Klepacki et Mateusz Dyrda.
https://hackaday.io/project/170481-laser-cut-medical-shield
Cette visière présente l'avantage d'être produite uniquement par découpage de feuilles de PETG de 0.5 mm d'épaisseur.

- Nous ne l'avons pas testée : les fichiers sont dans le répertoire VF

Nous pouvons utiliser le même film de 130 ou 180 microns employé pour les lunettes avec ce modéle de structure :
https://www.myminifactory.com/fr/object/3d-print-115247?fbclid=IwAR2c9N3aFWIlBcmv_PWLbtqA287igzUk3-ZPRXvf5xEHGqIFypm60IjLfNA

- [newshieldsupport-org-notext.stl](ns/newshieldsupport-org-notext.stl)
	


