## flex-flow

Esta propriedade é uma forma abreviada para a escrita das propriedades `flex-direction` e `flex-wrap`, nesta ordem. Portanto, ela se aplica ao container.

Normalmente essas propriedades são definidas uma a uma, da seguinte forma:

```css
.container {
	display: flex;
	flex-direction: column;
	flex-wrap: wrap;
}
```

Já com o flex-flow podemos escrever as duas de forma simplificada:

```css
.container {
	flex-flow: column wrap;
}
```
