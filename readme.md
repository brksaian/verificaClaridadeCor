# Color Checker

Este projeto é uma aplicação web simples que permite ao usuário selecionar uma cor usando um seletor de cores e verificar se a cor selecionada é clara ou escura. A interface exibe uma amostra da cor selecionada e uma mensagem indicando se a cor é "light" (clara) ou "dark" (escura).

## Funcionalidades

- **Seletor de Cores**: Permite que o usuário escolha qualquer cor utilizando um seletor de cores (`<input type="color">`).
- **Verificação de Claridade**: Após a seleção da cor, a aplicação determina se a cor escolhida é clara ou escura com base em sua luminância.
- **Exibição Dinâmica**: A cor selecionada é mostrada em uma caixa de amostra e uma mensagem abaixo indica se a cor é clara ou escura.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

## Como Funciona

### Algoritmo de Verificação de Claridade

A verificação de claridade é realizada utilizando a luminância da cor selecionada. A luminância é calculada com base nos valores RGB da cor, utilizando a seguinte fórmula:

Luminance = 0.2126 * R + 0.7152 * G + 0.0722 * B


Se a luminância for superior a 128, a cor é considerada clara (`light`), caso contrário, é considerada escura (`dark`).

### Estrutura do Código

- **index.html**: Contém a estrutura HTML básica e o seletor de cores.
- **style.css**: Define o estilo da página, incluindo a exibição da caixa de cor e do texto de resultado.
- **script.js**: Contém a lógica JavaScript para determinar se a cor é clara ou escura.

## Como Usar

1. Clone ou faça o download do repositório.
2. Abra o arquivo `index.html` em seu navegador.
3. Utilize o seletor de cores para escolher uma cor.
4. A cor selecionada será exibida na caixa, e o texto abaixo da caixa indicará se a cor é clara ou escura.

## Estrutura do Projeto

. ├── index.html # Página principal do projeto ├── style.css # Arquivo de estilos CSS └── script.js # Lógica JavaScript


## Demonstração

Ao escolher uma cor, a caixa mudará de cor para a cor selecionada e o texto indicará se a cor é "light" ou "dark".

## Exemplo de Uso

Ao carregar a página, o seletor de cores exibe a cor branca (`#ffffff`) por padrão, indicando que é uma cor "light". Quando o usuário seleciona uma cor diferente, a caixa de cor e o texto são atualizados automaticamente para refletir a nova seleção.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações.
