# POD Go - Preset Generique V2
# Clean / Crunch / Hard-Metal / Solo
# Telecaster Standard Mex - Micro Fender Vintage '64

---

## Signal Path (7 blocs + EQ param gratuit + pedale expression)

```
Input > [1. COMP: LA Studio Comp] > [2. DIST: Minotaur] > [3. DIST: Hedgehog D9] > [4. AMP: Placater Clean] > [5. DELAY: Simple Delay] > [6. REVERB: Glitz] > [7. CAB: 4x12 Cali V30] > Output
                                                                                          |
                                                                                     [EQ Param] (bloc gratuit, post-amp)
                                                                                          |
                                                                                     [Pedale: Volume] (bloc gratuit)
```

---

## Reglages detailles

### Bloc 1 - LA Studio Comp (modele Teletronix LA-2A)
| Param          | Valeur   |
|----------------|----------|
| Peak Reduction | 2.5      |
| Gain           | 4.5      |
| Type           | Compress |
| Mix            | 50%      |
| Etat par defaut| ON       |

Role : Compression douce, parallele (mix 50%). Peak Reduction baisse
a 2.5 pour preserver la dynamique et l'attaque de la Tele — essentiel
pour le jeu percussif style Fogerty/Eagle-Eye Cherry. Mix a 50% garde
du punch naturel. ON par defaut, footswitch FS5 pour le couper en
high gain si le son semble trop ecrase.

### Bloc 2 - Minotaur (modele Klon Centaur)
| Param          | Valeur |
|----------------|--------|
| Gain           | 3.0    |
| Level          | 7.0    |
| Tone           | 5.5    |
| Etat par defaut| OFF    |

Role : Boost transparent / crunch. Gain bas + level haut = pousse l'ampli
en crunch blues/rock sans denaturer le son de la Tele.

### Bloc 3 - Hedgehog D9 (modele DOD OD250 / YJM308)
| Param          | Valeur |
|----------------|--------|
| Gain           | 7.5    |
| Level          | 5.0    |
| Tone           | 4.5    |
| Etat par defaut| OFF    |

Role : Distortion hard/metal. Son serre et agressif.
Seul = hard rock. Avec Minotaur devant = plus de sustain pour leads metal.

### Bloc 4 - Placater Clean (modele Friedman BE-100 canal clean)
| Param          | Valeur |
|----------------|--------|
| Drive          | 3.5    |
| Bass           | 4.0    |
| Mid            | 5.0    |
| Treble         | 7.5    |
| Presence       | 7.0    |
| Master         | 8.0    |
| Channel Vol    | 9.0    |
| Etat           | TOUJOURS ON |

Role : Coeur du son. Drive a 3.5 = clean net et defini, chaque corde
se detache. Bass a 4 pour eviter l'empâtement. Mid a 5 = mediums
presents mais pas boueux. Treble 7.5 et Presence 7 pour l'attaque
tranchante style Fogerty/Eagle-Eye Cherry/Counting Crows.
Master a 8 et Channel Vol a 9 pour un niveau clean genereux.
Repond tres bien aux pedales de gain en amont. Plus polyvalent qu'un
Fender pour encaisser du high gain.
Note : le volume global est plus fort sur tous les sons. Si les canaux
avec gain sont trop forts, baisser le Level du Minotaur/Hedgehog.

### Bloc 5 - Simple Delay
| Param          | Valeur |
|----------------|--------|
| Time           | 400 ms |
| Feedback       | 25%    |
| Mix            | 25%    |
| Level          | 0 dB   |
| Etat par defaut| OFF    |

Role : Delay polyvalent. 400ms = bon compromis rythme/solo.
Feedback modere pour ne pas noyer le son.

### Bloc 6 - Glitz (Reverb)
| Param          | Valeur |
|----------------|--------|
| Decay          | 3.0 s  |
| Predelay       | 80 ms  |
| Mix            | 20%    |
| Tone           | 6.0    |
| Etat par defaut| OFF    |

Role : Reverb shimmer/plate. Predelay a 80ms preserve l'attaque.
Mix bas pour rester subtil. Combine avec delay en solo = gros son lead.

### Bloc 7 - Cab: 4x12 Cali V30
| Param          | Valeur     |
|----------------|------------|
| Mic            | 57 Dynamic |
| Distance       | 2.0        |
| Low Cut        | 80 Hz      |
| High Cut       | 8.0 kHz    |
| Level          | 0 dB       |
| Etat par defaut| OFF        |

