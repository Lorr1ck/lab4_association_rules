# Лабораторная работа №4: Поиск ассоциативных правил

## Описание
Реализация алгоритмов Apriori и FP-Growth с нуля. Поиск ассоциативных правил в транзакционных данных.

## Датасет
Online Retail (сокращённая версия) / синтетические данные

## Структура
- `data/transactions.csv` – транзакционные данные
- `notebooks/04_association_rules.ipynb` – основной ноутбук
- `report/association_report.md` – отчёт

## Запуск
```bash
git clone https://github.com/Lorr1ck/lab4_association_rules.git
cd lab4_association_rules
pip install pandas numpy matplotlib seaborn networkx
jupyter notebook notebooks/04_association_rules.ipynb
