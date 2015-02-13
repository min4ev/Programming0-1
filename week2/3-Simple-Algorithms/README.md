# Задачи с прости алгоритми

## Задача 1 - Списък от всички делители на едно число.

Ако имаме едно цяло число `n`, то всички делети на това число са тези числа между 1 и `n - 1`, които се делят на `n` без остатък.

Например, ако `n = 6`, то всички делители са:

* 1, защото `6 % 1 == 0`
* 2, защото `6 % 2 == 0`
* 3, защото `6 % 3 == 0`

Във файл `divisors.py`, напишете програма, която:

* Чете едно цяло число `n`
* Изкарва списък от всички делители на `n`, без самото `n`.

## Задача 2 - Сумата на всички делитети на едно число

Във файл `sum_divisors.py`, напишете програма, която:

* Чете едно число `n`
* Изкарва сумата на всички негови делители, без `n`.

Например, ако `n = 6`, сумата на делитете е `1 + 2 + 3 = 6`

## Задача 3 - Дали едно число е перфектно

Едно цяло число, [наричаме перфектно](http://en.wikipedia.org/wiki/Perfect_number), ако сумата на неговите делители, без самото число, е равно на самото число.

* Например, числото 6 е перфектно, защото сумата на неговите делители е 6.
* Друго перфеткно число е 28, което има сума на делителите: `1 + 2 + 4 + 7 + 14 = 28`
* Следващото перфектно число е 496.

Във файл `is_perfect.py`, напишете програма, която:

* Чете едно число `n` от клавиатурата
* Казва дали това число е перфектно или не.

## Задача 4 - Първите n на брой перфектни числа.

**Това е трудна задача!**

Във файл `first_n_perfect.py`, напишете програма, която:

* Чете едно цяло число `n`
* На екрана изкарва първите `n` на брой перфектни числа.

Например, ако `n = 3`, то първите 3 перфектни числа са:

* 6
* 28
* 496

Ако `n = 6`, това са:

* 6
* 28
* 496
* 8128
* 33550336
* 8589869056

[Ако искате да видите списък с перфектните числа, може да го намерите тук](http://en.wikipedia.org/wiki/List_of_perfect_numbers)

## Задача 5 - Има ли проста цифра в число?

Във файл `prime_digit.py`, напишете програма, която:

* Чете едно цяло число `n`
* Изкарва на екрана Да или Не ако в числото, **има поне 1 цифра, което да е просто число.**

* Например, за числото `22448`, няма нито 1 цифра, която да е просто число.
* В числото `123`, цифрата `3` е просто число.

## Задача 6 - Прости близнаци

Два цели прости числа `p`, и `q` се наричат [близнаци](http://en.wikipedia.org/wiki/Twin_prime), ако е изпълнено `p = q + 2`

Например:

* 3 и 5 са прости числа близнаци.
* 5 и 7 са прости близнаци.

Във файл `twin_prime.py`, напишете програма, която:

* Чете едно цяло число `p`
* Изкарва на екрана неговото просто число близнак, ако има такова. **Може да има повече от 1 просто число близнак.**
* Ако числото `p` не е просто или пък няма прост близнак, програмата казва, че няма близнак.

Например:

```
Enter p: 5
Twin primes with 5:
3, 5
5, 7
```

```
Enter p: 8
8 is not a prime.
```

```
Enter p: 23
23 is prime but:
21 is not
25 is not
```