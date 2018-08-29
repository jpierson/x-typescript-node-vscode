#  A minimal setup to Debug TypeScript on Node in VSCode

Please note that this repository serves as an example of one way that I've found to set up a minimal project which allows for debugging TypeScript that is running on Node in VSCode. At the time of writing I've only tested on a x64 based Windows 10 machine and have not verified that the same steps work in a multitude of other configurations or environments. Please note also the [prerequisites](#prerequisites) as well as an indication of what worked for me.

## Prerequisites: 

* VSCode (tested with v1.25.1)
* NodeJS (tested with v0.10.9)
* NPM (tested with v6.1.0)

## Run in VSCode

To get started first clone this repo:

```
> git clone https://github.com/jpierson/x-typescript-node-vscode
```

Install node package dependencies (typescript and ts-node):

```
> npm install
```

Start up VSCode if you haven't already (tested with VSCode v1.25.1):

```
> code .
```

Set a breakpoint on one of the lines such as line 5 in [index.ts](/index.ts) and start debugging by pressing the `F5` key or select `Debug: Start Debugging` form the VSCode command pallet.