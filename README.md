# Тестовое задание для стажировки 

## Инструкция по запуску

---
Запуск контейнера с программой:

Сборка:

```zsh
git clone https://github.com/https://github.com/ArtemPr1/test-problem
cd test-problem
docker build --tag problem .

```

Запуск:

```zsh
docker run problem:latest /main tests/basic.txt
```

Также можно посмотреть результаты работы программы на тестовых входных данных:

```zsh
docker run -it problem:latest bash
cd /app/tests/out
cat basic.out
...
```
