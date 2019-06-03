# Cours VueJS

## Ressources

### [Vue CLI](https://cli.vuejs.org/guide/)

Vue CLI est un système complet pour le développement rapide de Vue.js, fournissant :

- Échafaudage de projet interactif via @ vue / cli.
- Zéro config prototypage rapide via @ vue / cli + @ vue / cli-service-global.
- Une dépendance d'exécution (@ vue / cli-service) qui est :
Évolutif;
Construit sur le webpack, avec des défauts raisonnables;
Configurable via le fichier de configuration dans le projet;
Extensible via des plugins
- Une riche collection de plugins officiels intégrant les meilleurs outils de l'écosystème frontal.

Vue CLI vise à être la base de référence standard de l'outillage pour l'écosystème Vue. Il s'assure que les différents outils de construction fonctionnent sans heurts avec des valeurs par défaut raisonnables afin que vous puissiez vous concentrer sur l'écriture de votre application au lieu de passer des jours à se débattre avec des configurations. Dans le même temps, il offre encore la possibilité de modifier la configuration de chaque outil sans avoir besoin d'éjecter.

### [VueJS](https://vuejs.org/v2/guide/)

Vue (prononcé /vjuː/, comme le terme anglais view) est un framework évolutif pour construire des interfaces utilisateur. À la différence des autres frameworks monolithiques, Vue a été conçu et pensé pour pouvoir être adopté de manière incrémentale. Le cœur de la bibliothèque est concentré uniquement sur la partie vue, et il est vraiment simple de l’intégrer avec d’autres bibliothèques ou projets existants. D’un autre côté, Vue est tout à fait capable de faire tourner des applications web monopages quand il est couplé avec des outils modernes et des bibliothèques complémentaires.

### [Vue DevTools](https://github.com/vuejs/vue-devtools)

Extension devtools pour le débogage des applications Vue.js.

### [Vue Router](https://router.vuejs.org/)

#### Introduction

Vue Router est le routeur officiel de Vue.js. Il s'intègre profondément avec le core de Vue.js pour faire de la construction d'applications Single Page avec Vue.js un jeu d'enfant.

#### Exemple

```
import Vue from 'vue'
import Router from 'vue-router'
import HelloWorld from '@/components/HelloWorld'

Vue.use(Router)

export default new Router({
  routes: [
    {
      path: '/',
      name: 'HelloWorld',
      component: HelloWorld
    }
  ]
})
```

### [Vue Store](https://vuex.vuejs.org/)

Vuex est un modèle de gestion d'état + bibliothèque pour les applications Vue.js. Il sert de magasin centralisé pour tous les composants d'une application, avec des règles garantissant que l'état ne peut être muté que de manière prévisible. Il s'intègre également à l'extension officielle devtools de Vue pour fournir des fonctionnalités avancées telles que le débogage time-voyage zéro-config et l'exportation / importation de snapshots d'état.

### [Vue Awesome](https://github.com/vuejs/awesome-vue)

Une liste organisée de choses géniales liées à Vue.js
