# Phénotypage par Deep Learning — Posters (EPPS 2025)

Ce dépôt rassemble **deux posters** de recherche présentant l'application de la **vision par ordinateur** et du **Deep Learning** à l'imagerie RGB en champ pour l'évaluation de maladies des céréales.

- **Fusarium Head Blight (FHB) — blé** : détection/segmentation des symptômes sur épis en conditions réelles.  
  → [`EPPS_2025_FHB_Poster.pdf`](posters/01_FHB_ble/EPPS_2025_FHB_Poster.pdf)
- **Barley Yellow Dwarf Virus (BYDV) — orge** : comparaison détection (**YOLO**) vs classification (**CNN**) à partir d'images RGB.  
  → [`EPPS_2025_BYDV_Poster.pdf`](posters/02_BYDV_orge/EPPS_2025_BYDV_Poster.pdf)

![Aperçu FHB](assets/vignette_fhb.png)
![Aperçu BYDV](assets/vignette_bydv.png)

---

## 🔎 Points saillants (non confidentiels)

**FHB (blé)**  
- Imagerie RGB de terrain, annotations d'épis (*sain* / *symptômes FHB*).  
- Pipeline de détection/segmentation (type **YOLO**), avec prétraitements d'alignement/recadrage.  
- Bon alignement avec les notations expertes ; interfaces de démo web/mobile possibles pour l'inférence.

**BYDV (orge)**  
- Jeu de données multi-sites/années.  
- Deux approches évaluées : **YOLO** (détection) vs **CNN** (classification).  
- Performances compétitives ; **CNN** = pipeline plus simple selon l'usage.

> ℹ️ Le **code n'est pas public** pour raisons de confidentialité. Ce dépôt diffuse les posters et un résumé de haut niveau des méthodes et résultats.

---

## 📚 Références (posters)

**FHB (blé)**  
Ousmane Kone, S., Cadot, V., Vincke, D., Treier, S., Mascher, N., Maigniel, J‑P., Herrera, J. & Vermeulen, P. (2025). *Automated detection of Fusarium Head blight symptoms on wheat spikes using Deep Learning on field RGB imaging*. **Poster** — European Plant Phenomics Symposium (EPPS), Bonn, 16–19 septembre 2025.

**BYDV (orge)**  
(Adapté du poster correspondant ; compléter ici la liste d'auteurs exacte si nécessaire.) *Development of deep learning models to detect and quantify symptoms of Barley Yellow Dwarf Virus in barley using RGB images*. **Poster** — EPPS 2025.

---

## 🗂️ Structure du dépôt

```
Posters-EPPS-2025/
├── README.md
├── assets/
│   ├── vignette_fhb.png      # généré automatiquement si possible
│   └── vignette_bydv.png
└── posters/
    ├── 01_FHB_ble/
    │   └── EPPS_2025_FHB_Poster.pdf
    └── 02_BYDV_orge/
        └── EPPS_2025_BYDV_Poster.pdf
```

---

## 🤝 Contact

- Auteur : **Seydina Ousmane Kone**  
- Contact : *(ajouter votre e‑mail ou profil LinkedIn ici)*

---

### Conseils d'usage
- Ajoutez ce dépôt en **épingle** sur votre profil GitHub.  
- Dans votre **CV** et sur **LinkedIn**, liez directement chaque PDF (ou la page du dépôt).  
- Optionnel : créez deux **Releases** (p. ex. `FHB-poster-2025`, `BYDV-poster-2025`) pour obtenir des liens stables.
