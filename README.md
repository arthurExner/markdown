# Dominando Markdown
Linguagem de marcação para formatar o README.
- [Dominando Markdown](#dominando-markdown)
  - [Títulos](#títulos----etc)
  - [Texto](#texto)
  - [Imagens](#imagens-)
  - [Links](#links-)
  - [Listas](#listas)
    - [UL](#ul-)
    - [OL](#ol-1)
  - [Blockquote](#blockquote-)
  - [Código](#código-)
  - [Task List](#task-list-------x)
  - [Tabelas](#tabelas)
## Títulos: \# \## \### etc...
# (h1)
## (h2) 
### (h3)
#### (h4)
##### (h5)
###### (h6)
## Texto:
Deixando em **negrito**. \**

Deixando em _itálico_. \_ _

_**Combinando**_. \_**
## Imagens: \!\[]()
![Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/175px-Markdown-mark.svg.png)

Utilizando \!\[]() não consigo modificar as dimensões.

Para isso utilizo a tag HTML \<img scr heigth width>.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/175px-Markdown-mark.svg.png" width="100px" heigth="75px">

## Links: \()[]
[LinkedIn](https://www.linkedin.com/in/arthur-exner-63a4431ba/)

## Listas:
### UL: \*
* Criando UL
* Usando Markdown

ou com - 

- Criando UL
  - sublista usando dois espaços
### OL: 1.
1. Criando OL.
    1. (Tab + 1.)
    2. Criando
    3. Sublista
2. Usando Markdown.
    1. De novo. (Tab + 1.)


## Blockquote: \>
>BlockQuote: destacando esta área
>
>Quebro linha com \> vazio

## Código: \```

```
git commit -m "MD learning"
```
Em JS: \`\`\`js
```js
function helloWorld(){
    console.log("Hello, world!")
}
```
Em Java: \`\`\`java
```java
public void helloWorld(){
    System.out.println("Hello, world!");
}
```
Posso fazer com html, css, etc...

## Task List: \- [ ] \- [x]
- [x] Feito
- [ ] Não Feito

## Tabelas: 
Nome | Peso (kg) | Altura (m) | Foto
-----|-----------|------------|-----
Arthur| 74 | 1,79 | <img src="img/newMe.jpg" width="100" title="eu">
Katchussia| 55 | 1,55|<img src="https://uxwing.com/wp-content/themes/uxwing/download/peoples-avatars/female-face-icon.svg" width="100" title="alguem">