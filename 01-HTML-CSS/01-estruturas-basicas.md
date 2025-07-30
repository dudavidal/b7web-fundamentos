# 📘 Explicação estrutura do HTML

Abaixo está a estrutura básica de uma página HTML. Essa base é usada em praticamente todas as páginas web e serve como ponto de partida para qualquer desenvolvimento.

```html
<!DOCTYPE html>

<html>

<head>
    <meta charset="UTF-8" />
    <title>nome da pagina</title>
</head>

<body>
    Corpo do texto
</body>

</html>
```
---
🧠 Explicação de cada parte:
--- 
```html
!DOCTYPE html
```
- Essa linha informa ao navegador que o documento está usando a versão HTML5.
---
```html
<html>
```
- É o elemento raiz da página. Todo o conteúdo HTML deve estar dentro dele.

---
```html
<head>
```
- A seção <head> contém  informações sobre o documento que não são visíveis diretamente na tela.
  
 Nela  você inclui coisas como:

```html
- <meta charset="UTF-8">
```
- Define o conjunto de caracteres como UTF-8, garantindo que acentos e símbolos sejam interpretados corretamente.
  
```html
- <title>
```
- Define o título da aba do navegador.

--- 
```html
<body>
```
- É a parte visível da página. Tudo que você quer que o usuário veja (textos, imagens, botões, etc.) fica dentro do <body>.

