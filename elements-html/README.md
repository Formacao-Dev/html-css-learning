# Entendendo os comandos e tags HTML5

**O HTML5 assim como qualquer outra linguagem ao ser atualizada, além de receber novo comandos, aposenta outros0.** Dessa forma, você pode acompanhar no artigo abaixo, as tags que permanecem em uso no HTML5 e as tags que foram descontinuadas e só servem para as versões anteriores.

---

### Tags Continuadas:
```html
- <!--...--> Define um comentário;
- <!DOCTYPE> Define o tipo de documento; (No HTML 4 existiam três (3) diferentes tipos de doctype, mas no HTML 5 temos apenas um (1) tipo <!DOCTYPE HTML>. É aqui que o navegador entende o tipo de documento e como ele deve interpretar as tags nele contidas.)
- <a> Define um hyperlink;
- <abbr> Define uma abreviação
- <address> Define um endereço. (Passa a ser tratado como uma seção);
- <area> Define uma área dentro de um mapa de imagem;
- <b> Define um texto em negrito; (Possui o mesmo nível semântico que um SPAN, e também o estilo de negrito no texto. Contudo, ele não dá nenhuma importância para o texto marcado com ele.)
- <base> Define uma base URL para todos os links da página;
- <bdo> Define a direção do texto apresentado;
- <blockquote> Define uma citação longa;
- <body> Define o corpo da página;
- <br> Insere uma quebra de linha simples;
- <button> Define um botão de comando;
- <caption> Define o "caption" de uma tabela;
- <cite> Define uma citação;
- <code> Define o código texto do computador;
- <col> Define os atributos da coluna da tabela;
- <colgroup> Define um grupo de colunas da tabela;
- <dd> Define uma descrição de definição;
- <del> Define um texto deletado;
- <dfn> Define um termo de definição;
- <div> Define uma seção no documento;
- <dl> Define uma lista de definição;
- <dt> Define um termo de definição;
- <em> Define um texto em ênfase;
- <fieldset> Define um conjunto de campos (fieldset);
- <form> Define um formulário;
- <h1> até >h6> Define do cabeçalho 1 até o cabeçalho 6;
- <head> Define uma informação sobre o documento. (Não aceita mais elementos Child como filho);
- <hr> Define uma regra horizontal. (Tem o mesmo nível que um parágrafo, mas também é utilizado para fazer separações e quebras de linha);
- <html> Define um documento html;
- <i> Define um texto em itálico; (Possui o mesmo nível semântico que um SPAN. O texto continua sendo itálico e para usuários de leitores de tela, a voz utilizada é modificada para indicar ênfase. É de grande valor e utilidade para marcar, termos técnicos, termos em outras linguagens etc.)
- <iframe> Define uma linhas sobre a janela (frame);
- <img> Define uma imagem;
- <input> Define um campo de inserção;
- <ins> Define um texto inserido;
- <kbd> Define um texto do teclado;
- <label> Define uma "label" para o formulário;
- <legend> Define um título para os campos (fields);
- <li> Define os itens da lista;
- <link> Define uma referência;
- <map> Define uma imagem de mapa;
- <menu> Define uma lista de "menus";
- <meta> Define informações meta;
- <noscript> Define uma seção noscript;
- <object> Define um objeto incorporado;
- <ol> Define uma lista ordenada;
- <optgroup> Define um grupo de opção;
- <option> Define uma opção em uma lista suspensa (drop-down list);
- <p> Define um parágrafo;
- <param> Define um parâmetro para determinado objeto;
- <pre> Define um texto pré-formatado;
- <q> Define uma citação curta;
- <s> Define um texto que não é mais correto.
- <samp> Define um código de amostra;
- <script> Define um script;
- <select> Define uma lista selecionável;
- <small> Define um pequeno texto;
- <span> Define uma seção no documento;
- <strong> Define um texto forte (similar ao negrito);
- <style> Define um estilo;
- <sub> Define um texto subscrito;
- <sup> Define um texto sobrescrito;
- <table> Define uma tabela;
- <tbody> Define o corpo da tabela;
- <td> Define uma célula da tabela;
- <textarea> Define um área de texto;
- <tfoot> Define o rodapé da tabela;
- <th> Define o cabeçalho da tabela;
- <thead> Define o cabeçalho da tabela;
- <title> Define o título do documento;
- <tr> Define uma linha da tabela;
- <ul> Define uma lista desordenada;
- <var> Define uma variável;
```


