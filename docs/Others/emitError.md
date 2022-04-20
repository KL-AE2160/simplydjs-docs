---
sidebar_position: 2
tags:
  - Others
---

# emitError

Produce error messages just like Simply DJS

```js
simplydjs.emitError({ name: "Test", tip: "This is just to test" })
```


:::danger WARNING
This may cause your entire project to stop as it emits an error not logging in the console.
:::

## Arguments:
```ts
simplydjs.emitError({ name: string, tip: string })
```

- name: `string`
- tip: `string`
