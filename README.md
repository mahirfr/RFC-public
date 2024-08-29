
# Introduction à l'application RFC

L'application RFC est une application mobile dédiée à la collecte d'informations lors de l'installation des Répartiteurs de Frais de Chauffage (RFC) sur les radiateurs.

### L'application est divisée en trois sections principales :
1. Adresse de l'intervention
2. Détails de l'intervention
3. Détails des RFC

<br>
<hr>
<br>

## Page d'accueil

La page d'accueil affiche les interventions déjà effectuées par le technicien.

> **Un espace où les techniciens peuvent consulter leurs interventions passées**

<img src="screenshots/home_screen.png" width="200px">

*Veuillez noter que cette page ne contient pas de données réelles et **n'est pas encore implémentée**. L'intégration de ces fonctionnalités nécessiterait une base de données ainsi qu'un serveur, ce qui engendrerait des coûts supplémentaires.*

<hr>

### 1. Adresse de l'intervention

L'application permet de saisir des informations sur l'adresse exacte de l'intervention en utilisant l'API fournie par le gouvernement, qui répertorie toutes les adresses en France. Cela permet aux techniciens d'être plus rapides et précis lors de la saisie des adresses.

> **Champs d'adresse à remplir**

<img src="screenshots/address_fields.png" width="200px">

<br>

> **Saisie d'adresse avec autocomplétion**

<img src="screenshots/address_autocomplete.png" width="200px">

<br>

> **Champs d'adresse remplis**

<img src="screenshots/address_filled.png" width="200px">

<br>

<hr>

### 2. Détails de l'intervention

Cette page contient les informations relatives au client ainsi qu'au technicien. Veuillez consulter les images ci-dessous.

> **Champs d'intervention à remplir**

<img src="screenshots/intervention_details.png" width="200px">

<br>

> **Sélection de la date d'intervention via le calendrier**

<img src="screenshots/intervention_details_datepicker.png" width="200px">

<br>

> **Champs d'intervention remplis**

<img src="screenshots/intervention_details_filled.png" width="200px">

<br>

<hr>

### 3. Détails des RFC

Cette page regroupe la majorité des informations relatives à l'installation des RFC. Vous y trouverez les dimensions des radiateurs, les codes-barres des RFC (à installer et déjà installés), leurs index, les coefficients KS et KA, la composition des radiateurs, les matériaux, ainsi que les photos des RFC installés sur les radiateurs. Vous pouvez consulter les images illustrant ces fonctionnalités et bien plus encore.

> **Vue complète de la page pour mieux comprendre le fonctionnement de l'application**

<img src="screenshots/rfc_complete_view.jpg" width="300px">

<br>

> **Dialogue affichant toutes les valeurs de KS**

<img src="screenshots/rfc_details_ks.png" width="200px">

<br>

> **Champ de localisation du radiateur avec autocomplétion pour les pièces d'un logement**

<img src="screenshots/rfc_details_emplacement.png" width="200px">

<br>

> **Branchement d'un radiateur KA**

<img src="screenshots/rfc_details_ka.png" width="200px">

<br>

> **Robinet maniable ? (oui/non)**

<img src="screenshots/rfc_details_tap_man.png" width="200px">
    
<br>

> **Type de robinet**

<img src="screenshots/rfc_details_tap_type.png" width="200px">

<br>

> **Champ de marque du radiateur** où le technicien peut choisir parmi plus de 60 marques couramment utilisées

<img src="screenshots/rfc_details_brand.png" width="200px">

<br>

> **Champ de sélection de la famille de radiateurs**

<img src="screenshots/rfc_details_family.png" width="200px">

<br>

> **Champ de sous-famille de radiateur** (les sous-familles étant souvent omises sur les bordereaux papier)

<img src="screenshots/rfc_details_sub_family.png" width="200px">

<br>

> **Composition (choix parmi toutes les options disponibles)**

<img src="screenshots/rfc_details_composition.png" width="200px">

<br>

> **Matériaux du radiateur**

<img src="screenshots/rfc_details_material.png" width="200px">

<br>

> **Dimensions du radiateur** (avec un bouton calculant la longueur totale du radiateur)

<img src="screenshots/rfc_details_dimensions.png" width="200px">

<br>

> **Champs des codes-barres et index des RFC** (installés et désinstallés)

<img src="screenshots/rfc_details_rfcs.png" width="200px">

<br>

> **Fonctionnalité de scan de codes-barres**

<img src="screenshots/rfc_details_barcode_scanner.png" width="200px">

<br>

> **Observations relatives à l'intervention**

<img src="screenshots/rfc_observation.jpg" width="200px">

<br>

> **Fonctionnalité de prise de photos**

<img src="screenshots/rfc_details_take_photo.jpg" width="200px">

<br>

> **Boîte de dialogue de confirmation**

<img src="screenshots/rfc_confirmation.jpg" width="200px">

<br>

> **Ajout d'un autre RFC pour l'intervention**

<img src="screenshots/rfc_added.jpg" width="200px">

<br>

> **Fonctionnalité de partage des informations en format PDF**

<img src="screenshots/pdf_export_option.jpg" width="200px">

<br>

> **Document PDF généré**

<img src="screenshots/generated_pdf.jpg" width="200px">

<br>

> **Signatures nécessaires pour valider l'intervention**

<img src="screenshots/signatures.jpg" width="200px">

<br>

> **Fonctionnalité permettant aux techniciens de modifier un RFC déjà renseigné**

<img src="screenshots/individual_rfc_complete_view.jpg" width="200px">

<br>

> **Fonctionnalité permettant de supprimer un RFC renseigné** (via le bouton rouge situé dans les RFC de l'intervention)

<img src="screenshots/rfc_delete_confirmation.jpg" width="200px">
