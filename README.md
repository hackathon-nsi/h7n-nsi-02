### H7N-NSI #02

~ La 👸 d'Émoji ~

Émoji (絵文字 / えもじ, emoji, prononcé /emodʑi/), est un terme issu du japonais pour désigner les pictogrammes utilisés dans les messages électroniques et les pages web japonaises, qui se sont répandus dans le monde entier.<br />
[[lire la suite]](https://fr.wikipedia.org/wiki/%C3%89moji)


**Mission**

- Niveau 1 -

* Lire l'article Wikipedia sur les Émoji
* Revoir les encodages ASCII et Unicode.
* Visiter et étudier : https://home.unicode.org / https://unicode.org/emoji/charts/full-emoji-list.html
* Etudier [la première partie de La Princesse de Clève](https://github.com/hackathon-nsi/h7n-nsi-02/tree/main/textes/La%20%F0%9F%91%B8%20de%20Cl%C3%A8ves) et faire une première liste de termes qui pourraient être remplacés par un Émoji.
* Ecrire un programme en Python qui remplace les termes de la liste précédente par les Emoji correspondants.

- Niveau 2 -

Faire la même chose en Javacript

- Niveau 3 -

Construire une page web avec un formulaire permettant de changer des termes en Emoji pour tout texte présent sur le site [Wikisource](https://fr.wikisource.org/wiki/Wikisource:Accueil). 


**Aide**

Pour lire un fichier texte en Python :
```python
import requests
reponse = requests.get('https://raw.githubusercontent.com/hackathon-nsi/h7n-nsi-02/main/textes/La%20%F0%9F%91%B8%20de%20Cl%C3%A8ves/La%20Princesse%20de%20Cl%C3%A8ves%2C%20%C3%A9dition%20Lepetit%2C%201820%20-%20Premi%C3%A8re%20partie.txt')
texte = reponse.text
print(texte)
```




