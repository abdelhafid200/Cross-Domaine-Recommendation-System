# Cross-Domaine-Recommendation-System

---

##  Cross-Domain Recommendation - User-Based Approaches  

Ce repository regroupe l'implémentation de plusieurs approches de **recommandation cross-domaine** dans le cas où les **utilisateurs sont similaires entre deux domaines** :  

###  Approches implémentées :  
- **EMCDR (Embedding Mapping Cross-Domain Recommendation)**  
- **CACDR (Coupled Autoencoder Cross-Domain Recommendation)**  
- **DACDR (Domain-Aware Cross Attention Recommendation)**  
- **SURNet-CDR (Shared User Representation Network for Cross-Domain Recommendation)** — *notre approche proposée*  

---

###  **Structure du repo :**  
- `Calcule the Similarity.ipynb` — Calcul de la similarité des utilisateurs, items et paires user-item entre les deux datasets.  
- `pfe-emcdr-user-based.ipynb` — Implémentation EMCDR  
- `PFE-CACDR-user-based.ipynb` — Implémentation CACDR  
- `PFE-DACDR-user-based.ipynb` — Implémentation DACDR  
- `PFE-SURNet-CDR-user-based.ipynb` — Implémentation de notre approche SURNet-CDR  

---

###  **Datasets utilisés :**  
- **Target Domain : Taobao User Behavior Dataset**  
  - 1 million d’utilisateurs, 4 millions d’items, interactions (click, cart, fav, buy).  
  - le lien de Dataset :[Dataset Target](https://www.kaggle.com/datasets/marwa80/userbehavior)

- **Source Domain : Taobao Alimama Ad Dataset**  
  - 1.14 million d’utilisateurs, 26 millions d’interactions, données publicitaires (ad clicks).
  - Le lien de Dataset : [Dataset Source](https://www.kaggle.com/datasets/pavansanagapati/ad-displayclick-data-on-taobaocom/data)
---