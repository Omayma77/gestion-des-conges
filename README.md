# LeaveSystem - Application de Gestion des Congés en Java

** LeaveSystem ** est une application développée en Java avec Swing et JDBC, permettant d'automatiser la gestion des demandes de congés des employés au sein d'une entreprise : gestion des employés, demandes de congés, approbations, authentification sécurisée et historique des actions.

## 📷 Aperçu des interfaces
### 🔑 Page d'accueil
  ![ Connexion ] ( media/image24.jpg )

### 🔑Interface de connexion
- Authentification sécurisée pour employés et administrateurs
- Validation des identifiants dans MySQL
  ![ Connexion ] ( media/ image25 .jpg )

### 🧑‍💼 Interface Employé
- Visualiser les types de congés disponibles
- Consultez le solde restant
- Soumettre une nouvelle demande de congé
- Imprimer ses demandes
  ![ Connexion ] ( media/image34.jpg )
  ![ Connexion ] ( media/image35.jpg )
  ![ Connexion ] ( media/image36.jpg )
### 🛠Administrateur d'interface
- Gérer les employés (ajout, édition, suppression)
- Valider ou rejeter les demandes de congés
- Impression des listes d'employés et des congés validés
- Envoi automatique d'email après décision
-    ![ Connexion ] ( media/image60.jpg )
   ![ Connexion ] ( media/image41.jpg )
   ![ Connexion ] ( media/image43.jpg )
   ![ Connexion ] ( media/image52.jpg )
  ![ Connexion ] ( media/image64.jpg )
  ![ Connexion ] ( media/image65.jpg )
  ![ Connexion ] ( media/image68.jpg )
---

## 🎯 Fonctionnalités principales
| Module                | Fonctionnalités clés                                    |
| ---------------------- | -------------------------------------------------------- |
| 🔐Authentification    | Connexion sécurisée (email et mot de passe)             |
| 🧑‍💼 Gestion Employés   | Ajouter, modifier, supprimer, rechercher employés      |
| 🛫 Gestion Congés       | Soumettre, visualiser, approuver/rejeter des congés     |
| 🖨 Impressions           | Impression de listes et d'attestations                 |
| 📧 E-mail de notification | Envoi d'email après validation ou rejet de demande     |
---
## 🛠️ Technologies utilisées
- Java 8+
- Swing – pour les interfaces graphiques
- JDBC – pour la connexion MySQL
- MySQL – base de données de gestion
- XAMPP – serveur local (Apache + MySQL)
- WebSwing – pour rendre l'application accessible via le navigateur (optionnel)
- IDE NetBeans
---
## ⚙️Installation & Réalisation
✅ ** Prérequis : **
- Kit de développement Java (JDK)
- Serveur XAMPP (MySQL actif)
- IDE NetBeans
🚀 ** Étapes d'installation : **
``` bash
# Cloner le projet
git clone https://github.com/Omayma77/gestion-des-conges.git
cd gestion-des-conges
```
- Importer le projet dans ** NetBeans IDE ** .
- Configurer la base de données avec les scripts SQL depuis ` /DataBase/ ` .
- Lancer ` Login.java ` pour démarrer l'application.
---
## 👩‍💻 Auteurs
-  ** Omayma Harchich **
-  ** Kawtar Gantouh **
---
## 📄 Licence
Projet réalisé dans un cadre académique - Utilisation libre avec attribution.
---
## ✅ Conclusion
** LeaveSystem ** propose une solution moderne et performante pour simplifier la gestion administrative des congés.  
Ergonomique, rapide et fiable, il répond aux besoins des RH en matière d'organisation et de suivi du personnel.
⭐ Pensez à noter ⭐ ou partagez ce projet si vous le trouvez utile !
---
