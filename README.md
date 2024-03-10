Sevryukov Stepan 253504  
Программное средство организации личного каталога книг  
Данная программа предоставляет возможность выбирать в библиотеке понравившуюся книгу, добавлять ее к себе в избранное и читать, с возможностью пометки ключевых моментов.

==Library  
=FilterBooks - Отфильтровать книги по критерию (жанр, год, автор, издание)  
=FindBooks - Поиск книги (поиск по назв книги, автору, году издания, по изданию)  
=AddToFavBook - Добавить книгу в избранные  

==User  
=ViewFavBooks - Просмотр избранных книг  
=ChangeUsrname - Изменить имя пользователя  
=ChangePass - Изменить пароль  
=RemoveFromFavBook - Удалить книгу из избранных

==Book  
=OpenBook - Открыть книгу (просмотр информации о книге)  
=ReadBook - Чтение книги  
=RemoveBook - Удалить книгу из приложения   

==Bookmark  
=MakeBookmark - Создать закладку (внутри книги)  
=DeleteBookmark - Удалить закладку  
=EditBookmark - Редактировать существующую закладку
##==================================================================================Диаграмма классов приложения==========================================================================================
![ООП drawio (1)](https://github.com/auumeiss/OOP_KURS/assets/159965679/103582cf-048f-435c-b079-2fae5c59c166)




##==================================================================================Схема работы приложения==========================================================================================
![image](https://github.com/auumeiss/OOP_KURS/assets/159965679/a6ab9411-ab3a-41e7-926c-c9582cad6d9b)

Удобный инструмент для организации личного каталога книг, который позволяет пользователям выбирать книги из библиотеки, добавлять их в избранное и читать, с возможностью добавления пометок к ключевым моментам.

==Авторизация и регистрация:  
=Пользователи имеют возможность зарегистрироваться и авторизоваться в системе.

==Поиск и выбор книг:  
=Пользователи могут осуществлять поиск книг в базе данных по различным критериям (название, автор, жанр и т.д.).  
=Пользователи могут просматривать информацию о книгах.  
=Возможность добавлять книгу к себе в личный кабинет.

==Личный кабинет:   
=Каждый пользователь имеет личный кабинет, где отображаются добавленные им книги.  
=Пользователь может отмечать книги, которые он уже прочитал.  
=Пользователь может добавлять пометки к ключевым моментам в прочитанных книгах.  

==Чтение книг:  
=Пользователи могут читать книги онлайн внутри приложения.  
=Добавление закладки во время прочтения книги.

==Управление закладками:  
=Добавление закладки.  
=Удаление закладки.  
=Редактирование закладки.


==Язык программирования : .NET MAUI  
==Данные будут храниться в базе данных на Firebase.

