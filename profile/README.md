# OPIB - Outil de Pentest Indépendant Breton

## Etudiants : 
- [Sofiane EL NAGGAR](https://github.com/SofianeElNaggar)
- [Timoté CHIMIENTI](https://github.com/fra-2107)
- [Thomas LE BARON](https://github.com/MizuSARiUs)
- [Aubry TONNERRE](https://github.com/kiurow590)

> **Projet universitaire réalisé dans le cadre de l’Atelier Pratique Cybersécurité 2 – UQAC**

Cette organisation regroupe l'ensemble des dépôts liés au projet **OPIB**, une suite modulaire d'outils destinée à faciliter les audits de sécurité.  
Ce projet a été conçu, développé et présenté dans le cadre du cours **Atelier Pratique Cybersécurité 2** de la maîtrise en informatique à l'**Université du Québec à Chicoutimi (UQAC)**.

---

## 🎯 Objectif du projet

Concevoir une solution logicielle complète et modulaire pour :

- Réaliser des tests d'intrusion ciblés
- Identifier les failles de sécurité sur différents vecteurs (réseau, authentification, services, etc.)
- Automatiser la génération de rapports professionnels
- Intégrer des fonctionnalités IA pour une analyse augmentée

---

## 🧩 Architecture modulaire

Le projet est structuré autour de plusieurs modules indépendants, tous interconnectés via une API centrale :

### Frontend

- [`vue-js-front`](https://github.com/Uqac-Atelier-Cyber-Project/vue-js-front)  
  Interface utilisateur développée avec Vue.js pour interagir avec les modules.

### Backend central

- [`spring-boot-back-for-front-api-rest`](https://github.com/Uqac-Atelier-Cyber-Project/spring-boot-back-for-front-api-rest)  
  API REST principale (Spring Boot) orchestrant les communications entre le front, les modules d’analyse et la base de données.

### Modules fonctionnels

- [`spring-boot-scan-port`](https://github.com/Uqac-Atelier-Cyber-Project/spring-boot-scan-port) — Scan de ports réseau  
- [`spring-boot-bruteforce-ssh`](https://github.com/Uqac-Atelier-Cyber-Project/spring-boot-bruteforce-ssh) — Brute-force SSH  
- [`spring-boot-attack-wifi`](https://github.com/Uqac-Atelier-Cyber-Project/spring-boot-attack-wifi) — Audit de sécurité Wi-Fi  
- [`spring-boot-analyse-cve`](https://github.com/Uqac-Atelier-Cyber-Project/spring-boot-analyse-cve) — Analyse des CVE connues  
- [`spring-boot-generate-report`](https://github.com/Uqac-Atelier-Cyber-Project/spring-boot-generate-report) — Génération de rapports automatisée  
- [`API_Python_IA_Generate_Report`](https://github.com/Uqac-Atelier-Cyber-Project/API_Python_IA_Generate_Report) — API IA pour classification des vulnérabilités  

### Déploiement

- [`OPIB_installer_repo`](https://github.com/Uqac-Atelier-Cyber-Project/OPIB_installer_repo)  
  Scripts et instructions d’installation/déploiement.

---

## ✨ Réalisations

- Implémentation de plusieurs modules spécialisés en Spring Boot et Python
- Frontend responsive et ergonomique en Vue.js
- Intégration d'une IA pour interpréter et classifier les résultats
- Exportation automatisée de rapports complets en PDF/Markdown

---

## 📚 Contexte académique

Ce projet a permis de mettre en œuvre, de manière concrète, des connaissances en :

- Cybersécurité offensive
- Développement logiciel modulaire
- Communication interservices (API REST, microservices)
- Analyse de vulnérabilités
- Intelligence artificielle appliquée à la cybersécurité

---

## 📄 Licence et droits intellectuels

Ce projet a été réalisé à des fins pédagogiques**.

L’ensemble du code, des documents et des ressources produits dans le cadre de ce projet sont soumis à une licence open source, mais restent la propriété intellectuelle des auteurs (présenter en section `Etudiants`).

Sauf mention contraire, ce projet est distribué sous licence MIT.

Toute utilisation à des fins commerciales ou en dehors d’un cadre académique doit faire l’objet d’une autorisation préalable des auteurs.

