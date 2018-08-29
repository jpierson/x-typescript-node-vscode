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

## Other resources:

1. [Debugging TypeScript from VSCode](https://medium.com/spektrakel-blog/debugging-typescript-from-vscode-3cb3a182bf63)
2. [Debugging TypeScript Mocha Tests With VSCode](https://medium.com/@benlesh/debugging-typescript-mocha-tests-with-vscode-89310051531)
3. [Debugging Node.js apps in TypeScript with Visual Studio Code](https://fettblog.eu/typescript-node-visual-studio-code/)
4. [TypeScript Programming with Visual Studio Code](https://code.visualstudio.com/docs/languages/typescript)
5. [Debugging in Visual Studio Code](https://code.visualstudio.com/docs/editor/debugging)
6. [StackOverflow: How to run Mocha tests written in TypeScript?](https://stackoverflow.com/questions/26977722/how-to-run-mocha-tests-written-in-typescript/35661569#35661569)