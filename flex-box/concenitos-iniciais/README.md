## Topicos

O **Flexbox** é um conjunto de propriedades que tem por objetivo organizar itens dentro de um elemento pai, normalmente chamado de container, conforme ilustra a **Figura 1**.

`Figura 1 Estrutura dos elementos para aplicação do Flexbox`
![](https://arquivo.devmedia.com.br/artigos/Fernando_gaspar/flex/estrutura_elementos.png)

Portanto, para utilizar esse recurso é necessário ter no HTML ao menos um elemento (container) contendo outros (itens), como no código abaixo:

```html
<div class="container">
	<div class="item item1"></div>
	<div class="item item2"></div>
	<div class="item item3"></div>
</div>
```

---

## Alinhamento dos eixos

Para entender o **funcionamento do Flexbox** é necessário ter em mente alguns conceitos fundamentais que dizem respeito a como os itens são distribuídos no container. O principal deles é o conceito de eixo principal e eixo transversal, que depende do valor atribuído à propriedade flex-direction. Se essa propriedade receber o valor row ou row-reverse (organização em linhas), o eixo principal do container será o horizontal. Já se essa propriedade receber o valor column ou column-reverse (organização em coluna), o eixo principal será o vertical. Consequentemente isso definirá qual é o eixo transversal. Se o principal for o vertical, o transversal será o horizontal e vice-versa.

Na Figura 2 podemos ver esse e outros conceitos ilustrados para o caso de o eixo principal ser o horizontal.

![](https://arquivo.devmedia.com.br/artigos/Fernando_gaspar/flex/alinhamento.png)
`Figura 2. Alinhamento dos eixos do Flexbox`

-   **Tamanho principal**: É a dimensão do elemento na direção do eixo principal (largura, caso horizontal e altura caso vertical);
-   **Tamanho transversal**: É a dimensão do elemento na direção do eixo transversal (largura, caso horizontal e altura caso vertical);
-   **Início principal e final principal**: Representam o início e o fim do eixo principal;
-   **Início transversal e final transversal**: Representam o início e o fim do eixo transversal.
