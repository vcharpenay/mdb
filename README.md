TODO:
 - the eye of the cyclone is not visible by non-master players
 - app crashes if user denies geo-location
 - `setInterval` only working if the tab is active...
 - autorecentrage à enlever?
 - les marqueurs des joueurs sont sous les zones, on ne peut pas les cliquer
 - On a pas l'affichage des ranks à la fin
 - les layers ne gardent pas leur position en altitude
 - condition de sortie c'est quand tous les joueurs sont out.
 - Diminuer la taille des espace pour rentrer les valeurs (gain de place pour le nom des joueurs
 - dans la structure que je propose, les "Event listeners" ( ou handlers) appellent les fonctions des composants mais pas l'inverse.
il faudrait pour ca ajouter un evenement mdb* qui donne la position de l'oeil, envoye une fois lorsque le master clique 'Start'


Doit y avoir un problème avec le _li parce que cette commande ne marche pas dans timeout() :li.querySelector('span[title=rank]').innerText = 'ca'
alors que la globale oui: document.querySelector('#player-me span[title=rank]').innerText = 'caca'
