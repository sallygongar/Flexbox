## Flexbox & BEM

============

## General Info

#### What's flexbox
It was designed as a one-dimensional layout model, and as a method that can help distribute the space of the elements of an interface
and improve alignment capabilities.

#### What's REM
It is a naming methodology for defining classes in HTML nodes, to later configure them with CSS
The goal of BEM is to give much more transparency and clarity to the HTML and CSS structure

BEM are 3 acronyms

* B of BLOCK - block
* E of ELEMENT - block__element
* M of Modifier - block__element--modifier


A block is a section ind

Example
```
<div class="block">
    <div class="block__element">Elem 1</div>
    <div class="block__element">Elem 2</div>
    <div class="block__element block__element--modifier">Elem 3</div>
</div>

<!-- EJEMPLO 2 -->
<div class="item item--modifier">
    <div class="item__element">Elem 1</div>
    <div class="item__element">
        <div class="item__another-element">Elem 2</div>
        <div class="item__another-element">Elem 3</div>
    </div>
    <div class="item__element item__element--modifier">Elem 4</div>
</div>

```

## TECHNOLOGIES
* HTML 5
* CSS
* BEM naming
* Visual studio Code
* Plugin GO Live of Visual Code

## SEPTUP
1. Open the folder from visual Code
2. Install Go live plugin
3. Press go live at the bottom

## Source

This information was obtained in AnimatiCSS
(
  https://animaticss.com/articulo/que-es-bem-css/
  https://animaticss.com/articulo/b-de-bloque-bem-css/
)