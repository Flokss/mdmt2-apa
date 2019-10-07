# Плагин для [mdmTerminal2](https://github.com/Aculeasis/mdmTerminal2)
```
Код не мой, мой только файл Readme.
Если найду автора, обязательно укажу его.
```
# Описание
Плагин управляет встроенными светодиодами APA102 на плате Respeaker 2.
Проверено на платах RPI 3 и RPI Zero.

# Установка
 
```
cd 
~/mdmTerminal2/env/bin/python -m pip install spidev

~/mdmTerminal2/env/bin/python -m pip install gpiozero

~/mdmTerminal2/env/bin/python -m pip install numpy

cd ~/mdmTerminal2/src/plugins
git clone https://github.com/Flokss/mdmt2-apa.git

```

И перезапустить терминал.



