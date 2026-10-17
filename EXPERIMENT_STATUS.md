# Visible Arsenal 0.4.35 — remplacement expérimental de CORE

Objectif : conserver toutes les fonctionnalités de la v0.4.33 tout en remplaçant uniquement `PlayerModel.putAttachment` / `removeAttachment` par un `NativeAttachmentEngine` basé sur `ModelComponent` natif.

**Attention : le code source complet de cette version n'a pas encore été importé dans le dépôt GitHub.** L'archive expérimentale a été produite séparément dans la conversation ChatGPT.

Contraintes : pas de copie du code CORE, pas de modification de l'inventaire par le moteur cosmétique, apparence (cape, vêtements, armure) à vérifier en jeu. En cas de modification externe du modèle, ne pas écraser l'apparence.

La compilation Java 25 et la sécurité du rangement virtuel après crash restent à vérifier. Tester uniquement sur un monde de test, avec objets sans valeur.
