# AutoBCI

## Plataforma de Interface Cérebro-Máquina com Configuração Automatizada
---

### Demo: 
- https://youtu.be/5l7inGVSwsc

### Instalação em sistemas Linux ##
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

### Clonar o repositório (ou efetuar o download)
```shell
git clone https://github.com/vitorvilasboas/autobci
```

### Executar a plataforma (executar de dentro do diretório raiz do autobci)
```shell
python autobci
```

### Dados públicos de EEG incorporados: ###
* BCI Competition III: http://bbci.de/competition/iii/index.html
* BCI Competition IV: http://bbci.de/competition/iv/index.html
* LEE et al., 2019: http://gigadb.org/dataset/view/id/100542

* Dados III3a, III4a, IV2a e IV2b devidamente compatibilizados com o AutoBCI disponíveis <a href="https://iftoedubr-my.sharepoint.com/:u:/g/personal/vitorvilasboas_ifto_edu_br/EUNu9fhzsUBJudJuNybEX38B2-xhEln8z0SZjUau0XI3ag?e=FtWXp1" target="blank">aqui</a>.

### Conteúdo extra (códigos experimantais):
* ./dsformat/ &nbsp;&nbsp; :: Scripts para normalização de dados públicos de EEG (Formato para AutoBCI)
* ./scripts/ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :: Scripts python de laboratório (cenários independentes)

### Ferramentas recomendadas para edição: ###

* Sistema Operacional Linux (derivados Debian)
* Plataforma Anaconda: https://www.anaconda.com/distribution/
* IDE Spyder (Disponível via Anaconda)
* IDE PyCharm: https://www.jetbrains.com/pycharm/promo/anaconda/

* para mais detalhes acesse https://vitorvilasboas.github.io/autobci/ (em construção)
