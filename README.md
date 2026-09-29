# Mon carnet

Application web autonome pour suivre des routines, noter des observations et conserver des situations particulières avec leurs pistes.

## Utilisation

Ouvrir `index.html` dans un navigateur. Les données sont enregistrées localement dans ce navigateur. Dans **Paramètres**, exporter régulièrement une sauvegarde complète JSON et l'importer pour changer de navigateur ou d'adresse.

## Déploiement sur Vercel

Importer ce dépôt Git dans Vercel avec le préréglage **Other** (site statique). Aucun framework ni commande de compilation n'est nécessaire : `index.html` se trouve à la racine. Les mises à jour du dépôt pourront ensuite être publiées dans le même projet Vercel.

## Données personnelles

Ce dépôt contient uniquement l'application générique. Ne pas y ajouter de journaux ou de sauvegardes personnelles. Après la mise en ligne, importer la sauvegarde JSON depuis le téléphone dans la page **Paramètres**.

L'application utilise la clé locale `mon-carnet-v1`. La conserver lors de futures modifications évite de rendre les données existantes invisibles. L'adresse du site doit également rester la même, car le stockage du navigateur dépend de son origine.
