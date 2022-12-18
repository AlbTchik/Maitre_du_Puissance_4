
## 🔥 Vous vous trouvez dans le répertoire du Maitre du Puissance 4. 🔥  
🔰 Son rang de Maitre lui a été décerné après sa victoire contre chacuns des autres programmes de la classe de Datascience. 🔰   
<br>
_________________________________________________________________________________________________________________________________

**Date de réalisation :** Avril-Mai 2020, Cours de DataScience & IA, ESILV  
<br>
**Cadre du projet :** Projet réalisé en groupe, avec deux équipes concurrentes : Dimitri et Stéphan contre Morgane et moi, les meilleurs codes pour chacunes des fonctions ont été gardés.  
<br>
**Mots-clés :** Puissance 4, Algorithme Min-Max, Elagage Alpha-Beta, Adversarial Coding  

____________________________________________________________________________________________________________________________________

Cette Intelligence Artificelle utilise l'agorithme Min-Max, pour prédire vos coups les plus géniaux. L'algorithme est applicable à de nombreux jeux, tant que le joueur et son adversaire s'affontent dans un espace de mouvements fini. La Figure 1 présente son fonctionnement sur un jeu de Morpion :  
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/90097422/208294578-eca26d53-12a1-4482-ab11-651f1b176b6d.png" width="500"><br>
  <b>Figure 1 : L'arbre du Min-Max sur le jeu du Morpion</b>
</p>
<br><br>
A chaque coup, l'agorithme Min-Max génère un arbre qui va représenter tout les mouvements possibles, jusqu'a une certaine distance dans le futur. Grace a une heuristique, on attribue une certaine valeurs a chacuns des mouvements, en fonction de leur probabilité de victoire. Puis l'Intelligence Artificelle choisi le mouvement qui l'avantage le mieux, en prenant en compte tout vos meilleurs coups.  

La Figure 2 présente une exemple de l'arbre Min-Max avec une heuristique, chaque noeud correspond à un mouvement dans le jeu :  
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/90097422/208295650-0a7abd0c-e160-4da6-a19f-2a333c9a3350.png" width="400">
  <b>Figure 2 : L'arbre du Min-Max avec une heuristique</b>
</p>
<br><br>
Pour améliorer la rapidité de l'agorithme Min-Max, on utilise l'élagage Alpha-Beta, qui permet de réduire la taille de l'arbre. En pratique, celui-ci supprime  les branches qui ne seront pas exploités du fait de leur trop faible probabilités de victoire. Pour en savoir plus, je vous conseille cette [excellente vidéo](https://www.youtube.com/watch?v=l-hh51ncgDI) de Sébastien Lague sur le sujet.  

Voici le résultat d'une partie contre le Maitre. La victoire lui revient, évidemment : 

![Victory IA](https://user-images.githubusercontent.com/90097422/174677532-b8e32e2f-e650-4244-8926-c4073288fc21.png)

Vous savez donc maintenant comment fonctionne cet algorithme. Mais auriez-vous la capacité de le battre ?  
Pour cela, vous pouvez télécharger et lancer le fichier suivant : 'Maitre_Puissance_4.py'.  

Mais je vous previens, ça ne va pas étre facile de lui arracher une victoire.  
