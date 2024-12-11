Клонирование репозитория:
git clone https://github.com/Bolidik/Tdata-converter
cd Tdata-converter


Windows manual installation
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python main.py

Linux manual installation
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
python3 main.py

Структура папок:
raw_converter/tdata_to_sessions/: ##Сюда поместите папки с распакованными данными TData. Каждая папка должна содержать папку tdata.
Например: 
raw_converter/tdata_to_sessions/account1/tdata, 
raw_converter/tdata_to_sessions/account2/tdata и т.д.

raw_converter/res_sessions/: Сюда будут сохраняться готовые сессии Pyrogram и Telethon.
