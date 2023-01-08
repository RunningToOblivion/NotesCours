# Construction des probabiliés

## Le mouvement

### Dés simples (sans prise en compte des doubles)

Ω = {2;3;4;5;6;7;8;9;10;11;12}
P(X=2) = 1/36 (1+1)
P(X=3) = 2/36 (1+2;2+1)
P(X=4) = 3/36
P(X=5) = 4/36
P(X=6) = 5/36
P(X=7) = 6/36
P(X=8) = 5/36
P(X=9) = 4/36
P(X=10) = 3/36
P(X=11) = 2/36
P(X=12) = 1/36

### Avec les doubles :

On retire 1/36 à  chaque proba paire puis on ajoute les probas déterminées précédemment, multipliées par 1/36

L'univers est maintenant \[2;35\] . Si on fait 3 doubles, on passe à la case prison dont on parlera plus tard

P(X=2) = 0 (et oui ! vous ne pouvez pas faire un déplacement de 2 cases au monopoly, sauf par les cartes chances dont on parlera aussi plus tard)
P(X=3) = 2/36
P(X=4) = 2/36 (case 2 -> case 4 = un déplacement de 2 donc un double)
P(X=5) = 4/36 + 1/36 \* 2/36 (déplacement de 3 depuis case 2)
P(X=6) = 4/36 + 1/36 \* 2/36 (case 2 -> case 4 -> case 6 revient à 3 doubles donc la prison + cse 2-> 2+2 revient à encore un double)
P(X=7) = 6/36 + P(2->5) + P(4->3) + P(2->4->7)= 6/36 + 1/36 \* 4/36 + 1/36 \* 2/36 + 1/36 \* 1/36 \* 2/36
P(X=8) = 4/36 + P(2->6) + P(4->4) + p(2->4->4)


