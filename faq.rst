Foire Aux Questions (FAQ)
=========================

Vous trouverez ici les réponses à des questions courantes.

*Géofoncier ne répond plus! Que faire ?*
	
	Si l’application Géofoncier semble ne plus répondre, la meilleure méthode consiste à rafraichir la page de votre navigateur. Si le problème persiste, lorsque vous êtes connecté au portail, appuyer simultanément sur les touches CTRL + F5 de votre clavier pour recharger complètement le code de l’application.

*À certaines échelles l’écran devient blanc, est-ce normal ?*
	
	Certaines couches de données ne sont visualisables que dans une certaine plage d’échelle. Consulter le chapitre 6 pour connaitre les échelles d’affichage des différentes couches de données. Un usage trop «violent» de la molette de la souris pour changer l’échelle de la carte peut aussi provoquer ce phénomène; il suffit alors de patienter quelques instants pour que les données puissent se charger.

*Où puis-je obtenir la date de mise à jour des données IGN ?*
	
	Les dates de mise à jour sont fournies par l’IGN. Consulter le chapitre `Thème Géoportail IGN <donnees.html#theme-geoportail-ign>`_ pour connaitre la façon d’obtenir ces informations.

*Je ne parviens pas à me localiser sur une parcelle dont les références cadastrales sont pourtant actives ?*
	
	Il s’agit à n’en pas douter d’un problème de mise à jour. Pour connaitre le millésime de la BD parcellaire disponible sur votre département, consulter le chapitre `Thème Géoportail IGN <donnees.html#theme-geoportail-ign>`_.

*J’ai remarqué que la localisation sur une adresse postale ne localise pas la carte au bon endroit ?*
	
	Pour la localisation à l’adresse postale, Géofoncier s’appuie sur un service fourni par l’IGN. L’outil de géocodage mis en œuvre interpoleles numéros de voirie. Ainsi un numéro de voirie est situé dans la bonne rue mais pas à l’emplacement exact de la plaque adresse (contrainte CNIL).

*Pourquoi certains de mes dossiers sont-ils mal localisés ?*
	
	L’ensemble des dossiers versé à l'époque d'Aurige (avant Géofoncier) ont été localisés à partir des coordonnées fournies dans Aurige. Des contrôles de cohérence ont été réalisés après uniformatisation de la projection (une projection unique par territoire). Tous les dossiers présents dans Géofoncier ont l’assurance d’être positionnés «sur la bonne commune», c'est-à-dire que le localisant du dossier est bien situé sur la commune dont le code INSEE correspond avec celui spécifié dans le dossier.

	Si vous détectez un dossier mal positionné vous appartenant, il est possible de déplacer son localisant en éditant sa fiche (cf. `Interrogation couche dossier <outils.html#interro-dossier-interrogation-de-la-couche-dossiers>`_ ).

*Est-il possible de supprimer un dossier erroné ?*
	
	Oui, tout à fait! Cela est faisable pour tous les dossiers que détient votre structure. Il vous faut rechercher le dossier avant de pouvoir le supprimer (cf. `Rechercher parmi ses dossiers <outils.html#recherche-parmi-ses-dossiers>`_ ).

*Est-il possible de renommer un dossier erroné ?*
	
	Il n’est pas possible de renommer un dossier Géofoncier. La seule perspective envisageable est de supprimer le dossier erroné puis de le verser/créer à nouveau avec la référence correcte.

*Quelles sont les règles de transferts des dossiers dans la version grand public ?*
	
	Pour connaitre le détail des règles de transfert des dossiers dans la version grand public, il suffit de prendre connaissance de l’écran «Version grand public» accessible via l’outil «diagnostic de mes dossiers» (cf. `Diagnostic de mes dossiers <outils.html#diagnostic-de-mes-dossiers>`_). Cette fonction permet par ailleurs d’être informé à tout moment des dossiers pour lesquels il manque des informations nécessaires à leur transfert.

*Quelles sont les opérations à versement obligatoire ?*

	Le détail des opérations à versement obligatoire (c’est-à-dire les dossiers qui doivent être saisies dans Géofoncier) est fourni au chapitre `Création de dossier <outils.html#creation-de-dossier>`_.
