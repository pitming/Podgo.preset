# POD Go - 06A Clean Jangle 90S

**Cible :** clean pop, folk-rock, jangle et rythmiques acoustiques electriques.
**Guitare :** Telecaster Vintage '64. **Sortie live :** MAIN Out vers FX Return, IR bypass.

## Signal path complet

```text
Input > Wah > [1. LA Studio Comp] > [2. 70s Chorus] > US Deluxe Nrm
      > Volume > FX Loop > [3. Simple Delay] > [4. Plate]
      > IR York KW 412 M25-SH Mix 01 > Preset EQ Parametric > Output
```

Les blocs dedies sont places pour le resultat musical : compression et modulation avant l'ampli, volume post-ampli, effets temporels apres l'ampli, puis IR casque et EQ final.

## Reglages detailles

### Blocs utilisateur

| Bloc | Parametre | Valeur |
|------|-----------|--------|
| LA Studio Comp | Peak Reduction / Gain / Emphasis | 4.2 / 5.2 / 5.0 |
| LA Studio Comp | Type / Mix / Level | Compress / 65% / 0.0 dB |
| LA Studio Comp | Etat par defaut | ON |
| 70s Chorus | Mode / Chorus Rate / Vibrato Rate / Vibrato Depth | Chorus / 2.4 / 2.4 / 0.0 |
| 70s Chorus | Spread / Stereo / Mix / Level / Headroom | 4.0 / Classic / 12% / 0.0 dB / 0.0 dB |
| 70s Chorus | Etat par defaut | OFF |
| Simple Delay | Time / Scale / Feedback / Bass / Treble | 360 ms / 100% / 18% / 5.0 / 5.0 |
| Simple Delay | Mix / Level / Trails | 14% / 0.0 dB / ON |
| Simple Delay | Etat par defaut | OFF |
| Plate | Decay / Predelay / Low Cut / High Cut / Mix / Level / Trails | 3.5 / 18 ms / 140 Hz / 5.6 kHz / 9% / 0.0 dB / ON |
| Plate | Etat par defaut | ON |

### Ampli - US Deluxe Nrm

| Parametre | FS1 GAIN OFF | FS1 GAIN ON |
|-----------|:------------:|:-----------:|
| Drive | 2.8 | 4.1 |
| Bass | 3.5 | 3.5 |
| Mid | 5.8 | 5.8 |
| Treble | 5.8 | 5.8 |
| Presence | 5.0 | 5.0 |
| Ch Vol | 9.5 | 8.8 |
| Master | 9.0 | 9.0 |
| Sag / Hum / Ripple | 4.5 / 0.8 / 1.0 | identique |
| Bias / Bias X | 5.3 / 5.0 | identique |

### Preset EQ - Parametric, toujours ON

| Parametre | FS3 SOLO OFF | FS3 SOLO ON |
|-----------|:------------:|:-----------:|
| Low Frq / Q / Gain | 120 Hz / 0.8 / -1.5 dB | identique |
| Mid Frq / Q / Gain | 1.8 kHz / 1.4 / +0.8 dB | 1.8 kHz / 1.4 / +2.0 dB |
| High Frq / Q / Gain | 3.8 kHz / 1.0 / 0.0 dB | identique |
| Low Cut / High Cut | 80 Hz / 7.2 kHz | identique |
| Level | 0.0 dB | +1.3 dB |

### Blocs dedies

| Bloc | Reglage | Etat par defaut |
|------|---------|------------------|
| Wah | Fassel, Position EXP 1 0-100%, Mix 100%, Level 0.0 dB | BYPASS, toe switch |
| Volume Pedal | Position EXP 2 0-100%, Curve Log, Level 0.0 dB | ON |
| FX Loop | Send 0.0 dB, Return 0.0 dB, Mix 100%, Trails OFF | BYPASS |
| IR | Mix 01, Low Cut 85 Hz, High Cut 7.2 kHz, Mix 100%, Level -18.0 dB | BYPASS |
| Output | Pan Center, Level 0.0 dB | ON |

## Configuration STOMP

| FS1 | FS2 | FS3 | FS4 | FS5 | FS6 |
|-----|-----|-----|-----|-----|-----|
| Parametres ampli | 70s Chorus | Simple Delay + parametres EQ | Plate | LA Studio Comp | IR |
| GAIN | COLOR | SOLO | SPACE | COMP | CAB CASQUE |

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | FS5 | Description |
|-----|:---:|:---:|:---:|:---:|:---:|-------------|
| Base | OFF | OFF | OFF | ON | ON | Clean net, chaud et lisible |
| Jangle / 12 cordes | OFF | ON | OFF | ON | ON | Largeur legere sans effet 80s |
| Refrain pousse | ON | OFF/ON | OFF | ON | ON | Plus de grain, volume percu stable |
| Solo pop | ON/OFF | OFF/ON | ON | ON | ON | Delay et projection medium en une frappe |
| Folk sec | OFF | OFF | OFF | OFF | ON/OFF | Rythmique directe et percussive |

## Notes / justifications

- `FS1` modifie l'ampli sans consommer un bloc de drive ; la baisse de `Ch Vol` compense la compression supplementaire.
- Le delay revient car il est plus utile aux solos de la setlist qu'un boost externe redondant.
- Le chorus est en mode `Classic`, plus stable vers un seul baffle que le mode stereo `True`.
- Quatre blocs utilisateur exactement. Risque DSP faible.
- `Ch Vol 9.5` constitue la reference de niveau des six presets ; validation finale a faire au volume de repetition.
