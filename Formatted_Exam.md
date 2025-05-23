1. Никогда не работаем на целой выборке данных. Всегда имеем дело
с генеральной совокупностью. Г.С - всевозможные комбинации всех
объектов или наблюдений, относительно которых делаем выводы
при решении задачи.
2. Вероятность - относительная мера возможности наступления события.
3. Свойства вероятности
   1. Вероятность невозможного события равна нулю.
     Вероятность любого события можно представить как сумму 
     вероятностей наступления этого события и невозможного события.
     В силу аддитивности и конечности выходит, что вероятность
     невозможного события нулевая.
   2. \(P(A)\) <= \(P(B)\). Если событие А включается в событие В, то
     наступление А влечет наступление В.
     Это происходит в силу аддитивности и неотрицательности 
     вероятностной меры, т.к событие В помимо А может содержать и
     другие события.
   3. Вероятность события лежит в промежутке от 0 до 1, включая
   концы. P(X) = 1 аксиоматические предполагается. А любое событие
   входит в Х.
   4. P(B\A) = \(P(B)\) - \(P(A)\). Где В включает А. Вероятность В\А
   наступление события В при одновременном ненаступлении события А.
   Следует из несовместности событий. Под несовместными событиями
   понимаются события, исходы которых невозможно получить 
   одновременно. Из аддитивности вероятности: А и В\А являются
   несовместными. Их сумма равна вероятности В.
   5. Вероятность противоположного события к данному равна 1 - вероятность данного события
   P(!A) = 1 - \(P(A)\)
   Доказывается по аналогии. Используем все вероятностное пространство. !А и А несовместны.
   6. Вероятность наступления хотя бы одного из произвольных событий А или В
   P(A+B) = \(P(A)\) + \(P(B)\) - P(AB)
   Можно получить если представить как объединение двух множеств.
   P(A+B) = \(P(A)\) + P(B\AB) = \(P(A)\) + \(P(B)\) - P(AB)
4. Вероятностные распределения (дискретные)
   1. Дискретное равномерное распеределение.
   Случайная величина E имеет дискретное равномерное распределение, если она принимает
   конечное число значений с равными вероятностями.
   2. Распределение Бернулли.
   Нам заранее известна вероятность успеха.
   Случайная величина E имеет распределение Бернулли с параметром p, если E принимает значения
   0 и 1 с вероятностями 1-p и p. Случайная величина E с таким распределением равна числу 
   успехов в одном испытании схемы бернулли с вероятностью успеха E. P(E=1) = p, P(E=0) = q = 1 -p.
   3. Биномиальное распределение.
   Два возможных исхода: успехи и неудача. Вероятность успеха p. Серия из независимых испытаний
   с вероятностью успеха p называют испытаниями Бернулли.
   Биномиальное распределение - закон распределения случайной величины, равной количеству успехов
   в испытаниях бернулли. Случайная величина может принимать значения от 0 до n, где n - число
   испытаний. Вероятность определяется формулой Бернулли.
   \(P(E=k)\) = \(C_n^k\) \(p^k\) \(q^{n-k}\), где k - число успешных испытаний.
   С_n^k = \(n!\) / \(k!\)(n-k)!  - биномиальный коэффициент.
   4. Распределение Пуассона.
   Проводится n независимых испытаний, в каждом из которых случайное событие A происходит с
   вероятностью p.
   Распределение Пуассона - распределение дискретного типа случайной величины, представляющей
   собой число испытаний, произошедших за фиксированное время, при условии, что данные события
   происходят с некоторой фиксированной средней интенсивностью \(\Lambda\) и независимо друг от друга.
   \(P(E=k)\) = \(\Lambda\) ^ k / \(k!\) e ^ (-\(\Lambda\)), где \(\Lambda\) = np - мат.ожидание случайной величины (среднее кол-во
   событий за фиксированный промежуток времени.
   5. 
5. Нормальное распределение. (Определения)

- Среднее значение - среднее арифметическое от значений признака
Св-ва средних значений: 
1. Алгебраическая сумма отклонений значений признака от среднего значения равна нулю
2. Если увеличить или уменьшить значения признака на одинаковое значение, то среднее значение
уменьшится или увеличится в то же количество раз.
3. Если каждое значение признака уменьшить или увеличить на одно и то же значение, то среднее
значение увеличится или уменьшится на то же значение.

- Медиана - значение, разбивающее упорядоченное по возрастанию множество ровно пополам. Если
в множестве четное количество элементов, то медиану определяем как среднее от двух значений,
разбивающих выборку пополам.

- Мода - самое частовстречающееся значение в множестве. Мод может быть несколько.
- Дисперсия - квадрат среднеквадратичного отклонения
- Среднеквадратичное отклонение: \(\sqrt\)((x_i - M) ^ 2 / n)

Нормальное распределение: унимодально и симметрично
Функция плотности вероятности: f(x) = 1 / \(\sigma\) / \(\sqrt\)(2pi) * e^(-0.5 ((x - \(\mu\))/\(\sigma\)) ^ 2)

Правило трех сигм: внтури диапазона (\(\mu\) - 3\(\sigma\); \(\mu\) + 3\(\sigma\)) лежат 99.73% значений. 

6. Закон больших чисел.
Пусть есть бесконечная последовательность независимых одинаково распределенных СВ, для
которых существуют мат.ожидание и дисперсия. Тогда для любого eps>0:
lim(n->oo) P(sum^n_i(E_i - \(\mu\)) / n) >= eps) = 0
При стремлении n к бесконечности среднее арифметическое случайных величин мало отличается от
мат.ожидания. Вероятность отклонения от мат.ожидания стремится к нулю при стремлении
размера выборки к бесконечности.

