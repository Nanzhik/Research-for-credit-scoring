# Исследование надёжности заёмщиков

[ipynb](https://github.com/Nanzhik/Research-for-credit-scoring/blob/main/Research_for_credit_scoring.ipynb)

## Описание проекта

**Заказчик:** кредитный отдел банка. 

**Задача:** разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. 

**Исходные данные:** статистика о платёжеспособности клиентов из банка.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **pymystem3**

## Вывод
Основываясь на полученных данных можно прийти к следующему выводу: Семейное положение и наличие детей в семье безусловно влияют на факт погашения кредита. Так мы можем увидеть, что вероятность клиента принадлежащего к группе "многодетные" стать должником составляет 9.2%, а вероятность клиента принадлежащего к группе "не женат / не замужем" стать должником составляет 9.8%. Поэтому логично будет предположить, что наиболее безопасными для банка заемщиками являются семьи без детей и люди являющиеся вдовой/вдовцом
