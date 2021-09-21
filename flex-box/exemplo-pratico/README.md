## Exemplo prático

A seguir podemos ver um exemplo prático de uso do Flexbox. Primeiramente temos a estrutura do HTML na qual foram aplicadas as propriedades que vimos anteriormente:

```html
<div class="container">
	<div class="item item1">1</div>
	<div class="item item2">2</div>
	<div class="item item3">3</div>
</div>
```

E abaixo temos o código CSS responsável pela formatação desse layout:

````css
.container {
    background-color: #FF5722;
    height: 100vh;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.item {
    background-color: #0000ff;
    color: #fff;
    padding: 10px;
    margin: 10px 0;
}

.item1{
    height: 100px;
    width: 100px;
}

.item2{
    height: 50px;
    width: 150px;
}

.item3{
    height: 100px;
    width: 200px;
}
```
````

---

<br/>

<a title="RUN" style="line-height: 0px !important;color: #FFF;border: none;background-color: #454545;padding: 10px 25px;" href="https://jsfiddle.net/5ssLdzth/3/" target="_blank">Executar</a>

<br/>

-   **Linha 2**: Definimos a cor do plano de fundo do container para facilitar a visualização;

-   **Linhas 3 e 4**: Definimos a altura e largura do container para ocupar 100% da página;

-   **Linha 5**: Definimos o display flex no container para que as demais propriedades surtam o efeito esperado;

-   **Linha 6**: Com a propriedade flex-direction definida como column definimos que os itens devem ser organizados em coluna (um abaixo do outro);

-   **Linha 7**: Nesta linha definimos que os itens serão centralizados no eixo principal (vertical);

-   **Linha 8**: A propriedade align-items define aqui que os itens serão centralizados também ao longo do eixo transversal (horizontal);

-   **Linhas 11 a 30**: Neste trecho estamos definindo algumas características dos itens. Eles possuem diferentes alturas e larguras, o que facilita a visualização do resultado final (mesmo com diferentes dimensões, o layout é mantido organizado).
