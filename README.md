# 🏠 Регрессионный анализ рынка недвижимости Алматы

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Regression-F7931E?logo=scikitlearn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

Аналитический проект: **предсказание цены квартир** в Алматы с помощью пяти моделей регрессии.

## Датасет
500 квартир, 11 признаков, цена 12–950 млн ₸, 7 районов Алматы.

## Структура
```
almaty-housing-regression/
├── Regression_Analysis_Housing.ipynb
├── almaty_housing.csv
├── model_results.csv
├── fig1_eda.png ... fig6_regularization.png
└── README.md
```

## Модели
| Модель | R² | RMSE |
|--------|----|------|
| Simple LR | 0.801 | 112.1M |
| Multiple LR | 0.797 | 110.5M |
| Ridge | 0.796 | 110.8M |
| **Lasso** | **0.799** | **110.1M** |
| Polynomial(2) | 0.796 | 110.9M |

## Установка
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Regression_Analysis_Housing.ipynb
```
