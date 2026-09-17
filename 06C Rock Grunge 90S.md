# POD Go - 06C Rock Grunge 90S
# Cible : alt-rock / grunge / hard rock 90s
# IR cible : York Audio KW 412 M25-SH - Mix 07

---

## Signal path complet

```text
Input > Wah > [1. Scream 808] > [2. 70s Chorus] > [3. Hedgehog D9] > Placater Clean > Volume > FX Loop > [4. Simple Delay] > IR > EQ Param > Output
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
| Vibrato Rate | 2.3 |
| Vibrato Depth | 0.0 |
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

### Ampli - Placater Clean
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

### Bloc 4 - Simple Delay
| Param | Valeur |
|-------|--------|
| Time | 420 ms |
| Scale | 100% |
| Feedback | 22% |
| Mix | 17% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | OFF |

### IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix 07 |
| Mix | 100% |
| Low Cut | 90 Hz |
| High Cut | 7.0 kHz |
| Level | -18.0 dB |
| Etat par defaut | BYPASS |

### EQ Parametrique (bloc fixe - post IR)
| Param | Valeur |
|-------|--------|
| Low Cut | 90 Hz |
| Low Freq | 140 Hz |
| Low Q | 0.9 |
| Low Gain | -1.5 dB |
| Mid Freq | 1.7 kHz |
| Mid Q | 1.0 |
| Mid Gain | +4.0 dB |
| High Freq | 3.8 kHz |
| High Q | 1.0 |
| High Gain | +1.2 dB |
| High Cut | 6.8 kHz |
| Level | +2.5 dB |
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
| Scream 808 | 70s Chorus | Hedgehog D9 | EQ Param + Simple Delay | Rien | IR casque |
| DRIVE | CHORUS | D9 | SOLO | LIBRE | IR |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | Description |
|-----|:---:|:---:|:---:|:---:|-------------|
| Base | ON | OFF | OFF | OFF | Rock 90s dense et sec |
| Grunge chorus | ON | ON | OFF | OFF | Pour `Come As You Are` / `TMWSTW` |
| Hard rock large | ON | OFF | ON | OFF | Plus d'attaque et d'epaisseur |
| Solo | ON | OFF/ON | OFF/ON | ON | Mode lead avec projection |

---

## Notes / justifications

- Preset principal pour `Come As You Are`, `The Man Who Sold The World`, `Black Hole Sun`, `Seven Nation Army`, `Bitch`, `Teenage Dirtbag`, `Only Happy When It Rains`, `Zombie`, `Creep`, `Noir Desir`, `All Apologies`, `Fight For Your Right`.
- Le `Placater Clean` sert ici de plate-forme qui accepte bien l'`808` et la `D9`.
- Le chorus est reserve aux morceaux qui en ont vraiment besoin pour ne pas diluer le riff rock.
- IR conseillee : `Mix 07`. Alternative rapide a tester : `Mix JA 1` si tu veux plus de medium live et moins de grain brut.
- L'IR reste en bypass vers le FX Return et ne s'active que pour le casque.
- L'EQ solo est volontairement plus affirmatif ici pour que `FS4` se percoive aussi hors contexte groupe, sans ajouter trop de fizz.
- Volume rebaisse pour rester proche de `06A Clean Jangle 90S` malgre plus de gain percu.
- La `Glitz` a ete retiree pour respecter quatre blocs libres. Ce preset reste volontairement sec ; le delay est conserve car il est plus utile aux leads.
- Les quatre blocs libres sont `Scream 808`, `70s Chorus`, `Hedgehog D9` et `Simple Delay`. DSP soutenu mais compatible POD Go ; verifier apres chargement du preset.
