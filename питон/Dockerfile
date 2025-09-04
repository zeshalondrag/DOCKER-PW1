# Базовый образ 
FROM python:alpine

# Метаданные образа
LABEL version="1.0.1"

# Установка рабочей директории в контейнере
WORKDIR /testdir/python

# Копирование файлов в контейнер (из текущей директории в /testdir/python)
COPY . /testdir/python/

# Установка зависимостей
CMD [ "python" , "test.py" ]