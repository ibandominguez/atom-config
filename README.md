# Atom Config

Personal atom config &amp; packages

## How to use it

Make sure you have installed atom https://atom.io/, Ideally you would clone this repo on a fresh
atom installation

```sh
cd ~/.atom
git clone https://github.com/ibandominguez/atom-config.git .
rm -rf .git
```

## Useful commands

```sh
apm list # List all packages [--installed --bare]
apm list --installed --bare > package-list.txt # Write a file with all packages
apm install --packages-file package-list.txt  # Install from file
apm star --installed # Star all installed packages (Requires Token)
```

## License

MIT
