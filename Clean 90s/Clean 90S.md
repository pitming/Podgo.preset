# POD Go - Clean 90S
# Inspiration : Thorn (Natalie Imbruglia)
# Telecaster Standard Mex - Micro Fender Vintage '64

---

## Signal Path (7 blocs + EQ param gratuit + pedale expression)

```
Input > [1. COMP: LA Studio Comp] > [2. DRIVE: Kinky Boost] > [3. MOD: 70s Chorus] > [4. AMP: US Deluxe Nrm] > [5. DELAY: Simple Delay] > [6. REVERB: Plate] > [7. CAB: 2x12 Double C12N] > Output
                                                                                        |
                                                                                   [EQ Param] (bloc gratuit, post-amp)
                                                                                        |
                                                                                   [Pedale: Volume] (bloc gratuit)
```

---

## Reglages detailles

### Bloc 1 - LA Studio Comp
| Param           | Valeur   |
|-----------------|----------|
| Peak Reduction  | 2.8      |
| Gain            | 4.6      |
| Type            | Compress |
| Mix             | 58%      |
| Etat par defaut | ON       |

Role : base du son. Compression moderee pour lisser les attaques sans trop ecraser
la dynamique en contexte groupe.

### Bloc 2 - Kinky Boost
| Param           | Valeur |
|-----------------|--------|
| Drive           | 3.8    |
| Boost           | ON     |
| Bright          | ON     |
| Etat par defaut | OFF    |

Role : pousse legerement le haut-medium et le niveau percu pour les refrains,
sans salir les accords ouverts.

### Bloc 3 - 70s Chorus
| Param           | Valeur |
|-----------------|--------|
| Mode            | Chorus |
| Chorus Rate     | 3.0    |
| Spread          | 6.0    |
| Stereo          | True   |
| Mix             | 16%    |
| Level           | 0.0 dB |
| Headroom        | 0.0 dB |
| Etat par defaut | ON     |

Role : largeur discrete et tres controlee. Le mix est volontairement plus bas pour
garder une guitare lisible en groupe.

### Bloc 4 - US Deluxe Nrm
| Param           | Valeur |
|-----------------|--------|
| Drive           | 3.1    |
| Bass            | 3.4    |
| Mid             | 5.6    |
| Treble          | 6.1    |
| Presence        | 5.5    |
| Master          | 8.0    |
| Channel Vol     | 9.0    |
| Sag             | 4.2    |
| Hum             | 0.8    |
| Ripple          | 1.0    |
| Bias            | 5.3    |
| Bias X          | 5.0    |
| Etat            | TOUJOURS ON |

Role : clean Fender stable, mais recentre pour le live. Un peu moins de grave et un
peu plus de mediums pour mieux passer avec basse, batterie et deuxieme guitare.

### Bloc 5 - Simple Delay
| Param           | Valeur |
|-----------------|--------|
| Time            | 320 ms |
| Scale           | 100%   |
| Feedback        | 15%    |
| Mix             | 12%    |
| Level           | 0.0 dB |
| Trails          | ON     |
| Etat par defaut | OFF    |

Role : ambience courte et discrete pour les intros ou arpges. Niveau reduit pour ne
pas prendre de place dans le mix live.

### Bloc 6 - Plate
| Param           | Valeur |
|-----------------|--------|
| Decay           | 2.2 s  |
| Predelay        | 20 ms  |
| Low Cut         | 140 Hz |
| High Cut        | 5.2 kHz|
| Mix             | 14%    |
| Level           | 0.0 dB |
| Etat par defaut | ON     |

Role : reverb plus courte et plus seche pour garder l'assise rythmique nette sur scene.

### Bloc 7 - Cab: 2x12 Double C12N
| Param           | Valeur      |
|-----------------|-------------|
| Mic             | 121 Ribbon  |
| Distance        | 3.0         |
| Low Cut         | 90 Hz       |
| High Cut        | 6.8 kHz     |
| Early Reflections | 12%       |
| Level           | 0.0 dB      |
| Etat par defaut | OFF         |

Role : option casque. Le 121 evite l'agressivite du haut du spectre et garde un clean
plus disque que la sortie ampli seule. Le preset reste toutefois regle d'abord pour le live via FX Return.

