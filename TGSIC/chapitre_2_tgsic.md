## 2. LE TEMPS DES INGÉNIEURS

### THERMODYNAMIQUE ET ENTROPIE

Les théoriciens de la télécommunication se sont servis d'outils, mathématiques déjà existants, en l'occurrence ceux de la thermody­namique et de la mécanique statistique.

Première source artificielle d'énergie applicable à l'industrie, la machine à vapeur avait déjà posé des problèmes de rendement aux chercheurs. En 1824, le physicien Sadi Carnot publia une petite brochure intitulée: *Réflexions sur la puissance motrice du feu et les machines propres à développer cette puissance* (1). Comme plus tard celle de Shannon, cette mise au point était l'aboutissement d'un grand nombre de recherches et de tâtonnements antérieurs. On y trouve formulé, outre le principe de l'équivalence du travail et de la chaleur, ce qui est appelé le « principe de Carnot » et qui s'énonce maintenant de la manière suivante: « Une machine thermique ne peut fonctionner sans qu'il passe de la chaleur d'une source chaude sur une source froide. » 

En 1850 le physicien allemand Rudolf Emmanuel Clausius (2) donna de ce principe la formulation suivante: « La chaleur ne peut passer d'elle-même d'un corps froid à un corps chaud. » De là il tira en 1876 la notion d'*entropie*.
C'est une quantité qui s'exprime par l'intégrale

<a href="https://www.codecogs.com/eqnedit.php?latex=\int&space;\frac{dQ}{T}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\int&space;\frac{dQ}{T}" title="\int \frac{dQ}{T}" /></a>

où dQ est la quantité de chaleur cédée par une source chaude à un système mécanique et T la température absolue à laquelle s'effectue l'opération. Dans le cas d'une machine parfaite fonctionnant en cycle fermé, cette quantité reste constante: le gaz contenu dans le, cylindre d'une machine perd de la chaleur à mesure qu'il fournit du travail en poussant le piston, mais si l'on restitue ce travail en repoussant le piston en sens inverse, il récupère la même quantité de chaleur.

Si la chaleur est cédée sans l'interposition d'un système mécanique
qui la transforme en travail, l'entropie augmente. C'est ce qui se passe,
par exemple, quand le gaz cède aux parois du cylindre une partie de sa

***
1. Sadi Carnot (1796-1832), fils du « Grand Carnot» et oncle du futur Président de
la République, ancien polytechnicien, a participé comme officier du génie aux derniers
combats de l'Empire. Sa brochure, tirée à 200 exemplaires, a longtemps été ignorée et sa
portée n'en fut comprise que bien des années plus tard par les physiciens Kelvin et Clapeyron.
" .
2. C'est dans son ouvrage Uber die bewegende Kraft der Wiirme (1850) que Clausius,
alors professeur de physique à l'école d'artillerie de Berlin, a reformulé le principe de Carnot .

***

chaleur qui est rayonnée vers l'extérieur et devient irrécupérable, puis­ qu'elle ne peut revenir d'elle-même de la source froide constituée par l'air ambiant vers la source chaude constituée par le cylindre.

En aucun cas l'entropie ne peut diminuer, ce qui revient à dire que si l'énergie se conserve, elle prend des formes de moins en moins utili­sables. La chaleur par exemple n'est jamais entièrement transformable en énergie mécanique. C'est ce qu'on appelle la dégradation de l'énergie.

On voit immédiatement le parti qui peut être tiré de la notion d'en­tropie pour la recherche d'un meilleur rendement des machines ther­miques. Il est remarquable qu'une telle théorie n'ait été formulée que deux siècles après l'apparition des premières machines à vapeur et un siècle après que James Watt (3), pressentant par la pratique ce qui devait devenir le principe de Carnot, eut donné à ce type de machine un rendement assez acceptable pour que des applications industrielles puissent etre mises en œuvre.

