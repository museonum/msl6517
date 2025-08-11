### La documentation d’exposition : retour d’expérience

Dans le monde dynamique des institutions culturelles, les archives d’exposition sont au cœur de l’histoire de l’institution. Les expositions représentent bien plus qu’une simple présentation d’œuvres d’art. Elles constituent une mine d’informations cruciales sur les œuvres exposées, offrant un contexte, une narration et une compréhension plus profonde de la biographie de l’œuvre. L’archivage des expositions devient une pierre angulaire pour la préservation de l’histoire institutionnelle, bien que cette tâche soit habituellement complexe et chronophage.

Cet article a pour objectif de soutenir le personnel des institutions muséales qui souhaitent produire une documentation raisonnée de leurs expositions. C’est une réponse aux questions que je me suis posées lorsque j’ai commencé à organiser la documentation d’exposition dans les institutions où j’ai travaillé. Je tends à définir ce qui se trouve dans les archives d’exposition, puis à fournir des bonnes pratiques et un guide pour mettre en place ce processus. Je finirai par proposer une amorce de réflexion sur une base de données de gestion de collection et de production événementielle mise en place pour une institution.

### L’archive d’exposition

La distinction entre exposition permanente et exposition temporaire ne repose plus uniquement sur des données temporelles d’accrochage. Il y a des expositions de collection (plus ou moins permanentes) et des expositions avec des prêts extérieurs (plus ou moins temporaires). Nous aborderons les deux types d’événements sous le terme exposition. L’exposition en ligne n’est pas au centre de cet article car elle interroge d’autres modalités de conservation.

Les avantages d’une bonne documentation d’exposition sont multiples. Lorsque les objets exposés font partie des collections de l’institution, cette documentation fournit des informations sur les œuvres, leur accrochage et leur biographie. Mais elle facilite aussi les itinérances et le processus de reconstitution de l’exposition elle-même[¹]. Elle permet également d’établir un catalogue de ressources des solutions techniques utilisées en scénographie pour des projets futurs. Elle constitue la mémoire d’événements centraux de l’institution.

L’archive est constituée par différents services, rarement rassemblée, bien qu’il existe dans certaines institutions des chargés d’archives ou de documentation dédiés à cette tâche. Constituer cette documentation est souvent complexe, généralement assemblée à la fin de l’exposition, rendant cette étape difficile. Cependant, le numérique, s’il est bien utilisé, peut grandement faciliter ce processus.

