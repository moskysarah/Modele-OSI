
# 🌐 Modèle OSI

Le **modèle OSI (Open Systems Interconnection)** est un modèle de référence composé de **7 couches**. Il permet de comprendre comment les données sont transmises d'un appareil à un autre sur un réseau.

Lorsqu'un appareil **envoie** des données, elles traversent les couches de **7 → 1**. Lorsqu'elles arrivent sur le serveur, elles remontent de **1 → 7**.

## 📡 Communication entre un PC et un serveur

```text
                    MODÈLE OSI

        TON PC                              SERVEUR
          │                                    │
    7. Application ────────────────────────►  7. Application
    6. Présentation ───────────────────────►  6. Présentation
    5. Session ───────────────────────────►  5. Session
    4. Transport ─────────────────────────►  4. Transport
    3. Réseau ────────────────────────────►  3. Réseau
    2. Liaison de données ────────────────►  2. Liaison de données
    1. Physique ══════════════════════════►  1. Physique
          │                                    │
          └────────────── RÉSEAU ──────────────┘
