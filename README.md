# mathbot

## Дроби
Дроби пишутся просто через слеш 123\9854 (см. ремарку про слеши выше!)

## Многочлены
Многочлены тоже набираются почти как угодно, единственное — если у него есть коэфициент (например (x^2+1) * 5, здесь это 5), то коэфициент должен идти спереди, а многочлен быть в квдартаных скобках, т.е. 5*[x^2+1]

## .rw
— Читает, и отправляет тот же объект (но в красивом виде) назад

## .+
— Складывает (числа, дроби, многочлены)

## .-
— Вычитает (числа, дроби, многочлены)

## .*
— Умножает (числа, дроби, многочлены)

## .divmod
— Делит с остатком (кидает и остаток, и частное). Работает для целых чисел и многочленов.

## ./ 
— Делит дроби
Другой слеш тоже добавлен как допустимое сочетание, но пока он ломает мой самодельный парсер JSON (с консоли работает хорошо)

## .gcd
— НОД (числа, многочлены)

## .lcm
— НОК (числа)

## .derivative или .der или .'
— Производная многочлена

## .trimDegSaveRoots или .deleteDoubledRoots или .ddr или .tdsr
— Убивает кратные корни многочлена (т.е. (x-2)^100*(x-1)^666 превращается в (x-2)*(x-1) )

