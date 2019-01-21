# Dad Joke CLI
A simple Command Line Interface (CLI) to bring you the freshest dad jokes straight to your terminal.

[![HitCount](http://hits.dwyl.com/Anupya/dadjoke-cli.svg)](http://hits.dwyl.com/Anupya/dadjoke-cli) ![](https://img.badgesize.io/Anupya/dadjoke-cli/master/dadjoke.svg) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![](https://raw.githubusercontent.com/Anupya/dadjoke-cli/master/screenshot.png)

All data is from [icanhazdadjoke](https://icanhazdadjoke.com/api).

## Installation

First, install jq which is a command line json parser using this command:

### Mac
```
brew install jq
```

### Windows
```
chocolatey install jq
```

### Linux
```
sudo apt-get install jq
```

Find more information about installing jq [here](https://stedolan.github.io/jq/download/).    

Second, run the following command in your terminal:

```
curl "https://raw.githubusercontent.com/Anupya/dadjoke-cli/master/dadjoke" -o /usr/local/bin/dadjoke && chmod +x /usr/local/bin/dadjoke
```

## Usage

You are all set! Enter this in your terminal to receive a new dad joke :)

```
dadjoke
```

## Development

```
git clone https://github.com/Anupya/dadjoke-cli.git
cd dadjoke-cli
vim dadjoke
```

## License

MIT License

## Accomplishments

Trended #5 on ProductHunt on Jan 20, 2019 (150+ upvotes)
Written in 1 line

