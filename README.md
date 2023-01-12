# snippets-for-vscode

这是一个适配 Vue3 Api 的 snippets 插件

## 使用方法

<img src="assets/2.gif" style="zoom: 100%;" />

<img src="assets/1.gif" style="zoom: 100%;" />

**注意** :本插件可能不完全适用于 vue2

# 特性

目前支持的代码片段

### 模版片段

|  关键词  |                                  代码片段                                   |
| :------: | :-------------------------------------------------------------------------: |
|   vue2   | `<script>export default{name:'demo',data(){return{}},mounted(){}}</script>` |
|   vue3   |   `<template></template><script lang="ts" setup></script><style></style>`   |
| template |                     `<template><div></div></template>`                      |
|  script  |                     `<script lang="ts" setup></script>`                     |
|  style   |                          `<style lang=""></style>`                          |
|   css    |                          `<style scoped></style>`                           |
|   scss   |                    `<style lang="scss" scoped></style>`                     |
|   Sass   |                    `<style lang="sass" scoped></style>`                     |
|   Less   |                    `<style lang="less" scoped></style>`                     |

### script&vue 片段

|    关键词     |                   代码片段                   |
| :-----------: | :------------------------------------------: |
|    import     |          `import {...} from '...'`           |
|     data      |            `data(){return {...}}`            |
|     vtext     |                `v-text="..."`                |
|     vhtml     |                `v-html="..."`                |
|     vshow     |                `v-show="..."`                |
|      vif      |                 `v-if="..."`                 |
|     velse     |                   `v-else`                   |
|    velseif    |              `v-else-if="..."`               |
|     vfor      |       `v-for="... in ..." :key="..."`        |
|   vfornokey   |             `v-for="... in ..."`             |
|      von      |                 `v-on="..."`                 |
|     vbind     |                `v-bind="..."`                |
|    vmodel     |               `v-model="..."`                |
|     vslot     |                `v-slot="..."`                |
|     vonce     |                   `v-once`                   |
|  iscomponent  |     `<component :is="..."></component>`      |
|  **vmethod**  |           `methods: {name() { }}`            |
| **vcomputed** |  `computed: {name() {return this.data }},`   |
|  **vprops**   | `const props = defineProps({ foo: String })` |
|  **vemits**   |  `const emit = defineEmits(['...', '...'])`  |

### 其他代码 片段

| 关键词 |                代码片段                 |
| :----: | :-------------------------------------: |
|  clg   | `console.log('output->${0}',${0:name})` |
|   cb   |         `const name = () => {}`         |
|   fb   |      `function name(){return ''}`       |

**Enjoy!**
