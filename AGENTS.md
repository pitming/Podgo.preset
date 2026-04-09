# Opencode Music - POD Go Preset Design

Ce projet contient des presets pour le Line6 POD Go. Toutes les conversations
dans ce dossier concernent la conception, l'optimisation et la documentation
de presets POD Go.

## Contexte materiel

- **Guitare** : Fender Telecaster Standard Mex, micro Fender Vintage '64
- **Multi-effets** : Line6 POD Go
- **Amplis** : Fender Champion 100 ou Boss Katana MKII (utilisation de l'etage de puissance uniquement)
- **Sortie** : FX Return ampli (etage de puissance) — pas de cab sim necessaire

## Regles de conception obligatoires

### Limites hardware POD Go

- **7 blocs** de traitement max (FX Loop converti en bloc generique)
- **1 EQ parametrique** (bloc gratuit, hors limite)
- **1 pedale d'expression** (Wah/Volume, bloc gratuit, hors limite)
- **6 footswitches** assignables en mode STOMP (FS1-FS6)
- Mode **STOMP uniquement** (pas de snapshots)
- Multi-assignation possible (un FS active/desactive plusieurs blocs)
- **Un bloc ne peut etre assigne qu'a un seul footswitch** (pas de double assignation d'un meme bloc sur deux FS differents)

### Cab Sim / IR

- Inclure un bloc cab sim/IR dans les presets pour permettre le jeu au casque
- Ce bloc est OFF par defaut (sortie prioritaire = FX Return ampli)
- Un footswitch STOMP dedie permet de l'activer pour le casque
- **Priorite absolue** : le son est optimise pour la sortie ampli (FX Return).
  Le casque est un bonus, pas la cible principale

### Ampli sans FX Return

- Si l'ampli n'a pas de FX Return (ex: Fender Champion 100) : le mentionner
  explicitement et adapter le preset (entree input classique, ajustements gain/EQ)

### DSP

- Respecter les limites DSP du POD Go
- Privilegier les blocs legers en DSP quand c'est possible
- Signaler si un preset risque de depasser les limites DSP

## Format de reponse attendu pour chaque preset

1. **Signal path complet** : ordre exact des blocs
2. **Reglages detailles** : valeurs numeriques precises pour chaque parametre de chaque bloc
3. **Configuration STOMP** : quel footswitch (FS1-FS6) fait quoi, avec multi-assignations
4. **Guide des sons** : tableau recapitulatif des combinaisons ON/OFF et du son obtenu
5. **Notes / justifications** : explication rapide de chaque choix de bloc et de reglage

## Fichier de reference

- `podgo-preset-generique-v2.md` : preset de reference (Clean/Crunch/Hard-Metal/Solo)

IMPORTANT : Avant de concevoir un nouveau preset, toujours lire ce fichier
pour s'assurer de la coherence avec les contraintes et le preset existant.

## Conventions

- Ecrire en francais
- Utiliser des tableaux Markdown pour les reglages
- Fournir des schemas ASCII pour les signal paths
- Nommer les presets de facon descriptive (ex: "Preset Generique V2", "Preset Blues")
