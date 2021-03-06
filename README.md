# containers.css

> A starting point for container and gaps when you don't want to use Bootstrap and you can't go evergreen with CSS Grid.

![GitHub](https://img.shields.io/github/license/morsecodemedia/containers.css.svg?color=green&label=license)
![NPM](https://img.shields.io/npm/v/@morsecodemedia/containers.css)
![npm](https://img.shields.io/npm/dt/@morsecodemedia/containers.css)

## Installation
**YARN**
```sh
yarn add -D @morsecodemedia/containers.css
```

**NPM**
```sh
npm install -D @morsecodemedia/containers.css
```

## Adding to project
### Nuxt.js
In the `nuxt.config.js` file
```js
css: [
  '@morsecodemedia/containers.css'
]
```

## Browser support
* Chrome
* Edge
* Firefox ESR+
* Internet Explorer 10+
* Safari 8+
* Opera

## Containers
Containers are the max-width areas in which content blocks can take up. Currently there are three (1-3), 1 being the widest and 3 being the most narrow.
### A Visual Representation
https://morsecodemedia.github.io/containers.css/

### Containers Breakdown

#### 0px-767px
`.container1` 100% - 30px (15px on either side)

`.container2` 100% - 30px (15px on either side)

`.container3` 100% - 30px (15px on either side)

#### 768px-991px
`.container1` 100% - 50px (25px on either side)

`.container2` 100% - 70px (35px on either side)

`.container3` 100% - 110px (55px on either side)

#### 992px-1199px
`.container1` 100% - 70px (35px on either side)

`.container2` 100% - 200px (100px on either side)

`.container3` 100% - 400px (200px on either side)

#### 1200px-1399px
`.container1` 100% - 100px (50px on either side)

`.container2` 100% - 300px (150px on either side)

`.container3` 100% - 500px (250px on either side)

#### 1400px+
`.container1` max-width: 1300px

`.container2` max-width: 1000px

`.container3` max-width: 700px

## Gaps
Gaps are vertical spacing used between columns to keep a consistent vertical rhythm among containers. Currently there are four gaps (1-4). 1 being the smallest and 4 being the tallest.

### Gaps Breakdown

#### 0px-767px
`.gap1` 10px

`.gap2` 15px

`.gap3` 20px

`.gap4` 30px

#### 768px-1199px
`.gap1` 15px

`.gap2` 20px

`.gap3` 30px

`.gap4` 40px

#### 1200px+
`.gap1` 20px

`.gap2` 30px

`.gap3` 40px

`.gap4` 50px

## Content Blocks
`.half` `.half`

`.forty` `.sixty`

`.sixty` `.forty`

`.third` `.third` `.third`

`.quarter` `.quarter` `.quarter` `.quarter`

`.third` `.two-third`

`.two-third` `.third`

`.quarter` `.three-quarter`

`.three-quarter` `.quarter`
