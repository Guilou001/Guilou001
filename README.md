# Guillaume Vaudescal

Économiste financier (M. Sc. économie financière, UQAM, 2024), Montréal. Je reproduis des papiers de finance
empirique sur données libres, je mesure ce qui survit hors échantillon, et je documente aussi ce qui ne
survit pas. Chaque dépôt contient le code, les données téléchargeables par script, les tests, une CI, et un
compte rendu dont chaque chiffre porte son statut (mesuré, rapporté, modélisé) et vient d'un fichier de
résultats du dépôt. Les numéros des dépôts donnent l'ordre de lecture, des fondations vers le capstone.

*Financial economist (MSc, UQAM 2024), Montréal. I replicate empirical-finance papers on open data, measure
what survives out of sample, and document what does not. Every repository ships code, scripted data
downloads, tests, CI, and a report where each number carries its provenance. Repository numbers give the
reading order, from foundations to capstone.*

| Dépôt | La question posée | Ce qui est mesuré |
|---|---|---|
| [01-efficient-frontier-mpt](https://github.com/Guilou001/01-efficient-frontier-mpt) | À quelle distance 50 000 portefeuilles aléatoires restent-ils de la frontière de Markowitz exacte, et le portefeuille tangent tient-il hors échantillon contre 1/N ? | Meilleur Sharpe simulé 0,73 contre 0,80 pour la tangence exacte ; hors échantillon net de coûts, le tangent bat 1/N aux États-Unis (0,77 contre 0,51) et perd au Canada (0,62 contre 0,73) |
| [02-estimation-error-lab](https://github.com/Guilou001/02-estimation-error-lab) | La réplication exacte de DeMiguel, Garlappi et Uppal (2009) tient-elle, et le verdict « rien ne bat 1/N » survit-il à vingt ans de données de plus ? | 312/312 cellules des tables 3 et 4 reproduites à la précision imprimée ; une cellule dégénérée du papier découverte ; sur 1963-2026, aucune règle ne bat 1/N sur les quatre univers à la fois |
| [03-portfolio-ops-ca](https://github.com/Guilou001/03-portfolio-ops-ca) | Les briques d'un gestionnaire institutionnel (Black-Litterman, HRP, attribution de Brinson, bandes de politique), vérifiées contre leurs papiers, rapportent-elles quelque chose une fois branchées sur six FNB canadiens ? | Chaîne Idzorek (2005) exacte aux 2 décimales imprimées ; moteur 2007-2026 sur FNB de Toronto : la politique à bandes sans vue fait 6,63 % par an net, les vues systématiques 6,25 % ; rapport mensuel régénérable |
| [04-memoire-uqam-2024](https://github.com/Guilou001/04-memoire-uqam-2024) | Mon mémoire (8 modèles d'apprentissage machine, macro LCDMA et FRED-MD, 50 titres TSX et 50 titres S&P 500, 2008-2024) se réexécute-t-il, et que valent ses portefeuilles long short une fois le short réellement soustrait ? | Réexécution exacte (écart 2,8 × 10⁻⁷) ; long short réel : au mieux 7,4 % par an aux États-Unis, 5,6 % au Canada, sous l'équipondéré ; v1.1 avec PDF des résultats refaits |
| [05-memoire-2.0](https://github.com/Guilou001/05-memoire-2.0) | La même question, refaite avec les méthodes de 2026 : information réellement disponible, réglages gelés hors test, validation croisée purgée, coûts, Sharpe déflaté | Aucun des huit modèles ne bat l'équipondéré ; la rotation de 2 à 3 par mois coûte plus que le signal extrait ; Sharpe déflaté maximal 0,01 une fois les 33 essais comptés, loin du seuil de 0,95 |
| [06-risk-engine-ca](https://github.com/Guilou001/06-risk-engine-ca) | Parmi six modèles de VaR à un jour (historique, gaussien, Student, EWMA, simulation historique filtrée, GARCH maison), lesquels survivent aux backtests réglementaires sur 22 ans de données canadiennes ? | Seule la simulation historique filtrée passe Kupiec (69 dépassements pour 54,8 attendus, p = 0,063) et n'a aucune année rouge de Bâle ; l'historique dépasse 22 fois dans la seule année 2008 |
| [07-nowcast-canada](https://github.com/Guilou001/07-nowcast-canada) | Pour prévoir le trimestre en cours du PIB canadien avec l'information réellement disponible, qui gagne : l'autorégression, le PIB mensuel, les 400 séries de la LCDMA ou l'apprentissage machine ? | Le bridge du PIB mensuel réduit l'erreur de 57 % contre l'AR au mois 3 (p = 0,027, hors COVID) ; le grand panel fait pire que l'AR au même mois, le bloc américain de FRED-MD dégrade le mois 1 |
| [08-factor-lab-ca](https://github.com/Guilou001/08-factor-lab-ca) | Les primes de facteurs canadiennes (valeur, momentum, bêta faible, qualité) ont-elles fondu après leur publication, comme aux États-Unis, et le Canada se distingue-t-il ? | Pas de décote après 2001 : momentum stable à 15,7 %/an (t = 3,3), valeur qui monte, et le Canada bat les États-Unis sur les quatre primes vivantes à période commune (corrélations bilatérales 0,37 à 0,82) |
| [09-valuation-lab-ca](https://github.com/Guilou001/09-valuation-lab-ca) | Que vaut le Canadien National, et surtout : quelle croissance le cours de 175 $ suppose-t-il, est-elle plausible au vu de quinze ans d'états financiers ? | DCF prudent 93 $, comparables 200-225 $ (le CN le moins cher de sa cohorte), et DCF inversé : le cours suppose 11,9 %/an de FCFF pendant 5 ans contre 7,8 % livré sur 2011-2025 et 4,0 % sur la dernière décennie ; classeur Excel à formules vivantes et mémo bilingue |
| [10-credit-lab-ca](https://github.com/Guilou001/10-credit-lab-ca) | Comment prouver qu'un moteur de probabilité de défaut mesure ce qu'il prétend, et que vaut le dossier de crédit d'Enbridge une fois les ratios étalés ? | Le hasard de Shumway retrouve les paramètres d'un portefeuille synthétique à vérité connue (−6,13 contre −6,20 vrai) ; l'ECL pondérée par scénarios dépasse la centrale de 0,6 % (convexité mesurée) ; capital IRB OSFI testé à la main ; dossier Excel Enbridge : la grille de ratios donne B, les agences BBB, et l'écart est l'enseignement |
| [11-yield-curve-ca](https://github.com/Guilou001/11-yield-curve-ca) | Diebold-Li bat-il encore la marche aléatoire, et la pente de la courbe prédit-elle encore les récessions canadiennes après l'inversion de 2022-23 sans récession ? | Non et non : la marche aléatoire gagne 26 cases sur 27 (1996-2026) ; hors échantillon l'AUROC de la pente tombe à 0,50 (0,27 hors COVID), fausse alarme de 2022-24 comprise ; en ALM, le choc réalisé de 2022 (+412 pb à 3 mois) coûte moitié moins que la pentification réglementaire : la forme du choc compte autant que l'ampleur |
| [12-plan-epargne-ca](https://github.com/Guilou001/12-plan-epargne-ca) | REER ou CELI d'abord, et que devient la promesse d'un plan de retraite quand on simule les rendements au lieu de les supposer constants ? | L'équivalence REER = CELI à taux égaux est prouvée par test analytique (1e-12) ; au cas type 35/25, REER d'abord gagne 8,0 % de richesse nette, mais le remboursement dépensé inverse le classement (-18,9 %) ; la promesse déterministe (95 862 $) cache un cinquième percentile à 45 855 $ ; au scénario prudent, un avenir sur dix ne finance pas la cible |
| [13-fx-hedge-ca](https://github.com/Guilou001/13-fx-hedge-ca) | Couvrir le dollar US est vendu comme de la prudence pure : est-ce vrai pour un investisseur canadien en actions américaines ? | Non, mesuré : la parité couverte des taux reconstruit XSP à 93 pb/an près (corr 0,995), et la couverture AUGMENTE le risque (vol 15,2 % contre 12,2 %, pire baisse -52 % contre -42 %), car le USD monte quand les actions tombent (corr -0,59) ; le ratio optimal vaut zéro |
| [14-performance-lab-ca](https://github.com/Guilou001/14-performance-lab-ca) | Quatre méthodes de chaînage d'attribution concurrentes : le verdict au comité dépend-il de la méthode choisie ? | Non : Cariño, Menchero, GRAP et Frongello réconcilient chacun exactement (résidu 5e-15, testé) et s'accordent à 0,83 point près sur 58,7 ; les totaux GRAP et Frongello sont identiques (identité redémontrée et testée) ; TWR, Dietz et MWR retombent au centième sur l'exemple officiel du GIPS Handbook 2020 |
| [17-licat-alm-ca](https://github.com/Guilou001/17-licat-alm-ca) | L'immunisation par la durée a-t-elle survécu à la torsion de courbe de 2022, et le capital TSAV prescrit couvrait-il la perte ? | L'appariement par taux clés ramène le surplus à son point de départ à travers 400 pb de torsion ; la duration seule erre ; sans couverture, insolvabilité transitoire ; et l'exigence du chapitre 5 (chocs en racine carrée des taux plancher de 2021 : +147 pb prescrits, 400 livrés) n'a couvert que 67 % de la perte réalisée |
| [skill-redaction-pedagogique](https://github.com/Guilou001/skill-redaction-pedagogique) | Un skill Claude Code : écrire des documents techniques en français clair sans perdre la rigueur | Utilisé pour les README de tous les dépôts ci-dessus |

## Par où commencer, en trois arrêts

1. **La réplication la plus dure** : [02-estimation-error-lab](https://github.com/Guilou001/02-estimation-error-lab),
   312 cellules sur 312 de DeMiguel, Garlappi et Uppal (2009) reproduites à la précision imprimée, puis le
   verdict retesté sur 63 ans.
2. **Le métier de gestionnaire** : [03-portfolio-ops-ca](https://github.com/Guilou001/03-portfolio-ops-ca),
   de la politique de placement au rapport mensuel, chaque brique vérifiée contre son papier fondateur.
3. **La méthode de 2026** : [05-memoire-2.0](https://github.com/Guilou001/05-memoire-2.0), le même mémoire refait
   sans fuite d'information, avec validation purgée, coûts et Sharpe déflaté, et un verdict négatif assumé.

## Ce que chaque dépôt démontre

| Compétence | Dépôts |
|---|---|
| Réplication quantitative et rigueur hors échantillon | 02-estimation-error-lab, 05-memoire-2.0, 01-efficient-frontier-mpt |
| Gestion de portefeuille institutionnelle (allocation, attribution, politique) | 03-portfolio-ops-ca, 01-efficient-frontier-mpt |
| Apprentissage machine appliqué aux rendements | 04-memoire-uqam-2024, 05-memoire-2.0 |
| Backtests propres (walk-forward, coûts, validation purgée) | 05-memoire-2.0, 03-portfolio-ops-ca, 02-estimation-error-lab, 01-efficient-frontier-mpt |
| Gestion des risques (VaR, ES, backtests réglementaires) | 06-risk-engine-ca |
| Macroéconomie appliquée (nowcasting, temps réel) | 07-nowcast-canada |
| Recherche facteurs et valorisation d'actifs | 08-factor-lab-ca, 02-estimation-error-lab |
| Analyse fondamentale et valorisation d'entreprise (DCF, comparables, Excel) | 09-valuation-lab-ca |
| Risque de crédit et banque commerciale (PD, IFRS 9, IRB, dossier de crédit) | 10-credit-lab-ca |
| Courbe des taux et ALM bancaire (Nelson-Siegel, probit, IRRBB, durations clés) | 11-yield-curve-ca |
| Planification d'épargne et Monte Carlo client (REER/CELI, risque de séquence) | 12-plan-epargne-ca |
| Couverture de change et overlay (parité couverte, ratio à variance minimale) | 13-fx-hedge-ca |
| Mesure et attribution de performance (Brinson, chaînages, TWR/MWR, GIPS) | 14-performance-lab-ca |
| ALM d'assurance vie et capital réglementaire (TSAV, Redington, taux clés) | 17-licat-alm-ca |
| Rédaction technique bilingue, chiffres sourcés | tous, plus skill-redaction-pedagogique |

Quinze dépôts publiés (01-14 et 17). En réserve, vérifiés source par source : pricing d'options (15), options d'achat couvertes (16), inflation fondamentale (18), immobilier Teranet (19), entrepôt point-in-time SEC (20)
(projection REER/CELI par simulation).

Outils : Python 3.12 (uv, pandas, scikit-learn, cvxpy, matplotlib), SQL, Excel, LaTeX et Typst.
Données libres seulement : Yahoo Finance (usage personnel), FRED, Banque du Canada (Valet), Ken French,
LCDMA. Français d'abord, résumé anglais dans chaque dépôt.