On peut d'ailleurs noter par parenthèse que le perfectionnement le plus important apporté par Watt à la machine à vapeur est le tiroir. C'est un dispositif mécanique que l'on peut décrire comme un système de communication et plus précisément de *feedback*, c'est-à-dire de réin­jection de l'information. Pièce coulissante commandée par le mouvement du piston, le tiroir commande alternativement l'admission de la vapeur de part et d'autre du piston, produisant ainsi ce qu'on appelle le « double effet ». En d'autres termes, on peut dire que le tiroir, utilisant un vecteur mécanique pour transmettre l'information, « fait savoir » à la machine que, le piston ayant achevé sa course, un état d'équilibre est atteint et lui « donne l'ordre » d'injecter la vapeur sur l'autre face, ce qui replace le système en état de déséquilibre et amorce un nouveau cycle.

L'ingénieur a donc très largement précédé le théoricien. Il y a là un schéma sur lequel il est utile d'insister car nous le retrouvons dans le cas de la technologie de l'information. L'invention proprement dite vient souvent d'une idée fortuite comme la marmite de Denis Papin, idée qui est parfois le sous-produit d'un bricolage scientifique comme le cohéreur de Branly. Puis vient le technicien, l'ingériieur, le praticien - Watt pour la machine à vapeur, Edison pour l'électricité, Marconi pour les ondes hertziennes - qui invente le dispositif capable de donner à l'idée initiale un rendement acceptable et donc susceptible d'appeler l'investissement des capitaux. Notons que Gutenberg se situe très exactement à ce stade dans le développement de l'imprimerie.
Dès lors, c'est l'investissement qui commande, exigeant une rémunération et donc un rendement toujours accrue. A partir de la découverte de l'énergie artificielle et l'invention de Gutenberg a stagné plus de deux siècles jusqu'à ce moment , la technologie devient suffisamment raffinée et complexe pour justifier des investissements spéciaux consacrés à la recherche systématique du rendement.
C'est alors qu'entrent en scène les théoriciens et que peut vraiment se développer une recherche fondamentale utilisant l'outil mathématique.

***
3. L'Ecossais James Watt (1736-1819) était avant tout un ingénieur praticien. C'est en 1767 qu'il réalisa la première machine à vapeur opérationnelle et en 1776 la machine à double effet grâce, notamment, au dispositif du tiroir.

