# Curso de Programação Avançada Front End

### Aula 1
**Data:** 09/12/2022

#### Introdução

Semântica x Sintaxe.

Tag `canvas`: permite parte gráfica de HTML com API.

As partes do site são definidas pelas seguintes tags:

- section;
- article;
- nav;
- aside;
- header;
- footer.

Tag `embed`: uso de plugins.

Tag `progress`: representa dados em progresso. Exemplo: download de um arquivo.

Conteúdo que envolve hora, semanticamente é correto colocar a tag `<time> </time>`.

Hoje em dia já é possível fazer validação de dados "inputados" pelo usuário, eliminando a necessidade de validação em scripts externos.

Criação do atributo `required` que exige e indica a obrigatoriedade do preenchimento de um campo dentro de um formulário.

A tag `<i>` que antes era itálico agora representa informações em outras línguas ou um novo tom de voz para leitores de tela.

#### Boas práticas em JavaScript

1. Não utilizar `document.write()`;
2. Para efeito de performance, colocar o caminho para o arquivo externo no fim da tag `body` em vez de usar o `defer`;
3. Todas as variáveis booleanas devem começar com `is`. Exemplo: `usernameIsNull()`, `usernameIsShort()`;
4. Nomeie variáveis e funções de forma lógica. Por exemplo: `popUpWindowForAd` ao invés de `myWindow`;
5. Não faça reduções ao nomear variáveis com exceção de `i` (interador). Dentro dos laços `for` os nomes devem ser longos o suficiente para entender o que aquele pedaço de código fará;
6. Documentação deve seguir o padrão Natural Docs (tipo javadoc);
7. Constantes ou variáveis de configuração (duração de animações por exemplo) devem ficar no começo do arquivo;
8. Reduza variáveis globais - quantos menos as criar, melhor;
9. Esforce-se para criar funções que possam ser generalizadas, ter parâmetros e valores de retorno;
10. Todas as variáveis Javascript devem ser escritas apenas com minúsculas ou cammelCase. A única exceção para este caso é se estiver criando Constructor Functions, quais começam com maiúsculas por tradição.

#### Conceito Mobile-First

Criar a aplicação partindo de um dispositivo móvel.

**Media query:** consiste de um *media type* e pelo menos uma expressão que limita o escopo das folhas de estilo usando *media features*, tal como lagura, altura e cor. **Isso não é mobile-first**.

Ler a página da MDN Docs Usndo Media Queries. 