Role : Simulation baffle pour casque. 4x12 V30 + SM57 = standard
qui fonctionne de clean a metal. OFF pour sortie FX Return ampli,
ON pour casque.

### EQ Parametrique (bloc gratuit - post amp)
| Param          | Valeur    |
|----------------|-----------|
| Low Freq       | 100 Hz    |
| Low Gain       | +2.0 dB   |
| Mid Freq       | 800 Hz    |
| Mid Q          | 2.0       |
| Mid Gain       | +3.5 dB   |
| High Freq      | 3.2 kHz   |
| High Gain      | +1.0 dB   |
| Level          | +3.0 dB   |
| Etat par defaut| OFF       |

Role : Boost solo. Mid push a 800 Hz pour percer dans le mix + boost
de level. Pas de coloration de gain, fonctionne avec toutes les
combinaisons.

### Pedale d'expression
| Assignation    | Volume (post-amp, pre-effets) |
|----------------|-------------------------------|
| Heel (min)     | 0%                            |
| Toe (max)      | 100%                          |

Note : Peut etre switchee en Wah via le toe switch integre si besoin.

---

## Configuration STOMP (6 Footswitches en mode STOMP)

Le POD Go dispose de 6 footswitches assignables en mode STOMP (FS1-FS6).

| FS1               | FS2                 | FS3                         | FS4               | FS5                    | FS6               |
|-------------------|---------------------|-----------------------------|-------------------|------------------------|-------------------|
| Minotaur (Bloc 2) | Hedgehog D9 (Bloc 3)| EQ Param + Delay + Reverb  | Cab 4x12 (Bloc 7) | LA Studio Comp (Bloc 1)| Delay (Bloc 5)    |
| CRUNCH ON/OFF     | HARD/METAL ON/OFF   | SOLO MODE ON/OFF            | CAB SIM ON/OFF    | COMP ON/OFF            | DELAY ON/OFF      |

Rangee du haut (FS1-FS3) : les 3 sons principaux (crunch / metal / solo)
Rangee du bas (FS4-FS6) : utilitaires (cab sim / comp / delay independant)

Notes :
- FS3 est une multi-assignation qui active/desactive les 3 blocs
  d'un coup (EQ param + delay + reverb). Un seul appui = mode solo.
- FS6 permet d'activer le delay seul (sans le boost solo), utile
  pour un delay leger en rythmique clean ou crunch.
- Le compresseur (FS5) est ON par defaut, a couper en high gain si desire.

---

## Les 4 sons - Guide rapide

| Son            | FS1 (Crunch) | FS2 (Metal) | FS3 (Solo) | FS4 (Cab) | Description                          |
|----------------|:---:|:---:|:---:|:---:|----------------------------------------------|
| Clean          | OFF | OFF | OFF | *   | Tele compressée, clean chaud et defini       |
| Crunch         | ON  | OFF | OFF | *   | Blues/rock, Klon qui pousse l'ampli          |
| Hard/Metal     | OFF | ON  | OFF | *   | Distortion serree et agressive               |
| Solo (clean)   | OFF | OFF | ON  | *   | Boost mid + delay + reverb sur son clean     |
| Solo (crunch)  | ON  | OFF | ON  | *   | Lead blues/rock avec ambiance                |
| Solo (metal)   | OFF | ON  | ON  | *   | Lead sature avec sustain et espace           |
| Full send      | ON  | ON  | ON  | *   | Klon > D9 > boost = sustain et presence max  |

* FS4 (Cab) : OFF = sortie FX Return ampli / ON = sortie casque
* Compresseur (FS5) : ON par defaut, couper en high gain si desire

---

## Notes

- Compresseur (FS5) : ON par defaut. Le couper en high gain si le son
  semble trop ecrase/sans dynamique. En clean et crunch, le laisser ON.
- Delay independant (FS6) : permet d'ajouter du delay en rythmique sans
  activer le boost solo (FS3). Utile en clean ou crunch.
- Le Placater Clean a ete choisi plutot qu'un modele Fender car il encaisse
  mieux les pedales de high gain tout en restant propre et musical en clean.
- DSP : Tous les blocs choisis sont legers en DSP. Le Placater est un ampli
  "eco", les overdrives et le compresseur sont simples. Pas de risque de
  depassement.
- Si tu remplaces la cab stock par une IR tierce, ajuste le low/high cut
  en fonction de l'IR choisie.