***
### GÉNÉRALISATION DE L'ENTROPIE
Le souci principal des théoriciens mathématiques est la généra­lisation, c'est-à-dire le processus par lequel la formule descriptive d'un phénomène particulier (comme l'intégrale de Clausius) peut être ramenée à un modèle plus général, rendant compte d'un plus grand nombre de phénomènes.

La notion d'entropie a été généralisée dès la fin du XIXe siècle par la mécanique statistique et notamment par le physicien autrichien Ludwig Boltzmann (4). Considérant que chaque état macroscopique d'un gaz peut être réalisé par un certain nombre de « complexions » microscopiques dépendant de la position et de la vélocité des molécules qui le composent, Boltzmann en a déduit que cet état est d'autant plus probable que le nombre des complexions qui peuvent le réaliser est grand. L'entropie est proportionnelle à la probabilité, d'où la formule qu'on a gravée sur son tombeau:
S = *k* log W
où S est l'entropie, W la probabilité de l'état thermodynamique d'un gaz et k une constante dite « constante de Boltzmann » (1,381 x 10-16 C.G.S.).
Nous citons ici la formule de Boltzmann parce que sa structure logarithmique et probabiliste a servi plus tard de modèle aux théoriciens de l'information.

Mouvement irréversible, l'augmentation de l'entropie apparaît donc comme l'évolution d'un ordre différencié vers un désordre indiffé­rencié ou, si l'on préfère, d'une prévisibilité quantifiable vers une imprévi­sibilité aléatoire. Par exemple nous savons que la température d'un gaz est liée à l'énergie cinétique de translation des molécules qui le composent. Si une certaine quantité de ce gaz est répartie entre un espace « chaud » et un espace « froid », il est possible de calculer la vélocité et la position des molécules, c'est-à-dire qu'on peut définir là un système et évaluer son énergie disponible. On peut récupérer celle-ci en faisant passer les molécules de l'espace « chaud » dans l'espace « froid », ce qui produit un travail utilisable moyennant un dispositif mécanique, mais aboutit à une situation d'équilibre où les molécules sont distribuées de manière aléatoire. Bien que leur énergie cinétique totale reste la même, il devient impossible, en vertu du principe de Carnot, de tirer d'elles du travail.

***
4. Ludwig Boltzmann (1844-1906) est à l'origine de nombreuses théories mathéma­tiques qui ont joué un rôle décisif dans l'évolution de la physique nucléaire et atomique, notamment la *théorie des quanta*.

***
On ne peut le faire qu'à condition de considérer chaque molécule
comme un système organisé à l'intérieur duquel la distribution des atomes n'est pas aléatoire. Pour récupérer l'énergie intra-moléculaire d'un tel système, il faut « faire craquer » les molécules. C'est ce qui se produit dans une réaction chimique, une combustion par exemple - ce qui explique qu'un moteur à combustion interne ait un rendement supérieur à celui d'une machine à vapeur.

On peut aller encore au-delà et « faire craquer » l'organisation interne de l'atome, voire du noyau de l'atome. C'est le principe de l'énergie atomique, puis nucléaire, qui, après récupération du travail (malheureu­sement jusqu'ici par une méthode à faible rendement de réchauffement de fluides), aboutit à un état stable de la matière et, à la limite, à une répartition aléatoire des particules d'énergie.

Dans la mesure où l'univers connu peut être considéré comme une gigantesque machine nucléaire, cette notion sous-tend la plupart des grandes théories cosmogoniques modernes, notamment celles qui supposent une expansion de l'univers à partir d'un noyau initial à l'en­tropie minimale. Certaines de ces théories, pour fuir la fatalité de cette évolution à sens unique, envisagent une alternance cyclique d'expansions et de contractions, auquel cas on pourrait dire que l'univers fonctionne comme une machine de Carnot parfaite à entropie constante à la fin de chacun de ses cycles. D'autres théories, comme celle du physicien anglais Frederick Hoyle, envisagent la création permanente d'atomes dans l'univers et donc une diminution compensative de l'entropie. Les unes et les autres de ces théories font apparaître la notion d'une anti­ entropie à laquelle on a donné le nom de *nég-entropie*.

La biologie a été attirée par la notion d'entropie, puis plus récemment par celle de nég-entropie dans la mesure où elles permettent de rendre compte du processus de l'évolution. En effet une des lois fondamentales de ce processus semble être l'accroissement de la complexité morpho­logique des espèces, c'est-à-dire l'accroissement de la différenciation, de la spécialisation, de l'organisation, en un mot d'un certain ordre. Le mouvement de la vie serait donc inverse de celui de la matière et correspondrait à une diminution constante de l'entropie. L'évolution darwinienne est en fait nég-entropique (5).
Il est tentant d'aller plus loin. Un philosophe français, André
Lalande, l'a fait dès 1899 dans sa thèse de doctorat (6), mettant en opposition l'entropie des physiciens et l'évolution des biologistes.

***
5. On trouvera une excellente discussion de ce problème dans l'article « The Concept of Evolution » du chapitre « Evolution » (par R.C. Lewontin) de l'*International Encyclopedia of the Social Sciences*, vol. 5, pp. 202-210.
6. Le titre en est *L'idée directrice de dissolution opposée à celle d'évolution dans la méthode des sciences physiques et morales*. Lalande est célèbre pour son *Vocabulaire philo­sophique* (1902-1923).

***

En 1930 il dénonçait les « illusions évolutionnistes» dans les domaines intellectuel, moral et social en proposant la notion d'*involution* (7), fi s'agit d'un mouvement entropique caractérisé par un accroissement des similitudes et de l'indifférenciation.

