### H7N-NSI #02

~ La 👸 de Clèves ~

Émoji (絵文字 / えもじ, emoji, prononcé /emodʑi/), est un terme issu du japonais pour désigner les pictogrammes utilisés dans les messages électroniques et les pages web japonaises, qui se sont répandus dans le monde entier.<br />
[[lire la suite]](https://fr.wikipedia.org/wiki/%C3%89moji)

<br />

**MISSION**

-- **Niveau 1** --

* Lire l'article Wikipedia sur les Émojis.
* Revoir les encodages ASCII et Unicode.
* Visiter et étudier : https://home.unicode.org / https://unicode.org/emoji/charts/full-emoji-list.html
* Étudier [la première partie de La Princesse de Clèves](https://github.com/hackathon-nsi/h7n-nsi-02/tree/main/textes/La%20%F0%9F%91%B8%20de%20Cl%C3%A8ves) et faire une première liste de termes qui pourraient être remplacés par des Émoji.
* Écrire un programme en Python qui remplace les termes de la liste précédente par les Émojis correspondants.

<br />

-- **Niveau 2** --

Faire la même chose en Javacript.

<br />

-- **Niveau 3** --

Construire une page web avec un formulaire permettant de changer des termes en Émoji pour tout texte présent sur le site [Wikisource](https://fr.wikisource.org/wiki/Wikisource:Accueil). 

<br />

**Consignes**
* Rédiger la documentation de votre projet dans le fichier README.md (présenter la technique choisie, décrire la démarche, expliquer le code...)
* Placer le code Python dans un ou plusieurs fichiers .py
* Commenter le code
* Toute contribution doit faire l'objet de discussions entre les membres d'une équipe avant soumission ("commit"). De plus, les contributions des différents membres d'une équipe doivent être équilibrées. Si un membre dépasse un seuil de contribution (60% pour une équipe de deux, 40% pour une équipe de trois), il doit cesser ses contributions et communiquer avec les autres membres de l'équipe afin de partager et expliquer ses idées et son code. 

<br />

**Aide**

Pour lire un fichier texte en Python :
```python
import requests
reponse = requests.get('https://raw.githubusercontent.com/hackathon-nsi/h7n-nsi-02/main/textes/La%20%F0%9F%91%B8%20de%20Cl%C3%A8ves/La%20Princesse%20de%20Cl%C3%A8ves%2C%20%C3%A9dition%20Lepetit%2C%201820%20-%20Premi%C3%A8re%20partie.txt')
texte = reponse.text
print(texte)
```