---

### Tags Descontinuadas:
```html
- <acronym> Define siglas em HTML 4.01. (Desenvolvedores preferem utilizar a tag <abbr>);
- <applet> Define um miniaplicativo incorporado. (Ficou obsoleto em função da tag <object>);
- <basefont> Define as propriedads da font padrão para todo o texto do documento. (Apenas efeito visual);
- <big> Usado para tornar o texto maior. (Apenas efeito visual);
- <center> Usado para alinhar texto e conteúdo no centro. (Apenas efeito visual);
- <dir> Define a lista do diretório. (Ficou obsoleto em função da Tag <ul>);
- <font> Especifica o tipo de fonte, tamanho, e cor do texto. (Apenas efeito visual);
- <frame> Define uma janela particular dentro de um conjunto de "frames". (Fere princípios de usabilidade e acessibilidade);
- <frameset> Define um conjunto de frames organizado por múltiplas janelas.(Fere princípios de usabilidade e acessibilidade);
- <noframes> Texto exibido para navegadores que não lidam com "frames". (Fere princípios de usabilidade e acessibilidade);
- <strike> Exibe texto rasurado. (Apenas efeito visual);
- <tt> Define teletipo de texto. (Apenas efeito visual);
- <u> Define sublinhado. (Apenas efeito visual);
- <xmp> Define texto pré-formatado. (Ficou obsoleto em função da tag <pre>);
```


Se analisarmos bem as definições podemos perceber que muitas tags descontinuadas tiveram esse fim por já existirem tags que realizam a mesma função. E ao utilizar o **HTML 5 você perceberá que algumas tags continuadas foram modificadas e passaram a exercer outras propriedades**, fazendo, também, que outras tags percam valor.

> Nota 1: Você pode ouvir em algum lugar sobre HTML - ArqHP (Arquitetura de Home Pages). É o próprio HTML 5 com outra denominação e isso é apenas uma jogada de marketing.

> Nota 2: **Os HTML 1, HTML 2 , HTML 3 e o HTML 4 estão todos contidos no HTML 5** e mesmo as tags descontinuadas não trazem nenhum problema de compatibilidade com o HTML 5 e o contrário também ocorre, onde as novas tags também não trazem nenhum problema de compatibilidade com as versões antigas.


### HTML5 DOCTYPE e as Tags link e script
A tag **<DOCTYPE>** é a primeira que aparece em um documento HTML e indica para o browser o tipo e versão do documento que está sendo aberto.

Na **HTML5** o **DOCTYPE** ficou mais simples, com relação à **HTML4.1**. Observe as listagens a seguir.


`Listagem 1: HTML4.1 DOCTYPE`
```hmtl
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
 "http://www.w3.org/TR/html4/strict.dtd">
```

Agora fica apenas:

`Listagem 2: HTML5 DOCTYPE`

```html
<!DOCTYPE html>
```

Nas tags link e script, utilizadas para referenciar arquivos **CSS** e **JavaScript**, respectivamente, não é mais necessário informar o atributo **type=”text/css”** ou **text=”text/javascript”**, como era feito na HTML 4.1.

As listagens a seguir mostram como eram essas tags na HTML4.1 e como são agora na HTML5.

`Listagem 3: HTML4.1 LINK e SCRIPT`
```hmtl
<link rel="stylesheet" type="text/css" href="arquivo.css">
<script type="text/javascript" src="arquivo.js"></script>
```

E agora, na HTML5:

`Listagem 4: HTML5 LINK e SCRIPT`
```hmtl
<link rel="stylesheet" href="arquivo.css">
<script src="arquivo.js"></script>
```

