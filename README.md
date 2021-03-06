# Crystallize CLI

[![Build Status](https://travis-ci.org/CrystallizeAPI/crystallize-cli.svg?branch=master)](https://travis-ci.org/CrystallizeAPI/crystallize-cli)

Bootstrap an app running on the [headless ecommerce][1] and GraphQL based
[Product Information Management][2] service [Crystallize][3].

## Usage

You'll need the following installed to use Crystallize CLI:

- [Node.js][7] (>=8)
- [Git][8]

To create a new app using Crystallize, simply run the following command:

```sh
npx @crystallize/cli <project-name>
```

This will walk you through creating a project, allowing you to choose which
template and preferences you want to use.

### Templates

The default mode of the Crystallize CLI is to use a template. Each template has
different options that can be chosen to configure the initial project to suit
your needs.

Current templates include:

- Next.js + React

### Boilerplate

You can also initialise a project through one of the various boilerplates
provided by Crystallize. This clones the boilerplate without any customisation
options.

```sh
npx @crystallize/cli <project-name> -b react
```

The current boilerplates include:

- [react][4]: A boilerplate for React powered by Next.js
- [react-native][5]: A boilerplate for React Native
- [flutter][6]: A boilerplate for Flutter

[1]: https://crystallize.com/product
[2]: https://crystallize.com/product/product-information-management
[3]: https://crystallize.com/
[4]: https://github.com/CrystallizeAPI/crystallize-frontend-boilerplate
[5]: https://github.com/CrystallizeAPI/crystallize-react-native-boilerplate
[6]: https://github.com/CrystallizeAPI/crystallize-flutter-boilerplate
[7]: https://nodejs.org
[8]: https://git-scm.com/
