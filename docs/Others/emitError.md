---
sidebar_position: 2
tags:
  - Others
---

# emitError

Emit Errors like Simply DJS does

```js
simplydjs.emitError({ name: "Test", tip: "This is just to test" })
```


:::danger WARNING
This can stop your whole project as it emits an error not logging in console.
:::

## Arguements:
```ts
simplydjs.emitError({ name: string, tip: string })
```

- name: `string`
- tip: `string`
