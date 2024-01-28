```markdown
Version française : [README.French.md](README.French.md) |
Version anglaise : [README.md](README.md) |
Version chinoise simplifiée : [README.zh-CN.md](README.zh-CN.md) |
Version chinoise traditionnelle : [README.zh-TW.md](README.zh-TW.md)

L'objectif de cette procédure opérationnelle standard (SOP) complète est de fournir des orientations approfondies et une formation aux membres de l'équipe technique de Starlight sur l'utilisation efficace des outils de traitement multimédia, notamment Canva, VLC et QuickTime. Cette SOP est spécifiquement conçue pour doter les nouveaux membres de l'équipe technique de Starlight des connaissances et compétences nécessaires pour organiser, créer et traiter efficacement des éléments multimédias pour les plateformes en ligne de Starlight. En suivant cette SOP, les membres de l'équipe acquerront une base solide en traitement multimédia, leur permettant d'améliorer la qualité et l'impact de la présence en ligne de Starlight.

## Table des matières
- [Annexe](#annexe-1---utilisation-de-l'écosystème-apple)
    - [Annexe 1 - Utilisation de l'écosystème Apple](#annexe-1---utilisation-de-l'écosystème-apple)
    - [Annexe 1.1 - Capturer une capture d'écran](#annexe-11---capturer-une-capture-d'écran)
    - [Annexe 1.2 - Spotlight](#annexe-12---spotlight)
- [Traitement des enregistrements vidéo en direct](#traitement-des-enregistrements-vidéo-en-direct)
    - [Fusion dans QuickTime](#fusion-dans-quicktime)
    - [Découpage dans QuickTime](#découpage-dans-quicktime)
    - [Correction de l'audio mono dans VLC](#correction-de-l'audio-mono-dans-vlc)
- [Création de vignettes](#création-de-vignettes)
- [Téléchargement sur YouTube](#téléchargement-sur-youtube)
- [Création avancée de vignettes](#création-avancée-de-vignettes)


### Annexe 1 - Utilisation de l'écosystème Apple

Le matériel informatique et les périphériques utilisés par Starlight sont basés sur l'écosystème MacOS. Notamment, il existe des distinctions significatives entre MacOS et Windows, y compris la disposition du clavier MacOS. Le clavier MacOS intègre les touches de contrôle (rouge), d'option (vert) et de commande (bleu). La touche de commande fonctionne de manière similaire à la touche Ctrl sous Windows, par exemple, Command + C est équivalent à Ctrl + C, qui est le raccourci pour copier ; tandis que la touche d'option sert d'équivalent à Alt. Il est important de reconnaître que le comportement des programmes MacOS peut diverger de leurs homologues Windows en raison de leurs principes de conception distincts.

![](assets/2024-01-11-22-46-35.png)

### Annexe 1.1 - Capturer une capture d'écran

Pour prendre une capture d'écran, appuyez sur Commande + Maj + 3. Elle enregistrera la capture d'écran dans votre dossier bureau, situé à ~/Bureau ou le nom complet de /Utilisateur/Starlight/Bureau.

### Annexe 1.2 - Spotlight
Spotlight est un puissant outil de recherche disponible sur MacOS qui permet aux utilisateurs de localiser rapidement des fichiers, des dossiers et des applications. Pour accéder à Spotlight, appuyez simplement sur la combinaison de touches Commande + Espace. Cette fonction pratique est particulièrement utile pour résoudre les problèmes audio en accédant aux paramètres audio.

### Limitation administrative

En raison de strictes limitations administratives, les membres de l'équipe technique de Starlight sont interdits d'installer des applications supplémentaires sur les ordinateurs de Starlight. Cependant, malgré cette contrainte importante, nous avons accès à un ensemble d'outils essentiels déjà installés sur les ordinateurs, y compris VLC, QuickTime, Google Chrome et ProPresenter. Ces outils fournissent une base de départ pour surmonter les limitations administratives et effectuer efficacement des tâches de traitement multimédia.

## Traitement des enregistrements vidéo en direct

Starlight enregistre la session de livestream et la sauvegarde sous forme de fichier vidéo. Cependant, nous devons uniquement télécharger la partie principale du livestream sur YouTube. Il est donc nécessaire de découper le fichier vidéo. De plus, il peut arriver que des problèmes d'enregistrement entraînent plusieurs fichiers nécessitant une fusion. Dans certains cas, l'audio peut également poser problème et nécessiter une correction dans VLC. Cette section fournit des instructions sur l'utilisation de QuickTime et VLC pour découper, fusionner et corriger les problèmes audio.

### Fusion dans QuickTime

En cas de problèmes d'enregistrement et de fichiers vidéo multiples, il est nécessaire de les fusionner. Pour les fusionner, ouvrez QuickTime et cliquez sur Édition > Ajouter des clips à la fin. Ensuite, sélectionnez tous les fichiers vidéo que vous souhaitez fusionner. Une fois terminé, cliquez sur Fichier > Exporter sous et donnez un nom à la vidéo.

![](assets/2024-01-21-20-03-49.png)

### Découpage dans QuickTime

Pour découper une vidéo dans QuickTime, ouvrez le fichier vidéo dans QuickTime. Prévisualisez la vidéo et notez le timestamp. Vous pouvez noter le timestamp dans l'application Notes par défaut d'Apple. Utilisez Commande + Entrée pour rechercher l'application Notes. Ensuite, cliquez sur Édition > Découper. Vous pouvez faire glisser la barre jaune pour découper la vidéo. Une fois terminé, cliquez sur Découper. Ensuite, cliquez sur Fichier > Exporter sous > 1080p et donnez un nom à la vidéo.

![](assets/2024-01-21-20-04-41.png)

![](assets/2024-01-21-20-05-17.png)

### Correction de l'audio mono dans VLC

Parfois, l'audio ne sort que d'un seul canal et n'est pas adapté à YouTube. Il est préférable d'éviter ce problème en vérifiant la configuration audio avant le livestream. Cependant, si le problème audio est inévitable, nous pouvons le corriger dans VLC. Pour corriger l'audio, ou