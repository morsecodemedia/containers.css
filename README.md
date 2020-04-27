# containers.css

> A starting point for container and gaps when you don't want to use Bootstrap and you can't go evergreen with CSS Grid.

![GitHub](https://img.shields.io/github/license/morsecodemedia/containers.css.svg?color=green&label=license)
![NPM](https://img.shields.io/npm/v/@morsecodemedia/containers.css)

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
  'containers.css/dist/css/containers.css'
]
```

## Browser support
* Chrome
* Edge
* Firefox ESR+
* Internet Explorer 10+
* Safari 8+
* Opera

## Containers Breakdown
### 0px-767px
`.container1` 100% - 30px (15px on either side)

`.container2` 100% - 30px (15px on either side)

`.container3` 100% - 30px (15px on either side)

### 768px-991px
`.container1` 100% - 50px (25px on either side)

`.container2` 100% - 70px (35px on either side)

`.container3` 100% - 110px (55px on either side)

### 992px-1199px
`.container1` 100% - 70px (35px on either side)

`.container2` 100% - 200px (100px on either side)

`.container3` 100% - 400px (200px on either side)

### 1200px-1399px
`.container1` 100% - 100px (50px on either side)

`.container2` 100% - 300px (150px on either side)

`.container3` 100% - 500px (250px on either side)

### 1400px+
`.container1` max-width: 1300px

`.container2` max-width: 1000px

`.container3` max-width: 700px

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

## TODO
* Write up better documentation.