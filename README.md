![](https://img.shields.io/badge/Microverse-blueviolet)

# Hello Microverse

> In this project, you will set up a "Hello world" repository. No complex coding is required for this exercise. Your goal here is to master all of the tools and best practices you learned about in previous steps.

![screenshot](./app_screenshot.png)

This project can be used as a template for future projects.

## Built With

- HTML
- CSS
- Linters workflow

## Live Demo

[Live Demo Link](https://lfmnovaes.github.io/Hello-Microverse/) (Not online yet)

## Getting Started

To get a local copy and make linters working follow these steps:

### Prerequisites
[NodeJS LTS](https://nodejs.org/en/download/)

### Setup

Run git clone on this project
   ```
   git clone https://github.com/lfmnovaes/Hello-Microverse.git
   ```

### Install

Run
   ```
   npm install
   ```
To install all dependencies for the project.

### Usage
Open the website with any Browser (preferably with Google Chrome).

### Run tests

#### [Lighthouse](https://developers.google.com/web/tools/lighthouse)
You can get the Lighthouse report by any of the following ways:

- [In Chrome DevTools](https://developers.google.com/web/tools/lighthouse#devtools)
- [From the command line](https://developers.google.com/web/tools/lighthouse#cli)
- [As a Node module](https://developers.google.com/web/tools/lighthouse#programmatic)
- [From a web UI](https://developers.google.com/web/tools/lighthouse#psi)

#### [Webhint](https://webhint.io/)

A customizable linting tool that helps you improve your site's accessibility, speed, cross-browser compatibility, and more by checking your code for best practices and common errors.

1. Run
   ```
   npm install --save-dev hint@6.x
   ```
   (not sure how to use npm? Read [this](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)).
2. Copy [.hintrc](.hintrc) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run
   ```
   npx hint .
   ```
5. Fix validation errors.

#### [Stylelint](https://stylelint.io/)

A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.

1. Run

   ```
   npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
   ```

   (not sure how to use npm? Read [this](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)).

2. Copy [.stylelintrc.json](./.stylelintrc.json) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run
   ```
   npx stylelint "**/*.{css,scss}"
   ```
   on the root of your directory of your project.
5. Fix linter errors.
6. **IMPORTANT NOTE**: feel free to research [auto-correct options for Stylelint](https://stylelint.io/user-guide/cli#autofixing-errors) if you get a flood of errors but keep in mind that correcting style errors manually will help you to make a habit of writing a clean code!

### Deployment

Download the main

## Authors

👤 **Luís Fernando**

- GitHub: [@githubhandle](https://github.com/lfmnovaes)
- Twitter: [@twitterhandle](https://twitter.com/lfmnovaes)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/lfmnovaes/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- It is far easier to design a class to be thread-safe than to retrofit it for thread safety later.

## 📝 License

This project is [MIT](./MIT.md) licensed.
