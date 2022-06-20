# Задание 2

Создание образа:
```dockerfile
docker build -t stocksproducts:1
```

Запуск контейнера:
```dockerfile
docker container run -d -p 8000:8000 stocksproducts:1
```
