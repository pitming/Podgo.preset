# POD Go - Clean Jangle 90S
# Cible : clean pop / folk-rock / 90s live
# IR cible : York Audio KW 412 M25-SH - Mix 01

---

## Signal path complet

```text
Input > [1. COMP: LA Studio Comp] > [2. DRIVE: Kinky Boost] > [3. MOD: 70s Chorus] > [4. AMP: US Deluxe Nrm] > [5. DELAY: Simple Delay] > [6. REVERB: Plate] > [7. IR: York Audio KW 412 M25-SH] > Output
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
| Peak Reduction | 2.6 |
| Gain | 4.6 |
| Type | Compress |
| Mix | 58% |
| Etat par defaut | ON |

### Bloc 2 - Kinky Boost
| Param | Valeur |
|-------|--------|
| Drive | 3.4 |
| Boost | ON |
| Bright | ON |
| Etat par defaut | OFF |

### Bloc 3 - 70s Chorus
| Param | Valeur |
|-------|--------|
| Mode | Chorus |
| Chorus Rate | 2.8 |
| Spread | 6.2 |
| Stereo | True |
| Mix | 15% |
| Level | 0.0 dB |
| Headroom | 0.0 dB |
| Etat par defaut | ON |

### Bloc 4 - US Deluxe Nrm
| Param | Valeur |
|-------|--------|
| Drive | 3.2 |
| Bass | 3.5 |
| Mid | 5.5 |
| Treble | 6.2 |
| Presence | 5.6 |
| Master | 8.0 |
| Channel Vol | 9.0 |
| Sag | 4.5 |
| Hum | 0.8 |
| Ripple | 1.0 |
| Bias | 5.3 |
| Bias X | 5.0 |
| Etat | TOUJOURS ON |

### Bloc 5 - Simple Delay
| Param | Valeur |
|-------|--------|
| Time | 320 ms |
| Scale | 100% |
| Feedback | 16% |
| Mix | 12% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | OFF |

### Bloc 6 - Plate
| Param | Valeur |
|-------|--------|
| Decay | 2.2 s |
| Predelay | 20 ms |
| Low Cut | 140 Hz |
| High Cut | 5.5 kHz |
| Mix | 15% |
| Level | 0.0 dB |
| Etat par defaut | ON |

### Bloc 7 - IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix 01 |
| Low Cut | 85 Hz |
| High Cut | 7.2 kHz |
| Level | 0.0 dB |
| Etat | TOUJOURS ON |

### EQ Parametrique (bloc gratuit - post IR)
| Param | Valeur |
|-------|--------|
| Low Cut | 80 Hz |
| Low Freq | 120 Hz |
| Low Q | 0.8 |
| Low Gain | -1.5 dB |
| Mid Freq | 1.8 kHz |
| Mid Q | 1.4 |
| Mid Gain | +2.8 dB |
| High Freq | 3.8 kHz |
| High Q | 1.0 |
| High Gain | +0.8 dB |
| High Cut | 7.2 kHz |
| Level | +2.0 dB |
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
| Kinky Boost | 70s Chorus | EQ Param | Simple Delay | Plate | LA Studio Comp |
| PUSH | CHORUS | MIX CUT | AIR | ROOM | COMP |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | FS6 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|:---:|-------------|
| Base | OFF | ON | OFF | OFF | ON | ON | Clean pop large et lisible |
| Couplet sec | OFF | OFF | OFF | OFF | ON | ON | Clean plus direct |
| Arpeges ouverts | OFF | ON | OFF | ON | ON | ON | Plus d'air sans laver le jeu |
| Refrain qui sort | ON | ON | ON | OFF | ON | ON | Push + haut-medium live |
| Clean roots | ON | OFF | OFF | OFF | OFF | ON | Plus simple et plus roots |

---

## Notes / justifications

- Preset principal pour `Save Tonight`, `Mr. Jones`, `Have You Ever Seen The Rain`, `Torn`, `Dreams`, `Island In The Sun`, `Kiss Me`, `Big Me`, `This Is The Life`, `Starman`.
- Le `US Deluxe Nrm` garde l'attaque Tele tout en restant stable en groupe.
- L'IR `KW 412 M25-SH` apporte plus de medium vocal qu'une 2x12 Fender stock, ce qui aide a exister dans le mix.
- IR conseillee : `Mix 01`. Alternative rapide a tester : `Mix 03` si tu veux un peu plus de presence.
- Le `70s Chorus` est regle tres bas : il doit elargir, pas laver.
