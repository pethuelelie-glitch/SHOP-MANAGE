Aboresence du projet


BoutiqueGestion/
│
├── src/
│   ├── Main.java                # Point d’entrée de l’application
│   │
│   ├── models/                  # Classes représentant les entités
│   │   ├── Produit.java
│   │   ├── Vente.java
│   │
│   ├── services/                # Logique métier (CRUD, calcul, etc.)
│   │   ├── ProduitService.java
│   │   ├── VenteService.java
│   │   ├── StockService.java
│   │
│   ├── utils/                   # Classes utilitaires (lecture/écriture fichiers)
│   │   ├── DataManager.java
│   │
│   └── ui/                      # Interface console
│       ├── Menu.java
│       ├── ConsoleHelper.java
│
├── data/                        # Stockage des fichiers de données
│   ├── produits.txt
│   └── ventes.txt
│
└── README.md
