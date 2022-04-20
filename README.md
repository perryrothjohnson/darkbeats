# whalebeats

This project was forked from tinysynth. We swapped out the drum samples with [whale sounds from NOAA](https://www.fisheries.noaa.gov/national/science-data/sounds-ocean).

## Setup instructions

You'll need node and npm installed, then:

```
$ npm i
$ npm start
```

## What the heck is npm??

Start [here](https://youtu.be/0twjvW0c1r0) for an overview... but essentially you'll want to:  

1. install [NodeJS](https://nodejs.org)
2. run the project with `npm start`

## Getting Tone.js audio to play

The original tinysynth won't play audio in most web browsers. To fix this, we added [Tone.context.resume()](https://tonejs.github.io/docs/r13/Context) to the Tone.Sequence start function.

## Update the webpage on GitHub Pages

You'll need [yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable) installed, then:

```
$ npm run deploy
```

See all the details in this blog:
[How to Deploy a React App to GitHub Pages](https://www.freecodecamp.org/news/deploy-a-react-app-to-github-pages/)

Note: you can skip the **Routing in React** section, since `whalebeats` is a single page React app.
