# Conversor de Unidades

Este projeto é uma aplicação web simples que converte unidades de medida (metros, quilômetros, centímetros e milímetros) utilizando JavaScript para a lógica de conversão e CSS para a estilização da interface.

## Tecnologias Utilizadas

### JavaScript
- **Document Object Model (DOM) Manipulation**: Utiliza a API do DOM para selecionar e manipular elementos HTML. Funções como `document.querySelector` são usadas para capturar elementos e interagir com eles.
- **Event Handling**: Gerencia eventos de usuário através de `addEventListener`. Um evento de clique (`click`) é associado ao botão de conversão (`convertButton`).
- **Estruturas de Controle**: Faz uso de condicionais (`if` e `switch`) para controlar o fluxo da aplicação, verificando as unidades selecionadas e realizando a conversão de valores.
- **Funções**: Organiza o código em funções, encapsulando a lógica de conversão na função `convert`.

### HTML
- A estrutura básica da aplicação é construída em HTML, com elementos como `<input>`, `<select>` e `<button>`, que são manipulados pelo JavaScript para criar a interface de usuário interativa.

### CSS
- **Box Model**: Usa `box-sizing: border-box;` para garantir que o padding e a borda sejam incluídos na largura e altura dos elementos.
- **Flexbox**: Utiliza `display: flex;` para centrar a aplicação vertical e horizontalmente dentro da página, criando uma interface centralizada e responsiva.
- **Estilos Visuais**: Estiliza elementos com propriedades como `background-color`, `border-radius`, `box-shadow`, `padding`, `margin` e `font-family` para criar uma interface moderna e atraente.
- **Transições**: Implementa o efeito `hover` no botão de conversão (`button:hover`) para melhorar a experiência do usuário, fornecendo feedback visual.
- **Responsividade**: Usa propriedades de layout flexível e tamanhos de fonte relativos para garantir que a aplicação se adapte bem a diferentes tamanhos de tela.

## Funcionalidades Principais
- **Seleção de Unidades**: Usuários podem selecionar unidades de entrada e saída a partir de listas suspensas (`<select>`), permitindo conversões entre metros, quilômetros, centímetros e milímetros.
- **Conversão de Unidades**: A função `convert` lida com a lógica de conversão, transformando valores de entrada para a unidade desejada através de operações matemáticas simples.
- **Interatividade**: A aplicação responde a eventos de clique, executando a conversão e atualizando a interface com o resultado e uma mensagem descritiva.

## Estrutura do Código

### HTML
Contém elementos de formulário (`<input>`, `<select>`, `<button>`) para a entrada de dados e visualização dos resultados.

### CSS
- **Estilização Global**: Define margens, paddings e fonte padrão para todos os elementos.
- **Estilização do Container**: Centraliza o container principal com `display: flex` e estiliza para uma aparência limpa e moderna.
- **Estilização de Inputs e Botões**: Personaliza campos de entrada e botão de conversão para uma interface amigável.

### JavaScript
- **Seleção de Elementos**: Elementos HTML são selecionados e armazenados em variáveis usando `document.querySelector`.
- **Conversão de Valores**: O valor de entrada é convertido primeiro para metros, e então para a unidade de saída desejada. A conversão é realizada através de condicionais que determinam o fator de conversão apropriado.
- **Atualização da Interface**: O resultado da conversão é exibido tanto no campo de saída (`outputElement`) quanto em uma mensagem descritiva (`messageElement`), fornecendo feedback ao usuário.

Este projeto exemplifica o uso de JavaScript e CSS para criar uma aplicação web interativa e funcional, integrando manipulação do DOM, eventos, lógica de programação e design responsivo.
