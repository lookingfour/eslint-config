# eslint-config

An eslint configuration that is being used by LookingFour.

## Installation

You can install the package and its basic peer dependencies by running:

```sh
npm install --dev eslint@^8 @typescript-eslint/eslint-plugin@^7 @typescript-eslint/parser@^7 eslint-config-prettier@^9 @lookingfour/eslint-config
```

You should also install the following peer dependencies to be able to use the `react` eslint configuration:

```sh
npm install --dev eslint-config-standard-jsx@^11 eslint-plugin-react@^7 eslint-plugin-react-hooks@^4
```

If you will be using the `next` eslint configuration, you should to install the `react` configurations peer dependencies plus the following:

```sh
npm install --dev eslint-config-next@^14
```

## Usage

You can extend from one of our preset configurations:

```json
{
  "extends": ["@lookingfour/eslint-config/service"]
}
```

Available configurations are:

- `@lookingfour/eslint-config/service`
- `@lookingfour/eslint-config/react`
- `@lookingfour/eslint-config/next`
