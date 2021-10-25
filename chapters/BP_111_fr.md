## Préférer le texte brut au HTML

### Identifiants

| GreenIT |  V2  |  V3  |  V4  |
|:-------:|:----:|:----:|:----:|
|   104   | 112  | 111  |      |

### Indications

| Degré de priorité |      Mise en oeuvre       |  Impact écologique    | 
|-------------------|:-------------------------:|:---------------------:|
| Prioritaire       |  Facile                   |    Fort               | 


|Ressources Economisées                                      |
|:----------------------------------------------------------:|
|  Réseau / Requêtes  |

### Règle

Lorsqu’une notification, une alerte ou un message de confirmation doit être envoyé par e-mail à l’utilisateur, préférer, quand c’est pos- sible, du texte brut au code HTML.

### Exemple

L’envoi d’un e-mail de confirmation de prise en compte d’une demande de contact ne justifie pas l’ajout de code HTML et d’images.
Un message HTML basique utilise en moyenne :
 - au moins 2 images (le logo et une signature en bas de page), soit 10 Ko environ ;
 - 12 Ko de code HTML pour la mise en page (styles inline, tableaux...) ;
 - 4 Ko de texte (le message + 2 liens d’action).

Au final :
 - e-mail HTML = 26 Ko ;
 - e-mail text brut = 4 Ko.

Soit un gain de 22 Ko par e-mail envoyé.
Dans le cas d’un site transactionnel avec, par exemple, des alertes clients et internes, le gain potentiel devient considérable.


### Principe de validation

| Le nombre ...     | est inférieur ou égal à   |  
|-------------------|:-------------------------:|
| de courriels envoyés par l'URL au format HTML  |  25% |