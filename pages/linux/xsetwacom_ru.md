# xsetwacom

> Инструмент командной строки для изменения настроек планшетов Wacom во время выполнения.

- Список всех доступных устройств wacom. Имя устройства находится в первом столбце:

`xsetwacom list`

- Установить область Wacom на конкретный экран. Получить имя экрана с помощью "xrandr":

`xsetwacom set "{{имя устройства}}" MapToOutput {{экран}}`

- Установить режим в относительный (например, мышь) или абсолютный (например, перо) режим:

`xsetwacom set "{{имя устройства}}" Mode "{{Relative|Absolute}}"`

- Поворот при вводе (полезно для планшетного ПК при вращении экрана) на 0 | 90 | 180 | 270 градусов от «естественного» вращения:

`xsetwacom set "{{имя устройства}}" Rotate {{none|half|cw|ccw}}`

- Установить кнопку, чтобы работать, только когда кончик пера касается планшета:
	
`xsetwacom set "{{имя устройства}}" TabletPCButton "on"`
