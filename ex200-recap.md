# Serie 7

## Chaîne
Ecrire une fonction qui transforme une chaîne de caractères en minuscule.

## length
Ecrire une fonction qui retourne la longueur d'une chaîne passée en paramètre sans utiliser `strlen`.

## Swap
Ecrire une fonction qui échange deux valeurs entières 16bits signées passées en paramètre

## Bit
Donner une expression qui force le bit #2 d'une valeur à 1

## argv
Affiche version sur la sortie standard si
--version est présent dans un des arguments
void fonc(int argc, char* argv){
}


# Circuit RC

Dans cet exercice, il faut calculer la tension aux bornes d'un condensateur
dans un circuit RC.

Les données du circuit sont :
- `R = 100 [ohm]`
- `C = 1 [mF]`

Pour les calculs, l'incrément de temps sera de `1 [us]`. 

À la fin de chaque étape, affichez :
- le temps,
- le courant,
- la tension.

## Étape 1
Le circuit est alimenté avec une tension de `5 [V]` pendant `100 [ms]` 

## Étape 2
La tension passe à `10 [V]`, jusqu'à ce que le temps total soit de `200 [ms]`.

## Étape 3
La tension passe à `0.6 [V]`.  
Après le changement de tension, combien de temps faut-il pour que la tension
aux bornes du condensateur soit plus petite que `1.2 [V]` ?

## Étape 4
Calculer l'énergie dissipée par la résistance et afficher la valeur pour chaque étape.



# Déplacement

La consommation d'un engin propulsé se déplaçant à `25 km/h` est donnée par la formule suivante :
`c = 30 + m * 1.6 [l / km]` ou `m` est la masse totale du véhicule.

La masse du véhicule est de 1500 kg plus le carburant.

La masse volumique du carburant est de `1500 [kg/m3]`

Quelle distance il peut parcourir en partant avec 50 litres de carburant.


# Chute 

Un objet de 80 kg et lâché avec une vitesse initiale nulle.

Sa force de frottement vaut `F = k * v`  
avec `k=34`

`F = m*a => m*g - k*v = m*a` 

Quelle est la vitesse maximale de l'objet ?

Combien de temps met l'objet pour tomber de `500 m` ?

Après combien de temps la vitesse de l'objet est stable ?