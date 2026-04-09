# POD Go - Preset Clean 90s Folk-Rock
# Son clair generique — strumming & arpege
# Telecaster Standard Mex - Micro Fender Vintage '64

---

## Morceaux cibles

| Morceau                          | Artiste                  | Caractere son guitare                     |
|----------------------------------|--------------------------|-------------------------------------------|
| This Is the Life                 | Amy Macdonald            | Strumming percussif, brillant, energique  |
| Save Tonight                     | Eagle-Eye Cherry         | Clean chaud, groovy, legere compression   |
| Mr. Jones                        | Counting Crows           | Arpege + strumming, mediums riches        |
| Have You Ever Seen the Rain      | CCR                      | Twang clean, claquant, dynamique          |
| Runaway Train                    | Soul Asylum              | Clean avec chorus subtil, arpege emotive  |
| Torn                             | Natalie Imbruglia        | Clean brillant, chorus/doubler, aere      |
| Kiss Me                          | Sixpence None the Richer | Arpege delicat, reverb douce, shimmer     |

**Denominateur commun** : clean brillant et defini, mediums presents pour
couper dans le mix, dynamique preservee (strumming percussif), spatialisation
legere (chorus/reverb). Son 90s folk-rock electrique qui sonne presque
acoustique par moments.

---

## Signal Path (7 blocs + EQ param gratuit + pedale expression)

```
Input > [1. COMP: LA Studio Comp] > [2. AMP: US Princess] > [3. CHORUS: 70s Chorus] > [4. TREMOLO: Harmonic Tremolo] > [5. DELAY: Simple Delay] > [6. REVERB: Plateaux] > [7. CAB: 1x12 US Princess] > Output
                                            |
                                       [EQ Param] (bloc gratuit, post-amp)
                                            |
                                       [Pedale: Volume] (bloc gratuit)
```

---

## Reglages detailles

### Bloc 1 - LA Studio Comp (modele Teletronix LA-2A)

| Param          | Valeur   |
|----------------|----------|
| Peak Reduction | 3.0      |
| Gain           | 4.0      |
| Emphasis       | 3.0      |
| Type           | Compress |
| Mix            | 60%      |
| Etat par defaut| ON       |

**Role** : Compression parallele douce. Egalise le strumming sans ecraser
la dynamique. Peak Reduction a 3.0 = touche legere, la Tele garde son
attaque et son twang. Mix a 60% pour un peu plus de tenue que le preset
generique — le strumming folk-rock demande un volume plus constant entre
les cordes. Emphasis a 3.0 = le compresseur reagit un peu moins aux basses,
ce qui evite le pompage en strumming (les cordes graves ne declenchent pas
excessivement la compression). Bloc leger en DSP.

### Bloc 2 - US Princess (modele Fender Princeton Reverb)

| Param          | Valeur |
|----------------|--------|
| Drive          | 3.0    |
| Bass           | 4.5    |
| Mid            | 6.5    |
| Treble         | 8.0    |
| Master         | 8.0    |
| Channel Vol    | 8.5    |
| Bias           | 0.52   |
| BiasX          | 0.50   |
| Sag            | 0.50   |
| Hum            | 0.50   |
| Ripple         | 0.50   |
| Etat           | TOUJOURS ON |

**Role** : Coeur du son clean. Le Princeton est *le* son clean americain
des 90s. Drive a 3.0 = clean cristallin meme en strumming fort. Mid a 6.5
pour la chaleur et la presence dans le mix (Mr. Jones, Save Tonight).
Treble a 8.0 pour le brillant et le twang de la Tele — monte par rapport
a la version precedente pour compenser l'absence de controle Presence sur
cet ampli. Bass a 4.5 (baisse de 5.0) pour reduire l'empatement et
l'effet "wouf" en strumming. Master a 8.0 et Channel Vol a 8.5 pour un
volume genereux — c'est un ampli clean, il faut le pousser pour qu'il
sonne vivant. Note : le US Princess n'a pas de controle Presence dans le
POD Go, tout le brillant passe par Treble.

### Bloc 3 - 70s Chorus (modele Boss CE-1)

| Param          | Valeur   |
|----------------|----------|
| Chorus Rate    | 2.5      |
| Mode           | Chorus   |
| Vibrato Rate   | 7.0      |
| Vibrato Depth  | 5.0      |
| Spread         | 0.0      |
| Stereo         | Classic  |
| Mix            | 35%      |
| Level          | 0.0 dB   |
| Headroom       | 0.0 dB   |
| Etat par defaut| OFF      |

