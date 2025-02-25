# PVM - PHP Version Manager

A simple bash script to manage multiple PHP versions on Linux and macOS.

## Installation

```bash
curl -o /usr/local/bin/pvm https://raw.githubusercontent.com/smoqadam/pvm/main/pvm
chmod +x /usr/local/bin/pvm
export PATH="$HOME/.pvm/current:$PATH"
```

## Usage

```bash
# Install a PHP version
pvm install 8.2

# Switch PHP version
pvm use 8.2

# List installed versions
pvm list

# Remove a PHP version
pvm uninstall 8.2
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Credits

Inspired by [nvm](https://github.com/nvm-sh/nvm)
