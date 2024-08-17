
# Lesson_2
## Тема “Введение в математических анализ”
### Задача 1. 
Как относятся друг к другу множество и последовательность? (в ответе использовать слова типа: часть, целое, общее, частное, родитель, дочерний субъект и т.д.)
### Задача 2
Прочитать высказывания математической логики, построить их отрицания и установить
истинность.

+ $\forall y \in [0;1]:sgn(y)=1$
+ $\forall n \in \mathbb {N} > 2 : \exists x, y, z \in \mathbb {N}: x^n = y^n + z^n$
+ $\forall x \in \mathbb {R} \exists X \in \mathbb {R} :X >x$
+ $\forall x \in \mathbb {C} \nexists y \in \mathbb {C} : x > y \parallel x < y$
+ $\forall y \in [0; \frac {\pi} {2}] \exists \epsilon> 0: \sin{y} < \sin{(y + \epsilon)}$
+ $\forall y \in [0; \pi) \exists \epsilon> 0: \cos{y} > \cos{(y + \epsilon)}$
+ $\exists x: x \notin \{\mathbb{N, Z, Q, R, C}\}$

## Тема “Множество”
### Задача 1. 
Даны три множества a,b и с. Необходимо выполнить все изученные виды бинарных операций
над всеми комбинациями множеств.
### Задача 2
*Выполнить задание 1 на языке Python

## Тема 3 “Последовательность”
### Задача 1. 
Даны 4 последовательности. Необходимо:
a. исследовать их на монотонность;
b. исследовать на ограниченность;
c. найти пятый по счету член.

+ $\{a_n\}^\infty_{n=1}=2^n -n$
+ $\{b_n\}^\infty_{n=2} = \frac {1} {1 -n}$
+ $\{c_n\}^\infty_{n=1} = -1^n + \sqrt{2n}$
+ $\{d_n\}^\infty_{n=1}= (-1)^{2n} + \frac{1}{n^2}$

### Задача 2
Найти 12-й член заданной неявно последовательности
$a_1 =128, a_{n+1} - a_n =6$

### Задача 3
*На языке Python предложить алгоритм вычисляющий численно предел с точностью
$\epsilon = 10^7$
$\lim\limits_{n \to +\infty} \frac{n}{\sqrt[n]{n!}}$

### Задача 4
*Предложить оптимизацию алгоритма, полученного в задании 3, ускоряющую его сходимость