<div align="center">

# Shadow Tool

**Boîte à outils système pour Windows, dans une interface terminal au style cyberpunk.**

[![Version](https://img.shields.io/github/v/release/ShadowForge-Off/ShadowTool?label=version&color=red)](https://github.com/ShadowForge-Off/ShadowTool/releases/latest)
[![Téléchargements](https://img.shields.io/github/downloads/ShadowForge-Off/ShadowTool/total?color=orange)](https://github.com/ShadowForge-Off/ShadowTool/releases)
![Plateforme](https://img.shields.io/badge/plateforme-Windows%2010%20%7C%2011-blue)

### [⬇️ Télécharger la dernière version](https://github.com/ShadowForge-Off/ShadowTool/releases/latest)

</div>

---

## C'est quoi ?

Shadow Tool regroupe dans un seul `.exe` les outils dont on a besoin au quotidien pour
**surveiller, nettoyer et optimiser son PC** : infos matérielles, moniteur de ressources,
outils réseau, nettoyage des fichiers temporaires, libération de RAM, mode gaming…

Aucune installation : on télécharge, on lance, c'est prêt.

## Fonctionnalités

| N° | Module | Ce qu'il fait |
|----|--------|---------------|
| 01 | 📊 **Informations système** | OS, architecture, processeur, cœurs CPU, RAM et disque |
| 02 | 🐍 **Outils Python** | Lister / installer des modules pip, lancer un script Python |
| 03 | 🌐 **Outils réseau** | Ping, configuration IP, test de connexion Internet |
| 04 | 📁 **Gestionnaire de fichiers** | Contenu du dossier courant, tailles et statistiques |
| 05 | 📈 **Moniteur système** | Usage CPU / RAM / disque en direct, top 5 des processus |
| 06 | 🚀 **Optimizer** | Nettoyage PC, Boost RAM, gestion du démarrage, Mode Gaming |
| 07 | 🔄 **Mises à jour** | Vérifie et installe automatiquement la dernière version |
| 08 | ⚙️ **Paramètres** | Version, infos système et modules disponibles |

### 🚀 Optimizer en détail

- **Nettoyage PC** : supprime les fichiers temporaires de Windows et le cache des navigateurs
- **Boost RAM** : libère la mémoire inutilisée par les processus en arrière-plan
- **Gestion du démarrage** : liste et désactive les programmes lancés au démarrage de Windows
- **Mode Gaming** : ferme les applications gourmandes, coupe les notifications et active le mode performances

> 💡 Lance Shadow Tool **en tant qu'administrateur** (clic droit → *Exécuter en tant qu'administrateur*) pour profiter de toutes les optimisations.

### 🔄 Mises à jour automatiques

Le menu **07** compare ta version à la dernière release publiée ici, puis télécharge et
installe la nouvelle version en un clic. L'application redémarre toute seule.

## Installation

1. Va dans les [**Releases**](https://github.com/ShadowForge-Off/ShadowTool/releases/latest)
2. Télécharge **`Shadow Tool.exe`**
3. Double-clique dessus

> ⚠️ **Avertissement Windows SmartScreen** : l'exécutable n'est pas signé numériquement,
> Windows peut donc afficher « Windows a protégé votre ordinateur ».
> Clique sur **Informations complémentaires → Exécuter quand même**.

## Utilisation

Au lancement, tape le numéro du module voulu (`01` à `08`) puis **Entrée**.
Tape `00` pour revenir en arrière ou quitter.

```
┌─[shadow-tool@system]─[22:43:23]
└──> 06
```

## Configuration requise

- Windows 10 ou 11 (64 bits)
- Aucune dépendance : Python n'est **pas** nécessaire (sauf pour le module 02 « Outils Python »)
- Connexion Internet uniquement pour les mises à jour et les outils réseau

---

<div align="center">

© 2024-2026 Shadow Tool Team

</div>
