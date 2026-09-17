# POD Go - 06D Heavy Alt Modern

**Cible :** hard rock moderne, accordages bas, riffs serres et leads denses.
**Sortie live :** MAIN Out vers FX Return, IR bypass.

## Signal path complet

```text
Input > Wah > [1. Scream 808] > Placater Dirty > Volume > FX Loop
      > [4. LA Studio Comp] > [2. Simple Delay] > [3. Plate]
      > IR York KW 412 M25-SH Mix JA 2 > Preset EQ Parametric > Output
```

Le compresseur place avant delay sert uniquement de soutien de lead leger ; il reste bypass en rythme. Si le DSP refuse cette combinaison, le supprimer en premier et conserver le solo via EQ + delay.

## Reglages detailles

### Blocs utilisateur

| Bloc | Parametre | Valeur |
|------|-----------|--------|
| Scream 808 | Gain / Tone / Level | 0.8 / 5.2 / 7.0 |
| Scream 808 | Etat par defaut | ON |
| Simple Delay | Time / Scale / Feedback / Bass / Treble | 430 ms / 100% / 19% / 5.0 / 5.0 |
| Simple Delay | Mix / Level / Trails | 14% / 0.0 dB / ON |
| Simple Delay | Etat par defaut | OFF |
| Plate | Decay / Predelay / Low Cut / High Cut / Mix / Level / Trails | 2.8 / 14 ms / 170 Hz / 5.0 kHz / 7% / 0.0 dB / ON |
| Plate | Etat par defaut | OFF |
| LA Studio Comp | Peak Reduction / Gain / Emphasis | 1.5 / 3.0 / 5.0 |
| LA Studio Comp | Type / Mix / Level | Compress / 35% / 0.0 dB |
| LA Studio Comp | Etat par defaut | OFF |

### Ampli - Placater Dirty

| Parametre | FS1 GAIN OFF | FS1 GAIN ON |
|-----------|:------------:|:-----------:|
| Drive | 4.6 | 6.0 |
| HBE | OFF | ON |
| Bass / Mid / Treble / Presence | 3.5 / 5.8 / 5.7 / 5.3 | identique |
| Ch Vol | 7.4 | 6.7 |
| Master | 7.5 | 7.5 |
| Sag / Ripple / Bias / Bias X | 4.2 / 1.2 / 5.0 / 5.0 | identique |
| Fat / C45 / Saturation | OFF / ON / OFF | identique |

| Parametre | FS5 TIGHT OFF | FS5 TIGHT ON |
|-----------|:-------------:|:------------:|
| Bass | 3.5 | 3.0 |
| Sag | 4.2 | 3.5 |

`FS5 TIGHT` ne bypasse aucun bloc : il alterne uniquement ces deux parametres de l'ampli.

### Preset EQ - Parametric, toujours ON

| Parametre | FS3 SOLO OFF | FS3 SOLO ON |
|-----------|:------------:|:-----------:|
| Low Frq / Q / Gain | 120 Hz / 0.9 / -2.0 dB | identique |
| Mid Frq / Q / Gain | 1.5 kHz / 1.3 / +0.8 dB | 1.5 kHz / 1.3 / +2.0 dB |
| High Frq / Q / Gain | 3.5 kHz / 1.0 / 0.0 dB | identique |
| Low Cut / High Cut | 90 Hz / 6.6 kHz | identique |
| Level | 0.0 dB | +1.2 dB |

### Blocs dedies

| Bloc | Reglage | Etat par defaut |
|------|---------|------------------|
| Wah | Fassel, Position EXP 1 0-100%, Mix 100%, Level 0.0 dB | BYPASS, toe switch |
| Volume Pedal | Position EXP 2 0-100%, Curve Log, Level 0.0 dB | ON |
| FX Loop | Send 0.0 dB, Return 0.0 dB, Mix 100%, Trails OFF | BYPASS |
| IR | Mix JA 2, Low Cut 95 Hz, High Cut 6.6 kHz, Mix 100%, Level -18.0 dB | BYPASS |
| Output | Pan Center, Level 0.0 dB | ON |

## Configuration STOMP

| FS1 | FS2 | FS3 | FS4 | FS5 | FS6 |
|-----|-----|-----|-----|-----|-----|
| Drive + HBE + Ch Vol ampli | Scream 808 | Simple Delay + LA Comp + parametres EQ | Plate | Bass + Sag ampli | IR |
| GAIN | TUBE | SOLO | SPACE | TIGHT | CAB CASQUE |

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Base heavy | OFF | ON | OFF | OFF | ON | Riff moderne serre |
| Gros refrain | ON | ON | OFF | OFF | ON | Plus de saturation sans gros saut de niveau |
| Rock ouvert | OFF | OFF | OFF | OFF/ON | OFF | Moins moderne, plus dynamique |
| Lead | ON | ON | ON | ON/OFF | OFF/ON | Sustain, delay et projection medium |

## Notes / justifications

- Un seul drive externe suffit : le Placater fournit le second palier par ses parametres `Drive` et `HBE`.
- La Plate est OFF par defaut pour ne pas ramollir `Animal I Have Become` et `Slither`.
- Quatre blocs utilisateur exactement. C'est le preset le plus charge en DSP ; supprimer `LA Studio Comp` si un modele apparait grise.
- Le niveau doit rester proche de 06A malgre une sensation plus dense ; `Ch Vol` est volontairement bas.
