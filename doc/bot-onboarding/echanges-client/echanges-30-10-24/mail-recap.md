## Objet : Remerciements et compte-rendu suite à notre rendez-vous du _30-10-24_

Bonjour Claire et Benjamin,

Nous tenons à vous remercier sincèrement pour le temps précieux que vous nous avez accordé lors de notre rencontre du **mercredi 30 octobre 2024 à 14h00**.

Ce fut un véritable plaisir d'échanger avec vous, et nous avons particulièrement apprécié la qualité de vos retours ainsi que votre vision claire du projet.

Vos réponses, idées et suggestions ont été extrêmement enrichissantes pour nous, et elles contribueront sans aucun doute à la réussite de ce projet.

Durant notre rendez-vous, nous avons discuté des points suivants :
- Le message des règles d'utilisation que le nouvel arrivant devra accepter.
- Le terme de fabrique et son possible changement.
- La possibilité que le projet soit également déployé dans des antennes Simplon d'autres régions.
- La possibilité de définir une date de début et de fin de validité d'une promotion lors de sa création dans Discord.
- La possibilité de renommer les rôles "admins" et "administrateur".
- Le droit futur donné à un formateur de créer de nouveaux posts et sa limite en terme de nombre.
- La possibilité d'ajouter un champ texte libre pour les nouveaux arrivants lors de leur demande d'identification.
- L'automatisation possible du formulaire d'identification en permettant à l'apprenant de sélectionner directement sa formation et sa promotion.
- La possibilité d'obtenir une copie du serveur Simplon HDF afin de pouvoir réaliser des essais dessus.
- Le fait que la suppression d'une formation entraine ou non automatiquement la suppression de sa formation associée.
- Le nombre de formations qui ont lieu en parallèle.
- La présentation d'un premier schéma que nous avons établi pour nous assurer que nous avons bien compris le flux de création d'une nouvelle promotion ainsi qu'un second schéma présentant une amélioration possible de ce flux. 

À l'issue de notre discussion, nous avons convenu des actions suivantes :
- L'amélioration de notre flux de création de formation suites aux différentes remarques concernant son fonctionnement et les améliorations possibles.
- Le début de travail des diagrammes Merise liés au projet
- Collaborer avec le bot feedback qui paramétrera une annonce une semaine avant la fin de la promotion pour signaler que le serveur va fermer un mois après la fin de la formation.


Nous avons également validé les éléments suivants pour le développement du bot:
- Les nouveaux arrivant devront cocher sur "J'ai lu et j'accepte les règles du serveur" lors de la lecture des règles du serveur.
- "Fabrique" devient "campus" dès maintenant, un terme à modifier dès à présent. De même les apprenants changeront également de nom, mais nous ne savons pas exactement lequel. ("Étudiants" il me semble non?)
- Le bot discord sera conçu en prenant en compte sa scalabilité.
- Lors de la création d'une promotion, y ajouter sa date de début et de fin. La promotion devra apparaître automatiquement au moment de sa date de début.
- Collaborer avec le bot feedback qui paramétrera une annonce une semaine avant la fin de la promotion pour signaler que le serveur va fermer un mois après la fin de la formation.
- Il n'y aura pas de changement pour le terme "admins" et "administrateur".
- Un formateur pourra créer de nouveaux posts, mais ce droit sera limité en quantité.
- Pour la gestion des identifications, le chargé de projet pourra envoyer un email d'invitation discord à ses apprenants, ils seront ainsi automatiquement identifiés. Ensuite, les apprenants pourront sélectionner leur formation et leur promotion; de fait, les admins / CDP n'auront plus qu'à vérifier et à valider.
- Aucun champ texte libre ne sera prévu lors de l'identification pour faciliter l'automatisation du processus.
- Du fait de l'architecture que devrait avoir le back-end, la suppression d'une formation entrainera forcément la suppression de sa formation associée.


Je vous confirme que nous avons bien pris en compte les remarques suivantes :
- La version V1 n'avait pas de scalabilité.
- Pour le moment aucun déploiement n'est prévu dans d'autre région, chaque région ayant ses propres règles de fonctionnement vis à vis du discord. Mais comme c'est une suite possible, le bot doit être développé de façon à ce qu'il ait une scalabilité au cas où le cas se présente.
- Ce sont les chargés de projet qui créent leurs promos sur discord.
- Il n'y a pas de champ de date prévu dans Discord, il faudra donc utiliser un champ de texte classique pour gérer les dates.
- La limite de nombre de posts que le formateur pourra créer n'a pas encore été définie.
- Claire apprécierait le fait d'avoir un pop up lui indiquant lorsqu'un apprenant d'une de ses formations souhaite rejoindre le discord.
- Un modèle de stock de forum serait préférable aux stock de channels.
- Plutôt que d'avoir la version présentielle et la version distantielle d'une formation comme deux entités séparées, il sera préférable de créer un template auquel on pourra aposer des ajustements pour le distantiel en cochant une case. Cela permettra d'éviter une redondance de données.
- En ce moment, l'antenne de Valenciennes compte à elle seule 5 formations dont 2 en sourcing. Compter qu'il y a également les antennes de Béthune, Lille, Boulogne-sur-Mer et possiblement Douai et Arras qui devrait s'ajouter prochainement. Ce nombre sera pris en compte dans la gestion des channels.
- Les forums sont inclus dans la limitation en quantité des channels.

Pour rappel, lors de cet entretien, vous avez convenu de :
- Nous envoyer le lien du serveur template si vous avez le temps de le paramétrer.
- Des accès à certaines parties du serveur seront données aux deux tech leads.

Si vous avez des réserves sur un des points évoqués plus haut, d'autres éléments à ajouter ou des sujets que vous souhaiteriez aborder lors de nos prochains échanges; n’hésitez pas à nous en faire part. Nous sommes très heureux de collaborer avec vous et sommes enthousiastes à l'idée d'avancer ensemble sur les prochaines phases du projet.

Nous restons bien entendu à votre disposition pour toute question complémentaire. Aussi, n'hésitez pas à revenir vers nous si vous avez besoin de précisions sur les points abordés lors de notre rendez-vous.

Dans l’attente de vous lire, nous vous souhaitons une excellente journée.

Bien cordialement,

**Aurore Reynier**

Le groupe Discord onboarding
