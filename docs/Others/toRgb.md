---
sidebar_position: 1
tags:
  - Others
---

# toRgb

Transforms Hex code into RGB Array (or) RGB String. This makes it easy to convert discord.js v13 to v14.

```js
simplydjs.toRgb('hex code')
```


:::info INFO
This can be implemented anywhere. Even outside of discord.js ;)
:::

## Arguments:
```ts
simplydjs.toRgb(hex: string, type: 'Array' | 'String')
```

- hex: `#string` | `string`
- type: `Array` | `String`

## Returns:
- `<Array>` (or) `<string>`

```js
// Hex code: #FFFFFF
[255, 255, 255]
// or
'rgb(255, 255, 255)'
```
