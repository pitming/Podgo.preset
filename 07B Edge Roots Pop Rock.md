# POD Go - 07B Edge Roots Pop Rock

**Cible :** edge-of-breakup, roots, garage, riffs vintage et octave de Seven Nation Army.
**Sortie live :** MAIN Out vers FX Return, IR bypass.

## Signal path complet

```text
Input > Wah > [4. LA Studio Comp] > [1. Simple Pitch] > Essex A30 > Volume
      > FX Loop > [2. Simple Delay] > [3. Plate]
      > IR York KW 412 M25-SH Mix JA 1 > Preset EQ Parametric > Output
```

Le pitch est volontairement avant l'ampli pour que l'octave inferieure excite le grain de l'Essex comme le riff original.

## Reglages detailles

### Blocs utilisateur

| Bloc | Parametre | Valeur |
|------|-----------|--------|
| Simple Pitch | Interval / Cents / Delay / Shift Level | -12 / 0 / 0.0 ms / 0.0 dB |
| Simple Pitch | Mix / Level | 100% / 0.0 dB |
| Simple Pitch | Etat par defaut | OFF |
| Simple Delay | Time / Scale / Feedback / Bass / Treble | 350 ms / 100% / 17% / 5.0 / 5.0 |
| Simple Delay | Mix / Level / Trails | 13% / 0.0 dB / ON |
| Simple Delay | Etat par defaut | OFF |
| Plate | Decay / Predelay / Low Cut / High Cut / Mix / Level / Trails | 3.2 / 14 ms / 145 Hz / 5.2 kHz / 8% / 0.0 dB / ON |
| Plate | Etat par defaut | ON |
| LA Studio Comp | Peak Reduction / Gain / Emphasis | 2.5 / 4.0 / 5.0 |
| LA Studio Comp | Type / Mix / Level | Compress / 50% / 0.0 dB |
| LA Studio Comp | Etat par defaut | OFF |

### Ampli - Essex A30

| Parametre | FS1 GAIN OFF | FS1 GAIN ON |
|-----------|:------------:|:-----------:|
| Drive | 4.0 | 5.8 |
| Bass / Cut / Treble / Presence | 3.3 / 5.6 / 5.6 / 4.9 | identique |
| Ch Vol | 8.0 | 7.2 |
| Master | 7.8 | 7.8 |
| Sag / Hum / Ripple | 4.6 / 0.5 / 1.0 | identique |
| Bias / Bias X | 5.0 / 5.0 | identique |

### Preset EQ - Parametric, toujours ON

| Parametre | FS3 SOLO OFF | FS3 SOLO ON |
|-----------|:------------:|:-----------:|
| Low Frq / Q / Gain | 170 Hz / 0.8 / -1.0 dB | identique |
| Mid Frq / Q / Gain | 1.7 kHz / 1.1 / +0.6 dB | 1.7 kHz / 1.1 / +1.8 dB |
| High Frq / Q / Gain | 3.4 kHz / 0.9 / 0.0 dB | identique |
| Low Cut / High Cut | 90 Hz / 6.6 kHz | identique |
| Level | 0.0 dB | +1.2 dB |

### Blocs dedies

| Bloc | Reglage | Etat par defaut |
|------|---------|------------------|
| Wah | Fassel, Position EXP 1 0-100%, Mix 100%, Level 0.0 dB | BYPASS, toe switch |
| Volume Pedal | Position EXP 2 0-100%, Curve Log, Level 0.0 dB | ON |
| FX Loop | Send 0.0 dB, Return 0.0 dB, Mix 100%, Trails OFF | BYPASS |
| IR | Mix JA 1, Low Cut 90 Hz, High Cut 6.6 kHz, Mix 100%, Level -18.0 dB | BYPASS |
| Output | Pan Center, Level 0.0 dB | ON |

## Configuration STOMP

| FS1 | FS2 | FS3 | FS4 | FS5 | FS6 |
|-----|-----|-----|-----|-----|-----|
| Parametres ampli | Simple Pitch | Simple Delay + parametres EQ | Plate | LA Studio Comp | IR |
| GAIN | OCTAVE | SOLO | SPACE | COMP | CAB CASQUE |

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Base roots | OFF | OFF | OFF | ON | OFF | Edge organique et ouvert |
| Garage sec | ON | OFF | OFF | OFF | OFF | Crunch nerveux pour Last Nite |
| Refrain roots | ON | OFF | OFF | ON | OFF/ON | Plus de grain sans changer de preset |
| Solo roots | ON | OFF | ON | OFF/ON | OFF/ON | Delay court et lift medium |
| Seven Nation Army riff | OFF/ON | ON | OFF | OFF | OFF | Octave inferieure avant l'ampli |

## Notes / justifications

- Ce preset abandonne le chorus redondant pour une fonction introuvable ailleurs : l'octave du riff de `Seven Nation Army`.
- La variation de Drive de l'Essex remplace le Kinky Boost et preserve le caractere Tele/Vox.
- Quatre blocs utilisateur exactement. Risque DSP faible a modere a cause du pitch.
- Le niveau de base se situe entre 06A et 06B ; la compensation de `Ch Vol` maintient FS1 proche du meme volume percu.
