# Mobile Money en Afrique : Substitut Bancaire ou Complément Technologique ?

##  Contexte et Vue d'ensemble
L'émergence du Mobile Money en Afrique est souvent citée comme l'exemple parfait de **"Leapfrogging"** (saut technologique). Ce projet analyse si l'adoption massive des services financiers mobiles agit comme un substitut au système bancaire traditionnel ou s'il s'inscrit dans un modèle hybride de complémentarité. 

L'étude couvre **43 pays africains** sur une période de **14 ans (2011-2024)**, avec une analyse approfondie du "Paradoxe Marocain".

##  Structure des Données & Modélisation
L'analyse repose sur l'intégration de trois sources de données hétérogènes, harmonisées via une approche **CRISP-DM**.

* **Données Cibles :** Volume et valeur des transactions Mobile Money (Source : **FMI FAS**).
* **Données de Contexte :** PIB, croissance annuelle, population urbaine vs rurale (Source : **Banque Mondiale WDI**).
* **Modèle Relationnel :** Normalisation des séries temporelles (Unpivot) et jointures via les codes ISO pays et Series Code.

##  Résumé Exécutif (Key Insights)
L'analyse démontre que le Mobile Money n'est plus une simple alternative pour les populations non-bancarisées, mais un moteur de croissance systémique :
* **Accélération Post-Covid :** Une croissance exponentielle des transactions a été observée dès 2020. Des leaders comme le Ghana et la Côte d'Ivoire affichent des taux d'adoption active dépassant les **36%**.
* **Le Paradoxe Marocain :** Contrairement au modèle de substitution pur, le Maroc affiche un **modèle hybride**. La densité des ATMs (pic à 8 118 unités en 2022) continue de croître parallèlement à l'adoption du mobile (43 millions de transactions en 2024).
* **Intensité d'Usage :** L'indice d'intensité (Transactions/PIB) montre une décorrélation positive entre la maturité numérique et la résilience économique.

##  Deep Dive : Analyse Thématique

### 1. Preuve du Leapfrogging
L'analyse spatiale montre une corrélation inverse entre la maturité des infrastructures bancaires physiques et la vitesse d'adoption du mobile. Dans les régions à faible densité d'agences, le téléphone mobile remplace intégralement l'infrastructure bancaire classique.

### 2. Le Duel "Cash vs Mobile" au Maroc
L'étude du cas marocain révèle une cohabitation unique :
* Le cash reste prédominant pour les transactions de faible valeur.
* Le Mobile Money progresse sur les segments de transfert de fonds et de paiement de factures, avec une marge de progression importante par rapport aux leaders de l'Afrique de l'Est.

## 💡 Recommandations Stratégiques
1.  **Interopérabilité :** Accélérer l'interconnexion entre banques et opérateurs pour transformer le flux "Cash-to-Digital" en épargne formelle.
2.  **Ciblage Rural :** Étant donné la corrélation entre ruralité et inclusion financière, les services USSD (sans data) doivent rester au cœur de la stratégie de déploiement.
3.  **Digitalisation B2B :** Passer d'un modèle de transfert P2P (Person-to-Person) à un écosystème de paiement marchand (B2C/B2B) pour stabiliser les dépôts.

## 🛠️ Stack Technique
* **Power BI :** Dashboard décisionnel interactif (Navigation : Panorama, Leapfrogging, Modèle Marocain, Prospective 2027).
* **Power Query :** Nettoyage et transformation de données (80% du temps projet dédié à l'harmonisation FMI/WB).
* **DAX :** Création de mesures complexes (Indice d'intensité, taux d'adoption active, projections 2027).

##  Limites et Hypothèses
* **Latence :** Les données internationales présentent un décalage de 1 à 2 ans, nécessitant des projections pour les années 2023-2024.
* **Informel :** Le modèle ne capture que les flux enregistrés ; une part de l'économie liquide échappe par nature à l'analyse numérique.


---
**Contact :** [MAJRI Douha] – [www.linkedin.com/in/douha-majri] //
*Projet réalisé dans le cadre du module Data Driven Decision Making - École Centrale Casablanca.*

