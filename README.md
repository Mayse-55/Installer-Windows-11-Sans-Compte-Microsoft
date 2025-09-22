
**BUT** : procédure permettant d’installer Windows 11 sans créer ou se connecter à un compte Microsoft (méthode OOBE). À utiliser à vos risques — sauvegardez toujours vos données et respectez les conditions d'utilisation de Microsoft.

## Prérequis

* Un PC compatible Windows 11.
* Un support d'installation (USB) ou une image ISO de Windows 11.
* Connexion réseau **débranchée** au moment indiqué.

## Étapes

1. Ne pas brancher l’ordinateur aux réseaux (câble Ethernet et Wi‑Fi désactivés ou déconnectés).
2. Démarrer l’installation de Windows 11 depuis le support d’installation.
3. Suivre l’installation jusqu’à l’écran **Réseaux / Connectez-vous à Internet**.
4. À cet écran, appuyer sur **Shift + F10** pour ouvrir l’invite de commandes (CMD).
5. Dans la fenêtre CMD, taper la commande suivante puis appuyer sur Entrée :

```
OOBE\BYPASSNRO
```

6. L’ordinateur redémarre automatiquement.
7. Reprendre l’installation depuis le début jusqu’à l’écran **Réseaux**. Cliquer sur **Je n’ai pas internet** ou continuer sans connexion.
8. Poursuivre l’installation normalement : l’assistant proposera maintenant la création d’un compte local ou l’option pour continuer sans compte Microsoft.

## Remarques et conseils

* Cette méthode contourne l’obligation de créer un compte Microsoft pendant l’OOBE (Out-Of-Box Experience). Elle est fournie à titre informatif et peut ne plus fonctionner si Microsoft modifie le processus d’installation.
* Sauvegardez toujours vos fichiers avant toute opération d’installation/réinstallation.
* Après l’installation, vous pouvez reconnecter le réseau et, si nécessaire, créer ou lier un compte Microsoft ultérieurement.
* Pensez à installer les pilotes et les mises à jour Windows Update.

## Avertissements

* N’utilisez pas cette méthode pour contourner des restrictions d’entreprise ou des politiques informatiques gérées par un administrateur.
* Les conditions d’utilisation de Microsoft s’appliquent toujours. Cette procédure n’enlève pas les obligations légales ou contractuelles.

---

*Fichier prêt à être ajouté à un dépôt GitHub : copiez ce `README.md` à la racine du dépôt.*