Si elle n'est guère acceptable sous sa forme primitive, l'idée de Lalande est séduisante et présente au moins le mérite de tenter une synthèse du phénomène entropique, Il s'en faut cependant de beaucoup qu'elle puisse être considérée comme une théorie générale. La spécu­lation franchit ici la frontière entre la science et la philosophie.

Sans un outil de quantification adéquat, la transposition de l'entropie et de la nég-entropie dans le domaine des sciences sociales ne peut guère dépasser le stade des métaphores attrayantes. La notion de progrès, par exemple, peut y trouver une nouvelle formulation. Il serait aisé de renouveler brillamment le classique débat scolaire entre Voltaire et Rousseau en disant par exemple que l'un a une vision nég-eritropique et l'autre une vision entropique de l'évolution des institutions humaines. On pourrait aussi montrer le contraire car le raisonnement par métaphore n'a d'autre effet que de masquer les réalités et, en l'occurrence, les réalités idéologiques. Décrire l'histoire, ainsi que l'a fait en d'autres termes Paul Valéry, comme une alternance de périodes entropiques et de périodes nég-entropiques, ne serait qu'une façon de ramener les mouvements révolutionnaires à des épisodes cycliques à l'intérieur d'une machine de Carnot où « plus cela change, plus c'est la même chose ».

C'est cependant peut-être l'idée de *modèle répétitif* qui peut aider
les sciences de l'homme à tirer partie des notions d'entropie et de nég­-entropie. La biologie intracellulaire fait usage de la notion de « programmes » transportés par des « messagers » qui sont les gènes, dans la molécule d'A.D.N. Le programme est l'inscription par le messager, au moyen d'un code chimique, du modèle d'une certaine organisation, d'un certain ordre. Il tend à maintenir au niveau *phylo­génique* (celui de l'espèce) une entropie constante, alors qu'au niveau *ontogénique* la vie de l'individu se caractérise par une période nég­-entropique, suivie d'une période entropique. Mais parfois il y a des incidents de communication qui impliquent des modifications du programme. Ces modifications sont des mutations qui peuvent avoir un caractère nég-entropique comme dans le cas des adaptations au
milieu, ou entropique comme dans le cas du cancer (8).

Nous sommes ici ramenés au schéma de la communication au sens où elle est transfert d'information. Il est donc probable que, dès qu'on passe du mécanique au vivant et plus encore du vivant à l'humain, un nouvel outil épistémologique devient nécessaire. Cet outil est sans doute la notion d'information. Nous pouvons hasarder l'hypothèse que cette notion est structurellement liée à celle d'entropie, mais qu'elle en diffère par le fait qu'elle prend en compte deux éléments laissés de côté par la science physique: la vie et surtout la pensée.