Les archives d’exposition sont consultées par certains services du musée mais aussi sur demande par des chercheurs extérieurs. Une partie peut être mise en ligne afin de rendre public l’historique événementiel de l’institution à une plus grande audience. Si la plupart des institutions mettent en ligne des informations sommaires (titre, dates, texte de présentation, liste des artistes exposés, quelques vues d’exposition), d’autres travaillent à un partage plus important d’archives en ligne. Prenons l’exemple du MoMA a collaboré avec Google Arts & Culture Lab sur un projet utilisant l’apprentissage automatique pour identifier les œuvres d’art dans les photos d’installation. Ces archives sont disponibles sur le [site de l’institution](https://www.moma.org/calendar/exhibitions/history/) et nous montrent l’importance d’une telle ressource d’informations pour l’Histoire de l’art.

Ces archives portent les meta-données[²] de l’exposition, mais où se trouvent-elles et de quoi sont-elles composées?

### Unir les forces des services

Une exposition n’est pas simplement un assemblage d’œuvres d’art éphémères. C’est un univers éphémère où contexte, dialogues entre les œuvres et narration s’entrelacent pour immerger les visiteurs. Chaque exposition, définie par son espace, son temps et la vision curatoriale qui l’anime, devient une expérience unique.

La documentation d’une exposition ne se résume pas à une simple liste des pièces exposées. Les composants d’une exposition vont au-delà des œuvres elles-mêmes : des textes descriptifs aux dispositifs interactifs, des éléments descriptifs, aux supports audiovisuels, etc. Ils tissent tous une trame narrative[³]. Elle englobe aussi les choix curatoriaux, les intentions artistiques, les processus de production de l’exposition mais aussi parfois les réactions des visiteurs.

L’élaboration d’une exposition au sein d’un musée implique une synergie complexe et organisée entre plusieurs services clés, chacun jouant un rôle essentiel pour la concrétisation et la réussite de l’événement. Ces services interagissent étroitement, combinant expertise artistique, logistique, communication et éducation pour garantir le succès d’une exposition. Leur collaboration permet de créer une expérience immersive et enrichissante pour les visiteurs, tout en assurant la préservation et la mise en valeur des œuvres exposées. Sommairement, ce schéma présente les traces laissées par les différents services s’ils étaient récupérés par la conservation :

![img](https://cdn-images-1.medium.com/max/1600/1*EwywV8uMq9lbrQ1m-poqzQ.jpeg)ill.1 : les services d’une institution et leur production d’archive pour les expositions

Chacun de ces services crée des archives selon la définition du [Glossaire PIAF 2015](https://www.piaf-archives.org/sites/default/files/bulk_media/glossaire/glossaire_papier.pdf) : « documents, quels que soient leur date, leur forme et leur support matériel, produits ou reçus par toute personne physique ou morale, et par tout service ou organisme public ou privé, dans l’exercice de leur activité. Le mot archives est couramment employé dans le sens restrictif de documents ayant fait l’objet d’un archivage, par opposition aux archives courantes. ». Pour constituer l’archive de l’exposition, il n’est pas forcement nécessaire de toutes les récupérer, il est possible de les lister et de décrire leur accessibilité. 

Un point important pour l’archive d’exposition sont les vues d’expositions. Fréquemment, ces photographies ne documentent pas certains aspects de l’exposition qui pourraient paraître triviaux. En effet, les photographies faites par un service d’archive ne se répondent pas au même cahier des charges que des vues d’exposition dédiées à la publication. Souvent un film ou des vues d’exposition faites au téléphone vont donner plus d’information qu’une belle vue d’exposition. 

Les sources d’information relatives à une exposition peuvent varier en termes d’accessibilité et de confidentialité. Il est très souvent difficile de récupérer les mails ou les archives des rencontres du curator. Certaines sont publiques, tandis que d’autres sont confidentielles, nécessitant une gestion appropriée de la confidentialité des données. Désormais les archives sont essentiellement numériques. Comment les conserver et les rendre disponibles à la consultation ?

### Le serveur

Afin de sensibiliser les différents services à la création de leurs archives, il est préconisé d’inclure la gestion des traces dans le processus de production d’exposition.

Les différents services utilisent souvent des logiciels distincts pour transmettre les informations sur les données physiques, généralement sous forme de listes Excel (Microsoft), envoyées par le cloud, par e-mail ou messagerie d’entreprise (type Slack). La gestion événementielle est généralement sous forme de calendrier (Google ou Outlook), ou des calendriers Excel, parfois suivant le diagramme de Gantt. La gestion de collection se fait habituellement sur des bases de données relationnelles propriétaires. Elles ne permettent sauf exception pas de gérer la production d’œuvre ou de projets.

Concernant le stockage des documents, il est crucial qu’ils ne soient pas stockés sur la machine de l’employé. La plupart des institutions travaillent sur des serveurs de fichiers en réseau pour limiter la duplication des documents. Ces solutions doivent être sécurisées pour protéger les données. Bien que cela ait un coût, cette action s’inscrit dans la démarche de [sobriété numérique](https://www.ethique.gouv.qc.ca/fr/actualites/ethique-hebdo/sobriete-numerique-avantages-et-limites-d-une-demarche-individuelle/), visant à réduire l’impact environnemental du numérique en limitant ses usages, et constitue un aspect de l’informatique durable.

Si chaque service gère ses archives de manière similaire, il est plus facile de garantir leur disponibilité. Inclure la procédure d’archivage pendant la phase de travail, avec un versionnage pour éviter les pertes, facilite le suivi des données. Il est alors important de discuter avec les équipes pour connaître leurs méthodes de travail, trouver des compromis pour une uniformisation sans contraintes excessives. Cette étape peut prendre plus de temps que prévu, car les individus sont parfois réticents au changement de leurs habitudes et appréhendent l’utilisation de nouvelles technologies. Cependant, il existe des [bonnes pratiques](https://cours.ebsi.umontreal.ca/sci6005/co/nommage.html) en termes de nommage de fichiers :

\- Évitez les espaces, points et caractères spéciaux (é, à, &, ?, !…)
\- Privilégiez le trait d’union ( — ), le symbole de soulignement (\_) ou la majuscule © pour séparer les éléments d’un nom de fichier.
\- Limitez la longueur des noms de fichier.
\- Datez tous les documents de la même manière, en début de nom de fichier, pour faciliter le tri : AAMMJJ ou AAAAMMJJ. Vous pouvez imposer une procédure de nommage, mais si elle est trop stricte, elle risque de ne pas être respectée.

Je recommande également de mettre en place une structure de dossiers (arborescence) fixe et commune, basée sur les pratiques de chacun, pour faciliter le travail dans les répertoires. Chaque individu a une logique différente, il est essentiel de prendre cela en considération, sinon les équipes risquent de contourner le serveur et travailler sur leur propre machine sans partager les fichiers.

Attention, certaines informations concernant la propriété ou la propriété intellectuelle sont confidentielles et ne peuvent pas être partagés à tous. Difficile à mettre en place sur un serveur il est pourtant essentiel de gérer les accès en fonction des droits utilisateurs. C’est une information importante à prendre en compte avant de partager des documents à des chercheurs. 

La gestion de collection est usuellement réalisée sur des bases de données relationnelles dépendant de logiciels propriétaires dans lesquelles sont stockées des informations. Serait-il possible d’inclure la dimension de gestion évènementielle pour créer les documents à partir de la base de données? 

### Base de données relationnelle

Nous l’avons vu, l’une des principales difficultés dans la constitution de l’archive d’une exposition réside dans sa création postérieure à l’événement lui-même. Comment garantir la conservation des archives pendant que les équipes travaillent ? Le cœur de l’archive récupérable est produit par les services de la conservation, gestion de collections, régie et production d’exposition. J’ai donc envisagé la création d’un schéma de base de données relationnelles afin de relier la base de données de gestion de la collection et de la production d’expositions. Ainsi, au lieu d’archiver les documents existants à plusieurs endroits, ces derniers sont créés à partir de la base de données qui concentre les métadonnées de l’exposition et des collections. Cela permet d’avoir un jeu de données uniforme pour tous, réduisant ainsi les erreurs et facilitant le partage d’information.

Voici comment je conçois l’organisation de l’exposition dans cette base de données [⁴]:

![img](https://cdn-images-1.medium.com/max/1600/1*6SjA45ftCl8uJA0MUsJjWg.jpeg)Ill.2 Schéma de relation du processus de production d’exposition

Tout d’abord, j’avance que la collection comprend des biens culturels composés d’éléments physiques ou non, dont les métadonnées sont conservées dans la base de données, et ce sont ces éléments que nous gérons. Par exemple, prenons une œuvre composée de 5 morceaux de bois de tailles différentes, dispersés avec de la cendre renouvelée à chaque exposition, et installés selon un plan spécifique.

Au-delà de l’œuvre en elle-même, ce sont les éléments qui sont prêtés et exposés (ou non), et c’est cela que nous gérons. Reprenons l’exemple : l’œuvre est exposée mais seulement trois morceaux de bois sont dans l’exposition et la cendre doit être fournie. Les deux autres éléments restent en réserves. Il faut pouvoir dire que l’œuvre se trouve à deux endroits différents, et qu’un des éléments doit être produit.

Ces trois éléments deviennent temporairement des expôts[⁵] lorsqu’ils entrent dans l’exposition. Ce sont ces expôts que nous gérons dans l’événement. Ces expôts peuvent être des œuvres, mais aussi du matériel d’exposition (multimédia, etc.). Par exemple, que fait-on dans le cas d’une œuvre multimédia, composée d’un film numérisé (dont le master est dans les réserves), projeté à l’aide d’un projecteur qui est loué sur un écran qui est propre à l’œuvre ? Le schéma de cette base de données permet de gérer les éléments de l’œuvre et de l’associer dans le projet au projecteur emprunté. Cela permet ainsi de garder l’information de l’activation de l’œuvre directement dans la base, de savoir exactement ce que nous avons utilisé comme matériel et comment. Ce système permet de gérer les œuvres éphémères ou performatives qui peuvent être composées d’éléments non physiques ou à produire et être ainsi “ prêtés ”.

Le projet quant à lui représente un événement dans lequel nous sélectionnons l’élément du bien culturel. Selon le type de projets, si c’est une exposition ou une restauration, nous pouvons renseigner toutes les informations nécessaires au projet et à son suivi afin de générer tous les documents liés à la logistique ainsi qu’à la documentation mais aussi conserver toutes les étapes de constitution du projet.

### Vers l’interopérabilité

Cette base de données va bien au-delà de simplement enrichir l’historique de l’institution et de faciliter le partage d’informations ou la création de documents. Elle offre un large éventail d’informations supplémentaires sur les collections. Les fiches des œuvres empruntées sont consciencieusement archivées une fois qu’elles quittent l’institution, garantissant ainsi la conservation des informations pertinentes. La possibilité de partager ces informations avec l’institution prêteuse est un aspect intéressant, bien que cela requière une uniformité des normes entre les institutions pour faciliter cette démarche.

L’interopérabilité entre différents systèmes et la normalisation des données (par le biais de standards comme [CIDOC-CRM](https://www.cidoc-crm.org/)) permettent de partager et d’échanger des informations entre les institutions, favorisant une approche collaborative et une gestion plus efficace des expositions et des collections. Nous pouvons donc nous poser la question, existe-t-il d’autres solutions que la base de données relationnelle pour gérer des données aussi complexes tout en améliorant l’interopérabilité ? Serait-il envisageable d’explorer les technologies du Web sémantique ? 





[¹]: en savoir plus sur la reconstitution d’exposition: [Mémoire de Florence-Agathe Dubé-Moreau, 2019](https://archipel.uqam.ca/12861/1/M16214.pdf) ou le travail de Camille Hoffsummer doctorante au sein du Service d’Histoire de l’art de l’époque contemporaine de l’Université de Liège. Elle prépare actuellement, sous la direction de Julie Bawin, une thèse consacrée au phénomène de réactivation et de patrimonialisation des expositions d’art moderne et contemporain des années 1960 à nos jours.
[²]: “Ensemble structuré de données accompagnant un ouvrage et servant notamment à en décrire le contenu et le format, à assurer son indexation dans les moteurs de recherche et les bases de données, et à faciliter la gestion des droits d’auteur qui y sont liés. \[…] Dans la perspective des entrepôts de données, les métadonnées sont un élément primordial et sont destinées à diverses catégories d’utilisateurs. Elles permettent notamment de connaitre l’origine et la nature des données stockées dans l’entrepôt, de comprendre comment elles sont structurées, de savoir comment y avoir accès et comment les interpréter, de connaître les différents modèles de données en présence et les règles de gestion de ces données. Donnée qui renseigne sur la nature de certaines autres données et qui permet ainsi leur utilisation pertinente. (Office québécois de la langue française. « Métadonnées», dans Le grand dictionnaire terminologique)” source cours MSL6517-A-A23 — Inventaires et traitement des données d’Emmanuel Château-Dutier de l’Automne 2023 à l’Université de Montréal.
[³]:Davallon, Jean. 1999
[⁴]: Base de données développée sur Filemaker Pro avec [Novarem](https://www.novarem.com/). Aujourd’hui diffusée sous le nom de Novart. Un projet similaire avait été amorcé mais n’a jamais abouti : [Monnin, Alexandre, Jérôme Denis, et Nicolas Delaforge. 2016.](https://doi.org/10.3917/i2d.162.0052)
Pour connaitre les différences entre les différents types de base de données, lire le chapitre 2 de [Hooland, Seth van, Florence Gillet, Simon Hengchen, et Max De Wilde. 2016.](https://www.cairn.info/introduction-aux-humanites-numeriques-methodes--9782807302150.htm)
[⁵]: différentes définitions du mot expôt dans l’article de [Chaumier, Serge. 2011.](https://doi.org/10.3917/herm.061.0045) 


**Bibliographie**

Baca, Murtha, et Getty Research Institute, éd. 2016. *Introduction to Metadata*. 2nd ed. Los Angeles, CA: Getty Research Institute.

Chaumier, Serge. 2011. « Les écritures de l’exposition ». *Hermès, La Revue* 61 (3): 45‑51. https://doi.org/10.3917/herm.061.0045.

Château-Dutier, Emmanuel. 2023. Cours *MSL6517-A-A23 — Inventaires et traitement des données* l’[Université de Montréal](http://www.umontreal.ca/).

Davallon, Jean. 1999. *L’exposition à l’œuvre : stratégies de communication et médiation symbolique*. Communication et civilisation. Paris: L’Harmattan. https://catalogue.bnf.fr/ark:/12148/cb37106747j.

Dubé-Moreau, Florence-Agathe. 2019. *Reprendre en écho(s). effets et enjeux de la reconstitution d’exposition en art contemporain*, Mémoire de fin d’étude à l’UQAM, https://archipel.uqam.ca/12861/1/M16214.pdf

Dufour, Christine. 2020. site Web du cours *SCI6005 — Information numérique et informatique documentaire* de l’[Université de Montréal](http://www.umontreal.ca/).

Hooland, Seth van, Florence Gillet, Simon Hengchen, et Max De Wilde. 2016. *Introduction aux humanités numériques : Méthodes et pratiques numériques en sciences humaines et sociales*. Méthodes en sciences humaines. Louvain-la-Neuve: De Boeck supérieur.

Monnin, Alexandre, Jérôme Denis, et Nicolas Delaforge. 2016. « Re-Source, une archive en temps réel pour la publication et la production ». *I2D — Information, données & documents* 53 (2): 52. https://doi.org/10.3917/i2d.162.0052.