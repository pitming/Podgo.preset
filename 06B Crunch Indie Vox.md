# POD Go - 06B Crunch Indie Vox
# Cible : crunch rock / indie costaud / alt-pop live
# IR cible : York Audio KW 412 M25-SH - Mix JA 1

---

## Signal path complet

```text
Input > Wah > [1. Kinky Boost] > [2. Minotaur] > Essex A30 > Volume > FX Loop > [3. Simple Delay] > [4. Plate] > IR > EQ Param > Output
```

---

## Reglages detailles

### Bloc 1 - Kinky Boost
| Param | Valeur |
|-------|--------|
| Drive | 2.0 |
| Boost | ON |
| Bright | ON |
| Etat par defaut | OFF |

### Bloc 2 - Minotaur
| Param | Valeur |
|-------|--------|
| Gain | 3.7 |
| Tone | 4.7 |
| Level | 7.0 |
| Etat par defaut | OFF |

### Ampli - Essex A30
| Param | Valeur |
|-------|--------|
| Drive | 5.6 |
| Bass | 3.2 |
| Cut | 5.0 |
| Treble | 5.9 |
| Presence | 5.4 |
| Master | 7.4 |
| Ch Vol | 7.4 |
| Sag | 4.3 |
| Hum | 0.5 |
| Ripple | 1.0 |
| Bias | 5.0 |
| Bias X | 5.0 |
| Etat | TOUJOURS ON |

### Bloc 3 - Simple Delay
| Param | Valeur |
|-------|--------|
| Time | 390 ms |
| Scale | 100% |
| Feedback | 22% |
| Mix | 17% |
| Level | +1.4 dB |
| Trails | ON |
| Etat par defaut | OFF |

### Bloc 4 - Plate
| Param | Valeur |
|-------|--------|
| Decay | 1.4 s |
| Predelay | 10 ms |
| Low Cut | 150 Hz |
| High Cut | 4.9 kHz |
| Mix | 8% |
| Level | 0.0 dB |
| Trails | ON |
| Etat par defaut | ON |

### IR: York Audio KW 412 M25-SH
| Param | Valeur |
|-------|--------|
| IR | KW 412 M25-SH - Mix JA 1 |
| Mix | 100% |
| Low Cut | 90 Hz |
| High Cut | 6.4 kHz |
| Level | -18.0 dB |
| Etat par defaut | BYPASS |

> L'ampli est attaque par son FX Return avec un baffle reel : le preset tourne
> sans cab ni IR en situation live. L'IR n'est reactivee manuellement que pour
> l'ecoute au casque. Attention, son `Level` est a `-18.0 dB` : l'ecoute casque
> est donc nettement plus basse que le reste de la chaine.

### EQ Parametrique (bloc fixe - post IR)
| Param | Valeur |
|-------|--------|
| Low Cut | 90 Hz |
| Low Freq | 180 Hz |
| Low Q | 0.8 |
| Low Gain | -1.3 dB |
| Mid Freq | 1.8 kHz |
| Mid Q | 1.0 |
| Mid Gain | +3.6 dB |
| High Freq | 3.3 kHz |
| High Q | 0.9 |
| High Gain | +0.4 dB |
| High Cut | 6.4 kHz |
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
| Kinky Boost | Minotaur | EQ Param + Simple Delay | Plate | Rien | IR casque |
| PUSH | GAIN+ | SOLO | ROOM | LIBRE | IR |

---

## Guide des sons

| Son | FS1 | FS2 | FS3 | FS4 | Description |
|-----|:---:|:---:|:---:|:---:|-------------|
| Base | OFF | OFF | OFF | ON | Vrai crunch rock, plus dense et plus stable |
| Dry crunch | OFF | OFF | OFF | OFF | Plus frontal et plus sec |
| Refrain pousse | ON | OFF | OFF | ON | Plus de grain, plus de corps, plus de lift |
| Riff dense | ON | ON | OFF | OFF | Crunch muscle, sec et agressif |
| Solo / lead | ON | ON | ON | OFF | Projection medium + niveau + delay |

---

## Utilisation cible - Take Me Out

| Passage | FS1 | FS2 | FS3 | FS4 | FS5 | Resultat |
|---------|:---:|:---:|:---:|:---:|:---:|----------|
| Base / couplet | OFF | OFF | OFF | OFF | OFF | Crunch sec et nerveux |
| Riff principal | ON | ON | OFF | OFF | OFF | Plus dense, plus agressif |
| Solo / mise en avant | ON | ON | ON | OFF | OFF | Lift de medium + volume + delay |

---

## Notes / justifications

- Preset principal pour `Take Me Out`, `Lonely Boy`, `The Middle`, `Today`, `Not An Addict`, `Celebrity Skin`, `Learn To Fly`, `Hello`, `Louie` et les morceaux pop-rock qui demandent un vrai crunch live.
- L'`Essex A30` est maintenant regle plus haut pour que le preset ait deja du coffre sans dependre d'une drive engagee en permanence.
- `Kinky Boost` sert a faire passer le preset du vrai crunch au refrain plus muscle ; `Minotaur` prend ensuite le relais pour les riffs les plus denses et les leads.
- Le voicing reste plus compact et plus vocal que `07B`, mais moins gros, moins sale et moins massif que `06C`.
- La zone haute est volontairement tenue par le `High Cut` IR/EQ pour garder de l'attaque sans finir metallique ou fizz.
- Sur `Take Me Out`, pars sur `FS4 OFF` pour le riff principal. Le vrai palier de gain arrive avec `FS1 + FS2`, pas avec `FS3` seul.
- `FS3` doit rester un switch de projection, pas un simple delay d'ambiance ; son EQ est donc plus marquee que sur `07B`.
- IR conseillee pour l'ecoute casque : `Mix JA 1`. Alternative rapide a tester : `Mix 07` si tu veux un registre plus brut ou plus garage.
- Le `Kinky Boost` doit imperativement rester **OFF** en Base. Il etait active par erreur dans le
  preset machine, ce qui faisait sonner `06B` nettement plus fort que `06A` et cassait la
  hierarchie de volume du set. Le palier de gain se prend avec `FS1`, pas en permanence.
- Volume rebaisse pour rester proche de `06A Clean Jangle 90S`, malgre un niveau de gain et de compression percue plus eleves.
- Le compresseur a ete retire : l'Essex deja pousse fournit assez de tenue et les quatre blocs libres restent consacres aux deux paliers de gain, au solo et a l'ambiance.
- Les quatre blocs libres sont `Kinky Boost`, `Minotaur`, `Simple Delay` et `Plate` : risque DSP faible.
