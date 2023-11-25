
# Jeu de rôle fake en Python pour apprendre les commandes GIT

Ce dépot a été créé dans le cadre de la [vidéo Youtube](https://youtu.be/A5_kJps4qjc) de la chaîne [Bande de codeurs](https://www.youtube.com/@bandedecodeurs) afin d'expliquer les commandes GIT.



## Screenshots

![App Screenshot](https://img.freepik.com/free-vector/black-spooky-castle-flying-dragon-canyon-with-mountains-forest-cartoon-fantasy-illustration-with-medieval-palace-with-towers-creepy-beast-with-wings-rocks-pine-trees_107791-4592.jpg?w=1380&t=st=1700129693~exp=1700130293~hmac=42db732dcc4835c402a6bf65bed2b1a7d879dcc28984d7b63437060747e30a9d)



# Outils

Projet réalisé avec 
- GIT
- Python
- Tabulate


# git tuto

[Apprendre à utiliser GIT](https://www.youtube.com/watch?v=A5_kJps4qjc)  
[github](https://github.com/bandeDeCodeurs/bdc_rpg)  

```bash
git init
git config user.email "djvu.guchz@gmail.com"
git config user.name "dgucc"
git add README.md
git commit -m 'init'
git branch -M main
git remote add origin https://github.com/dgucc/tutos-python-bdc_rpg.git
git push -u origin main

git log
git branch -a

git checkout -b dev

pip install tabulate

git diff Personnage.py

git push -u origin dev

git checkout -b feature/armes


```