<p align="center">
<a href="https://github.com/zanixongroup/pinterest-scraper" target="_blank">
    <img src="http://forthebadge.com/images/badges/built-with-love.svg"/>
  </a>
</p>

  <p align="center">
<p align="center">
  <a href="https://github.com/ztrdiamond" target="_blank">
    <img src="https://img.shields.io/npm/v/@zanixongroup/pinterest-scraper.svg" alt="Build Status">
  </a>
  <a href="https://github.com/zanixongroup/pinterest-scraper" target="_blank">
    <img src="https://img.shields.io/badge/License-Boost_1.0-lightblue.svg" alt="Codecov" />
  </a>
  <a href="https://github.com/ztrdiamond" target="_blank">
    <img src="https://img.shields.io/badge/License-ISC-blue.svg" alt="License">
  </a>
  
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@zanixongroup/pinterest-scraper" target="_blank">
    <img src="https://img.shields.io/npm/dt/@zanixongroup/pinterest-scraper.svg" />
  </a>
  
</p>

# Pinterest-Scraper

#### Fetch information about a pin, board, user and many more, without any API KEY or ACCESS TOKEN.

## Why to use?

- Flexible
- Exceedingly fast
- Includes type definition
- Lightweight

## Features

- ✅ │ Get specific pin
- ✅ │ Search up to 80 + pins
- ✅ │ Get information about a user.
- ✅ │ Get board information

# 🔗 Prerequisites

- NodeJS 16 +

# ❔Installation

```console
$ npm install @zanixongroup/pinterest-scraper
```

## Import

```typescript
import * as Pinterest from "@zanixongroup/pinterest-scraper";
```

## Example

```ts
import * as Pinterest from "@zanixongroup/pinterest-scraper";

(async () => {
  await get();
})(); // Anonymous arrow function
async function get() {
  const postId = "459156124515639652";
  const response = await Pinterest.getPins(postId);
  console.log(response);
}
```

## Output

```ts
{
  tags: [
    'Feel Good Quotes',
    'Pretty Quotes',
    'Cute Quotes',
    'Good Qoutes',
    'Good News Quotes',
    'Simple Qoutes',
    'Cute Short Quotes',
    'Motivacional Quotes',
    'Words Quotes'
  ],
  post: 'https://i.pinimg.com/originals/68/a8/58/68a85891ccbac21aba585d1fc42a7ec8.jpg',
  username: 'SheBeKrafty-Kelen┃Mental Health, Chronic Illness, Anxiety',
  followers: '1k',
  image: 'https://i.pinimg.com/75x75_RS/63/f0/ca/63f0ca7bb609c35149679b682b95d2eb.jpg',
  url: 'https://www.pinterest.com/search/pins/?q=happiness'
}
```

# 🔗 Links

- [Github](https://github.com/ztrdiamond)
- [Repository](https://github.com/zanixongroup/pinterest-scraper)

# License

ISC
