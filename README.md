> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/brolykdanyysamp73/tidal-live-stream-botting/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py main.py`
> 
>  or
> 
> `python main.py`


# Tidal Song Playing Bot

## How to setup for local machine.

### Install requirements.
* ``pip install -r requirements.txt``

### Run following command to browsec install extension.
* ``python ``[utils.py](utils.py)

Following variables are defined in [config.py](config.py) file.
* ``LINKS_PER_ACCOUNT = 10``
* ``SONGS_PER_URL = 10``
* ``LIKE_SONG_CHANCE = 20``
* ``FOLLOW_ARTIST_CHANCE = 20``
* ``MINIMUM_SONGS_PER_LINK = 5``
* ``MAX_SONGS_PER_LINK = 20``
* ``MINIMUM_LINKS_PER_ACCOUNT = 1``
* ``MAX_LINKS_PER_ACCOUTN = 20``
* ``PROXY_LIST = []``
* ``MAX_THREADS = 2``
* ``USE_PROXY = False``
* ``USE_BROWSEC = True``


Main directory should contains the credentials.txt file with following format on each line.
* ``emailx:password``
* ``emaily:password``

Finally run
* ``python ``[main.py](main.py)

gy