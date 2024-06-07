<h1>Анализ мобильной игры</h1>

<h3 class="heading-element" dir="auto">Стек:</h3>
<div id="badges">
  <img src="https://img.shields.io/badge/python-white?style=for-the-badge&logo=python" height="32"/>
  <img src="https://img.shields.io/badge/pandas-white?logo=pandas&logoColor=blue&style=for-the-badge" height="32"/>
  <img src="https://img.shields.io/badge/numpy-white?logo=numpy&logoColor=blue&style=for-the-badge" height="32"/>
<img src="https://img.shields.io/badge/plotly-white?logo=plotly&logoColor=blue&style=for-the-badge" height="32"/>
<img src="https://img.shields.io/badge/scipy-white?style=for-the-badge&logo=scipy" height="32"/>
<img src="https://img.shields.io/badge/bootstrap-white?style=for-the-badge&logo=bootstrap" height="32"/>


</div>
<hr>

<h3>Применялись следующие подходы:</h3>
<ul><li>Когортный анализ</li>
<li>А/Б тестирование</li>
<li>Bootstrap</li>
</ul>

<hr>
<h3>Реализация проекта:</h3>
<ul>
<li>Использовал API для загрузки данных</li>
<li>Провел предварительный анализ (EDA) и предобработку данных</li>
<li>Написал функцию для расчета <strong>Retention</strong> игроков по требуемым параметрам когорты игроков (дата регистрации, период для анализа) </li>
</ul>
  По результатам A/B теста:
  <ul>
<li>Посчитал и проанализировал продуктовые метрики (<strong>конверсия CR, ARPPU, ARPU</strong>)</li>
<li>Проанализировал результаты <strong>А/B-теста</strong> с использованием тестов на нормальность распределений и стат значимость (тест на независимость Хи-квадрат, T-test, Bootstrap)</li>
<li>Проверил <strong>гипотезы</strong></li>
<li>Визуализировал результаты в Python с применением seaborn и matplotlib.pyplot</li>
<li>Сделал <strong>вывод</strong> о невозможности однозначной интерпретации результатов A/B теста</li>
<li>Выбрал группу метрик для оценки результатов периодических тематических событий в игре </li>

 </ul>
<hr>
Проект следует рассматривать как учебный. <br>
При работе использовалось несколько тестов для проверки стат занчимости.<br>
НО! В работе лучше выбрать что-то одно для однозначной трактовки результатов.<br>