***
7. Dans *Les illusions évolutionnistes* (1930).
8. L'A.D.N. est l'*acide désoxyribonucléique* qui est le constituant de base du noyau cellulaire et des chromosomes. Le *gène*, élément chimique autocatalytique (c'est-à-dire susceptible de se reproduire), est porteur des éléments du patrimoine héréditaire.

***
### CHAOS ET COSMOS

Toutes les religions cosmogoniques ont décrit la création comme le passage d'un état de désordre indifférencié (le *khaos* des Grecs, le *tohu ve bohu* de la Bible) à un ordre organisé (le *kosmos* des Grecs, le *mondus* des Latins repris par le christianisme). De toute évidence la création est décrite comme un processus nég-entropique.

« Au commencement Eloïm créa la terre et le ciel » est un énoncé sans antériorité et parfaitement imprévisible. Il ne renvoie à rien qu'à une bipartition arbitraire dans un ensemble infiniment homogène et donc infiniment entropique. Il faut insister sur le caractère énonciatif de cette « création ». Ses phases ultérieures sont introduites par « Eloïm *dit* ». C'est en ce sens que les théologiens ont défini l'acte créateur comme Verbe. En fait il y a production par une volonté de deux « signes » le terrestre et le céleste, au sein de ce qui était perçu comme une absence de signification.

Ces signes se définissent par des caractéristiques différentes et exclusives les unes des autres, qui sont des états de la matière. Cela entraîne une diminution brutale de l'entropie au sens probabiliste de Boltzmann. Le nombre des « complexions » qui peuvent réaliser chacun des états désignés par ces signes, n'est plus infini: il est simplement très grand. On entre dans le domaine de l'évaluable, sillon encore du mesurable. Un pas décisif a été franchi, celui de la création : un ordre a été constitué.

Dès lors, les bipartitions s'enchaînent les unes aux autres: la lumière et l'obscurité, les eaux d'en haut et les eaux d'en bas, etc. A chaque étape se construit progressivement une codification binaire de l'univers par création de *sous-ensembles* dont le nombre croît exponentiellement. On observera que, si le nombre des bipartitions effectuées est de *n*, le nombre des sous-ensembles et donc des signes les désignant est de 2^*n*, ce qui oriente naturellement vers une relation logarithmique. Le nombre des « complexions » qui peuvent réaliser l'état correspondant à chaque sous-ensemble est de moins en moins grand, ce qui implique que cet état est de moins en moins probable. On peut imaginer le cas où une infinité de bipartitions aboutit à une probabilité de <a href="https://www.codecogs.com/eqnedit.php?latex=\frac{1}{\infty&space;}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{1}{\infty&space;}" title="\frac{1}{\infty }" /></a> où l'entropie tend vers zéro et où l'univers est entièrement énoncé. C'est peut-être là ce que Teilhard de Chardin appelle le « point oméga ».

On peut aussi, en interprétant strictement la Bible, considérer que le processus nég-entropique ne dure qu'un temps limité (les 7 jours de la création), pour être immédiatement suivi d'un processus entropique de « retour à la poussière », c'est-à-dire à un état indifférencié. Cela s'accorderait assez bien avec les observations de la physique. Cela s'accor­derait aussi avec les spéculations de la biologie si l'on admet que, dans le cas particulier de la matière vivante, le cycle entier de la période nég-entropique suivie d'une période entropique est réalisé au niveau de chaque espèce (phylogenèse) et au niveau de chaque individu (onto­
génèse).
Mais - et c'est là que la théologie fait des suggestions intéressantes à la théorie de l'information - on peut également dire que l'« accident » humain amorce dans une création vouée à l'entropie un contre-processus nég-entropique fondé sur la pensée et donc sur la capacité d'énonciation productive. En mangeant le fruit de l'arbre de la science, Adam et Eve s'emparent du pouvoir divin du verbe qui leur permet de continuer la création à travers la « dé-création ». Ce pouvoir est celui d'annuler l'entropie par la parole, c'est-à-dire par l'émission de signes.

Il est difficile de dire si les théoriciens de l'information ont été inspirés par la Bible, mais il est de fait que *l'annulation de l'entropie par l'émission de signes* est très exactement l'idée qu'ils ont été amenés à se faire de l'information.

Le bon sens a du mal à voir dans l'information, phénomène ressenti comme positif entre tous, comme un facteur négatif, même si ce facteur affecte un processus lui-même à coloration négative, tel que l'entropie. Il est important, pour bien comprendre l'attitude intellectuelle de la théorie de l'information, de ne pas assimiler l'information à des acqui­sitions comme le savoir ou la connaissance, mais de lui maintenir son double signe négatif.

Cette façon de voir les choses fait en somme de l'information une valeur de signe opposé au travail mécanique. De là dérive la tentation de calquer le schéma de sa production sur le schéma de la production de travail mécanique. On peut imaginer une source « froide » chargée d'entropie qui fait passer du « froid » (c'est-à-dire de l'indétermination) sur une source « chaude » et produit au passage de l'information, le processus étant irréversible. La mesure de l'information potentielle contenue dans la source froide est son imprévisibilité statistique.

