## align-content

Essa propriedade define como as linhas são distribuídas ao longo do eixo transversal do container. A sintaxe e os valores possíveis para essa propriedade são apresentados a seguir:

```css
.container {
	display: flex;
	align-content: [stretch/flex-start/flex-end/center/space-between/space-around];
}
```

-   **stretch** (padrão): As linhas são distribuídas uniformemente ao longo do eixo transversal, ocupando todo o espaço disponível;
-   **flex-start**: As linhas são distribuídas a partir do início do eixo transversal;
-   **flex-end**: As linhas são distribuídas a partir do fim do eixo transversal;
-   **center**: As linhas são mantidas no centro do eixo transversal;
-   **space-between**: A primeira linha é deslocada para o início do eixo transversal, a última é deslocada para o final do eixo transversal e as demais são distribuídas uniformemente entre eles;
-   **space-around**: As linhas são uniformemente distribuídas ao longo do eixo transversal. Aqui, porém, são atribuídas margens iguais à esquerda e à direita (ou acima e abaixo, dependendo da direção do eixo transversal). Por isso a primeira e a última linha não ficam “coladas” nas bordas do container.

A Figura 5 ilustra o funcionamento de cada valor:

`Figura 5. Funcionamento da propriedade align-content`
![](https://arquivo.devmedia.com.br/artigos/Fernando_gaspar/flex/align-content.png)
