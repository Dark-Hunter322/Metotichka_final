# Metotichka_final
1)	Создай папку, открываешь и в ней правой кнопкой мышей – открыть терминал
2)	Пишешь  python3 -m venv .venv 
3)	source .venv/bin/activate
4)	sudo dnf install vscode
5)	sudo dnf install -y dbeaver
6)	sudo dnf install postgresql postgresql-server postgresql-devel
7)	проверка какая версия накатана : psql –version
8)	systemctl start postgresql12
9)	systemctl status postgresql12
10)	дальше проверяешь наличие гита: git –version , если нету там напишет
11)	sudo dnf install git-core
12)	git clone git clone https://github.com/Dark-Hunter322/Metotichka1_final.git
13)	git clone https://github.com/Dark-Hunter322/chudo_obuv2.git
14)	code .
15)	открываешь dbeaver , после настраиваешь соединение у слона, вводишь туда пароль 12345678, галку ставить показывать все базы данных, и драйвера накати если нету их.
16)	Создаешь новую БД, в ней делаешь запрос sql который лежит в vscode .sql
17)	Выполняешь запрос
18)	Возвращаешься в терминал vscode, туда накатываешь все библиотеки питона:
19)	pip3 install PySide6 psycopg2-binary openpyxl
20)	после каждого изменения интерфейса пишешь для каждой библиотеки ui:
21)	pyside6-uic login.ui -o ui_login.py