Следствие: Среднее по нашей выборке, достаточно близко к настоящему среднему и достаточно
хорошо его описывает.

В реальности тяжело гарантировать стремление n к бесконечности. Поэтому на практике ЦПТ.

7. Центральная предельная теорема.

Пусть задана бесконечная последовательность независимых случайных величин, для которых
существуют конечные мат.ожидание \(\mu\) и дисперсия \(\sigma\)^2.

lim(n->oo) \(\sqrt\)(n) (<E> - \(\mu\)) / \(\sigma\) = N(0, 1) - нормальное распределение \(\mu\) = 0, \(\sigma\) = 1

Нормировка по среднему квадратичному отклонению и размеру выборки дает возможность
выставлять требования к размеру выборки. Это позволяет утверждать, что при бесконечном
размере выборки нормированное среднее значение ведет себя как СВ, подчинающаяся
стандартному распределению.

8. Условная вероятность.

Вероятность наступления события A, при условии наступления события B называется условной 
вероятность и обозначается \(P(A|B)\).

Рассмотри множество элементарных исходов w события B: B э w.
Пусть вероятность наступления элементарного исхода w при условии наступления B: P(w|B) = aP(w)
Для иных элементарных исходов, не принадлежащих событию B: P(w|B) = 0.
sum_w(P(w|B)) = 1
Тогда sum_w P(w|B) = sum_w aP(w) = a\(P(B)\) = 1 => a = 1 / \(P(B)\) => P(w|B) = P(w) / \(P(B)\)

Для события А: \(P(A|B)\) = sum_w P(w|B) = P(AB) / \(P(B)\)

9. Формула Байеса.

Опр. усл. вер. P(AB) = \(P(A|B)\)\(P(B)\) = \(P(B|A)\)\(P(A)\)

Тогда: \(P(A|B)\) = \(P(B|A)\)\(P(A)\) / \(P(B)\)

Формула позволяет переставить причину и следствие.

10. Независимые события

События A и B называются независимыми, если вероятность наступления одного, не зависит от
наступления другого события.
Т.е \(P(A|B)\) = \(P(A)\), тогда: 
P(AB) = \(P(A|B)\)\(P(B)\) = \(P(A)\)\(P(B)\)

Если рассматривается произвольная совокупность независимых событий, то:
P(A_1...A_n) = P(A_1) ... P(A_n)

11. Полная вероятность.

Набор событий А_i, хотя бы одно из которых обязательно наступит в результате испытания, т.е
P(sum (A_i)) = 1, называется полным.

Пусть имеется полный набор попарно несовместных событий А_i. Тогда для любого события B
формула полной вероятности:
\(P(B)\) = sum P(B|A_i)P(A_i)

Формула Байеса через полную вероятность: 

P(A_j|B) = P(A_j)P(B|A_j) / \(P(B)\) = P(A_j)P(B|A_j) / sum P(B|A_i)P(A_i)


Практика по задачкам:
1. Вероятность выпадения 6 решек при 10 подбрасываниях монеты.
Одно подбрасывание монеты является испытанием Бернулли, так как у нас возможно два исхода:
удача: выпадение решки
неудача: выпадение орла

События являются равновероятными, так как рассматриваем идеальную монетку.
В нашем случае p = 0.5 - вероятность выпадения решки, q = 1 - p = 1 - 0.5 = 0.5 - вероятность
выпадения орла.

