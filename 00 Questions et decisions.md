# Questions et decisions - Correction des six presets

## Questions posees avant modification

| Question | Reponse retenue |
|----------|-----------------|
| Perimetre des fichiers | Corriger uniquement les fichiers Markdown |
| Synchronisation de la couverture | Mettre aussi `00 Setlist Coverage.md` a jour |
| Priorite lors des suppressions | Preserver la couverture de la setlist |
| Etat des IR en live | Mettre les six IR en bypass par defaut |

## Decisions prises en autonomie

| Sujet | Decision | Motif |
|-------|----------|-------|
| Interpretation des quatre blocs | Compter quatre blocs libres en plus des blocs fixes Wah, Volume, FX Loop, ampli, cab/IR et EQ | Architecture imposee du POD Go et regles du projet |
| 06A | Retirer `Simple Delay` | Le clean principal garde compression, push, chorus et reverb ; l'EQ fixe conserve la projection |
| 06B | Retirer `LA Studio Comp` | Le crunch de l'Essex fournit deja de la compression ; les deux gains et le solo sont prioritaires |
| 06C | Retirer `Glitz` | Le preset rock peut rester sec ; chorus, deux gains et delay de solo couvrent mieux les morceaux |
| 06D | Retirer `70s Chorus` | Pour le registre lourd, deux gains, delay de lead et reverb sont plus utiles |
| 07A | Retirer `Kinky Boost` | Le clean ethere repose d'abord sur compresseur, chorus, delay et Glitz |
| 07B | Retirer `LA Studio Comp` | L'edge-of-breakup doit rester dynamique ; push, chorus, delay et reverb sont prioritaires |
| FX Loop | L'ajouter explicitement, bypass par defaut | Le bloc est obligatoire mais aucun effet externe n'est indique |
| Wah et Volume | Les montrer dans tous les chemins ; Wah bypass, Volume sur EXP 2 | Rendre le chemin complet et exploitable sans consommer de bloc libre |
| Footswitch IR | Utiliser FS6 libre pour l'IR casque | Evite une activation manuelle dans l'interface et ne sacrifie aucune fonction musicale |
| Niveau des IR | Uniformiser a `-18.0 dB` | Eviter les ecarts de niveau casque entre presets ; valeur deja documentee sur 06A et 06B |
| Egalisation des volumes | Garder les `Ch Vol` initiaux et viser un ecart percu maximal d'environ 1 dB autour de 06A | Un clean et un son sature n'ont pas le meme niveau percu a valeur numerique egale ; le reglage final exige le materiel et le volume de repetition |
| DSP | Signaler les presets plus charges et demander une verification au chargement | Le respect exact depend de la version du firmware et des modeles disponibles |

## Question apparue pendant le travail

| Question | Choix effectue |
|----------|----------------|
| Faut-il conserver les references `FS5:OFF si sec` de 06C apres retrait de Glitz ? | Non. Le preset devient sec par conception et FS5 reste libre |
