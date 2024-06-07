<h1>Анализ мобильной игры</h1>

<hr>
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

Применялись следующие подходы:
когортный анализ
А/Б тестирование
bootstrap




Важным итогом работы является принятие решения о запуске пакета акционных предложений на основе А/Б теста, который показал стаитистически значимое различие (89%) в среднем чеке платящих пользователей (ARPPU) на 11,31%

<hr>
Реализация проекта:
- Использовал API для загрузки данных
- Провел предварительный анализ (EDA) и предобработку данных
- Написал функцию для расчета Retention игроков по требуемым параметрам когорты игроков (дата регистрации, период для анализа) 
По результатам A/B теста:
- Посчитал и проанализировал продуктовые метрики (конверсия CR, ARPPU, ARPU)
- проанализировал результаты А/B-теста с использованием тестов на нормальность распределений и стат значимость (тест на независимость Хи-квадрат, T-test, Bootstrap).
- проверил гипотезы
- Визуализировал результаты в Python с применением seaborn и matplotlib.pyplot.
- Выбрал группу метрик для оценки результатов периодических тематических событий в игре
- сделаны выводы
<hr>
Проект следует рассматривать как учебный. 
При работе использовалось несколько тестов для проверки.
НО! В работе лучше выбрать что-то одно для однозначной трактовки результатов.
