# Conception et développement de Distributed File Replicator, un système de réplication automatique de fichiers entre plusieurs nœuds: Cas de Debian

# Objectifs:
1. Comprendre la réplication, la consistance, la propagation.
2. Apprendre les mécanismes de synchronisation distribuée.
3. Implémenter un système proche de rsync.

# Fonctionnalités attendues
1. Un répertoire "source" → modifié (création, suppression, mise à jour).
2. Ces changements sont propagés automatiquement aux nœuds répliqués.
3. Détection : nouveaux fichiers, fichiers modifiés, fichiers supprimés
4. Stratégies de synchronisation :
push (source → destinations)
pull (destinations → source)

# NB: README à mettre à jour progressivement par l'équipe.
