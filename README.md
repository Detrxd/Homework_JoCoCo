## **Рассмотрим подробнее три типа расчёта показателей покрытия, также их называют «Counter Coverage».**

1.	Instructions - самая простой тип расчёта показателей покрытия, предоставляет только информацию о том, что строка кода была выполнена или пропущена.
2.	Branches – более подробно предоставляет информацию о покрытии кода, «смотрит» не только на то, что  строка выполнена или нет, но также все ответвления («if», «switch»).
3.	Lines – немного схожий тип покрытия кода на «instructions», но строже, в данном типе покрытия кода строка кода считается выполненной(«зелёной»), если была выполнена хотя бы одна команда, на этой строке. Вычисление происходит на основе фактических покрытых исходных линий.

_При выполнении домашнего задания использовался счётчик - Branches._