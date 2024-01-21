## Version Française: [README.fr.md](README.fr.md)

L'objectif de cette procédure opérationnelle standard (SOP) complète est de fournir des conseils et une formation approfondis aux membres de l'équipe technique de Starlight sur l'utilisation efficace des outils de traitement multimédia, y compris Canva, VLC et QuickTime. Cette SOP est spécialement conçue pour doter les nouveaux membres de l'équipe technique de Starlight des connaissances et des compétences nécessaires pour organiser, créer et traiter efficacement les ressources multimédias pour les plateformes en ligne de Starlight. En suivant cette SOP, les membres de l'équipe acquerront une base solide en matière de traitement multimédia, ce qui leur permettra d'améliorer la qualité et l'impact de la présence en ligne de Starlight.

## Table des matières
- [Annexe](#annexe-1---utilisation-de-l'écosystème-apple)
    - [Annexe 1 - Utilisation de l'écosystème Apple](#annexe-1---utilisation-de-l'écosystème-apple)
    - [Annexe 1.1 - Capturer une capture d'écran](#annexe-11---capturer-une-capture-d'écran)
    - [Annexe 1.2 - Spotlight](#annexe-12---spotlight)
- [Traitement des enregistrements vidéo en direct](#traitement-des-enregistrements-vidéo-en-direct)
    - [Fusionner dans QuickTime](#fusionner-dans-quicktime)
    - [Rogner dans QuickTime](#rogner-dans-quicktime)
    - [Correction de l'audio mono dans VLC](#correction-de-l'audio-mono-dans-vlc)
- [Création de vignettes](#création-de-vignettes)
- [Téléchargement sur YouTube](#téléchargement-sur-youtube)
- [Création de vignettes avancée](#création-de-vignettes-avancée)


### Annexe 1 - Utilisation de l'écosystème Apple

Le matériel informatique et les périphériques utilisés par Starlight sont basés sur l'écosystème MacOS. Il existe notamment des différences significatives entre MacOS et Windows, notamment en ce qui concerne la disposition du clavier MacOS. Le clavier MacOS intègre les touches de contrôle (rouge), d'option (vert) et de commande (bleu). La touche de commande fonctionne de manière similaire à la touche Ctrl de Windows, par exemple, Commande + C équivaut à Ctrl + C, qui est le raccourci pour copier ; tandis que la touche d'option sert d'équivalent à Alt. Il est important de reconnaître que le comportement des programmes MacOS peut différer de leurs homologues Windows en raison de leurs principes de conception distincts.

![](assets/2024-01-11-22-46-35.png)

### Annexe 1.1 - Capturer une capture d'écran

Pour capturer une capture d'écran, appuyez sur Commande + 3. Elle enregistrera la capture d'écran dans votre dossier de bureau, qui est situé à ~/Desktop ou au nom complet de /User/Starlight/Desktop.

### Annexe 1.2 - Spotlight
Spotlight est un puissant outil de recherche disponible sur MacOS qui permet aux utilisateurs de localiser rapidement des fichiers, des dossiers et des applications. Pour accéder à Spotlight, appuyez simplement sur la combinaison de touches Commande + Espace. Cette fonctionnalité pratique est particulièrement utile pour résoudre les problèmes audio en accédant aux paramètres audio.

### Limitation administrative

En raison de strictes limitations administratives, les membres de l'équipe technique de Starlight sont interdits d'installer des applications supplémentaires sur les ordinateurs de Starlight. Cependant, malgré cette contrainte importante, nous avons accès à un ensemble d'outils essentiels déjà installés sur les ordinateurs, y compris VLC, QuickTime, Google Chrome et ProPresenter. Ces outils fournissent une base de départ pour surmonter les limitations administratives et effectuer efficacement les tâches de traitement multimédia.

## Traitement des enregistrements vidéo en direct

Starlight enregistre en direct l'intégralité de la session de diffusion en direct et l'enregistre sous forme de fichier vidéo. Cependant, nous n'avons besoin de télécharger que la partie principale de la diffusion en direct sur YouTube. Il est donc nécessaire de rogner le fichier vidéo. De plus, il peut arriver que des problèmes d'enregistrement entraînent la création de plusieurs fichiers qui doivent être fusionnés. Dans certains cas, l'audio peut également présenter des problèmes qui doivent être résolus à l'aide de VLC. Cette section explique comment utiliser QuickTime et VLC pour rogner, fusionner et résoudre les problèmes audio.

### Fusionner dans QuickTime

Dans le cas où nous avons des problèmes d'enregistrement et que nous avons plusieurs fichiers vidéo, nous devons les fusionner. Pour les fusionner, ouvrez QuickTime et cliquez sur Edition > Ajouter des clips à la fin. Ensuite, sélectionnez tous les fichiers vidéo que vous souhaitez fusionner. Une fois que vous avez terminé, cliquez sur Fichier > Exporter sous et donnez un nom à la vidéo.

`Il n'y a pas encore d'images, je mettrai à jour les instructions d'image une fois que j'aurai accès à l'ordinateur de l'église.`

### Rogner dans QuickTime

Pour rogner une vidéo dans QuickTime, ouvrez le fichier vidéo dans QuickTime. Prévisualisez la vidéo et notez le timestamp, vous pouvez noter le timestamp dans l'application Notes par défaut d'Apple. Utilisez Commande + Entrée pour rechercher l'application Notes. Ensuite, cliquez sur Edition > Rogner. Vous pouvez faire glisser la barre jaune pour rogner la vidéo. Une fois que vous avez terminé, cliquez sur Rogner. Ensuite, cliquez sur Fichier > Exporter et donnez un nom à la vidéo.

`Il n'y a pas encore d'images, je mettrai à jour les instructions d'image une fois que j'aurai accès à l'ordinateur de l'église.`

### Correction de l'audio mono dans VLC

Parfois, l'audio ne sort que d'un seul canal et n'est pas adapté à YouTube. Il est préférable d'éviter ce problème en vérifiant la configuration audio avant la diffusion en direct. Cependant, si le problème audio est inévitable, nous pouvons le résoudre dans VLC. Pour corriger l'audio, ouvrez VLC et cliquez sur Fichier > Convertir/Enregistrer. Ici, je vais vous montrer comment procéder avec un fichier dont le canal audio droit a été supprimé intentionnellement.

![](assets/2024-01-20-23-58-08.png)

Dans VLC, cliquez sur Ajouter et sélectionnez le fichier vidéo. Ensuite, allez dans Média > Convertir/Enregistrer. Cliquez maintenant sur l'icône plus pour ajouter votre média. Ensuite, cliquez sur Convertir/Enregistrer.

!