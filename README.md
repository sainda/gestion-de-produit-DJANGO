# 🛍️ Gestion des Produits - Projet Django

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

Une application web moderne de gestion des produits développée avec Django, offrant une interface utilisateur intuitive et des fonctionnalités complètes de gestion des produits.

## ✨ Fonctionnalités

### 🔐 Authentification
- Inscription et connexion des utilisateurs
- Protection des routes avec authentification
- Gestion des sessions utilisateur

### 📦 Gestion des Produits
- ✅ Création de produits avec images
- ✅ Affichage de la liste des produits
- ✅ Modification des produits existants
- ✅ Suppression de produits
- ✅ Recherche de produits
- ✅ Pagination des résultats
- ✅ Interface utilisateur responsive avec Bootstrap
- ✅ Gestion des images

### 🎨 Design
- Interface moderne et professionnelle
- Thème personnalisé avec des couleurs cohérentes
- Animations douces sur les cartes
- Icônes Bootstrap
- Messages d'alerte stylisés
- Navigation améliorée avec menu déroulant

## 🚀 Installation

1. Clonez le dépôt :
```bash
git clone https://github.com/khouloudlassoued-sys/test.git
cd test
```

2. Créez un environnement virtuel :
```bash
python -m venv venv
```

3. Activez l'environnement virtuel :
- Windows :
```bash
.\venv\Scripts\activate
```
- Linux/Mac :
```bash
source venv/bin/activate
```

4. Installez les dépendances :
```bash
pip install -r requirements.txt
```

5. Appliquez les migrations :
```bash
python manage.py migrate
```

6. Créez un superutilisateur :
```bash
python manage.py createsuperuser
```

7. Lancez le serveur de développement :
```bash
python manage.py runserver
```

8. Accédez à l'application via votre navigateur à l'adresse : `http://127.0.0.1:8000/`

## 📁 Structure du Projet

```
test/
├── products/                 # Application principale
│   ├── models.py            # Définition du modèle Product
│   ├── views.py             # Logique des vues
│   ├── forms.py             # Formulaires
│   ├── templates/           # Templates HTML
│   │   ├── products/        # Templates de l'application
│   │   └── registration/    # Templates d'authentification
│   └── urls.py              # Configuration des URLs
├── product_manager/         # Configuration du projet
│   ├── settings.py          # Paramètres du projet
│   └── urls.py              # URLs principales
├── media/                   # Dossier pour les fichiers médias
├── requirements.txt         # Dépendances du projet
└── README.md               # Documentation
```

## 🛠️ Technologies Utilisées

- **Backend** :
  - Django 5.0
  - Python 3.x
  - SQLite3

- **Frontend** :
  - Bootstrap 5.3
  - Bootstrap Icons
  - HTML5
  - CSS3

## 👤 Auteur

**Khouloud Lassoued**
- GitHub: [@khouloudlassoued-sys](https://github.com/khouloudlassoued-sys)

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

<div align="center">
  <sub>Built with ❤️ by Khouloud Lassoued</sub>
</div> 