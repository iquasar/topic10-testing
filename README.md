# topic10-testing
Модуль testing-example - примеры тестов, которые разбирали на занятии.  
Модуль homework - домашнее задание  

### Домашнее задание:  
+ Logging
1. В классах StudentPrinter и NumberOfStudentsPrinter дописать методы и добавить логирование (описание нужного функционала и уровня логирования указано в TODO)
2. Настроить логирование (файл конфигурации) так, чтобы в файл лога student.log попадали только логи класса StudentPrinter, при этом должны писаться только логи уровня info и выше (info, warn,error, fatal)
3. Настроить логирование (файл конфигурации) так, чтобы в файл лога numberOfStudent.log попадали только логи класса NumberOfStudentsPrinter, при этом должны писаться только логи уровня info и ниже (info, debug,trace)  
Для 2 и 3 задания изменения в сами классы вносить нельзя

+Testing
Для класса RemoteFileHandler написать тесты для методов handleRequest, handleResponse, handleError. Необходимо проверить все значимые кейсы. Покрытие для методов должно быть 100%
Обратите внимание на другие классы в пакете. Их реальные методы вызываться не должны
