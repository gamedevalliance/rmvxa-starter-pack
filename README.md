# RPG Maker VX Ace Starter Pack

RPG Maker VX Ace Starter Pack is a project including tons of examples to guide and inspire beginners in the creation of their game.

[Download the latest version.](https://gamedevalliance.itch.io/starterpack)

[Chat with us on our FR & EN Discord server.](https://discord.gg/RrBppaj)

# Contribuer

Ce guide explique comment proposer du contenu au Starter Pack. En résumé, vous allez apprendre à créer une copie du projet, et à envoyer uniquement les fichiers modifiés, tout cela avec GitHub pour faciliter la fusion des contributions de chacun.

Installez [GitHub Desktop](https://desktop.github.com/) et connectez-vous au logiciel avec votre compte GitHub.

## Si vous n'avez pas les droits sur `gamedevalliance/rmvxa-starter-pack`

Créez une copie de `gamedevalliance/rmvxa-starter-pack` sur votre compte en cliquant sur le bouton Fork en haut de la page.

Clonez votre fork sur GitHub Desktop.

![Cloner](https://i.imgur.com/OjORmKq.png)

## Si vous avez les droits sur `gamedevalliance/rmvxa-starter-pack`

Clonez directement `gamedevalliance/rmvxa-starter-pack`.

Sur GitHub Desktop, créez une nouvelle branche, que vous pouvez appeler par votre nom par exemple.

![Branches](https://i.imgur.com/Fq6Tt0f.png)

Merci de ne jamais éditer la branche `master` sans avoir eu le feu vert d'Aurélien, afin d'éviter tout risque de perte de données.

## Suite du guide

Ouvrez le projet dans RPG Maker, faites vos ajouts dans les maps de réserve inutilisées, puis sauvegardez.

Vous remarquerez ensuite que dans GitHub Desktop, la liste des fichiers modifiés s'affiche. Dans cet exemple, j'ai seulement modifié la map 60 avant de sauvegarder.

![Liste des modifications](https://i.imgur.com/0tXhVxn.png)

Pourtant, de nouveaux fichiers MapInfos et System ont été générés. RPG Maker le fait obligatoirement et nous ne pouvons pas l'éviter, malheureusement. Ces fichiers ne peuvent pas être fusionnés facilement car les .rvdata2 sont cryptés. Pour une fusion sans accroc, vous devez les envoyer uniquement si vous les avez modifiés, ou nous pourrions perdre des données.

Concrètement, si vous modifiez uniquement des maps, vous devez annuler les changements de MapInfos, System, et tout autre fichier ne concernant pas vos maps. Pour cela, faites un clic droit, Discard changes, puis confirmez.

![Discard changes](https://i.imgur.com/Z3y1EoS.png)

Ensuite, donnez un titre à votre mise à jour, détaillez dans la description (renseignez notamment les ID des maps modifiées), puis cliquez sur commit.

![Commit](https://i.imgur.com/Hc0xwNY.png)

En haut à droite, le bouton Actualiser s'est transformé en un bouton Envoyer. Vous n'avez plus qu'à cliquer dessus, et voilà !

Si vous avez un doute sur ce procédé, contactez Aurélien sur le Discord de RPG Maker Alliance, qui vous répondra très vite.

## Crédits

RPG Maker VX Ace Starter Pack est une initiative de No0ony. Toutes les personnes alimentant ce projet sont bénévoles.

Les cartes, systèmes et autres éléments du projet sont **réutilisables librement sans citer l'auteur d'origine**.

Les rayons du soleil dans le dossier `Graphics/Pictures` sont réalisés par **Benben**, et distribués en open source, ce qui signifie qu'ils sont **modifiables et réutilisables librement**.
