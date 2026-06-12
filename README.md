# Majestis — Site vitrine

Site statique (HTML/CSS/JS vanilla) hébergé sur GitHub Pages.
Deux dépôts jumeaux : **site complet** (`majestis`) et **vitrine** (`majestis_vitrine`).

---

## 🗺️ Avancement de la réorganisation photos

> Tout est appliqué **sur les 2 sites**, **1 commit par catégorie**.
> ⛔ = bloqué tant que Maxime n'a pas fourni/identifié la photo.

### Intérieur
- [x] **Sol** — réorganisé : carrelage pierre / pierre naturelle séparés (ATN), marbre veiné (ATN),
  Versailles, Opéra Garnier (Renofors), Oiron, Shoah (photo **sol** remplacée — plus la fenêtre), dallage SELE
- [x] **Mur** — Mémorial de la Shoah (4 photos)
- [x] **Salle de bain** — pierre naturelle (ATN) + marbre (banque) ; photo au carrelage bleu retirée (reste dans Sol)
- [x] **Escaliers** — intérieurs uniquement, doublon « client privé » fusionné, titres à la norme
- [x] **Dressing** — 3 dressings : 2 banque + le dressing **ATN** (photo fournie par Maxime, verre fumé & métal)
- [x] **Salon** — 9 salons/séjours (banque)
- [x] **Charpente** — bois lamellé collé (Renofors)
- [x] **Bibliothèque** — boiseries Ateliers Perrault (photo du PowerPoint Résidences, **105 px seulement** → fournir une version HD)
- [x] **Plafond** — **catégorie retirée** (carte + menu) à la demande de Maxime
- [ ] **Chambre** — client privé ⛔ *(aucune photo de chambre dans la banque + page inexistante)*

### Extérieur
- [x] **Clocher** — église Saint-Sauveur (Compagnons de Saint Jacques)
- [x] **Entrée** — État-Major de Compiègne (3 photos, Léon-Noël) — la photo d'escalier déplacée vers Escalier extérieur
- [x] **Couronne d'Or** — Château des Ducs de Bretagne (Lefèvre)
- [x] **Escalier extérieur** — État-Major de Compiègne (4 photos, Léon-Noël)
- [x] **Pont Alexandre III** — métallerie & ors → placé dans **Dorure** (pas un pont à montrer, mais la ferronnerie/dorure réalisée dessus)
- [x] **Façade** — Château de Chantilly (Pavillon Nord) ✓ · « théâtre » (Rochefort) identifié mais photos en 148px seulement → ⛔ fournir une version HD · façade du château à la chaux ✓ · « RZ » toujours à identifier ⛔
- [ ] **Fenêtre** — version **haute résolution** ⛔
- [ ] **Couronne d'Or — carte** : image générique (la carte montre les Invalides, faux)

### Déco / Finition
- [x] **Dorure** — Oiron (lambris dorés) + Hôtel de la Marine (ors)
- [x] **Peinture** — Hôtel de la Marine (décors peints)
- [ ] **Dorure** — Hôtel **Vendôme** & Hôtel **Zurich** ⛔
- [x] **Mosaïque** — le **dragon** du Centre aquatique de l'Amandinois (Tollis, HD)

---

## 🖼️ Banque d'images — état du tri
- **Placées comme réalisations** : dressings (banque-7,17) → Dressing · marbre (14) → Salle de bain ·
  escalier (15) → Escaliers · salons (1,3,4,5,6,9,10,12,13) → **Salon**.
- **NON placées (= visuels génériques de représentation, pas des réalisations)** :
  extérieurs `banque-2,8,11,16,18` + `banque-interieurs / exterieurs / classique / contemporaine /
  renovation / realisation`. Disponibles dans `assets/` pour servir de **cartes de catégories**
  (chantier « cartes génériques » encore à faire — voir Couronne d'Or, Entrée, Façade…).

---

## 📸 Images encore à fournir / identifier
> Candidates dans `_a_identifier/`. À ajouter dans le ZIP de la banque (nom clair).

| Catégorie | À faire |
|---|---|
| **Façade** | photo « RZ » (initiales) toujours à identifier + théâtre Rochefort en HD |
| **Dorure** | Hôtel **Vendôme**, Hôtel **Zurich** |
| **Bibliothèque** | version **HD** (l'actuelle vient du PowerPoint en 105 px) |
| **Fenêtre** | version haute résolution |
| **Photos floues** | Maxime renvoie les versions nettes |

## 🗂 Dossier `_a_definir/` (photos en attente)
- `THEATRE-rochefort-…` : le théâtre (Façade) n'existe qu'en 148px → fournir HD
- `SOCRA-atelier-…` : atelier d'œuvres d'art (sculpture) → aucune catégorie ne correspond

## ❓ Décisions attendues
- **Chambre / Cuisine** : pages inexistantes, non créées. Les créer ? (Chambre n'a de toute
  façon aucune photo dans la banque.)

---

## Source & norme
Réalisations issues des **4 PowerPoints** (`HERITAGE ET MEMOIRE`, `Résidences d'exceptions`,
`Espaces pro réinventés`, `ESPACES ET STRUCTURES`).
**Titres (norme appliquée partout)** : le **truc + la matière** (ex. « Escalier en marbre »,
« Clocher — hydrogommage au mortier de chaux ») ; le **lieu/monument** (château, hôtel…) va en
**description** ; le **réalisateur** (trouvé dans le titre des slides : SELE, Mériguet-Carrère,
Tollis, Renofors, Léon-Noël, Lefèvre, Jacquet Barberot, Compagnons de Saint Jacques, ATN,
Ateliers Perrault…) en petit **dans la description uniquement**, jamais dans le titre.
Exceptions retitrage : Fenêtre (commence par « Fenêtre » + style), Peintures, Mosaïque.
Quand la banque sert (visuels génériques), description rédigée d'après le contenu de l'image.
