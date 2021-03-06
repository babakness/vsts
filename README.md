# VSCode Typescript Starter Repo

This is a simple starter scaffold for a Typescript server project.

## `npm` Scripts

`watch` will watch the project for changes and build the output to the `build` folder.

`dev` will use `nodemon` and `ts-node` to run enter the project at `src/index.ts`

`repl` will use `ts-node` to enter REPL mode

## Custom Keybindings

### Tasks
`shift+cmd+b` will run the `watch` script

`shift+cmd+m` will run the `dev` script

### Git
`alt+p` will push committed changes

### Editor
`shift+cmd+d` will duplicate a line

### Workbench
`ctrl+f5` will reload the workbench (some changes in the editor are not registered until this happens)

Note: You may need to hold the function key to access f1-f12.

### Specific Side Panels
`alt+1` Toggle Explorer Side Pane

`alt+2` Toggle Search Side Pane

`alt+3` Toggle Git Side Pane

`alt+4` Toggle Debug Side Pane

`alt+5` Toggle Extensions Side Pane

### General Panel Toggles
`alt+0` Toggle Activity Bar Visibility
`alt+9` Toggle Side Bar Visibility
`alt+8` Toggle Status Bar activity


## Notes

Be sure to fill in the project name and description in package.json. Also add author, keywords, and license as needed.

The `now` settings are basic settigns for publishing using `now-cli`. Fill in the `alias` parameter or remove it as needed.

Output targets `es2016` given the presumption that this is for a server/node enviroment. If this scaffolding starter is being used for the browser, the configure `lib: ["es2015"]` and `target: ["es5"]` in `tsconfig.json`