Arkanoid
########

Arkanoid - игра, в которой Вам нужно разбить все блоки с помощью шарика.
Каждый блок имеет несколько жизней, за один удар шарика снимается одна жизнь.
Управление шариком происходит с помощью панели внизу. Если шарик упадет вниз,
то игрок теряет одну жизнь (всего их три). Количество жизней отображается
в верхнем левом углу.

Как только вы откроете игру, то увидете меню опций:
Resume - продолжить игру, если она была поставлена на паузу;
New Game - начать новую игру;
Quit - выйти из игры.

Во время игры вы можете управлять платформой с помощью стрелок
вправо и влево на клавиатуре. Если во время движения платформы с ней
столкнется шар, то угол его движения изменится на случайную величину
в соответствии с направлением движения платформы. При нажатии кнопки
Escape игра будет поставлена на паузу, и отобразится игровое меню.
<cheat> При нажатии кнопки X случайный блок потеряет одну жизнь. </cheat>

Как только игра завершится (вы выйграете или проиграете), то отобразится
соответствующее сообщение. Нажмите по нему левой кнопкой мыши, чтобы вернуться
в игровое меню.

Запуск
######

python run.py

Системные требования
####################
    Python 3.4+
    PyGame

Файлы игры
##########

resources         - Директория с игровыми ресурсами: музыкой и картинками.
arkanoid.py       - Содержит все игровые классы. При запуске данного файла
                    игра запустится в отладочном режиме.
decomposition.svg - Описание иерархии классов и делегирования.
geometry.py       - Пакет, содержащий некоторый геометрический функционал
                    игры.
README.txt        - Этот файл.
run.py            - Файл для запуска игры.
TestBallPath.py   - Файл для тестирования траектории движения игрового мяча.
