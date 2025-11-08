# Les détecteurs de particules

> **📸 Analogie photographique : Les détecteurs de particules sont comme des appareils photo ultra-sophistiqués pour l'invisible - ils capturent des instantanés de collisions quantiques, révélant des détails que l'œil humain ne pourra jamais voir.**

---

## 👁️ Défis de la détection

### ⚡ Particules ultra-rapides

**Vitesse :** 99.9999991% de c

**Temps de vie :** 10^-23 secondes pour certaines

**Énergie :** TeV (mille milliards d'eV)

**Solutions :** Détection indirecte par effets secondaires

---

## 🏗️ Architecture multi-couches

### 📚 Principe en pelures d'oignon

**Détecteur typique (ATLAS/CMS) :**

```
Collision centrale
    ↓
Calorimètre électromagnétique (ECAL)
    ↓
Calorimètre hadronique (HCAL)
    ↓
Chambré à muons
    ↓
Aimants (pour mesurer p)
```

---

## 🔍 Types de détecteurs

### 💫 Chambres à traces

**Chambre à bulles :**
- Liquide surchauffé
- Bulles sur trajectoire ionisante
- Précision : 0.1 mm

**Chambre à étincelles :**
- Plaques conductrices
- Étincelles visualisent trajectoire

---

### 📱 Détecteurs à semi-conducteurs

**Pixels et strips :**
- Silicium dopé
- Signal électrique direct
- Précision : 10 μm

**Avantages :**
- Haute granularité
- Lecture rapide
- Résistance au rayonnement

---

### 🌊 Calorimètres

**Électromagnétique :**
- Cristaux (PbWO₄)
- Mesure énergie photons/électrons
- Résolution : 1%/√E

**Hadronique :**
- Échantillonnage acier/scintillateur
- Mesure énergie hadrons
- Compensation e/π

---

## 🧮 Mesure de l'énergie

### 📊 Reconstruction des trajectoires

**Champs magnétiques :**
- Aimant toroïdal (ATLAS) : 2 T
- Aimant solénoïdal (CMS) : 4 T

**Formule :** `p = 0.3 B r` (GeV/c)

Où r en mètres, B en tesla

---

## 🎯 Identification des particules

### 🔬 Techniques avancées

**dE/dx :** Perte d'énergie par ionisation

**Time-of-flight :** Vitesse par temps de vol

**Transition radiation :** Pour électrons relativistes

**Cherenkov :** Cône de lumière pour particules ultra-relativistes

---

## 📊 Exemple : Détection d'un muon

### 🧲 Trajectoire complète

1. **Collision :** Création du muon
2. **Tracker :** Mesure trajectoire incurvée
3. **Calorimètre :** Traversée (peu d'énergie déposée)
4. **Chambre à muons :** Confirmation identité
5. **Reconstruction :** Calcul momentum et masse

---

## 🧠 Activité d'analyse

**⏰ Scénario : Vous êtes physicien détecteur**

Une particule traverse votre détecteur. Signes :
- Trace courbe dans tracker
- Pic dans ECAL
- Rien dans HCAL
- Signal dans muon chambers

**Quelle particule ?** Justification ?

---

## 📚 Synthèse

- Détection indirecte essentielle
- Multiples technologies complémentaires
- Précision exceptionnelle
- Reconstruction 3D complète
