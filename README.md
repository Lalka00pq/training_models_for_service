
# Тренировка моделей для детекции падения людей

В проекте показана тренировака моделей семейства YOLO-pose и YOLO-NAS для детекции падения людей.




## Где используется

Модели из данного проекта используется при в работе нейросетевого сервиса [Human detection project](https://github.com/Lalka00pq/human_detection_project)


## Авторы

- [@Lalka00pq](https://github.com/Lalka00pq)



## Стек технологий

- PyTorch 2.6.0+cu124
- Ultralytics 8.3.107
- Wandb 0.19.9




## Установка

1. Клонировать проект 
```bash
git clone https://github.com/Lalka00pq/training_models_for_service
```
2. Создание виртуального окружения
Если используется `uv`:
```bash
uv venv
```
Если используется `pip`:
```bash
pip venv .venv
```
Активируйте виртуальное окружение:

Linux/macOS:
```bash
source .venv/bin/activate
```
Windows:
```powershell
.venv\Scripts\Activate.ps1
```

3. Установить зависимости
Если используется `uv`:
```bash
uv sync
```
Если используется `pip`
```bash
pip install -r requirements.txt
```
    
