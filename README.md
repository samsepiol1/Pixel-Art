## Como fazer?

Os quadrados são a unidade básica que compõe o pixel art neste código HTML e CSS. Eles são representados por elementos <div> no HTML e estilizados usando CSS para criar uma grade de quadrados dentro de uma área específica.A razão pela qual os quadrados são usados é para representar visualmente cada "pixel" na tela de pixel art. Pixel art é uma forma de arte digital na qual as imagens são criadas em uma resolução muito baixa, com cada pixel representando uma cor individual. Neste caso, os quadrados brancos são como pixels em branco em uma tela de pixel art em que você pode aplicar diferentes cores para criar padrões e desenhos.
 
![Logo do R](https://scontent.fnat16-1.fna.fbcdn.net/v/t1.6435-9/102741146_555476091791152_96373435232745376_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGZaXvePKcV9SKyMKsVDRBcRzL5uvKoh_1HMvm68qiH_cpht_JQKdnCNDOeMXqfUKkcCvz4lShUsl53r6c8pCiq&_nc_ohc=tDq-2Z4w1Y4Q7kNvgEltH_h&_nc_ht=scontent.fnat16-1.fna&oh=00_AfD_svWPlRufaus2RB8n5A-Ya9W8KJ-g5RO9vzfxaZnCcw&oe=665CC0ED)
    
Usamos Também CSS para que cada quadrado tenha uma cor: O Código base do HTML é feito da seguinte forma
    
```html
    <div id="conteudo">
        <div class="linhas">
            <div class="quadrados" style="background-color:#fff;"></div>
   ```

<div class="quadrados" style="background-color:#fff;"></div>: Esta é uma tag <div> que representa um quadrado branco dentro da linha. Ela tem a classe "quadrados", que pode ser estilizada ou selecionada da mesma forma que a classe "linhas". Além disso, esta tag também possui um estilo embutido (style) que define a cor de fundo (background-color) como branco (#fff). Isso significa que este quadrado específico será branco.
    

```css
 #conteudo {
    width: 640px;
    height: 640px;
    background-color: #ccc;
    padding: 30px;
}

.linhas {
    background-color: #fff;
    width: 640px;
    height: 20px;
}

.quadrados {
    width: 20px;
    height: 20px;
    float: left;
}
```
            
Essas regras CSS combinadas criam uma grade de quadrados dentro do contêiner principal, com cada quadrado sendo 20x20 pixels e alinhados horizontalmente. A cor de fundo do contêiner principal é cinza claro, enquanto a cor de fundo das linhas é branco, criando um contraste visual entre as linhas e o contêiner.
