# Problem with Nuxt Playground linting

There are two problems with the Nuxt Playground linting:

### Reproduction

Only see the console output

## 1. `vue/multi-word-component-name` rule

Default this off on nuxt pages and layers folder, but it not working in `.playground` folder.

`pages/index.vue` has no error, but the same file in playground (`.playground/pages/index.vue`) has error.

## 2. `vue/no-multiple-template-root` rule

Default this is error on nuxt pages and layers folder, but it not working in `.playground` folder.

`pages/multiple-template-root.vue` has error, but the same file in playground (`.playground/pages/multiple-template-root.vue`) has no error.
