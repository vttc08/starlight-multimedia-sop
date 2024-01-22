```markdown
Version Française : [README.French.md](README.French.md) |
Version Anglaise : [README.md](README.md) |
Version Chinoise Simplifiée : [README.zh-CN.md](README.zh-CN.md) | 
Version Chinoise Traditionnelle : [README.zh-TW.md](README.zh-TW.md)

L'objectif de cette procédure opérationnelle standard (SOP) complète est de fournir des orientations approfondies et une formation aux membres de l'équipe technique de Starlight sur l'utilisation efficace des outils de traitement multimédia, notamment Canva, VLC et QuickTime. Cette SOP est spécifiquement conçue pour équiper les nouveaux membres de l'équipe technique de Starlight des connaissances et compétences nécessaires pour organiser, créer et traiter efficacement des ressources multimédias pour les plateformes en ligne de Starlight. En suivant cette SOP, les membres de l'équipe acquerront une base solide en traitement multimédia, leur permettant d'améliorer la qualité et l'impact de la présence en ligne de Starlight.

## Table des matières
- [Annexe](#annexe-1---utilisation-de-l'écosystème-apple)
    - [Annexe 1 - Utilisation de l'écosystème Apple](#annexe-1---utilisation-de-l'écosystème-apple)
    - [Annexe 1.1 - Capture d'écran](#annexe-11---capture-d'écran)
    - [Annexe 1.2 - Spotlight](#annexe-12---spotlight)
- [Traitement des enregistrements vidéo en direct](#traitement-des-enregistrements-vidéo-en-direct)
    - [Fusion dans QuickTime](#fusion-dans-quicktime)
    - [Rognage dans QuickTime](#rognage-dans-quicktime)
    - [Correction de l'audio mono dans VLC](#correction-de-l'audio-mono-dans-vlc)
- [Création de vignettes](#création-de-vignettes)
- [Téléchargement sur YouTube](#téléchargement-sur-youtube)
- [Création avancée de vignettes](#création-avancée-de-vignettes)


### Annexe 1 - Utilisation de l'écosystème Apple

Le matériel informatique et les périphériques utilisés par Starlight sont basés sur l'écosystème MacOS. Il existe des distinctions significatives entre MacOS et Windows, notamment la disposition du clavier MacOS. Le clavier MacOS intègre les touches de contrôle (rouge), d'option (vert) et de commande (bleu). La touche de commande fonctionne de manière similaire à la touche Ctrl sous Windows, par exemple, Command + C équivaut à Ctrl + C, qui est le raccourci pour copier ; tandis que la touche d'option sert d'équivalent à Alt. Il est important de reconnaître que le comportement des programmes MacOS peut diverger de leurs homologues Windows en raison de leurs principes de conception distincts.

![](assets/2024-01-11-22-46-35.png)

### Annexe 1.1 - Capture d'écran

Pour prendre une capture d'écran, appuyez sur Commande + Maj + 3. Elle enregistrera la capture d'écran dans votre dossier bureau, situé à ~/Bureau ou au nom complet de /Utilisateur/Starlight/Bureau.

### Annexe 1.2 - Spotlight
Spotlight est un puissant outil de recherche disponible sur MacOS qui permet aux utilisateurs de localiser rapidement des fichiers, des dossiers et des applications. Pour accéder à Spotlight, appuyez simplement sur la combinaison de touches Commande + Espace. Cette fonction pratique est particulièrement utile pour résoudre les problèmes audio en accédant aux paramètres audio. 

### Limitation administrative

En raison de restrictions administratives strictes, les membres de l'équipe technique de Starlight sont interdits d'installer des applications supplémentaires sur les ordinateurs Starlight. Cependant, malgré cette contrainte significative, nous avons accès à un ensemble d'outils essentiels déjà installés sur les ordinateurs, notamment VLC, QuickTime, Google Chrome et ProPresenter. Ces outils fournissent une base de départ pour surmonter les limitations administratives et effectuer efficacement des tâches de traitement multimédia.

## Traitement des enregistrements vidéo en direct

Starlight enregistre en direct l'intégralité de la session de diffusion en direct et la sauvegarde sous forme de fichier vidéo. Cependant, nous devons uniquement télécharger la partie principale de la diffusion en direct sur YouTube. Par conséquent, il est nécessaire de rognée le fichier vidéo. De plus, il peut arriver que des problèmes d'enregistrement entraînent plusieurs fichiers, nécessitant leur fusion. Dans certains cas, l'audio peut également présenter des problèmes nécessitant une correction dans VLC. Cette section fournit des instructions sur l'utilisation de QuickTime et VLC pour rogner, fusionner et résoudre les problèmes audio.

### Fusion dans QuickTime

Dans le cas où nous rencontrons des problèmes d'enregistrement et que nous avons plusieurs fichiers vidéo, nous devons les fusionner. Pour les fusionner, ouvrez QuickTime et cliquez sur Édition > Ajouter des clips à la fin. Ensuite, sélectionnez tous les fichiers vidéo que vous souhaitez fusionner. Une fois terminé, cliquez sur Fichier > Exporter sous et donnez un nom à la vidéo.

![](assets/2024-01-21-20-03-49.png)

### Rognage dans QuickTime

Pour rogner une vidéo dans QuickTime, ouvrez le fichier vidéo dans QuickTime. Prévisualisez la vidéo et notez le timestamp, vous pouvez noter le timestamp dans l'application Notes par défaut d'Apple. Utilisez Commande + Entrée pour rechercher l'application Notes. Ensuite, cliquez sur Édition > Rogner. Vous pouvez faire glisser la barre jaune pour rogner la vidéo. Une fois terminé, cliquez sur Rogner. Ensuite, cliquez sur Fichier > Exporter sous > 1080p et donnez un nom à la vidéo.

![](assets/2024-01-21-20-04-41.png)

![](assets/2024-01-21-20-05-17.png)

### Correction de l'audio mono dans VLC

Parfois, l'audio peut provenir d'un seul canal et n'est pas adapté à YouTube. Il est préférable d'éviter ce problème en vérifiant la configuration audio avant la diffusion en direct. Cependant, si le problème audio est inévitable, nous pouvons le corriger dans VLC. Pour corr