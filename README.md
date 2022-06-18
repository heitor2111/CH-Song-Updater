<p align="center">
    <a href="https://github.com/heitor2111/CH-Song-Updater">
        <img
            src="https://i.ibb.co/xY3WcCz/Novo-Projeto.png"
            alt="CH Song Updater"
        />
    </a>
</p>

----------

## About CH Song Updater

Clone Hero Song Updater is a unofficial project for [Clone Hero](https://clonehero.net), dedicated to [Python 3](https://python.org) studies.

This script **tries** to update the metadata, cover art and music video of songs installed in [Clone Hero](https://clonehero.net) from your computer, searching on [MusicBrainz](https://musicbrainz.org) and [YouTube](https://youtube.com) database, downloading available data and updating in each song folder.

## Dependencies:

- [alive-progress](https://github.com/rsalmei/alive-progress) to show the progress bar.
- [musicbrainzngs](https://python-musicbrainzngs.readthedocs.io) to search and download metadata and cover arts.
- [pytube](https://pytube.io) to search and download [YouTube](https://youtube.com) videos.

#### *To install all dependencies automatically, run this command:*

`pip install -r dependencies.txt`

##### In the current version of [pytube](https://pytube.io) (12.1.0) there is a bug when getting the video streams. To fix the bug, just look for the *cipher.py* file and replace line 30 with the command `var_regex = re.compile(r"^\$*\w+\W")`.

## License

The CH Song Updater script is open-sourced software licensed under the MIT license.

----------

## Sobre o CH Song Updater

Clone Hero Song Updater é um projeto não oficial para o [Clone Hero](https://clonehero.net), dedicado aos estudos em Python 3.

Esse script tenta atualizar os metadados, a arte da capa e o vídeoclipe das músicas instaladas no [Clone Hero](https://clonehero.net) do seu computador, fazendo uma busca no banco de dados do [MusicBrainz](https://musicbrainz.org) e no [YouTube](https://youtube.com), baixando os dados disponíveis e atualizando na pasta de cada música.

## Dependências:

- [alive-progress](https://github.com/rsalmei/alive-progress) para mostrar a barra de progresso.
- [musicbrainzngs](https://python-musicbrainzngs.readthedocs.io) para buscar e baixar os metadados e a arte da capa.
- [pytube](https://pytube.io) para buscar e baixar o video do [YouTube](https://youtube.com).

#### *Para instalar todas as dependências automaticamente, execute este comando:*

`pip install -r dependencies.txt`

##### Na versão atual do [pytube](https://pytube.io) (12.1.0), existe um bug ao obter as streams do video. Para resolver o bug, procure pelo arquivo *cipher.py* dentro da pasta onde está instalado o pacote e substitua a linha 30 pelo comando `var_regex = re.compile(r"^\$*\w+\W")`.

## Licença

O script CH Song Updater é um software de código aberto licenciado sob a licença do MIT.

----------

## Acerca de CH Song Updater

Clone Hero Song Updater es un proyecto no oficial de [Clone Hero](https://clonehero.net), dedicado a los estudios de [Python 3](https://python.org).

Este script **intenta** actualizar los metadatos, la carátula y el video musical de las canciones instaladas en [Clone Hero](https://clonehero.net) desde su computadora, buscando en [MusicBrainz](https://musicbrainz. org) y la base de datos de [YouTube](https://youtube.com), descargando los datos disponibles y actualizándolos en cada carpeta de canciones.

## Dependencias:

- [alive-progress](https://github.com/rsalmei/alive-progress) para mostrar la barra de progreso.
- [musicbrainzngs](https://python-musicbrainzngs.readthedocs.io) para buscar y descargar metadatos y portadas.
- [pytube](https://pytube.io) para buscar y descargar videos de [YouTube](https://youtube.com).

#### *Para instalar todas las dependencias automáticamente, ejecute este comando:*

`pip install -r dependencies.txt`

##### En la versión actual de [pytube](https://pytube.io) (12.1.0) hay un error al obtener las transmisiones de video. Para corregir el error, simplemente busque el archivo *cipher.py* y reemplace la línea 30 con el comando `var_regex = re.compile(r"^\$*\w+\W")`.

## Licencia

El script CH Song Updater es un software de código abierto con licencia MIT.
