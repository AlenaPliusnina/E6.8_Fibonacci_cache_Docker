# E6.8_Fibonacci_cach_Docker

Описание веб-приложения:

    - сервис по GET запросу с параметром k возвращать k-ое число Фибоначчи (http://localhost:8081/k);
    
    - если число уже было запрошено, результат берется из кеша, а не пересчитываться (использована библиотека pymemcache);
    
    - приложение можно запустить в Docker при помощи команды: docker-compose up server
