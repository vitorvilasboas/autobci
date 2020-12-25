# AutoBCI
---
## Plataforma de Interface Cérebro-Máquina com Configuração Automatizada


## Instalação em sistemas Linux ##
```shell
sudo apt install python3.7 python3-pip
pip install numpy scipy matplotlib scikit-learn pyserial
pip install git+https://github.com/kivy/kivy
pip install kivy-garden
garden install bar
garden install graph
pip install hyperopt pygame pyautogui plyer pyOpenBCI
pip install xorg-libx11
pip install -U https://api.github.com/repos/mne-tools/mne-python/zipball/master
sudo apt-get install xclip xsel
sudo chmod 777 /dev/input/event*
```

## Clonar o repositório (ou efetuar o download) ##
```shell
git clone https://github.com/vitorvilasboas/autobci
```

## Executar a plataforma (executar de dentro do diretório raiz do autobci) ##
```shell
python autobci
```
