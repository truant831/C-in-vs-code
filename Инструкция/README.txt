Понятия:
*корень диска - это папка которая находиться в самом начале диска, т.е. путь до папки будет C:\mingw64
Путь - "C:\test\hey\kek\" - он содержит только английские символы.

Так же для шагов 3, 5 и 7 сделал картинки

ИНСТРУКЦИЯ

1. Распаковываем архив
	1.1 переносим папку mingw64 в корень диска*

2. Переносим папку C++, можно перенести куда угодно (пожалуйста, пусть путь до папки будет содержать только английские символы, иначе ничего не заработает).

3. Открываем проводник
	3.1 нажимаем правой кнопкой мыши на "мой компьютер"
	3.2 нажимаем свойства
	3.3 нажимаем дополнительные свойства системы
	3.4 наживаем переменные среды
	3.5 нажимаем на Path
	3.6 создаём новый путь и вставляем вот этот: "C:\mingw64\bin" (В картинке путь другой, не обращайте внимание, правильный путь тут)
	3.7 нажимаем Окей
!!!К шагу 3 я отдельно сделал картинки!!!

4. Установить Vs code - вот ссылочка: https://code.visualstudio.com/download

5. Устанавливаем расширения
	5.1 нажимаем на шестерёнку
	5.2 нажимаем на profile
	5.3 нажимаем профили
	5.4 нажимаем на стрелочку радом с новый профиль
	5.5 импорт профиля
	5.6 в папке С++ находим С++.code-profile



P.S.
6. Оставил тестовую программу с работой через файлы.

7. Чтоб отрыть в доп окне input и output (их я тоже сделал ~чмок~) нажимаем на окошко сверху.

8. Официальный гайд - https://code.visualstudio.com/docs/cpp/config-mingw