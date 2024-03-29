# Прогноз поведения клиента

**Описание проекта**

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

---
**Цель проекта**

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет, основываясь на исторических данных о поведении клиентов и расторжении договоров с банком. Построим модель с предельно большим значением `F1-меры`, доведя метрику до 0.59.

---
**Описание данных**

Набор данных находится в файле `Churn.csv`.

Признаки:
- `RowNumber` — индекс строки в данных
- `CustomerId` — уникальный идентификатор клиента
- `Surname` — фамилия
- `CreditScore` — кредитный рейтинг
- `Geography` — страна проживания
- `Gender` — пол
- `Age` — возраст
- `Tenure` — сколько лет человек является клиентом банка
- `Balance` — баланс на счёте
- `NumOfProducts` — количество продуктов банка, используемых клиентом
- `HasCrCard` — наличие кредитной карты
- `IsActiveMember` — активность клиента
- `EstimatedSalary` — предполагаемая зарплата
  
Целевой признак:
- `Exited` — факт ухода клиента
