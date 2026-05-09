---
name: carousel
type: support-graphique
format: serie-slides
---

# Template - Carousel (LinkedIn / Instagram)

## Objectif
Serie de slides visuelles coherentes pour expliquer un sujet, vendre un service ou raconter une histoire.

## Dimensions
- 1080x1080 px (1:1) - LinkedIn / Instagram standard
- 1080x1350 px (4:5) - Instagram portrait

## Structure standard (8 slides)

| Slide | Role | Contenu |
|-------|------|---------|
| 1 | Accroche | Titre choc + visuel fort + promesse |
| 2 | Probleme | La douleur ou le contexte |
| 3 | Contenu 1 | Premier point / astuce / etape |
| 4 | Contenu 2 | Deuxieme point |
| 5 | Contenu 3 | Troisieme point |
| 6 | Contenu 4 | Quatrieme point |
| 7 | Recap | Resume visuel ou citation forte |
| 8 | CTA | Appel a l'action + nom / logo |

## Regles de prompt
- Style identique sur toutes les slides
- Slide 1 : texte tres grand, visuel dominant, accroche en moins de 7 mots
- Slides 2-7 : hierarchie claire titre > corps > numero de slide
- Slide 8 : fond couleur de marque, CTA centre, nom visible
- Numero de slide visible dans un coin (ex: "3/8")
- Zone de securite : 40px minimum sur tous les bords
- MODELE IMAGE OBLIGATOIRE : GPT Image 2

## Couleurs 99school (par defaut)
- Fond principal : #111111 (noir)
- Accent : #FCA311 (orange)
- Texte : #FFFFFF (blanc)

## Style anchor type
"Slide [N]/[TOTAL] d'un carousel professionnel [THEME], format 1080x1080px,
style [STYLE], palette [COULEURS], typographie moderne lisible,
fond [COULEUR_FOND], titre tres lisible,
cohesion visuelle avec toutes les autres slides,
tout le texte est en francais, rendu dans l'image par GPT Image 2"

## Prompt exemple - Slide 1 accroche
"Slide 1/8 d'un carousel LinkedIn professionnel sur [THEME],
format 1080x1080px, style graphique moderne et epure,
fond noir (#111111), elements accent orange (#FCA311), texte blanc,
TEXTE A AFFICHER :
Titre : '[ACCROCHE EN 5-7 MOTS]'
Sous-titre : '[PROMESSE OU QUESTION]'
Numero : '1/8' en petit coin inferieur droit,
tout le texte est rendu dans l'image, GPT Image 2 obligatoire"

## Prompt exemple - Slide 8 CTA
"Slide 8/8 d'un carousel LinkedIn, format 1080x1080px,
fond orange (#FCA311), texte noir (#111111),
TEXTE A AFFICHER :
CTA : '[ACTION EN 5 MOTS MAX]'
Nom : '[NOM / MARQUE]'
Contact : '[INFO]',
typographie bold centree, GPT Image 2 obligatoire"
