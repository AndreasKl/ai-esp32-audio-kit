# ai-esp32-audio-kit
Things I learned while playing with the audio kit.

## Setup

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
git clone --recursive https://github.com/Ai-Thinker-Open/ESP32-A1S-AudioKit.git

✔ ~/Coding/ESP32-A1S-AudioKit/esp-idf [:722043f73|✔] 
./install.sh

✔ ~/Coding/ESP32-A1S-AudioKit/esp-idf [:722043f73|✔] 
22:05 $ . ./export.sh


cd ./ESP32-A1S-AudioKit/examples/get-started/play_mp3_dac
make menuconfig
make flash monitor




21:45 $ cat ~/Coding/ESP32-A1S-AudioKit/.env
export PATH="$PATH:$HOME/Tools/esp/xtensa-esp32-elf/bin"
export ADF_PATH="/home/andreaskluth/Coding/ESP32-A1S-AudioKit"
export IDF_PATH="/home/andreaskluth/Coding/ESP32-A1S-AudioKit/esp-idf"
```

## Compile a demo app
```bash
```


See for general instructions:
https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html#get-started-get-esp-idf
https://docs.espressif.com/projects/esp-idf/en/release-v3.0/get-started/linux-setup.html
