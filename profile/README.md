# Stend

Stend est un projet visant à être l'une des meilleures solutions pour configurer son propre service de partage de fichiers. Il a été conçu pour être aussi complet que la plupart des services propriétaires, mais avec une facilité d'installation et de configuration incomparable aux autres projets open-source.

Cette organisation contient le code source des différents projets en lien avec Stend, vous pouvez avoir des informations sur chacun d'entre eux via la [documentation](https://stend.johanstick.fr/).

![Accueil](https://stend.johanstick.fr/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fstend_web_homedemo.5c70690e.png&w=1920&q=100)
*illustration : client web*


## Pourquoi utiliser Stend ?

Stend se veut être un service de partage de fichiers simple et rapide. Voici les principaux avantages de ce service :
* **Contrôle total :** en hébergeant Stend sur votre propre serveur, vous avez un contrôle total sur vos fichiers, et vous pouvez les supprimer à tout moment.
* **Confidentialité :** vos données restent sur votre infrastructure. Aucune donnée n'est envoyée à des tiers, aucun service de suivis n'est utilisé, aucune publicité n'est affichée.
* **Sécurité :** vous pouvez configurer l'utilisation ou non d'un mot de passe, qui sera nécessaire pour créer un transfert.
* **Gratuité :** Stend est un projet open-source et gratuit. Vous pouvez l'utiliser sans aucune restriction, et même le modifier si vous le souhaitez.
* **Facilité d'installation :** Stend est conçu pour être facilement installable sur n'importe quel serveur. Vous pouvez l'installer en quelques minutes seulement.
* **API ouverte :** Stend propose une API ouverte, documenté et simple d'utilisation. Vous pouvez l'utiliser pour automatiser l'envoi ou le téléchargement de fichiers, ou même pour développer votre propre client tiers.


## Pourquoi Stend est né ?

Stend est né d'un constat assez simple : au moment du développement, aucun service de partage de fichiers open-source et hébergeable sur son propre serveur ne proposait une expérience utilisateur satisfaisante ainsi qu'une facilité d'installation de même niveau. Les solutions propriétaires sont parfois trop chères ou pas assez complètes, et les solutions open-source sont souvent trop compliquées à installer ou à utiliser.

Stend a donc été créé afin de régler plusieurs problèmes :
* Remplacer les solutions propriétaires (Wetransfer, Swisstransfer, ...).
* Devenir une alternative viable aux solutions open-source déjà existantes (Firefox Send, ...).
* Respecter les données et la vie privée des utilisateurs.
* Ne pas être dépendant de services tiers.
* Être facilement installable, et complètement gratuit.
* Proposer une limite de taille de fichier plus élevée (dépend de la configuration de votre serveur) :

| Service | Taille maximale |
| :------ | :-------------- |
| Stend | Définissez vos propres limites |
| Free Transfert | Illimitée si abonné Free, sinon 10 Go |
| Swisstransfer | 50 Go |
| Wetransfer | 2 Go |
| Smash | 2 Go |


## Dépôts principaux

- [API](https://github.com/hoststend/stend-api) ― [Documentation](https://stend.johanstick.fr/api-docs/intro)
- [Serveur global](https://github.com/hoststend/stend-globalserver) ― [Documentation](https://stend.johanstick.fr/global-server/intro)
- [Client WEB](https://github.com/hoststend/stend-web) ― [Documentation](https://stend.johanstick.fr/web-docs/intro)
- [Client mobile](https://github.com/hoststend/stend-mobile) ― [Documentation](https://stend.johanstick.fr/mobile-docs/intro)
- [Client terminal](https://github.com/hoststend/stend-cli) ― [Documentation](https://stend.johanstick.fr/cli-docs/intro)
