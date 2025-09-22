# Installer Windows 11 sans compte Microsoft

**Objectif :** Installer Windows 11 sans être obligé de créer ou utiliser un compte Microsoft.

---

## ✅ Prérequis

* Un PC compatible Windows 11
* Une clé USB bootable ou ISO Windows 11
* Réseau **débranché** (Ethernet et Wi‑Fi désactivés)

---

## 🛠️ Étapes détaillées

1. **Déconnectez** tout accès réseau (Ethernet + Wi‑Fi).
2. Lancez l’installation de Windows 11.
3. Avancez jusqu’à l’écran **Réseaux**.
4. Appuyez sur **Shift + F10** → ouvre l’invite de commandes (CMD).
5. Dans CMD, tapez :

   ```
   OOBE\BYPASSNRO
   ```
6. Le PC redémarre automatiquement.
7. Reprenez l’installation → à l’écran Réseaux, cliquez **Je n’ai pas Internet**.
8. Continuez l’installation : un **compte local** sera proposé.

---

## ℹ️ Remarques

* Cette méthode contourne uniquement l’étape OOBE (Out-Of-Box Experience).
* Pensez à **sauvegarder vos fichiers** avant l’installation.
* Après installation, vous pouvez reconnecter Internet et lier un compte Microsoft si besoin.
* N’oubliez pas d’installer les pilotes et mises à jour Windows Update.

---

## ⚠️ Avertissements

* ❌ Ne pas utiliser pour contourner des restrictions professionnelles.
* 📜 Les **conditions d’utilisation Microsoft** s’appliquent toujours.
* 🔒 Méthode donnée à titre informatif, susceptible de changer si Microsoft met à jour son processus.
