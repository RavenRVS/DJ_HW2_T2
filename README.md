# Пагинация

## Задание <a href="https://github.com/RavenRVS/DJ_HW2_T2/blob/master/stations/views.py">(моё решение)</a>

Реализуйте пагинацию по csv файлу с [портала открытых данных](https://data.mos.ru/datasets/752), содержащего список остановок наземного общественного транспорта.

Для этого необходимо реализовать функцию отображение `stations.views.bus_stations`, формируя контекст, как показано в примере.

Путь к файлу хранится в настройках `settings.BUS_STATION_CSV`.

Для чтения csv файла можете использовать [DictReader](https://docs.python.org/3/library/csv.html#csv.DictReader) и учтите, что файл в кодировке `utf-8`.

![Пример результата](./res/result.png)

## Документация по проекту

Для запуска проекта необходимо:

Установить зависимости:

```bash
pip install -r requirements.txt
```

Выполнить команду:

```bash
python manage.py runserver
```
