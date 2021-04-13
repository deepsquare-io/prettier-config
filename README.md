# `@csquare/prettier-config`

[csquare-ai](https://github.com/csquare-ai)'s official [Prettier](https://prettier.io) configuration.

Proudly maintained by:

- Mathieu Bour <[mathieu@csquare.ai](mailto:mathieu@csquare.ai)>
- Clarisse Tarrou <[clarisse@csquare.ai](mailto:clarisse@csquare.ai)>

## Installation

```bash
npm install --dev @csquare/prettier-config
```

Then, ensure that your `package.json` file contains the entry:

```json
{
  "prettier": "@csquare/prettier-config"
}
```

## Plugins

In addition to the Prettier default rules, we also use the following plugins:

- [@trivago/prettier-plugin-sort-imports](https://github.com/trivago/prettier-plugin-sort-imports)

## References

- [Prettier - Sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations)
