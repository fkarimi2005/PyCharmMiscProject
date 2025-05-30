# 📊 Анализ данных о продажах видеоигр (Video Game Sales 2024)

## 1. Общее описание данных

- Датасет содержит информацию об играх: название, жанр, платформа, издатель, оценка критиков, глобальные продажи и др.
- После очистки и кодирования данных использовались следующие признаки:
  - `console` — игровая платформа
  - `publisher` — издатель
  - `critic_score` — оценка критиков
  - `genre` — жанр игры
  - `total_sales` — глобальные продажи

## 2. Модель машинного обучения — Прогнозирование глобальных продаж (регрессия)

Использовались две модели:
- **Linear Regression**
- **Random Forest Regressor**

**Метрики качества:**
| Модель               | MSE (ошибка) | R² (качество) |
|----------------------|--------------|----------------|
| Linear Regression    | …            | …              |
| Random Forest        | …            | …              |

_Вывод_: Random Forest показал лучшую точность на тестовых данных.

## 3. Визуализация данных

- 📈 **Гистограмма глобальных продаж** показала, что большинство игр имеют продажи менее 1 миллиона копий.
- 🎯 **Диаграмма рассеяния** между `critic_score` и `total_sales` показала слабую положительную корреляцию.
- 📦 **BoxPlot** по жанрам выявил, что жанры Action и Sports чаще приносят больше продаж.
- 🏆 **Топ-10 издателей** по средним продажам визуализированы с помощью `barplot`.

## 4. Выводы

- На продажи игр влияют такие факторы, как оценка критиков, жанр и издатель.
- Лучшую точность прогноза показала модель случайного леса.
- Большинство игр не становятся блокбастерами — высокие продажи имеют лишь небольшая часть.

---

