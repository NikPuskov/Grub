# Grub
Включаем меню загрузчика

nano /etc/default/grub

#GRUB_TIMEOUT_STYLE=hidden

GRUB_TIMEOUT=10

update-grub

reboot

e

Попадаем в систему без пароля с помощью init=/bin/bash
![Image alt](https://github.com/NikPuskov/Grub/blob/main/grub1.jpg)
![Image alt](https://github.com/NikPuskov/Grub/blob/main/grub2.jpg)

Попадаем в систему без пароля с помощью Recovery Menu
![Image alt](https://github.com/NikPuskov/Grub/blob/main/grub3.jpg)

Переименовываем VG в LVM

![Image alt](https://github.com/NikPuskov/Grub/blob/main/grub4.jpg)

В файле /boot/grub/grub.cfg ищем и изменяем название VG ubuntu-vg на ubuntu-otus и перезагружаемся 

![Image alt](https://github.com/NikPuskov/Grub/blob/main/grub5.jpg)
