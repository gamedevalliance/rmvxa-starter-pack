# RPG Maker VX Ace Starter Pack

RPG Maker VX Ace Starter Pack est un projet regroupant un panel complet d'exemples afin de guider et inspirer les débutants dans la création de leur jeu.

[Télécharger la dernière version.](https://github.com/rpgmakeralliance/rmvxa-starter-pack/releases)

[![Capture d'écran](https://i.imgur.com/gJZirk0.png)](https://github.com/rpgmakeralliance/rmvxa-starter-pack/releases)

# Contribuer

Ce guide explique comment proposer du contenu au Starter Pack. En résumé, vous allez apprendre à créer une copie du projet, et à envoyer uniquement les fichiers modifiés, et tout cela avec GitHub pour faciliter la fusion des contributions de chacun.

Installez [GitHub Desktop](https://desktop.github.com/) et connectez-vous au logiciel avec votre compte GitHub.

## Vous ne possédez pas les droits sur `rpgmakeralliance/rmvxa-starter-pack`

Créez une copie de `rpgmakeralliance/rmvxa-starter-pack` sur votre compte en cliquant sur le bouton Fork en haut de la page.

Clonez votre fork sur GitHub Desktop.

![Cloner](https://i.imgur.com/OjORmKq.png)

## Vous possédez les droits sur `rpgmakeralliance/rmvxa-starter-pack`

Clonez directement `rpgmakeralliance/rmvxa-starter-pack`.

Sur GitHub Desktop, créez une nouvelle branche indiquant votre nom ou le contenu que vous ajoutez, pour plus de clarté.

![Branches](https://i.imgur.com/Fq6Tt0f.png)

Merci de ne jamais éditer la branche `master` sans avoir eu le feu vert d'Aurélien, afin d'éviter tout risque de perte de données.

## Suite du guide

Ouvrez le projet dans RPG Maker, faites vos ajouts dans une des maps de réserve inutilisées, puis sauvegardez.

Vous remarquerez ensuite que dans GitHub Desktop, la liste des fichiers modifiés s'affiche. Dans cet exemple, j'ai seulement modifié la map 60 avant de sauvegarder.

![Liste des modifications](https://i.imgur.com/0tXhVxn.png)

Pourtant, de nouveaux fichiers MapInfos et System ont été générés. RPG Maker le fait obligatoirement et nous ne pouvons pas l'éviter. Ces fichiers ne peuvent pas être fusionnés facilement car les .rvdata2 sont cryptés. Vous devez les envoyer uniquement si vous les avez modifiés, ou cela pourrait faire perdre des données lors de la fusion.

Concrètement, si vous modifiez uniquement des maps, vous devez annuler les changements de MapInfos, System, et tout autre fichier ne concernant pas vos maps.

![Discard changes](https://i.imgur.com/Z3y1EoS.png)

Lorsqu'il ne reste plus que les fichiers utiles, ajoutez un titre à votre mise à jour, listez les ID des maps modifiées dans la description, puis faites un commit.

![Commit](https://i.imgur.com/Hc0xwNY.png)

En haut à droite, le bouton Actualiser s'est transformé en un bouton Envoyer. Vous n'avez plus qu'à cliquer dessus, et voilà !

Si vous avez un doute à ce sujet, contactez Aurélien sur le Discord de RPG Maker Alliance, qui vous répondra très vite.

## Crédits

RPG Maker VX Ace Starter Pack est une initiative de No0ony. Toutes les personnes alimentant ce projet sont bénévoles.

Les cartes, systèmes et autres éléments du projet sont **réutilisables librement sans citer l'auteur d'origine**.

Les rayons du soleil dans le dossier `Graphics/Pictures` sont réalisés par **Benben**, et distribués en open source, ce qui signifie qu'ils sont **modifiables et réutilisables librement**.

![Capture d'écran](https://i.imgur.com/AgFm0Qj.png)
