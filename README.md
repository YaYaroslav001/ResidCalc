Данный скрипт строит графики случайных составляющих для нескольких точек наблюдения, выводит результат декомпозиции в файл, строит матрицу корреляции и группирует метеостанции.

Для запуска скрипта необходимы библиотеки pandas, numpy, matplotlib, seaborn, scipy и statsmodels.

Данные по температуре и осадкам берутся с помощью обновленной технологии веб-доступа АИСОРИ-М с сайта aisori-m.meteo. Датасет должен содержать все столбцы (индекс ВМО, год, месяц, день, общий признак качества температур, минимальная температура воздуха, средняя температура воздуха, максимальная температура вохдуха, количество осадков) и точку с запятой в качестве разделителя.

Перед запуском скрипта его необходимо переместить в папку с метеоданными. В командной строке необходимо перейти по пути, где лежит скрипт, с помощью команды cd. После этого запустить скрипт. Названия файлов с данными вводятся после запуска скрипта. После завершения работы скрипта, весь результат сохраняется в папке Result.