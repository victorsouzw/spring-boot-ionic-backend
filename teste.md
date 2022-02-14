# Um documento em Markdown

## Sobre o Markdown

O Markdown Ã© uma linguagem de marcaÃ§Ã£o muito simples, desenvolvida por
John Gruber.

A ideia bÃ¡sica por trÃ¡s da linguagem Ã© fazer com que o escritor se
preocupe mais com o **conteÃºdo** do texto do que com a *formataÃ§Ã£o*.

## Mais um tÃ­tulo

Aqui vamos tentar descrever uma anÃ¡lise.

## Simulando variÃ¡veis aleatÃ³rias

No R podemos simular valores de uma distribuiÃ§Ã£o normal padrÃ£o atravÃ©s
da funÃ§Ã£o `rnorm()`.

Seja $X \sim \text{N}(0,1)$, entÃ£o para gerar 30 valores dessa variÃ¡vel
aleatÃ³rio normal, fazemos

```
(x <- rnorm(30))
```

Com o resultado dessa simulaÃ§Ã£o, podemos calcular a mÃ©dia e a variÃ¢ncia
dessa VA $X$ para conferir se o resultado fica prÃ³ximo de 0 e 1,
respectivamente.

TambÃ©m podemos fazer um histograma dessa VA $X$ simulada

```
hist(x)
```
