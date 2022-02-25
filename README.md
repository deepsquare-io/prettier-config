# `@deepsquare/prettier-config`

[deepsquare-io](https://github.com/deepsquare-io)'s official [Prettier](https://prettier.io) configuration.

Proudly maintained by:

- Mathieu Bour <[mathieu@squarefactory.io](mailto:mathieu@squarefactory.io)>
- Clarisse Tarrou <[clarisse@squarefactory.io](mailto:clarisse@squarefactory.io)>
- Valentin Pollart <[valentin@squarefactory.io](mailto:valentin@squarefactory.io)>

## Installation

```bash
pnpm install --dev @deepsquare/prettier-config
```

Then, ensure that your `package.json` file contains the entry:

```json
{
  "prettier": "@deepsquare/prettier-config"
}
```

## Plugins

In addition to the Prettier default rules, we also use the following plugins:

- [@trivago/prettier-plugin-sort-imports](https://github.com/trivago/prettier-plugin-sort-imports)

## References

- [Prettier - Sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations)
