---
sidebar_position: 6
tags:
  - Systems
---

# automeme

The memes are sent automatically, so others will be able to laugh at the jokes without having to do anything !


```js
simplydjs.automeme(client, { 
  channelId: '01234567890123' // channelId (required)

  // options (optional)
})
```


:::info INFO
This should be implemented in the `ready` event !

```js
client.on('ready' => {
  simplydjs.automeme() // automeme function
})
:::

## Output

![image](https://user-images.githubusercontent.com/71836991/137742616-05fc1330-aeef-4f40-9031-1d81e93ff705.png)

## Arguments:
```ts
simplydjs.automeme(client: Client, options: memeOptions)
```

- client: `Discord.Client`
- options: [`memeOptions`](#options-memeoptions)

## Options `memeOptions`

import Link from '@docusaurus/Link';

| Parameter | Type | Required | Default    | Description |
| --------- | ----- | -------- | -------- | ---------- |
| `channelId`       | <Link to="https://discord.js.org/#/docs/discord.js/stable/class/Channel?scrollTo=id">Channel ID</Link>       | ✓        | _none_     | Channel ID of a Discord `TextChannel`    |
| `sub` | <Link to="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array">Array</Link> | ✘        | _default array_  | An array of custom subreddits                             |
| `interval`   | <Link to="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">milliseconds</Link>     | ✘        | _120000ms_ | Interval between memes sent by the bot. |
| `embed` | <Link to="/types/CustomizableEmbed">CustomizableEmbed</Link>         | ✘        | _none_  | Pass an CustomizableEmbed Object to customize the embed  |
