---
name: banner
type: support-graphique
format: banniere
---

# Template - Bannieres (LinkedIn, YouTube, Facebook)

## Objectif
Banniere professionnelle pour couverture de profil ou chaine, avec gestion stricte des zones de securite.

## Formats et zones de securite

| Plateforme | Dimensions totales | Zone sure (texte/logo) |
|------------|--------------------|-----------------------|
| LinkedIn profil | 1584x396 px | 1192x220 px au centre |
| LinkedIn entreprise | 1128x191 px | 800x150 px au centre |
| YouTube chaine | 2560x1440 px | 1546x423 px au centre |
| Facebook couverture | 820x312 px | 640x312 px au centre |

## Regle critique
- Le logo et texte principal TOUJOURS dans la zone centrale sure
- Les bords : elements decoratifs uniquement, jamais d'info critique
- Preciser les dimensions exactes dans chaque prompt
- MODELE IMAGE OBLIGATOIRE : GPT Image 2

## Structure du visuel
1. Zone decorative gauche (fond, motifs, elements graphiques)
2. Zone centrale sure : nom, titre, tagline, logo
3. Zone decorative droite (continuation du fond)

## Couleurs 99school (par defaut)
- Fond : #111111 (noir)
- Accent : #FCA311 (orange)
- Texte : #FFFFFF (blanc)

## Prompt exemple - LinkedIn profil
"Banniere LinkedIn profil, dimensions 1584x396px,
style moderne et professionnel, palette noir (#111111) et orange (#FCA311),
ZONE CENTRALE (1192x220px au centre) - contenu essentiel :
  Nom : '[NOM]'
  Titre : '[TITRE / METIER]'
  Tagline : '[SLOGAN EN 5-8 MOTS]'
ZONES LATERALES (decoratif uniquement) :
  Fond degrade, motifs geometriques, aucun texte important hors zone centrale,
tout le texte est rendu dans l'image par GPT Image 2"

## Prompt exemple - YouTube
"Banniere YouTube, dimensions 2560x1440px,
zone TV-safe centrale (1546x423px) :
  Nom de chaine : '[NOM]'
  Sujet : '[THEME]'
  Rythme : '[EX : Nouvelle video chaque semaine]'
Bords et coins : elements decoratifs [STYLE] sans texte critique,
style [STYLE], couleurs [PALETTE],
tout le texte en francais, rendu dans l'image par GPT Image 2"

## Prompt exemple - LinkedIn entreprise
"Banniere LinkedIn entreprise, dimensions 1128x191px,
zone sure centrale (800x150px) :
  Nom entreprise : '[NOM]'
  Tagline : '[SLOGAN]'
  Logo simple : [description],
fond [COULEUR], style professionnel,
tout le texte rendu dans l'image par GPT Image 2"
