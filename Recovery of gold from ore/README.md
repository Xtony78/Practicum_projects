
# Восстановления золота из золотосодержащей руды
## Описание проекта
Подготовьте прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В вашем распоряжении данные с параметрами добычи и очистки.
Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.
## Использованные библиотеки 
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- sklearn.model_selection.train_test_split, cross_val_score
- sklearn.tree.DecisionTreeRegressor
-  sklearn.ensemble.RandomForestRegressor
-  sklearn.linear_model.LinearRegression
-  numpy.random.RandomState
-  sklearn.metrics.make_scorer, mean_absolute_error
-  sklearn.dummy.DummyRegressor
-  sklearn.model_selection.GridSearchCV
-  sklearn.preprocessing.StandardScaler 
## Вывод
Были выбраны и обучены модели для нескольких стадий очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.
