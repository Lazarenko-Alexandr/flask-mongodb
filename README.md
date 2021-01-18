# Использование Docker с БД, кластеризация
1. Run cluster
```shell script
sudo docker-compose up --scale app=2 -d --build --force-recreate
```
2. Checkout http://localhost to see result
