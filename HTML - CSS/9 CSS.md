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
block: '<p> <div> <section>, todos os heading '<h1><h2>...'
inline: '<a> <strong> <span> <em>
