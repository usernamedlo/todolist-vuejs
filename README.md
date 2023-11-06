# TODOLIST - VUE CLI - COMPOSITION API

## Description

Ce projet vise à créer une application de gestion de tâches (TodoList) en utilisant VueCLI et la Composition API de Vue.js. L'objectif est de permettre aux utilisateurs d'ajouter, modifier, et supprimer des tâches de leur liste.

## Liste des tâches

### Issue1: Créer la structure de l'app

- [ ] Initialiser le projet avec VueCLI
- [ ] Installer les dépendances

### Issue2: Adapter l'App.vue

- [ ] Charger DB.js
- [ ] Définir le template de base
- [ ] Styler le composant principal
- [ ] Charger le component TaskList et lui envoyer les tasks du localstorage

### Issue3: Créer le component TasksList

- [ ] Créer le fichier du composant
- [ ] Définir la structure HTML de base
- [ ] Styler le composant
- [ ] Créez une data tasks avec soit un [] soit le contenu du localstorage
- [ ] Charger et bouclez les Task en envoyant les tasks
- [ ] Créez et affichez une completed 'notCompletedCount' qui reprend le nombre de tasks restantes

### Issue4: Créer le component Task

- [ ] Créer le fichier du composant Task
- [ ] Définir la structure HTML du task
- [ ] Ajouter les props nécessaires
- [ ] Styler chaque task
- [ ] Tester l'intégration avec TasksList
- [ ] Modéliser le completed

### Issue5: Ajouter une task

- [ ] Créer une data 'newTaskContent'
- [ ] Modéliser cette data avec l'input en mode lazy
- [ ] Capturer l'évébement @change ou un watcher
- [ ] Pushez un objet littéral dans les tasks
- [ ] Mettez à jour le localstorage

### Issue6: Supprimer une task

- [ ] Capturez l'événement
- [ ] Emettez une événement 'delete' vers le parent avec l'id
- [ ] Lancer un deleteOneById qui splice et supprime du localstorage

### Issue7: Modifier une task

- [ ] Créer une data 'isEdited' à false
- [ ] Inverser la data au doubleclick
- [ ] Utilisez un v-if, else pour afficher soit le label soit l'input qui modélise
- [ ] Capturez l'évent et togglez le isEdited
- [ ] Mettez à jour le localstorage
