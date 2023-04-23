---
title: Funções do tema Gitbook
date: 2023-04-22
layout: post
---

Suportado pela sintaxe [kramdowh](https://kramdown.gettalong.org/quickref.html#block-attributes)


# Tabelas
## Sintaxe
```markdown
<div class="table-wrapper" markdown="block">

|title1|title2|title3|title4|title5|title6|title7|title8|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|

</div>
```
## Resultado
<div class="table-wrapper" markdown="block">

|title1|title2|title3|title4|title5|title6|title7|title8|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|

</div>


# Mensagens
## Sintaxe
```
> mensagem
{: .block-tip}
>mensagem
{: .block-warning}
>mensagem
{: .block-danger}
```
## Resultado
> mensagem
{: .block-tip}
>mensagem
{: .block-warning}
>mensagem
{: .block-danger}
