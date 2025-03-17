# OPIB - Outil de Pentest Indépendant Breton

## Organisation du projet

Le projet est structuré en **7 dépôts** :

- **`vue-js-front`** : Interface graphique utilisateur.
- **`spring-boot-back-for-front-api-rest`** : API centrale assurant l’interface entre les modules, le front-end et la base de données.
- **`spring-boot-scan-port`** : Module dédié au scan de ports.
- **`spring-boot-bruteforce-ssh`** : Module de brute-force sur SSH.
- **`spring-boot-attack-wifi`** : Module d’attaques sur les réseaux Wi-Fi.
- **`spring-boot-analyse-cve`** : Module d’analyse des vulnérabilités CVE.
- **`spring-boot-generate-report`** : Génération de rapports basés sur les résultats des modules.
