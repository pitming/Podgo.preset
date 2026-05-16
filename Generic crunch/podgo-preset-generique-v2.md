# POD Go - Preset Generique V2
# Valeurs relevees depuis `Generic.pgp`
# Telecaster Standard Mex - Micro Fender Vintage '64

---

## Signal Path reel

```text
Input (Noise Gate ON) > [Pedale: WAH Fassel] > [1. COMP: LA Studio Comp] > [2. DRIVE: Scream 808] > [3. DIST: Hedgehog D9] > [4. AMP: Placater Clean] > [5. DELAY: Simple Delay] > [6. REVERB: Glitz] > [7. CAB: 4x12 Cali V30] > [EQ Param] > [Gain] > Output
```

Note : `Generic.pgp` contient aussi un Wah avant les blocs principaux et un bloc `Gain` fixe apres l'EQ.

---

## Reglages detailles

### Pedale d'expression - Wah Fassel Stereo
| Param           | Valeur |
|-----------------|--------|
| Fc Low          | 455 Hz |
| Fc High         | 2155 Hz|
| Level           | 0.0 dB |
| Mix             | 100%   |
| Pedal           | 100%   |
| Etat par defaut | OFF    |

Note : la pedale d'expression est assignee au Wah dans `Generic.pgp`, pas a un volume pedal.

### Bloc 1 - LA Studio Comp
| Param           | Valeur   |
|-----------------|----------|
| Peak Reduction  | 2.5      |
| Gain            | 4.5      |
| Level           | 0.0 dB   |
| Mix             | 50%      |
| Emphasis        | 1.0      |
| Type            | Compress |
| Etat par defaut | OFF      |

### Bloc 2 - Scream 808
| Param           | Valeur |
|-----------------|--------|
| Gain            | 4.0    |
| Tone            | 5.8    |
| Level           | 7.0    |
| Etat par defaut | ON     |

### Bloc 3 - Hedgehog D9
| Param           | Valeur |
|-----------------|--------|
| Gain            | 7.5    |
| Tone            | 4.5    |
| Level           | 5.0    |
| Etat par defaut | OFF    |

### Bloc 4 - Placater Clean
| Param           | Valeur |
|-----------------|--------|
| Drive           | 3.5    |
| Bass            | 4.0    |
| Treble          | 7.5    |
| Presence        | 7.0    |
| Master          | 8.0    |
| Ch Vol          | 9.0    |
| Bright          | 2      |
| Sag             | 5.0    |
| Ripple          | 5.0    |
| Bias            | 5.0    |
| Bias X          | 5.0    |
| Etat            | TOUJOURS ON |

Note : ce bloc suit les parametres confirmes de `Placater Clean` sur POD Go.

### Bloc 5 - Simple Delay
| Param           | Valeur |
|-----------------|--------|
| Time            | 400 ms |
| Scale           | 75%    |
| Feedback        | 25%    |
| Mix             | 25%    |
| Level           | 0.0 dB |
| Trails          | OFF    |
| Tempo Sync      | OFF    |
| Etat par defaut | OFF    |

### Bloc 6 - Glitz
| Param           | Valeur |
|-----------------|--------|
| Decay           | 3.0 s  |
| Delay           | 44 ms  |
| Predelay        | 80 ms  |
| Depth           | 3.8    |
| Rate            | 1.8 Hz |
| Modulation Mix  | 3.5    |
| Xover           | 866 Hz |
| Low Cut         | 118 Hz |
| High Cut        | 8.0 kHz|
| Mix             | 20%    |
| Level           | 0.0 dB |
| Trails          | OFF    |
| Etat par defaut | ON     |

### Bloc 7 - Cab: 4x12 Cali V30
| Param           | Valeur     |
|-----------------|------------|
| Mic             | 57 Dynamic |
| Distance        | 2.0        |
| Position        | 23%        |
| Angle           | 0.0        |
| Low Cut         | 80 Hz      |
| High Cut        | 8.0 kHz    |
| Level           | 0.0 dB     |
| Etat par defaut | OFF        |

### EQ Parametrique
| Param           | Valeur     |
|-----------------|------------|
| Low Cut         | 19.9 Hz    |
| Low Freq        | 100 Hz     |
| Low Gain        | +2.0 dB    |
| Low Q           | 0.707      |
| Mid Freq        | 805 Hz     |
| Mid Gain        | +3.5 dB    |
| Mid Q           | 2.0        |
| High Freq       | 3.2 kHz    |
| High Gain       | +1.0 dB    |
| High Q          | 1.0        |
| High Cut        | 20.1 kHz   |
| Level           | +3.0 dB    |
| Etat par defaut | OFF        |

### Bloc utilitaire - Gain
| Param           | Valeur |
|-----------------|--------|
| Gain            | 0.0 dB |
| Etat par defaut | ON     |

### Input / Output
| Section | Param        | Valeur |
|---------|--------------|--------|
| Input   | Noise Gate   | ON     |
| Input   | Threshold    | -48 dB |
| Input   | Decay        | 5.0    |
| Output  | Gain         | +6.4 dB|
| Output  | Pan          | 50%    |

---

## Configuration STOMP relevee dans `Generic.pgp`

Le fichier contient des indexes internes POD Go. Je les laisse tels quels pour ne pas deviner une correspondance physique incorrecte.

| Index interne | Bloc(s)              | Label lu dans le fichier | Etat par defaut |
|---------------|----------------------|--------------------------|-----------------|
| 1             | Scream 808           | Scream 808               | ON              |
| 2             | Hedgehog D9          | Hedgehog D9              | OFF             |
| 4             | Simple Delay + EQ    | solo                     | OFF             |
| 5             | Glitz                | Glitz                    | ON              |
| 6             | LA Studio Comp       | LA Studio Comp           | OFF             |
| 9             | Wah Fassel           | Fassel                   | OFF             |

Notes :
- L'index `4` est une multi-assignation qui active `Simple Delay` + `EQ Parametrique`.
- Le bloc `Cab` n'a pas d'assignation footswitch dans `Generic.pgp`.
- Le Wah apparait sur l'index `9`, probablement lie au toe switch.

---

## Guide des sons

| Son                | 808 | D9  | Solo | Glitz | Description |
|--------------------|:---:|:---:|:----:|:-----:|-------------|
| Son de base        | ON  | OFF | OFF  | ON    | Crunch/edge-of-breakup principal du preset |
| Clean plus sec     | OFF | OFF | OFF  | ON    | Son plus propre, toujours avec la Glitz active |
| Hard rock          | ON  | ON  | OFF  | ON    | Scream 808 pousse la D9 dans l'ampli |
| Solo crunch        | ON  | OFF | ON   | ON    | Boost mid + delay pour sortir dans le mix |
| Solo hard rock     | ON  | ON  | ON   | ON    | Version la plus dense du preset |

---

## Notes

- Cette version du Markdown colle aux valeurs de `Generic.pgp`, meme quand elles different du document precedent.
- Changement majeur : le drive principal est `Scream 808`, pas `Minotaur`.
- Changement majeur : `LA Studio Comp` est `OFF` par defaut.
- Changement majeur : `Glitz` est `ON` par defaut.
- Changement majeur : le bloc `Cab` est bien present mais n'est pas assigne a un footswitch dans le fichier.
