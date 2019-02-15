# Developer's Guide

We use Visual Studio Code for developing LoopBack and recommend the same to our
users.

## VSCode setup

Install the following extensions:

 - [tslint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
 - [prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Development workflow

### Visual Studio Code

1. Start the build task (Cmd+Shift+B) to run TypeScript compiler in the
   background, watching and recompiling files as you change them. Compilation
   errors will be shown in the VSCode's "PROBLEMS" window.

### Other editors/IDEs

1. Open a new terminal window/tab and start the continous build process via
   `npm run build:watch`. It will run TypeScript compiler in watch mode,
   recompiling files as you change them. Any compilation errors will be printed
   to the terminal.
