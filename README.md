# flower-classification-project

Проєкт класифікує зображення квітів за 5 класами. Реалізовано дві моделі: власна CNN і ResNet50 з Transfer Learning.

## Основні етапи:
- Завантаження та підготовка датасету
- Побудова та тренування власної CNN
- Гіперпараметрична оптимізація (ручна + Optuna)
- Transfer Learning з ResNet50
- Візуалізація, матриця плутанини, оцінка якості

## Використано:
- PyTorch
- Torchvision
- Optuna
- Sklearn
- Matplotlib
