# POD Go - Crunch Indie Vox
# Cible : crunch pop-rock / indie / garage melodique
# IR cible : York Audio KW 412 M25-SH - Mix JA 1

---

## Signal path complet

```text
Input > [1. COMP: LA Studio Comp] > [2. DRIVE: Kinky Boost] > [3. DRIVE: Minotaur] > [4. AMP: Essex A30] > [5. DELAY: Simple Delay] > [6. REVERB: Plate] > [7. IR: York Audio KW 412 M25-SH] > Output
                                                                                             |
                                                                                        [EQ Param] (bloc gratuit, post-IR)
                                                                                             |
                                                                                        [Pedale: Volume] (bloc gratuit)
```

---

## Reglages detailles

### Bloc 1 - LA Studio Comp
| Param | Valeur |
|-------|--------|
| Peak Reduction | 2.2 |
| Gain | 4.2 |
| Type | Compress |
| Mix | 42% |
| Etat par defaut | OFF |

### Bloc 2 - Kinky Boost
| Param | Valeur |
|-------|--------|
| Drive | 3.2 |
| Boost | ON |
| Bright | ON |
| Etat par defaut | ON |

### Bloc 3 - Minotaur
| Param | Valeur |
|-------|--------|
| Gain | 2.6 |
| Tone | 5.4 |
| Level | 5.6 |
| Etat par defaut | OFF |

### Bloc 4 - Essex A30
| Param | Valeur |
|-------|--------|
| Drive | 4.1 |
| Bass | 3.2 |
| Cut | 5.0 |
| Treble | 6.0 |
| Presence | 5.8 |
| Master | 8.0 |
| Ch Vol | 7.8 |
| Sag | 4.7 |
| Hum | 0.5 |
| Ripple | 1.0 |
| Bias | 5.0 |
| Bias X | 5.0 |
| Etat | TOUJOURS ON |

### Bloc 5 - Simple Delay
| Param | Valeur |
|-------|--------|
| Time | 360 ms |
| Scale | 100% |
| Feedback | 18% |
| Mix | 13% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | OFF |

### Bloc 6 - Plate
| Param | Valeur |
|-------|--------|
| Decay | 1.9 s |
| Predelay | 18 ms |
| Low Cut | 150 Hz |
| High Cut | 5.0 kHz |
| Mix | 12% |
| Level | 0.0 dB |
| Etat par defaut | ON |

### Bloc 7 - IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix JA 1 |
| Low Cut | 90 Hz |
| High Cut | 7.0 kHz |
| Level | 0.0 dB |
| Etat | TOUJOURS ON |

### EQ Parametrique (bloc gratuit - post IR)
| Param | Valeur |
|-------|--------|
| Low Cut | 90 Hz |
| Low Freq | 140 Hz |
| Low Q | 0.9 |
| Low Gain | -1.8 dB |
| Mid Freq | 1.6 kHz |
| Mid Q | 1.3 |
| Mid Gain | +2.5 dB |
| High Freq | 3.4 kHz |
| High Q | 1.0 |
| High Gain | +0.6 dB |
| High Cut | 7.0 kHz |
| Level | +1.2 dB |
| Etat par defaut | OFF |

### Pedale d'expression
| Assignation | Volume (post-amp, pre-delay/reverb) |
|-------------|--------------------------------------|
| Heel (min) | 0% |
| Toe (max) | 100% |

---

## Configuration STOMP

| FS1 | FS2 | FS3 | FS4 | FS5 | FS6 |
|-----|-----|-----|-----|-----|-----|
| Kinky Boost | Minotaur | EQ Param + Simple Delay | Plate | LA Studio Comp | Rien |
| BASE EDGE | GAIN+ | SOLO | ROOM | COMP | LIBRE |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Base | ON | OFF | OFF | ON | OFF | Crunch indie vivant |
| Rythmique plus seche | ON | OFF | OFF | OFF | OFF | Plus frontal |
| Refrain dense | ON | ON | OFF | ON | OFF | Crunch plus epais |
| Solo indie | ON | OFF | ON | ON | OFF | Delay + EQ pour sortir |
| Garage plus compresse | ON | OFF | OFF | ON | ON | Plus plaque et serre |

---

## Notes / justifications

- Preset principal pour `Take Me Out`, `Lonely Boy`, `Here Comes Your Man`, `My Favorite Game`, `Rock & Roll Queen`, `Valerie`, `Psycho Killer`, `The Middle`, `Today`, `Celebrity Skin`.
- L'`Essex A30` donne le mordant haut-medium utile pour l'indie sans monter trop en gain.
- `Kinky Boost` reste la base edge-of-breakup, `Minotaur` sert de deuxieme etage pour les refrains ou riffs plus epais.
- IR conseillee : `Mix JA 1`. Alternative rapide a tester : `Mix 07` si tu veux plus d'attaque ou un registre plus garage.
- Volume rebaisse pour s'aligner sur `01 Clean Jangle 90S`, qui reste la reference de balance.
