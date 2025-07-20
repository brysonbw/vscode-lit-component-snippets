# Lit Component Snippets

Visual Studio Code extension for adding lit component snippets.

![snippets in action](https://res.cloudinary.com/ddlhtsgmp/video/upload/v1752985509/lit-component-snippets.gif)

## Features

These snippets are opinionated and include common lifecycle hooks, decorators, etc. I've also added a few JSDoc snippets, which are also opinionated.

## Snippets

### Lit JavaScript

| Prefix             | Description                                                       |
|--------------------|-------------------------------------------------------------------|
| litwc              | Lit Web Component in JavaScript                                   |
| litwclccc          | Lit Web Component Lifecycle: connectedCallback() in JavaScript    |
| litwclcdc          | Lit Web Component Lifecycle: disconnectedCallback() in JavaScript |
| litwclcfu          | Lit Web Component Lifecycle: firstUpdated() in JavaScript         |
| litwclcu           | Lit Web Component Lifecycle: updated() in JavaScript              |
| litwclcr           | Lit Web Component Lifecycle: render() in JavaScript               |
| litwcinternalstate | Lit Web Component Internal Reactive State in JavaScript           |
| litwcgetter        | Lit Web Component Getter in JavaScript                            |
| litwcmethod        | Lit Web Component Method in JavaScript                            |

### Lit JavaScript With JSDoc Annotations

| Prefix           | Description                                                                              |
|------------------|------------------------------------------------------------------------------------------|
| litwcjsdoc       | Lit Web Component in JavaScript with JSDoc Annotations                                   |
| litwcjsdoclccc   | Lit Web Component Lifecycle: connectedCallback() in JavaScript with JSDoc Annotations    |
| litwcjsdoclcdc   | Lit Web Component Lifecycle: disconnectedCallback() in JavaScript with JSDoc Annotations |
| litwcjsdoclcfu   | Lit Web Component Lifecycle: firstUpdated() in JavaScript with JSDoc Annotations         |
| litwcjsdoclcu    | Lit Web Component Lifecycle: updated() in JavaScript with JSDoc Annotations              |
| litwcjsdoclcr    | Lit Web Component Lifecycle: render() in JavaScript with JSDoc Annotations               |
| litwcjsdocgetter | Lit Web Component Getter in JavaScript with JSDoc Annotations                            |
| litwcjsdocmethod | Lit Web Component Method in JavaScript with JSDoc Annotations                            |

### JSDoc

> I'm sure there are other JSDoc snippets available, but I've included a few within Lit Component Snippets.

| Prefix         | Description                 |
|----------------|-----------------------------|
| jsdoctdobj     | JSDoc TypeDef Object        |
| jsdoctd        | JSDoc TypeDef               |
| jsdoctypewdesc | JSDoc Type With Description |
| jsdoctype      | JSDoc Type                  |

### Lit Typescript

| Prefix             | Description                                                       |
|--------------------|-------------------------------------------------------------------|
| litwc              | Lit Web Component in Typescript                                   |
| litwclccc          | Lit Web Component Lifecycle: connectedCallback() in Typescript    |
| litwclcdc          | Lit Web Component Lifecycle: disconnectedCallback() in Typescript |
| litwclcfu          | Lit Web Component Lifecycle: firstUpdated() in Typescript         |
| litwclcu           | Lit Web Component Lifecycle: updated() in Typescript              |
| litwclcr           | Lit Web Component Lifecycle: render() in Typescript               |
| litwcgetter        | Lit Web Component Getter in Typescript                            |
| litwcmethod        | Lit Web Component Method in Typescript                            |
| litwcinternalstate | Lit Web Component Internal Reactive State in Typescript           |

## Contributing

Contributions are welcome! If you have suggestions on additonal snippets reach out and [message me on discord](https://discordapp.com/users/805262289119739924). Also, feel free to submit a pull request by adding your snippet(s) to any of the `.json` files in `/snippets`.

### Run And Test Extension Locally

1. Clone repository.
2. `cd` into repository.
3. Press `F5` to open a new window.
4. Create a new file with a file name suffix matching languages, which are `.js` and `.ts`.
5. Verify that your snippet(s) are proposed on IntelliSense.

### Make Changes

- You can relaunch the extension from the debug toolbar after making changes to the `/json` files in `/snippets`.
- You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.
