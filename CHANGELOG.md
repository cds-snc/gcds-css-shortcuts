([Français](#journal-des-modifications))
# Changelog
## [1.1.0](https://github.com/cds-snc/gcds-css-shortcuts/compare/css-shortcuts-v1.0.1...css-shortcuts-v1.1.0) (2025-12-18)


### :rocket: New Features

* notify when issue created by external user ([#307](https://github.com/cds-snc/gcds-css-shortcuts/issues/307)) ([1fc95f6](https://github.com/cds-snc/gcds-css-shortcuts/commit/1fc95f6db1124f09e1d4403bfe60098a2be62201))

## [1.0.1](https://github.com/cds-snc/gcds-css-shortcuts/compare/css-shortcuts-v1.0.0...css-shortcuts-v1.0.1)
Released on: 2025-10-16


### :wrench: Improvements
* **visibility-sr-only**: Remove extra padding when using this class for accessibility to align with the SR Only component ([#288](https://github.com/cds-snc/gcds-css-shortcuts/issues/288)) ([a45bdca](https://github.com/cds-snc/gcds-css-shortcuts/commit/a45bdcaf362f04df8dc7e9448d4d6c7cef50ef8d))

## v1.0.0

Released on: 2025-09-29

### :rocket: CSS Shortcuts v1.0.0 is now live!

CSS Shortcuts is a CSS utility framework built to match GC Design System styles and Canada.ca standards. It provides CSS classes with pre-defined design elements, like colour, spacing, and typography.

Apply these classes to your HTML when you need custom styles for page layouts or elements. Read our new [guidance section](https://design-system.alpha.canada.ca/en/css-shortcuts/) on the website for technical documentation (coming soon!).

#### Update from `@cdssnc/gcds-utility` to `@gcds-core/css-shortcuts`
This product has previously been released as an alpha version named GCDS Utility Framework (`@cdssnc/gcds-utility`). We have republished it under a new name, a new home (it’s now under `@gcds-core`), with full technical documentation which marks its official product release: `@gcds-core/css-shortcuts`.

As part of this change, the version number has been reset to v1.0.0, so you’ll need to update your references to continue receiving future improvements. Here’s a guide to help with update your code:

##### Update the stylesheet:
Our page templates use the CSS Shortcuts (previously `gcds-utility`) stylesheet by default. Replace your existing stylesheet link with the following. Note the new path, version number, and filename.
```html
<link rel="stylesheet"
href="https://cdn.design-system.alpha.canada.ca/@gcds-core/css-shortcuts@1.0.0/dist/gcds-css-shortcuts.min.css" />
```

###### ⚠️ CDN deprecation notice:
References to the legacy `@cdssnc/gcds-utility` CDN build will remain available for one year to support existing projects. After that period, the CDN will be removed and requests to the old URLs will no longer resolve. Please update your references to point to the new package and CDN path as soon as possible to avoid disruptions.

##### Update your NPM package:
Find out if you’re using the old package in your project by checking your package.json for references to `@cdssnc/gcds-utility`. If you are, here’s how to update to the new one:
1. `npm uninstall @cdssnc/gcds-utility`
2. `npm install @gcds-core/css-shortcuts`
3. Change all references to the old package and files to the new one:

Before:
  ```js
    import '@cdssnc/gcds-utility/dist/gcds-utility.min.css';
  ```
  After:
  ```js
    import '@gcds-core/css-shortcuts/dist/gcds-css-shortcuts.min.css';
  ```

**Note**: As CSS Shortcuts was previously released as `@cdssnc/gcds-utility`, we’ve kept an archived version of the CHANGELOG which can be found [here](archived/CHANGELOG-UTILITY.md).
We have deprecated the `@cdssnc/gcds-utility` package on npm. It will no longer receive updates or bug fixes, and we strongly recommend migrating to `@gcds-core/css-shortcuts` to continue receiving improvements and future releases.

---

# Journal des modifications

## v1.0.0

Version publiée le : 2025-09-29

### :rocket: Accédez aux Raccourcis CSS v1.0.0 dès maintenant!

Les Raccourcis CSS sont un cadre utilitaire CSS conçu en conformité avec les styles de Système de design GC et les normes de Canada.ca. Vous y trouverez des classes CSS avec des éléments de design prédéfinis, comme la couleur, l’espacement et la typographie. 

Appliquez ces classes à votre code HTML lorsqu’il vous faut des styles personnalisés pour des mises en page ou des éléments particuliers.
Consultez la nouvelle section du site Web sur les [lignes directrices](https://design-system.alpha.canada.ca/fr/raccourcis-css/) afin de lire la documentation technique (à venir!).

#### Mise à jour de `@cdssnc/gcds-utility` à `@gcds-core/css-shortcuts`
Ce produit existait déjà en version Alpha sous le nom GCDS Utility Framework (Cadre utilitaire SDGC) (`@cdssnc/gcds-utility`). Pour signaler le lancement officiel de `@gcds-core/css-shortcuts`, nous lui avons donné un nouveau nom, un nouvel emplacement (il se trouve maintenant sous `@gcds-core`), ainsi qu’une documentation technique complète. 

Dans le cadre de ce changement, le numéro de version a été réinitialisé à v1.0.0. Il faudra donc mettre à jour toute référence afin de continuer à recevoir les améliorations futures. Voici un guide pour vous aider à mettre à jour votre code :

##### Mettre à jour la feuille de style :
Nos modèles de page utilisent la feuille de style Raccourcis CSS (anciennement `gcds-utility`) par défaut. Remplacez le lien existant de votre feuille de style par le suivant. Notez le nouveau chemin d’accès, le numéro de version et le nom de fichier.
```html
<link rel="stylesheet"
href="https://cdn.design-system.alpha.canada.ca/@gcds-core/css-shortcuts@1.0.0/dist/gcds-css-shortcuts.min.css" />
```

###### ⚠️ Avis d’obsolescence du CDN :
Les références à l’ancienne version du CDN `@cdssnc/gcds-utility` resteront accessibles pendant un an pour soutenir les projets existants. Après cette période, le CDN sera supprimé et les demandes liées aux anciennes URL ne seront plus résolues. Veuillez mettre à jour vos références vers le nouveau paquet et chemin CDN dès que possible afin d’éviter toute interruption.

##### Mettre à jour le paquet NPM :
Découvrez si vous utilisez l’ancien paquet dans votre projet en vérifiant si votre paquet.json contient des références à `@cdssnc/gcds-utility`. Si l’ancien paquet s’y trouve, voici comment faire la mise à jour vers le nouveau :
1. `npm uninstall @cdssnc/gcds-utility`
2. `npm install @gcds-core/css-shortcuts`
3. Changez toute référence à l’ancien paquet et aux anciens fichiers par le nouveau :

Avant:
  ```js
    import '@cdssnc/gcds-utility/dist/gcds-utility.min.css';
  ```
Après :
  ```js
    import '@gcds-core/css-shortcuts/dist/gcds-css-shortcuts.min.css';
  ```
**Remarque** : Comme les Raccourcis CSS avaient été publiés auparavant sous le nom `@cdssnc/gcds-utility`, nous avons conservé une version archivée du journal des modifications. Vous pouvez y accéder [ici](archived/CHANGELOG-UTILITY.md#journal-des-modifications).

Nous avons désactivé le paquet `@cdssnc/gcds-utility` sur npm. Il ne recevra plus de mises à jour ni de corrections de bogues, et nous recommandons fortement la migration vers `@gcds-core/css-shortcuts` pour continuer à recevoir des améliorations et mises à jour futures.
