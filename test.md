# **Работа с удаленными репозиториями**

создаю конфликт


* git pull - эта команда __скачать__ все из текущего репозитория и автоматически 
сделать __merge__ с нашей версией 

* git push - эта команда позволяет __отправить__ нашу версию репозитория на внешний репозиторий, __ТРЕБУЕТ АВТОРИЗАЦИИ__ на внешнем репозитории 

## Как сделать pull request
● Делаем __fork__ репозитория   
● Делаем clone СВОЕЙ версии репозитория   
● Создаем новую ветку и в НЕЕ вносим свои изменения   
● Фиксируем изменения (делаем коммиты)   
● Отправляем свою версию в свой GitHub   
● На сайте GitHub нажимаем кнопку pull request  

# **Основные команды Git**  

## 1. Создать пустой репозиторий в Git.Появляется скрытая папка с Git-ом:  
>  git init  
  
## 2. Получить информацию от git о его текущем состоянии:  
>  git status

## 3. Добавить файл или файлы к следующему коммиту:  
>  git add . name.expansion

## 4. Создать коммит:  
> git commit -m “message” 

## 5. Вывод на экран истории всех коммитов с их хеш-кодами:  
>  git log

## 6. Переход от одного коммита к другому:  
>  git checkout

## 7.  Вернуться к актуальному состоянию и продолжить работу:  
>  git checkout master

## 8.  Увидеть разницу между текущим файлом и закоммиченным файлом:  
>  git diff

## 9.  Вывести список веток в репозитории:  
>  git branch 

## 10.  Создать новую ветку с именем name:  
>  git branch name

## 10.  Удалить ветку с именем name:  
>  git branch -d name

## 11.  Переходить на ветку name:  
>  git checkout name

## 12.  Выводить список коммитов в виде красивого графа/дерева   
>  git log –graph 

## 13.  Слить ветку name с текущей веткой   
>  git merge name

# **Инструкция для работы с языком Markdown**  

# **Синтаксис языка Markdown**  

## 1. Выделение заголовков. 
### Первый способ - количество символов “#” задаёт уровень заголовка (поддерживается 6 уровней):  

 * # Заголовок  - первый уровень обозначается "#"  
 * ## Заголовок  - второй уровень обозначается "##"    
 * ### Заголовок  - третий уровень обозначается "###"    
 * #### Заголовок  - четвёртый уровень обозначается "####"       
 * ##### Заголовок  - пятый уровень обозначается "#####"     
 * ###### Заголовок  - шестой уровень обозначается "#######" 

### Второй способ - выделение заголовков первого и второго уровней соответственно можно с помощью символов (не менее 3 подряд).


## 2. Выделение текста.

> Чтобы выделить текст курсивом, необходимо обрамить его (*) или знаком нижнего подчеркивания (_).  

Например: *Привет*  или _Привет_  

> Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания (__).  

Например: **Привет** или __Привет__

> Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба эти способа.  

Например: _текст может быть выделен курсивом и при этом может быть **полужирным**_ или ***Полужирное курсивное начертание***

> Чтобы сделать текст зачеркнутым, необходимо обрамить его (~~).  
Например: ~~Зачеркнутый текст~~


## 3. Списки   
Чтобы добавить не нумерованные списки , необходимо пункты выделить звёздочкой (*) или знаком (+)
Например:  
* Элемент 1  
* Элемент 2
* Элемент 3
+ Элемент 4
+ Элемент 5
+ Элемент 6


Чтобы добавить нумерованные списки , необходимо пункты просто пронумеровать
Например:  
1. Элемент 1  
2. Элемент 2
3. Элемент 3

## 4. Работа с изображениями 

Привет  
Привет  
Привет  
Привет  
Привет  
Привет  
Привет  
Привет  
Хочу вызвать ошибку при слиянии веток  
Хочу вызвать ошибку при слиянии веток
Хочу вызвать ошибку при слиянии веток  
Хочу вызвать ошибку при слиянии веток  
Хочу вызвать ошибку при слиянии веток  
Хочу вызвать ошибку при слиянии веток  


>Чтобы вставить изображение в текст, достаточно написать следующее:  
1. ![hi, NG_fotoshop](NG_fotoshop.jpg)  
2. ![hi, NG_2](NG_2.jpg)  
>Если добавить изображение с обшибкой в название изображения, получим следующее:  
![hi, NG_fotoshop_fatal](NG_fotosho.jpg)   

## Ссылки  
Все ссылки должны быть безопасными (с протоколом https вместо http), ссылки обрамляются квадратными скобками [].  
Например: Хотите узнать больше про разметку языка Markdown перейдите по следующей ссылке - [https://www.google.com/url?q=https://docs.microsoft.com/ru-ru/contribute/markdown-reference&sa=D&source=editors&ust=1658662385023542&usg=AOvVaw3518E5g-RRY5_nHBRNs8L3]  

## Работа с таблицами    
 Чтобы создать стандартную таблицу с заголовком, вставьте пунктирную линию после первой строки.  Для разделения столбцов таблицы используют вертикальную черту |. Выравнивание задаётся двоеточием. 

> Таблица №2

 | Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 4 is      | right-aligned | $1600 |
| col  is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |  
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии
Привет, хочу слить две ветки и получить ошибку при слиянии




> Таблица №5
  
strong | beautiful | beloved
--- | --- | ---
*мама* | `папа` | **дочь**
300 | 300 | 400000000000000
 

