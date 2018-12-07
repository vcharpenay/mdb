TODO:
 - app crashes if user denies geo-location
 - autorecentrage à enlever?
 - On a pas l'affichage des ranks à la fin
 - les layers ne gardent pas leur position en altitude
 - condition de sortie c'est quand tous les joueurs sont out.
 - Diminuer la taille des espace pour rentrer les valeurs (gain de place pour le nom des joueurs

Doit y avoir un problème avec le _li parce que cette commande ne marche pas dans timeout() :li.querySelector('span[title=rank]').innerText = 'ca'
alors que la globale oui: document.querySelector('#player-me span[title=rank]').innerText = 'caca'

Test du 27/11 a deux joueurs :
- Quand un joueur meurt, il devient rouge pour lui mais pas sur écran des autres.
- mon frère est mort au round 5 et pas moi, pourtant on était tous les deux marqués round 5 dans le menu, alors que je suis devenu rouge au round 6.
- on voit pas le rank des autres
- le jeu continue quand on est tous mort
- a la création de la room, c'est centré sur Lyon et pas les joueurs