# Vue js Snippets

![vue-snippet-hero](assets/hero.jpg)

## Description

Short and simple vue snippets!

**This project still needs support for nuxt, vite config, vue 2, vue router, and pinia.**

- Contributions are welcome [github](https://github.com/devloos/vue-snippets)
- If you are contributing a snippet, please be sure to add the documentation for it in the tables in the README, the pull request cannot be accepted without this addition. Thanks!

https://github.com/devloos/vue-snippets/blob/594748025111933bff35451e2ec1dc85a47905e0/assets/snippets-demo.mp4

## Installation

- Go here [vscode Extensions Marketplace](https://marketplace.visualstudio.com/items?itemName=devloos.vue-snippets)

You can enable tab completion (recommended) by opening `Code > Preferences > Settings` (on a Mac) and applying `"editor.tabCompletion": "onlySnippets"` to your personal settings

### Vue

| Snippet       | Purpose                                                |
| ------------- | ------------------------------------------------------ |
| `vueinit`     | Single file component with script, template, and style |
| `vuescript`   | vue script tag                                         |
| `vuetemplate` | vue template tag                                       |
| `vuestyle`    | vue style tag                                          |

### Script

| Snippet           | Purpose                                                                  |
| ----------------- | ------------------------------------------------------------------------ |
| `vdata`           | Component data as a function                                             |
| `vmethod`         | Vue method                                                               |
| `vcomputed`       | Vue computed property                                                    |
| `vwatcher`        | Vue watcher with new and old value args                                  |
| `vbeforecreate`   | beforeCreate lifecycle method                                            |
| `vcreated`        | created lifecycle method                                                 |
| `vbeforemount`    | beforeMount lifecycle method                                             |
| `vmounted`        | vmounted lifecycle method                                                |
| `vbeforeupdate`   | beforeUpdate lifecycle method                                            |
| `vupdated`        | updated lifecycle method                                                 |
| `vbeforedestroy`  | beforeDestroy lifecycle method                                           |
| `vdestroyed`      | destroyed lifecycle method                                               |
| `vprops`          | Props with type and default                                              |
| `vimport`         | Import one component into another                                        |
| `vimport-dynamic` | Import one component that should be lazy loaded by webpack               |
| `vcomponents`     | Import one component into another within the export statement            |
| `vimport-export`  | Import one component into another and use it within the export statement |
| `vmapstate`       | import mapState from Vuex into vue component component                   |
| `vmapgetters`     | import mapGetters from Vuex into vue component component                 |
| `vmapmutations`   | import mapMutations from Vuex into vue component component               |
| `vmapactions`     | import mapActions from Vuex into vue component component                 |
| `vfilter`         | Vue filter                                                               |
| `vmixin`          | Create a Vue Mixin                                                       |
| `vmixin-use`      | Bring a mixin into a component to use                                    |
| `vc-direct`       | Vue create a custom directive                                            |
| `vimport-lib`     | Import a library                                                         |
| `vimport-gsap`    | Import GreenSock                                                         |
| `vanimhook-js`    | Using the Transition component JS hooks in methods                       |
| `vcommit`         | Commit to Vuex store in methods for mutation                             |
| `vdispatch`       | Dispatch to Vuex store in methods for action                             |
| `vtest`           | A simple unit testing component                                          |

### Template

| Snippet           | Purpose                             |
| ----------------- | ----------------------------------- |
| `vfor`            | v-for directive                     |
| `vmodel`          | Semantic v-model directive          |
| `von`             | v-on click handler with arguments   |
| `vslot-named`     | Named slot                          |
| `vel-props`       | Component element with props        |
| `vsrc`            | Image src binding                   |
| `vstyle`          | Inline style binding                |
| `vstyle-obj`      | Inline style binding with objects   |
| `vclass`          | Class binding                       |
| `vclass-obj`      | Class binding with objects          |
| `vclass-obj-mult` | Multiple conditional class bindings |
| `vanim`           | Transition component with JS hooks  |
| `vnuxtl`          | Nuxt Routing Link                   |
| `vroutename`      | router-link Named Routing           |
| `vroutenameparam` | router-link Named with Parameters   |
| `vroutepath`      | router-link Path Routing Link       |
| `vemit-child`     | Emit event from child component     |
| `vemit-parent`    | Emit event to parent component      |

### 0.1.0

Initial release of vue-snippets

**Enjoy!**
