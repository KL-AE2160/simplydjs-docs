---
sidebar_position: 1
tags:
  - Others
---

# toRgb

Converts Hex code to RGB Array (or) RGB String. Useful for converting discord.js v13 to v14.

```js
simplydjs.toRgb('hex code')
```


:::info INFO
This can be implemented anywhere. Even outside of discord.js ;)
:::

## Arguements:
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
