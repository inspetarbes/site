# INSPE TOP · Site de Tarbes

Site vitrine one-page du site de Tarbes de l'INSPE Toulouse Occitanie-Pyrénées.

## Contenu
- Le métier de professeur des écoles (+ témoignage vidéo)
- Parcours réforme 2026 : Licence PE → CRPE en fin de L3 → Master M2E rémunéré → titulaire (frise interactive)
- Formations : Licence PE (4 blocs, ECTS), Master M2E (statuts, rémunérations), le concours
- CRPE bilingue français-occitan (texte FR / occitan, témoignage vidéo)
- DU Pédagogie du chant (compétences, UE des 2 semestres, débouchés, contacts)
- Licence PE détaillée (plaquette « INSPE-Licence LPE 2026 ») : 1 570 h, partenaires, 8 sites, Parcoursup, après la licence, réorientations
- Visite immersive 360° (21 panoramas, visionneuse Pannellum 2.5.6 via CDN) — données dans le tableau `PANOS`
- Visite guidée du campus en 8 étapes (salles, bibliothèque, numérique, restauration, sport, logement, accès)
- Vie étudiante (BDE Becarut, galerie, témoignage vidéo), plan d'accès OpenStreetMap, « Et après ? », contacts

## Technique
- HTML + CSS + JS vanilla, un seul fichier `index.html`
- Charte INSPE TOP : marine `#203F63`, rouge `#DC0D15`, vert `#8AC1A0`
- Mode clair / sombre, responsive, accessible (onglets ARIA, `prefers-reduced-motion`)
- `img/` : photos WebP optimisées · `img360/` : panoramas équirectangulaires 4096×2048 + vignettes · `videos/` : témoignages MP4 compressés

## Déploiement GitHub Pages
1. Pousser le contenu de ce dossier à la racine du dépôt
2. *Settings → Pages → Source : Deploy from a branch → `main` / `(root)`*
3. Le fichier `.nojekyll` désactive le traitement Jekyll

## Mise à jour
- Textes du parcours : tableau `ETAPES` dans le script
- Étapes de la visite : tableau `LIEUX`
- Galerie vie étudiante : tableau `GALERIE`

Sources : [devenirenseignant.gouv.fr](https://www.devenirenseignant.gouv.fr/avant-le-concours-preparer-une-licence-pour-devenir-enseignant-1542) · plaquette DU Pédagogie du chant (MAJ 2025) · Genially « Visite guidée » · diaporama « Devenir PE ».
