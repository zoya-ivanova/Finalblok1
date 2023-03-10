## __Итоговая работа по I блоку__
---
### Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
---
### Алгоритм выполнения задания:
1. Создать репозиторий на GitHub.
2. Нарисовать блок-схему алгоритма.
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md).
4. Написать программу, решающую поставленную задачу.
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что все залито одним коммитом, как минимум этапы 2, 3 и 4 должны быть расположены в разных коммитах)
---
### Блок-схема алгоритма:
![блок схема](C:\Users\ThinkPad\Desktop\Учеба\итоговый проект 1\блок-схема.png)
---
### Описание алгоритма решения задачи:
Пользователем задается массив строкой с клавиатуры с количеством n-символов. 
В блок-схеме проходим по заданному массиву в цикле и проверяем, подходит ли первый элемент условию "длина символов 
<= 3". Если элемент подходит под данное условие, то мы добавляем его в новый массив, используя при этом дополнительный счетчик, чтобы элементы в новом массиве заполнялись последовательно. Далее через счетчик проверяем следующий элемент - "длина символов <= 3", когда пройдет весь массив, итогом выводится новый массив с элементами в которых не более 3-х символов.

### Программа, решающая поставленную задачу:
В папке Task решение задачи на C#.
Необходимо запустить программу в терминале командой 
```
dotnet run 
```
Далее введите массив строкой с клавиатуры с количеством n-символов, например: 2 hello sun 33 world,
программа выведет: 2, sun, 33
