# Bourgenais2015
Ce site contient les liens vers le matériel qui a été utilisé lors de l'EPU organisé par la [SFPM](http://www.sfpm.asso.fr/) à Port-Bourgenay les 7-9 octobre 2015.

Les notebooks présentés lors de cet EPU se sont largement inspirés de ceux trouvés [içi](http://insightsoftwareconsortium.github.io/SimpleITK-Notebooks/).

## Note aux utilisateurs macOSX el Capitan:
Suite à la mise à jour de votre OS en version 10.11 (El Capitan), l'importation de votre ancienne configuration ne semble pas fonctionner correctement et que vous soyez obliger de faire une nouvelle installation proprement. Or, la commande **sudo** avec El Capitan ne permettrait pas les mêmes facilités d'installation. La solution consiste à créer au préalable un environnement virtuel grâce à la commande virtualenv récupérée par exemple avec un pip install.

>cd virtualenv nomdelenvironnement

>source nomdelenvironement/bin/activate

>pip install python (simpleITK, etc, ...)

(merci à François Gardaveau pour avoir fourni la nouvelle procédure).
