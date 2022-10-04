# `@seeker64/streak-counter` - a basic streak counter

This is a basic streak counter - inspired by DuoLingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install

```shell
npm install @seeker64/streak-counter
```

## Usage

```JavaScript
import {streakCounter} from '@stephen-dalessandri/streak-counter'

const today = new Date();
const streak = streakCounter(localStorage, today);

// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021"
//    startDate: "11/11/2021"
// }