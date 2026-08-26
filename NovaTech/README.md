# TechNova Studios

Projeto desenvolvido para a atividade prática de criação de layout responsivo com **CSS Flexbox**.

## Conceitos de Flexbox

- **`display: flex;`**: Aplicado nas seções `header`, `hero`, `services-container`, `about`, `contact-form` e `footer`.
- **`flex-direction`**: Utilizado em modo `row` para organizar itens lado a lado em telas grandes e alterado para `column` via media queries no layout mobile.
- **`justify-content`**: Usado para distribuição de espaço como `space-between` no cabeçalho e `center` no container de serviços.
- **`align-items`**: Empregado para o alinhamento vertical dos elementos centrais (`center`).
- **`flex-wrap`**: Aplicado na seção de serviços e formulário para permitir a quebra fluida de linha quando a largura diminui.
- **`gap`**: Controla o espaçamento direto entre os flex-items sem necessidade de `margins` externas.
- **`flex-grow` / `flex-shrink` / `flex-basis`**: Utilizados na propriedade abreviada `flex` nos cards de serviços (`flex: 1 1 280px`) e nos campos do formulário.
- **`order`**: Aplicado na media query da seção "Sobre nós" para alterar visualmente a posição da imagem em telas menores.
