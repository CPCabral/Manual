## Resistência à Pressão Externa

A equação de resistência à pressão externa do tubo depende do regime ao qual ele está submetido, e este é obtido de acordo com a esbeltez do tubo, sendo esta a relação entre o diâmetro externo e a espessura do tubo $D/t$, arredondada em duas casas decimais. Estes regimes caracterizam o modo de falha por colapso, sendo classificados em colapso por escoamento, colapso plástico, colapso de transição e colapso elástico, que devem apresentar valores com arredondamento para o múltiplo de 10 mais próximo. Os limites de esbeltez são dados nas Equações 1, 2 e 3 que se seguem.

_Equação 1:_
$$(D/t)_{Y_p}=\frac{\sqrt{(A-2)^2+8(B+\frac{C}{Y_p})}+(A-2)}{2(B+\frac{C}{Y_p})}$$

_Equação 2:_
$$(D/t)_{Y_p}=\frac{Y_p(A-F)}{C+Y_p(B-G)}$$

_Equação 3:_
$$(D/t)_{PT}=\frac{2+(B/A)}{3(B/A)}$$

Se o $D/t$ do tubo for menor que $(D/t)_{Y_p}$, então o colapso do tubo poderá ocorrer por escoamento, e a resistência ao colapso pode ser calculada pela Equação 4.
_Equação 4:_
$$P_{y_p}=2Y_p\biggr[\frac{(D/t)-1}{(D/t)^2}\biggr]$$


Caso o $D/t$ do tubo esteja entre $(D/t)_{Y_p}$ e $(D/t)_{PT}$, o colapso será plástico, dado pela Equação 5.

_Equação 5:_
$$P_P=Y_p\biggr[\frac{A}{(D/t)}-B\biggr]-C$$


Se o $D/t$ do tubo estiver entre  $(D/t)_{PT}$e $(D/t)_{TE}$ então o tubo estará sujeito ao colapso de transição, que é calculado através da Equação 6.

_Equação 6:_

$$P_T=Y_p\left[\frac{F}{(D/t)}-G\right]$$

Quando o $D/t$ do tubo é maior do que $(D/t)_{TE}$ o tubo pode sofrer um colapso elástico, definido pela Equação 7.

_Equação 7:_
$$P_E=\frac{46,95\times10^6}{(D/t)[(D/t)-1]^2}$$

Nota-se a presença dos fatores A, B, C, F e G, calibrados experimentalmente e aplicados à definição dos regimes plástico e de transição, cujas expressões são apresentadas na norma API/TR 5C3:2008.
