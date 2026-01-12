<img width="640" height="320" alt="StoreKit" src="https://github.com/user-attachments/assets/56d1bcd8-b8e8-4239-b3bf-016bc6c26b81" />

```md
# 📱 StoreKitDemo

Application iOS de démonstration utilisant **SwiftUI** et **StoreKit 2**  
pour gérer des **abonnements mensuels et annuels** avec un paywall personnalisé.

---

## ✨ Fonctionnalités

- SwiftUI (architecture moderne)
- StoreKit 2 (`async / await`)
- Abonnements mensuel & annuel
- Gestion des droits utilisateur (Pro)
- Persistance locale avec `@AppStorage`
- Restauration des achats
- Écoute en temps réel des transactions
- Paywall personnalisé
- Tests locaux via fichier `.storekit`

---

## 🧱 Architecture du projet

├── App
│ └── StoreKitDemoApp.swift
├── Managers
│ ├── EntitlementManager.swift
│ └── SubscriptionsManager.swift
├── Views
│ ├── ContentView.swift
│ ├── PaywallOptionView.swift
│ └── SubscriptionItemView.swift
└── StoreKitConfiguration
└── PremiumSubs.storekit



