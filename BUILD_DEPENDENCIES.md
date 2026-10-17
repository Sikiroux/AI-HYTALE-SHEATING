# Dépendance HytaleServer.jar

Les builds Visible Arsenal doivent utiliser une copie locale du serveur Hytale, placée dans `libs/HytaleServer.jar` (dans le dossier racine du projet Gradle).

La copie fournie en conversation a été validée comme archive JAR (SHA-256 `23f71f03763422ce7c04df191db49cd0e7d87d43b12baad75c43fdc202410aff`). Le fichier ne doit pas être commité dans ce dépôt public sans autorisation de redistribution.

Le JAR est utilisé comme dépendance de compilation (`compileOnly`) et ne doit pas être intégré au JAR du mod. Les versions livrées doivent signaler la version d'API attendue et être compilées/testées séparément avant publication.