Проводится 10 испытаний. Поэтому нам необходимо воспользоваться биномильным распределением.
k = 6 - число успешных испытаний, ты число выпадений решки.
n = 10 - число испытаний

Тогда P(E=6) = C_10^6 * 0.5 ^ 6 * 0.5 ^ (10 - 6), где C_10^6 = 10! / 6!(10-6)! 

2. Вероятность выпадения 6 очков 2 раза при 8 подбрасываниях кубика.
по аналогии, только p = 1 / 6, q = 1 - 1 / 6 = 5 / 6
k = 2, n = 8

3. Имеются три одинаковые урны. В первой урне находятся 5 белых и 3 черных шаров,
во второй – только белые и в третьей – только черные шары.
Наудачу выбирается одна урна и из неё наугад извлекается шар.
Какова вероятность того, что этот шар чёрный?

Решаем через полную вероятность:

\(P(B)\) = sum P(B|A_i)P(A_i)

Не забываем, что A_i должны давать нам полный набор, т.е должно
точно произойти хотя бы одно из этих событий.

В данном случае у нас имеются три урны. Так как они одинаковые,
то выбор одной из трех урн равно вероятен.

Пусть A_i, где i = {1, 2, 3} - вынемаем шар из урны с соответсвующим
индексом. P(A_i) = 1 / 3.

Все эти события возможны, их вероятность больше нуля.
Какова вероятность, что мы выберем хотя бы одну урну из трех и вынем
оттуда шар? 
P(A1 + A2 + A3) = 1

Поэтому данные события образуют полный набор.

Давайте за B обозначим событие, соответствующие вынеманимю черного
шара.

В таком случае событие P(B|A_i) будет означать следующее: 
вероятность, что мы вынем черный шар, при условии, что мы вынимаем
его из iой урны.

В нашем случае: 
1. P(B|A_1) = 3 / 8. Так как в урне всего 8 шаров:5 белых и 3 черных.
2. P(B|A_2) = 0, так как во второй урне лишь белые шары. Поэтому мы не
можем вынуть из нее черный шар никоем образом.
3. P(B|A_3) = 1, так как в третьей урне лишь черные шары, поэтому 
единственный шар, который мы можем вытащить из этой урны, черного
цвета.

В итоге подставляя в формулу полной вероятности, найдем вероятность
вытягивания черного шара из одной из урн:

\(P(B)\) = 3 / 8 * 1 / 3 + 1 / 3 * 1 = 3 / 24 + 1 / 3 = 11 / 24.

Ответ: 11 / 24. 

4. На склад поступило 2 партии изделий: первая – 8000 штук, вторая – 5000 штук. 
Средний процент нестандартных изделий в первой партии 15%, во второй – 23%. 
Наудачу взятое со склада изделие оказалось нестандартным. 
Найти вероятность того, что оно из второй партии.

Здесь явно следствие и причина поменяны местами:
Причина - принадлежность партии
Следствие - нестандартное изделие

Проще решать задачу, задавая себе такой вопрос: Какова вероятность получить нестандартное
издели, если мы случайно выбрали изделие из одной из партий.

Так как исходная задача, относительно сформулированной меняет местами причину и следствие,
воспользуемся формулой Байеса:
P(A_i|B) = P(B|A_i)P(A_i) / \(P(B)\)

A_i должны образовывать полный набор.

В нашем случае
A_i - выбрать изделие из одной из партий.

А_1 = 8000 / (5000+8000) = 8 /13, А_2 = 5 / 13. 
Оба события возможны. Они несовместны, так как одно изделие не может принадлежать 
двум партиям. И хотя бы одно из них всегда выполняется P(A_1+A_2) = P(A_1) + P(A_2) = 1

B - выбранное изделие, оказалось нестандартным.

Тогда P(B|A_i) вероятность, что выбранное изделие оказалось нестандартным, при условии, что
взяли его из iой партии.

P(B|A_1) = 0.15, P(B|A_2) = 0.23

Остается воспользоваться полной вероятностью для нахождения \(P(B)\)

\(P(B)\) = P(B|A_i)P(A_i)

Тогда: \(P(B)\) = 0.15 * 8 / 13 + 0.23 * 5 / 13

Нам необходимо найти, какова вероятность, что выбранное нестандартное издели принадлежит
второй партии, поэтому

P(A_2 | B) = P(B|A_2)P(A_2) / \(P(B)\) = 0.23 * 5 / 13 / (0.15 * 8 / 13 + 0.23 * 5 / 13) = 0.489

Ответ: 0.489

