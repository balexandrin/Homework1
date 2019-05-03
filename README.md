текущая версия ядра: 
uname -sr
Linux 3.10.0-957.5.1.el7.x86_64

Скачал с сайта kernel.org архив longterm: 4.19.38.
Распаковал архив в /usr/src.
Сопировал файл /boot/config-3.10.0-957.5.1.el7.x86_64 в файл /usr/src/linux-4.19.38/.config.
Выполнил make oldconfig соглашаясь со всеми предложениями скрипта.
Установил необходимые пакеты yum install -y ncurses-devel make gcc bc bison flex elfutils-libelf-devel openssl-devel grub2.
Выполнил make && make modules && make && make install && make modules_install.
Процесс шел очень долго, и закончился выводом строки "DEPMOD  4.19.38".


Файлы .config, .config.old, yum.log - выложены рядом.
