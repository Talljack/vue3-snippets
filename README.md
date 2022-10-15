# Vue 3 VS Code Snippets

![Vue Version](https://img.shields.io/badge/vue-3-%234FC08D?logo=vuedotjs)

## Description

These vue snippets is for vue3 developer. Use it you can write boilerplate code infinitely faster.

> inspire by [vue-vscode-snippets](https://github.com/sdras/vue-vscode-snippets)@sdras.
> because I want to more snippets for vue3. so I create this repo.

### `.vue` files

| Snippet        | Purpose                                                                                            |
| -------------- | -------------------------------------------------------------------------------------------------- |
| `vbase`        | Base for Vue 3 File with `<script lang="ts" setup>`, `TypeScript` and `Scss`                       |
| `vbase-nt`     | Base for Vue 3 File with `<script lang="tsx"> with setup custom render`, `TypeScript` and `Scss`   |
| `vbase-render` | Base for Vue 3 File with `<script lang="tsx" setup> with render function`, `TypeScript` and `Scss` |
| `vbase-ns`     | Base for Vue 3 File with `<script lang="ts" setup>`, `TypeScript`                                  |

### Template

| Snippet        | Purpose                                          |
| -------------- | ------------------------------------------------ |
| `vfor-arr`     | `v-for` array statement                          |
| `vfor-obj`     | `v-for` object statement                         |
| `vif`          | `v-if` statement                                 |
| `vshow`        | `v-show` statement                               |
| `vhtml`        | `v-html` statement                               |
| `vmodel`       | `v-model:value` model directive                  |
| `vupdate`      | `:value` and `@:update:value` binding and update |
| `vclass-arr`   | `:class` array of class                          |
| `vclass-obj`   | `:class` object of class                         |
| `vstyle-arr`   | `:style` array of style                          |
| `vstyle-obj`   | `:class` object of style                         |
| `vref-tmpl`    | `ref` ref of template                            |
| `von`          | `v-on` click handler                             |
| `vslot`        | `slot` name of define slot                       |
| `vslot-name`   | Named template slot                              |
| `vel-props`    | Component element with `props`                   |
| `vimg`         | Image source binding                             |
| `vtrans`       | Transition component                             |
| `vtrans-group` | Transition group component                       |
| `vkeep-alive`  | KeepAlive component                              |
| `vteleport`    | Teleport component                               |
| `vsuspense`    | Susepense component                              |
| `vrlink`       | Router link                                      |
| `vrlink-param` | Router link with param                           |

### Script

| Snippet            | Purpose                                       |
| ------------------ | --------------------------------------------- |
| `vimport`          | Vue import                                    |
| `vref`             | Vue `ref`                                     |
| `vreactive`        | Vue `reactive`                                |
| `vcomputed`        | Vue `computed`                                |
| `vwatch`           | Vue Watch                                     |
| `vwatcheffect`     | Watch Effect                                  |
| `vshallowref`      | Vue `shallowRef`                              |
| `vshallowreactive` | Vue `shallowReactive`                         |
| `vmarkraw`         | Vue `markRaw`                                 |
| `vonmounted`       | onMounted hook                                |
| `vonbeforemount`   | onBeforeMount hook                            |
| `vonbeforeupdate`  | onBeforeUpdate hook                           |
| `vonupdated`       | onUpdated hook                                |
| `vonunmounted`     | onUnmounted hook                              |
| `vonactivated`     | onActivated hook                              |
| `vondeactivated`   | onDeactivated hook                            |
| `vonbeforeunmount` | onBeforeUnmount hook                          |
| `vprovide`         | Vue `provide`                                 |
| `vinject`          | Vue `inject`                                  |
| `vprops`           | Define props                                  |
| `vprops-default`   | Define props with default value               |
| `vemits`           | Define emits                                  |
| `voptions`         | Define Vue options about inheritAttrs quickly |
| `vnexttick`        | Vue `nextTick`                                |
| `vunref`           | Vue `unref`                                   |
| `vtoRefs`          | Vue `toRefs`                                  |
| `vtoRef`           | Vue `toRef`                                   |
| `visRef`           | Vue `isRef`                                   |
| `visReactive`      | Vue `isReactive`                              |

### Vue Router

| Snippet                     | Purpose                                         |
| --------------------------- | ----------------------------------------------- |
| `vrouter`                   | Vue Router base config                          |
| `vrouter-scrollbehavior`    | Vue Router `scrollBehavior` config              |
| `vrouter-import`            | Vue Router import quickly                       |
| `vrouter-useRouter`         | Vue Router `useRouter` and `useROute`           |
| `vrouter-push`              | Vue Router `push`                               |
| `vrouter-redirect`          | Vue Router `redirect` config                    |
| `vrouter-beforeEach`        | Vue Router global guards `beforeEach`           |
| `vrouter-beforeEach`        | Vue Router global guards `beforeEach`           |
| `vrouter-beforeResolve`     | Vue Router global guards `beforeResolve`        |
| `vrouter-afterEach`         | Vue Router global guards `afterEach`            |
| `vrouter-beforeEnter`       | Vue Router per-route guard `beforeEnter`        |
| `vrouter-beforeRouteEnter`  | Vue Router component guards `beforeRouteEnter`  |
| `vrouter-beforeRouteUpdate` | Vue Router component guards `beforeRouteUpdate` |
| `vrouter-beforeRouteLeave`  | Vue Router component guards `beforeRouteLeave`  |
| `vrouter-params`            | Get `params` and `query` by `useRoute` quickly  |
| `vrouter-uselink`           | Get `href` and `isActive` by `useLink` quickly  |


### Vuex

| Snippet         | Purpose                                                                                                                                                                          |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `vueximport`    | Vuex improt quickly                                                                                                                                                              |
| `vuexuseStore`  | Use `useStore`                                                                                                                                                                   |
| `vuexbase`      | Vuex base template without `Typescript`                                                                                                                                          |
| `vuexlogger`    | Vuex `plugins` of `createLogger`                                                                                                                                                 |
| `vuexbase-type` | Vuex base template with `Typescript`, only in typescript file, ref[vuex](https://vuex.vuejs.org/zh/guide/typescript-support.html#%E7%AE%80%E5%8C%96-usestore-%E7%94%A8%E6%B3%95) |


## License

[MIT License](https://github.com/Talljack/vue3-hotKey/blob/main/LICENSE) © 2022-PRESENT [Talljack](https://github.com/Talljack)
