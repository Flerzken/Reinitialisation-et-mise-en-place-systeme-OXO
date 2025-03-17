#📞 Projet Système Téléphonique

#📝 Description

Ce projet consiste en l'installation et la configuration d'un système téléphonique utilisant un OXO ainsi que plusieurs types de postes (IP, numériques et DECT). L'objectif est de mettre en place une infrastructure fonctionnelle et d'assurer une communication efficace entre les différents équipements.

#🎯 Objectifs

🔧 Installer et configurer un serveur OXO

📡 Mettre en place des postes numériques, IP et DECT

🔄 Résoudre les problèmes de connectivité et d’enregistrement des postes

🛠️ Assurer une mise à jour et une gestion optimisée du système

#✅ Prérequis

Avant de commencer, il est nécessaire de disposer de :

🖥️ Un serveur OXO avec les droits administrateur

🌐 Un réseau fonctionnel avec connectivité LAN

🔌 L’ensemble des équipements téléphoniques requis (Poste IP, Poste Numérique, Borne DECT, Poste DECT)

#📌 Déroulement du Projet

🔄 Réinstallation de l’OXO avec LoLa

L’OXO a rencontré un problème d’accessibilité en LAN. Il a donc fallu réinstaller entièrement le système avec le logiciel LoLa d’Alcatel, permettant de restaurer un OXO à son état d’usine avec une nouvelle version compatible.

🏗️ Mise en place des équipements

📞 Poste Numérique

Installation d’une carte d’extension pour supporter les ports numériques.

Connexion du poste et configuration via l’OMC.

🌍 Poste IP

Résolution du problème de serveur TFTP (No TFTP Response).

Analyse réseau avec Webdiag pour identifier les ports manquants.

Mise à jour de la version du serveur de R2 à R3 pour inclure les fichiers VoIP nécessaires.

Configuration du poste via OMC et assignation de son adresse MAC.

📡 Borne et Postes DECT

Connexion de la borne DECT à l’OXO et création d’une station de base xBS.

Ajout du poste DECT via l’OMC et enregistrement via GAP.

Validation de l’association en renseignant le code PIN et activation en mode évolutif.

🔍 Informations Supplémentaires

🔌 Ports utilisés dans l’OXO

5059 : Port standard Alcatel SIP

5060 : Port standard SIP

5061 : Port sécurisé SIP sur TCP

5080 : Port alternatif de configuration SIP

⏳ Temps d'inscription des appareils

Un appareil a 300 secondes pour s’enregistrer sur l’OXO.

Une vérification automatique est effectuée toutes les 120 secondes pour assurer l’état de connexion.
