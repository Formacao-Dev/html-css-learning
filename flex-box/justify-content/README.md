## justify-content

A propriedade `justify-content` define o alinhamento dos itens ao longo do eixo principal do container. A sintaxe e os valores possíveis para essa propriedade são apresentados a seguir:

```css
.container {
	display: flex;
	justify-content: [flex-start/flex-end/center/space-between/space-around];
}
```

-   **flex-start** (padrão): Os itens são alinhados a partir do início do eixo principal;
-   **flex-end**: Os itens são alinhados a partir do fim do eixo principal;
-   **center**: Os itens são alinhados ao centro do eixo principal;
-   **space-between**: O primeiro item é deslocado para o início do eixo principal, o último é deslocado para o final do eixo principal e os demais são distribuídos uniformemente entre eles;
-   **space-around**: Os itens são uniformemente distribuídos ao longo do eixo principal. Aqui, porém, são atribuídas margens iguais à esquerda e à direita (ou acima e abaixo, dependendo da direção do eixo principal). Por isso o primeiro e o último item não ficam “colados” nas bordas do container.

A Figura 4 ilustra o funcionamento de cada valor:

![](https://arquivo.devmedia.com.br/artigos/Fernando_gaspar/flex/justify-content.png)
<br/>
`Figura 4 Representação da propriedade justify-content`
