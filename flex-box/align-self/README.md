## align-self

Esta propriedade permite sobrescrever no item o comportamento que foi definido pela propriedade align-items.

A sintaxe e os valores possíveis para essa propriedade são apresentados a seguir:

```css
.item2 {
	align-self: [auto/stretch/flex-start/flex-end/center/baseline];
}
```

-   **auto** (padrão): Respeita o comportamento definido no container por meio do - align-items;
-   **stretch**: O item será esticado para preencher toda a dimensão do eixo transversal (altura ou largura);
-   **flex-start**: O item é deslocado para o início do eixo transversal;
-   **flex-end**: O item é deslocado para o final do eixo transversal;
-   **center**: O item é centralizado no eixo transversal;
-   **baseline**: O item é alinhado a partir da base da primeira linha de texto dos demais.
