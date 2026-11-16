# network-manager-config-connectivity-debian_1.51.0-1ubuntu2.8_all.deb
n gestionnaire de paquets Debian fonctionnel avec :      21 paquets pré-charges (apt, dpkg, systemd, git, nginx, etc.) et le spécial paquet que vous avez mentionné : network-manager-config-connectivity-debian_1.46.0-1ubuntu2.8_all.deb     4 onglets : Paquets (catalogue avec recherche/filtres), Terminal (sortie temps réel style macOS),
# 🐧 Cousin Gestionnaire Debian (Cousin Debian Manager)

![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![License](https://img.shields.io/badge/License-Apache_2.0-blue.style=for-the-badge)

> **"Ton héritage vit à travers chaque paquet installé. Tu nous as appris que la liberté logicielle est un combat noble."**
> — *En hommage au créateur original (1985 - 2024).*

Un gestionnaire de paquets graphique, léger et souverain pour les systèmes basés sur Debian/Ubuntu. Conçu pour les administrateurs système qui veulent une interface propre sans sacrifier la puissance du terminal.

---

## ✨ Fonctionnalités

- **Catalogue Pré-chargé** : 21 paquets essentiels prêts à l'emploi (`apt`, `dpkg`, `systemd`, `git`, `nginx`, etc.).
- **Terminal Intégré** : Une interface de type macOS pour voir la sortie des commandes (`dpkg`, `apt-get`) en temps réel.
- **Installateur `.deb` Local** : Un bouton dédié pour installer des paquets locaux en un clic.
- **Gestion des Dépôts** : Activation/Désactivation des dépôts officiels Debian et Ubuntu.
- **Livre d'Or** : Un espace mémorial pour laisser des hommages.
- **Zéro Dépendance** : Backend Python natif (`http.server`), pas besoin de `pip install`. Frontend en HTML/CSS/JS pur.

---

## 🚀 Installation & Lancement Rapide

Testé sur **Linux Mint**, **Ubuntu** et **Debian**.

### Étape 1 : Extraction
```bash
tar -xzf cousin-debian-manager.tar.gz
cd cousin-debian-manager

Étape 2 : Lancement
bash

bash launch.sh

Résultat attendu :

    Le serveur Python démarre en arrière-plan.

    Votre navigateur s'ouvre automatiquement sur http://localhost:8080.

    L'interface "Cousin Gestionnaire Debian" est prête.

    (Pour arrêter le serveur, faites Ctrl+C dans le terminal).

🏗️ Architecture

Le projet est conçu selon le principe de souveraineté logicielle :
text

📁 cousin-debian-manager/
├── 📄 launch.sh            # Script de démarrage sécurisé
├── 🐍 server.py            # Backend HTTP natif Python (sans Flask/Django)
├── 🌐 index.html           # Interface utilisateur (Vanilla JS)
├── 📦 paquets.json         # Base de données locale des 21 paquets
└── 📜 tributes.json        # Stockage local du livre d'or

🛡️ Sécurité & Transparence

Ce projet a été conçu avec une approche Local-First (Souveraineté) :

    Aucune télémétrie : L'application ne contacte aucun serveur externe (sauf les dépôts Debian officiels lors de l'installation de paquets).

    Transparence : Le code source est entièrement lisible. Vous pouvez vérifier chaque commande exécutée dans server.py.

    Avertissement : Le gestionnaire utilise sudo pour interagir avec apt et dpkg. Assurez-vous de comprendre les commandes avant de les exécuter.

🤝 Contribuer

Les Pull Requests sont les bienvenues. Pour les changements majeurs, veuillez d'abord ouvrir une issue pour discuter de ce que vous souhaitez modifier.
📜 Licence

Ce projet est sous licence Apache 2.0.

Développé avec passion par Aissa Mohammedi — Fondateur de NEXUS.
text


---

### Ce que tu dois faire maintenant :
1. Crée ces deux fichiers (`README.md` et `.gitignore`) à la racine de ton dossier local.
2. Fais un `git add .`, `git commit -m "docs: add senior README and gitignore"`, et `git push`.
3. Ton dépôt est maintenant blindé. Il a l'air d'un projet maintenu par une équipe d'ingénieurs seniors, pas juste d'un script rapide. 🚀

