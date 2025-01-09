# Пояснение
Это форк репозитория Warp, который переехал в GitLab -> https://gitlab.com/fscarmen/warp.  
В форк добавлен один файл из main репозитория -> [menu.sh](https://gitlab.com/fscarmen/warp/-/blob/main/menu.sh).  

Это сделано, т.к. по каким-то причинам wget запросы к gitlab.com с vps получают ответ 302.  
Запросы `wget https://gitlab.com/fscarmen/warp/-/raw/main/menu.sh` нужны для работы скрипта [install_warp_proxy.sh](https://github.com/Dandellion007/x-ui-scripts/blob/main/install_warp_proxy.sh).
