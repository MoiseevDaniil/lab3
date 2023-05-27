### 2.8 Огляд етапів побудови С-програми GNU-компілятором GCC

![image](https://github.com/oleksandrblazhko/ai222-sivizina/assets/127392659/5725ff7b-3a90-48e9-98aa-856451d01393)

2.8.1 Виконати prepocessing-етап для вказаного файлу, зберігши результат у файлі
«назва таблиці.i»

![image](https://github.com/oleksandrblazhko/ai222-sivizina/assets/127392659/97fc9d4b-4b1a-4349-92f3-fd4515e694e1)

2.8.2 Виконати compilation-етап для файлу «назва таблиці.i», зберігши результат у
файлі «назва таблиці.s»

![image](https://github.com/oleksandrblazhko/ai222-sivizina/assets/127392659/9dd83535-4ee8-4210-8317-793ed35013f9)

![image](https://github.com/oleksandrblazhko/ai222-sivizina/assets/127392659/7e293c40-75df-449e-89e4-60ee9fb5a3c5)

2.8.3 Повторити compilation-етап для файлу «назва таблиці.i» з оптимізацію
програмного коду, зберігши результат у файлі «назва таблиці_opt.s», та визначити відсоток
зменшення кількості рядків після оптимізації.

Кількість рядків зменшилася на невеликий відсоток

![image](https://github.com/oleksandrblazhko/ai222-sivizina/assets/127392659/d31c2763-896d-44f8-9d4c-e9a9c5564610)

2.8.4 Виконати assembly-етап для файлу «назва таблиці.i», зберігши результат у
файлі «назва таблиці.o»

![image](https://github.com/oleksandrblazhko/ai222-sivizina/assets/127392659/7abfc7e6-85ba-4cba-a8b3-9f0e63e60264)

2.8.5 Визначити командний рядок виконання linking-етапу для файлу «назва
таблиці.o» та зберегти результат у файл-скрипті ld.sh

![image](https://github.com/oleksandrblazhko/ai222-sivizina/assets/127392659/220a9a93-cf90-4ca8-889d-998464a79e19)

2.8.6 Виконати linking-етап через виконання створеного раніше файл-скрипту ld.sh.

![image](https://github.com/oleksandrblazhko/ai222-sivizina/assets/127392659/5a072eca-f0ad-4482-b9fd-18e4e4cb2352)

2.8.7 Переглянути список файлів динамічних бібліотек, пов’язаних зі створеним
executable-файлом.
