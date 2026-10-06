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

| N° | Catégorie | Ce qu'elle contient |
|----|-----------|---------------------|
| 01 | 🩺 **Santé du PC** | Note sur 100 avec conseils : espace disque, fichiers temporaires, démarrage, RAM, pilote graphique, batterie, protection système |
| 02 | 📊 **Système** | Informations, moniteur en temps réel (CPU, RAM, GPU), gestionnaire de processus, analyse disque, batterie & températures |
| 03 | 🎮 **Jeux** | Ping des serveurs de jeu, DNS le plus rapide, profils gaming, nettoyage des caches de jeux, Mode Gaming |
| 04 | 🚀 **Optimizer** | Nettoyage PC, Boost RAM, gestion du démarrage, Mode Gaming |
| 05 | 🌐 **Réseau** | Ping, IP & MAC, test de connexion, scanner de ports |
| 06 | 🧰 **Outils** | Explorateur de fichiers, outils Python |
| 07 | 🔄 **Mises à jour** | Vérifie et installe automatiquement la dernière version |
| 08 | ⚙️ **Paramètres** | Préférences, nettoyage planifié, points de restauration, informations |

### 🩺 Santé du PC

Une note sur 100 calculée en quelques secondes, avec pour chaque point vérifié
le chemin du menu qui permet de corriger : espace libre sur C:, fichiers temporaires,
programmes au démarrage, mémoire utilisée, durée depuis le dernier redémarrage,
âge du pilote graphique, usure de la batterie, mises à jour, protection du système.

### 🎮 Jeux

- **Ping des serveurs** : latence, minimum et gigue vers FiveM, Steam, Epic Games et Riot, plus **ton propre serveur FiveM** (ip:port mémorisé)
- **DNS & réseau** : compare ton DNS actuel à Cloudflare, Google et Quad9, vide le cache DNS, passe au plus rapide (en administrateur) avec un bouton **« Restaurer mon DNS »**
- **Profils gaming** : choisis les applications à fermer (ex. profil *Streaming* qui garde Spotify), les notifications, le plan d'alimentation, la veille et le Boost RAM
- **Nettoyage des jeux** : caches FiveM (jamais les fichiers du jeu), Steam, Epic, Riot et shaders NVIDIA / AMD / DirectX, avec la taille de chaque dossier. Un jeu ouvert n'est jamais nettoyé

### 📊 Système

- **Processus** : tri CPU / RAM, recherche, fermeture d'un programme bloqué (les processus vitaux de Windows sont protégés)
- **Analyse disque** : dossiers les plus lourds (navigation dossier par dossier) et 20 plus gros fichiers. Les fichiers OneDrive restés dans le cloud ne sont pas comptés
- **Batterie & températures** : usure réelle de la batterie et cycles de charge, température / utilisation / ventilateur des cartes NVIDIA, température du processeur quand Windows la fournit

### 🚀 Optimizer

- **Nettoyage PC** : fichiers temporaires de Windows et caches des navigateurs (jamais tes documents), après confirmation
- **Boost RAM** : libère la mémoire des processus et purge le cache mémoire de Windows (en administrateur), le maximum en un seul lancement
- **Gestion du démarrage** : active / désactive les programmes au démarrage, de façon réversible (comme le Gestionnaire des tâches)
- **Mode Gaming** : applique ton profil gaming. Se désactive en un clic et restaure tes réglages

### ⚙️ Paramètres

- **Préférences** : animation de démarrage (complète, courte ou désactivée), vérification automatique des mises à jour, mode 16 couleurs pour les vieux écrans
- **Nettoyage planifié** : Shadow Tool nettoie tout seul chaque jour ou chaque semaine (tâche Windows, sans administrateur), même si le PC était éteint à l'heure prévue
- **Points de restauration** : création manuelle, et **automatique avant chaque action qui modifie Windows** (Mode Gaming, démarrage, DNS)

> 💡 Lance Shadow Tool **en tant qu'administrateur** (clic droit → *Exécuter en tant qu'administrateur*) pour profiter de toutes les optimisations.

### 🔄 Mises à jour automatiques

Shadow Tool vérifie en arrière-plan au démarrage si une nouvelle version existe. Le menu **07**
la télécharge et l'installe en un clic, puis l'application redémarre toute seule.

### 🎨 Interface

- Animation de démarrage avec détection du matériel, puis révélation du logo
- Thème violet / néon, cadres et jauges colorées
- L'affichage s'adapte quand on agrandit la fenêtre

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
shadow@tool » 06
```

## Configuration requise

- Windows 10 ou 11 (64 bits)
- Aucune dépendance : Python n'est **pas** nécessaire (sauf pour le module 02 « Outils Python »)
- Connexion Internet uniquement pour les mises à jour et les outils réseau

---

<div align="center">

© 2024-2026 Shadow Tool Team

</div>
