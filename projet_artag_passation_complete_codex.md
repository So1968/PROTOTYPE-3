# PROJET ARTAG — PAQUET COMPLET DE PASSATION POUR CODEX

Ce document rassemble, en un seul endroit, la base de passation complète du projet pour Codex.

---

# README.md

## Objet du projet
Ce projet correspond à la mise en œuvre d’un outil de parcours et d’appui pour ARTAG.

Il s’agit d’un projet déjà cadré sur le fond, sur l’architecture, sur les contenus fonctionnels, sur l’orientation visuelle générale, sur la séparation des espaces de travail, sur la couche didactique, sur la logique de démonstration, sur la sécurité et sur la perspective de déploiement.

## Important
Ce projet ne doit pas être réinventé.

Il ne faut pas :
- changer la logique métier
- renommer les parties validées
- simplifier librement la structure
- proposer une autre direction produit
- remplacer les spécifications par une interprétation personnelle
- transformer le projet en simple maquette décorative
- transformer le projet en dashboard startup
- transformer le projet en formulaire administratif compact

## Principe de travail
Le projet doit être exécuté fidèlement à partir :
- du code existant
- des assets réels
- des fichiers contenus dans le dossier `docs/`

En cas de doute :
- conserver l’existant
- ne rien inventer
- ne pas improviser

## Structure du projet
- `src/` : code de l’application
- `public/` : assets publics, dont le logo ARTAG
- `docs/` : spécifications complètes et obligatoires du projet

## Entrées principales validées
- Parcours social / socio-professionnel
- Appui TNS
- Direction

## Assets obligatoires
Le vrai logo ARTAG doit être utilisé :
- fichier : `public/logo-artag.png`
- ne pas déformer
- ne pas recolorer
- vérifier qu’il s’affiche réellement

## Signature à conserver
Outil conçu par Sofia de los Rios dans le cadre de sa mission

Toujours écrire :
- Sofia avec un f
- de los Rios

## Règle finale
Aucune partie du projet ne doit être modifiée hors des spécifications fournies dans `docs/`.

---

# docs/00_REGLE_ABSOLUE.md

## Principe général
Ce projet repose sur une base déjà stabilisée.

Tu ne réinventes rien.
Tu ne changes pas la logique métier.
Tu ne modifies pas les intitulés validés.
Tu ne proposes pas une autre direction visuelle.
Tu ne remplaces pas la structure par une interprétation personnelle.

## Ce qui est attendu
Tu exécutes fidèlement les spécifications.
Tu corriges et mets en œuvre.
Tu n’improvises pas.
Tu ne simplifies pas.
Tu ne renommes pas.
Tu ne déplaces pas arbitrairement les éléments validés.

## En cas de doute
- tu conserves l’existant
- tu n’inventes rien
- tu ne reformules pas librement
- tu n’ajoutes pas de solution créative non demandée
- tu ne supprimes rien sans consigne explicite

## Interdits absolus
- réinventer la structure du projet
- remplacer les intitulés validés
- modifier la logique métier
- transformer le projet en site vitrine
- transformer le projet en dashboard startup
- remplacer une consigne précise par une approximation
- livrer une réinterprétation au lieu d’une exécution fidèle

## Règle de travail
Le projet doit être réalisé dans l’ordre prévu.
On ne passe pas à l’étape suivante tant que l’étape en cours n’est pas conforme.

## Objectif
Obtenir une exécution fidèle du projet complet, sans erreur, sans dérive et sans interprétation.

---

# docs/01_VISION_GENERALE.md

## Nature du projet
Il s’agit d’un outil de parcours et d’appui pour ARTAG.

Ce n’est pas :
- un simple formulaire
- un site vitrine
- un dashboard startup
- un tableur amélioré
- une interface décorative
- un prototype purement graphique déconnecté du fond

## Finalité générale
Le projet vise à proposer un support structuré permettant de mieux :
- repérer les situations au départ
- approfondir certains points selon les besoins
- transmettre les informations utiles
- soutenir la continuité en cas de relais ou d’absence
- orienter les situations vers le TNS quand cela est pertinent
- rendre plus lisible le travail réellement effectué
- outiller la direction sur une lecture d’ensemble plus claire

## Logique de fond
Le projet repose sur :
- un socle autonomie au premier entretien
- des modules spécifiques ensuite selon les besoins
- un dossier unique partagé
- un espace professionnel réservé
- une traçabilité des actions et des évolutions
- un historique des versions sur les éléments sensibles
- une vue direction / pilotage séparée
- une couche didactique embarquée
- un mode travail et un mode démonstration

