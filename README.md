# mhe2

Post correspondence problem - przykład nierozstrzygalnego problemu decyzyjnego. Celem jest znalezienie konkatenacji tych słów w takiej kolejności, aby obie listy dawały ten sam wynik.

mój przykład :

sqn| numerator |   denominator|
___|___________|______________|
1  |a          |      aaa     |
2  | abaaa     |        ab    |
3  | ab        |        b     |
--------------------------------
ex1                             ex2
rozwiazanie : 2 1 1 3           rozwiazanie : 1 2 1 3
numerator  : abaaaaaab          numerator  : aabbaaabb
denominator: abaaaaaab          denominator: aabbaaabb

ex 3
rozwiazanie : 1 3 1 1 3 2 2
numerator  : abb a abb abb a b
denominator: abb a abb abb a b
