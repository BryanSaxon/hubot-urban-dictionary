# hubot-urban-dictionary
A package for Hubot that allows you to look up definitions via Urban Dictionary.

#### Note:
Be aware that this script usually returns responses that are NSFW so use at your
own risk.

## Installation
You need to set up an account with Mashape at https://www.mashape.com in order
to use this package. Once you have signed up:

* Add a new application
* Go to https://www.mashape.com/community/urban-dictionary and create a
  X-Mashape-Key for your new application
* Grab your X-Mashape-Key from your curl REQUEST EXAMPLE
* Add your key to your enviornment variables with the name HUBOT_MASHAPE_KEY
* Add hubot-urban-dictionary to your dependancies in the package.json file and
  in your exteranl-scripts.json file (Note that you will also need to grab the
  latest version from https://www.npmjs.com/package/hubot-urban-dictionary to
  add to the package.json)
* run `npm install` to download the package
* Enjoy ;)

## Usage
This package listens for the word `define` and returns the first definition and
examples from Urban Dictionary.

#### Example:
`define stories`

#### Returns:
**Definition:**

What white-trash call Television shows.

**Example:**

Bubba, run to the Piggly Wiggly and pick mamma up some smokes. I don't want to
miss my stories.

## License
See LICENSE for details.
