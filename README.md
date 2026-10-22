# CI/CD Student Project

![CI Status](https://github.com/Fil1n32/ci-cd-student-project/actions/workflows/ci.yml/badge.svg)

Простой проект для демонстрации CI/CD pipeline с автоматическим тестированием.

## Возможности

- Класс `Calculator` с операциями сложения, вычитания, умножения, деления и возведения в степень.
- Модульные тесты на pytest.
- Проверка стиля кода (flake8) и безопасности (bandit) в GitHub Actions.

## Установка

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## Запуск тестов

```bash
pytest tests/ -v
pytest tests/ --cov=src --cov-report=xml
```

## Структура

```
ci-cd-student-project/
├── src/calculator.py
├── tests/test_calculator.py
├── .github/workflows/ci.yml
├── requirements.txt
└── README.md
```

