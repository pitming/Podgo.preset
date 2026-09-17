# POD Go - 07B Edge Roots Pop Rock
# Cible : edge-of-breakup / roots / pop-rock organique live
# IR cible : York Audio KW 412 M25-SH - Mix JA 1

---

## Signal path complet

```text
Input > Wah > [1. Kinky Boost] > [2. 70s Chorus] > Essex A30 > Volume > FX Loop > [3. Simple Delay] > [4. Plate] > IR > EQ Param > Output
```

---

## Reglages detailles

### Bloc 1 - Kinky Boost
| Param | Valeur |
|-------|--------|
| Drive | 2.2 |
| Boost | ON |
| Bright | OFF |
| Etat par defaut | OFF |

### Bloc 2 - 70s Chorus
| Param | Valeur |
|-------|--------|
| Mode | Chorus |
| Chorus Rate | 1.8 |
| Vibrato Rate | 1.8 |
| Vibrato Depth | 0.0 |
| Spread | 5.8 |
| Stereo | True |
| Mix | 11% |
| Level | 0.0 dB |
| Headroom | 0.0 dB |
| Etat par defaut | OFF |

### Ampli - Essex A30
| Param | Valeur |
|-------|--------|
| Drive | 4.1 |
| Bass | 3.3 |
| Cut | 5.8 |
| Treble | 5.6 |
| Presence | 4.9 |
| Master | 7.8 |
| Ch Vol | 8.0 |
| Sag | 4.6 |
| Hum | 0.5 |
| Ripple | 1.0 |
| Bias | 5.0 |
| Bias X | 5.0 |
| Etat | TOUJOURS ON |

### Bloc 3 - Simple Delay
| Param | Valeur |
|-------|--------|
| Time | 360 ms |
| Scale | 100% |
| Feedback | 19% |
| Mix | 15% |
| Level | +1.0 dB |
| Trails | ON |
| Etat par defaut | OFF |

### Bloc 4 - Plate
| Param | Valeur |
|-------|--------|
| Decay | 1.7 s |
| Predelay | 14 ms |
| Low Cut | 145 Hz |
| High Cut | 5.2 kHz |
| Mix | 10% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | ON |

### IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix JA 1 |
| Mix | 100% |
| Low Cut | 90 Hz |
| High Cut | 6.7 kHz |
| Level | -18.0 dB |
| Etat par defaut | BYPASS |

### EQ Parametrique (bloc fixe - post IR)
| Param | Valeur |
|-------|--------|
| Low Cut | 90 Hz |
| Low Frq | 170 Hz |
| Low Q | 0.8 |
| Low Gain | -1.0 dB |
| Mid Frq | 1.7 kHz |
| Mid Q | 1.1 |
| Mid Gain | +2.8 dB |
| High Frq | 3.4 kHz |
| High Q | 0.9 |
| High Gain | +0.5 dB |
| High Cut | 6.6 kHz |
| Level | +2.0 dB |
| Etat par defaut | OFF |

### Pedale d'expression
| Assignation | Volume (post-amp, pre-delay/reverb) |
|-------------|--------------------------------------|
| Heel (min) | 0% |
| Toe (max) | 100% |

### Blocs fixes
| Bloc | Reglage | Etat par defaut |
|------|---------|------------------|
| Wah | EXP 1, plage 0-100% | BYPASS |
| Volume Pedal | EXP 2, Min 0%, Max 100% | ON |
| FX Loop | Send 0.0 dB, Return 0.0 dB, Mix 100%, Trails OFF | BYPASS |

---

## Configuration STOMP

| FS1 | FS2 | FS3 | FS4 | FS5 | FS6 |
|-----|-----|-----|-----|-----|-----|
| Kinky Boost | 70s Chorus | EQ Param + Simple Delay | Plate | Rien | IR casque |
| PUSH | WIDTH | SOLO | SPACE | LIBRE | IR |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | Description |
|-----|:---:|:---:|:---:|:---:|-------------|
| Base | OFF | OFF | OFF | ON | Edge-of-breakup simple, vivant et organique |
| Roots sec | OFF | OFF | OFF | OFF | Plus frontal, plus vintage, moins poli |
| Refrain pousse | ON | OFF | OFF | ON | Plus de corps et de grain sans tomber dans le vrai crunch |
| Pop large | OFF/ON | ON | OFF | ON | Plus de largeur pour refrains et arpeges pop-rock |
| Solo roots | ON | OFF | ON | ON/OFF | Lift medium propre, delay court et musical |

---

## Notes / justifications

- Preset principal pour `Have You Ever Seen The Rain`, `Here Comes Your Man`, `Ziggy Stardust`, `Valerie`, `Psycho Killer`, `Last Nite` et les morceaux qui demandent un ampli deja un peu pousse mais encore ouvert.
- L'`Essex A30` est utilise plus bas et plus simplement que dans `06B` pour garder le cote edge-of-breakup plutot qu'un vrai crunch indie.
- `Kinky Boost` sert ici de vrai push de refrain, pas de fondation permanente du son.
- Le `70s Chorus` reste optionnel et leger : il doit juste ouvrir le preset sur certains morceaux pop, pas donner une identite 80s trop marquee.
- Le solo type se joue avec `FS1 + FS3`, puis `FS4` selon que tu veux quelque chose de plus sec ou plus chantant.
- IR conseillee : `Mix JA 1`. Alternative rapide a tester : `Mix 07` si tu veux un peu plus d'attaque et un grain plus brut.
- L'IR reste en bypass vers le FX Return et ne s'active que pour le casque.
- A regler entre `06A` et `06B` en niveau percu : il doit paraitre plus vivant que `06A`, mais nettement moins dense et moins appuye que `06B`.
- Le compresseur a ete retire pour preserver le caractere organique et tenir dans quatre blocs libres sans sacrifier le push, la largeur, le solo ou l'ambiance.
- Les quatre blocs libres sont `Kinky Boost`, `70s Chorus`, `Simple Delay` et `Plate` : risque DSP faible.
