# Contrat des modèles 3D

Le jeu fonctionne intégralement avec ses silhouettes procédurales. Pour remplacer une silhouette, déposer un fichier GLB au chemin déclaré dans `manifest.json`, puis passer `enabled` à `true`.

Contraintes : Y vers le haut, personnage regardant +Z, 1 unité = 1 mètre, pivot au sol, matériaux PBR metallic-roughness. Les animations reconnues sont `Idle`, `Move`, `Attack`, `Hit`, `Dodge`, `Death` et, pour les boss, `Cast`.
