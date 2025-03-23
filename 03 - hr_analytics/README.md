<h1>HR-аналитика (Сборный Проект — 2)</h1>

<h2>Описание проекта.</h2> 

HR-аналитики компании «Работа с заботой» помогают бизнесу оптимизировать управление персоналом: бизнес предоставляет данные, а аналитики предлагают, как избежать финансовых потерь и оттока сотрудников. В этом HR-аналитикам пригодится машинное обучение, с помощью которого получится быстрее и точнее отвечать на вопросы бизнеса.

<h2>Цель исследования</h2>
  
Исследование уровня удовлетворённости сотрудника, чтобы предсказать отток сотрудников.

<h2>Задачи исследования</h2>

- Построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика.

- Построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.

<h2>Инструменты решения задачи</h2>

- pandas 
- matplotlib
- seaborn 
- numpy 
- phik
- Pipeline

- sklearn.preprocessing.OneHotEncoder
- sklearn.preprocessing.OrdinalEncoder
- sklearn.preprocessing.StandardScaler
- sklearn.preprocessing.MinMaxScaler
- sklearn.preprocessing.LabelEncoder 
- sklearn.compose.ColumnTransformer
- sklearn.impute.SimpleImputer
- sklearn.metrics.roc_auc_score
- sklearn.metrics.make_scorer
- sklearn.model_selection.RandomizedSearchCV
- sklearn.linear_model.LogisticRegression
- sklearn.linear_model.LinearRegression
- sklearn.neighbors.KNeighborsClassifier
- sklearn.tree.DecisionTreeClassifier
- sklearn.tree.DecisionTreeRegressor
- sklearn.svm.SVC
- sklearn.inspection.permutation_importance
- scipy  

<h2>Исходные данные</h2>

- Тренировочная выборка: train_job_satisfaction_rate.csv

- Входные признаки тестовой выборки: test_features.csv

- Целевой признак тестовой выборки: test_target_job_satisfaction_rate.csv

- id — уникальный идентификатор сотрудника;
- dept — отдел, в котором работает сотрудник;
- level — уровень занимаемой должности;
- workload — уровень загруженности сотрудника;
- employment_years — длительность работы в компании (в годах);
- last_year_promo — показывает, было ли повышение за последний год;
- last_year_violations — показывает, нарушал ли сотрудник трудовой договор за последний год;
- supervisor_evaluation — оценка качества работы сотрудника, которую дал руководитель;
- salary — ежемесячная зарплата сотрудника;
- job_satisfaction_rate — уровень удовлетворённости сотрудника работой в компании, целевой признак.

  <h2>Вывод по итогам исследования</h2>

- Выполнила предобработку данных и исследовательский анализ.
- Провела корреляционный анализ
- Для задачи 1 построила и подобрала параметры для моделей рассматривались: DecisionTreeRegressor() и LinearRegression()
- Для задачи 2 построила и подобрала параметры для моделей рассматривались: DecisionTreeClassifier(), KNeighborsClassifier(), LogisticRegression(), CVС()
- Разработаны предложения для бизнеса