5. Электролампы изготавливаются на трех заводах. 
1-й завод производит 30% общего количества ламп, 2-й – 55%, а 3-й – остальную часть. 
Продукция 1-го завода содержит 1% бракованных ламп, 2-го – 1,5%, 3-го – 2%. 
В магазин поступает продукция всех трех заводов. Купленная лампа оказалась с браком. 
Какова вероятность того, что она произведена 2-м заводом?

Здесь снова меняются местами причина и следствие.

Причина: лампа произведена заводом
Следствие: лампа оказалась бракованной

Переформулируем: Какова вероятность выбрать бракованную лампу, если она была произведена
на одном из заводов?

Здесь тоже используем формулу Байеса

P(A_i|B) = P(B|A_i)P(A_i)/\(P(B)\)

Пусть n - общее число ламп, произведенное всеми заводами.
Тогда первый завод произвел: 0.3n
второй завод: 0.55n
третий завод: 0.15n

A_i должны образовывать полный набор.

Пусть A_i - лампа принадлежит одному из заводов.

в таком случае

P(A_1) = 0.3n/n = 0.3, P(A_2) = 0.55n/n = 0.55, P(A_3) = 0.15n/n = 0.15

Действительно. Все события возможны и они несовместны, также хотя бы одно из них выполняется,
поэтому A_i образуют полный набор.

Событие B - получение бракованной лампы.

В таком случае P(B|A_i) - Получение бракованной лампы, если она была произведена на iом заводе.

P(B|A_1) = 0.01, P(B|A_2) = 0.015, P(B|A_3) = 0.02

Остается найти полную вероятность:

\(P(B)\) = sum P(B|A_i)*P(A_i) = 0.01 * 0.3 + 0.015 * 0.55 + 0.02 * 0.15 = 0.01425

В таком случае остается воспользоваться формулой Байса: 

Необходимо найти вероятность, что бракованная лампа была получена со второго завода

P(A_2|B) = P(B|A_2)P(A_2) / \(P(B)\) = 0.015 * 0.55 / 0.01425 = 0.579

Ответ: 0.579

6. В двух урнах находится соответственно 4 и 5 белых и 6 и 3 чёрных шаров.
Из каждой урны наудачу извлекается один шар, а затем из этих двух наудачу берется один.
Какова вероятность, что это будет белый шар?

Воспользуемся полной вероятностью \(P(B)\) = sum P(B|A_i)P(A_i)

A_i - должны образовывать полный набор.

A_i - вытянуты по одному шару из двух урн.

Рассмотрим все возможные комбинации вытянутых шаров из двух урн.

A_1:​﻿ из первой урны вытащили белый шар, из второй вытащили черный шар.
A_2:﻿ из первой урны вытащили белый шар, из второй вытащили белый шар.
A_3​:﻿ из первой урны вытащили черный шар, из второй вытащили черный шар.
A_4​: из первой урны вытащили черный шар, из второй вытащили белый шар.

Цвет вынутого шара из одной урны, никак не зависит от цвета вытянутого шара из другой урны,
поэтому рассматриваемые нами события являются независимыми, поэтому: P(CD) = P(C)P(D).
Заметим, что события несовместны, так как любые из этих событий не могут произойти
одновременно.

В первой урне n1 = 4 (бел) + 6 (чер) = 10 шаров,
Во второй урне n2 = 5 (бел) + 3 (чер) = 8 шаров

P(A_1) = 4 / 10 * 3 / 8 = 12 / 80 = 3 / 20
P(A_2) = 4 / 10 * 5 / 8 = 20 / 80 = 5 / 20
P(A_3) = 6 / 10 * 3 / 8 = 18 / 80 = 4.5 / 20
P(A_4) = 6 / 10 * 5 / 8 = 30 / 80 = 7.5 / 20

Заметим, что хотя бы одно из событий мы точно получим P(A_1 + ... A_4) = 1

A_i образуют полный набор событий.

Событие В - выбрали черный шар.

P(B|A_i) - вероятность, что выбранный шар окажется черным, при условии что из двух урн,
вытащили i-ую пару шаров.

P(B|A_1) = P(B|A_4) = 1 / 2, так как есть два шара, один из них черный.
P(B|A_3) = 1, так как из двух шаров оба черных.
P(B|A_2) = 0, так как из двух шаров оба белых.

Используем формулу полной вероятности: 

\(P(B)\) = 1 / 2 * 3 / 20 + 1 * 4.5 / 20 + 1 / 2 * 7.5 / 20 = 19.5 / 40 = 39 / 80

Ответ: 39 / 80