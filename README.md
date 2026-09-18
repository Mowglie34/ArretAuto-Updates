# Arrêt Auto — Mises à jour

## 🧠 Description

**Arrêt Auto** est un utilitaire simple et moderne permettant de programmer l’arrêt automatique de votre PC sous Windows, avec une interface sombre et un compte à rebours bien visible.

Vous définissez un délai (en minutes), et le système s’arrête automatiquement à l’heure indiquée.  
Un mini-compteur flottant (optionnel) et une icône dans la zone de notification vous permettent de :
- Vérifier le temps restant
- Réafficher la fenêtre principale
- Prolonger ou annuler l’arrêt
- Quitter l’application

---

## 🛠️ Utilisation

1. Lancez **Arrêt Auto**
2. Entrez une durée au format `heures:minutes:secondes` (les `:` sont fixes), ou cliquez sur les boutons rapides (`5 min` / `10 min` / `30 min` / `1 h` / `1 h 30` / `2 h`) — les valeurs s’additionnent  
   (`↺` remet le champ à `00:00:00`)
3. Cliquez sur **✅ Programmer l’arrêt** (ou appuyez sur Entrée)
4. Un compte à rebours et une barre de progression s’affichent  
   → À 5 minutes de l’extinction, le statut passe en orange
5. Vous pouvez annuler à tout moment via :
   - Le bouton **❌ Annuler l’arrêt**
   - Le mini-compteur flottant
   - Le menu de l’icône dans la zone de notification

> **Note** : Dans la dernière minute, Windows affiche sa propre fenêtre native d’arrêt.  
> Si l’application est fermée de force plus d’une minute avant l’échéance, l’arrêt n’aura pas lieu.

---

## 💡 Mini-compteur flottant

- Activable/désactivable depuis la fenêtre principale (réglage mémorisé)
- Reste visible même si la fenêtre principale est fermée
- Déplaçable librement
- Actions disponibles : +5 / +15 / +30 min, Annuler, Réafficher la fenêtre, Masquer

---

## 🔄 Mises à jour automatiques

L’application vérifie automatiquement au démarrage si une nouvelle version est disponible (silencieusement si vous êtes à jour).

- Bouton **🔄 Mises à jour** dans l’aide pour forcer une vérification
- Les notes de version s’affichent en cas de mise à jour
- Le fichier est vérifié (SHA256) avant installation
- Impossible d’installer une mise à jour pendant qu’un arrêt est en cours

---

## 🗑️ Désinstallation

1. Panneau de configuration → Applications  
2. Ou raccourci **🗑️ Désinstaller Arrêt Auto** dans le menu Démarrer  
3. Ou lancez `unins000.exe` dans le dossier d’installation

---

## 🔒 Confidentialité

Aucune donnée personnelle n’est collectée.  
L’application se connecte uniquement à GitHub au démarrage pour vérifier les mises à jour (aucune information n’est transmise).  
Le reste du fonctionnement ne nécessite pas de connexion internet.

---

## 📥 Télécharger la dernière version

👉 **[Télécharger Arrêt Auto](https://github.com/Mowglie34/ArretAuto-Updates/releases/latest)**
