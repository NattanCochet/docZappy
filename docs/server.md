# Documentation Serveur Zappy

![image](https://github.com/NattanCochet/docZappy/assets/63796498/6e220584-0441-45ae-abc6-cb881a72a67e)

Le serveur gère les différentes commandes du côté de l'interface graphique et de l'IA.
Il est donc le coeur du programme et permet aux autres parties de communiquer avec le jeu.

IA:

- Forward: Avancer de une case dans la direction qu'a pris le client
- Inventory : Voir son inventaire
- Take : Prendre l'un des objets sur sa case
- Set : Poser l'un de ses objets sur la case
- Right : Tourner de 90° vers la droite
- Left : Tourner de 90° vers la gauche
- Look : Regarder les cases selon la direction, dépendant du niveau
- Eject : Ejecte tous les autres clients dans la direction du client qui ejecte
- Connect_nbr : Voir le nombre de clients qui peuvent se connecter dans la team
- Fork : Créer un nouvel oeuf pour qu'un nouveau client puisse se connecter
- Broadcast : Permet de communiquer à tous les autres clients n'importe quelle phrase
- Incantation : Permet de monter de niveau

Look :

![image](https://github.com/NattanCochet/docZappy/assets/63796498/535b006e-7cc6-429a-a13c-2ea18311b132)

Broadcast :

![image](https://github.com/NattanCochet/docZappy/assets/63796498/2553195a-1675-495f-a4d0-60888bc35805)

Incantation :

![image](https://github.com/NattanCochet/docZappy/assets/63796498/432224b7-8d23-4295-a6f7-afbfd98f201c)

That's all you should know to use the server as the AI.

For the GUI protocol :

![image](https://github.com/NattanCochet/docZappy/assets/63796498/07dc4bd3-b980-43e8-b3e4-4a9fde50f7f8)
![image](https://github.com/NattanCochet/docZappy/assets/63796498/75c37b99-41fc-4e25-99e3-2f44d8041c8b)
