Defina a função `composicao` que recebe 3 argumentos, nessa ordem:

* Um número, `x`
* Uma função, `f`
* Outra função, `g`

As funções `f` e `g` têm apenas um argumento numérico cada uma. Por exemplo, _f(x) = 2x_ e _g(x) = x+3_.

A função `composicao` deve, então, aplicar _f_ a _x_ e, em seguida, aplicar _g_ sobre o resultado. Matematicamente, isso equivale a _g(f(x))_.

Por exemplo, se _f(x)=2x_ e _g(x)=x+3_, então `composicao(7, f, g)` deve retornar 17, pois o dobro de 7 é 14, que ao ser acrescido de 3, retulta 17.
