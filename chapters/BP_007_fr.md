## Respecter le principe de navigation rapide dans l’historique

### Identifiants

| GreenIT |  V2  |  V3  |  V4  |
|:-------:|:----:|:----:|:----:|
|   28   | 5  |  7 |      |

### Indications

| Degré de priorité |      Mise en oeuvre       |  Impact écologique    | 
|-------------------|:-------------------------:|:---------------------:|
| Conseillé         | Standard                  | Fort                  | 


|Ressources Economisées                                      |
|:----------------------------------------------------------:|
|Processeur / Réseau    |

### Règle

Les navigateurs possèdent une fonction de navigation rapide dans l’historique (boutons Page précédente et Page suivante). 
Grâce à cette fonction, il n’est pas nécessaire de redemander la page au serveur, puis de la recharger. 
On évite ainsi de consommer inutilement de la bande passante et de générer des requêtes HTTP supplémentaires.

Par conséquent, ne pas prévoir d’éléments qui rendent la page inutilisable après l’avoir quittée.

### Exemple

Éviter :
 - les boutons de formulaire qui se désactivent lors de la soumission ;
 - les menus qui ne fonctionnent plus après un clic ; 
 - les effets JavaScript qui font disparaître le contenu de la page lorsqu’on la quitte.

### Principe de validation

| Le nombre ...     | est inférieur ou égal à   |  
|-------------------|:-------------------------:|
| de pages / URLs ne respectant pas ce principe  |  10% |