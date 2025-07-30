
# BEM (Block, Element, Modifier)

> Gustavo Trajano Dos Reis Padilha
> 
> Desenvolvedor Front-End

## Introdução

Uma metodologia de nomenclatura para classes CSS que busca tornar o código mais organizado, reutilizável e fácil de manter. Ela é muito útil, especialmente quando se trabalha com projetos grandes, pois ajuda a estruturar o CSS de forma que ele seja semântico e modular.

## Aplicações e benefícios

### Onde é utilizado ?

A metodologia BEM é amplamente utilizada em projetos Front-end que exigem uma estrutura CSS escalável, organizada e reutilizável. É aplicada em frameworks modernos, bibliotecas e equipes que trabalham com:

-Desenvolvimento de componentes reutilizáveis

-Sistemas de design (Design Systems)

-Aplicações web de médio e grande porte

-Integração com metodologias ágeis e times colaborativos

-Frameworks 
### Quais problemas ele resolve ?

| Problema comum em CSS tradicional      | Como o BEM resolve?                                |
| -------------------------------------- | -------------------------------------------------- |
| Classes genéricas e ambíguas           | Usa nomes semânticos e específicos por contexto    |
| Dificuldade de manter projetos grandes | Torna o CSS modular e previsível                   |
| Estilos colidindo entre componentes    | Utiliza nomenclatura única com estrutura clara     |
| Baixa reusabilidade de componentes     | Permite variações com modificadores (modularidade) |
| CSS difícil de escalar ou debugar      | Estrutura lógica e padronizada facilita manutenção |

### Quais são as vantagens ?

| Vantagem                   | Descrição                                                       |
| -------------------------- | --------------------------------------------------------------- |
| Organização                | Classes seguem um padrão que facilita leitura e entendimento    |
| Modularidade               | Componentes são independentes e reaproveitáveis                 |
| Previsibilidade            | A estrutura das classes evita conflitos e surpresas no layout   |
| Facilidade em Times        | Ajuda múltiplos devs a entenderem e manterem o CSS              |
| Integração com ferramentas | Funciona bem com SCSS, SASS, BEMIT, e arquiteturas CSS modernas |

## Exemplo Prático

```
<style>
css
CopiarEditar
/* Bloco */
.button {
  background-color: blue;
  padding: 10px;
  border-radius: 5px;
}

/* Elemento dentro do bloco */
.button__text {
  color: white;
  font-size: 16px;
}

/* Modificador para variação do bloco */
.button--primary {
  background-color: green;
}

/* Modificador para variação do elemento */
.button__text--large {
  font-size: 20px;
}

</style>

```

## Conclusão

A metodologia BEM se mostrou uma solução eficiente para problemas comuns no desenvolvimento CSS, como conflitos de estilos, falta de organização e dificuldade de manutenção em projetos maiores. Ao estruturar o código de forma semântica, modular e previsível, o BEM facilita a escalabilidade e a colaboração entre desenvolvedores.

## Fontes utilizadas

-https://desenvolvimentoparaweb.com/css/bem/
-https://codigoaoponto.com/blog/a-maneira-correta-de-utilizar-a-nomenclatura-bem
-https://www.youtube.com/watch?v=mj6Ze34qGtc


link para os slides

https://www.canva.com/design/DAGt0LgxXpw/FT5oogpOhXV3TAr0PWqwlQ/edit?utm_content=DAGt0LgxXpw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
