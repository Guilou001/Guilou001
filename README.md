# Guillaume Vaudescal

Économiste financier (M. Sc. économie financière, UQAM, 2024), Montréal. Je reproduis des papiers de finance
empirique sur données libres, je mesure ce qui survit hors échantillon, et je documente aussi ce qui ne
survit pas. Chaque dépôt contient le code, les données téléchargeables par script, les tests, une CI, et un
compte rendu dont chaque chiffre porte son statut (mesuré, rapporté, modélisé) et vient d'un fichier de
résultats du dépôt. Chacun porte aussi ce compte rendu en PDF, dans `rapport/rapport.pdf`, engendré
depuis le même texte pour qu'il ne puisse pas en diverger. Les numéros des dépôts donnent l'ordre de
lecture, des fondations vers le capstone.

*Financial economist (MSc, UQAM 2024), Montréal. I replicate empirical-finance papers on open data, measure
what survives out of sample, and document what does not. Every repository ships code, scripted data
downloads, tests, CI, and a report where each number carries its provenance, in Markdown and as a
typeset PDF generated from that same text. Repository numbers give the
reading order, from foundations to capstone.*

## Par métier

Sept familles se partagent les trente-trois dépôts, une étiquette cliquable par dépôt, celle du poste qu'il vise.

**[Gestion de portefeuille](https://github.com/topics/gestion-de-portefeuille)**

- [01-frontiere-efficiente](https://github.com/Guilou001/01-frontiere-efficiente) : 50 000 portefeuilles tirés au hasard contre la frontière exacte, puis le portefeuille tangent testé hors échantillon contre 1/N.
- [02-erreur-estimation](https://github.com/Guilou001/02-erreur-estimation) : les 312 cellules de DeMiguel, Garlappi et Uppal (2009) reproduites, puis le verdict retesté sur 63 ans.
- [03-gestion-portefeuille](https://github.com/Guilou001/03-gestion-portefeuille) : de l'énoncé de politique de placement au rapport mensuel, chaque brique vérifiée contre son papier fondateur.
- [12-plan-epargne](https://github.com/Guilou001/12-plan-epargne) : REER ou CELI d'abord, et ce que devient la promesse d'un plan quand on simule les rendements au lieu de les supposer constants.
- [13-couverture-de-change](https://github.com/Guilou001/13-couverture-de-change) : couvrir le dollar américain augmente le risque, mesuré sur 249 mois, et le ratio de couverture optimal vaut zéro.
- [14-attribution-performance](https://github.com/Guilou001/14-attribution-performance) : quatre méthodes de chaînage d'attribution réconciliées, et le verdict au comité qui ne dépend pas de la méthode.
- [16-options-couvertes](https://github.com/Guilou001/16-options-couvertes) : le revenu des options d'achat couvertes n'est pas gratuit, il vaut 527 points de base par an de prime de risque.
- [23-fnb-levier-quotidien](https://github.com/Guilou001/23-fnb-levier-quotidien) : l'érosion des FNB à levier n'est pas une loi mais un régime ; sur le Nasdaq elle a rapporté, sur Toronto elle a coûté.

**[Finance quantitative](https://github.com/topics/finance-quantitative)**

- [04-memoire-uqam-2024](https://github.com/Guilou001/04-memoire-uqam-2024) : mon mémoire réexécuté à l'identique, et ses portefeuilles long short une fois le short réellement soustrait.
- [05-memoire-2.0](https://github.com/Guilou001/05-memoire-2.0) : le même mémoire refait sans fuite d'information ; aucun des huit modèles ne bat l'équipondéré.
- [08-facteurs-canada](https://github.com/Guilou001/08-facteurs-canada) : les primes canadiennes n'ont pas fondu après publication, le momentum tenant 15,7 % par an.
- [15-valorisation-options](https://github.com/Guilou001/15-valorisation-options) : construire un pricer d'options, puis prouver qu'il est juste, vingt prix sur vingt du tableau de Longstaff-Schwartz.
- [21-vwap-intrajournalier](https://github.com/Guilou001/21-vwap-intrajournalier) : la stratégie qui transforme 25 000 dollars en 2 millions en perd si l'on paie un demi-cent d'écart à chacun de ses seize passages quotidiens.
- [22-derniere-demi-heure](https://github.com/Guilou001/22-derniere-demi-heure) : le momentum intrajournalier publié en 2018 a changé de signe, et c'est l'écart d'ouverture qui le portait, pas la première demi-heure de bourse.
- [24-vwap-iex-vs-consolide](https://github.com/Guilou001/24-vwap-iex-vs-consolide) : le flux de données gratuit est presque toujours là et ne voit presque rien ; il fait tenir des positions opposées une minute sur vingt-neuf.
- [uqam-transformer-actions](https://github.com/Guilou001/uqam-transformer-actions) : un Transformer à douze têtes qui ne prédit qu'une ligne plate sur les rendements quotidiens.

**[Économie](https://github.com/topics/economie)**

- [07-nowcast-pib-canada](https://github.com/Guilou001/07-nowcast-pib-canada) : avec l'information réellement disponible, le pont du PIB mensuel réduit l'erreur de 57 % contre l'autorégression au troisième mois.
- [11-courbe-des-taux](https://github.com/Guilou001/11-courbe-des-taux) : la marche aléatoire bat Diebold-Li dans 26 cases sur 27, et la pente ne prédit plus les récessions hors échantillon.
- [18-inflation-fondamentale](https://github.com/Guilou001/18-inflation-fondamentale) : l'IPC-tronq garde son premier rang à travers le choc de 2021-2023, l'IPC-comm finit dernier.
- [uqam-cycle-economique-canada](https://github.com/Guilou001/uqam-cycle-economique-canada) : les faits stylisés du cycle canadien refaits cinq ans plus tard, et la grande modération qui ne tient plus jusqu'en 2026.
- [uqam-apprentissage-sept-bases](https://github.com/Guilou001/uqam-apprentissage-sept-bases) : neuf algorithmes comparés sur sept bases de données ; aucun ne gagne partout, et cinq se partagent les premières places.
- [uqam-prevision-facteurs](https://github.com/Guilou001/uqam-prevision-facteurs) : six modèles prévoient le chômage américain sur douze horizons ; le VAR gagne, et le pari laissé ouvert en 2021 sur la Covid est tranché par le réalisé.
- [uqam-svar-monetaire-budgetaire](https://github.com/Guilou001/uqam-svar-monetaire-budgetaire) : un choc de taux creusait la production de 0,85 % avant 1983 ; de 1983 à 2007 il ne la fait plus passer sous son niveau de départ.
- [uqam-croissance-capital-humain](https://github.com/Guilou001/uqam-croissance-capital-humain) : un travail théorique sans code doté du sien ; la calibration se retrouve à la précision machine et l'état stationnaire annule les cinq conditions d'équilibre.

**[Gestion des risques](https://github.com/topics/gestion-des-risques)**

- [06-risque-marche](https://github.com/Guilou001/06-risque-marche) : sur six modèles de valeur à risque, seule la simulation historique filtrée passe Kupiec et n'a aucune année rouge de Bâle.
- [25-scenario-climatique-bsif](https://github.com/Guilou001/25-scenario-climatique-bsif) : l'exercice climatique que le BSIF impose aux banques, recalculé à un milliardième de dollar près, et une majoration qui frappe les bons emprunteurs 5,9 fois plus que les mauvais.
- [30-risque-operationnel](https://github.com/Guilou001/30-risque-operationnel) : le capital contre les ratés d'une banque, refait depuis ses relevés publics ; quatre des six grandes en portent moins que le barème n'exige, et la Toronto-Dominion seule davantage.
- [32-xva-swaps](https://github.com/Guilou001/32-xva-swaps) : trois portefeuilles de swaps de même nominal, dont le coût de contrepartie va de moins 400 à plus 280 points de base ; les 42 cellules de l'article de référence reproduites dans trois erreurs types.

**[Crédit](https://github.com/topics/credit)**

- [10-credit-bancaire](https://github.com/Guilou001/10-credit-bancaire) : un moteur de probabilité de défaut prouvé sur un portefeuille à vérité connue, et le dossier de crédit d'Enbridge étalé en Excel.
- [27-portefeuille-de-credit](https://github.com/Guilou001/27-portefeuille-de-credit) : la règle de capital du BSIF suppose une infinité de prêts, et manque 36 % du capital sur un livre où dix clients font la moitié du montant.

**[Analyse financière](https://github.com/topics/analyse-financiere)**

- [09-valorisation-entreprise](https://github.com/Guilou001/09-valorisation-entreprise) : le cours du Canadien National suppose 11,9 % de croissance annuelle des flux, contre 7,8 % livrés depuis 2011.
- [28-etats-financiers-reformules](https://github.com/Guilou001/28-etats-financiers-reformules) : sur 39 industries canadiennes, aucune ne tire de l'emprunt plus que de son affaire ; l'exploitation rapporte 11,5 % par an, l'emprunt moins d'un point.
- [29-rentabilite-des-banques](https://github.com/Guilou001/29-rentabilite-des-banques) : les six grandes banques gardent trente cents de chaque dollar encaissé contre dix-neuf en 1997, et rapportent trois points de moins à leurs actionnaires.

**[Assurance](https://github.com/topics/assurance)**

- [17-alm-assurance-vie](https://github.com/Guilou001/17-alm-assurance-vie) : l'appariement par taux clés survit à la torsion de courbe de 2022, la duration seule non.
- [26-provisionnement-iard](https://github.com/Guilou001/26-provisionnement-iard) : la fourchette de provisionnement qui promet 95 % n'en tient que 59 à 74, sur 207 assureurs et deux millésimes de triangles.
- [31-fonds-distincts](https://github.com/Guilou001/31-fonds-distincts) : dans le nouveau régime de capital des garanties de fonds distincts, le choc de volatilité pèse plus lourd que le choc d'actions, et la grille du régulateur épingle en fait la volatilité à 41 % au court terme et 25 % au long.

## Les dépôts, dans l'ordre de lecture

| Dépôt | La question posée | Ce qui est mesuré |
|---|---|---|
| [01-frontiere-efficiente](https://github.com/Guilou001/01-frontiere-efficiente) | À quelle distance 50 000 portefeuilles aléatoires restent-ils de la frontière de Markowitz exacte, et le portefeuille tangent tient-il hors échantillon contre 1/N ? | Meilleur Sharpe simulé 0,73 contre 0,80 pour la tangence exacte ; hors échantillon net de coûts, le tangent bat 1/N aux États-Unis (0,77 contre 0,51) et perd au Canada (0,62 contre 0,73) |
| [02-erreur-estimation](https://github.com/Guilou001/02-erreur-estimation) | La réplication exacte de DeMiguel, Garlappi et Uppal (2009) tient-elle, et le verdict « rien ne bat 1/N » survit-il à vingt ans de données de plus ? | 312/312 cellules des tables 3 et 4 reproduites à la précision imprimée ; une cellule dégénérée du papier découverte ; sur 1963-2026, aucune règle ne bat 1/N sur les quatre univers à la fois |
| [03-gestion-portefeuille](https://github.com/Guilou001/03-gestion-portefeuille) | Les briques d'un gestionnaire institutionnel (Black-Litterman, HRP, attribution de Brinson, bandes de politique), vérifiées contre leurs papiers, rapportent-elles quelque chose une fois branchées sur six FNB canadiens ? | Chaîne Idzorek (2005) exacte aux 2 décimales imprimées ; moteur 2007-2026 sur FNB de Toronto : la politique à bandes sans vue fait 6,63 % par an net, les vues systématiques 6,25 % ; rapport mensuel régénérable |
| [04-memoire-uqam-2024](https://github.com/Guilou001/04-memoire-uqam-2024) | Mon mémoire (8 modèles d'apprentissage machine, macro LCDMA et FRED-MD, 50 titres TSX et 50 titres S&P 500, 2008-2024) se réexécute-t-il, et que valent ses portefeuilles long short une fois le short réellement soustrait ? | Réexécution exacte (écart 2,8 × 10⁻⁷) ; long short réel : au mieux 7,4 % par an aux États-Unis, 5,6 % au Canada, sous l'équipondéré ; v1.1 avec PDF des résultats refaits |
| [05-memoire-2.0](https://github.com/Guilou001/05-memoire-2.0) | La même question, refaite avec les méthodes de 2026 : information réellement disponible, réglages gelés hors test, validation croisée purgée, coûts, Sharpe déflaté | Aucun des huit modèles ne bat l'équipondéré ; la rotation de 2 à 3 par mois coûte plus que le signal extrait ; Sharpe déflaté maximal 0,01 une fois les 33 essais comptés, loin du seuil de 0,95 |
| [06-risque-marche](https://github.com/Guilou001/06-risque-marche) | Parmi six modèles de VaR à un jour (historique, gaussien, Student, EWMA, simulation historique filtrée, GARCH maison), lesquels survivent aux backtests réglementaires sur 22 ans de données canadiennes ? | Seule la simulation historique filtrée passe Kupiec (69 dépassements pour 54,8 attendus, p = 0,063) et n'a aucune année rouge de Bâle ; l'historique dépasse 22 fois dans la seule année 2008 |
| [07-nowcast-pib-canada](https://github.com/Guilou001/07-nowcast-pib-canada) | Pour prévoir le trimestre en cours du PIB canadien avec l'information réellement disponible, qui gagne : l'autorégression, le PIB mensuel, les 400 séries de la LCDMA ou l'apprentissage machine ? | Le bridge du PIB mensuel réduit l'erreur de 57 % contre l'AR au mois 3 (p = 0,027, hors COVID) ; le grand panel fait pire que l'AR au même mois, le bloc américain de FRED-MD dégrade le mois 1 |
| [08-facteurs-canada](https://github.com/Guilou001/08-facteurs-canada) | Les primes de facteurs canadiennes (valeur, momentum, bêta faible, qualité) ont-elles fondu après leur publication, comme aux États-Unis, et le Canada se distingue-t-il ? | Pas de décote après 2001 : momentum stable à 15,7 %/an (t = 3,3), valeur qui monte, et le Canada bat les États-Unis sur les quatre primes vivantes à période commune (corrélations bilatérales 0,37 à 0,82) |
| [09-valorisation-entreprise](https://github.com/Guilou001/09-valorisation-entreprise) | Que vaut le Canadien National, et surtout : quelle croissance le cours de 175 $ suppose-t-il, est-elle plausible au vu de quinze ans d'états financiers ? | DCF prudent 93 $, comparables 200-225 $ (le CN le moins cher de sa cohorte), et DCF inversé : le cours suppose 11,9 %/an de FCFF pendant 5 ans contre 7,8 % livré sur 2011-2025 et 4,0 % sur la dernière décennie ; classeur Excel à formules vivantes et mémo bilingue |
| [10-credit-bancaire](https://github.com/Guilou001/10-credit-bancaire) | Comment prouver qu'un moteur de probabilité de défaut mesure ce qu'il prétend, et que vaut le dossier de crédit d'Enbridge une fois les ratios étalés ? | Le hasard de Shumway retrouve les paramètres d'un portefeuille synthétique à vérité connue (−6,13 contre −6,20 vrai) ; l'ECL pondérée par scénarios dépasse la centrale de 0,6 % (convexité mesurée) ; capital IRB OSFI testé à la main ; dossier Excel Enbridge : la grille de ratios donne B, les agences BBB, et l'écart est l'enseignement |
| [11-courbe-des-taux](https://github.com/Guilou001/11-courbe-des-taux) | Diebold-Li bat-il encore la marche aléatoire, et la pente de la courbe prédit-elle encore les récessions canadiennes après l'inversion de 2022-23 sans récession ? | Non et non : la marche aléatoire gagne 26 cases sur 27 (1996-2026) ; hors échantillon l'AUROC de la pente tombe à 0,50 (0,27 hors COVID), fausse alarme de 2022-24 comprise ; en ALM, le choc réalisé de 2022 (+412 pb à 3 mois) coûte moitié moins que la pentification réglementaire : la forme du choc compte autant que l'ampleur |
| [12-plan-epargne](https://github.com/Guilou001/12-plan-epargne) | REER ou CELI d'abord, et que devient la promesse d'un plan de retraite quand on simule les rendements au lieu de les supposer constants ? | L'équivalence REER = CELI à taux égaux est prouvée par test analytique (1e-12) ; au cas type 35/25, REER d'abord gagne 8,0 % de richesse nette, mais le remboursement dépensé inverse le classement (-18,9 %) ; la promesse déterministe (95 862 $) cache un cinquième percentile à 45 855 $ ; au scénario prudent, un avenir sur dix ne finance pas la cible |
| [13-couverture-de-change](https://github.com/Guilou001/13-couverture-de-change) | Couvrir le dollar US est vendu comme de la prudence pure : est-ce vrai pour un investisseur canadien en actions américaines ? | Non, mesuré : la parité couverte des taux reconstruit XSP à 93 pb/an près (corr 0,995), et la couverture AUGMENTE le risque (vol 15,2 % contre 12,2 %, pire baisse -52 % contre -42 %), car le USD monte quand les actions tombent (corr -0,59) ; le ratio optimal vaut zéro |
| [14-attribution-performance](https://github.com/Guilou001/14-attribution-performance) | Quatre méthodes de chaînage d'attribution concurrentes : le verdict au comité dépend-il de la méthode choisie ? | Non : Cariño, Menchero, GRAP et Frongello réconcilient chacun exactement (résidu 5e-15, testé) et s'accordent à 0,83 point près sur 58,7 ; les totaux GRAP et Frongello sont identiques (identité redémontrée et testée) ; TWR, Dietz et MWR retombent au centième sur l'exemple officiel du GIPS Handbook 2020 |
| [15-valorisation-options](https://github.com/Guilou001/15-valorisation-options) | Construire un pricer d'options, puis PROUVER qu'il est juste : que valent les vingt prix du tableau 1 de Longstaff-Schwartz face à un arbre poussé à convergence ? | Réplication 20/20 dans les deux erreurs types (puts bermudéens, transcription verrouillée par tests), convergence CRR mesurée à la pente -0,98, couverture des IC vérifiée (94-96 %), et le surapprentissage du LSM chiffré en multi-graines : +0,2 à +0,5 cent, invisible à graine unique |
| [16-options-couvertes](https://github.com/Guilou001/16-options-couvertes) | Le « revenu » des FNB d'options d'achat couvertes est-il gratuit, et la donnée libre suffit-elle à répliquer le BXM ? | Non et non, mesuré : le BXM reconstruit au VIX (corr 0,981) ressort trop riche de +527 pb/an, la mesure du skew que le VIX ne voit pas ; la prime de variance est positive 84 % des mois depuis 1990 (t 3,3) ; et ZEB bat ZWB de 2,75 pt/an sur les mêmes banques pour un pire creux identique |
| [17-alm-assurance-vie](https://github.com/Guilou001/17-alm-assurance-vie) | L'immunisation par la durée a-t-elle survécu à la torsion de courbe de 2022, et le capital TSAV prescrit couvrait-il la perte ? | L'appariement par taux clés ramène le surplus à son point de départ à travers 400 pb de torsion ; la duration seule erre ; sans couverture, insolvabilité transitoire ; et l'exigence du chapitre 5 (chocs en racine carrée des taux plancher de 2021 : +147 pb prescrits, 400 livrés) n'a couvert que 67 % de la perte réalisée |
| [18-inflation-fondamentale](https://github.com/Guilou001/18-inflation-fondamentale) | Les mesures d'inflation fondamentale choisies en 2016 gagnent-elles encore leur concours à travers le choc de 2021-23 ? | Oui pour l'IPC-tronq (premier au critère prédictif dans les deux fenêtres) ; l'IPC-comm, déclassé par la Banque en 2022, finit dernier : c'était dans les données ; et IPC-tronq/IPC-méd sont reconstruits depuis les 55 composantes officielles à 0,22-0,24 pt près, l'écart maximal tombant sur la TPS de 1991, la signature de l'approximation déclarée |
| [21-vwap-intrajournalier](https://github.com/Guilou001/21-vwap-intrajournalier) | Une stratégie qui rapporte 671 % en six ans en suppose zéro coût d'exécution alors qu'elle change de position seize fois par jour : que reste-t-il quand on la facture ? | Le repère passif de l'article se reproduit à 0,03 point près, ce qui atteste les données ; sa stratégie atteint 587 % pour un Sharpe de 2,01, mais 1,05 cent de glissement par passage l'annule et 0,42 cent suffit après sa publication, où le rendement annuel sans frais tombe de 40,5 % à 7,0 % ; sur le fonds à levier, un demi-cent transforme les 2 085 417 dollars annoncés en une perte |
| [22-derniere-demi-heure](https://github.com/Guilou001/22-derniere-demi-heure) | Le momentum intrajournalier de Gao, Han, Li et Zhou tient-il hors de son échantillon de 1993-2013 ? | Non : la pente est négative pour six des huit fonds testés sur 2016-2026, aucun fonds d'actions n'en montre une positive, et le renversement est le plus fort là où l'article disait l'effet le plus fort ; la décomposition montre que l'écart d'ouverture portait tout le signal, et la seule relation qui survit s'annule à 0,23-0,51 point de base par passage |
| [23-fnb-levier-quotidien](https://github.com/Guilou001/23-fnb-levier-quotidien) | Un fonds qui rend trois fois le rendement quotidien de son indice rend-il, au bout de quinze ans, trois fois le rendement de l'indice ? | Non, et l'écart change de signe avec la tendance : sur le Nasdaq 100 depuis 2010, composer trois fois chaque jour donne +51 108 % contre +4 673 % au multiple naïf, quand la même mécanique coûte 42 points sur Toronto ; la formule fermée rejoint vingt mille tirages à 0,16 point, les quatre fonds inverses finissent à −100 %, et onze séances de 2008 suffisaient à faire tomber la corrélation des fonds canadiens de 0,99 à 0,24 |
| [24-vwap-iex-vs-consolide](https://github.com/Guilou001/24-vwap-iex-vs-consolide) | Le flux de données gratuit, qui ne voit qu'une petite bourse, suffit-il à rejouer une stratégie qui compare le prix à sa moyenne pondérée par les volumes ? | Non, et pas pour la raison attendue : IEX publie une barre dans 91,9 % des minutes de séance, donc il ne se tait presque jamais, mais avec 1,4 % du volume sa moyenne pondérée s'écarte de 9,6 cents en médiane et fait tenir aux deux flux des positions opposées une minute sur vingt-neuf ; le signal passe de 339 % à 189 % sur QQQ et de 75 % à 105 % sur SPY, donc l'erreur n'a pas de signe et ne se corrige pas |
| [25-scenario-climatique-bsif](https://github.com/Guilou001/25-scenario-climatique-bsif) | Le module de crédit de l'exercice normalisé de scénarios climatiques du BSIF se code-t-il depuis ses seules formules publiées, et qui la majoration prescrite frappe-t-elle ? | Les huit nombres de l'exemple officiel retrouvés à 1,2 × 10⁻¹⁰ dollar près ; la majoration s'ajoutant au logit multiplie la COTE de défaut, si bien qu'à vingt ans elle coûte 9,31 % de perte attendue au meilleur seau de qualité contre 1,58 % au pire, soit 5,9 fois moins |
| [26-provisionnement-iard](https://github.com/Guilou001/26-provisionnement-iard) | La fourchette de provisionnement de Mack, qui promet de contenir la vraie facture 95 fois sur 100, la contient-elle vraiment ? | Les 38 chiffres de l'article de 1993 retrouvés, puis une couverture de 58,9 % sur les accidents de 1988-1997 et de 74,1 % sur ceux de 1998-2007, sur 207 assureurs ; le montant prévu est bon, l'incertitude annoncée ne l'est pas |
| [27-portefeuille-de-credit](https://github.com/Guilou001/27-portefeuille-de-credit) | De combien la règle de capital du BSIF, qui suppose un portefeuille infiniment granulaire, se trompe-t-elle sur un vrai livre de banque commerciale ? | 143 des 144 poids publiés retrouvés, la 144e étant une coquille du BSIF contre la table de Bâle ; sur 500 prêts dont dix font la moitié, la règle manque 36 % du capital, et l'ajustement de granularité en rattrape 88 % |
| [28-etats-financiers-reformules](https://github.com/Guilou001/28-etats-financiers-reformules) | La rentabilité des entreprises canadiennes vient-elle de leur affaire ou de leur endettement ? | L'affaire rapporte 11,5 % par an en médiane, l'emprunt entre +0,18 et -0,98 point selon le traitement des soldes intragroupe ; sur 39 industries, aucune ne tire de l'emprunt plus que de son affaire |
| [29-rentabilite-des-banques](https://github.com/Guilou001/29-rentabilite-des-banques) | D'où vient le rendement des six grandes banques canadiennes, et qu'est-ce qui a changé depuis 1997 ? | Sur 174 exercices, la marge ajoute +5,7 points de rendement et la productivité de l'actif en retire 4,5, le levier 4,1 ; le rendement passe de 15,95 % à 12,98 %, et l'identité se referme à 5,6e-17 |
| [30-risque-operationnel](https://github.com/Guilou001/30-risque-operationnel) | Que suppose le capital de risque opérationnel d'une banque sur ses propres pertes, alors que ces pertes ne sont pas publiées ? | Le capital se refait depuis les relevés publics, seize banques sur trente-neuf à mieux qu'un millième et la meilleure au dollar près ; quatre des six grandes portent moins que le barème, et l'exemple travaillé du BSIF se révèle faux sur sa dernière ligne |
| [31-fonds-distincts](https://github.com/Guilou001/31-fonds-distincts) | Dans le nouveau régime de capital des garanties de fonds distincts, lequel des deux chocs simultanés fait le capital ? | Le choc de volatilité exige plus que le choc d'actions à dix ans, 57,6 % de l'exigence conjointe et jusqu'à 64,4 % à douze ans ; les neuf exemples travaillés du BSIF se reproduisent, sauf une addition qui imprime 51,4 là où 54,0 moins 3,6 fait 50,4 |
| [32-xva-swaps](https://github.com/Guilou001/32-xva-swaps) | Trois portefeuilles de swaps de même nominal total coûtent-ils le même risque de contrepartie ? | Non : de -138,6 à +35,8 points de base à corrélation nulle, le seul calendrier de l'exposition les séparant de 174 points ; les 42 cellules de l'article de référence tiennent dans trois erreurs types, et l'écart résiduel est chiffré convention par convention |
| [uqam-transformer-actions](https://github.com/Guilou001/uqam-transformer-actions) | Un Transformer à douze têtes, nourri de vingt-six ans de prix quotidiens de la Banque Royale, apprend-il à prédire le rendement de demain ? | Non : l'écart type de la prédiction vaut 0,0015 % de celui du rendement réalisé et la corrélation −0,04 ; après lissage sur dix jours, 59,5 % et 0,79. Le portage sur Keras 3 a révélé un modèle à 8 833 paramètres au lieu de 306 175, défaut invisible en 2022 |
| [uqam-cycle-economique-canada](https://github.com/Guilou001/uqam-cycle-economique-canada) | Les faits stylisés du cycle canadien, mesurés en 2021 sur un fichier de cours, tiennent-ils une fois reconstruits sur les tables ouvertes de Statistique Canada et prolongés à 2026 ? | La validation croisée du portage passe (inflation 1973-1982 à 9,62 contre 9,63) ; la grande modération tient sur 1984-2017 et NE TIENT PLUS jusqu'en 2026, quatre trimestres de 2020 la renversant |
| [uqam-apprentissage-sept-bases](https://github.com/Guilou001/uqam-apprentissage-sept-bases) | Neuf algorithmes d'apprentissage automatique, du lasso au réseau de neurones, sont comparés sur sept bases de données sans rapport les unes avec les autres : lequel gagne, et le classement dépend-il de la base ? | Aucun ne gagne partout, cinq estimateurs se partageant les sept premières places et un modèle non paramétrique l'emportant sur six bases ; la réplication retrouve les nombres de 2022 sur les cinq bases publiques (lasso et ridge à 0,24 sur Boston Housing, cinq des sept pénalités identiques), tandis que les deux bases macroéconomiques, reconstruites depuis FRED-MD faute des fichiers du cours, donnent un chômage que rien ne prédit mieux que sa moyenne |
| [uqam-prevision-facteurs](https://github.com/Guilou001/uqam-prevision-facteurs) | Six modèles prévoient la variation mensuelle du chômage américain sur douze horizons, chacun réestimé 732 fois hors échantillon : lequel gagne, et faut-il retirer la Covid des données pour prévoir la suite ? | La réplication retrouve le travail de 2021 : l'autorégressif direct d'ordre 4 donne 0,841 contre 0,840, et le VAR reste le meilleur des six, 0,798 contre 0,822 du repère ; la question laissée ouverte en 2021 est tranchée par le chômage réalisé, retirer la Covid était le bon choix pour les trois modèles rejoués, et l'ARMA divise son erreur par deux |
| [uqam-svar-monetaire-budgetaire](https://github.com/Guilou001/uqam-svar-monetaire-budgetaire) | Que fait un choc de taux à l'économie américaine, la réponse est-elle la même qu'avant 1983, et l'effet d'un choc de dépense publique tient-il à autre chose qu'à l'ordre choisi pour l'identifier ? | Le schéma de Christiano, Eichenbaum et Evans se retrouve sur 1965-2020, énigme des prix comprise ; avant 1983 le choc creuse la production de 0,85 % en onze mois, de 1983 à 2007 elle ne passe jamais sous son niveau de départ ; côté budgétaire l'ordre de récursivité décide du signe à l'impact, de +0,11 % à zéro par construction |
| [uqam-croissance-capital-humain](https://github.com/Guilou001/uqam-croissance-capital-humain) | Un travail de macroéconomie entièrement théorique, sans une ligne de code : sa calibration tient-elle quand on la refait par le calcul, et son état stationnaire existe-t-il vraiment ? | Les quatre paramètres déduits à la main se retrouvent, deux à la précision machine et deux à l'arrondi imprimé ; l'état stationnaire, que le travail ne calculait pas, annule les cinq conditions d'équilibre à 2 × 10⁻¹⁶ près, et le schéma d'identification proposé en conclusion retrouve des chocs connus à 0,999 |
| [gv-fintools](https://github.com/Guilou001/gv-fintools) | Comment donner des figures, des données et un rapport PDF à trente dépôts sans écrire trente fois le même code ? | Une feuille de style qui écrit les axes en français, sept fabriques de figures qui rendent les nombres qu'elles dessinent, un chargeur des relevés du BSIF qui pose un entrepôt DuckDB, et un traducteur de README en Typst ; 38 tests fermés, dont un qui compile un document complet et relit le PDF produit |
| [skill-redaction-pedagogique](https://github.com/Guilou001/skill-redaction-pedagogique) | Un skill Claude Code : écrire des documents techniques en français clair sans perdre la rigueur | Utilisé pour les README de tous les dépôts ci-dessus |

## Par où commencer, en trois arrêts

1. **La réplication la plus dure** : [02-erreur-estimation](https://github.com/Guilou001/02-erreur-estimation),
   312 cellules sur 312 de DeMiguel, Garlappi et Uppal (2009) reproduites à la précision imprimée, puis le
   verdict retesté sur 63 ans.
2. **Le métier de gestionnaire** : [03-gestion-portefeuille](https://github.com/Guilou001/03-gestion-portefeuille),
   de la politique de placement au rapport mensuel, chaque brique vérifiée contre son papier fondateur.
3. **La méthode de 2026** : [05-memoire-2.0](https://github.com/Guilou001/05-memoire-2.0), le même mémoire refait
   sans fuite d'information, avec validation purgée, coûts et Sharpe déflaté, et un verdict négatif assumé.

## Ce que chaque dépôt démontre

| Compétence | Dépôts |
|---|---|
| Réplication quantitative et rigueur hors échantillon | 02-erreur-estimation, 05-memoire-2.0, 01-frontiere-efficiente |
| Gestion de portefeuille institutionnelle (allocation, attribution, politique) | 03-gestion-portefeuille, 01-frontiere-efficiente |
| Apprentissage machine appliqué aux rendements | 04-memoire-uqam-2024, 05-memoire-2.0 |
| Backtests propres (walk-forward, coûts, validation purgée) | 05-memoire-2.0, 03-gestion-portefeuille, 02-erreur-estimation, 01-frontiere-efficiente |
| Gestion des risques (VaR, ES, backtests réglementaires) | 06-risque-marche |
| Actuariat de dommages (triangles, provisionnement, Mack) | 26-provisionnement-iard |
| Capital réglementaire de crédit et risque de concentration | 27-portefeuille-de-credit, 10-credit-bancaire |
| Capital réglementaire de risque opérationnel et relevés du BSIF | 30-risque-operationnel |
| Capital d'assurance vie et garanties de fonds distincts | 31-fonds-distincts, 17-alm-assurance-vie |
| Risque de contrepartie, XVA et modèles de taux à deux facteurs | 32-xva-swaps |
| Microstructure de marché et qualité des données (flux consolidé, IEX, agrégateurs) | 24-vwap-iex-vs-consolide |
| Stratégies intrajournalières et coûts d'exécution (barres d'une minute, glissement) | 21-vwap-intrajournalier, 22-derniere-demi-heure, 24-vwap-iex-vs-consolide |
| Analyse d'états financiers et décomposition de la rentabilité | 28-etats-financiers-reformules, 29-rentabilite-des-banques, 09-valorisation-entreprise |
| Tension réglementaire et risque climatique (exercice normalisé du BSIF, IFRS 9, Frye-Jacobs) | 25-scenario-climatique-bsif |
| Macroéconomie appliquée (nowcasting, temps réel) | 07-nowcast-pib-canada |
| Recherche facteurs et valorisation d'actifs | 08-facteurs-canada, 02-erreur-estimation |
| Analyse fondamentale et valorisation d'entreprise (DCF, comparables, Excel) | 09-valorisation-entreprise |
| Risque de crédit et banque commerciale (PD, IFRS 9, IRB, dossier de crédit) | 10-credit-bancaire |
| Courbe des taux et ALM bancaire (Nelson-Siegel, probit, IRRBB, durations clés) | 11-courbe-des-taux |
| Planification d'épargne et Monte Carlo client (REER/CELI, risque de séquence) | 12-plan-epargne |
| Couverture de change et overlay (parité couverte, ratio à variance minimale) | 13-couverture-de-change |
| Mesure et attribution de performance (Brinson, chaînages, TWR/MWR, GIPS) | 14-attribution-performance |
| ALM d'assurance vie et capital réglementaire (TSAV, Redington, taux clés) | 17-alm-assurance-vie |
| Valorisation de dérivés et validation de modèles (CRR, LSM, Heston) | 15-valorisation-options |
| Produits d'options et prime de variance (BXM, VIX, options couvertes) | 16-options-couvertes |
| Inflation et mesures fondamentales (IPC-tronq, concours de mesures) | 18-inflation-fondamentale |
| Rédaction technique bilingue, chiffres sourcés | tous, plus skill-redaction-pedagogique |

Trente-trois dépôts publiés : 01 à 18, 23, et 25 à 32, plus les six travaux de maîtrise `uqam-`. En
réserve, vérifiés source par source : le programme intrajournalier issu de la revue VWAP (21, 22 et
24 : réplication Zarattini-Aziz, dernière demi-heure, VWAP IEX contre consolidé), et six candidats de
second tour du côté réglementaire.

Outils : Python 3.12 (uv, pandas, scikit-learn, cvxpy, matplotlib), SQL sur DuckDB (les relevés du
BSIF, 2,2 millions de lignes dans 29 et 30), Excel, LaTeX et Typst.
Données libres seulement : Yahoo Finance (usage personnel), FRED, Banque du Canada (Valet), Ken French,
LCDMA. Français d'abord, résumé anglais dans chaque dépôt.
