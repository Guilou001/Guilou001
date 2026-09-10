# Guillaume Vaudescal

Économiste financier à Montréal, titulaire d’une maîtrise en économie financière de l’UQAM obtenue en 2024.

Je construis des projets pour répondre à des questions concrètes en finance. Comment répartir son épargne, prévoir une perte ou comprendre les comptes d’une banque ? Je pars des données et des travaux de recherche, je refais les calculs, puis je vérifie ce que les résultats permettent de conclure.

Un fil relie mes projets de placement. Une méthode qui fonctionne sur le passé reste-t-elle utile sur les périodes suivantes, une fois les frais payés ? Les projets de crédit, d’assurance et d’économie posent une question voisine. Les calculs décrivent-ils correctement le risque et l’incertitude ?

## Quelques points de départ

- [Comprendre comment répartir un placement](https://github.com/Guilou001/01-frontiere-efficiente). Le projet 01 compare une répartition calculée à une règle qui met la même somme dans chaque fonds.
- [Voir le travail d’un gestionnaire de portefeuille](https://github.com/Guilou001/03-gestion-portefeuille). Le projet 03 suit un plan de placement, décide quand ajuster les positions et produit un rapport mensuel.
- [Explorer le laboratoire de recherche](https://github.com/Guilou001/quant-research-platform). Les stratégies passent par des contrôles sur les données, les périodes de test, les coûts et le nombre d’essais effectués.
- [Lire mon mémoire et son audit](https://github.com/Guilou001/04-memoire-uqam-2024). Le projet 04 conserve le travail de 2024 et explique les défauts de méthode trouvés lors de sa réexécution.

## Les projets par sujet

Chaque lien mène au code et à une présentation du projet. Les descriptions ci-dessous donnent la question étudiée et l’enseignement principal, ou le calcul que l’on peut reproduire. Les résultats restent liés aux périodes, aux données et aux hypothèses précisées dans chaque dépôt.

[Placement et épargne](#placement-et-épargne) · [Entreprises et crédit](#entreprises-et-crédit) · [Risques et assurance](#risques-et-assurance) · [Économie canadienne](#économie-canadienne) · [Transactions en cours de journée](#transactions-en-cours-de-journée) · [Recherche et apprentissage automatique](#recherche-et-apprentissage-automatique) · [Travaux universitaires](#travaux-universitaires) · [Outils communs](#outils-communs)

### Placement et épargne

| Projet | Ce qu’on y étudie |
|---|---|
| [01 · Choisir une répartition](https://github.com/Guilou001/01-frontiere-efficiente) | Comparer une répartition calculée à une somme égale dans chaque fonds. Sur les périodes suivantes, les écarts de performance restent trop incertains pour conclure que le calcul améliore le placement. |
| [02 · Comprendre l’erreur d’estimation](https://github.com/Guilou001/02-erreur-estimation) | Vérifier si des calculs de placement battent une répartition égale. L’étude de 2009 est reproduite et prolongée jusqu’en 2026. Le classement change selon les actifs étudiés. |
| [03 · Gérer un portefeuille](https://github.com/Guilou001/03-gestion-portefeuille) | Suivre un plan de placement sur des fonds canadiens et expliquer ses résultats. Dans le test, suivre ce plan rapporte davantage que les ajustements fondés sur les prévisions testées, après les frais. |
| [08 · Choisir des actions au Canada](https://github.com/Guilou001/08-facteurs-canada) | Tester des règles comme acheter les actions qui ont récemment monté ou celles jugées peu chères par rapport aux comptes de l’entreprise. Comparer leurs résultats avant et après 2001, avant les frais. |
| [12 · Préparer son épargne](https://github.com/Guilou001/12-plan-epargne) | Comparer deux comptes d’épargne canadiens, le REER et le CELI, selon leurs impôts et les rendements possibles. Dépenser le remboursement d’impôt peut inverser le classement des deux stratégies. |
| [13 · Mesurer l’effet du dollar américain](https://github.com/Guilou001/13-couverture-de-change) | Acheter des actions américaines depuis le Canada expose aussi aux variations du dollar américain. Sur la période étudiée, retirer cet effet augmente les fluctuations et la pire perte du placement. |
| [14 · Expliquer la performance](https://github.com/Guilou001/14-attribution-performance) | Comprendre pourquoi un portefeuille fait mieux ou moins bien que son plan. Séparer le choix des marchés du choix des fonds, puis vérifier que les contributions retrouvent l’écart total au plan. |
| [16 · Échanger des hausses futures contre un revenu](https://github.com/Guilou001/16-options-couvertes) | Un fonds peut recevoir un revenu en cédant une partie des hausses futures de ses actions. La comparaison de fonds bancaires canadiens montre que ce revenu n’évite pas les fortes pertes. |
| [23 · Comprendre les fonds à levier quotidien](https://github.com/Guilou001/23-fnb-levier-quotidien) | Un fonds qui multiplie chaque mouvement quotidien ne multiplie pas de la même façon le gain de plusieurs années. Les calculs montrent que l’écart peut aider ou pénaliser le placement. |
| [36 · Apprendre à répartir un portefeuille](https://github.com/Guilou001/36-apprendre-portefeuille) | Comparer des modèles qui choisissent directement les placements à ceux qui prévoient les rendements. Sur six fonds canadiens, apprendre avec plusieurs frais possibles donne presque les mêmes résultats que supposer leur coût moyen. |

### Entreprises et crédit

| Projet | Ce qu’on y étudie |
|---|---|
| [09 · Évaluer le Canadien National](https://github.com/Guilou001/09-valorisation-entreprise) | Relier le prix d’une action à l’argent que l’entreprise pourrait générer. Comparer plusieurs évaluations du Canadien National et calculer la croissance que son cours suppose, sous des hypothèses explicites. |
| [10 · Étudier un dossier de crédit](https://github.com/Guilou001/10-credit-bancaire) | Estimer le risque qu’un emprunteur ne rembourse pas. Vérifier les calculs sur des prêts simulés dont les risques sont connus, puis examiner les comptes d’Enbridge dans un dossier Excel. |
| [27 · Mesurer le risque des gros emprunteurs](https://github.com/Guilou001/27-portefeuille-de-credit) | Une banque dépend davantage de quelques clients lorsque leurs prêts concentrent une grande part du montant total. Une simulation mesure l’argent supplémentaire nécessaire pour absorber les pertes dans ce cas. |
| [28 · Lire les comptes autrement](https://github.com/Guilou001/28-etats-financiers-reformules) | Réorganiser les comptes des industries canadiennes pour séparer ce que leur activité rapporte de ce que leur financement ajoute ou retire. Montrer pourquoi les dettes entre sociétés d’un même groupe comptent. |
| [29 · Comprendre la rentabilité des banques](https://github.com/Guilou001/29-rentabilite-des-banques) | Décomposer la rentabilité comptable des six grandes banques canadiennes. Depuis 1997, elles conservent davantage de bénéfice par dollar de revenu, mais leur rentabilité comptable moyenne baisse sur la période étudiée. |

### Risques et assurance

| Projet | Ce qu’on y étudie |
|---|---|
| [06 · Prévoir les mauvaises journées de Bourse](https://github.com/Guilou001/06-risque-marche) | Comparer six façons d’annoncer une limite de perte quotidienne, puis compter les jours où elle est dépassée. Aucun modèle ne réussit tous les contrôles de risque du projet. |
| [15 · Calculer le prix d’une option](https://github.com/Guilou001/15-valorisation-options) | Une option donne le droit d’acheter ou de vendre plus tard à un prix fixé. Comparer plusieurs méthodes de calcul à des prix de référence et vérifier leurs marges d’erreur. |
| [17 · Financer les rentes d’un assureur](https://github.com/Guilou001/17-alm-assurance-vie) | Comparer plusieurs façons de choisir des obligations pour payer des rentes pendant des décennies. Mesurer comment les variations de taux changent l’écart entre la valeur des placements et celle des rentes à payer. |
| [25 · Traduire un scénario climatique en pertes de crédit](https://github.com/Guilou001/25-scenario-climatique-bsif) | Refaire l’exemple du régulateur bancaire canadien. Expliquer comment ses hypothèses climatiques modifient la probabilité de non-remboursement et la perte attendue. Il s’agit d’un scénario imposé, pas d’une prévision. |
| [26 · Prévoir la facture d’un assureur](https://github.com/Guilou001/26-provisionnement-iard) | Estimer ce qu’un assureur devra encore payer pour des sinistres déjà survenus. Dans les données étudiées, la facture finale sort de la fourchette annoncée bien plus souvent que prévu. |
| [30 · Prévoir le capital contre les fraudes et les erreurs](https://github.com/Guilou001/30-risque-operationnel) | Reconstituer le capital réglementaire lié aux fraudes, erreurs et pannes bancaires à partir des relevés publics. Distinguer ce que l’on peut calculer de ce qui reste incertain sans les données internes. |
| [31 · Chiffrer une garantie de placement](https://github.com/Guilou001/31-fonds-distincts) | Un assureur promet de protéger une partie de la valeur d’un placement. Calculer le capital demandé face à une baisse des actions et à des variations de prix plus fortes. |
| [32 · Mesurer le risque d’un échange d’intérêts](https://github.com/Guilou001/32-xva-swaps) | Deux parties s’échangent des intérêts pendant plusieurs années. Calculer comment leur risque de non-paiement et le calendrier des échanges modifient la valeur du contrat, puis comparer à une étude de référence. |

### Économie canadienne

| Projet | Ce qu’on y étudie |
|---|---|
| [07 · Estimer la croissance avant sa publication](https://github.com/Guilou001/07-nowcast-pib-canada) | Prévoir la croissance du trimestre en cours à partir de données mensuelles. Leur apport est comparé à celui de modèles plus complexes, avec des délais de publication simulés et des données révisées. |
| [11 · Lire les taux d’intérêt](https://github.com/Guilou001/11-courbe-des-taux) | Tester ce que les taux canadiens permettent de prévoir sur leurs mouvements futurs et les récessions. Dans l’exercice, supposer que les taux resteront inchangés bat presque toujours le modèle étudié. |
| [18 · Distinguer l’inflation durable des à-coups](https://github.com/Guilou001/18-inflation-fondamentale) | Comparer les mesures canadiennes qui cherchent la tendance générale des prix en atténuant les mouvements extrêmes. Vérifier lesquelles restent utiles lorsque l’analyse inclut la forte inflation de 2021 à 2023. |

### Transactions en cours de journée

| Projet | Ce qu’on y étudie |
|---|---|
| [21 · Rejouer une stratégie minute par minute](https://github.com/Guilou001/21-vwap-intrajournalier) | Acheter ou vendre selon la position du prix par rapport à sa moyenne, pondérée par les volumes échangés. Mesurer comment de petits écarts de prix à chaque transaction peuvent effacer les gains. |
| [22 · Prévoir la dernière demi-heure](https://github.com/Guilou001/22-derniere-demi-heure) | Vérifier si le mouvement du début de journée annonce celui de la fin. Sur les fonds et la période testés, la relation historique se dégrade et les frais fragilisent les signaux restants. |
| [24 · Comparer deux sources de prix](https://github.com/Guilou001/24-vwap-iex-vs-consolide) | Comparer les transactions d’une seule bourse à celles du marché américain rassemblé. Des données presque toujours présentes peuvent donner une moyenne différente et inverser une décision d’achat ou de vente. |

### Recherche et apprentissage automatique

| Projet | Ce qu’on y étudie |
|---|---|
| [04 · Mon mémoire de maîtrise de 2024](https://github.com/Guilou001/04-memoire-uqam-2024) | Reproduire un travail sur la prévision des rendements d’actions canadiennes et américaines. L’audit révèle notamment que la cible prévue porte sur un mois déjà écoulé. Ce défaut est conservé et documenté. |
| [05 · Reprendre la question du mémoire](https://github.com/Guilou001/05-memoire-2.0) | Mieux séparer l’apprentissage des tests et déduire les frais de transaction. Les modèles testés restent derrière la répartition égale. Les données révisées et la sélection des actions restent des limites déclarées. |
| [34 · Tester des modèles plus complexes](https://github.com/Guilou001/34-complexite-utile) | Comparer des modèles simples et complexes pour prévoir le marché américain. Dans le test avec frais et contraintes, les données ne démontrent pas d’avantage du modèle complexe. |
| [35 · Comprendre le désaccord des modèles](https://github.com/Guilou001/35-desaccord-obligations) | Mesurer ce que révèle le désaccord entre six modèles qui prévoient les rendements obligataires. Il renseigne sur leurs erreurs futures, mais pénaliser ce désaccord dégrade ici le portefeuille après les frais. |
| [Laboratoire de recherche quantitative](https://github.com/Guilou001/quant-research-platform) | Reproduire des stratégies publiées, les tester sur d’autres périodes et comptabiliser les essais. Le laboratoire examine si leurs gains résistent aux coûts et aux contrôles qui cherchent à écarter un succès dû au hasard. |

### Travaux universitaires

Ces travaux de maîtrise de 2021 et 2022 sont accompagnés du code permettant de refaire les calculs. Les dépôts distinguent le travail remis, les vérifications ajoutées et les données remplacées lorsque les fichiers du cours ne sont pas publics.

| Projet | Ce qu’on y étudie |
|---|---|
| [Prévoir une action avec un réseau de neurones](https://github.com/Guilou001/uqam-transformer-actions) | Donner à un modèle l’historique des prix et des volumes de la Banque Royale pour prévoir le lendemain. Sur les rendements quotidiens bruts testés, ses prévisions restent presque constantes. |
| [Comprendre les cycles de l’économie canadienne](https://github.com/Guilou001/uqam-cycle-economique-canada) | Mesurer comment la production, l’emploi et les autres grandeurs économiques bougent ensemble. Prolonger les données montre combien le choc de 2020 change le constat d’une économie devenue plus stable. |
| [Comparer neuf modèles sur sept jeux de données](https://github.com/Guilou001/uqam-apprentissage-sept-bases) | Prédire des valeurs dans des domaines différents, des logements à l’économie. Aucun modèle ne gagne partout. Les fichiers disponibles permettent de distinguer les résultats reproduits des exercices reconstruits. |
| [Prévoir le chômage américain](https://github.com/Guilou001/uqam-prevision-facteurs) | Comparer des prévisions à plusieurs mois d’avance, puis mesurer leurs erreurs. Examiner aussi si conserver les observations exceptionnelles de la pandémie aide ou gêne la prévision des mois suivants. |
| [Étudier les effets des taux et des dépenses publiques](https://github.com/Guilou001/uqam-svar-monetaire-budgetaire) | Estimer comment l’économie américaine réagit à une variation de taux ou de dépenses publiques. Montrer que les réponses dépendent de la période et des hypothèses utilisées pour séparer les causes. |
| [Vérifier un modèle de croissance](https://github.com/Guilou001/uqam-croissance-capital-humain) | Transformer un travail théorique en calculs reproductibles. Retrouver les paramètres et vérifier les équations d’équilibre. Ces contrôles vérifient les calculs, sans prouver que le modèle décrit correctement l’économie. |

### Outils communs

| Projet | À quoi il sert |
|---|---|
| [gv-fintools](https://github.com/Guilou001/gv-fintools) | Réutiliser les mêmes outils pour télécharger des données, produire des graphiques lisibles et transformer les présentations des projets en rapports PDF. Cela évite de recopier le même code dans chaque dépôt. |
| [Guides de rédaction pédagogique](https://github.com/Guilou001/skill-redaction-pedagogique) | Deux guides pour expliquer les termes techniques, donner le contexte des chiffres et accompagner la lecture des tableaux. Ils servent à rendre les documents plus compréhensibles sans perdre leur précision. |

## Comment je travaille

- Je relève la provenance des données et les transformations nécessaires pour les utiliser.
- Je vérifie les calculs avec des exemples connus, des résultats publiés ou des cas que l’on peut résoudre à la main.
- Pour les prévisions et les placements, je compare les méthodes à un repère simple et je précise les périodes de test.
- Je documente les limites, les corrections et les résultats qui contredisent l’hypothèse de départ.

J’utilise Python pour les calculs et les graphiques, SQL avec DuckDB pour organiser les données, et Excel pour les analyses à formules consultables. Les projets utilisent aussi des tests automatisés et, selon le besoin, Docker, LEAN, LaTeX ou Typst.

<details>
<summary>English overview</summary>

Financial economist based in Montréal, with an MSc in Financial Economics from UQAM, completed in 2024. My projects cover portfolio management, banking, insurance, economic forecasting and empirical finance.

I reproduce published research, check calculations against known examples and test investment methods on later periods. Each project explains its data, assumptions and limitations, including unsuccessful results. The repositories above contain the code and project write-ups, primarily in French.

</details>
