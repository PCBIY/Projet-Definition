**📘 PCBIY – Machine de Fabrication de PCB Semi-Automatisée**

**Une machine de fabrication de circuits imprimés 2 couches, semi-automatisée, intégrant le fraisage d’isolation, le perçage/rivetage automatique des vias et une assistance à l’application du soldermask. Conçue pour rendre la fabrication de PCB accessible dans un environnement de bureau.**

Il s’agit de la version **V1** du projet.La machine exécute automatiquement tous les déplacements et opérations de fabrication, tandis que l’utilisateur effectue manuellement les changements d’outil lorsque requis.

⸻

**🚀 Fonctionnalités (V1)**

**🌀 Fabrication**

	•	Fraisage d’isolation haute précision
	•	Perçage automatique des vias
	•	Rivetage automatique des vias (micro-rivets)
	•	Assistance à l’application du soldermask
	•	Palpage automatique pour garantir une profondeur de fraisage constante

**🔧 Interaction Utilisateur (Semi-Automatique)**

	•	Changement manuel des outils (dévissage / vissage de l’embout)
	•	La machine s’arrête et guide l’utilisateur lors des changements
	•	Indicateurs visuels et messages prévus dans l’interface

**⚙️ Électronique & Contrôle**

	•	Système de mouvement précis (pas à pas ou boucle fermée)
	•	Broche à vitesse contrôlée
	•	Génération d’itinéraires outil (toolpaths) à partir de fichiers Gerber
	•	Architecture firmware modulaire pour future intégration d’un ATC

⸻

**🎯 Objectifs du Projet**

	•	Permettre la fabrication de PCB rapide, fiable et abordable à domicile
	•	Réduire l’utilisation de produits chimiques
	•	Établir une base solide pour les versions futures (V2 avec ATC?, V3 complètement automatisée?)
	•	Offrir un projet open-source complet : mécanique, électronique, firmware et logiciel

**📁 Structure du Dépôt (Planifié)**

pcbiy/

 ├── docs/              # Documentation, schémas d’ensemble, notes de recherche
 
 ├── mechanics/         # Conception mécanique : CAD, STL, STEP, BOM
 
 ├── electronics/       # Schémas électroniques, PCB
 
 ├── firmware/          # Firmware du microcontrôleur
 
 ├── ui/                # Interface de contrôle (web ou desktop)
 
 ├── toolpath/          # Pipeline CAM, génération G-code depuis Gerber
 
 └── research/          # Expérimentation, données, résultats de tests

** 🧩 Trajectoire**

**V1 — Semi-Automatisée (actuelle)**

	•	Changements d’outil manuels
	•	Isolation, perçage, vias
	•	Assistance soldermask
	•	Interface et firmware de base

**V2 — Fortement Automatisée**

	•	Changeur d’outils automatique
	•	À définir

**V3 — Fabrication Intégral**

	•	Du “Début → PCB fini” 
	•	À définir

⸻

**🧪 État Actuel**

	•	Le projet est phase de définition

⸻

**🤝 Contribution**

Le projet est encore en phase initiale.
Vous pouvez ouvrir des issues, proposer des idées ou partager des recherches.

La structure de contribution sera définie une fois l’architecture stabilisée.

⸻

**📜 Licence**

À déterminer.
La mécanique, l’électronique et le logiciel pourraient utiliser des licences différentes.

⸻

**⭐ Suivre le Projet**

Ajoutez le REPO à votre Watchlist pour suivre les avancées.
Plus de documentation et de fichiers seront publiés au fur et à mesure de l’évolution du projet.



