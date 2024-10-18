# CowSelectionML

## Цель проекта
Разработка двух моделей машинного обучения:

1. **Прогнозирование удоя коров** — модель должна предсказывать, сколько молока даст каждая корова за год. Минимальное требование — 6000 кг.
2. **Прогнозирование вкуса молока** — модель должна оценивать вероятность того, что молоко будет вкусным, согласно строгим критериям фермера.

## Датасеты
В проекте используются три датасета:

- **ferma_main.csv** — данные о текущем стаде фермера, включая показатели молока, питания и других характеристик.
- **ferma_dad.csv** — данные о породе и имени отца каждой коровы.
- **cow_buy.csv** — данные о коровах, предлагаемых на продажу, которые фермер рассматривает для покупки.

## Этапы проекта
1. **Загрузка и предобработка данных** — очистка, преобразование типов данных и устранение пропусков.
2. **Исследовательский анализ данных** — изучение взаимосвязей между признаками, корреляционный анализ.
3. **Обучение моделей**:
   - Линейная регрессия для предсказания удоя.
   - Логистическая регрессия для предсказания вкуса молока.
4. **Оценка моделей** — использование метрик (R², MSE, MAE, RMSE для регрессии, а также accuracy, recall, precision для классификации) для выбора лучшей модели.
5. **Прогноз для коров на продажу** — на основе данных о кормах и генетических характеристиках коров «ЭкоФермы» модели предсказывают их продуктивность.

## Итог
Итогом работы является список коров, которые соответствуют строгим критериям фермера по удою и вкусу молока.
