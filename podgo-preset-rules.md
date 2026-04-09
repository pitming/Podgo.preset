# Preconfiguration - Line6 POD Go Presets

## Guitare
- Fender Telecaster Standard Mex
- Micro : Fender Vintage '64

## Sortie
- FX Return ampli (etage de puissance uniquement) OU casque
- Un seul preset couvrant les deux cas via un switch STOMP

## Cab Sim / IR Switch
- Prevoir un switch STOMP dedie pour activer/desactiver la cab sim/IR
  - OFF = sortie ampli via FX Return (pas besoin de sim cab, le vrai HP est la)
  - ON  = sortie casque (cab sim/IR necessaire pour un son realiste)

## Cas particulier : ampli sans FX Return
- Si l'ampli n'a pas de FX Return (ex: Fender Champion 100) : le mentionner explicitement et adapter le preset (entree input classique, ajustements de gain/EQ)

## Configuration blocs (astuce FX Loop converti)
- Le FX Loop est converti en bloc generique, ce qui donne :
  - 7 blocs de traitement (effets / amp / cab)
  - 1 EQ parametrique (bloc gratuit, hors limite)
  - 1 pedale d'expression (Wah/Volume, bloc gratuit, hors limite)
- Total exploitable : 7 blocs + EQ param + pedale

## Footswitches
- Le POD Go dispose de 6 footswitches assignables en mode STOMP (FS1-FS6)
- Toutes les assignations doivent tenir sur ces 6 FS
- Multi-assignation possible (un FS active/desactive plusieurs blocs)

## Regles de conception
- Respecter les limites DSP du POD Go (7 blocs avec FX Loop converti)
- Fournir l'ordre exact des blocs dans le signal path
- Donner des reglages precis (valeurs numeriques) pour chaque bloc
- Configuration en mode STOMP uniquement (pas de snapshots)
- Justification rapide de chaque choix de bloc/reglage

## Format de reponse attendu
1. Ordre des blocs (signal path complet)
2. Reglages detailles de chaque bloc
3. Configuration STOMP (quel footswitch fait quoi)
4. Notes / justifications
