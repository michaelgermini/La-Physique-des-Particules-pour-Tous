# Annexe : Formules et calculs physiques

> **🧮 Collection complète des formules mathématiques utilisées dans "La Physique des Particules pour Tous" - avec explications, exemples numériques et applications concrètes.**

---

## 📐 Constantes fondamentales

### ⚡ Valeurs numériques (2024)

| Constante | Symbole | Valeur | Unité | Précision |
|-----------|---------|--------|-------|-----------|
| **Vitesse lumière** | c | 299 792 458 | m/s | Exacte (définition) |
| **Constante Planck** | h | 6.626 070 15 × 10^-34 | J⋅s | Exacte |
| **ℏ = h/2π** | ℏ | 1.054 571 817 × 10^-34 | J⋅s | Exacte |
| **Charge élémentaire** | e | 1.602 176 634 × 10^-19 | C | Exacte |
| **Masse électron** | m_e | 9.109 383 701 5 × 10^-31 | kg | 10^-10 |
| **Constante d'Avogadro** | N_A | 6.022 140 76 × 10^23 | mol^-1 | Exacte |
| **Constante de Boltzmann** | k_B | 1.380 649 × 10^-23 | J/K | Exacte |
| **Constante gravitation** | G | 6.674 30 × 10^-11 | m³⋅kg⁻¹⋅s⁻² | 10^-4 |

---

## ⚛️ Relativité restreinte

### 📊 Transformations de Lorentz

**Pour une vitesse v selon x :**

```
γ = 1/√(1 - v²/c²)

x' = γ(x - v t)
t' = γ(t - v x/c²)
```

**Exemple : Proton LHC (v = 0.999999991 c)**
```
γ = 1/√(1 - 0.999999991²) ≈ 7460
Énergie = γ m c² = 7460 × 0.938 GeV ≈ 7000 GeV
```

### ⚖️ Équivalence masse-énergie

**E = m c²**

**Énergie de liaison proton :**
```
Masses :
- Proton : 938.272 MeV
- 2 up + 1 down : 2×2.2 + 4.7 = 9.1 MeV

Énergie liaison = 938.272 - 9.1 = 929.172 MeV
E = m c² → m = E/c² = 929.172 MeV / (931.494 MeV/u) ≈ 1 u
```

---

## 🧲 Électromagnétisme

### ⚡ Loi de Coulomb

**F = k q₁ q₂ / r²**

Où k = 1/(4πε₀) = 9 × 10^9 N⋅m²/C²

**Force proton-électron :**
```
q₁ = +e, q₂ = -e
r = 0.1 nm = 10^-10 m
F = 9×10^9 × (1.6×10^-19)² / (10^-10)² = 2.3 × 10^-8 N
```

### 🌊 Équations de Maxwell

**∇·E = ρ/ε₀** (Gauss)
**∇·B = 0** (pas de monopôles)
**∇×E = -∂B/∂t** (Faraday)
**∇×B = μ₀ J + μ₀ ε₀ ∂E/∂t** (Ampère-Maxwell)

---

## 🌀 Mécanique quantique

### 📈 Équation de Schrödinger

**i ℏ ∂ψ/∂t = H ψ**

**Oscillateur harmonique :**
```
H = p²/2m + (1/2) m ω² x²
Énergies : E_n = ℏ ω (n + 1/2)
```

### 🎯 Principe d'incertitude

**Δx Δp ≥ ℏ/2**

**Électron dans atome :**
```
Δx ≈ 10^-10 m (rayon Bohr)
Δp ≥ ℏ/(2 Δx) ≈ 10^-24 kg⋅m/s
```

### 🌊 Dualité onde-particule

**λ = h / p**

**Électron 1 eV :**
```
p = √(2 m E) = √(2 × 9.1×10^-31 × 1.6×10^-19) ≈ 5.4×10^-25 kg⋅m/s
λ = 6.6×10^-34 / 5.4×10^-25 ≈ 1.2 nm
```

---

## 🧲 Interaction forte

### 🧮 Chromodynamique quantique (QCD)

**Paramètre de couplage :**
```
α_s(Q²) = 1 / (β₀ ln(Q²/Λ²))
β₀ = 11 - 2 n_f/3
```

**À Q = 1 GeV : α_s ≈ 0.3**
**À Q = 100 GeV : α_s ≈ 0.1**

### ⚖️ Masse des hadrons

**Modèle quark :**
```
M_hadron = ∑ m_quarks + énergie liaison
```

**Proton : 2m_u + m_d + E_liaison = 9.1 + 929 = 938 MeV**

---

## ⚠️ Interaction faible

### 📊 Théorie électrofaible

**Groupe SU(2)_L × U(1)_Y**

**Brisure spontanée :**
```
φ = (0, v/√2) → masse des bosons W, Z
```

**Constante de Fermi :**
```
G_F = 1.166 × 10^-5 GeV^-1
```

---

## 🌌 Cosmologie

### 🌠 Équations de Friedmann

**ȧ/a = H = √(8πG ρ/3 - k c²/a² + Λ c²/3)**

**Densité critique :**
```
ρ_c = 3 H² / (8π G) ≈ 10^-26 kg/m³
```

### 🌑 Matière noire

**Paramètre de densité :**
```
Ω_m = ρ_m / ρ_c ≈ 0.27
Ω_Λ = Λ c² / (3 H²) ≈ 0.68
Ω_radiation < 0.01
```

**Ω_total = 1.00 ± 0.005**

---

## 📊 Statistiques en physique des particules

### 🎯 Significativité statistique

**Test χ² :**
```
χ² = ∑ (O_i - E_i)² / E_i
```

**Probabilité :**
```
P(χ² > valeur) donne la significativité
```

**Découverte : 5σ (p = 2.9×10^-7)**

---

## 🧮 Exemples d'application

### 🚀 Énergie LHC

**Collision proton-proton :**
```
E_total = 2 × E_proton × γ
γ = 1/√(1 - β²) ≈ 7460
E_total = 2 × 6.5 TeV × 7460 ≈ 97 TeV
```

**Température équivalente :**
```
T = E / (3 k_B n)^{1/3} × 1.3 ≈ 10^12 K
```

### 🧲 Aimant LHC

**Champ B = 8.33 T**
**Rayon ρ = 4.3 km**
**Énergie max : p = 0.3 B ρ ≈ 14 TeV**

---

## 📚 Glossaire des symboles

| Symbole | Signification | Unité |
|---------|----------------|-------|
| **c** | Vitesse lumière | m/s |
| **ℏ** | Constante Planck réduite | J⋅s |
| **e** | Charge élémentaire | C |
| **α** | Constante structure fine | - |
| **G_F** | Constante Fermi | GeV^-1 |
| **Λ** | Échelle QCD | GeV |
| **v** | VEV champ Higgs | GeV |
| **H** | Constante Hubble | km/s/Mpc |

---

*💡 Cette annexe rassemble toutes les formules essentielles. Utilisez-la comme référence rapide pour vos calculs !*
