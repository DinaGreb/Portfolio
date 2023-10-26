# Прогноз оттока клиентов

 [ipynb](https://github.com/DinaGreb/Portfolio/blob/main/Customer_retention/%D0%A1ustomer_retention.ipynb)

## Описание проекта

Требуется создать модель машинного обучения, которая будет предсказывать уход клиента по собранным с него данным. Этому отобранному моделью списку клиентов будут предложены специальные условия сотрудничества.


  
## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **sklearn**
- **lightgbm**
- **xgboost**
- **matplotlib**
- sklearn.metrics.**roc_auc_score**
- sklearn.model_selection.**cross_validate**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**
- sklearn.model_selection.**GridSearchCV**
- sklearn.pipeline.**Pipeline**


## Общий вывод

Была проведена предобработка и создание новых признаков для обучения моделей.  Были построены несколько моделей, обучены и подобраны их лучшие гиперпараметры для максимизации метрики roc_auc.
Была проведена проверка наиболее эффективной модели (бустинг CatBoost) на тестовом наборе, искомое значение метрики было достигнуто.

