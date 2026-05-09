---
name: workbook_atelier
type: livre-visuel
format: cahier-exercices
---

# Template - Workbook / Cahier d'atelier

## Objectif
Cahier d'exercices visuel et actionnable pour ateliers, formations ou auto-formation.
Chaque page a une seule action principale.
Ideal pour ateliers 99school, formations IA, coaching.

## Structure (25 pages)

| Page | Type | Contenu |
|------|------|---------|
| 1 | Couverture | Titre atelier, sous-titre, logo formateur |
| 2 | Mode d'emploi | Comment utiliser ce cahier |
| 3 | Objectif du module | Ce que tu vas accomplir |
| 4 | Exercice 1 Consigne | Titre + instructions claires |
| 5 | Exercice 1 Espace | Grande zone vide + lignes / cadres |
| 6 | Exercice 1 Exemple | Version remplie commentee |
| 7-9 | Exercice 2 | Meme structure |
| 10-12 | Exercice 3 | Meme structure |
| 13-15 | Exercice 4 | Meme structure |
| 16 | Plan d'action | Mes 3 prochaines actions |
| 17 | Recap | Ce que j'ai appris |
| 18 | Ressources | Outils recommandes |
| 19 | A propos formateur | Bio + contacts |

## Regles de design
- Zones d'ecriture clairement delimitees (cadres, lignes, cases)
- Une seule action par page
- Titres tres visibles, corps de texte court
- Pictogrammes pour guider (crayon = a remplir, oeil = exemple)
- Pages 'a remplir' : fond blanc ou pale
- Pages 'consigne' : fond colore
- MODELE IMAGE OBLIGATOIRE : GPT Image 2

## Couleurs 99school
- Orange (#FCA311), Noir (#111111), Blanc (#FFFFFF)

## Dimensions
- Portrait : 1800x2700 px (print 6x9") ou 2550x3300 px (print 8.5x11")

## Style anchor type
"Page [N] d'un cahier d'exercices professionnel pour formation [THEME],
dimensions [WxH]px, style pedagogique moderne,
palette orange (#FCA311), noir (#111111), blanc (#FFFFFF),
zones d'ecriture delimitees par des cadres ou lignes,
pictogrammes expressifs, une seule action principale par page,
tout le texte en francais rendu dans l'image par GPT Image 2"

## Prompt exemple - page consigne
"[STYLE ANCHOR] Page [N] - Exercice [NUM] : [NOM EXERCICE],
type de page : CONSIGNE, fond orange (#FCA311),
TEXTE A AFFICHER :
  Titre exercice : 'Exercice [NUM] - [NOM]'
  Consigne : '[INSTRUCTION CLAIRE EN 2-3 PHRASES MAX]'
  Icone : crayon dans un cercle blanc,
  Encadre : 'Temps : [DUREE]',
GPT Image 2 obligatoire"

## Prompt exemple - page espace
"[STYLE ANCHOR] Page [N] - Espace de travail : Exercice [NUM],
type de page : A REMPLIR, fond blanc (#FFFFFF),
TEXTE A AFFICHER :
  Titre leger : 'Exercice [NUM] - [NOM]'
  Icone crayon en haut a gauche,
ZONE CENTRALE : grande zone vide avec lignes horizontales grises legeres,
Numero de page : '[N]' en bas centree, petit,
GPT Image 2 obligatoire"
