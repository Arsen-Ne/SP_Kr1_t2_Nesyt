# SP_Kr1_t2_Nesyt


## Сценарий командной строки

Этот сценарий командной строки написан на языке Bash и предназначен для выполнения различных операций в зависимости от переданных аргументов.

## Описание

Сценарий принимает два аргумента: 

тип (folder или file) и путь к папке или файлу. В зависимости от указанного типа, сценарий выполняет различные действия.

- Если тип равен folder, сценарий выводит список файлов в указанной папке в длинном формате, исключая первые две строки (текущий каталог и родительский каталог). Также выводится общее количество файлов.
- Если тип равен file, сценарий выполняет замену заданного слова, удаляет пятую строку в файле и выводит измененный файл на стандартный вывод.
## Использование

- Склонируйте репозиторий с сценарием командной строки:
```
git clone <URL репозитория>
```
- Перейдите в каталог с репозиторием:
```
cd <название репозитория>
```
- Дайте права на выполнение сценарию:
```
chmod +x myscript
```
- Запустите сценарий, указав тип (folder или file) и путь к папке или файлу:
```
./myscript <тип> <путь>
```
- где <тип> может быть folder или file, а <путь> - путь к папке или файлу.

### Примеры запуска:

Вывести список файлов в папке:
```
./myscript folder /path/to/folder
```
Выполнить замену слова в файле:
```
./myscript file /path/to/file.txt
```
