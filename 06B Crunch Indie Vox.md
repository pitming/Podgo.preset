# POD Go - 06B Crunch Indie Vox

**Cible :** indie-rock, Britpop et crunch nerveux.
**Sortie live :** MAIN Out vers FX Return, IR bypass.

## Signal path complet

```text
Input > Wah > [1. Minotaur] > Essex A30 > [2. 70s Chorus] > Volume
      > FX Loop > [3. Simple Delay] > [4. Plate]
      > IR York KW 412 M25-SH Mix JA 1 > Preset EQ Parametric > Output
```

Le chorus est place apres l'ampli pour elargir le crunch sans rendre l'attaque molle.

## Reglages detailles

### Blocs utilisateur

| Bloc | Parametre | Valeur |
|------|-----------|--------|
| Minotaur | Gain / Tone / Level | 2.8 / 4.7 / 6.7 |
| Minotaur | Etat par defaut | OFF |
| 70s Chorus | Mode / Chorus Rate / Vibrato Rate / Vibrato Depth | Chorus / 2.0 / 2.0 / 0.0 |
| 70s Chorus | Spread / Stereo / Mix / Level / Headroom | 3.5 / Classic / 9% / 0.0 dB / 0.0 dB |
| 70s Chorus | Etat par defaut | OFF |
| Simple Delay | Time / Scale / Feedback / Bass / Treble | 390 ms / 100% / 20% / 5.0 / 5.0 |
| Simple Delay | Mix / Level / Trails | 15% / 0.0 dB / ON |
| Simple Delay | Etat par defaut | OFF |
| Plate | Decay / Predelay / Low Cut / High Cut / Mix / Level / Trails | 2.8 / 10 ms / 150 Hz / 4.9 kHz / 7% / 0.0 dB / ON |
| Plate | Etat par defaut | ON |

### Ampli - Essex A30

| Parametre | FS1 GAIN OFF | FS1 GAIN ON |
|-----------|:------------:|:-----------:|
| Drive | 4.5 | 6.2 |
| Bass / Cut / Treble / Presence | 3.2 / 5.2 / 5.8 / 5.2 | identique |
| Ch Vol | 7.6 | 6.8 |
| Master | 7.4 | 7.4 |
| Sag / Hum / Ripple | 4.3 / 0.5 / 1.0 | identique |
| Bias / Bias X | 5.0 / 5.0 | identique |

### Preset EQ - Parametric, toujours ON

| Parametre | FS3 SOLO OFF | FS3 SOLO ON |
|-----------|:------------:|:-----------:|
| Low Frq / Q / Gain | 180 Hz / 0.8 / -1.3 dB | identique |
| Mid Frq / Q / Gain | 1.8 kHz / 1.0 / +0.8 dB | 1.8 kHz / 1.0 / +2.2 dB |
| High Frq / Q / Gain | 3.3 kHz / 0.9 / 0.0 dB | identique |
| Low Cut / High Cut | 90 Hz / 6.4 kHz | identique |
| Level | 0.0 dB | +1.3 dB |

### Blocs dedies

| Bloc | Reglage | Etat par defaut |
|------|---------|------------------|
| Wah | Fassel, Position EXP 1 0-100%, Mix 100%, Level 0.0 dB | BYPASS, toe switch |
| Volume Pedal | Position EXP 2 0-100%, Curve Log, Level 0.0 dB | ON |
| FX Loop | Send 0.0 dB, Return 0.0 dB, Mix 100%, Trails OFF | BYPASS |
| IR | Mix JA 1, Low Cut 90 Hz, High Cut 6.4 kHz, Mix 100%, Level -18.0 dB | BYPASS |
| Output | Pan Center, Level 0.0 dB | ON |

## Configuration STOMP

| FS1 | FS2 | FS3 | FS4 | FS5 | FS6 |
|-----|-----|-----|-----|-----|-----|
| Parametres ampli | 70s Chorus | Simple Delay + parametres EQ | Plate | Minotaur | IR |
| GAIN | COLOR | SOLO | SPACE | BOOST | CAB CASQUE |

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Base | OFF | OFF | OFF | ON | OFF | Crunch Vox dynamique |
| Riff principal | ON | OFF | OFF | OFF/ON | OFF | Crunch dense en une frappe |
| Refrain epais | ON | OFF/ON | OFF | ON | ON | Sustain supplementaire |
| Solo | ON | OFF | ON | OFF/ON | OFF/ON | Lift medium et delay |
| Dry garage | OFF/ON | OFF | OFF | OFF | OFF | Attaque seche et immediate |

## Notes / justifications

- Le Minotaur n'est plus necessaire pour obtenir le gain principal : `FS1` suffit, ce qui simplifie les transitions.
- `FS5` reste un etage facultatif pour les riffs qui demandent plus de sustain.
- Quatre blocs utilisateur exactement. Risque DSP faible.
- Le `Ch Vol` plus bas que 06A compense le RMS superieur du crunch.
