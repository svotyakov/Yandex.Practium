# Мои проекты

#### [Предобработка данных, WebScraping](https://github.com/svotyakov/Yandex.Practium/tree/main/WebScraping_DataPreprocessing)
| Название проекта| Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Создание новых признаков](https://github.com/svotyakov/Yandex.Practium/blob/main/WebScraping_DataPreprocessing/creating_new_features/Data_analysis_creating_new_features.ipynb) |Суть задачи в том, что на текущем датасете качество обучения модели очень низкое и надо что-то сделать, чтобы выяснить закономерности в данных| *pandas, numpy, matplotlib, seaborn, sklearn(StandardScaler, MDS, DecisionTreeClassifier, PolynomialFeatures, GridSearchCV), itertools, CatBoostClassifier, tqdm* |
| | | |
| [Анализ, создание и трансформация признаков (Телеком)](https://github.com/svotyakov/Yandex.Practium/blob/main/WebScraping_DataPreprocessing/telecom_analysis/rus/Telecom_classification.ipynb) |В работе рассматриваются различные методы трансформации данных для дальнейшего использования в модели машинного обучения, бинарная классификация| *pandas, numpy, matplotlib, seaborn, sklearn(GridSearchCV, TfidfVectorizer), itertools, CatBoostClassifier, lightgbm, tqdm* |

#### [А/Б тестирование](https://github.com/svotyakov/Yandex.Practium/tree/main/A_B_testing)
| Название проекта| Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Теория А/Б теста](https://github.com/svotyakov/Yandex.Practium/blob/main/A_B_testing/A_B_test_%20Theory.ipynb) |Теория с практическими примерами по А/Б тестированию. В работе представлены не только стандартные примеры по p-value, но и применимость t-testа к различным выборкам, способы определения размера выборки, сущность Alpha-коэффициента и мощности теста.| *pandas, numpy, scipy stats, matplotlib* |

#### [Монте-Карло](https://github.com/svotyakov/Yandex.Practium/tree/main/Montecarlo)
| Название проекта| Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Построение модели для распределения прибыли](https://github.com/svotyakov/Yandex.Practium/blob/main/Montecarlo/Bootstrap_profits_distribution.ipynb) |Необходимо постоить модель распределения прибыли для нефтяной компании методом бутстрап. Для этого у нас есть три нефтяных участка и информация по запасам нефти уже в разведаных скважинах. Необходимо выбрать оптимальный участок исходя из критериев задания| *pandas, numpy, sklearn, matplotlib, seaborn* |
| | | |
| [Теория Монте-Карло](https://github.com/svotyakov/Yandex.Practium/blob/main/Montecarlo/Monte-carlo_theory.ipynb) |Увлекательные задачи по теории вероятности, которые решаются методом Монте-Карло| *pandas, numpy, math, random* |

#### [Машинное обучение](https://github.com/svotyakov/Yandex.Practium/tree/main/Machine_learning_predictions)
| Название проекта| Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Построение модели оттока клиентов](https://github.com/svotyakov/Yandex.Practium/blob/main/Machine_learning_predictions/RandomForestClassifier%20VS%20CatBoost%20%26%20LGBM.ipynb) |Необходимо наилучшим образом предсказать вероятность ухода пользователя исходя из имеющихся данных для планирования маркетинговой кампании| *pandas, numpy, sklearn, lightgbm, catboost, matplotlib, seaborn* |

#### [Машинное обучение для текстов](https://github.com/svotyakov/Yandex.Practium/tree/main/Natural-Language-Processing-NLP)
| Название проекта| Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Предсказание токсичных комментариев](https://github.com/svotyakov/Yandex.Practium/blob/main/Natural-Language-Processing-NLP/Finding_toxic_commentsPipelineLR.ipynb) |Построение модели, которая будет отправлять подозрительные комментарии пользователей на модерацию. | *pandas, numpy, sklearn(TfidfVectorizer, LogisticRegression, f1_score, train_test_split, Pipeline, GridSearchCV, FeatureUnion), nltk, re, Detoxify* |
| | | |
| [Предсказание токсичных комментариев Detoxify](https://github.com/svotyakov/Yandex.Practium/blob/main/Natural-Language-Processing-NLP/Finding_toxic_comments_Detoxify.ipynb) |Построение модели, которая будет отправлять подозрительные комментарии пользователей на модерацию с использованием модуля Detoxify, вычисления с GPU, Colab. | *pandas, numpy, sklearn(TfidfVectorizer, LogisticRegression, f1_score, train_test_split, Pipeline, GridSearchCV, FeatureUnion), nltk, re, Detoxify* |

#### [Анализ временных рядов](https://github.com/svotyakov/Yandex.Practium/tree/main/Time_series_forecasting)
| Название проекта| Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Предсказание загрузки такси](https://github.com/svotyakov/Yandex.Practium/blob/main/Time_series_forecasting/Next_hour_predictions.ipynb) |Для привлечения оптимального водителей в различные временные периоды, нужно спрогнозировать количество заказов такси на следующий час. | *pandas, numpy, seasonal_decompose, sklearn(mean_squared_error, train_test_split, LinearRegression, TimeSeriesSplit), lightgbm, matplotlib.pyplot*|