**Role** : Chorus lent et subtil, style "doubler". Elargit le son clean
et lui donne un cote shimmer/acoustique. Chorus Rate a 2.5 (bas) pour
eviter l'effet "wobbly" — on veut un epaississement, pas un effet
audible. Mode Chorus (pas Vibrato, qui coupe le signal sec). Spread a
0.0 car la sortie est mono (FX Return ampli). Stereo en Classic pour
un chorus plus naturel et vintage. Mix a 35% garde le son naturel de
la Tele au centre. Vibrato Rate et Depth sont les parametres du mode
Vibrato — pas actifs en mode Chorus, laisser aux valeurs par defaut.
Leger en DSP.

### Bloc 4 - Harmonic Tremolo (modele Fender Brownface)

| Param          | Valeur   |
|----------------|----------|
| Speed          | 3.5 Hz   |
| Intensity      | 5.0      |
| Wave Shape     | Sine     |
| Duty Cycle     | 50%      |
| Bass Freq      | 500 Hz   |
| Treble Freq    | 700 Hz   |
| Level          | 0.0 dB   |
| Mix            | 100%     |
| Spread         | 0.0      |
| Etat par defaut| OFF      |

**Role** : Effet "bonus" vintage. Le tremolo harmonique separe les
basses et les aigus autour d'un point de croisement (Bass Freq / Treble
Freq) et les fait pulser en alternance — son organique et chaud, typique
Fender 60s. Speed a 3.5 Hz = pulsation perceptible mais musicale.
Intensity a 5.0 (moitie) pour un effet present mais pas extreme — le
tremolo reste musical sans hacher le son. Wave Shape Sine = modulation
douce et ronde. **Spread a 0.0 obligatoire** car sortie mono (FX Return
ampli). Un Spread a 1.0 en mono cause des annulations de phase et un son
bizarre. Ajoute du mouvement sur les arpeges (Kiss Me, Torn). Tres leger
en DSP.

### Bloc 5 - Simple Delay

| Param          | Valeur  |
|----------------|---------|
| Time           | 350 ms  |
| Feedback       | 20%     |
| Mix            | 20%     |
| Level          | 0.0 dB  |
| Scale          | 75%     |
| Trails         | On      |
| Etat par defaut| OFF     |

**Role** : Delay court et discret. 350ms = slap-back allonge, ajoute
de la profondeur sans creer d'echo audible. Feedback a 20% = 2-3
repetitions max. Mix bas pour rester en arriere-plan. Scale a 75% =
les repetitions sont legerement plus courtes que le temps principal,
ce qui donne un decay plus naturel. Trails On = quand tu coupes le
delay via FS6, les repetitions en cours s'eteignent naturellement au
lieu de couper net (plus musical). Utile sur les arpeges et les
passages calmes.

### Bloc 6 - Plateaux (Reverb)

| Param          | Valeur  |
|----------------|---------|
| Decay          | 2.5     |
| Predelay       | 60 ms   |
| Tone           | 7.0     |
| Modulation     | 5.0     |
| Mix            | 25%     |
| Level          | 0.0 dB  |
| Pitch 1        | -12     |
| Cents 1        | -0.80   |
| Pitch 2        | +7      |
| Cents 2        | +0.40   |
| Pitch Mix      | 15%     |
| Trails         | On      |
| Etat par defaut| ON      |

**Role** : Reverb plate avec shimmer subtil. Le Plateaux a deux
pitch-shifters integres dans la queue de reverb. Pitch 1 a -12 (octave
basse) et Pitch 2 a +7 (quinte) ajoutent des harmoniques dans les
reflexions — c'est ce qui donne le cote aerien et "shimmer". Pitch Mix
a 15% = les harmoniques sont tres en retrait, juste assez pour enrichir
la reverb sans que l'effet soit audible comme tel. Modulation a 5.0 =
mouvement subtil dans la reverb, evite un son statique. Predelay a 60ms
preserve l'attaque du pick. Tone a 7.0 = reverb brillante qui s'integre
au son clean. Trails On = la reverb s'eteint naturellement quand on
coupe via FS3. ON par defaut car tous ces morceaux utilisent de la reverb.

### Bloc 7 - Cab: 1x12 US Princess

