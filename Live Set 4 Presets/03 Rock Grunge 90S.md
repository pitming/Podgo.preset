# POD Go - Rock Grunge 90S
# Cible : alt-rock / grunge / hard rock 90s
# IR cible : York Audio KW 412 M25-SH - Mix 07

---

## Signal path complet

```text
Input > [1. DRIVE: Scream 808] > [2. MOD: 70s Chorus] > [3. DRIVE: Hedgehog D9] > [4. AMP: Placater Clean] > [5. DELAY: Simple Delay] > [6. REVERB: Glitz] > [7. IR: York Audio KW 412 M25-SH] > Output
                                                                                               |
                                                                                          [EQ Param] (bloc gratuit, post-IR)
                                                                                               |
                                                                                          [Pedale: Volume] (bloc gratuit)
```

---

## Reglages detailles

### Bloc 1 - Scream 808
| Param | Valeur |
|-------|--------|
| Gain | 3.8 |
| Tone | 5.6 |
| Level | 5.8 |
| Etat par defaut | ON |

### Bloc 2 - 70s Chorus
| Param | Valeur |
|-------|--------|
| Mode | Chorus |
| Chorus Rate | 2.3 |
| Spread | 5.5 |
| Stereo | True |
| Mix | 18% |
| Level | 0.0 dB |
| Headroom | 0.0 dB |
| Etat par defaut | OFF |

### Bloc 3 - Hedgehog D9
| Param | Valeur |
|-------|--------|
| Gain | 6.8 |
| Level | 4.3 |
| Tone | 4.3 |
| Etat par defaut | OFF |

### Bloc 4 - Placater Clean
| Param | Valeur |
|-------|--------|
| Drive | 4.2 |
| Bass | 3.8 |
| Treble | 6.2 |
| Presence | 6.0 |
| Master | 8.0 |
| Ch Vol | 7.6 |
| Bright | 1 |
| Sag | 5.0 |
| Ripple | 5.0 |
| Bias | 5.0 |
| Bias X | 5.0 |
| Etat | TOUJOURS ON |

### Bloc 5 - Simple Delay
| Param | Valeur |
|-------|--------|
| Time | 420 ms |
| Scale | 100% |
| Feedback | 22% |
| Mix | 17% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | OFF |

### Bloc 6 - Glitz
| Param | Valeur |
|-------|--------|
| Decay | 2.8 s |
| Delay | 35 ms |
| Predelay | 60 ms |
| Depth | 3.0 |
| Rate | 1.6 Hz |
| Modulation Mix | 2.5 |
| Xover | 900 Hz |
| Low Cut | 130 Hz |
| High Cut | 6.0 kHz |
| Mix | 16% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | ON |

### Bloc 7 - IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix 07 |
| Low Cut | 90 Hz |
| High Cut | 7.0 kHz |
| Level | 0.0 dB |
| Etat | TOUJOURS ON |

### EQ Parametrique (bloc gratuit - post IR)
| Param | Valeur |
|-------|--------|
| Low Cut | 85 Hz |
| Low Freq | 130 Hz |
| Low Q | 0.9 |
| Low Gain | -1.0 dB |
| Mid Freq | 1.4 kHz |
| Mid Q | 1.1 |
| Mid Gain | +2.5 dB |
| High Freq | 3.6 kHz |
| High Q | 1.0 |
| High Gain | +0.8 dB |
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
| Scream 808 | 70s Chorus | Hedgehog D9 | EQ Param + Simple Delay | Glitz | Rien |
| DRIVE | CHORUS | D9 | SOLO | VERB | LIBRE |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Base | ON | OFF | OFF | OFF | ON | Rock 90s dense |
| Grunge chorus | ON | ON | OFF | OFF | ON | Pour `Come As You Are` / `TMWSTW` |
| Hard rock large | ON | OFF | ON | OFF | ON | Plus d'attaque et d'epaisseur |
| Solo | ON | OFF/ON | OFF/ON | ON | ON | Mode lead avec projection |
| Dry punch | ON | OFF | OFF | OFF | OFF | Plus sec et frontal |

---

## Notes / justifications

- Preset principal pour `Come As You Are`, `The Man Who Sold The World`, `Black Hole Sun`, `Seven Nation Army`, `Bitch`, `Teenage Dirtbag`, `Only Happy When It Rains`, `Zombie`, `Creep`, `Noir Desir`, `All Apologies`, `Fight For Your Right`.
- Le `Placater Clean` sert ici de plate-forme qui accepte bien l'`808` et la `D9`.
- Le chorus est reserve aux morceaux qui en ont vraiment besoin pour ne pas diluer le riff rock.
- IR conseillee : `Mix 07`. Alternative rapide a tester : `Mix JA 1` si tu veux plus de medium live et moins de grain brut.
- La `Glitz` est volontairement plus courte que dans un preset ambient, juste assez pour donner de la taille.
- Volume rebaisse pour rester proche de `01 Clean Jangle 90S` malgre plus de gain percu.
