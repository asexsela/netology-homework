# 05-virt-03-docker-usage

1. Подходит ли в этом сценарии использование докера? Или лучше подойдет виртуальная машина, физическая машина? Или возможны разные варианты?
    1. Ответ: WMware что бы эффективнее использовать ресурсы благодаря удобной системе управления жизненным циклом и ускоренному масштабированию по сравнению с физическими устройствами, но вообще я думаю можно и докер использовать.
2. 
    1. Ответ: docker hub - https://hub.docker.com/r/asexsela/05-virt-03-docker-usage
    git - https://github.com/asexsela/netology-homework/tree/master/05-virt-03-docker-usage/docker


# Run
```bash
    docker run -d -p 8080:80 docker-netology:latest
```