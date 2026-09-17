# POD Go - 07A Clear Ether Clean

**Cible :** clean ample, passages aeriens, crescendo et solo ethere.
**Sortie live :** MAIN Out vers FX Return, IR bypass.

## Signal path complet

```text
Input > Wah > [1. LA Studio Comp] > Placater Clean > [2. 70s Chorus]
      > Volume > FX Loop > [3. Simple Delay] > [4. Glitz]
      > IR York KW 412 M25-SH Mix 03 > Preset EQ Parametric > Output
```

La modulation apres l'ampli et la Glitz en fin de chaine creent l'espace sans brouiller le transient compresse.

## Reglages detailles

### Blocs utilisateur

| Bloc | Parametre | Valeur |
|------|-----------|--------|
| LA Studio Comp | Peak Reduction / Gain / Emphasis | 2.8 / 4.5 / 5.0 |
| LA Studio Comp | Type / Mix / Level | Compress / 58% / 0.0 dB |
| LA Studio Comp | Etat par defaut | ON |
| 70s Chorus | Mode / Chorus Rate / Vibrato Rate / Vibrato Depth | Chorus / 1.8 / 1.8 / 0.0 |
| 70s Chorus | Spread / Stereo / Mix / Level / Headroom | 4.5 / Classic / 13% / 0.0 dB / 0.0 dB |
| 70s Chorus | Etat par defaut | OFF |
| Simple Delay | Time / Scale / Feedback / Bass / Treble | 430 ms / 100% / 23% / 5.0 / 5.0 |
| Simple Delay | Mix / Level / Trails | 18% / 0.0 dB / ON |
| Simple Delay | Etat par defaut | OFF |
| Glitz | Decay / Predelay / Low Cut / High Cut / Mix / Level | 4.8 / 24 ms / 150 Hz / 6.8 kHz / 14% / 0.0 dB |
| Glitz | Delay / Rate / Depth / Xover / Modulation Mix / Trails | 3.0 / 1.3 Hz / 2.4 / 1.2 kHz / 2.2 / ON |
| Glitz | Etat par defaut | OFF |

### Ampli - Placater Clean

| Parametre | FS1 GAIN OFF | FS1 GAIN ON |
|-----------|:------------:|:-----------:|
| Drive | 2.6 | 3.8 |
| Bass / Treble / Presence | 3.4 / 6.3 / 5.2 | identique |
| Ch Vol | 8.7 | 8.2 |
| Master / Bright | 8.2 / ON | identique |
| Sag / Ripple / Bias / Bias X | 4.2 / 1.0 / 5.2 / 5.0 | identique |

### Preset EQ - Parametric, toujours ON

| Parametre | FS3 SOLO OFF | FS3 SOLO ON |
|-----------|:------------:|:-----------:|
| Low Frq / Q / Gain | 140 Hz / 0.8 / -1.2 dB | identique |
| Mid Frq / Q / Gain | 1.9 kHz / 1.3 / +0.6 dB | 1.9 kHz / 1.3 / +1.8 dB |
| High Frq / Q / Gain | 4.2 kHz / 0.9 / 0.0 dB | identique |
| Low Cut / High Cut | 85 Hz / 7.2 kHz | identique |
| Level | 0.0 dB | +1.2 dB |

### Blocs dedies

| Bloc | Reglage | Etat par defaut |
|------|---------|------------------|
| Wah | Fassel, Position EXP 1 0-100%, Mix 100%, Level 0.0 dB | BYPASS, toe switch |
| Volume Pedal | Position EXP 2 0-100%, Curve Log, Level 0.0 dB | ON |
| FX Loop | Send 0.0 dB, Return 0.0 dB, Mix 100%, Trails OFF | BYPASS |
| IR | Mix 03, Low Cut 85 Hz, High Cut 7.2 kHz, Mix 100%, Level -18.0 dB | BYPASS |
| Output | Pan Center, Level 0.0 dB | ON |

## Configuration STOMP

| FS1 | FS2 | FS3 | FS4 | FS5 | FS6 |
|-----|-----|-----|-----|-----|-----|
| Parametres ampli | 70s Chorus | Simple Delay + parametres EQ | Glitz | LA Studio Comp | IR |
| GAIN | COLOR | SOLO | SPACE | COMP | CAB CASQUE |

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Base | OFF | OFF | OFF | OFF | ON | Clean plein et tres lisible |
| Clean ouvert | OFF | OFF/ON | OFF | ON | ON | Grande profondeur sans perdre l'attaque |
| Crescendo | ON | ON | OFF | ON | ON | Plus de corps pour les montees |
| Solo ethere | ON/OFF | ON/OFF | ON | ON | ON | Lift, delay et reverb modulee |
| Clean dynamique | OFF | OFF | OFF | OFF | OFF | Plus de transient et moins de sustain |

## Notes / justifications

- `FS1` remplace le boost externe et permet les montees de `Malibu` et `Champagne Supernova`.
- Glitz conserve la vraie identite de ce preset ; elle n'est jamais active par defaut.
- Quatre blocs utilisateur exactement. Risque DSP eleve mais plausible ; si un modele est grise, remplacer Glitz par Plate avant toute autre concession.
- Le volume de base doit etre aligne sur 06A ; le solo vise environ +1.5 a +2 dB percus, pas davantage.
