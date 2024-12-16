## 1. Скопируйте все файлы
## 2. Установите свои значения в .env
```
PORT=
HOST=
REDIS_PORT=
```
## 3. Установите зависимости
```
pip install -r requirements.txt
```
## 4. Перед выполнением программы убедитесь что Redis запущен
```
#Если Redis установлен через WSL, выполните следующую команду powershell
sudo service redis-server start
```
## 5. Выполнение программы
```
# перейдите в директорию проекта
cd otrpo_9 & python main.py
```
