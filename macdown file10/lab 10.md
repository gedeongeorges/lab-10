## РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ
## Факультет физико-математических и естественных наук 
### Кафедра прикладной информатики и теории вероятностей

### ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ № 10

*дисциплина: Операционные системы*

**Студент: ГЕОРГЕС Гедеон** 
**Группа: НПМбд-02-20**

МОСКВА 2021 г.

# Цель работы :
познакомиться с операционной системой Linux, получить практические навыки работы с редактором Emacs.
# Ход работы:
1. Открыла emacs.
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2003.png)
(Рисунок 1)
2. Создала файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2002.png)
(Рисунок 2)
3. Набрала текст:
  #!/bin/bash
HELL=Hello
function hello {
LOCAL HELLO=World
echo $HELLO
}
echo HELLO
hello
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2004.png)
(Рисунок 3)
4. Сохранила файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2005.png)
(Рисунок 4)
5. Проделала с текстом стандартные процедуры редактирования, каждое действие осуществлялось комбинацией клавиш.
5. 1. Вырезала одной командой целую строку (С-k).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2006.png)
(Рисунок 5)
5. 2. Вставила эту строку в конец файла (C-y).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2007.png)
(Рисунок 6)
5. 3. Выделила область текста (C-space).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2005.png)
(Рисунок 7)
5. 4. Скопировала область в буфер обмена (M-w).
5. 5. Вставила область в конец файла.
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2006.png)
(Рисунок 8)
5. 6. Вновь выделила эту область и на этот раз вырезала её (C-w).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2009.png)
(Рисунок 9)
5. 7. Отменила последнее действие (C-/).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2008.png)
(Рисунок 10)
6. Научилась использовать команды по перемещению курсора.
6. 1. Переместила курсор в начало строки (C-a).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2008.png)
(Рисунок 11)
6. 2. Переместила курсор в конец строки (C-e).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2008.png)
(Рисунок 12)
6. 3. Переместила курсор в начало буфера (M-<).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2009.png)
(Рисунок 13)
6. 4. Переместила курсор в конец буфера (M->).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2008.png)
(Рисунок 14)
7. Управление буферами.
7. 1. Вывела список активных буферов на экран (C-x C-b).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2010.png)
(Рисунок 15)
7. 2. Переместилась во вновь открытое окно (C-x) o со списком открытых буферов и переключилась на другой буфер.
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2011.png)
(Рисунок 16)
7. 3. Закрыла это окно (C-x 0).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2012.png)
(Рисунок 17)
7. 4. Вновь переключилась между буферами, но без вывода их списка на экран (C-x b).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2013.png)
(Рисунок 18)
8. Управление окнами.
8. 1. Поделила фрейм на 4 части: разделила фрейм на два окна по вертикали (C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2).
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2014.png)
(Рисунок 19)
8. 2. В каждом из четырёх созданных окон открыла новый буфер (файл) и ввела несколько строк текста.
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2015.png)
(Рисунок 20)
9. Режим поиска
9. 1. Переключилась в режим поиска (C-s) и нашла несколько слов, присутствующих в тексте.
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2016.png)
(Рисунок 21)
9. 2. Переключалась между результатами поиска, нажимая C-s.
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2017.png)
(Рисунок 22)
9. 3. Вышла из режима поиска, нажав C-g
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2018.png)
(Рисунок 23)
9. 4. Перешла в режим поиска и замены (M-%), ввела текст, который следует найти и заменить, нажала Enter , затем ввела текст для замены. После того как были подсвечены результаты поиска, нажала ! для подтверждения замены.
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2019.png)
(Рисунок 24)
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2020.png)
(Рисунок 25)
9. 5. Испробовала другой режим поиска, нажав M-s o. Он отличается от обычного режима тем, что при поиске указывает номера строк в которых найдено введённое слово и выделяет их цветом. В обычном режиме выделение цветом появляется, только когда нужно подтвердить замену.
![](https://raw.githubusercontent.com/gedeongeorges/lab-10/main/pictures%2010/lab10%2021.png)
(Рисунок 26)
# Вывод:
познакомилась с операционной системой Linux, получила практические навыки работы с редактором Emacs.
### Ответы на контрольные вопросы:
1. Emacs представляет собой мощный экранный редактор текста, написанный на
языке высокого уровня Elisp.
2. Развитие Emacs в сторону его многогранности послужило причиной того, что и без того интуитивно непонятная программа стала чрезвычайно сложной в применении. В частности, управление осуществляется при помощи различных клавиатурных комбинаций, запомнить которые будет непросто.
3. Буфер – что-то, состоящее из текста. 
Окно – область с одним из буферов.
4. В одном окне можно открыть больше 10 буферов.
5. После запуска emacs без каких-либо параметров в основном окне отображается буфер *scratch*, который используется для оценки выражений Emacs Lisp, а также для заметок, которые вы не хотите сохранять. Этот буфер не сохраняется автоматически.
6. Чтобы ввести следующую комбинацию C-c | я нажму клавиши: Control+c и Shift+\, и для C-c C-|: Control+c и Control+Shift+\.
7. Поделить текущее окно на две части можно двумя комбинациями клавиш: 
C-x 3 или C-x 2.
8. Настроить или расширить Emacs можно написав или изменив файл ~/.emacs.
9. Клавиша  выполняет функцию перемещения курсора в открытом окне также, как и многие другие клавиши её можно переназначить.
10. Редактор emacs показался мне удобнее из-за возможности открытия нескольких окон с буферами и работать комбинациями клавиш в этот редакторе мне было проще.