| Param          | Valeur     |
|----------------|------------|
| Mic            | 57 Dynamic |
| Distance       | 2.5        |
| Low Cut        | 80 Hz      |
| High Cut       | 8.5 kHz    |
| Level          | 0 dB       |
| Etat par defaut| **OFF**    |

**Role** : Simulation baffle pour casque UNIQUEMENT. Le cab 1x12
Princeton matche l'ampli pour un son coherent. Distance a 2.5 pour un
peu plus de room. High Cut a 8.5 kHz pour garder le brillant clean.
**IMPORTANT : ce bloc DOIT etre OFF pour la sortie FX Return ampli.**
Si le cab est ON en sortie ampli, le signal passe dans une simulation
de HP puis dans le vrai HP = double filtrage qui tue le son (sourd,
petit, sans dynamique). N'activer que pour le casque via FS4.

Note : utiliser le 1x12 (pas le 1x10) pour plus de corps et de bas.
Le 1x10 natif du Princeton est trop petit pour ce preset.

### EQ Parametrique (bloc gratuit - post amp)

| Param          | Valeur    |
|----------------|-----------|
| Low Freq       | 120 Hz    |
| Low Q          | 0.7       |
| Low Gain       | -1.5 dB   |
| Mid Freq       | 1.2 kHz   |
| Mid Q          | 1.5       |
| Mid Gain       | +2.5 dB   |
| High Freq      | 4.0 kHz   |
| High Q         | 0.7       |
| High Gain      | +2.0 dB   |
| Low Cut        | Off       |
| High Cut       | Off       |
| Level          | 0.0 dB    |
| Etat par defaut| ON        |

**Role** : Sculpture tonale permanente (pas un boost, un EQ correctif).
Low a -1.5 dB sur 120 Hz (Q large 0.7) = nettoie le bas en strumming,
evite le boomy. Mid a +2.5 dB sur 1.2 kHz (Q 1.5, plus serre) =
presence et definition, la guitare coupe dans le mix (essentiel pour
le strumming folk-rock). High a +2.0 dB sur 4 kHz (Q large 0.7) = air
et brillant, le cote "acoustique" du son. Low Cut et High Cut Off car
pas necessaires ici (le cab s'en charge au casque, et en sortie ampli
le HP filtre naturellement). ON par defaut car c'est un EQ de base,
pas un boost.

### Pedale d'expression

| Assignation    | Volume (post-amp, pre-effets) |
|----------------|-------------------------------|
| Heel (min)     | 0%                            |
| Toe (max)      | 100%                          |

Note : Peut etre switchee en Wah via le toe switch integre si besoin.

---

## Configuration STOMP (6 Footswitches en mode STOMP)

| FS1              | FS2              | FS3                | FS4               | FS5                        | FS6                    |
|------------------|------------------|--------------------|-------------------|----------------------------|------------------------|
| Chorus (Bloc 3)  | Tremolo (Bloc 4) | Reverb (Bloc 6)    | Cab 1x12 (Bloc 7) | Comp (Bloc 1)             | Delay (Bloc 5)         |
| CHORUS ON/OFF    | TREM ON/OFF      | REVERB ON/OFF      | CAB SIM ON/OFF    | COMP ON/OFF                | DELAY ON/OFF           |

**Rangee du haut (FS1-FS3)** : effets de modulation et spatialisation
**Rangee du bas (FS4-FS6)** : utilitaires

### Detail des assignations

- **FS1 - Chorus** : Active le 70s Chorus. Pour Torn, Runaway Train, Kiss Me.
- **FS2 - Tremolo** : Active le Harmonic Tremolo. Effet vintage en bonus.
- **FS3 - Reverb** : Coupe/active la reverb. ON par defaut. A couper si tu
  veux un son 100% sec.
- **FS4 - Cab Sim** : Active le cab pour casque. OFF = sortie ampli.
- **FS5 - Comp** : Coupe le compresseur. Utile si tu veux plus de dynamique
  brute sur certains morceaux (CCR par ex.).
- **FS6 - Delay** : Active le delay. Independant de la reverb.

---

## Guide des sons par morceau

