# Лабораторный практикум по операционным системам

## Структура
Лабораторные работы состоят из:
- требований к итоговой программе
- теоретической справки
- практического задания с разбалловкой

Каждая из 4 лабораторных работ находится в соответствующей папке репозитория. 

## Выполнение лабораторных работ
### Дедлайны:
0. Знакомство с Linux и bash - 30 сентября
1. Демонизация - 26 октября
2. Клиент-серверное приложение - 25 ноября
3. Многопоточные структуры данных - 21 декабря

### Процедура сдачи работы
1. Ознакомится с заданием, выбрать вариант. Сообщить выбранный вариант преподавателю. Это можно делать только если все 
предыдущие лабораторные успешно сданы.
2. Лабораторные работы делаются в вашем fork репозитории этого репозитория.
   Файлы для каждой работы должны находится в подпапке каталога <Фамилия>.<Имя> с названием lab№, где № - номер работы
   ``` 
   Operating-Systems-Labs
   |     README.md
   |____ 0. Знакомство с linux и bash
   |____ 1. Процессы, демонизация
   |____ 2. Межпроцессное взаимодействие
   |____ 3. Многопоточные структуры данных
   |____ Ivanov.Ivan
   |     |____ lab1
   |     |     | ...*sources*
   |     |    
   |     |____ lab2
   |     |     | ...*sources*
   |     |    
   |     |____ lab3
   |     |     | ...*sources*
   ```
3. Для того, чтобы сдать задачу, необходимо создать pull request. Целевой веткой нужно указать ветку develop.
   Задача будет зачтена, если она отвечает следующим требованиям
    * Разумный стиль кодирования.
    * Задача собирается без ошибок методом, который указан в тексте задания, и корректно работает на всех тестах
    * В случае незначительных недочетов или спорных ситуаций преподаватель может задать вопросы в комментариях к pull request
4. Если pull request смержен - задача считается сданной, преподаватель выставляет оценку согласно сложности задачи и 
полноты её реализации
    * Если задача сдана после дедлайна, то снимаются баллы от одного до половины
    * Если задача реализована не полностью, то она оценивается по объему выполенной части

### Соотношение баллов с оценкой за дифференцированный зачет:
- 3: 17 баллов
- 4: 21 баллов
- 5: 24 балла
## Список литературы
- Душутина Е.В. Системное программное обеспечение. Практические вопросы разработки системных приложений: учебное пособие
- Шмаков В.Э. Организация межпроцессных взаимодействий в OC UNIX: методические указания
- Душутина Е.В. Межпроцессные взаимодействия в операционных системах: учебное пособие
