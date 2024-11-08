# ArUco-маркеры

> **Note** Документация для версий [образа](image.md), начиная с версии **0.16**. Для более ранних версий см. [документацию для версии **0.15.1**](https://github.com/CopterExpress/drone/blob/v0.15.1/docs/ru/aruco.md).

[ArUco-маркеры](https://docs.opencv.org/3.2.0/d5/dae/tutorial_aruco_detection.html) — это популярная технология для позиционирования
робототехнических систем с использованием компьютерного зрения.

![ArUco-маркеры](../assets/markers.jpg)

> **Hint** При печати визуальных маркеров необходимо использовать максимально матовую бумагу. Глянцевая бумага будет бликовать на свету, сильно ухудшая качество распознавания.

Для быстрого генерирования маркеров для печати можно использовать онлайн-инструмент: http://chev.me/arucogen/.

На [образе Клевера для RPi](image.md) предустановлен пакет `aruco_pose`, предназначенный для работы с ArUco-маркерами.

## Режимы работы

Клевер имеет несколько преднастроенных режимов работы с ArUco-маркерами:

* [распознавание и навигация по отдельным маркерам](aruco_marker.md);
* [распознавание и навигация по картам маркеров](aruco_map.md).

> **Info** Исчерпывающую документацию по пакету `aruco_pose` на английском языке можно посмотреть [на GitHub](https://github.com/CopterExpress/drone/blob/master/aruco_pose/README.md).
