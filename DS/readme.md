Design system serasa
Design system serasa is a comprehensive collection of design tokens to ensure consistency and efficiency in building user interfaces across projects.

Installation
Use the package ds-serasa npm to install ds-serasa.

npm i ds-serasa
Usage
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