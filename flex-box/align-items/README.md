## align-items

Essa propriedade define como os itens são distribuídos ao longo do eixo transversal do container. A sintaxe e os valores possíveis para essa propriedade são apresentados a seguir:

```css
.container {
	display: flex;
	align-items: [stretch/flex-start/flex-end/center/baseline];
}
```

-   **stretch** (padrão): Os itens serão esticados para preencher toda a dimensão do eixo transversal (altura ou largura);
-   **flex-start**: Os itens são deslocadas para o início do eixo transversal;
-   **flex-end**: Os itens são deslocadas para o final do eixo transversal;
-   **center**: Os itens são centralizados no eixo transversal;
-   **baseline**: Os itens são alinhados a partir da base da primeira linha de texto de cada um.

A Figura 6 ilustra o funcionamento de cada valor:

`Figura 6. Representação da propriedade align-items`
![](https://arquivo.devmedia.com.br/artigos/Fernando_gaspar/flex/align-items.png)
