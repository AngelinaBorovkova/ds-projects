# Data Science Projects Repository

## 📂 Структура репозитория
```
/ds-projects  
│── README.md                      # Этот файл  
│── /customer-segmentation         # Сегментация клиентов  
│   │── customer_segmentation.ipynb  
│   │── /credit_card_dataset  
│   │   │── Train.csv  
│── /fraud-transactions            # Анализ мошеннических операций  
│   │── fraud-prediction.ipynb  
│   │── bank-transactions-analysis.ipynb  
│   │── /credit_card_fraud_dataset  
│   │   │── fraudTrain.csv  
│── /recommendations-and-churn     # Рекомендательная система и прогнозирование оттока  
│   │── recommendation-system.ipynb  
│   │── churn-prediction.ipynb  
│   │── /bank_clients_data  
│   │   │── bank_clients_data.csv  
```

## 🚀 Проекты

### 1. Customer Segmentation Using KMeans and DBSCAN
**Цель**: Сегментация клиентов банка по транзакционной активности  
**Технологии**: Python, KMeans, DBSCAN, PCA  
**Ключевые результаты**:
- Выделено 3 ключевых сегмента клиентов
- Разработаны персонализированные маркетинговые стратегии
- Обнаружены аномальные транзакции

[Подробнее →](./customer-segmentation/)

### 2. Fraud Transactions Analysis & Prediction
**Цель**: Выявление и прогнозирование мошеннических операций  
**Технологии**: Pandas, RandomForest, CatBoost, Optuna  
**Ключевые результаты**:
- Анализ временных и категориальных паттернов фрода
- Построена модель с F1-score 0.82
- Разработаны рекомендации по детекции аномалий

[Подробнее →](./fraud-transactions/)

### 3. Bank Churn Prediction
**Цель**: Прогнозирование оттока клиентов банка  
**Технологии**: RandomForest, CatBoost, Feature Importance  
**Ключевые результаты**:
- Выявлены ключевые факторы оттока (возраст, баланс, география)
- ROC AUC модели: 80%
- Рекомендации по снижению оттока на 15-20%

[Подробнее →](./recommendations-and-churn-prediction/)

### 4. Banking Recommendation System
**Цель**: Персонализированные рекомендации банковских продуктов  
**Технологии**: KMeans, DBSCAN, GMM, PCA  
**Ключевые результаты**:
- 4 четких сегмента клиентов
- Автоматизированные рекомендации для каждого сегмента
- Потенциал интеграции с CRM-системой

[Подробнее →](./recommendations-and-churn-prediction/)

---

## 🛠 Технологический стек

**Основные библиотеки:**
```python
pandas, numpy, scikit-learn, catboost, matplotlib, seaborn
```

**Методы ML:**
- Кластеризация: `KMeans`, `DBSCAN`, `GMM`
- Классификация: `RandomForest`, `CatBoost`
- Оптимизация: `Optuna`
- Визуализация: `PCA`, `t-SNE`

**Дополнительно:**
```python
imbalanced-learn, plotly, yellowbrick, scipy
```
---

## 📊 Ключевые навыки
- Предобработка и анализ финансовых данных
- Построение и интерпретация ML-моделей
- Бизнес-аналитика и формирование рекомендаций
- Визуализация и презентация результатов

## 📞 Контакты
Ангелина Боровкова  
t.me/angborovkova