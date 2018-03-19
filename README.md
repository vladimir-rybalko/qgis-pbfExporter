# qgis-pbfExporter

Плагин для Qgis 3, который позволяет сохранять слои карты в osm файлы. Сохранение в osm формат выполняется через ogr2osm [A tool for converting ogr-readable files like shapefiles into .osm data](https://github.com/pnorman/ogr2osm)

## Установка

Для установки необходимо клонировать репозиторий плагина в папку с плагинами Qgis. Для Windows это путь **C:\Users\<UserNAme>\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins**

## Подключение

Для подключения плагина необходимо в менеджере плагинов отметить **Pbf Extractor**.
![Подключение плагина](https://image.ibb.co/cwXcFH/screen1.png)

## Использование

Чтобы выгрузить данные в формате osm необходимо выбрать нужный слой с данными и нажать на кнопку *pbf extracter*. В открывшемся окне, необходимо указать место и имя файла без расширения. В результате работы плагина формируется osm файл в указанной директории. 
