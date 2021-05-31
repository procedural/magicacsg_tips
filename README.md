[[Same tips in English]](https://github.com/procedural/magicacsg_tips/blob/main/README_EN.md)

* #MagicaCSG v0.0.0 подсказки: поскольку ещё нет возможности выбрать элементы нескольких слоёв, предпочитайте держать элементы симметричного объекта на одном слое. Таким образом будет легче удалить одну половину объекта, переместить или повернуть другую половину, и воссоздать удаленную половину с помощью трюка с отражением. 

* #MagicaCSG v0.0.0:
```
Масштаб X: Куб --- 2 -- 2   --- 2     --- 2     --- X1 --- 447.5  --- 447.5
Масштаб Y: Куб --- 2 -- 2   --- 2     --- 893   --- X1 --- 893    --- 893
Масштаб Z: Куб --- 2 -- 2   --- 893   --- 893   --- X1 --- 893    --- 893

Позиция X: Куб --- 1 -- 1   --- 1     --- 1     --- X1 --- 223.75 --- 222.5
Позиция Y: Куб --- 0 -- 0   --- 0     --- 0     --- X1 --- 0      --- 0
Позиция Z: Куб --- 2 -- 893 --- 447.5 --- 447.5 --- X1 --- 447.5  --- 447.5
```

* #MagicaCSG v0.0.0 подсказки: символ " в именах слоёв запрещён.

* #MagicaCSG v0.0.0 подсказки: на данный момент, MagicaCSG не может экспортировать или импортировать текущую позицию и ориентацию камеры, поэтому в качестве обходного пути вы можете создать крошечную сферу на новом слое и сфокусировать камеру на неё нажав клавишу 5 на клавиатуре. Перезапустите сцену, выделете эту сферу и нажмите клавишу 5 снова, чтобы вернуть камеру на эту позицию.

* #MagicaCSG v0.0.0 подсказки: в настоящее время, MagicaCSG не может экспортировать и импортировать все настройки сцены, поэтому делайте снимки окна (Ctrl + 6) всех настроек сцены, чтобы ввести их все обратно позже.
