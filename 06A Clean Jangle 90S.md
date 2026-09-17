# POD Go - 06A Clean Jangle 90S
# Cible : clean pop / folk-rock / 90s live
# IR cible : York Audio KW 412 M25-SH - Mix 01

---

## Signal path complet

```text
Input > Wah > [1. LA Studio Comp] > [2. Kinky Boost] > [3. 70s Chorus] > US Deluxe Nrm > Volume > FX Loop > [4. Plate] > IR > EQ Param > Output
```

---

## Reglages detailles

### Bloc 1 - LA Studio Comp
| Param | Valeur |
|-------|--------|
| Peak Reduction | 5.2 |
| Gain | 6.0 |
| Type | Compress |
| Mix | 72% |
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
| Vibrato Rate | 2.8 |
| Vibrato Depth | 0.0 |
| Spread | 6.2 |
| Stereo | True |
| Mix | 15% |
| Level | 0.0 dB |
| Headroom | 0.0 dB |
| Etat par defaut | ON |

### Ampli - US Deluxe Nrm
| Param | Valeur |
|-------|--------|
| Drive | 3.2 |
| Bass | 3.5 |
| Mid | 5.5 |
| Treble | 6.2 |
| Presence | 5.6 |
| Master | 9.0 |
| Channel Vol | 9.5 |
| Sag | 4.5 |
| Hum | 0.8 |
| Ripple | 1.0 |
| Bias | 5.3 |
| Bias X | 5.0 |
| Etat | TOUJOURS ON |

### Bloc 4 - Plate
| Param | Valeur |
|-------|--------|
| Decay | 2.2 s |
| Predelay | 20 ms |
| Low Cut | 140 Hz |
| High Cut | 5.5 kHz |
| Mix | 11% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | ON |

### IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix 01 |
| Mix | 100% |
| Low Cut | 85 Hz |
| High Cut | 7.2 kHz |
| Level | -18.0 dB |
| Etat par defaut | BYPASS |

> L'ampli est attaque par son FX Return avec un baffle reel : le preset tourne
> sans cab ni IR en situation live. L'IR n'est reactivee manuellement que pour
> l'ecoute au casque. Attention, son `Level` est a `-18.0 dB` : l'ecoute casque
> est donc nettement plus basse que le reste de la chaine.

### EQ Parametrique (bloc fixe - post IR)
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
| Level | +1.2 dB |
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
| Kinky Boost | 70s Chorus | EQ Param | Plate | LA Studio Comp | IR casque |
| PUSH | CHORUS | MIX CUT | AIR | COMP | IR |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | FS6 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|:---:|-------------|
| Base | OFF | ON | OFF | ON | ON | OFF | Clean pop large et lisible |
| Couplet sec | OFF | OFF | OFF | ON | ON | OFF | Clean plus direct |
| Arpeges ouverts | OFF | ON | OFF | ON | ON | OFF | Largeur et ambiance legere |
| Refrain qui sort | ON | ON | ON | ON | ON | OFF | Push + haut-medium live |
| Clean roots | ON | OFF | OFF | OFF | ON | OFF | Plus simple et plus roots |

---

## Notes / justifications

- Preset principal pour `Save Tonight`, `Mr. Jones`, `Have You Ever Seen The Rain`, `Torn`, `Dreams`, `Island In The Sun`, `Kiss Me`, `Big Me`, `This Is The Life`, `Starman`.
- Le `US Deluxe Nrm` garde l'attaque Tele tout en restant stable en groupe.
- L'IR `KW 412 M25-SH` apporte plus de medium vocal qu'une 2x12 Fender stock, mais elle est
  bypassee en live : l'ampli est attaque par son FX Return avec un baffle reel.
- IR conseillee pour l'ecoute casque : `Mix 01`. Alternative rapide a tester : `Mix 03`.
- `Ch Vol 9.5` et `Master 9.0` calent le niveau de ce preset sur `06B Crunch Indie Vox`.
  Le clean n'a aucun gain de drive pour densifier son RMS, il doit donc sortir plus haut
  au niveau de l'ampli pour arriver au meme volume percu qu'un crunch.
- Le `70s Chorus` est regle tres bas : il doit elargir, pas laver.
- Le delay a ete retire pour respecter les quatre blocs libres du POD Go. L'EQ fixe assure le lift des solos.
- Les quatre blocs libres sont `LA Studio Comp`, `Kinky Boost`, `70s Chorus` et `Plate` : risque DSP faible.
