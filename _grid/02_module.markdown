---
layout: post

title: Миллиметровка
anchor: millimetrovka
---

Шаг миллиметровки задает минимальный размер элементов и отступов между ними в макете. Именно этот шаг мы принимаем за __модуль__ и на его основе высчитываем остальные расстояния между элементами. Разработчикам все размеры приходят именно в модулях.

Размер модуля может меняться в зависимости от задачи. Это позволяет адаптировать один и тот же интерфейс под разные экраны. К примеру, при изменении базового модуля интерфейс растянется, но сетка не сломается за счёт относительных расстояний.

<div class="my-4">
	<img src="img/grid/millimetrovka.svg" alt="Миллиметровка"/> 
</div>

За стандартный модуль для веб-интерфейсов мы обычно принимаем 8px. Это число удобно по нескольким причинам. Во-первых оно чётное. Во-вторых, ряд из чисел, кратных ему, растёт с оптимальной скоростью, а так же числам этого ряда соответствуют привычные размеры иконок и элементов интерфейса. Так же многие числа их этого ряда хорошо делятся на 2, 3, 4, 6 частей. 