En 1924, un ingénieur de l'American Telephone and Telegraph Company, Harry Nyquist, publia un article sur la vitesse de trans­mission des messages télégraphiques (9). Il montrait que si un système télégraphique dispose de *m* « signes » (c'est-à-dire qu'il peut produire *m* modulations du courant électrique), la vitesse de transmission W est liée à *m* par la relation W = K log *m* où K est une constante dépendant du nombre des modulations que le système peut transmettre par seconde.

***
9. « Certain Factors Affecting Telegraph Speed », cité par J.R. PIERCE, *Symbols, Signs and Noise*, New York, Harper, 1961, p. 35.

***
On ne peut qu'être frappé par la ressemblance formelle de cette formule avec celle de Boltzmann. En 1929 le physicien L. Szilard utilisa la théorie naissante de l'information pour lever une ambiguïté de la thermodynamique.

Un pas décisif fut franchi en 1928 par un théoricien de la télécommu­nication, R.Y. L. Hartley, qui, pour la première fois, introduisit une *mesure de la quantité d'information*. Si l'on imagine un système disposant de *s* signes équiprobables, un message composé de *n* de ces signes contient
une quantité d'information H telle que :

H = *n* log *s*

Cette formule a été généralisée ultérieurement sous la forme suivante: si un ensemble M contient *m* signes équiprobables, donc de probabilité *p* = <a href="https://www.codecogs.com/eqnedit.php?latex=\frac{1}{\mathit{m}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{1}{\mathit{m}}" title="\frac{1}{\mathit{m}}" /></a> , l'émission de chaque signe comporte une quantité d'information telle que:

<a href="https://www.codecogs.com/eqnedit.php?latex=\textup{H}&space;=&space;\textup{K&space;log&space;}&space;m&space;=&space;-&space;\textup{&space;K&space;log&space;}&space;\frac{1}{m}=-\textup{&space;K&space;log&space;}p" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\textup{H}&space;=&space;\textup{K&space;log&space;}&space;m&space;=&space;-&space;\textup{&space;K&space;log&space;}&space;\frac{1}{m}=-\textup{&space;K&space;log&space;}p" title="\textup{H} = \textup{K log } m = - \textup{ K log } \frac{1}{m}=-\textup{ K log }p" /></a>

où K est une constante dépendant des unités et de la base de logarithmes choisies. En prenant pour K la valeur de la constante de Boltzmann et en utilisant des logarithmes népériens, on obtient une valeur formulée en *nats (natural units)* qui permet d'établir une relation mathématique entre la mesure de l'entropie thermodynamique et celle de l'information. Les deux formules sont, au signe près, identiques.

Pour que le parallèle fût complet, il restait à mesurer la quantité d'information potentielle d'une source, c'est-à-dire son entropie. C'est ce qu'a fait Shannon. En supposant une source disposant de *n* signes non nécessairement équiprobables, il a montré que l'entropie informa­tionnelle H de cette source est calculable par la formule :

<a href="https://www.codecogs.com/eqnedit.php?latex=\textup{H}&space;=&space;-&space;\sum_{i=1}^{n}&space;p_i&space;\textup{&space;log&space;}&space;p_i" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\textup{H}&space;=&space;-&space;\sum_{i=1}^{n}&space;p_i&space;\textup{&space;log&space;}&space;p_i" title="\textup{H} = - \sum_{i=1}^{n} p_i \textup{ log } p_i" /></a>

C'est-à-dire que l'entropie d'une source est égale à moins la somme des probabilités de chacun des signes dont dispose la source, multipliées chacune par son propre logarithme.

