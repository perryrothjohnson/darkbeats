# spacebeats

This project was forked from [whalebeats](https://github.com/lizrothjohnson/whalebeats). We swapped out the whale sounds with space sounds from [NASA](https://soundcloud.com/nasa/popular-tracks) and [ESA](https://soundcloud.com/esa/popular-tracks).

## List of samples

Audio samples are located in `public/audio` and listed in `src/samples.json`. The original sources of these samples are listed below:

1. [comet-67p-rosetta-singing-magnetic-field](https://soundcloud.com/esa/a-singing-comet)
2. [comet-tempel-1-stardust-dust-particles](https://soundcloud.com/nasa/stardust-passing-comet-tempel-1)
3. [earth-emfisis-radio-waves](https://soundcloud.com/nasa/chorus-radio-waves-within-earths-atmosphere)
4. [enceladus-cassini-plasma-waves](https://soundcloud.com/nasa/enceladus-hiss-audio)
5. [ganymede-galileo-radio-emissions](ganymede-galileo-radio-emissions)
6. [jupiter-juno-bow-shock](https://soundcloud.com/nasa/juno-crossing-jupiters-bow-shock)
7. [jupiter-voyager-lightning](https://soundcloud.com/nasa/voyager-lightning-on-jupiter)
8. [mars-percy-rover-driving](https://soundcloud.com/nasa/sounds-of-perseverance-mars-rover-driving-sol-16-90-second-highlights)
9. [mars-percy-rover-filtered-first-sounds](https://soundcloud.com/nasa/first-sounds-from-mars-filters-out-rover-self-noise)
10. [mars-percy-rover-first-sound-recording](https://soundcloud.com/nasa/perseverance-mars-supercam-sounds-18-hours-after-landing)
11. [saturn-cassini-radio-emissions](https://soundcloud.com/nasa/cassini-saturn-radio-emissions-1)
12. [star-kic12268220c-kepler-light-curve-waves](https://soundcloud.com/nasa/stardust-passing-comet-tempel-1)
13. [sun-soho-natural-vibrations](https://soundcloud.com/nasa/sun-sonification)

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

Note: you can skip the **Routing in React** section, since `spacebeats` is a single page React app.
