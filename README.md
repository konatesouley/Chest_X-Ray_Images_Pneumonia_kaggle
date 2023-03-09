# Chest_X-Ray_Images_Pneumonia_kaggle
Dev Deep Learning for Pneumonia detection

# Contexte
http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

Figure S6. Exemples illustratifs de radiographies pulmonaires chez des patients atteints de pneumonie, liés à la figure 6 La radiographie pulmonaire normale (panneau de gauche) représente des poumons clairs sans aucune zone d’opacification anormale dans l’image. La pneumonie bactérienne (au milieu) présente généralement une consolidation lobaire focale, dans ce cas dans le lobe supérieur droit (flèches blanches), tandis que la pneumonie virale (à droite) se manifeste par un schéma « interstitiel » plus diffus dans les deux poumons. http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

# Contenu
Le jeu de données est organisé en 3 dossiers (train, test, val) et contient des sous-dossiers pour chaque catégorie d’image (Pneumonie/Normal). Il y a 5 863 images radiographiques (JPEG) et 2 catégories (pneumonie/normale).

Les radiographies thoraciques (antéro-postérieures) ont été sélectionnées à partir de cohortes rétrospectives de patients pédiatriques âgés de un à cinq ans du Guangzhou Women and Children’s Medical Center, Guangzhou. Toutes les radiographies pulmonaires ont été effectuées dans le cadre des soins cliniques de routine des patients.

Pour l’analyse des radiographies pulmonaires, toutes les radiographies pulmonaires ont d’abord été examinées pour le contrôle de la qualité en supprimant tous les scans de faible qualité ou illisibles. Les diagnostics des images ont ensuite été notés par deux médecins experts avant d’être autorisés à former le système d’IA. Afin de tenir compte des éventuelles erreurs de notation, l’ensemble d’évaluation a également été vérifié par un troisième expert.

# Objectif
Dans cette étude, nous allons chercher à développer un algorithme d’apprentissage (par transfert) efficace pour traiter les images médicales afin de fournir un diagnostic précis et opportun de la pathologie clé dans chaque image. L’illustration principale de cette technique impliquait des images de tomographie par cohérence optique (OCT) du thorace.
