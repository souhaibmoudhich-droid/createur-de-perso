# Créateur de perso – Roues

Chaque joueur construit son personnage roue par roue (race, force, magie, élément, pouvoir spécial, arme), puis tous les persos s'affrontent dans l'arène.

## Jouer

Ouvre la page du jeu, puis :

- **Sur le même écran** : règle le nombre de joueurs et tournez les roues chacun votre tour.
- **En ligne** : clique sur « Créer une salle », puis envoie le lien (ou le code à 5 caractères) à tes amis. Chacun tourne les roues de son perso depuis son propre écran, et tout le monde voit le même combat. Jusqu'à 8 joueurs.

Celui qui crée la salle est l'hôte : il doit garder la page ouverte pendant la partie, et lui seul peut recommencer la partie ou modifier les groupes.

## Technique

Un seul fichier, `index.html`, sans installation. Le mode en ligne relie directement les navigateurs entre eux avec [PeerJS](https://peerjs.com) (WebRTC) : aucun serveur de jeu, aucun compte.
