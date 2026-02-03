# Formação HTML notas de aula

## Links e estrutura
Recomenda-se a extenção live server de Ritwick Dey  
w3scholls - https://www.w3schools.com/

## Introdução so HTML
* Por convenção a página principal do site se chama **index.html**
### Estrutura do HTML
É composto por 3 partes:  
- **html:** indica o início e o fim do arquivo
- **head:** que será carregado antes dos conteúdos serem exibidos.
- **body:** o que será exibido ao usuário.  
```
<html>
    <head>
        <title>o que vai escrito na aba</title>
    </head>
    <body>
        CORPO (o que o ususário vê)
    </body>
</html>
```
### Tags
- Tags tem abertura e fechamento.
- Uma barra determina o fechamento.
- Tudo o que estiver entre tags o navegador irá interpretar conforme a tag.  

**`<strong>`** texto que ficará em negrito **`<\strong>`**  
### Atributos das tags
- Atributos são propriedades que as tags tem.
- Existem atributos que são genéricos (quase todas as tags tem) e outros que apenas tags específicas tẽm.  
- É possível colocar mais de um atributo por tag.

**Exemplos de Atributos**
- **id:**  é um especificador de um elemento. `<strong id="título">`
- **style:** é usado para aplicar estilos (voltado ao css) `<strong style="color: blue;">`
- **class:** também é usado para css. `<strong class="titulo-principal">`
- **type:** este pertence à tag input edefine o tipo de entrada, números, texto, cor, etc... `<input type="color">`  
### Tags de Textos (Tipografia)

- **\<blockquote> :**  usado para citações.
- **\<mark> :**  usado para emular um marca texto.
- **\<h1> :**  usado para títulos, o número muda a ênfase (1 é maior).
- **\<sup> :**  Texto em cima.

### Listas ordenadas e não ordenadas
As listas precisam de um componente filho para indicar os itens, esses itens são indicados pela tag **\<li>** (List Item).  
É possível colocar listas dentro de itens de lista também.
- **\<ol> :**  lista ordenada, vai ordenando por letras ou números sequenciais.
- **\<ul> :**  lista sem ordem, apenas coloca uma indicação de lista como um traçoou bullet.

### links
Para fazer links usa-se âncoras, por isso a tag se chama  \<a>
\<a href="https://google.com">link para google\</a >
#### Alguns atributos para links
- **href="..." :** endereço destino
- **target="_self" :** abrirá na mesma página 
(padrão)
- **title="dica" :** mostra um tooltip (balãozinho)

#### Ancoragem
Para fazer ancoragem link para a mesma página precisa definir o ID da âncora, para isso coloca um "#" na \<href>, como no exemplo abaixo(âncora surgimento):  
```
<a href="#surgimento">Surgimento da TI</a>  
....
....
<h2 id="surgimento">Surgimento da TI</h2>
```