## Alignement
Sur le fond, le projet est aligné avec :
- le référentiel
- le projet social ARTAG
- les attendus du comité des financeurs

## Problème auquel le projet répond
Le projet répond à un besoin de clarification sur le plan opérationnel, notamment sur :
- les fonctions
- l’accompagnement
- la transmission des situations
- la continuité en cas de relais ou d’absence
- l’orientation vers le TNS
- la lisibilité du travail réel

## Intention générale
L’objectif n’est pas d’ajouter un formulaire de plus.
L’objectif est de proposer une trame commune de suivi des situations, plus lisible, plus structurée et plus utile au travail réel.

## Effet recherché
Le projet doit permettre :
- une meilleure lecture partagée des situations
- une meilleure continuité de service
- une meilleure transmission
- une meilleure articulation entre repérage, approfondissement et orientation
- une meilleure visibilité du travail réalisé
- une lecture direction plus claire sans exposer les notes sensibles

---

# docs/02_ARCHITECTURE_GLOBALE.md

## Entrées principales validées
L’outil comporte 3 accès d’entrée :
1. Parcours social / socio-professionnel
2. Appui TNS
3. Direction

## Organisation générale

### A. Accueil
La page d’accueil doit orienter vers :
- le parcours social / socio-professionnel
- l’appui TNS
- l’accès Direction

### B. Parcours principal
Le parcours principal comprend :
- le bloc identité
- l’historique
- le socle autonomie
- la synthèse courte
- la note de continuité
- l’accès aux modules
- la chronologie des actions
- l’espace professionnel réservé selon les droits

### C. Appui TNS
L’entrée TNS est articulée au tronc commun.
Elle ne constitue pas un parcours séparé au sens institutionnel.
Elle permet un appui spécialisé sur les situations d’activité indépendante.

### D. Direction / pilotage
La vue Direction est séparée du parcours usager.
Elle comprend :
- un tableau de bord principal
- une analyse détaillée
- un accès dossier de secours
- des indicateurs agrégés
- des indicateurs de vigilance à manier avec prudence

## Tronc commun validé
Le tronc commun comprend :
- bloc identité
- socle autonomie
- synthèse courte
- note de continuité
- logique d’ouverture des modules
- traçabilité automatique
- historique des versions

## Dossier unique partagé
Le dossier unique partagé contient :
- identité
- historique
- socle autonomie
- freins repérés
- points d’appui
- modules ouverts
- synthèse courte
- note de continuité
- prochaines étapes utiles

## Espace professionnel réservé
L’espace professionnel réservé contient :
- bloc professionnel / relation d’aide
- hypothèses de travail
- posture professionnelle
- notes sensibles
- brouillons

## Modules validés

### Modules principaux
- Droits / démarches
- Habitat / parcours résidentiel
- TNS
- Budget
- Santé
- Écrit / illettrisme

### Modules secondaires
- Numérique
- Mobilité
- Vie familiale
- Projet professionnel détaillé

## Logique d’ouverture des modules
Le socle autonomie produit une lecture des axes :
- très fragile
- fragile
- à surveiller
- plutôt stabilisé

À partir de cette lecture :
- l’outil peut suggérer des modules
- l’outil peut recommander des modules
- la professionnelle garde la décision d’ouverture

## Mode démonstration
Le projet prévoit un mode démonstration permettant d’afficher :
- la source documentaire
- la page
- une citation courte
- la traduction dans l’outil

## Ordre logique de construction
1. architecture générale
2. profils d’accès
3. dossier unique partagé + espace réservé
4. parcours visuels
5. bloc identité
6. socle autonomie
7. bloc professionnel
8. synthèse courte + note de continuité
9. modules principaux
10. modules secondaires
11. traçabilité
12. historique des versions
13. vue direction
14. sécurité
15. mode démonstration
16. mise en forme visuelle

---

# docs/03_PROFILS_ACCES_DROITS.md

## Profils principaux
- professionnelle
- professionnelle relais
- professionnelle appui TNS
- direction
- admin technique

## Professionnelle
Peut voir :
- le dossier partagé
- le socle autonomie
- la synthèse courte
- la note de continuité
- les modules utiles à son travail
- la chronologie des actions
- ses propres contenus réservés selon les droits

Ne voit pas :
- les notes sensibles réservées aux collègues
- les couches techniques d’administration
- les indicateurs direction

