Vérifie bien que le nom de ton image dans la propriété `src` correspond au nom du fichier. Assure-toi que l'utilisation des majuscules est la même. Par exemple, 'myimage.png n'est **pas** la même chose que 'myimage.PNG'.

Ce code HTML ne permet pas d'afficher une image enregistrée sous le nom de 'happy.PNG' :

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

<img src="happy.png" alt="An outline of an anime-style girl with a happy facial expression."/>

\--- /code ---
