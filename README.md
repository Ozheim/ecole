# ecole

# Rapport d'activité - 08/12/2025 - Projet T-DEV-700

Aujourd'hui j'ai travaillé sur le projet Time Manager.  j'ai commencé par faire du refactoring du code existant pour améliorer la maintenabilité et la lisibilité. J'ai nettoyé plusieurs fichiers du backend et du frontend.  j'ai développé une nouvelle feature complète : l'export des pointages en CSV et PDF. J'ai créé un nouveau controller dans le backend qui gère la génération des exports. Pour le CSV, j'ai implémenté une fonction qui génère un fichier avec tous les enregistrements de pointage avec la date, l'heure, le type et l'employé, ainsi qu'un résumé avec le nombre total d'enregistrements et les heures totales travaillées. Pour le PDF, j'ai utilisé la bibliothèque pdfkit pour créer un document formaté avec des tableaux et une mise en page professionnelle, incluant également un résumé détaillé.

J'ai aussi créé une nouvelle route API avec deux endpoints pour le CSV et le PDF, qui respectent les permissions selon les rôles. Les managers et admins peuvent exporter les pointages de n'importe quel utilisateur ou équipe, tandis que les employés ne peuvent exporter que leurs propres données.

Pour le frontend, j'ai développé un composant modal réutilisable qui permet de sélectionner les paramètres d'export : les dates de début et fin optionnelles, et le format souhaité entre CSV et PDF. J'ai intégré ce composant dans les dashboards des managers et des employés avec un bouton Export visible et accessible. Le modal gère le téléchargement automatique du fichier généré.

J'ai également ajouté des tests unitaires pour vérifier le bon fonctionnement des exports et les restrictions d'accès selon les rôles. J'ai installé la dépendance pdfkit dans le backend pour la génération des PDFs.

En parallèle, j'ai traduit tous les commentaires du projet en anglais pour améliorer la cohérence du code et faciliter la collaboration. J'ai parcouru tous les fichiers du projet, backend et frontend, et remplacé tous les commentaires français par leurs équivalents anglais, en veillant à conserver le sens et la clarté.


j'ai fais un peu d'anglais aussi

https://github.com/EpitechMscProPromo2027/T-DEV-700-project-TLS_12/commit/fd62a3e48150cf6fef31bd2b2ea3f9331f2ae119
https://github.com/EpitechMscProPromo2027/T-DEV-700-project-TLS_12/commit/ffaf248a47a57d56ed60230e8b0b15504ba69545
