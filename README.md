# 🌍 GéoClimat Explorer

**Outil interactif de cartographie et d'analyse spatiale** — exploration de 35 croisements possibles entre données géospatiales françaises (IGN, Copernicus, ADEME, SANDRE, Météo-France…) autour des enjeux climatiques et environnementaux.

[![Cartographie](https://img.shields.io/badge/Domaine-SIG%20%26%20Cartographie-2FD97F?style=flat-square)](#)
[![Data](https://img.shields.io/badge/Données-IGN%20%7C%20Open%20Data-4A9EFF?style=flat-square)](#)
[![Front-end](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JS-FFC44D?style=flat-square)](#)

---

## 📑 Sommaire

- [À propos](#-à-propos)
- [Fonctionnalités](#-fonctionnalités)
- [Types de cartographie couverts](#-types-de-cartographie-couverts)
- [Domaines thématiques](#-domaines-thématiques)
- [Projets complémentaires](#-projets-complémentaires)
- [Stack technique](#-stack-technique)
- [Utilisation](#-utilisation)
- [Contact](#-contact)

---

## 👤 À propos

GéoClimat Explorer est une application web (page unique, sans dépendance serveur) qui recense des **croisements cartographiques** exploitant des bases de données publiques françaises. Chaque fiche présente : la justification du croisement, la méthodologie appliquée, les outils mobilisés et les sources de données avec liens directs.

Ce projet illustre des compétences en **cartographie thématique**, **analyse spatiale** et **développement d'interfaces de visualisation de données géographiques**.

---

## ⚙️ Fonctionnalités

- 🔍 **Filtrage** par domaine thématique et par base de données source
- 📄 **Fiches détaillées** : pourquoi ce croisement, méthodologie, outils, sources cliquables
- 📊 **Statistiques en direct** (nombre de productions, part d'open data, bases mobilisées)
- 📋 **Export** de fiche en un clic (copie formatée)

---

## 🗺️ Types de cartographie couverts

| Type | Icône | Ce qu'il permet de montrer |
|---|---|---|
| **Cartographie thématique** | 🎨 | Répartition spatiale d'un phénomène (ressource, pollution, carbone) |
| **Cartographie interactive** | 🖱️ | Exploration filtrable et dynamique des données (cet outil) |
| **Cartographie d'analyse spatiale** | 📐 | Croisement de couches (jointures, buffers, statistiques zonales) pour révéler des relations |
| **Cartographie des risques** | ⚠️ | Spatialisation d'un aléa et de l'exposition associée |
| **Cartographie diachronique** | 🕰️ | Évolution d'un phénomène dans le temps (occupation du sol, artificialisation) |
| **Cartographie environnementale** | 🌱 | Suivi d'un compartiment environnemental et de ses pressions |

---

## 🧭 Domaines thématiques

L'outil organise les 35 croisements autour de 9 domaines : `Eau & hydrologie` · `Transport & mobilité` · `Agriculture & alimentation` · `Santé & société` · `Énergie & transition` · `Risques naturels` · `Biodiversité` · `Urbanisme & ville` · `Forêt & sylviculture`.

---

## 🧩 Projets complémentaires

En plus des 35 croisements de l'outil, les analyses suivantes ont été développées (stage) et illustrent des applications supplémentaires par type de cartographie :

| Thématique | Type de cartographie | Données IGN | Données externes |
|---|---|---|---|
| Gestion de la ressource en eau | 🎨 Thématique | BD TOPO, OCS GE, RGE ALTI, LiDAR HD | OFB, BNPE, Observatoire des services publics d'eau et d'assainissement, VigiEau |
| Pollution de l'air | 🎨 Thématique | OCS GE, BD Forêts | Citepa, Airparif |
| Contrôle de l'érosion dans les territoires agricoles | 📐 Analyse spatiale | OCS GE, RPG | MTE, EFESE, INRAE, Agreste |
| Usage des sols agricoles et captation du carbone | 🎨 Thématique | OCS GE, OCS PV | ADEME (Base Carbone), INRAE |
| Artificialisation des sols par panneaux photovoltaïques | 🧩 Occupation du sol | OCS GE | Portail cartographique ENR |
| Pollution des sols | 🌱 Environnementale | BD TOPO | BASOL |
| Empreinte carbone selon le mode de transport | 🎨 Thématique | BD TOPO, IGN Rando | ADEME, FUB, ENEDIS |
| Incendies de forêt | ⚠️ Risques | BD Forêts, BDIFF | EFFIS |
| Observatoire des forêts françaises | 🔎 Suivi environnemental | LiDAR HD, BD Forêts | IFN, Observatoire des forêts françaises |

---

## 🛠️ Stack technique

`HTML` · `CSS` · `JavaScript` (vanilla, sans framework) · Icônes [Tabler Icons](https://tabler.io/icons) · Polices Google Fonts (Syne, Inter, JetBrains Mono)

---

## 🚀 Utilisation

Ouvrir simplement `index.html` dans un navigateur, ou activer **GitHub Pages** (`Settings → Pages → Deploy from branch → main`) pour une démo en ligne.

---

## 📬 Contact


- **Email :** *anjarasoa.raja@gmail.com*
