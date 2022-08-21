# shorthand

* junção de propriedades
* resumido
* legível

'''css

{
    /* background properties */
    background-color: #000;
    backuground-image: url(image/bg.gif);
    background-repeat: no-repeat;
    background-position: left top;

    /* background shothand */
    background: #000 url(images/bg.gif) no-repeat left top;

    Shorthand você alinha tudo e simplifica.
}

## Detalhes

* não considera propriedade anteriores
* valores não especificados irão assumir valor padrão
* geralmente a ordem descrito não importa mas se houver muitas propriedades com valores semelhantes, poderemos encontrar problemas

Caso precise saber todas

**https://developer.mozilla.org/pt-BR/docs/Web/CSS/Shorthand_properties**