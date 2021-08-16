# latex-template-universite-de-paris

Template LATEX pour un rapport de stage Université de Paris

## Style

Suis le style suivant:

- Papier format A4 (21x29,7 cm) recto-verso.
- Marges:
  - Gauche: 4 cm.
  - Droite: 2 cm.
  - Haut: 3,5 cm.
  - Bas: 3,5 cm.
- Pages numérotées progressivement au pied de la page au centre.
- Titre de police Arial (Liberation Sans) de dimension 18 [(17.28)](https://latex-tutorial.com/changing-font-size/#Changing-the-font-size-globally) en gras
- Titres des sous sections la police Arial (Liberation Sans) de dimension 14 [(14.4)](https://latex-tutorial.com/changing-font-size/#Changing-the-font-size-globally)  en gras et italique.
- L'alignement du texte est justifié forcé.
- Texte de police Times New Roman (Liberation Serif) de dimension 12, sauf cas échéant.
- Interligne de 1,15 lignes.
- Indentation de chaque paragraphe.
- Les listes non numérotées sont préfixées par $\circ$ au lieu des tirêts laids habituels.

## Template Pandoc

Un template Pandoc est fournis. Voici une paramétrisation YAML avec l'ensemble des variables comprises:

```yaml
uni:
  logo: resources/img/logo_uni.jpg
  name: Université de Paris
  department: Faculté de sciences
  ufr:
    name: UFRs d'Informatique et de Mathématiques
    director: "Directeurs: ... et ."

internship:
  title: "Mon intitulé de stage"
  tutors:
    teacher: mon_professeur
    in-company: mon_tuteur_en_entreprise
  student: mon_prénom_nom

study:
  year: 2020/2021
  level: Master 2
```
