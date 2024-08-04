# Оценка корректности проведения A/B-теста

[ipynb](https://github.com/MSH77/Portfolio/blob/main/Project%2015/A%20B%20%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.ipynb)

## Описание проекта

Оценить корректность проведения A/B-теста и проанализировать его результаты.

Чтобы оценить корректность проведения теста:

- удостовериться, что нет пересечений с конкурирующим тестом и нет пользователей, участвующих в двух группах теста одновременно;
- проверить равномерность распределения пользователей по тестовым группам и правильность их формирования.

## Навыки и инструменты

- Python
- Pandas
- Seaborn
- Matplotlib
- SciPy
- A/B-тестирование
- Проверка статистических гипотез


## Общий вывод

Условия проведения теста не были соблюдены, за счет чего не был получен ожидаемый результат, вместо повышения конверсии, она снизилась, хоть и в некоторых случаях незначительно. Поэтому нужно собирать новые данные и запускать тест заново, так как этот тест ничем не поможет.