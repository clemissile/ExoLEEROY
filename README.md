# Exercice Footer

## Développement

Le projet utilise ParcelJS pour simplifier le développement local.

Pour installer [ParcelJS](https://en.parceljs.org/getting_started.html), utiliser Yarn :

    yarn global add parcel-bundler

Pour démarrer le projet en local, executer les commandes suivantes dans le dossier de l'exercice:

    yarn install
    yarn start

> Un serveur local va se lancer à l'adresse: http://localhost:1234

---

## Consignes

### Intégrer le HTML et CSS

> Les maquettes sont fournis dans le dossier Maquettes, 3 formats sont disponibles Desktop, Tablet et Mobile.

-   [ ] Intégrer le HTML.
-   [ ] Intégrer le SCSS.
-   [ ] Utiliser le/les images du dossier /assets/images.
-   [ ] Intégrer l'adresse fournie.
-   [ ] Intégrer les icons sociaux avec des icons fontawesome (Fontawesome est déjà disponible dans le projet) et des liens href autour de chacun d'eux.
-   [ ] Respecter le responsive Desktop / Tablet / Mobile (Bootstrap est déjà disponible dans le projet).

    ***

### VueJS

-   [ ] Finir le component SubscriptionForm VueJS.
-   [ ] Empêcher la soumission du formulaire si le champs email est invalide.
-   [ ] Empêcher le rechargement de la page à la soumission du formulaire.
-   [ ] La fonction `subscribe()` doit uniquement s'executer lorsque les 2 conditions précédentes sont remplies.
-   [ ] La fonction `subscribe()` doit contenir un `console.log()` qui loggue un message de succès et l'email de l'utilisateur.

    ***

### Rendu final

-   [ ] Builder le projet grâce à la commande `yarn build`
-   [ ] Déposer le projet sur un git et me renvoyer le lien.

---

## Assets

### Maquettes

Version Desktop

![Version Desktop](Maquettes/Desktop.png 'Version Desktop')

---

Version Tablet

![Version Tablet](Maquettes/Tablet.png 'Version Tablet')

---

Version Mobile

![Version Mobile](Maquettes/Mobile.png 'Version Mobile')

---

### Couleurs

-   `grey: #f1f1f1`
-   `berry: #871262`
-   `text: #333f48`

---

### Font

La maquette est en Avenir mais pour l'exercice, utiliser `Nunito` de Google Fonts.

---

### Texte

Pour l'adresse, utiliser celle-ci:

```
1223, rue De La Gauchetière Ouest, bureau 2300
Montréal, Québec, Canada, H3B 6W6

Téléphone: 514.956.2536
Télécopieur: 514.252.6565
Courriel: info@leeroy.ca
```
