# General

## What's this?

This is a repository for candidates who applies to junior `frontend` and junior `fullstack` positions, using `ReactJS` framework.
This repo was originally created for myself to test juniors whether they are able to met the requirements they need to fulfill.

## How does this repo works?

The repository's structure is the following:

```
junior-fullstack
├── README.md
├── solutions
└── tasks
    └── 1
        └── index.md
```

The tasks are located in the `tasks` folder in an index ordered list.

# Solutions

If you want your solutions to be tested, follow theese steps:

0. set up a project using [`create-react-app`](https://github.com/facebook/create-react-app)
1. solve the task
1. clone this repo
1. create a new branch with your github `<username>` and `<filetaskId>`
1. `cd solutions/<taskorder>`
1. create a folder with your github username (eg `mkdir zilahir`)
1. put your solutions to this folder
1. don't forget to create detailed `readme.md` of your solution!
1. `commit` and `push` your changes to your cloned repository.
1. create a PR to this repo, and i'll review it. If it's good, i'll merge it to this repo to help others in the future when they needed.
1. be proud of your work!

## Rules

1. Please do _not_ use `class` based components, only [`stateless function`](https://www.robinwieruch.de/react-function-component#react-stateless-function-component) components. _Hey, it's almost 2020, right?-_ :wink:

Example:

```
/**
* @author zilahir
* @function MenuItem
* */

const Example = () => (
	<div>hello world</div>
)

export default MenuItem
```

**NOTE:** Please comment your components under the import section, so it's purpose will be clearly stated.

2. Use the `package.json` file, to see the pre-given `devDependencies`, and other important stuff.

3. Both [`redux`](https://github.com/reduxjs/redux) and [`react-hooks`](https://reactjs.org/docs/hooks-intro.html) (and `contect API`) can be used when it's needed.

As you can see a few package added that help you keep the basic rules of writing applications, such as:

[`prettier`](https://github.com/prettier/prettier)
[`eslint`](https://github.com/eslint/eslint)
[`husky`](https://github.com/typicode/husky)
[`lint-staged`](https://github.com/okonet/lint-staged)

Please use the entries given in `package-example.json` to start your project, and have all those settings, which will help you write better quality of code.

If the tasks requires to write css, the following rules applies.

Do _not_ write and `import` `css` files. Either use one of the powerful `css-in-js` solutions (such as [`styled-components`](https://github.com/styled-components), or [`emotion`](https://github.com/emotion-js/emotion)) or [`css-moduless`](https://create-react-app.dev/docs/adding-a-css-modules-stylesheet/)

4. Write as _generic_ functions and components as possible, to avoid _code repeating_.
5. Use meaninful function and variable names.

## Structure

Example:

```
├── components
│   ├── Example
│   │   └── index.js
│   └── common
│       ├── Example
│       │   └── index.js
```

This just an example given to you to get the idea of having some structure given to your project with all the files well organized. It will be helpful also during develoment, and then later to maintain it.

## Misc

If you have a question, just open an issue here.

Happy coding! :smile:
