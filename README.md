# Задание 4.6* по матстату

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Zv0obYLjNv6YgKnjLd_JzPJZRUh1BzCh?usp=sharing)

Построить на компьютере график ядерной оценки
функции плотности по выборке
**`(3; 0; 4; 3; 6; 0; 3; 1; 2; 1)`**, используя различные ядра и
параметры размытости.

## Ядерная оценка функции плотности имеет вид:

<a href="https://www.codecogs.com/eqnedit.php?latex=\hat{f}_n(x)&space;=&space;\frac{1}{n&space;\lambda&space;_n}&space;\sum_{i=1}^{n}&space;g(\frac{x-X_i}{&space;\lambda&space;_n})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\hat{f}_n(x)&space;=&space;\frac{1}{n&space;\lambda&space;_n}&space;\sum_{i=1}^{n}&space;g(\frac{x-X_i}{&space;\lambda&space;_n})" title="\hat{f}_n(x) = \frac{1}{n \lambda _n} \sum_{i=1}^{n} g(\frac{x-X_i}{ \lambda _n})" /></a>

## Список ядер:

1. Ядро треугольное:

    <a href="https://www.codecogs.com/eqnedit.php?latex=g(x)&space;=&space;(\frac{1}{\sqrt6}-\frac{&space;\left&space;|&space;x&space;\right&space;|}{6})&space;h(\sqrt6&space;-&space;\left&space;|&space;x&space;\right&space;|)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?g(x)&space;=&space;(\frac{1}{\sqrt6}-\frac{&space;\left&space;|&space;x&space;\right&space;|}{6})&space;h(\sqrt6&space;-&space;\left&space;|&space;x&space;\right&space;|)" title="g(x) = (\frac{1}{\sqrt6}-\frac{ \left | x \right |}{6}) h(\sqrt6 - \left | x \right |)" /></a>

2. Плотность стандартного нормального распределения:

    <a href="https://www.codecogs.com/eqnedit.php?latex=g(x)&space;=&space;\frac{1}{\sqrt2\sqrt\pi&space;}&space;e^{-\frac{x^2}{2}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?g(x)&space;=&space;\frac{1}{\sqrt2\sqrt\pi&space;}&space;e^{-\frac{x^2}{2}}" title="g(x) = \frac{1}{\sqrt2\sqrt\pi } e^{-\frac{x^2}{2}}" /></a>

3. Ядро Епанечникова:

    <a href="https://www.codecogs.com/eqnedit.php?latex=g(x)&space;=&space;(\frac{3}{4\sqrt5}-\frac{3}{20\sqrt5}x^2)&space;h(\sqrt5&space;-&space;\left&space;|&space;x&space;\right&space;|)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?g(x)&space;=&space;(\frac{3}{4\sqrt5}-\frac{3}{20\sqrt5}x^2)&space;h(\sqrt5&space;-&space;\left&space;|&space;x&space;\right&space;|)" title="g(x) = (\frac{3}{4\sqrt5}-\frac{3}{20\sqrt5}x^2) h(\sqrt5 - \left | x \right |)" /></a>
