# POD Go - 06C Rock Grunge 90S

**Cible :** contraste clean/distorsion, grunge, alt-rock et rock 90s.
**Sortie live :** MAIN Out vers FX Return, IR bypass.

## Signal path complet

```text
Input > Wah > [1. Hedgehog D9] > Placater Clean > [2. 70s Chorus]
      > Volume > FX Loop > [3. Simple Delay] > [4. Plate]
      > IR York KW 412 M25-SH Mix 07 > Preset EQ Parametric > Output
```

La D9 avant l'ampli fournit le mur de distorsion ; le chorus apres l'ampli garde un effet lisible pour les riffs aqueux.

## Reglages detailles

### Blocs utilisateur

| Bloc | Parametre | Valeur |
|------|-----------|--------|
| Hedgehog D9 | Gain / Tone / Level | 6.4 / 4.2 / 4.5 |
| Hedgehog D9 | Etat par defaut | OFF |
| 70s Chorus | Mode / Chorus Rate / Vibrato Rate / Vibrato Depth | Chorus / 2.2 / 2.2 / 0.0 |
| 70s Chorus | Spread / Stereo / Mix / Level / Headroom | 4.5 / Classic / 17% / 0.0 dB / 0.0 dB |
| 70s Chorus | Etat par defaut | OFF |
| Simple Delay | Time / Scale / Feedback / Bass / Treble | 420 ms / 100% / 21% / 5.0 / 5.0 |
| Simple Delay | Mix / Level / Trails | 15% / 0.0 dB / ON |
| Simple Delay | Etat par defaut | OFF |
| Plate | Decay / Predelay / Low Cut / High Cut / Mix / Level / Trails | 3.0 / 15 ms / 150 Hz / 5.2 kHz / 7% / 0.0 dB / ON |
| Plate | Etat par defaut | OFF |

### Ampli - Placater Clean

| Parametre | FS1 GAIN OFF | FS1 GAIN ON |
|-----------|:------------:|:-----------:|
| Drive | 3.3 | 4.9 |
| Bass / Treble / Presence | 3.8 / 6.0 / 5.5 | identique |
| Ch Vol | 7.8 | 7.2 |
| Master / Bright | 8.0 / ON | identique |
| Sag / Ripple / Bias / Bias X | 4.8 / 1.0 / 5.0 / 5.0 | identique |

### Preset EQ - Parametric, toujours ON

| Parametre | FS3 SOLO OFF | FS3 SOLO ON |
|-----------|:------------:|:-----------:|
| Low Frq / Q / Gain | 140 Hz / 0.9 / -1.5 dB | identique |
| Mid Frq / Q / Gain | 1.7 kHz / 1.0 / +0.8 dB | 1.7 kHz / 1.0 / +2.2 dB |
| High Frq / Q / Gain | 3.8 kHz / 1.0 / 0.0 dB | identique |
| Low Cut / High Cut | 90 Hz / 6.8 kHz | identique |
| Level | 0.0 dB | +1.3 dB |

### Blocs dedies

| Bloc | Reglage | Etat par defaut |
|------|---------|------------------|
| Wah | Fassel, Position EXP 1 0-100%, Mix 100%, Level 0.0 dB | BYPASS, toe switch |
| Volume Pedal | Position EXP 2 0-100%, Curve Log, Level 0.0 dB | ON |
| FX Loop | Send 0.0 dB, Return 0.0 dB, Mix 100%, Trails OFF | BYPASS |
| IR | Mix 07, Low Cut 90 Hz, High Cut 6.8 kHz, Mix 100%, Level -18.0 dB | BYPASS |
| Output | Pan Center, Level 0.0 dB | ON |

## Configuration STOMP

| FS1 | FS2 | FS3 | FS4 | FS5 | FS6 |
|-----|-----|-----|-----|-----|-----|
| Parametres ampli | Hedgehog D9 | Simple Delay + parametres EQ | Plate | 70s Chorus | IR |
| GAIN | DIST | SOLO | SPACE | COLOR | CAB CASQUE |

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Clean 90s | OFF | OFF | OFF | OFF/ON | OFF | Vrai couplet clair ou legerement sale |
| Come As You Are | OFF | OFF | OFF | OFF | ON | Chorus aqueux et attaque lisible |
| Refrain grunge | OFF/ON | ON | OFF | OFF/ON | OFF/ON | Contraste brutal et mur de guitare |
| Rock pousse | ON | OFF | OFF | OFF/ON | OFF | Crunch d'ampli plus organique |
| Solo | ON/OFF | ON/OFF | ON | OFF/ON | OFF/ON | Projection et delay en une frappe |

## Utilisation cible - Come As You Are

| Passage | FS1 | FS2 | FS3 | FS4 | FS5 |
|---------|:---:|:---:|:---:|:---:|:---:|
| Intro / couplet | OFF | OFF | OFF | OFF | ON |
| Refrain | OFF | ON | OFF | OFF | ON |
| Solo | OFF | ON | ON | OFF | ON |

## Notes / justifications

- La Scream 808 a ete retiree : elle empechait les vrais couplets clairs de `Creep`, `Today`, `All Apologies` et `Come As You Are`.
- `FS2` est la distorsion principale, coherent avec le role de couleur forte des presets rock.
- Quatre blocs utilisateur exactement. Risque DSP modere, a verifier sur l'appareil.
- Le niveau de base doit etre compare a 06A avec FS1/FS2 OFF ; la distorsion ne doit pas produire un saut excessif.
