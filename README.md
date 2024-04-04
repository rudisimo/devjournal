# Rudy's Dev Journal

## Quickstart

Setup Dev Container environment:

```shell
git submodule update --init --recursive
devcontainer open .
```

Update `blowfish` theme:

```shell
git -C themes/blowfish fetch
git -C themes/blowfish checkout <GITREF>
git add themes/blowfish
git submodule update --init --recursive --remote
```

## License

Licensed under the [MIT](LICENSE.txt) license.
