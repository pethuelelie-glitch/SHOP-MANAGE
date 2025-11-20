BoutiqueGestion/
│
├── src/
│   ├── Main.java                # Point d’entrée de l’application
│   │
│   ├── models/                  # Classes représentant les entités métier
│   │   ├── Produit.java
│   │   ├── Vente.java
│   │
│   ├── services/                # Logique métier (CRUD, calculs, etc.)
│   │   ├── ProduitService.java
│   │   ├── VenteService.java
│   │   ├── StockService.java
│   │
│   ├── utils/                   # Utilitaires (lecture/écriture de fichiers)
│   │   ├── DataManager.java
│   │
│   └── ui/                      # Interface utilisateur en console
│       ├── Menu.java
│       ├── ConsoleHelper.java
│
├── data/                        # Fichiers de données persistants
│   ├── produits.txt
│   └── ventes.txt
│
└── README.md