## Professionnelle relais
Peut voir :
- le dossier partagé
- l’historique utile à la continuité
- la synthèse courte
- la note de continuité
- les modules ouverts utiles à la reprise

Ne voit pas par défaut :
- l’historique détaillé des notes sensibles
- les espaces réservés non partagés

## Professionnelle appui TNS
Peut voir :
- le dossier partagé
- les éléments utiles à la compréhension de la situation
- le module TNS
- les croisements utiles avec droits, budget, habitat, écrit, numérique

Ne voit pas :
- les notes sensibles privées des collègues
- la totalité des espaces réservés non pertinents

## Direction
Peut voir :
- la vue direction / pilotage
- les indicateurs agrégés
- l’accès dossier de secours
- les éléments du dossier partagé en cas de besoin justifié

N’a pas accès par défaut :
- aux notes sensibles détaillées
- à l’espace réservé complet des professionnelles

## Admin technique
Peut voir :
- journaux techniques
- événements d’accès
- informations nécessaires à la maintenance

Ne doit pas lire par défaut :
- le contenu métier détaillé
- les notes sensibles
- les contenus réservés sans nécessité technique réelle

---

# docs/04_ACCUEIL.md

## Contenu obligatoire de la page d’accueil
- le bon logo ARTAG en haut à gauche
- un titre d’outil
- un sous-titre discret
- deux grandes entrées principales
- un accès Direction discret
- un chemin de parcours discret
- une ambiance générale calme, lumineuse, lisible, chaleureuse et professionnelle

## Entrées validées
- Parcours social / socio-professionnel
- Appui TNS
- Direction

## Carte gauche
Écrire exactement sur 2 lignes, sans slash :

Parcours social
socio-professionnel

Consignes :
- les deux lignes doivent être centrées
- “Parcours social” doit être centré au-dessus de “socio-professionnel”
- la composition doit être stable et équilibrée
- la deuxième ligne ne doit pas paraître décalée ou flottante

## Carte droite
Appui TNS doit être :
- centré horizontalement
- centré verticalement
- stable visuellement dans sa carte

## Accès Direction
- petite porte ancienne discrète
- sobre
- élégante
- séparée visuellement des deux grandes cartes

## Chemin
- fin
- souple
- discret
- élégant
- non enfantin
- non envahissant

## Hérisson
Le hérisson n’est pas validé en l’état.

S’il est utilisé :
- forme beaucoup plus ronde
- beaucoup moins de piquants
- dos souple, presque comme un galet
- nez très discret
- pas de pattes visibles
- pas d’œil
- pas de détail mignon
- pas d’effet animal réaliste

S’il ne fonctionne pas proprement :
- le retirer complètement
- garder seulement le chemin discret

---

# docs/05_DOSSIER_OUVERT.md

## Structure générale
- bandeau avec logo ARTAG
- grand bloc identité
- chemin de parcours
- colonne gauche = dossier partagé
- colonne droite = repères / historique / actions

## Colonne gauche
- socle autonomie
- synthèse courte
- note de continuité
- modules ouverts
- prochaines étapes utiles

## Colonne droite
- chronologie des actions
- historique
- versions précédentes
- ouverture des modules
- espace réservé selon le profil

---

# docs/06_BLOC_IDENTITE.md

## Fonction du bloc
Le bloc Identité sert à :
- ouvrir le dossier
- situer la personne dans son parcours
- donner accès à l’historique
- permettre une reprise rapide
- afficher les premiers repères utiles

## Informations visibles
- Nom
- Prénom
- Numéro Insertis
- Âge

## Repères de parcours
- date de première saisie
- date du dernier passage
- nombre d’évaluations / entretiens enregistrés
- référente principale actuelle
- professionnelles associées si besoin

## Accès rapides
- Liste des usagers
- Voir l’évolution
- Flash situation
- Retour accueil
- Continuer

---

# docs/07_SOCLE_AUTONOMIE.md

## Fonction
Le socle autonomie sert à faire un repérage global rapide au premier entretien.
Il ne remplace pas l’approfondissement.
Il prépare ensuite l’ouverture des modules spécifiques selon les besoins repérés.

