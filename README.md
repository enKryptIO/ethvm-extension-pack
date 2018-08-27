# Ethvm Extension pack

A collection of extensions for setting setting up your vscode environment for Development of Ethvm:Ethereum Blockchain Explorer

### Extensions Included
* [Go for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go)
* [Editorconfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

## Installing Visual studio code Ethvm Extension Pack

### Step 1

Download  ethvm.vsix 

### Step 2

Go to extension Tab in Visual studio code, from options press Install from Vsix

![Step 2 Screenshot](.github/assets/step.png)


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

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
