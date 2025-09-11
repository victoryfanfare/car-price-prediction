# 🚗 Определение стоимости автомобилей (Car Price Prediction)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![CatBoost](https://img.shields.io/badge/CatBoost-Gradient%20Boosting-yellow)
![LightGBM](https://img.shields.io/badge/LightGBM-Gradient%20Boosting-red)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML%20Models-purple)

Модель машинного обучения для определения рыночной стоимости автомобилей с пробегом. Разработана для быстрой оценки стоимости автомобилей.

## 🎯 О проекте

Проект посвящен разработке модели регрессии для точного прогнозирования стоимости подержанных автомобилей на основе их технических характеристик, комплектации и исторических данных.

**Ключевые особенности:**
- 📊 Глубокий анализ данных и выявление аномалий
- 🛠️ Feature engineering и обработка пропущенных значений
- 🤖 Сравнение нескольких ML-моделей (Decision Tree, CatBoost, LightGBM)
- ⚙️ Оптимизация гиперпараметров с RandomizedSearchCV
- 🎯 Достижение целевой метрики RMSE
- ⚡ Оптимизация скорости предсказания

## 📁 Структура проекта
- forecasting_taxi_orders/
- ├── 📓 car_price_prediction.ipynb # Полное исследование в Jupyter
- ├── 📈 results/                       # Результаты и графики
- └── 📖 README.md                      # Документация

## 🛠️ Технологический стек

- **Python 3.8+** - основной язык разработки
- **Pandas** - обработка и анализ данных
- **NumPy** - математические операции
- **Scikit-learn** - ML модели и preprocessing
- **CatBoost** - градиентный бустинг от Yandex
- **LightGBM** - градиентный бустинг от Microsoft
- **Phik** - анализ корреляций
- **Matplotlib/Seaborn** - визуализация
- **Jupyter Notebook** - интерактивная среда разработки

## 📊 Данные

### Источник данных:
- Исторические данные о продажах автомобилей с пробегом
- 354,369 записей с 16 признаками

### Основные признаки:
- `Price` - целевая переменная (цена автомобиля)
- `VehicleType` - тип транспортного средства
- `RegistrationYear` - год регистрации
- `Gearbox` - тип коробки передач
- `Power` - мощность двигателя
- `Model` - модель автомобиля
- `Kilometer` - пробег
- `FuelType` - тип топлива
- `Brand` - марка автомобиля
- `Repaired` - была ли машина в ремонте

## 🚀 Быстрый старт

```bash
# Клонирование репозитория
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
