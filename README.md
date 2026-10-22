Crée un jeu complet du "Jeu de l'Oie du Far West" ("Western Goose Game") entièrement jouable en HTML, CSS et JavaScript dans un seul fichier autonome.

Voici les fonctionnalités et spécifications exactes requises :

1. THÈME & DESIGN WESTERN
- Ambiance visuelle Saloon / Désert du Far West (palette ocre, bois, cuir, parchemin, cactus, étoiles de Sheriff).
- Graphismes responsifs en Canvas / SVG avec des animations fluides (déplacement des pions, lancer de dés 3D/CSS, cartes animées, tirs de revolver et confettis).
- Effets sonores rétro immersifs synthétisés via la Web Audio API (lancer de dés, galop de cheval, coups de feu, explosion, musique de fanfare/victoire) avec possibilité de couper le son.

2. CONFIGURATION ET PERSONNALISATION DES JOUEURS
- Prise en charge de 2 à 12 joueurs.
- Personnalisation pour chaque joueur : nom personnalisable et choix parmi 10 avatars Western distincts (Sheriff, Outlaw, Bounty Hunter, Le chercheur d'or, Cowgirl, Guerrier indigiene, Propriétaire Saloon, Trapper, Gambler, Bandit).
- Éditeur complet permettant de personnaliser le nom, l'effet, la couleur et le type de chaque case du plateau.

3. DISPOSITION DU PLATEAU NON-SPIRALE
- Le plateau de 63 cases suit un parcours sinueux et méandrique style piste sauvage du Far West ("Oregon Trail") divisé en plusieurs zones géographiques (Town, Canyons, Desert, Snake River, Ghost Town, Gold Mine).
- Chaque case affiche son numéro, son icône d'action et son type avec des tooltips au survol pour détailler son effet.

4. SYSTÈME DE CARTES ACTION & MAIN DES JOUEURS
- Intégration d'un jeu/deck de Cartes Action Western tactiques (tirage sur cases spécifiques ou événements).
- Main de cartes pour chaque joueur leur permettant de stocker et d'utiliser stratégiquement leurs cartes pendant leur tour ou au moment voulu.
- Exemples de cartes action : 
  * "Duel à midi" (défier un joueur dans un lancer de dé au perdant reculé)
  * "Lasso du Cowboy" (attraper le joueur devant soi et avancer sur sa case)
  * "Dynamite" (faire sauter les obstacles ou faire reculer les joueurs environnants)
  * "Diligence Express" (avancer de 2x le score du dé)
  * "Bourse d'Or" (échanger de position avec un joueur au choix)

5. CASES SPÉCIALES & ACTIONS DYNAMIQUES
- "Poussière dans les yeux" : Reculez d'autant de cases qu'il y a de joueurs dans la partie.
- "Grand Galop" : Avancez d'autant de cases que le nombre de joueurs qui vous précèdent au classement.
- "Relais de Diligence" : Rejouez immédiatement en doublant votre score de dé.
- "Embrouille au Saloon" / "Prison du Sheriff" : Tour(s) d'attente ou libération en faisant un double/un score spécifique.
- "Rebond Exact" : La case finale 63 (Le Filon d'Or) nécessite un score exact au dé ; si le score est trop élevé, le joueur rebondit en arrière.

6. INTERFACE DE JEU & JOURNAL DE BORD
- Panneau latéral retractable avec classement en direct, suivi du tour actuel, zone de lancer de dés et inventaire des cartes du joueur actif.
- Journal de bord de la partie (Game Log) enregistrant tous les déplacements, effets de cases, duels et cartes jouées.
- Écran de victoire stylisé "WANTED - WINNER" affichant le champion avec feux d'artifice/confettis et récapitulatif de la partie.
