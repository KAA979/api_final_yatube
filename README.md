# Проект «API для Yatube»
### Описание проекта:
Задание заключалось в использовании способа проектирования программной части API, основываясь на документации представленой в формате [ReDoc](https://github.com/Redocly/redoc) по адресу [http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/). Документация — это техническое задание.

Необходимо было написать код и привести его в соответствие с документацией: добавить недостающие модели в приложении **posts**, создать адреса и представления для обработки запросов в приложении **api**.


---

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```bash
git clone https://github.com/KAA979/api_final_yatube.git
```
```bash
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```bash
python3 -m venv env
```
```bash
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```bash
python3 -m pip install --upgrade pip
```
```bash
pip install -r requirements.txt
```

Выполнить миграции:

```bash
python3 manage.py migrate
```

Запустить проект:

```bash
python3 manage.py runserver
```

---
Автор: [Андрей Казанджян](https://github.com/KAA979) &#128013;.
