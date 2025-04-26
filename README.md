# 🏝️ LeaveManager - Système de Gestion des Congés en Java Swing

**LeaveManager** est une application desktop développée en Java avec **Swing** et **JDBC**, offrant une solution complète pour gérer les demandes de congés au sein d'une entreprise, depuis la soumission par les employés jusqu'à l'approbation par les administrateurs.

---

## 📁 Structure du projet

```
LeaveManager/
├── src/
│   ├── auth/               # Gestion de l'authentification
│   ├── employees/          # Module employés
│   ├── leave/              # Gestion des congés
│   ├── admin/              # Panneau d'administration
│   ├── config/             # Configuration (DB, email)
│   ├── models/             # Classes métier
│   └── utils/              # Utilitaires (PDF, calculs)
├── database/               # Scripts SQL et schémas
├── media/                  # Ressources graphiques
├── docs/                   # Documentation technique
└── README.md
```

---

## 📷 Aperçu des Interfaces

### 1. Interface de Connexion
![Login](media/image18.png)

Connexion sécurisée avec rôles distincts (employé/admin). Validation des identifiants via MySQL.

---

### 2. Tableau de Bord Employé
![Dashboard Employé](media/image21.png)

Visualisation du solde de congés, historique des demandes et bouton de nouvelle demande.

---

### 3. Formulaire de Demande
![Nouvelle Demande](media/image12.png)

Saisie des dates, type de congé et motif. Calcul automatique de la durée.

---

### 4. Panneau Administrateur
![Admin Panel](media/image19.png)

Gestion centralisée des demandes en attente avec options d'approbation/rejet.

---

### 5. Gestion des Employés
![Gestion Employés](media/image13.png)

CRUD complet des employés avec impression de la liste au format PDF.

---

## 🎯 Fonctionnalités principales

| Module                | Fonctionnalités                                                                 |
|-----------------------|---------------------------------------------------------------------------------|
| 🔐 Authentification   | Double système (employé/admin) avec email/mot de passe                          |
| 📅 Gestion des Congés | Soumission, suivi, calcul automatique des soldes                                |
| 👨‍💼 Employés         | Profils complets avec historiques de congés                                     |
| 👩‍💼 Administration    | Approbation/rejet des demandes, notifications email, reporting                 |
| 📊 Reporting          | Génération de PDF (demandes, listes d'employés)                                |

---

## 🛠️ Technologies utilisées

- **Java 11+** - Langage principal
- **Swing** - Interface graphique
- **JDBC** - Connexion à MySQL
- **iTextPDF** - Génération de documents
- **JavaMail** - Envoi de notifications
- **JUnit** - Tests unitaires
- **NetBeans IDE** - Environnement de développement

---

## ⚙️ Installation & Exécution

### ✅ Prérequis
- Java JDK 11+
- MySQL 8.0+
- NetBeans (optionnel)

### 🚀 Étapes d'installation

1. **Cloner le dépôt** :
```bash
git clone https://github.com/votre-utilisateur/LeaveManager.git
cd LeaveManager
```

2. **Initialiser la base de données** :
```bash
mysql -u root -p < database/leave_system.sql
```

3. **Configurer les accès** dans `src/config/DBConfig.java`

4. **Lancer l'application** :
```bash
java -jar dist/LeaveManager.jar
```

---

## 📄 Documentation Technique

- **Diagrammes UML** :  
  - Cas d'utilisation : `docs/use_case_diagram.png`  
  - Modèle conceptuel : `docs/mcd.png`

- **Tests** :  
  ```bash
  mvn test
  ```

---

## 👥 Équipe Projet

**Kawtar GANTOUH**  
📧 kawtar.gantouh@example.com  
🔗 [GitHub](https://github.com/kawtar)

**Omayma HARCHICH**  
📧 omayma.harchich@example.com  
🔗 [GitHub](https://github.com/omayma)

**Encadrants** :  
- Pr. Abdessadek AAROUD  
- Pr. Khaoula CHERRAT  
*Faculté des Sciences d'El Jadida*

---

## 📜 Licence

Projet sous licence **MIT** - Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## ✅ Conclusion

**LeaveManager** modernise la gestion des congés avec :
✔ Interface intuitive en français  
✔ Automatisation des processus RH  
✔ Système de notification intégré  
✔ Rapports exportables  

> 💡 Idées d'amélioration : Module mobile, synchronisation calendrier, tableau de bord analytique

```

Points forts de ce README :
1. **Structure claire** avec emojis pour une meilleure lisibilité
2. **Capture d'écran intégrée** directement depuis votre rapport
3. **Tableau récapitulatif** des fonctionnalités par module
4. **Instructions d'installation** détaillées
5. **Section équipe** professionnelle avec liens GitHub
6. **Perspectives d'évolution** pour encourager les contributions

Pour une optimisation maximale sur GitHub :
1. Compressez les images dans `/media/` (utilisez [TinyPNG](https://tinypng.com/))
2. Ajoutez un fichier `.gitignore` pour exclure les dossiers `build/` et `dist/`
3. Créez un wiki GitHub avec la documentation technique complète
