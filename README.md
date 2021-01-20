# AutoBCI

## Plataforma de Interface Cérebro-Máquina com Configuração Automatizada
---

### Demo: 
- https://youtu.be/5l7inGVSwsc

### Instalação em sistemas Linux (Preparação do sistema): ##
```shell
sudo apt install python3.7 python3-pip
sudo ln -sf /usr/bin/python3.7 /usr/bin/python
sudo apt-get install -y libglib2.0-dev sox xclip xsel build-essential libsdl2-dev libsdl2-image-dev libsdl2-mixer-dev libsdl2-ttf-dev libportmidi-dev libswscale-dev libavformat-dev libavcodec-dev zlib1g-dev ffmpeg
sudo chmod 777 /dev/input/event*
```

### Clonar o repositório (ou efetuar o download)
```shell
git clone https://github.com/vitorvilasboas/autobci
```

### Intalação de dependências (módulos python):
```shell
cd ~/Download/autobci/
python -m pip install -r requirements.txt
```

### Executar a plataforma (executar a partir do diretório raiz do autobci)
```shell
python main.py
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
