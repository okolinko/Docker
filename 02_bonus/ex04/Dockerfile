#Talking cow

FROM debian

RUN apt-get update && apt-get install -y cowsay fortune lolcat

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay | /usr/games/lolcat

# docker build -t bex04app .

# docker run --rm -t bex04app

#fortune: fortune - это программа, которая отображает псевдослучайное сообщение из базы данных котировок, которая впервые появилась в версии 7 Unix.
#cowsay: cowsay - это программа, которая генерирует изображения ASCII коровы с сообщением.
#lolcat создает радугу цветов в терминале.
#Flag -t важно в команде докеров. Без этого флага корова не получит цвета.