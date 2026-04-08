> 🇬🇧 [Read in English](README.md)

# UTasks — Application de gestion de tâches

Application de gestion de tâches inspirée de Trello, développée dans le cadre d'un projet universitaire à l'Université Laval. Tableaux, listes, cartes, glisser-déposer, chat en temps réel — frontend et backend, tous deux construits de zéro.

> Le dépôt original du cours est privé. Ce miroir contient uniquement ce README.
> 🔗 [Démo complète](https://youtu.be/M_y_7DwdNP0)

---

## 📹 Démo

*Aperçu du tableau*
![Demo](assets/board-demo.gif)

---

## Fonctionnalités

**Tableaux, listes et cartes**<br>
└─ `Créer, modifier, supprimer des tableaux, listes et cartes. CRUD complet à tous les niveaux.`

**Glisser-déposer**<br>
└─ `Réorganiser les cartes entre les listes et les listes au sein d'un tableau, de façon fluide.`

**Tri des cartes**<br>
└─ `Trier les cartes par priorité ou date d'échéance dans une liste.`

**Authentification**<br>
└─ `Inscription, connexion, déconnexion avec authentification par jeton.`

**Chat en temps réel**<br>
└─ `Messagerie en direct entre utilisateurs via WebSocket.`

---

## 📹 Démo

*Ajout d'une liste dans un tableau*
![Demo List](assets/list-demo.gif)

*Glisser-déposer en action*
![Drag and drop](assets/drag-and-drop-demo.gif)

---

## Technologies

**Frontend**
- Vue 3, Vite, Vue Router
- vuedraggable (glisser-déposer)
- Axios

**Backend**
- Node.js, Express, API REST
- MongoDB, Mongoose
- Passport.js (authentification)
- Socket.io (chat en temps réel)

---

## Structure du projet

```
frontend/
├── main.js
├── App.vue
└── src/
    ├── pages/          # Pages tableau, liste, carte
    ├── components/     # Composants UI réutilisables
    ├── router/         # Configuration Vue Router
    └── services/       # Appels API Axios
backend/
├── index.js
└── src/
    ├── repositories/   # Couche d'accès aux données
    ├── services/       # Logique métier
    ├── middleware/     # Authentification
    ├── socket/         # Événements Socket.io
    └── scripts/        # Scripts utilitaires
```

---

## Mes contributions

**Frontend**
- Glisser-déposer des cartes à l'intérieur et entre les listes
- Réorganisation des listes par glisser-déposer au sein d'un tableau
- Tri des cartes par priorité et date d'échéance

**Backend**
- Authentification (inscription, connexion, déconnexion, jeton)
- Chat en temps réel entre utilisateurs (Socket.io)

---

## Contributeurs

Projet universitaire d'équipe — GLO-3102, Université Laval.

- **[Petiton Wiseley](https://github.com/pwiseley)**
- **[Ouedraogo Aliya Imann](https://github.com/aioue8)**
- **[Dongmeza Murielle Christelle](https://github.com/muriellec)**

---

[petiton.dev](https://petiton.dev)
