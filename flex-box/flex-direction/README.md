## flex-direction

A propriedade `flex-direction` deve ser aplicada ao container e define o eixo/fluxo de exibição em que os elementos serão organizados. A sintaxe e os valores possíveis para essa propriedade são apresentados a seguir:

```css
.container {
	display: flex;
	flex-direction: [row / row-reverse / column / column-reverse];
}
```

-   **row** (padrão): Os itens são organizados em forma de linha da esquerda para a direita;
-   **row-reverse**: Os itens são organizados em forma exibição em linha da direita para a esquerda;
-   **column**: Os itens são organizados em forma de colunas iniciando de cima para baixo;
-   **column-reverse**: Os itens são organizados em forma de colunas iniciando de baixo para cima.

A Figura 3 ilustra o funcionamento de cada valor.

![](https://arquivo.devmedia.com.br/artigos/Fernando_gaspar/flex/flex-direction.png)
<br/>
`Figura 3. Funcionamento da propriedade flex-direction`
