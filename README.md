# eslint-config-react
huddo eslint config for react

.eslintrc.yaml:

```
  extends:
    - @huddo/eslint-config-react
```

## Bug: Rules with suggestions must set the meta.hasSuggestions property to true
https://github.com/facebook/react/issues/22545

react-hooks has an issue which is only solved in alpha. You might need to install the alpha to resolve

yarn add eslint-plugin-react-hooks@next -D