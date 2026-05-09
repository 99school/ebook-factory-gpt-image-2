---
name: thumbnail
type: support-graphique
format: miniature
---

# Template - Miniatures (YouTube, Stories, Posts)

## Objectif
Miniature visuelle forte et lisible meme en petite taille.
Objectif : attirer le clic, lisible en 150x150px.

## Formats

| Ratio | Dimensions | Usage |
|-------|-----------|-------|
| 16:9 | 1920x1080 px | YouTube, videos web |
| 9:16 | 1080x1920 px | Stories, Reels, TikTok |
| 4:3 | 1440x1080 px | Presentations |
| 1:1 | 1080x1080 px | Posts reseaux sociaux |

## Regles de design CRITIQUES
- Texte TRES grand et tres contraste
- Maximum 3-5 mots sur la miniature
- Focus visuel fort : visage, objet, chiffre, mot-cle en surbrillance
- Fond non encombre
- Couleurs contrastees et vives
- MODELE IMAGE OBLIGATOIRE : GPT Image 2

## Test de lisibilite
Avant de valider, imaginer la miniature affichee en 150x150px.
Le titre reste-t-il lisible ? Le visuel est-il reconnaissable ?
Si non, simplifier le prompt.

## Zones de securite Stories (9:16)
- Zone haut : 250px - aucun texte critique
- Zone bas : 250px - aucun texte critique
- Zone centrale : tout le contenu important

## Couleurs 99school (par defaut)
- Fond : #111111 (noir) ou couleur vive contrastee
- Accent : #FCA311 (orange)
- Texte : #FFFFFF (blanc)

## Prompt exemple - YouTube 16:9
"Miniature YouTube, dimensions 1920x1080px, ratio 16:9,
style [STYLE], palette tres contrastee,
VISUEL PRINCIPAL : [description du visuel dominant],
TEXTE EN TRES GRANDS CARACTERES :
  Titre : '[MAX 4 MOTS]' - couleur [COULEUR], tres grand, centree,
fond [COULEUR_FOND] contraste,
lisible a 150x150px,
tout le texte est rendu dans l'image par GPT Image 2, typographie bold impactante"

## Prompt exemple - Story 9:16
"Story / Reel, dimensions 1080x1920px, ratio 9:16,
style [STYLE],
ZONE SECURITE HAUT et BAS : 250px - aucun texte critique dans ces zones,
ZONE CENTRALE :
  Visuel fort : [description]
  Titre : '[ACCROCHE]' en tres grand
  Sous-titre : '[TEXTE SECONDAIRE]' plus petit,
fond [COULEUR], palette [PALETTE],
tout le texte en francais rendu dans l'image par GPT Image 2"

## Prompt exemple - Post carre 1:1
"Post reseaux sociaux, dimensions 1080x1080px, ratio 1:1,
style [STYLE], palette [COULEURS],
VISUEL : [description centrale],
TEXTE : '[TITRE COURT]' en tres grands caracteres contraste,
fond [COULEUR], lisible en 150x150px,
GPT Image 2 obligatoire"
