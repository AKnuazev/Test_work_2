# Test work 2
Тема:   Рубежный контроль номер 2 по предмету "Технологии и методы программирования"

Автор:  Князев Антон 

Группа: ИУ8-23

# Отчет

## Тип данных: Список
### Имя проекта: 
StarPlanner 
### Ссылки: 
На проект: https://github.com/pekalicious/StarPlanner

На файл с кодом: https://github.com/pekalicious/StarPlanner/blob/96fb19d72c7bc1264cb98d03f725ee0be428b654/swig-utils/etc/cpp/SwigUtils/TestCpp.cpp

### Номера строк с функциями АТД:
Вставка элементов:  14

Удаление элементов: 36 

Очистка списка:     49

### Описание использования данного АТД
  В данном проекте список list используется в качестве временного хранилища для некоторых случайных (тестовых) значений, на примере которого провекряется корректность работы программы (специальных типов данных и соответствующих функций). 
  
  Выбран именно этот тип данных, так как основная работы программы также заключается в работе с list, и, следовательно, тестирование следует проводить именно с использование объекта того же типа.



## Тип данных: Очередь
### Имя проекта: 
shared-queue
### Ссылки: 
На проект: https://github.com/Hazurl/shared-queue

На файл с кодом: https://github.com/Hazurl/shared-queue/blob/ce9f56b45939a51e83ce1d93a04db2ff28a2a90e/src/main2.cpp

### Номера строк с функциями АТД:
Вставка элементов:   69

Удаление элементов:  74

Получение элементов: 170

### Описание использования данного АТД
  В данном проекте очередь queue используется как база для создания усовершенствованной версии очереди - Multithreaded Queue (многопоточная очередь). В конкретном рассмотренном участке кода выполняется исследование работы программы при некоторых фиксированных значениях. 
  
  Данный тип данных выбран, поскольку основной целью данной программы является усовершенствование самого этого типа данных, и, следоваительно, для этого требуется все методы, уже реализованные для базового класса.  
  
  
  
  ## Тип данных: Дерево
### Имя проекта: 
treelib
### Ссылки: 
На проект: https://github.com/caesar0301/treelib

На файл с кодом: https://github.com/caesar0301/treelib/blob/master/examples/family_tree.py#L54

### Номера строк с функциями АТД:
Получение корня:         38

Получение значения узла: 43

Объединение деревьев:    50

Удаление узла:           54

### Описание использования данного АТД
  В данном проекте деревом tree задается некоторая семья с заранее заданными членами (где узлам и ребрам соответствуют члены семьи и родственные связи между ними). Она служит для иллюстрации работы программы на конкретном примере.
  
  Данный тип данных выбран, поскольку структура данных tree идейно абсолютно идентична структуре семейного древа, для которого как раз данный тип и выбран. 
  
  
  
  ## Тип данных: Множество
### Имя проекта: 
green-candy
### Ссылки: 
На проект: https://github.com/qaisjp/green-candy

На файл с кодом: https://github.com/qaisjp/green-candy/blob/807e79bac9296225ab3c162b713f2461c1542e46/MTA10/core/CCompressorJobQueue.cpp

### Номера строк с функциями АТД:
Добавление элемента:        239

Удаление элемента:          182

Определение принадлежности: 186

### Описание использования данного АТД
  В данном проекте множество set выполняет функцию контейнера, содержащего полученные в результате работы потоков значений.
  
  Данный тип данных выбран, поскольку он реализует все необходимые для контецнера подобного рода функции, и при этом не содержит лишних.

