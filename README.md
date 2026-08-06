# Портфолио Data Science и Machine Learning

В этом репозитории собраны учебные и прикладные проекты по анализу данных, классическому машинному обучению, нейронным сетям, NLP, кластеризации и снижению размерности.

Проекты оформлены как портфолио-кейсы в Jupyter Notebook: в начале каждого ноутбука есть краткое описание задачи, данных, подхода, результата и использованного стека.

## Рекомендуемый порядок просмотра

1. [Генерация и оценка описаний учебных курсов с NLP и LLM](nlp-course-description-generation.ipynb)
2. [Нейронные сети и CNN на PyTorch](pytorch-neural-networks-cnn.ipynb)
3. [Прогнозирование оттока клиентов с Decision Tree и Random Forest](churn-decision-trees-random-forest.ipynb)
4. [Компоненты нейронной сети с нуля](neural-network-from-scratch.ipynb)
5. [Сегментация клиентов с K-Means и DBSCAN](customer-clustering-kmeans-dbscan.ipynb)
6. [Снижение размерности и факторный анализ](factor-analysis-dimensionality-reduction.ipynb)

## Проекты

| Проект | Фокус | Стек | Что показывает |
| --- | --- | --- | --- |
| [Генерация описаний учебных курсов](nlp-course-description-generation.ipynb) | Предобработка текста, эмбеддинги, генерация LLM, оценка качества | pandas, NLTK, pymystem3, Word2Vec, SentenceTransformers, Hugging Face API, seaborn, plotly | Самый сильный end-to-end проект: NLP pipeline, prompting, количественная оценка и визуальный анализ результатов. |
| [Нейронные сети и CNN на PyTorch](pytorch-neural-networks-cnn.ipynb) | Практический deep learning workflow | PyTorch, torchvision, Dataset/DataLoader, NumPy, pandas, scikit-learn | Умение работать с PyTorch: тензоры, датасеты, training loop, оптимизаторы и сверточные сети. |
| [Прогнозирование оттока клиентов](churn-decision-trees-random-forest.ipynb) | Классификация и интерпретация моделей | pandas, scikit-learn, SHAP, seaborn, matplotlib | Прикладной ML-кейс: подготовка данных, сравнение моделей и анализ важности признаков. |
| [Нейронная сеть с нуля](neural-network-from-scratch.ipynb) | Базовая механика нейронных сетей | NumPy, scikit-learn, PyTorch, matplotlib, seaborn | Понимание forward pass, функций активации, функций потерь и роли нелинейности. |
| [Сегментация клиентов](customer-clustering-kmeans-dbscan.ipynb) | Обучение без учителя | scikit-learn, pandas, NumPy, matplotlib | Сравнение центроидной и плотностной кластеризации на синтетических и клиентских данных. |
| [Снижение размерности и факторный анализ](factor-analysis-dimensionality-reduction.ipynb) | Исследование структуры многомерных данных | PCA, t-SNE, StandardScaler, seaborn, matplotlib | Базовый exploratory workflow для визуализации и интерпретации многомерных признаков. |

## Как запустить

Создать виртуальное окружение и установить зависимости:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Открыть ноутбуки в Jupyter:

```bash
jupyter notebook
```

Некоторые ноутбуки загружают публичные датасеты или обращаются к внешним API. Токены, локальные датасеты, модели и другие крупные артефакты не хранятся в репозитории.
