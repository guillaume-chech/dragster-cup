# 🏁 Dragster Cup — Application de Compétition

Application web mobile-first (iPhone 12) pour gérer intégralement la **Dragster Cup** du Liceo Francés.

## 🚀 Démarrage rapide

### GitHub Pages

1. Créer un nouveau repo GitHub (ex: `dragster-cup`)
2. Copier le contenu de ce dossier dans le repo
3. Aller dans **Settings → Pages → Source : main / root**
4. L'URL de votre app sera : `https://[votre-username].github.io/dragster-cup/`

### Test local

Ouvrir `index.html` dans Safari sur iPhone ou dupliquer l'écran via AirPlay.

---

## 📂 Structure du projet

```
dragster-cup/
├── index.html          ← Application complète
├── img/                ← Logos des écuries (à ajouter)
│   ├── ecurie-01.png
│   ├── ecurie-02.png
│   └── ...
└── README.md
```

### Ajouter les vrais logos

Placer les logos dans le dossier `img/` avec exactement ces noms :
- `ecurie-01.png` à `ecurie-24.png`
- Format recommandé : PNG 200×200px, fond transparent
- Si le fichier est absent → affichage automatique du placeholder coloré

---

## 🏎 Déroulement de la compétition

| Étape | Format | Courses |
|---|---|---|
| **Validation** | Présence des 24 écuries | — |
| **Tirage au sort** | 6 poules de 4 (ou moins si absents) | — |
| **Qualifications** | 6 poules × 2 courses (3m + 6m) | 12 |
| **Quarts de Finale** | 4 groupes × 2 courses | 8 |
| **Demi-Finales** | 2 groupes × 2 courses | 4 |
| **Grande Finale** | 1 groupe de 4 × 2 courses | 2 |
| **Total** | | **26 courses** |

## 🎯 Barème des points

| Position | Points |
|---|---|
| 1er | 10 pts |
| 2e | 6 pts |
| 3e | 3 pts |
| 4e | 1 pt |
| DNF / Collision fautive | 0 pt |

---

## 📋 Personnalisation des noms d'écuries

Ouvrir `index.html` et modifier le tableau `TEAMS_DATA` (ligne ~230) :

```javascript
const TEAMS_DATA = [
  { id: 1, name: "Nom de votre écurie", color: "#E10600" },
  // ...
];
```

---

*Lycée Français — Technologie 4ème — Projet Dragster*
