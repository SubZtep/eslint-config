# My ESLint defaults

## Install

### Create required config files

#### .eslintrc

```
root: true
extends:
  - plugin:subztep/recommended
```

#### .editorconfig

```
root = true

[*]
charset = utf-8
end_of_line = lf
max_line_length = 120
insert_final_newline = true
trim_trailing_whitespace = true

[*.{js,ts}]
indent_style = space
indent_size = 2

[*.php]
indent_style = space
indent_size = 4
```

#### .prettierrc

```
semi: false
trailingComma: none
arrowParens: avoid
```
