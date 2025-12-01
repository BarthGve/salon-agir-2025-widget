# Widget Fiches Entreprises IA - Salon Agir 2025

Widget HTML interactif pour afficher les fiches détaillées des entreprises IA françaises présentes au Salon Agir de Montrouge.

## Aperçu

Ce widget permet de visualiser de manière élégante les informations sur 14 entreprises françaises spécialisées en Intelligence Artificielle :

| Entreprise | Secteur |
|------------|---------|
| OWI | IA Conversationnelle / Chatbots |
| EuroMC | Protection électromagnétique / CEM |
| DreamOnTech | Cybersécurité / Gestion de crise IA |
| EULER DATA SOLUTIONS | Renseignement / Investigation IA |
| Cleyrop | Data Platform / IA Générative souveraine |
| Theodo | Conseil digital / Développement / IA |
| TRANSCRIPT - AUTHOT | Transcription / Speech-to-Text |
| EURODECISION | Optimisation / Recherche opérationnelle |
| LightOn | IA Générative / LLM souverain |
| Hexamind | Conseil IA / NLP / LLM |
| Axon | Data Science / IA / Analytics |
| MICELIA | IA sur mesure / Vision / NLP |
| Coppernic | Terminaux mobiles / Biométrie / IoT |
| WAVESTONE | Conseil / Transformation digitale / IA |

## Fonctionnalités

- **Sélecteur d'entreprise** : Menu déroulant pour choisir l'entreprise à afficher
- **Fiche complète** avec :
  - Informations générales (description, effectifs, CA, siège)
  - Solutions IA proposées avec cas d'usage secteur public
  - Références clients
  - Investisseurs et levées de fonds
  - Expertises techniques et certifications
  - Insights LinkedIn (réputation, croissance)
- **Design moderne** : Style Tech/Startup avec gradients, animations CSS
- **Liens directs** vers sites web et profils LinkedIn

## Utilisation

### Mode standalone

Ouvrez simplement le fichier `widget-entreprises.html` dans un navigateur. Le widget fonctionne avec des données de démonstration intégrées.

### Intégration Grist

1. Hébergez le fichier HTML (GitHub Pages, serveur web, etc.)
2. Dans votre document Grist, ajoutez un **Custom Widget**
3. Configurez l'URL du widget
4. Le widget se synchronisera automatiquement avec les données de vos tables Grist

#### Structure Grist attendue

Le widget s'intègre avec les tables suivantes :

- **Entreprises** : Informations générales (Nom, Description, SiteWeb, LogoURL, etc.)
- **Solutions_IA** : Solutions proposées par chaque entreprise
- **References_Clients** : Références clients secteur public/privé
- **Investisseurs** : Levées de fonds et investisseurs
- **Expertises** : Domaines techniques et certifications
- **LinkedIn_Insights** : Données de présence LinkedIn

## Technologies

- HTML5 / CSS3 (animations, gradients, flexbox)
- JavaScript vanilla
- [Grist Plugin API](https://support.getgrist.com/widget-custom/) pour l'intégration
- Google Fonts (Inter)

## Contexte

Widget développé pour le **Salon Agir 2025** à Montrouge, permettant aux acteurs du secteur public de consulter rapidement les profils des entreprises IA françaises.

## Licence

Usage interne - Secteur public
