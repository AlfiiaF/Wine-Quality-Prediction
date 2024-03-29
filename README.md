# Wine-Quality-Prediction

Набор данных был загружен из репозитория машинного обучения UCI.

Два набора данных относятся к красному и белому вариантам португальского вина «Vinho Verde». Ссылка [Cortez et al., 2009]. Из-за проблем с конфиденциальностью и логистикой доступны только физико-химические (входные) и органолептические (выходные) переменные (например, нет данных о сортах винограда, марке вина, продажной цене вина и т. д.).

Эти наборы данных можно рассматривать как задачи классификации или регрессии. Классы упорядочены и не сбалансированы (например, нормальных вин намного больше, чем отличных или плохих). Алгоритмы обнаружения выбросов можно использовать для определения нескольких отличных или плохих вин. Кроме того, мы не уверены, что все входные переменные релевантны. Так что было бы интересно протестировать методы выбора признаков.

Два набора данных были объединены, и несколько значений были удалены случайным образом.

Информация об атрибутах:

Для получения дополнительной информации см. [Cortez et al., 2009].
Входные переменные (на основе физико-химических тестов):

1 - фиксированная кислотность

2 - летучая кислотность

3 - лимонная кислота

4 - остаточный сахар

5 - хлориды

6 - свободный диоксид серы

7 - диоксид серы общий

8 - плотность

9 - рН

10 - сульфаты

11 - алкоголь

Выходная переменная (на основе сенсорных данных):

12 - качество (оценка от 0 до 10)
