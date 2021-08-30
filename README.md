## Homework1
 1. Настроить Git репозиторий и добавить преподавателя (с ролью чтение + запись)
2. В репозитории создать проект с названием Homework1 (последнующие проекты будут называтьсяя подобным образом)
3. В проекте реализовать:
   
   3.1. Сервис, реализующий интерфейс. В интерфейсе должен быть метод, который принимает какие-либо значения (минимум 2 аргумента) и возвращает значение.
    
    3.2. Юнит тесты (MS Test, nUnit, xUnit зависит от Вас), которые:
        
        3.2.1. Производят проверку метода (несколько вариаций входных параметров)
        
        3.2.2. Отдельный юнит тест с использованием библиотеки Moq ("замокать" сервис и использовать callback для сохранения переданных значений). Сделать проверку, совпадают ли значения из callback с передаваемыми значениями
        
        3.2.3. Отдельный юнит тест с примером использования библиотеки Bogus
## Homework2
1. Создать .Net Core MVC Web Application (Model-View-Controller)
2. В действии (action) Index добавить во ViewBag поле Message с текстовым значением "Hello world!"
3. Добавить юнит тесты для проверки контроллера (действие Index):
   
   3.1. Проверить, чтобы тип результата выполнения был ожидаемым.
    
    3.2. Проверить, чтобы ViewBag представления имел поле Message с ожидаемым значением.
