# Holster Magnétique pour Manette Meta Quest 3

Ce projet a pour objectif la conception d’un **holster imprimé en 3D** pour les manettes du casque **Meta Quest 3**, utilisant des **aimants** pour maintenir la manette en place de manière fiable, tout en préservant sa fonctionnalité.

---

## 📁 Structure du dépôt

### `3DModel/`
Ce dossier contient l’ensemble des **modèles 3D (.STL)** créés au cours du développement.

- Les fichiers sont **classés dans l’ordre chronologique de création**.
- Chaque fichier représente une version intermédiaire ou finale d’un prototype test.

### `Projet_Blender.blend1`
Il s'agit du **fichier source principal du projet**, modélisé sous **Blender**. Il contient l’ensemble des objets 3D utilisés pour la création et l’assemblage du holster.

Voici les principaux objets présents dans ce fichier :

| Objet Blender             | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `Batterydoor_07`         | Dernière version de la backdoor modifiée.                                  |
| `Clip_3ligne`            | Dernière version du clip avec **3 lignes d’aimants**.                       |
| `Clip_Unchanged`         | Version originale du clip, **sans modifications**.                          |
| `cube`                   | Ajout destiné à venir se fixer sur la **backdoor**.                         |
| `Cylinder_ForHole`       | Cylindre utilisé pour **percer les emplacements d’aimants** dans les modèles. |
| `meta-quest3-controller` | Représentation 3D du **contrôleur Quest 3**, servant de référence de forme.  |

> 💡 Le projet Blender permet de générer ou modifier les fichiers `.stl` à tout moment en fonction des ajustements nécessaires.

---

## 🔧 Objectif technique

- Conception d’un holster compatible Quest 3.
- Intégration d’**aimants permanents** pour fixation magnétique.
- Tests d’agencement (1, 2 ou 3 lignes d’aimants).
- Réglage des dimensions pour insertion sans chaleur (éviter la perte de magnétisme).
- Validation de l’**ergonomie et de la tenue en mouvement**.

---

## 🧲 Ressources utiles pour l’amélioration

Pour améliorer encore l’efficacité magnétique, il est recommandé d’utiliser :

- des **aimants plats** pour une meilleure surface de contact,
- ou des **aimants plus puissants** (type N52 ou supérieur).

📦 Liens utiles :
- [magnetmontreal.com](https://magnetmontreal.com/fr/)

Il est aussi possible de s’inspirer du **système magnétique des manettes Nintendo Switch 2**, qui combine forme guidée et magnétisme réparti.

---
✅ *Pour plus de détails techniques et les étapes du développement, consultez les pages du Wiki associées à ce dépôt.*
