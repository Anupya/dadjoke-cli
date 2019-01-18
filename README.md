# Dad Joke CLI
A simple Command Line Interface (CLI) to bring you the freshest dad jokes straight to your terminal.

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

Find more information about installing jq [here](https://stedolan.github.io/jq/download/).    

Second, run the following command in your terminal:

```
curl "https://raw.githubusercontent.com/Anupya/dadjoke-cli/master/dadjoke" -o /usr/local/bin/dadjoke && chmod +x /usr/local/bin/dadjoke
```

## Usage

You are all set! Go ahead and enter this in your terminal to receive a fresh dad joke every time.

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




