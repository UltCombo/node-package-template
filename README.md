# Node.js Package Template

A simple template for creating modern Node.js packages.

## Set up

- Download latest source, unzip it to your new Node.js package's root.
- Fill in `package.json` fields, such as name, description, author, repository url and license.
- `git init && git commit --allow-empty -m 'chore: Init repository'`
- `yarn install`

## What's included

- Lint with ESLint.
- Format with Prettier, running as an ESLint plugin.
- Test and report coverage with Jest.
- Precommit hook to lint, format, test and check coverage.
- Lint commit messages.
