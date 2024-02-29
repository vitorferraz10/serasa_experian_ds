# Design system serasa

Design system serasa is a comprehensive collection of design tokens to ensure consistency and efficiency in building user interfaces across projects.

## Installation

Use the package [npm](https://docs.npmjs.com/cli/v8/commands/npm-install) to install ds-serasa.

```bash
npm i ds-serasa
```

## Usage

```javascript
import { tokens } from "ds-serasa";

# configurando thema para usar com styled-component em react
export const theme = {
  ...tokens
}

# Usando tokens nos componentes react
export const Title = styled.h1`
  color: ${({theme}) => theme.colors.text.brand.default};
  font-size: ${({theme}) => theme.font.size.desktop.body_m};
  font-family: ${({theme}) => theme.font.family.body};
`
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
