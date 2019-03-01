---
tags: Apresentações, RPGTools
---

# RPGTools 

## Tecnologia para melhorar seu RPG

## Episódio 1 - Apresentação e _Markdown_!


---

# Quem sou eu?

![Narrando RPG](https://fabiocosta0305.gitlab.io/assets/img/Fabio-RPG.jpg)

----

## Aspectos

+ _RPGista_ Inveterado - Desde os 9 anos de idade
+ Não tem medo de Pagar Mico
+ _Mr. Mickey_ do Fate Masters
+ Fascinado por Fate
+ Fissurado por tecnologia

----

## Fate Masters

<https://fatemasters.gitlab.io>

----

## Rolando +4 Next

<https://rolandomaisquatro.gitlab.io>

----

## Outros Interesses

+ RPG em geral
+ Linux
+ Indycar
+ Cosplay
+ Disney
+ Anime/Manga
+ Software Livre

----

![](https://fabiocosta0305.gitlab.io/assets/img/FabioTARDIS.jpg)

----

![](https://fabiocosta0305.gitlab.io/assets/img/FabioCosplayVsCosplayer.scale.png)

Pagar mico importa! :-)

---

# Objetivo

Mostrar ferramentas úteis que algumas vezes as pessoas podem  não conhecer

----

Muitas tecnologias úteis não estão facilmente acessíveis!

----

+ Desconhecimento
+ Falta de preparação
+ Falta de costume

----

Ferramentas poderosas para uso de narradores

---

# Markdown

----

Linguagem de _Marcação_ de texto

----

Símbolos ou comandos especiais indicam como trechos de texto devem ser formatados

----

Permite uma digitação rápida e uma formatação AINDA mais rápida

----

Portabilidade: muitas ferramentas a usam

----

+ StackEdit
+ Git(hub|lab)
+ Turtl
+ Wordpress
+ Tumblr
+ Blogger
+ HackMD
+ Simplenote
+ Evernote
+ TiddlyWiki
+ Jekyll
+ `...`

----

Popular no mundo da programação:

Fácil continuar editando código e fazendo documentação sem precisar trocar de ferramenta

----

Extensível, mas padronizada pelos usuários:

+ _Markdown Original_ não incluiam imagens e tabelas
    + _GitHub Flavored Markdown_ tornou-se um padrão _de facto_

---

# Introdução ao Markdown

----

Texto puro (ASCII ***ou*** Unicode)

----


Qualquer editor de texto serve...

<span>
<!-- .element: class="fragment" data-fragment-index="1" -->
    ... até mesmo o <i>Bloco de Notas</i>
</span>

----

Normalmente editores usam a extensão `.md`

----

Vamos utilizar exemplos no site <http://hackmd.io>

---

# Formatação básica

----

Cerque o texto com `*` ou `_`

| _**Texto**_ | **_Saída_** |
|--------------|--------------|
| `*Itálico*` ou `_Itálico_` | _Itálico_ |
| `**Negrito**` ou `__Negrito__` | __Negrito__ |
| `***Negrito Itálico***` ou `___Negrito Itálico___` ou `__*Negrito Itálico*__` | ___Negrito Itálico___ |

----

O Primeiro que abriu é o último a ser fechado

+ `__*Negrito Itálico*__` é okay
+ mas `__*Negrito Itálico__*` pode provocar confusão

---

# Títulos de cabeçalho

Comece a linha com `#`... Quanto mais `#`, mais abaixo será

----

```
# Título 1

## Título 2

### Título 3

...
```

----

# Título 1
    
## Título 2
    
### Título 3

---

# Listas

+ Use `1.` para listas numeradas e `+` ou `-` para listas de tópicos

----

```
1. A
2. B
3. C
e

+ A
+ B

e

- A
- B
```

----

1. A
2. B
3. C

e

+ a
+ b

e

- A
- B

----

Pode combinar elementos dentro de uma lista (adicione espaços para níveis)

----

```
1. A
    + A
    + B
2. B
    - A
    - B

e

+ C
    1. A
    2. B

```

----

1. A
    + A
    + B
2. B
    - A
    - B

e

+ C
    1. A
    2. B

---

# Links

```
[Clickando aqui](http://google.com) você vai para o Google

[Clickando aqui][google] você também vai para o Google

[google]: http://google.com

```

----

[Clickando aqui](http://google.com) você vai para o Google

[Clickando aqui][google] você também vai para o Google


[google]: http://google.com

---

# Imagens

`![Texto de Referência](https://meu-link-para-a-imagem.com)`


----

`![All your base are belong to us](https://fabiocosta0305.gitlab.io/assets/presentations/aybabtu.jpg)`

----

![All your base are belong to us](https://fabiocosta0305.gitlab.io/assets/presentations/aybabtu.jpg)

---

# Tabelas

----

```
| a | b |
|---|---|
| 1 | 2 |
```

----

| a | b |
|---|---|
| 1 | 2 |

----

```
| Direita | Centro | Esquerda |
|--:|:-:|-|
| Um texto Grande | Um texto Grande | Um texto Grande |
```

----

| Direita | Centro | Esquerda |
|--:|:-:|-|
| Um texto Grande | Um texto Grande | Um texto Grande |

---

# Citações

Utilize `>` no início de cada linha na qual você deseja usar como citação. Se quiser "descer" níveis, basta colocar mais `>` antes do texto.

----

```
> _"Uma risada pode ser realmente poderosa, porque às vezes 
> ela é a única arma que nós temos"_
>
> ___Roger Rabbit___
```

----

> _"Uma risada pode ser realmente poderosa, porque às vezes ela é a única arma que nós temos"_
>
> ___Roger Rabbit___

---

# Texto "como está"

Cerque o texto desejado com o crase (`), ou então adicione alguns espaços (ao menos 4) antes do texto

----

<pre>
    `Esse texto aparecerá *como é*, e onde coloquei
    os asteriscos não será negritado`
</pre>

----

`Esse texto aparecerá *como é*, e onde coloquei
    os asteriscos não será negritado`


----

Mais útil para programadores: exemplos de código

---

# Por que usar _Markdown_?

----

Editores e ferramentas compatíveis em quantidade

----

Publicação _Online_

----

Facilmente portado de ferramentas

----

Exportação de documento

---

# Usos para _Markdown_

----

## Gerar documentos

+ Fichas
+ Aventuras
+ Relatos de Jogo

<https://fabiocosta0305.gitlab.io/tiddly/pilgrimsoftheflyingtemple.html>

----

## Controle de Mesa

Em especial no _Discord_

---

# Dúvidas?

---

# Obrigado!