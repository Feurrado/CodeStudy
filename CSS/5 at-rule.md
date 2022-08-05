# at-rules

* Está relacionado ao comportamento do CSS
* Começa com o sinal de '@' seguido do identificador e valor

## Exemplo comund

- @import          /* incluir um css externo */
- @media           /* regras condicionais para dispositvos */
- @font-face       /* fontes externas */
- @keyframes       /* animation */

'''css

@import url("http://local.com/style.css");

@media (min-widht: 500px) {
    /* rules here */
}

@font-face {
    /* rules here */
}

@keyframes nameofanimation {
    /* rules here */
}