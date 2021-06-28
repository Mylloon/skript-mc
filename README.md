# Skript-mc
Commandes simples en skript pour mon serveur privé minecraft. (en français)

## Versions
- [Skript](https://github.com/SkriptLang/Skript) 2.5.3 (dernière version actuelle)
- [SkBee](https://github.com/ShaneBeee/SkBee) 1.11.2 (pour l'auto-complétion)
- [skRayFall](https://dev.bukkit.org/projects/skrayfall) 1.9.25 (pour le `title` dans le /broadcast)

## Commands & Features
### Commands
*(quand l'argument est entre `[]`, c'est facultatif, quand c'est entre `<>`, c'est obligatoire)*
- /skr -> Reload main skript.
- /forceexecute <joueur> <commande> -> Force un joueur à exécuter une commande.
- **/broadcast <message>** (or /bc) -> Faites une annonce. (30s cooldown)
- **/skull <joueur>** (or /head, /tete) -> Donnez la tête d'un joueur.
- **/clearchat** (or /cc) -> Efface l'historique des tchats pour tout le monde. (1mn de recharge)
- **/sethome [nom]** -> Définissez un point de téléportation. (par exemple, votre maison)
- **/delhome [nom]** -> Supprime un point de téléportation.
- **/home [nom]** -> Permet de se téléporter vers un point de téléportation.
- **/listhome** -> Liste de vos points de téléportation.
- **/afk** -> Annoncez que vous allez être afk.
- **/gmc [joueur]** -> Changez le mode de jeu d'un joueur en mode créatif.
- **/gms [joueur]** -> Changez le mode de jeu d'un joueur en mode spectateur.
- **/top** -> Vous téléporte au sommet du bloc au-dessus de vous.
- **/killall** -> Tue toutes les entités du monde sauf : les joueurs, les porte-d'armure, les flèches, les tableaux, les cadres, les bateaux, les villageois et les entités ayant un nom.
- **/feed [joueur]** -> Remplit la barre de nourriture d'un joueur.
- **/nickname [joueur] <surnom|off>** (or /nick) -> Changez votre nom ou celui d'un autre joueur. (max 15 caractères) - Mettez `off` comme argument pour supprimer le surnom.
- **/msg <joueur> <message>** (or /whisper, /w, /tell, /t) -> Envoyez un message privé à un joueur.
- **/reponse <message>** (or /rep, /r) -> Envoie une réponse à un joueur.
- **/rename <nom>** -> Renommer l'item dans votre main.
- **/quelbloc** -> Activez ou désactivez le nom du bloc qui se trouve devant vous dans l'`action bar`.
- **/deacoudre** -> Commencez une partie de dé à coudre (il téléporte tout le monde sur la plateforme, répétez la commande pour arrêter de jouer, les laines spawn d'elles-mêmes). - *si vous utilisez cela pour vous, vous devez d'abord construire la plateforme et changer les coordonnées.*
- **/casque** (or /hat) -> Mettez l'objet de votre main sur votre tête.

### Features
- **Il ne pleut jamais.**
- **Les commandes `home` ont une autocomplétion.**
- Personnalisation du message de première connexion, de connexion et de départ.
- Chat personnalisé.
- Motd et joueur maximum personnalisés.
- **La commande /clear ne supprime pas l'équipement, pour le supprimer, utilisez /clearall.**

## Disclaimer
Stockage des adresses IP pour la personalisation du Motd.
