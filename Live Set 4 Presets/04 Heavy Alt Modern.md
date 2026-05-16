# POD Go - Heavy Alt Modern
# Cible : hard rock moderne / riff lourd / lead dense
# IR cible : York Audio KW 412 M25-SH - Mix JA 2

---

## Signal path complet

```text
Input > [1. DRIVE: Scream 808] > [2. DRIVE: Hedgehog D9] > [3. MOD: 70s Chorus] > [4. AMP: Placater Dirty] > [5. DELAY: Simple Delay] > [6. REVERB: Plate] > [7. IR: York Audio KW 412 M25-SH] > Output
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
| Gain | 2.6 |
| Tone | 5.4 |
| Level | 5.8 |
| Etat par defaut | ON |

### Bloc 2 - Hedgehog D9
| Param | Valeur |
|-------|--------|
| Gain | 7.2 |
| Level | 4.2 |
| Tone | 4.2 |
| Etat par defaut | OFF |

### Bloc 3 - 70s Chorus
| Param | Valeur |
|-------|--------|
| Mode | Chorus |
| Chorus Rate | 2.0 |
| Spread | 4.8 |
| Stereo | True |
| Mix | 12% |
| Level | 0.0 dB |
| Headroom | 0.0 dB |
| Etat par defaut | OFF |

### Bloc 4 - Placater Dirty
| Param | Valeur |
|-------|--------|
| Drive | 5.6 |
| Bass | 3.6 |
| Mid | 5.7 |
| Treble | 6.0 |
| Presence | 5.8 |
| Master | 7.8 |
| Ch Vol | 7.3 |
| Sag | 4.8 |
| Ripple | 1.2 |
| Bias | 5.0 |
| Bias X | 5.0 |
| HBE | OFF |
| Fat | OFF |
| C45 | ON |
| Saturation | OFF |
| Etat | TOUJOURS ON |

### Bloc 5 - Simple Delay
| Param | Valeur |
|-------|--------|
| Time | 430 ms |
| Scale | 100% |
| Feedback | 20% |
| Mix | 15% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | OFF |

### Bloc 6 - Plate
| Param | Valeur |
|-------|--------|
| Decay | 1.8 s |
| Predelay | 18 ms |
| Low Cut | 150 Hz |
| High Cut | 5.5 kHz |
| Mix | 11% |
| Level | 0.0 dB |
| Etat par defaut | ON |

### Bloc 7 - IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix JA 2 |
| Low Cut | 95 Hz |
| High Cut | 6.8 kHz |
| Level | 0.0 dB |
| Etat | TOUJOURS ON |

### EQ Parametrique (bloc gratuit - post IR)
| Param | Valeur |
|-------|--------|
| Low Cut | 90 Hz |
| Low Freq | 120 Hz |
| Low Q | 0.9 |
| Low Gain | -2.0 dB |
| Mid Freq | 1.5 kHz |
| Mid Q | 1.3 |
| Mid Gain | +3.0 dB |
| High Freq | 3.5 kHz |
| High Q | 1.0 |
| High Gain | +0.8 dB |
| High Cut | 6.8 kHz |
| Level | +1.3 dB |
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
| Scream 808 | Hedgehog D9 | 70s Chorus | EQ Param + Simple Delay | Plate | Rien |
| TIGHT | HEAVY | CHORUS | SOLO | ROOM | LIBRE |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Base | ON | OFF | OFF | OFF | ON | Hard rock moderne serre |
| Heavy | ON | ON | OFF | OFF | ON | Riff lourd et plus compresse |
| Lead | ON | ON | OFF | ON | ON | Lead plus present |
| Large | ON | OFF | ON | OFF | ON | Variante plus large pour certains refrains |
| Dry heavy | ON | ON | OFF | OFF | OFF | Plus sec et agressif |

---

## Notes / justifications

- Preset principal pour `Animal I Have Become`, `Slither`, `Song 2`, `I Wanna Be Your Dog`, `Rockin' In The Free World`, `Learn To Fly`, `Celebrity Skin` si plus lourd, `Personal Jesus` version massive.
- Le `Placater Dirty` donne plus de marge que le preset grunge quand il faut du vrai poids moderne.
- L'`808` sert a serrer le bas, la `D9` n'est ajoutee que pour les morceaux les plus lourds.
- IR conseillee : `Mix JA 2`. Alternative rapide a tester : `Mix JA 3` si tu veux encore plus de densite.
- Volume fortement rebaisse pour que `01 Clean Jangle 90S` reste la reference commune.
