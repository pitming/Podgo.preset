# POD Go - 07A Clear Ether Clean
# Cible : clean tres clair / ouvert / solo ethere live
# IR cible : York Audio KW 412 M25-SH - Mix 03

---

## Signal path complet

```text
Input > Wah > [1. LA Studio Comp] > [2. 70s Chorus] > Placater Clean > Volume > FX Loop > [3. Simple Delay] > [4. Glitz] > IR > EQ Param > Output
```

---

## Reglages detailles

### Bloc 1 - LA Studio Comp
| Param | Valeur |
|-------|--------|
| Peak Reduction | 2.8 |
| Gain | 4.5 |
| Type | Compress |
| Mix | 60% |
| Etat par defaut | ON |

### Bloc 2 - 70s Chorus
| Param | Valeur |
|-------|--------|
| Mode | Chorus |
| Chorus Rate | 1.9 |
| Vibrato Rate | 1.9 |
| Vibrato Depth | 0.0 |
| Spread | 6.8 |
| Stereo | True |
| Mix | 14% |
| Level | 0.0 dB |
| Headroom | 0.0 dB |
| Etat par defaut | OFF |

### Ampli - Placater Clean
| Param | Valeur |
|-------|--------|
| Drive | 2.8 |
| Bass | 3.4 |
| Treble | 6.5 |
| Presence | 5.4 |
| Master | 8.2 |
| Ch Vol | 8.6 |
| Bright | 1 |
| Sag | 4.2 |
| Ripple | 1.0 |
| Bias | 5.2 |
| Bias X | 5.0 |
| Etat | TOUJOURS ON |

### Bloc 3 - Simple Delay
| Param | Valeur |
|-------|--------|
| Time | 430 ms |
| Scale | 100% |
| Feedback | 24% |
| Mix | 19% |
| Level | +1.0 dB |
| Trails | ON |
| Etat par defaut | OFF |

### Bloc 4 - Glitz
| Param | Valeur |
|-------|--------|
| Decay | 3.8 s |
| Predelay | 24 ms |
| Depth | 2.4 |
| Rate | 1.3 Hz |
| Modulation Mix | 2.2 |
| Xover | 1.2 kHz |
| Low Cut | 150 Hz |
| High Cut | 6.8 kHz |
| Mix | 14% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | OFF |

### IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix 03 |
| Mix | 100% |
| Low Cut | 85 Hz |
| High Cut | 7.4 kHz |
| Level | -18.0 dB |
| Etat par defaut | BYPASS |

### EQ Parametrique (bloc fixe - post IR)
| Param | Valeur |
|-------|--------|
| Low Cut | 85 Hz |
| Low Frq | 140 Hz |
| Low Q | 0.8 |
| Low Gain | -1.2 dB |
| Mid Frq | 1.9 kHz |
| Mid Q | 1.3 |
| Mid Gain | +2.6 dB |
| High Frq | 4.2 kHz |
| High Q | 0.9 |
| High Gain | +0.8 dB |
| High Cut | 7.2 kHz |
| Level | +1.8 dB |
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
| 70s Chorus | LA Studio Comp | EQ Param + Simple Delay | Glitz | Rien | IR casque |
| WIDTH | COMP | SOLO | ETHER | LIBRE | IR |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | Description |
|-----|:---:|:---:|:---:|:---:|-------------|
| Base | OFF | ON | OFF | OFF | Clean tres clair, droit et lisible |
| Clean ouvert | OFF | ON | OFF | ON | Plus d'air et de queue sans perdre l'attaque |
| Large pop | ON | ON | OFF | ON | Clean large pour arpeges et refrains ouverts |
| Clean dynamique | OFF | OFF | OFF | OFF/ON | Plus ouvert et moins tenu |
| Solo ethere | ON/OFF | ON | ON | ON | Lift medium + delay + reverb modulee |

---

## Notes / justifications

- Preset principal pour `Kiss Me`, `This Is The Life`, `Dreams`, `Malibu`, `Champagne Supernova` et les parties clean plus ouvertes qui doivent rester belles dans le mix.
- Le `Placater Clean` garde un clean plus plein qu'un Fender trop creuse dans les mediums, tout en restant assez clair pour la Tele et l'IR Greenback.
- `Glitz` est mise sur footswitch plutot qu'en permanence pour garder une vraie difference entre clean simple et clean aerien.
- Le mode solo cible est `FS3 + FS4`, avec `FS1` en option si tu veux encore plus de largeur sur une ligne melodique lente.
- IR conseillee : `Mix 03`. Alternative rapide a tester : `Mix 01` si tu veux un peu plus d'assise et un haut moins ouvert.
- L'IR reste en bypass vers le FX Return et ne s'active que pour le casque.
- A regler en repet juste apres `06A` pour garder le meme volume de base, avec une sensation un peu plus large et plus premium quand `FS4` est engage.
- Le `Kinky Boost` a ete retire pour conserver les quatre fonctions essentielles : compression clean, largeur, delay de solo et reverb etheree.
- Les quatre blocs libres sont `LA Studio Comp`, `70s Chorus`, `Simple Delay` et `Glitz`. La Glitz est couteuse en DSP, mais cette combinaison doit rester compatible ; verifier apres chargement du preset.
