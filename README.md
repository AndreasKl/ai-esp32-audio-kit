# ai-esp32-audio-kit
Things I learned while playing with the audio kit.

**Setup dependencies and chain on fedora 33**

```bash
$ sudo dnf install git wget make ncurses-devel flex bison gperf python python3-pyserial
```

**Download the toolchain**

```bash
$ wget https://dl.espressif.com/dl/xtensa-esp32-elf-linux64-1.22.0-80-g6c4433a-5.2.0.tar.gz
$ mkdir -p ~/Tools/esp
$ cd ~/Tools/esp
$ tar -xzf donwload/folder/xtensa-esp32-elf-linux64-1.22.0-80-g6c4433a-5.2.0.tar.gz
```


```
21:45 $ cat ~/Coding/ESP32-A1S-AudioKit/.env
export ADF_PATH="/home/andreaskluth/Coding/ESP32-A1S-AudioKit"
export IDF_PATH="/home/andreaskluth/Coding/ESP32-A1S-AudioKit/esp-idf"

```



See for general instructions:
https://docs.espressif.com/projects/esp-idf/en/release-v3.0/get-started/linux-setup.html
