# TPICT314_DJIONZE_NGOGANG_ANGE_25G2066


# Rapport sur mon implémentation de l'investigation numérique avec Autopsy 

## Présentation
C’est une plateforme de Digital Forensics (informatique légale) en open source. Elle est utilisée par les experts en sécurité, la police, et les administrateurs système pour fouiller dans un ordinateur ou un support de stockage afin de découvrir ce qui s'y est réellement passé.

##  Outils Utilisés
* **Logiciel :** Autopsy (Digital Forensics Platform)
* **Système d'exploitation :** Windows 


## Méthodologie appliquée

J'ai suivi les étapes standards d'une investigation numérique :

1.  **Création du Cas :** Configuration des métadonnées .
2.  **Ingestion des données :** Importation de la source de données et hachage (MD5/SHA-256) pour garantir l'intégrité de la preuve.
3.  **Analyse via Modules d'Ingestion :**
    * Recherche de fichiers supprimés.
    * Extraction de l'historique de navigation web.
    * Analyse des métadonnées des documents (EXIF, auteurs).
    * Extraction de mots-clés.
4.  **Examen des résultats :** Analyse des artefacts trouvés dans l'arborescence "Views".

##  Résultats obtenus
* **Récupération :** J'ai pu restaurer 2 fichiers qui avaient été supprimés.
* **Chronologie (Timeline) :** Identification des activités suspectes réalisées le 16 avril.
* **Preuves :** Localisation du fichier compromettant.

##  Conclusion
Cette expérience m'a permis de comprendre comment les enquêteurs numériques extraient des preuves de manière non destructive. J'ai appris l'importance de la chaîne de possession et de la vérification de l'intégrité des données.

