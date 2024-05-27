# Разработка модели для поиска корреляций в данных

# Цель проекта
Разработать модель, который будет анализировать временные ряды и выявлять связи между различными метриками в системе в момент появления аномалий
# Описание проекта
Для решения поставленной задачи мы применили алгоритм обнаружение аномалий IsolationForest с предварительной стандартизацеий данных.

<img src="https://imgur.com/jCKBWXE"/>

После был создан алогиртм класстеризации, главная суть которого - определение минимального времени для обозначение следующей аномалии как нового или текущего события.
По заданию мы нашли пересечения аномалий в заданных метриках, данные пересечения являются итогом нашей работы, они показывают на что специалисту стоит обратить внимание.

<img src="https://imgur.com/qhtB14R"/>

# Пример использования
Сотруднику с экспертизой в области подаются графики с метриками, на которых обнаружены аномальные события для дальнейшего анализа. 

<img src="https://imgur.com/oIO26zb"/>

# Стек
- Python
- Pandas
- Numpy
- Sklearn
- Matplotlib

# Команда
 - [Пирогов Дмитрий](https://github.com/PirogovDmitriy)
 - [Семён Григорьев](https://github.com/Nevers15)
