# Minimal reproduction project issue

## Issue :

Eslint returns "errors" instead of "warnings" for vue's rules.

## Steps to reproduce

```
npm run lint
```

Eg "vue/no-unused-components" should return a warning instead of an error :

> error: The "HelloWorld" component has been registered but not used (vue/no-unused-components) at src/App.vue:14:5:
