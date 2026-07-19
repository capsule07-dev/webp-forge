# WebP Forge

**Convertisseur et optimiseur d'images qui fonctionne entièrement sur votre poste.**
Un seul fichier HTML. Aucune installation, aucun compte, aucun serveur.

---

## Vos images ne quittent jamais votre appareil

Tout le traitement s'exécute dans votre navigateur. Aucune image, aucune donnée
et aucune statistique d'usage n'est transmise où que ce soit — il n'y a pas de
serveur à contacter. Vous pouvez couper votre connexion réseau et l'outil
continue de fonctionner à l'identique.

C'est la différence de fond avec les convertisseurs en ligne, qui envoient vos
fichiers à un tiers pour les traiter.

## Utilisation

1. Téléchargez `webp-forge.html`.
2. Double-cliquez dessus. C'est tout.

Ajoutez-le à vos favoris pour le relancer d'un clic. Le fichier étant autonome,
il fonctionne aussi bien depuis un disque local qu'un lecteur réseau partagé.

## Ce qu'il fait

- **Conversion** — entrée JPG, PNG, GIF, BMP, AVIF, SVG, ICO, WebP ;
  sortie WebP, PNG, JPG, BMP, ICO. La conversion fonctionne dans les deux sens.
- **Traitement par lot** avec pause et annulation, export en ZIP.
- **Redimensionnement** en pixels ou en pourcentage, préréglages personnalisables,
  accentuation automatique après réduction.
- **Recadrage** libre, par ratio, ou aux formats Instagram / Facebook / LinkedIn.
- **Contrôle qualité** — comparateur avant/après à curseur, zoom synchronisé,
  cible de poids (« ≤ 200 Ko ») avec recherche automatique de la qualité.
- **Pack SEO** — nommage de fichier propre, attribut `alt`, snippet `<img>`
  prêt à coller.

## Compatibilité

Chrome, Edge, Firefox et Safari. Safari n'encode pas le WebP nativement :
l'outil embarque un encodeur libwebp compilé en WebAssembly qui prend le relais,
de façon transparente.

## Licence

Apache 2.0 — voir [LICENSE](LICENSE). Les composants tiers embarqués et leurs
licences respectives sont listés dans [NOTICE](NOTICE).

Fourni en l'état, sans garantie (sections 7 et 8 de la licence).

---

Forgé en local par **Capsule07**.
