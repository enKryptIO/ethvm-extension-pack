# Ethvm Extension pack

A collection of extensions for setting up your vscode environment for Development of Ethvm:Ethereum Blockchain Explorer

### Extensions Included
* [Go for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go)
* [Editorconfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
* [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [ident-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
* [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
* [dotenv](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

## Installing Ethvm Extension Pack

### Step 1

Download  [ethvm.vsix](https://github.com/enKryptIO/ethvm-extension-pack/releases/download/0.0.1/ethvm-extension-pack.vsix)

### Step 2

Go to extension Tab in Visual studio code, from options press Install from Vsix

![Step 2 Screenshot](.github/assets/step.png)

This will install ethvm package extension into Visual studio code.

## Build from Source

### Step 1

Clone ethvm-extension-pack

```sh
$ git clone https://github.com/enKryptIO/ethvm-extension-pack/
```

### Step 2

Install vsce

```sh
yarn global add vsce
```

### step 3

pack extension

```sh
vsce package
```

This will package extension into a .vsix file and place it in the current directory

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
