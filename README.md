# Guillaume Vaudescal

Économiste financier (M. Sc. économie financière, UQAM, 2024), Montréal. Je reproduis des papiers de finance
empirique sur données libres, je mesure ce qui survit hors échantillon, et je documente aussi ce qui ne
survit pas. Chaque dépôt contient le code, les données téléchargeables par script, les tests, une CI, et un
compte rendu dont chaque chiffre porte son statut (mesuré, rapporté, modélisé) et vient d'un fichier de
résultats du dépôt.

*Financial economist (MSc, UQAM 2024), Montréal. I replicate empirical-finance papers on open data, measure
what survives out of sample, and document what does not. Every repository ships code, scripted data
downloads, tests, CI, and a report where each number carries its provenance.*

| Dépôt | La question posée | Ce qui est mesuré |
|---|---|---|
| [memoire-uqam-2024](https://github.com/Guilou001/memoire-uqam-2024) | Mon mémoire (8 modèles d'apprentissage machine, macro LCDMA et FRED-MD, 50 titres TSX et 50 titres S&P 500, 2008-2024) se réexécute-t-il, et que valent ses portefeuilles long short une fois le short réellement soustrait ? | Réexécution exacte (écart 2,8 × 10⁻⁷) ; long short réel : au mieux 7,4 % par an aux États-Unis, 5,6 % au Canada, sous l'équipondéré ; v1.1 avec PDF des résultats refaits |
| [memoire-2.0](https://github.com/Guilou001/memoire-2.0) | La même question, refaite avec les méthodes de 2026 : information réellement disponible, réglages gelés hors test, validation croisée purgée, coûts, Sharpe déflaté | Aucun des huit modèles ne bat l'équipondéré ; la rotation de 2 à 3 par mois coûte plus que le signal extrait ; Sharpe déflaté maximal 0,86, sous le seuil de 0,95 |
| [efficient-frontier-mpt](https://github.com/Guilou001/efficient-frontier-mpt) | À quelle distance 50 000 portefeuilles aléatoires restent-ils de la frontière de Markowitz exacte, et le portefeuille tangent tient-il hors échantillon contre 1/N ? | Meilleur Sharpe simulé 0,73 contre 0,80 pour la tangence exacte ; hors échantillon net de coûts, le tangent bat 1/N aux États-Unis (0,77 contre 0,51) et perd au Canada (0,62 contre 0,73) |
| [estimation-error-lab](https://github.com/Guilou001/estimation-error-lab) | La réplication exacte de DeMiguel, Garlappi et Uppal (2009) tient-elle, et le verdict « rien ne bat 1/N » survit-il à vingt ans de données de plus ? | 312/312 cellules des tables 3 et 4 reproduites à la précision imprimée ; une cellule dégénérée du papier découverte ; sur 1963-2026, aucune règle ne bat 1/N sur les quatre univers à la fois |
| [portfolio-ops-ca](https://github.com/Guilou001/portfolio-ops-ca) | Les briques d'un gestionnaire institutionnel (Black-Litterman, HRP, attribution de Brinson, bandes de politique), vérifiées contre leurs papiers, rapportent-elles quelque chose une fois branchées sur six FNB canadiens ? | Chaîne Idzorek (2005) exacte aux 2 décimales imprimées ; moteur 2007-2026 sur FNB de Toronto : la politique à bandes sans vue fait 6,66 % par an net, les vues systématiques 6,28 % ; rapport mensuel régénérable |
| [skill-redaction-pedagogique](https://github.com/Guilou001/skill-redaction-pedagogique) | Un skill Claude Code : écrire des documents techniques en français clair sans perdre la rigueur | Utilisé pour les README de tous les dépôts ci-dessus |

## Par où commencer, en trois arrêts

1. **La réplication la plus dure** : [estimation-error-lab](https://github.com/Guilou001/estimation-error-lab),
   312 cellules sur 312 de DeMiguel, Garlappi et Uppal (2009) reproduites à la précision imprimée, puis le
   verdict retesté sur 63 ans.
2. **Le métier de gestionnaire** : [portfolio-ops-ca](https://github.com/Guilou001/portfolio-ops-ca),
   de la politique de placement au rapport mensuel, chaque brique vérifiée contre son papier fondateur.
3. **La méthode de 2026** : [memoire-2.0](https://github.com/Guilou001/memoire-2.0), le même mémoire refait
   sans fuite d'information, avec validation purgée, coûts et Sharpe déflaté, et un verdict négatif assumé.

## Ce que chaque dépôt démontre

| Compétence | Dépôts |
|---|---|
| Réplication quantitative et rigueur hors échantillon | estimation-error-lab, memoire-2.0, efficient-frontier-mpt |
| Gestion de portefeuille institutionnelle (allocation, attribution, politique) | portfolio-ops-ca, efficient-frontier-mpt |
| Apprentissage machine appliqué aux rendements | memoire-uqam-2024, memoire-2.0 |
| Backtests propres (walk-forward, coûts, validation purgée) | memoire-2.0, portfolio-ops-ca, estimation-error-lab, efficient-frontier-mpt |
| Rédaction technique bilingue, chiffres sourcés | tous, plus skill-redaction-pedagogique |

En cours, dans l'ordre : `risk-engine-ca` (VaR et ES, backtests de Bâle), `nowcast-canada`,
`factor-lab-ca`, `valuation-lab-ca` (analyse fondamentale et DCF d'une société du TSX),
`credit-lab-ca`, `yield-curve-ca`.

Outils : Python 3.12 (uv, pandas, scikit-learn, cvxpy, matplotlib), SQL, Excel, LaTeX et Typst.
Données libres seulement : Yahoo Finance (usage personnel), FRED, Banque du Canada (Valet), Ken French,
LCDMA. Français d'abord, résumé anglais dans chaque dépôt.