| Morceau                     | FS1 (Chorus) | FS2 (Trem) | FS3 (Reverb) | FS5 (Comp) | FS6 (Delay) | Description son                              |
|-----------------------------|:---:|:---:|:---:|:---:|:---:|----------------------------------------------|
| **Son de base (defaut)**    | OFF | OFF | ON  | ON  | OFF | Clean compresse, reverb ON, EQ sculpted      |
| This Is the Life            | OFF | OFF | ON  | ON  | OFF | Son de base tel quel — strumming percussif   |
| Save Tonight                | OFF | OFF | ON  | ON  | OFF | Son de base — groove et dynamique            |
| Mr. Jones                   | ON  | OFF | ON  | ON  | ON  | Chorus + delay = arpege large et profond     |
| Have You Ever Seen the Rain | OFF | OFF | ON  | OFF | OFF | Comp OFF, reverb seule — twang brut, direct |
| Runaway Train               | ON  | OFF | ON  | ON  | ON  | Chorus + delay, son emotive et enveloppant   |
| Torn                        | ON  | OFF | ON  | ON  | OFF | Chorus = largeur, reverb seule suffit        |
| Kiss Me                     | ON  | OFF | ON  | ON  | ON  | Chorus + delay + reverb = arpege delicat     |

*FS4 (Cab)* : non montre dans le tableau, toujours OFF pour ampli / ON pour casque.

---

## Combinaisons bonus

| Combinaison          | FS1 | FS2 | FS6 | Resultat                                         |
|----------------------|:---:|:---:|:---:|--------------------------------------------------|
| Chorus + Tremolo     | ON  | ON  | OFF | Son psychedelique / dreampop, tres large          |
| Tremolo seul         | OFF | ON  | OFF | Pulsation vintage, cool sur arpèges lents         |
| Tremolo + Delay      | OFF | ON  | ON  | Hypnotique, style surf/indie                      |
| Tout OFF + Comp OFF  | OFF | OFF | OFF | Tele nue dans le Princeton — maximum de dynamique |

---

## Notes

- **Choix de l'ampli** : Le US Princess (Princeton) est le choix naturel
  pour ce type de clean 90s. Il a la chaleur, le headroom et le caractere
  "Fender propre" qui definit ce son. Avec ta Telecaster et le micro
  Vintage '64, c'est la combinaison classique. Note : le US Princess n'a
  pas de controle Presence dans le POD Go. Tout le brillant se regle via
  Treble (monte a 8.0 pour compenser).

- **Reverb ON par defaut** : Contrairement au preset generique ou tout est
  OFF, ici la reverb est ON d'office car 100% de ces morceaux utilisent de
  la reverb. C'est un preset clean, la reverb fait partie du son de base.

- **EQ param comme correctif** : Ici l'EQ n'est pas un boost solo mais un
  shaping permanent. Le cut de bas nettoie le strumming, le push de mediums
  fait percer la guitare, le boost d'aigus ajoute l'air "acoustique".

- **Pas de drive/overdrive** : Ce preset est volontairement 100% clean.
  Si tu veux du crunch, utilise le preset generique V2. Avoir les deux
  presets separes evite les compromis.

- **DSP** : Tous les blocs sont legers. Le US Princess est un ampli eco,
  le 70s Chorus et le Harmonic Tremolo sont des blocs simples, les
  delay/reverb sont basiques. Aucun risque de depassement DSP.

- **Compatibilite avec le preset generique V2** : Ce preset utilise le
  meme compresseur (LA Studio Comp) et la meme logique de footswitches
  (utilitaires en rangee du bas). La transition entre les deux presets
  sera intuitive.

---

## Erreurs a eviter (troubleshooting)

| Probleme | Cause | Solution |
|----------|-------|----------|
| Son sourd, petit, sans brillant | Cab ON en sortie FX Return ampli | **Couper le cab (FS4 OFF)** — le double filtrage (cab sim + vrai HP) tue le son |
| Basses "woouf", empatement | Bass trop haute sur l'ampli | Bass a 4.5 max. Verifier aussi le Low Gain de l'EQ param (-1.5 dB) |
| Son faible, pas de volume | Master et Channel Vol trop bas | Master a 8.0, Channel Vol a 8.5. Verifier aussi l'output gain |
| Son bizarre/phase sur le tremolo | Spread a 1.0 en sortie mono | **Spread a 0.0 obligatoire** en sortie mono (FX Return) |
| Chorus qui sonne mal en mono | Stereo en mode True | Mettre Stereo en **Classic** |
| Manque de brillant/twang | Treble trop basse | Treble a 8.0 (pas de Presence sur le US Princess) |
