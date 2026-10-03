# Bottleneck Analyzer

Ton CPU freine-t-il ta carte graphique ? Un test de 2 minutes, un verdict clair, des conseils concrets.

**[Télécharger la dernière version](../../releases/latest)** · [Site](https://bottleneck-pc.vercel.app)

## Utilisation

1. Télécharge `Bottleneck.Analyzer.exe` dans [Releases](../../releases/latest).
2. Lance-le : aucune installation, aucun compte.
3. Ferme les jeux et les applis lourdes, puis clique sur **Lancer le benchmark** (environ 2 min).

Windows 10 ou 11, 64 bits.

## Avertissement Windows

Au premier lancement, Windows peut afficher « Windows a protégé votre ordinateur » : c'est normal pour un logiciel
récent pas encore signé. Clique sur **Informations complémentaires** puis **Exécuter quand même**.

Pour vérifier que le fichier n'a pas été modifié, compare son empreinte SHA-256 avec celle indiquée dans la Release :

```
Get-FileHash .\Bottleneck.Analyzer.exe -Algorithm SHA256
```

## Confidentialité

Rien n'est envoyé tant que tu ne cliques pas sur **Partager**. Le partage est anonyme : matériel, FPS et verdict,
sans nom, e-mail ni numéro de série. Détails sur [la page confidentialité](https://bottleneck-pc.vercel.app/confidentialite).

## Licence

© 2026 Bottleneck Analyzer. Tous droits réservés. Le logiciel est gratuit à l'usage ; sa copie, sa modification,
sa décompilation et sa redistribution ne sont pas autorisées. Ce dépôt ne contient pas le code source.
