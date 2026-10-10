<div align="center">

# 📍 FindMe — Objets perdus, objets trouvés !

**Site vitrine et boutique en ligne d'une startup de traceurs pour retrouver ses objets perdus**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Design-responsive-2EA44F)

**[🌐 Voir le site en ligne](https://melissameziani.github.io/FindMe/)**

</div>

---

## 📸 Aperçu

![Page d'accueil](docs/captures/accueil.jpg)

| Produits | Packs spéciaux |
|:---:|:---:|
| ![Catalogue des produits](docs/captures/produits.jpg) | ![Packs spéciaux](docs/captures/packs.jpg) |

---

## 🎯 Le projet

> « Anticipez la perte, protégez vos objets dès aujourd'hui ! »

**FindMe** est un projet de startup réalisé dans le cadre du module universitaire **« Créer et Développer une Startup »** (Département d'Informatique, Université Mouloud Mammeri de Tizi-Ouzou, 2024-2025).

L'idée : aider les particuliers et les professionnels à **localiser leurs objets** (clés, sacs, bijoux, valises, véhicules, colis, animaux de compagnie…) et réduire le stress lié à la perte ou au vol.

**Vision :** devenir la référence algérienne, puis maghrébine, du suivi d'objets personnels et professionnels.

### 🔧 Trois technologies complémentaires

| Technologie | Usage | Exemples de produits |
|---|---|---|
| **Bluetooth Low Energy** | Localisation à courte portée (jusqu'à 100 m), buzzer pour faire sonner l'objet | Porte-clés, étiquettes, bracelets |
| **GPS + GSM/4G** | Suivi en temps réel partout dans le monde, historique des trajets, alertes de sortie de zone | Trackers pour voiture, valise, animaux |
| **RFID** | Identification sans batterie dans les lieux équipés de lecteurs (entrepôts, hôtels, événements) | Étiquettes, cartes, bracelets RFID |

### 💡 Services imaginés autour des produits

- **Partage de la localisation** avec ses proches ou son équipe (jusqu'à 6 personnes)
- **Abonnements** : gratuit, Standard, Premium et Famille / Équipe
- **Assurance « ObjetSûr »** : remboursement ou remplacement en cas de perte ou de vol
- **Solutions pour les entreprises** : suivi de colis, de flottes de livraison et d'équipements
- **Application mobile** (maquette) : liste de ses objets, scan de QR code, boutique, historique de localisation et bouton « Sonner »

## ✨ Le site web

Ce dépôt contient le **site vitrine et la boutique en ligne** de FindMe :

- **Catalogue de produits** : porte-clés Bluetooth, trackers GPS (voiture, animaux, valise), étiquettes RFID et QR code, bracelets, cartes RFID
- **Fiche détaillée** de chaque produit, dans une fenêtre : description, avantages, prix
- **Packs spéciaux** : Starter, Mobilité et Pro, avec le détail de leur contenu
- **Panier** : ajout de produits et calcul automatique du total, en JavaScript
- Section **« Partagez vos trackers avec votre cercle »**, qui présente la géolocalisation partagée
- **Barre de recherche**, menu de navigation et pied de page avec contact et services
- Design moderne et **responsive** (ordinateur, tablette, mobile)

## 🏗️ Structure

```
FindMe/
├── index.html        # Accueil : présentation, meilleurs produits, packs, panier
├── produit.html      # Catalogue complet des produits
├── css/
│   ├── style.css         # Styles de l'accueil
│   └── produitStyle.css  # Styles de la page produits
├── js/
│   └── carte.js      # Données des produits, fiches détaillées et panier
└── img/              # Images des produits et du site
```

## 🛠️ Technologies

- **HTML5** et **CSS3** : mise en page, animations, design responsive
- **JavaScript** (vanilla) : affichage dynamique des produits, fenêtres de détail, panier
- **Font Awesome** pour les icônes

## 🚀 Lancer le projet

Aucune installation n'est nécessaire :

- **En ligne :** [melissameziani.github.io/FindMe](https://melissameziani.github.io/FindMe/)
- **En local :** téléchargez le projet (bouton **Code**, puis **Download ZIP**) et ouvrez `index.html` dans votre navigateur.

## 📫 Contact

**Melissa MEZIANI** — Développeuse web full stack
[GitHub](https://github.com/melissameziani) · [LinkedIn](https://www.linkedin.com/in/melissa-meziani-b0ba4b299) · [mezianimelissa37@gmail.com](mailto:mezianimelissa37@gmail.com)
