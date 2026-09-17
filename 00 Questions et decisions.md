# Questions et decisions - Refonte des six presets

## Questions posees avant modification

| Question | Reponse retenue |
|----------|-----------------|
| Perimetre des fichiers | Corriger uniquement les fichiers Markdown |
| Synchronisation de la couverture | Mettre aussi `00 Setlist Coverage.md` a jour |
| Priorite lors des choix | Preserver et ameliorer la couverture de toute la setlist |
| Etat des IR en live | Mettre les six IR en bypass par defaut |
| Questions pendant l'absence de l'utilisateur | Ne pas interrompre ; prendre une decision et la consigner ici |

## Corrections apportees a la premiere passe

| Sujet | Premiere interpretation | Decision finale |
|-------|-------------------------|-----------------|
| Ordre des blocs | Chemin trop uniforme et presente comme impose | Tous les blocs sauf Input/Output sont mobiles ; chaque ordre sert le son vise |
| Quatre blocs | Quatre effets libres correctement comptes, mais sans exploiter assez les blocs dedies | Quatre effets libres plus Wah, Volume, FX Loop, Amp/Preamp, Cab/IR et Preset EQ dedies |
| Paliers de gain | Drives externes souvent conserves | `FS1` alterne Drive et Ch Vol de l'ampli, plus HBE sur 06D |
| Preset EQ | Utilise surtout comme bloc bypassable | Toujours ON ; `FS3` alterne ses parametres de solo sans bypasser le bloc |
| Niveau IR | `-18 dB` considere comme egalisation certaine | `-18 dB` reste un point de depart commun, a calibrer pour chaque fichier au casque |

## Sources officielles consultees

- `POD Go 2.50 Owner's Manual`, notamment les sections sur le signal flow, le deplacement des blocs, le DSP, les assignations bypass/controller, les sorties et le Global EQ.
- Liste officielle `POD Go 2.50 Models` : <https://line6.com/podgo-models/>.
- Manuel officiel : <https://line6.com/data/6/0a000f7108016a9ad09ab9f54/application/pdf/POD%20Go%202.50%20Owner's%20Manual%20-%20English%20.pdf>.

Le fichier `AGENTS.md` a ete corrige lorsque ses anciennes formulations contredisaient le manuel.

## Decisions de conception

| Sujet | Decision | Motif |
|-------|----------|-------|
| Logique commune | FS1 Gain, FS3 Solo, FS4 Space, FS6 IR casque | Reduit les erreurs en concert |
| FS1 | Alterner les parametres de l'ampli plutot qu'ajouter un drive | Economise un bloc et permet un changement de section en une frappe |
| Compensation FS1 | Reduire simultanement Ch Vol quand Drive augmente | Limite le saut de volume cause par la compression |
| FS3 | Activer Simple Delay et augmenter Mid Gain/Level du Preset EQ | Un seul geste pour le solo, environ +1.5 a +2 dB percus |
| IR | Bypass par defaut, FS6 dedie | Vrai baffle en live, activation rapide au casque |
| Sortie | MAIN Out niveau Line, Output Center/0.0 dB | Branchement coherent dans l'etage de puissance du Katana |
| Volume | Place apres ampli et avant les effets temporels | Permet les swells tout en conservant leurs queues |
| Chorus | Mode Classic | Usage essentiellement mono vers un baffle reel |
| DSP | Signaler 07A puis 06D comme presets a verifier en priorite | Glitz et les amplis peuvent consommer davantage ; le bypass ne libere pas le DSP |

## Choix par preset

| Preset | Quatre blocs | Choix determinant |
|--------|--------------|-------------------|
| 06A | LA Studio Comp, 70s Chorus, Simple Delay, Plate | Le gain d'ampli remplace Kinky Boost ; le delay revient pour les solos pop |
| 06B | Minotaur, 70s Chorus, Simple Delay, Plate | Gain principal par l'Essex ; Minotaur reserve au sustain supplementaire |
| 06C | Hedgehog D9, 70s Chorus, Simple Delay, Plate | Suppression de la 808 afin de retrouver un vrai couplet clean |
| 06D | Scream 808, Simple Delay, Plate, LA Studio Comp | Placater Drive/HBE fournit le gain lourd ; compresseur reserve au solo |
| 07A | LA Studio Comp, 70s Chorus, Simple Delay, Glitz | Conserve une vraie identite etheree et gagne un crescendo via l'ampli |
| 07B | Simple Pitch, Simple Delay, Plate, LA Studio Comp | Octave -12 dediee a Seven Nation Army ; gain roots fourni par l'Essex |

## Reorganisation de la setlist

| Decision | Motif |
|----------|-------|
| `Come As You Are` passe de 05B a 06C | Les six presets couvrent maintenant les 51 morceaux ; chorus + D9 reproduisent le contraste essentiel |
| `Island In The Sun` et `Jean Baltazar` passent a 07B | Leur edge-of-breakup organique convient mieux que le clean jangle |
| `A Ma Place` passe a 06B | Le crunch Vox correspond mieux aux refrains |
| `Today`, `Not An Addict`, `Celebrity Skin` et `Hello` passent a 06C | Ils exigent un vrai contraste clean/mur de distorsion |
| `Personal Jesus`, `Seven Nation Army` et `The Man Who Sold The World` passent a 07B | Riffs roots/garage ; octave specifique pour Seven Nation Army |
| `Rockin' In The Free World` passe a 06C | Distorsion ouverte 90s, moins moderne que 06D |
| `Kiss Me`, `This Is The Life` et `Wonderwall` passent ou restent a 06A | Jangle et strumming clair plus importants que l'ambiance etheree |

## Questions tranchees en autonomie

| Question | Choix effectue |
|----------|----------------|
| Faut-il repartir egalement les morceaux entre les presets ? | Non ; les 18 titres de 06C refletent la dominante alt-rock reelle de la setlist |
| Faut-il remplacer Hedgehog D9 par un modele DS-1 plus historique ? | Non pour cette passe ; D9 est deja documente et offre un mur plus polyvalent, mais `Deez One Vintage` reste une alternative a tester |
| Faut-il remplacer Glitz pour garantir le DSP ? | Non ; elle definit 07A. Si elle est grisee sur l'appareil, la remplacer par Plate |
| Faut-il utiliser Amp ou Preamp vers le Katana ? | Conserver Amp comme point de depart musical ; comparer Preamp sur le materiel reel avant tout remplacement global |
| Faut-il garantir numeriquement les six volumes ? | Impossible sans mesure sur le systeme reel ; fournir un protocole et des Ch Vol de depart coherents |
| Faut-il conserver les references a un septieme preset 05B ? | Non ; toute la playlist doit tenir dans les six presets |
