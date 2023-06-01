# Отток клиентов
### Описание проекта
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 
Требуется построить модель с предельно большим значением F1-меры. ЧЦелевой показатель метрики до 0.59.
### Использованные навыки
- pandas;
- numpy;
- matplotlib;
- sklearn;
sklearn.model_selection.train_test_split
 - sklearn.linear_model.LogisticRegression
 - sklearn.ensemble.RandomForestClassifier
 - sklearn.tree.DecisionTreeClassifier
 - sklearn.metrics.accuracy_score,roc_auc_score,f1_score,precision_score, recall_score
 - sklearn.utils.shuffle
 - sklearn.preprocessing.OrdinalEncoder
 - sklearn.metrics.roc_curve
### Выводы
Проведено исследование данных, по целевому признаку спрогнозирован результат, протестированы 3 модели, выбрана наиболее подходящая - "Случайный лес", на ней достигнуты требуемые показатели по метрикам.

