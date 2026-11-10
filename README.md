# MD Rénovation – site vitrine

Site vitrine de MD Rénovation (Manel Doisneau, entrepreneur individuel), plombier chauffagiste à Château-Gontier-sur-Mayenne (53) : plomberie, salle de bains, chauffage et dépannage, en neuf et en rénovation, dans un rayon de 50 km.

HTML, CSS et JavaScript natifs : aucune dépendance, aucun build. Seule requête externe : la carte OpenStreetMap.

## Arborescence

```
index.html                    page unique (sprite d'icônes inline, JSON-LD LocalBusiness)
assets/css/styles.css         styles, variables de couleur et mode sombre
assets/js/main.js             menu mobile, apparition au défilement, année du footer
assets/img/logo.svg           logo couleur (hexagone + monogramme MD chromé + wordmark)
assets/img/logo-mono-blanc.svg  logo blanc pour le footer
assets/img/favicon.svg        monogramme seul
robots.txt, sitemap.xml       référencement
```

## Lancer en local

```sh
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## Production

https://md-renovation.vercel.app

## TODO restants

- Adresse e-mail professionnelle (lien `mailto:` du contact, champ `email` du JSON-LD)
- Assurance décennale : assureur et numéro de contrat (bandeau d'engagements et mentions légales)
- Photos de chantiers terminés

## Versions

| Version | Date | Direction visuelle |
|---|---|---|
| v1 | 2026-11-10 | Ambiance enseigne lumineuse reprise de la vitrine rue Thiers ; bleu nuit, bleu électrique néon, jaune et chrome ; hero centré sur motif d'hexagones et réseau de tuyaux lumineux avec raccords jaunes, titre géant en capitales chromées, badge hexagonal « Devis gratuit » ; engagements en ligne sous le hero ; chiffres en ligne unique à séparateurs sur bande jaune, valeurs monospace ; prestations en frise le long d'un tuyau vertical, raccords ronds et cartes alternées gauche / droite ; arrondis forts, halos néon au lieu d'ombres ; capitales espacées ; logo hexagone au trait + monogramme MD plein chromé, wordmark monoline pochoir souligné de jaune |
