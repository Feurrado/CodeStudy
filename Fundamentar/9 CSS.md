 # Box model

- Fundamental para layout web
- Maior facilidade ao aplicar CSS

## What is it?

Uma caixa retangular pode ter os seguinter atributos

- Tamanho (largura x altura)   widht/height
- Conteúdo                     content
- Bordas                       border
- Preenchimento interno        padding
- Espaços fora da caixa        margin

Cada elemento na página será considerado uma caixa.




# Box sizing

Como calcular o tamanho total da caixa?

- content-box / border-box

'''css
div {
    box-sizing: border-box;
}
'''

<div> {
    widht: 100px;
    height: 100px;
    border: 1px solid red;
    margin: 10%;
    padding: 0 20px;

    box-sizing: border-box;
}
</div>




## Display: block vs Display: inline

**block**

ocupado toda a linha, colocando o próximo elemento abaixo desse

widht e height são respeitados

padding, margin, border irão funcionar normalmente

**inline**

Elemento ao lado do outro

widht e height não funcionam

Somente valores horizontais de margin, padding e border funcionarão

*Exemplos*
<!-- block: '<p> <div> <section>, todos os heading '<h1><h2>...'
inline: '<a> <strong> <span> <em> g-->

<div>um conteúdo</div> Outro conteúdo

<p>um <strong>texto</strong> qualquer </p>

## Margin

Espaços entre os elementos

- margin-top / margin-right / margin-bottom / margin-left
- values: '<lenght>' / '<percentage> / auto

'''css
div {
    /*shorthand*/
    margin: 12px 16px 10px 4px;
    margin: 12ox 16px 0;
    margin: 8px 16px;
    margin: 8px;
}
'''

<!-- margin collapsing (top junta com bottom) -->

mozilla.org CSS margin

## Padding

Preenchimento de uma caixa

- padding-top / padding-right / padding-bottom / padding-left
- values: '<lenght>' / '<percentage>' /

'''css
div{
    /*shorthand*/
    (conteúdo de padding px)
}
'''

<!-- Padding poderá causar diferença na largura -->

mozilla.org CSS padding

## Border e outline

As bordas da caixa

- value: '<border-style>' / '<border-widht>' / '<border-color>'

- style: solid / dotted / dashed / double / groove / ridge / inset / outset
- widht: '<lenght>'
- color: '<color>'

OUTLINE

- Não modifica o tamanho da caixa, não é parte do box model
- Poderá ser diferente de retangular
- Não permite ajuste individual
- mais usada pelo user agent para acessibilidade

mozilla.org CSS border