Le caractère binaire, déjà évoqué ci-dessus, de la constitution de beaucoup de systèmes de signes, notamment lorsqu'on utilise le courant électrique (positif/négatif ou circuit ouvert/circuit fermé), conduit ici à utiliser surtout des *logarithmes de base 2* (2 log n = N) et à exprimer le résultat en *bits* ou *binary units* (10). Le *bit* est la quantité d'information contenue par une source disposant de deux signes équiprobables, comme une pièce de monnaie dans le jeu de pile ou face.

***
10. Le terme de bit a été introduit par Shannon. II présente l'inconvénient de désigner à la fois une unité d'information et un symbole numérique (1 et 0) dans la notation binaire. On a proposé pour lui au sens d'unité d'information les noms de shannon ou de logon, mais l'usage semble imposer *bit*. Le *bit* correspond à l'emploi de logarithmes de base 2, le *nat* à celui de logarithmes naturels ou népériens (base *e*) et le *decit* ou *hartley* à celui de logarithmes décimaux.

***

On notera que dans le cas d'une source disposant de *n* signes équi­probables, la formule de Shannon peut être simplifiée:

<a href="https://www.codecogs.com/eqnedit.php?latex=\textup{H}&space;=&space;-&space;\sum_{i=1}^{n}&space;p_i&space;\textup{&space;log&space;}&space;p_i=-n(\frac{1}{n}\textup{&space;log&space;}\frac{1}{n})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\textup{H}&space;=&space;-&space;\sum_{i=1}^{n}&space;p_i&space;\textup{&space;log&space;}&space;p_i=-n(\frac{1}{n}\textup{&space;log&space;}\frac{1}{n})" title="\textup{H} = - \sum_{i=1}^{n} p_i \textup{ log } p_i=-n(\frac{1}{n}\textup{ log }\frac{1}{n})" /></a>

On vérifie dans le cas du jeu de pile ou face que:

<a href="https://www.codecogs.com/eqnedit.php?latex=\textup{H}&space;=&space;-\textup{&space;log&space;}\frac{1}{2}=-(-1)=1&space;bit" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\textup{H}&space;=&space;-\textup{&space;log&space;}\frac{1}{2}=-(-1)=1&space;bit" title="\textup{H} = -\textup{ log }\frac{1}{2}=-(-1)=1 bit" /></a>

Cela signifie que l'entropie de la pièce de monnaie avant d'être lancée est de 1 *bit* et qu'un seul coup de pile ou face suffit à épuiser l'entropie *liée à cette expérience,* puisque, selon la formule de Hartley, il apporte
une quantité d'information de :
<a href="https://www.codecogs.com/eqnedit.php?latex=\textup{H}&space;=&space;n&space;\textup{&space;log&space;}&space;s&space;=&space;1&space;*&space;\textup{log&space;}&space;2&space;=&space;1&space;*&space;1&space;=&space;1&space;bit" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\textup{H}&space;=&space;n&space;\textup{&space;log&space;}&space;s&space;=&space;1&space;*&space;\textup{log&space;}&space;2&space;=&space;1&space;*&space;1&space;=&space;1&space;bit" title="\textup{H} = n \textup{ log } s = 1 * \textup{log } 2 = 1 * 1 = 1 bit" /></a>

Mais si l'on institue une nouvelle expérience, c'est-à-dire si on lance de nouveau la pièce de monnaie, l'entropie de la pièce est de nouveau de 1 *bit*. Le résultat de l'expérience n'affecte pas les probabilités mises en jeu dans l'expérience suivante. Il en serait autrement si le fait d'apparaître dans un coup donné modifiait pour le côté pile ou le côté face sa proba­bilité d'apparition dans le coup suivant. Il faudrait pour cela que la pièce de monnaie fût dotée d'une *mémoire* lui permettant d'enregistrer les résultats des coups joués et de modifier les probabilités d'apparition des deux signes dont elle dispose en fonction de ces résultats, donc de modifier son entropie.

Mais une pièce de monnaie est une source sans mémoire. On retiendra que *la formule de Shannon s'applique exclusivement à des sources sans mémoire.*
