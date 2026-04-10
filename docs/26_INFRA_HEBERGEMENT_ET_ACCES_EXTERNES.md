## Destination finale du projet
L’application n’est pas pensée comme un simple prototype local.
Elle doit être préparée pour un déploiement sur l’infrastructure privée d’ARTAG.

## Exigences de destination
L’outil doit être conçu pour :
- être déployé sur le serveur privé d’ARTAG
- être accessible aux salariées autorisées de l’association
- fonctionner de manière fiable en environnement multi-utilisatrices
- être préparé pour une interconnexion avec Insertis
- pouvoir être consulté depuis l’extérieur de manière sécurisée
- limiter au maximum les problèmes de connexion, d’authentification et de session

## Contraintes d’architecture
L’application doit être pensée dès le départ pour un déploiement de type production.

Elle doit donc être compatible avec :
- un hébergement serveur privé
- un reverse proxy
- une authentification centralisée ou fédérée
- une gestion propre des sessions
- des droits d’accès par profil
- une journalisation des connexions et des actions sensibles

---

# PROMPT GLOBAL FINAL POUR CODEX

Tu travailles sur un projet déjà entièrement cadré.

Tu ne réinventes rien.
Tu ne simplifies rien.
Tu ne renommes rien.
Tu ne modifies ni la logique métier, ni l’architecture, ni les intitulés validés.
Tu n’interprètes pas.
Tu exécutes strictement les spécifications du dossier `docs/`.

Le projet complet est défini par l’ensemble des fichiers `docs/`.
Ils sont tous obligatoires.

En cas de doute :
- tu conserves l’existant
- tu n’inventes rien
- tu n’improvises rien

Ta mission :
mettre en œuvre fidèlement le projet complet tel qu’il est spécifié, sans écart.

Tu travailles dans l’ordre défini dans `docs/23_ORDRE_DE_TRAVAIL.md`.
Tu ne passes pas à l’étape suivante tant que l’étape en cours n’est pas conforme.

Le vrai logo ARTAG doit être utilisé.
La palette validée doit être respectée.
La structure complète du projet doit être conservée.

Je veux une exécution fidèle du projet complet, à la moindre virgule, sans erreur et sans interprétation.
