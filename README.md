# `@VAggrippino/streak-counter` - a basic streak counter

This is a basic streak counter - inspired by DuoLingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install

```shell
yarn add @VAggrippino/streak-counter
```
 &ndash; Or &ndash;
```shell
npm install @VAggrippino/streak-counter
```

## Usage
```JavaScript
import {streakCounter} from '@VAggrippino/streak-counter';

const today = new Date();
const streak = streakCounter(localStorage, today);

/* streak returns an object:
 * {
 *     currentCount: 1,
 *     lastLoginDate: "11/11/2021",
 *     startDate: "11/11/20121",
 * }
 */
