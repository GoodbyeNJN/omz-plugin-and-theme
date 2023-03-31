# agnoster theme

A ZSH theme forked from the [agnoster theme](https://github.com/agnoster/agnoster-zsh-theme) for oh-my-zsh. It is optimized for me.

# npm plugin

The npm plugin provides completion as well as adding many useful aliases.

To use it, add npm to the plugins array of your zshrc file:

```zsh
plugins=(... npm)
```

## Aliases

| Alias | Command               | Description                                                          |
| ----- | --------------------- | -------------------------------------------------------------------- |
| n     | `npm`                 | The npm command                                                      |
| na    | `npm add`             | Install a package in dependencies (`package.json`)                   |
| nad   | `npm add --save-dev`  | Install a package in devDependencies (`package.json`)                |
| nrm   | `npm remove`          | Remove installed packages                                            |
| nls   | `npm list`            | List installed packages                                              |
| nap   | `npm add --save-peer` | Install a package in peerDependencies (`package.json`)               |
| nga   | `npm add --global`    | Install packages globally on your operating system                   |
| ngls  | `npm list --global`   | List global installed packages                                       |
| ngrm  | `npm remove --global` | Remove global installed packages from your OS                        |
| ngu   | `npm update --global` | Upgrade packages installed globally to their latest version          |
| ni    | `npm init`            | Interactively creates or updates a package.json file                 |
| nin   | `npm install`         | Install dependencies defined in `package.json`                       |
| nr    | `npm run`             | Run a defined package script                                         |
| nrun  | `npm run`             | Run a defined package script                                         |
| nst   | `npm start`           | Run the start script defined in `package.json`                       |
| nln   | `npm run lint`        | Run the lint script defined in `package.json`                        |
| nb    | `npm run build`       | Run the build script defined in `package.json`                       |
| nd    | `npm run dev`         | Run the dev script defined in `package.json`                         |
| nsv   | `npm run serve`       | Run the serve script defined in `package.json`                       |
| nt    | `npm test`            | Run the test script defined in `package.json`                        |
| ntc   | `npm test --coverage` | Run the test script defined in `package.json` with coverage          |
| nu    | `npm update`          | Update packages to their latest version based on the specified range |
| nc    | `npm create`          | Create a project from a create-\* start kit                          |
