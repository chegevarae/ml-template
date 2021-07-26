# Jupyter Notebook файлы

Директория для Jupyter Notebook файлов с целью более удобной визуализации и манипуляции с данными, которые удобнее делать в интерактивном режиме. По сути здесь мы реализуем Baseline наших моделей с целью их дальнейшего переноса в dev-папку и последующей доработки в dev для выкатки в прод - core.  

**Важно! Если проектов несколько, то каждый набор Jupyter Notebook файлов (проект) должен находиться в своей подпапке данной директории и ни в коем случае не использоваться в продакшн. Управление версиями докускается осуществлять через копирование основного файла и присвоение его копии очередного номера версии в формате project_1_baseline_2, при этом в названии файла необходимо избегать пробелов. Управление версиями конкретной baseline модели все же рекомендуется осуществлять через Git - репозиторий.**  