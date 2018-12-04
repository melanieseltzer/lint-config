# Eslint and Prettier config

> Common Eslint and Prettier config for my projects ✨

A setup for Eslint and Prettier that I've come to use quite frequently. This is just to organize everything in one place, so I can get started quickly in the future. Also has my setup for Husky and lint-staged.

I extend the [Airbnb style guide](https://github.com/airbnb/javascript/) with a couple rules tweaked or turned off.

My code style can be summed up as:

- Indent lines with spaces, not tabs
- Use single quotes, not double
- Spaces between brackets in object literals
- Semi-colons at the end of statements
- No trailing commas
- Don't include parenthesis around a sole arrow function parameter

## Usage

Clone the repo:

```
git clone git@github.com:melanieseltzer/lint-config.git
```

Or alternatively, just download a zip from Github.

Then copy the `package.json` and dotfiles into the new project, and install dependencies:

```
yarn install
```

And you're good to go!