## Questions du socle
1. Pour vos papiers et vos démarches, vous vous y retrouvez comment en ce moment ?
2. Pour vous organiser dans ce que vous avez à faire, vous vous en sortez comment ?
3. Pour gérer l’argent au quotidien, vous vous en sortez comment ?
4. Pour votre santé, les rendez-vous ou les soins, vous vous en sortez comment ?
5. Pour vous déplacer là où vous avez besoin d’aller, ça se passe comment pour vous ?
6. Pour les courriers, les papiers ou les démarches sur téléphone, vous vous en sortez comment ?
7. Avec tout ce que vous avez à gérer dans la famille, pour vos démarches, vous vous en sortez comment ?
8. Quand vous voulez faire avancer quelque chose pour vous, vous y arrivez comment ?

## Formule de référence
Le socle autonomie ne remplace pas l’approfondissement ; il le prépare.

---

# docs/08_SYNTHESE_COURTE.md

## Fonction
Donner une vue d’ensemble rapide de la situation.

## Rubriques
- situation globale
- difficultés principales
- points d’appui
- modules / sujets travaillés
- étape actuelle
- vigilance utile

## Règles
- format court
- pas de roman
- pas d’analyse psychologique
- pas de jugement
- pas d’éléments trop sensibles

---

# docs/09_NOTE_CONTINUITE.md

## Fonction
Permettre à une autre professionnelle de reprendre la situation immédiatement, sans avoir à relire tout le dossier.

## Rubriques
- situation en cours
- priorité immédiate
- déjà fait
- si relais / absence
- vigilance utile

## Règles
- très court
- télégraphique
- concret
- pas de jugement
- pas d’analyse sensible

## Historique
La note de continuité ne doit pas être simplement écrasée lors d’une modification.
Conserver :
- version précédente
- date et heure
- professionnelle ayant modifié

---

# docs/10_BLOC_PRO_RELATION_AIDE.md

## Statut
Bloc strictement interne à la professionnelle.
Jamais visible par l’usager.

## Fonction
Aider à :
- prendre du recul sur la relation
- objectiver ce qui se joue
- éviter les interprétations trop personnelles
- ajuster la posture professionnelle

## Axes
- entrée en relation
- expression de la demande
- réception de l’aide proposée
- possibilité de co-construction
- rapport au cadre
- posture professionnelle à privilégier

---

# docs/11_LOGIQUE_OUVERTURE_MODULES.md

## Principe général
L’ouverture des modules suit une logique mixte :
- l’outil suggère ou recommande
- la professionnelle décide
- les modules ne s’ouvrent pas de manière rigide et imposée

## Niveaux
- module suggéré
- module recommandé
- module ouvert manuellement

---

# docs/12_TRACABILITE.md

## Principe
L’outil doit garder la mémoire du travail réalisé sans demander à la professionnelle de tout ressaisir.

## À tracer automatiquement
- étapes du parcours
- socle autonomie
- modules suggérés / ouverts / reportés
- actions réalisées
- relais
- changements de référente
- impressions
- exports
- accès direction
- événements de sécurité

---

# docs/13_HISTORIQUE_VERSIONS.md

## Principe
Les éléments importants du dossier ne doivent pas être simplement écrasés lors d’une modification.

## À prévoir au minimum pour
- synthèse courte
- note de continuité
- socle autonomie
- ouverture / fermeture de modules
- changement de référente
- éléments importants du dossier unique partagé

---

# docs/14_MODULES_PRINCIPAUX.md

## Modules principaux validés
- Droits / démarches
- Habitat / parcours résidentiel
- TNS
- Budget
- Santé
- Écrit / illettrisme

---

# docs/15_MODULES_SECONDAIRES.md

## Modules secondaires validés
- Numérique
- Mobilité
- Vie familiale
- Projet professionnel détaillé

---

# docs/16_DIRECTION_PILOTAGE.md

## Vue direction
Doit être séparée des écrans de travail ordinaires.

## Contenu
- tableau de bord principal
- analyse détaillée
- accès dossier de secours
- indicateurs agrégés
- indicateurs de vigilance

---

# docs/17_INDICATEURS_DIRECTION.md

## Noyau dur recommandé
- nombre de dossiers actifs
- nombre de socles autonomie réalisés
- répartition des dossiers par étape de parcours
- nombre de situations avec freins cumulés
- poids des difficultés Droits / démarches
- poids des difficultés Habitat / parcours résidentiel
- poids des difficultés Santé
- nombre de notes de continuité créées ou mises à jour
- nombre de relais / reprises de dossiers
- nombre de situations TNS repérées
- nombre d’orientations internes
- nombre d’actions de travail réel tracées

---

# docs/18_SECURITE.md

## Exigences
- accès nominatifs
- gestion des rôles
- récupération de mot de passe
- limitation des essais
- verrouillage temporaire
- journalisation des accès sensibles
- sessions robustes
- séparation claire des droits
- architecture exploitable en production

---

# docs/19_MODE_DEMONSTRATION.md

## Principe
Le projet doit prévoir deux modes sur une même base applicative :
- mode travail
- mode démonstration

## Mode travail
Contient :
- le fonctionnel
- le didactique
- les rappels de cadre
- les définitions
- les usages pro
- les vigilances

## Mode démonstration
Contient :
- tout le mode travail
- les sources détaillées
- les références documentaires
- les citations utiles
- les pages quand c’est pertinent
- la traduction entre source et outil
- les justifications des choix structurants

---

# docs/20_PALETTE_ET_UI.md

## Palette validée
- fond principal : #FAF6EF
- fond cartes : #EFE4D2
- couleur principale : #7A845F
- couleur secondaire : #A8B08D
- accent : #C2974A
- texte principal : #3F372F
- texte secondaire : #6F6559
- contours : #DCCFBE

## Grammaire visuelle
- grandes entrées d’accueil = galets allongés organiques
- cartes = très arrondies
- boutons secondaires = capsules sobres
- chemin = fin, souple, discret
- accès direction = petite porte ancienne discrète

---

# docs/21_INTERDITS.md

## Interdits absolus
- réinventer la structure
- changer les intitulés validés
- remplacer la palette validée
- improviser une mascotte
- déformer le logo ARTAG
- recolorer le logo ARTAG
- remplacer la logique métier par une interprétation graphique
- déplacer la direction dans le parcours usager
- transformer l’accueil en page vitrine
- livrer une réinterprétation au lieu d’une correction fidèle

---

# docs/22_ASSETS_ET_NOMS.md

## Assets obligatoires
- utiliser le vrai logo ARTAG : public/logo-artag.png

## Signature
Outil conçu par Sofia de los Rios dans le cadre de sa mission

Toujours écrire :
- Sofia avec un f
- de los Rios

---

# docs/23_ORDRE_DE_TRAVAIL.md

## Ordre de travail obligatoire
1. stabiliser la structure générale
2. intégrer correctement les assets
3. implémenter les profils et droits
4. finaliser accueil
5. finaliser dossier ouvert
6. finaliser bloc identité
7. finaliser socle autonomie
8. finaliser synthèse courte et note de continuité
9. finaliser bloc professionnel
10. finaliser logique d’ouverture des modules
11. finaliser modules principaux
12. finaliser modules secondaires
13. finaliser traçabilité
14. finaliser historique des versions
15. finaliser vue direction
16. finaliser indicateurs
17. finaliser sécurité
18. finaliser mode démonstration
19. finaliser couche didactique
20. finaliser mise en forme visuelle

---

# docs/24_COUCHE_DIDACTIQUE_ET_DOCUMENTAIRE.md

## Principe général
L’outil n’est pas seulement un outil d’accompagnement.
Il est aussi un outil didactique pour les professionnelles.

## Système standard à prévoir
Toujours les mêmes 4 accès, dans le même ordre :
- Définition
- Source
- Usage pro
- Vigilance

## Forme ergonomique
- présence discrète sous le titre des blocs ou des questions importantes
- ouverture en panneau dépliant léger dans le même écran
- contenu court en premier niveau
- approfondissement seulement si l’utilisatrice choisit de l’ouvrir

---

# docs/25_ETHIQUE.md

## Principes éthiques
1. le repérage ne vaut pas diagnostic total de la personne
2. l’outil aide à lire une situation ; il ne dispense jamais de la rencontrer
3. orienter n’est pas normaliser
4. partager l’utile ne signifie pas tout rendre visible
5. le réservé professionnel est une condition de qualité du travail
6. traçabilité n’est pas surveillance
7. l’indicateur sert la régulation d’équipe, pas la sanction cachée
8. cadre commun ne veut pas dire pratique mécanique
9. le rappel du cadre doit soutenir la pratique, non rabaisser la professionnelle
10. toute donnée doit avoir une finalité claire, utile et justifiable
11. l’ergonomie fait partie de l’éthique
12. être outillée ne signifie pas tout voir
13. l’outil doit rendre le cadre plus juste, pas simplement plus rigide
14. la personne ne doit jamais disparaître derrière la grille
15. un outil éthique est un outil révisable

---

# docs/26_INFRA_HEBERGEMENT_ET_ACCES_EXTERNES.md

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
