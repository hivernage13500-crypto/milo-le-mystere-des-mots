# Milo, le mystère des mots

Série animée jeunesse · 8 épisodes de 1 min 30 · animatiques MP4 (16:9, 1280×720)

Thème global — **la dyslexie à hauteur d'enfant**. Milo a 8 ans, il adore inventer des machines, mais lire lui demande un effort invisible. Avec Inès, son amie, et Ziko le robot qu'il construit, il découvre pourquoi, comment en parler et quelles aides lui conviennent.

> Les épisodes sont produits en **animatique** : illustrations animées (mouvement de caméra, fondus), dialogues en sous-titres (police **OpenDyslexic**), musique originale d'ambiance. Les dialogues sont courts pour une lecture facile par des enfants de 6–9 ans.

## Épisodes

| N° | Titre | Ce que l'épisode traite |
|---|---|---|
| 1 | Le mot impossible | Le découragement et la première conversation avec un adulte |
| 2 | La naissance de Ziko | La peur de se tromper et le droit de recommencer |
| 3 | Le mystère de la dyslexie | Comprendre la dyslexie, séparer lecture et intelligence |
| 4 | La planète des sons | Le lien lettres–sons (m + a = ma, retrouvé dans « manège ») |
| 5 | Même pas drôle ! | Les moqueries, l'amitié, le droit de parler ou non |
| 6 | Les outils secrets | Livre audio, lecture guidée : choisir l'aide du moment |
| 7 | Le grand défi | Demander un coup de main, prendre sa place dans l'équipe |
| 8 | À ma façon | Reconnaître ses progrès, lever la main |

Fil rouge de la saison (2 scènes) : en épisode 1, Milo baisse les yeux quand on l'invite à lire ; en épisode 8, il lève la main, car il a une histoire à raconter et connaît ses outils.

## Contenu du dépôt

- `videos/` — les 8 épisodes en MP4 (H.264 + AAC).
- `textes/` — scripts dialogués des épisodes (Markdown), pour lecture vocale ou redécoupage.
- `affiches/` — image de la série et affiche par épisode.

## Production

- Scripts : dialogues originaux, phrases courtes, vocabulaire 6–9 ans.
- Visuels : style cartoon 2D enfant, cohérence de personnages par références.
- Animation : travelling léger (zoom/pan), fondus enchaînés, carte-titre et fin de carte.
- Sous-titres : bandeau bas, fort contraste, **OpenDyslexic** (licence open source).
- Musique : nappes + arpèges pentatoniques synthétisés, une couleur par épisode.
- Rendu : Python (Pillow/NumPy) + ffmpeg — H.264 CRF 19, 12 images/s.

## Crédits licences

- Police [OpenDyslexic](https://github.com/antijingoist/opendyslexic) — licence open (OFL/CC, voir dépôt amont).
- Polices [Baloo 2](https://fonts.google.com/specimen/Baloo+2) et [Nunito](https://fonts.google.com/specimen/Nunito) — SIL OFL.
