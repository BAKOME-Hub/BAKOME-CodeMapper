
<p align="center">
  <img src="https://via.placeholder.com/800x400/0a0a0a/00ff88?text=BAKOME+CodeMapper+Terminal+Report" alt="BAKOME CodeMapper Terminal" width="100%">
</p>

<p align="center"><i>Rapport d'analyse dans le terminal — code mort, cycles, métriques.</i></p>

---

<p align="center">
  <img src="https://via.placeholder.com/800x400/0a0a0a/2962FF?text=BAKOME+CodeMapper+Dependency+Graph" alt="BAKOME CodeMapper Graph" width="100%">
</p>

<p align="center"><i>Graphe de dépendances interactif — fichiers et leurs connexions.</i></p>

---

## ⚡ Features

- 🔍 **8 langages** : Rust, Python, JS, TS, JSX, TSX, MQL5, C, C++
- 🗺️ **Graphe de dépendances** inter-fichiers
- 📞 **Graphe d'appels** de fonctions
- 💀 **Code mort** détecté automatiquement
- 👻 **Fichiers orphelins** (sans imports)
- 🔄 **Dépendances circulaires**
- 📊 **Métriques** : lignes, complexité, commentaires
- 🎯 **Mapping d'issues GitHub** (TF-IDF)
- 📄 **Export JSON** automatique
- 0️⃣ **Zéro dépendance externe**

---

## ⚙️ Quick Install

```bash
# Compiler
rustc bakome_codemapper.rs -o bakome_codemapper

# Lancer
./bakome_codemapper ./mon-projet

# Avec mapping d'issue GitHub
./bakome_codemapper ./mon-projet --issue "Titre|Corps de l'issue"
