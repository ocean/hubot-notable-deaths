# Hubot "Notable" Deaths

# not working yet

[![Build Status](https://img.shields.io/travis/ocean/hubot-tucker.svg?style=flat-square)](https://travis-ci.org/ocean/hubot-tucker) [![Dependency Status](https://david-dm.org/ocean/hubot-tucker.svg?style=flat-square)](https://david-dm.org/ocean/hubot-tucker) [![npm version](https://img.shields.io/npm/v/hubot-tucker.svg?style=flat-square)](https://www.npmjs.com/package/hubot-tucker) [![npm downloads](https://img.shields.io/npm/dt/hubot-tucker.svg?style=flat-square&label=total%20downloads)](https://www.npmjs.com/package/hubot-tucker) [![npm recent downloads](https://img.shields.io/npm/dm/hubot-tucker.svg?style=flat-square&label=recent%20downloads)](https://www.npmjs.com/package/hubot-tucker)

[Hubot](https://hubot.github.com) will tell you about recent "notable" deaths, drawn from the [Wikipedia recent deaths](https://en.wikipedia.org/wiki/Deaths_in_2016) page. Created by [@ocean][1].

## Installation

1. Add **hubot-notable-deaths** to your `package.json` file:

  ```json
  "dependencies": {
    "...": "*",
    "hubot": "*",
    "hubot-notable-deaths": "*",
    "...": "*",
  }
  ```

1. Add **hubot-notable-deaths** to your `external-scripts.json`:

  ```json
  ["hubot-notable-deaths"]
  ```

1. Run `npm install`

## Usage

Your Hubot will now respond with an insult whenever addressed with *"&lt;&lt;Hubot name&gt;&gt; tucker"*, or whenever the word "Malcolm", "Malc"<sup>1</sup> or "Tucker" is used in the chat room (case insensitive).

## Credits

Deaths are from the Wikipedia Recent deaths page.
 
Drew Robinson, [@ocean][1].

[![Follow ocean on Twitter](https://img.shields.io/twitter/follow/ocean.svg?style=social)][1]

[1]: https://twitter.com/ocean
