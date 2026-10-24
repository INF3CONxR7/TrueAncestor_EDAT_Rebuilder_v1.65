# TrueAncestor EDAT Rebuilder v1.65

**TrueAncestor EDAT Rebuilder** est un utilitaire Windows pour **PlayStation 3**, créé par **JjKkYu**. Il permet de déchiffrer, de chiffrer et de reconstruire des fichiers `EDAT` et `SDAT` utilisés par les contenus PS3.

**Version :** 1.65  
**Plateforme :** PS3  
**Système :** Windows  
**Développeur original :** JjKkYu

## Fonctionnalités

- Déchiffrement et chiffrement des fichiers `EDAT` et `SDAT` pris en charge.
- Reconstruction rapide des fichiers `EDAT` et `SDAT`.
- Mode de reconstruction personnalisée pour les fichiers `EDAT`.
- Traitement de plusieurs fichiers par lots et prise en charge des sous-dossiers.
- Prise en charge des fichiers `EDAT` compressés.
- Ajout et recherche de clés **DevKlic** dans le fichier `dev_klics.txt`.

## Nouveautés de la version 1.65

- Ajout de la recherche automatique des clés **DevKlic** en mode par lots.
- Ajout d’une pause dans toutes les listes de fichiers.
- Correction d’un plantage lors de l’ajout d’une clé avec l’option **Add DevKlic**.
- Mise à jour des instructions d’utilisation.

## Utilisation

1. Téléchargez ce dépôt avec **Code → Download ZIP**, puis extrayez l’archive sur votre PC Windows.
2. Conservez une copie des fichiers originaux avant toute opération.
3. Lancez `rebuilder.exe` depuis le dossier extrait et choisissez l’action adaptée au format à traiter : déchiffrement, chiffrement ou reconstruction.
4. Sélectionnez les fichiers et renseignez les paramètres demandés en suivant les instructions fournies.
5. Vérifiez les fichiers générés avant de remplacer ceux de votre projet.

## Contenu du dépôt

Le dépôt contient la distribution binaire Windows de la version 1.65 :

- `rebuilder.exe` : programme principal.
- `tool/` : les 12 outils, bibliothèques et fichiers auxiliaires fournis avec le programme, dont `core.jar`, `core.cfg` et `dev_klics.txt`.
- `data/` : les fichiers `keys`, `ldr_curves` et `vsh_curves` nécessaires aux outils.
- `history.txt` : historique des versions fourni avec le programme.
- `edat/`, `raps/`, `sdat/` et `temp/` : dossiers de travail conservés avec des fichiers `.gitkeep`.

Conservez cette arborescence complète à côté de `rebuilder.exe`. Le moteur `tool/core.jar` utilise Java (JRE) ; sa mémoire JVM est configurée dans `tool/core.cfg`. Git ignore le contenu ajouté dans les quatre dossiers de travail ainsi que les rapports de plantage `*.stackdump`. Les sources du logiciel ne sont pas incluses dans cette distribution.

## Important

- La prise en charge dépend du format du fichier et de l’opération sélectionnée.
- La recherche automatique de **DevKlic** ne garantit pas qu’une clé adaptée sera trouvée.
- Ce dépôt n’est **pas le projet officiel** du développeur original.

## Crédits et informations

- **Développeur original :** JjKkYu
- [Fiche et historique sur PSX-Place](https://www.psx-place.com/resources/trueancestor-edat-rebuilder-by-jjkkyu.34/)
- [Fonctions et notes de version 1.65 sur PSX-Place](https://www.psx-place.com/threads/t-a-edat-rebuilder-v1-65-by-jjkkyu.3531/)

Les droits sur le logiciel restent ceux de leurs détenteurs respectifs.