### EQ Parametrique (bloc gratuit - post amp)
| Param           | Valeur    |
|-----------------|-----------|
| Low Cut         | 80 Hz     |
| Low Freq        | 120 Hz    |
| Low Q           | 0.8       |
| Low Gain        | -2.0 dB   |
| Mid Freq        | 1.8 kHz   |
| Mid Q           | 1.4       |
| Mid Gain        | +2.8 dB   |
| High Freq       | 3.8 kHz   |
| High Q          | 1.0       |
| High Gain       | +0.8 dB   |
| High Cut        | 7.2 kHz   |
| Level           | +2.0 dB   |
| Etat par defaut | OFF       |

Role : mode "mix cut" clairement pense groupe. Il coupe un peu plus le bas et pousse
les hauts mediums qui percent sans rendre le son agressif.

### Pedale d'expression
| Assignation     | Volume (post-amp, pre-delay/reverb) |
|-----------------|--------------------------------------|
| Heel (min)      | 0%                                   |
| Toe (max)       | 100%                                 |

Note : pratique pour des entrees de couplet propres sans changer les reglages du preset.

### Input / Output
| Section | Param      | Valeur  |
|---------|------------|---------|
| Output  | Gain       | +6.4 dB |
| Output  | Pan        | 50%     |

Note : niveau de sortie aligne sur le preset `Generic` pour eviter un ecart trop important en changement de preset.

---

## Configuration STOMP (6 Footswitches en mode STOMP)

| FS1                   | FS2                  | FS3                  | FS4               | FS5                 | FS6               |
|-----------------------|----------------------|----------------------|-------------------|---------------------|-------------------|
| Kinky Boost (Bloc 2)  | 70s Chorus (Bloc 3)  | EQ Param             | Cab 2x12 (Bloc 7) | Simple Delay (Bloc 5) | Plate (Bloc 6)   |
| REFRAIN PUSH ON/OFF   | CHORUS ON/OFF        | MIX CUT ON/OFF       | CAB SIM ON/OFF    | AIR ON/OFF            | ROOM ON/OFF      |

Lecture pratique :
- FS1 ajoute un leger edge-of-breakup et surtout plus de presence utile.
- FS2 coupe la largeur 90s si tu veux un clean encore plus sec et plus focalise.
- FS3 est le vrai bouton live pour sortir du mix au bon moment.
- FS4 active la simulation de cab pour casque uniquement.
- FS5 ajoute l'espace court du delay pour intros/arpges.
- FS6 permet de secher encore le preset si la piece ou l'ampli ajoutent deja assez d'ambiance.

---

## Guide des sons

| Son                      | FS1 Push | FS2 Chorus | FS3 Mix Cut | FS4 Cab | FS5 Delay | FS6 Reverb | Description |
|--------------------------|:--------:|:----------:|:-----------:|:-------:|:---------:|:----------:|-------------|
| Clean 90S de base        | OFF      | ON         | OFF         | *       | OFF       | ON         | Clean pop brillant, serre et deja pense pour le groupe |
| Couplet sec              | OFF      | OFF        | OFF         | *       | OFF       | ON         | Plus direct, plus sec, tres lisible dans le mix |
| Intro / arpges aeriens   | OFF      | ON         | OFF         | *       | ON        | ON         | Plus d'espace, sans perdre la definition des attaques |
| Refrain plus pousse      | ON       | ON         | OFF         | *       | OFF       | ON         | Un peu plus de densite et de projection |
| Refrain qui perce le mix | ON/OFF   | ON         | ON          | *       | OFF/ON    | ON         | Presence plus marquee, mode groupe prioritaire |
| Casque / travail solo    | OFF      | ON         | OFF         | ON      | OFF       | ON         | Version optimisee pour ecoute directe au casque |

* FS4 (Cab) : OFF = sortie FX Return ampli / ON = sortie casque

---

## Notes / justifications

- Le preset reste inspire de "Thorn", mais la priorite a ete de le faire fonctionner en live de groupe plutot qu'en solo dans une piece.
- Le Kinky Boost a ete prefere a une overdrive plus marquee pour garder le cote pop et les accords ouverts.
- Le chorus est volontairement plus discret que dans une approche studio pour ne pas elargir excessivement la guitare sur scene.
- L'EQ param fait le travail de presence live sans ajouter de saturation ni multiplier les blocs DSP.
- Le niveau de sortie a ete remonte pour se rapprocher du `Generic`, avec `Channel Vol` a `9.0` et `Output Gain` a `+6.4 dB`.
- DSP : configuration legere a moderee. Pas de risque particulier de depassement sur POD Go avec ces modeles.
