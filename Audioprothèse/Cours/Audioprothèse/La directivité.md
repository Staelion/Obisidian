>[!WARNING]
>Directivité : manière dont le micro capte les sons en fonction de leur provenance
>
>En résumé :
>- Meilleur moyen d'améliorer la compréhension dans le bruit
>- Tout les ACA actuels possèdent deux micros omnidirectionnels
>- la complexité des traitements de signaux dépend des gammes 
>- On apprécie la directivité à l'aide des diagrammes polaires et l'index de directivité
>- L'oreille naturelle possède une directivité différentes entre les aigus et les graves

>[!INFO]+ Fonctionnement d'un microphone
>
>Les microphones utilisent longtemps la technologie de l'électret :
>
Electret : technologie utilisée pour transformer l’énergie acoustique en électrique et électrique a mécanique, technologie utilisée dans les micros de toutes les tailles
Quand les technologies sont différentes c’est une bobine ou une membrane
Electret est un micro condensateur variable (2 armatures bougent par rapport a l’autre par des variations sonores)
![[Pasted image 20231203214649.png]]  
>Le fonctionnement du microphone repose sur la transformation du mouvement de la petite membrane en un courant électrique à l'aide des plaques d'électret. Il comporte une entrée connectée à l'extérieur, la membrane elle-même, et des fils électriques pour capter le son. Ce dispositif peut également être désigné comme un capteur de pression, car le signal de sortie reflète la pression acoustique.

>[!INFO]+ Directivité
>- Le micro omnidirectionnel
>Le micro omni est le premier type de micro inventé, il utilise le fonctionnement simple à l'aide de la technologie de l'électret.
>
>Le système, inventé par Phonak, est analogique avec un début de traitement numérique. Actuellement, tous les appareils auditifs sont équipés de deux micros omnidirectionnels. En utilisant un effet de micro directionnel, le son provenant de chaque micro est mixé avec un retard pour le micro arrière, créant ainsi un gradient qui réalise la soustraction électrique des deux signaux.
>Cependant, il y a des inconvénients à ce système. Le patient doit effectuer manuellement l'intervention pour changer le programme, généralement avec un bouton sur le côté de l'appareil auditif, sans coordination entre les deux appareils auditifs. De plus, malgré ces modes, l'appareil auditif peut toujours être gênant dans un environnement bruyant, ce qui peut être insuffisant pour certaines situations.
>
>- Le micro directionnel simple
>  
>  Le micro directionnel à ensuite été inventé et se base sur un système de retard vu précédemment ainsi que sur les oppositions de phases. En plus de l'entrée principale qui envoie la pression acoustique sur la membrane, une deuxième entrée de son est crée de l'autre côté de l'ACA, mais cette fois si la pression acoustique est envoyée de l'autre coté de la membrane.
>  ![[Pasted image 20231204110333.png]]
>  On agit sur les phases de manière à optimiser la captation des sons.
>  - Lorsque le son provient de l'avant, la membrane se met en mouvement. Le son entre par l'avant, déplace la membrane, puis fait le tour pour entrer par l'arrière avec un léger retard induit par le filtre acoustique. Les ondes étant en phase, une variation de pression acoustique entre le dessus et le dessous de la membrane provoque son oscillation, permettant la captation du son frontal. L'effet d'écho est évité, car le cerveau n'interprète le retard que pour des écarts d'environ 15 millisecondes, tandis que dans ce cas, l'ordre de grandeur est à la microseconde.
>  - Lorsque le son provient de l'arrière, la membrane reste immobile. Le son arrive de l'arrière avec un retard induit par le filtre acoustique, et pendant ce temps, le son fait le tour pour entrer par l'avant. Les ondes étant en opposition de phase, la membrane ne bouge pas, ce qui **théoriquement** signifie l'absence de son provenant de l'arrière.
>  
>  
>- Le double microphone adaptatif
>
>Début des IA simples. Ajout des dispositifs de surveillance  pour enregistrer les réglages effectués ainsi que les retours des utilisateurs. Ces appareils ajustent constamment leurs paramètres en fonction du contexte, réadaptant régulièrement le retard (T) et le taux du signal du micro arrière. L'objectif est d'obtenir un diagramme polaire circulaire, masquant ainsi le bruit de fond, tel que le bruit d'un vidéoprojecteur dans une salle de classe.
>Les utilisateurs peuvent donner des indications à l'appareil sur la façon d'agir dans différentes situations, mais l'appareil est également capable de détecter l'environnement par lui-même. Il peut faire la distinction entre le bruit du vidéoprojecteur et la voix grâce à la détection de la modulation d'amplitude : l'absence de modulation suggère une faible probabilité de parole.
>Le diagramme polaire, dont la forme peut varier entre le cercle et le cardioïde en fonction de l'acoustique de la tête, joue un rôle crucial dans ces mécanismes continuellement variables et adaptables.
>![[Pasted image 20231204111739.png]]
>
>- Double micro adaptatif a directivité partielle
>
>Microphone dont la directivité est indépendante et automatique dans différentes bandes de fréquences, par exemple, on peut être en omni dans les graves (100-500 Hz = tous les sont captés de la même manière) et cardioïde entre 1000 et 2000Hz.
>Il permet d’éviter un effet directionnel dans les basses fréquences. Il peut simuler la directivité naturelle mais il est insuffisant dans le bruit 
>On retrouve ce système dans de nombreux appareils actuels
>![[Pasted image 20231204114312.png]]
>
>- Micro directionnel adaptatif à directivité partielle et par croisement des micros des appareils gauche et droit
>
>On fusionne deux micros pour faire un faisceau directionnel plus étroit et donc avoir un ID plus important ; Plus on rajoute de micros plus on aura un faisceau étroit.
>Il y a phonak, oticon (siemens ?) qui font ces fusions de micros
>Ce système permet de gagner encore une dizaine de dB, mais fusionne les deux ACA donc on passe en mono -> moins de stéréo pour le patient.
>
>- Index de directivité
>L'index de directivité est une valeur obtenue à l'aide de deux mesures permettant d'évaluer le niveau de dir. d'un ACA.
>
>La première mesure consiste à allumer uniquement le haut-parleur frontal, réglé à un niveau sonore de 60 dB SPL au niveau de l'appareil, et à mesurer le niveau de sortie délivré par l'appareil dans le coupleur 2cc (L1 = 105 dB SPL).
Pour la deuxième mesure, tous les haut-parleurs sont allumés, émettant le même son et réglés de manière à maintenir un niveau sonore de 60 dB SPL au niveau du microphone. Si le microphone est omnidirectionnel, le niveau de sortie mesuré dans le coupleur 2cc est L2 = 105 dB SPL, donnant un Index de Directivité (ID) de 0 dB. Un microphone omnidirectionnel ne fait aucune différence entre un son provenant de l'avant et un son provenant de toutes les directions.
Cependant, si le microphone est directionnel, le niveau de sortie mesuré dans le coupleur 2cc (L2) sera inférieur à 105 dB SPL, indiquant une zone d'ombre de captation d'énergie. L'Index de Directivité (ID) en dB est calculé comme ID = L1 - L2. Un ID plus élevé suggère une réduction plus importante du bruit environnant, tandis qu'un ID négatif indique une sensibilité réduite aux sons provenant de l'avant par rapport à ceux provenant de toutes les directions.

>[!INFO]+ Diagrammes polaires


