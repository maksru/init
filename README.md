# init
42 Project.
C MSC установить Oracle VM Virtual Box, скачать live дистрибутив с https://cdimage.debian.org/debian-cd/cu ... so-hybrid/ - выбираем, например, debian-live-9.3.0-amd64-cinnamon.iso
Заранее открываем терминал и пишем
cd /tmp
open .
При установке новой виртуальной машины на шаге File location and size - нажмите справа от названия на папку и мышкой перетащите вашу папку tmp, чтобы образ сохранился в темп папку не ограниченную размером.
# Для работы нужно еще утановить openssh-server:
# 1)sudo apt update.
# 2)sudo apt upgrate.
# 3)sudo apt-get install openssh-server.
После работы папку можно скинуть на флешку и носить с собой
