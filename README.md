# LAB1_EDA
Exploratory data analysis, outlier detection.


## Requirements

Install python requirements:

```bash
pip install -r requirements.txt
```

## Task

Заданы наблюдения по n объектам, каждый из которых характеризуется 5 числовыми признаками. В данных имеются пропуски и выбросы.
1. Рассмотрите данные и вычислите основные характеристики признаков: среднее, стандартное отклонение, медиана, квартили. 
2. Постройте гистограммы признаков и блок диаграммы  признаков. Сделайте первые выводы о возможном распределении признаков. 
3. Сделайте анализ пропусков. Предложите способ анализа зависимости признаков с учетом пропусков (корреляции, диаграммы рассеяния, …). Проанализируйте зависимость признаков. 
4. На основании анализа зависимости признаков, обсудите возможные способы восстановления пропусков в данных. 
5. Заполните пропуски средними значениями по каждому признаку. 
6. Заполните пропуски значением медианы по каждому признаку. 
7. Заполните пропуски с помощью EM алгоритма. 
8. Выберите способ определения выбросов. Для каждого варианта восстановленных данных пунктов 5-7 (среднее по признаку, медиана признака, ЕМ алгоритм)  найдите выбросы. Сравните результаты. 
9. Обсудите варианты обнаружения выбросов в данных с пропусками. Примените ваши варианты и сравните с результатами п.8 
