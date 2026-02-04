# ESP-FUN

I bought an esp32 starter kit and I am going to mess around with it.

# ENVIRONMENT

since I use wsl2 as my go to environment I will be following a guide that allows me to flash, monitor, and build using esp-idf directly from the terminal. I will link it below 

![ESP-IDF on WSL2 (Ubuntu 20.04) for programming ESP32
 - Alija Bobija](https://www.youtube.com/watch?v=eQ0D8pnZTSY)

 # NOTE ON ESP_IDF VENV

 run this command on each new shell

 `. $HOME/esp/esp-idf/export.sh`

 or else you will get error

```
 No module named 'click'
This usually means that "idf.py" was not spawned within an ESP-IDF shell environment or the python virtual environment used by "idf.py" is corrupted.
Please use idf.py only in an ESP-IDF shell environment. If problem persists, please try to install ESP-IDF tools again as described in the Get Started guide.
```

whenever you run idf.py

# PROJECT STRUCTURE

run 

`idf.py create-project .`

in an empty directory to create the idf project structure.