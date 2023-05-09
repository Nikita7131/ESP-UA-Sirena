# ESP-UA-Sirena

Плата управління сиреною повітряної тривоги по всій території України. Дані беруться звідси : https://alerts.com.ua/

Плата автоматично оновлюється на нові версії прошивки по wifi, тому якщо щось не робе пишіть сюди : https://t.me/Nikita7131 

Підтримати проект да і самого автора можна тут: 5168755910184213 Приват24


 Більш детально в цьому відео : https://www.youtube.com/watch?v=_4etPlHOewc
 

 ![alt tag](https://github.com/Nikita7131/ESP-UA-Sirena/blob/main/Schematic/Photo_WebServer.jpg "Опису не буде")​
 
  ![alt tag](https://github.com/Nikita7131/ESP-UA-Sirena/blob/main/Schematic/photo_2023-03-10_22-36-15%20%E2%80%93%20%D0%BA%D0%BE%D0%BF%D1%96%D1%8F.jpg "Опису не буде")​
 
 Ось тут під кінець, налаштування часу розгону і зупинки мотора можна виставити в діапазоні (0-98сек), кількість повторів, тобто скільки
часу звучатиме звук початку повітряної тривоги. І самий останній пункт, це час за який при відбої повітряної тривоги сирена буде звучати постійно.
Із додатково функціоналу при бажанні можна в обох полях час розгону і зупинки виставити значення 99, в такому випадку при повітряній тривозі сигнал
на виході буде постійно високим, наприклад в такому випадку можна підключити світлодіодну стрічку і можна зробити яке-небуть табло.


 ![alt tag](https://github.com/Nikita7131/ESP-UA-Sirena/blob/main/Schematic/Schematic_sirena_ESP-UA_Sirena.png "Опису не буде")​
 
 ![alt tag](https://github.com/Nikita7131/ESP-UA-Sirena/blob/main/Schematic/Photo_PCB.png "Опису не буде")​
 
 ![alt tag](https://github.com/Nikita7131/ESP-UA-Sirena/blob/main/Schematic/%D0%A1omponents%20Foto.png "Опису не буде")​
 
 
 правила користування : https://github.com/Nikita7131/ESP-UA-Sirena/blob/main/ReadMe%20Terms%20of%20use%20of%20the%20device.txt
 Якщо Ви використовуєте цей прилад, ви автоматично погоджуєтесь з встановленими Правилами і приймаєте всю відповідальність, яка може бути на Вас покладена.
 
| версії  | нововедення |
| ------------- | ------------- |
| V1.1  | тест автоматичних оновлень по wi-fi |
| V1.3  | добавлений таймер для для підключення моторів сирен  напряму до плати + добавлений сигнал відбою повітряної тривоги ( ці сигнали виведені на окрему ніжку мікрокотроллера  ( IO27)  )  |
| V1.5 | добавлена можливість увікнути тайм аут з 23:00 - 7:00 |
| v2.0 | доданий в схему DFplayer |
| v2.3 | тепер можна налаштувати гучність DFplayer + при запуску веб сервера (налаштувань) індикатор wi-fi моргає кожні 200млс |
| v2.5 | 33 GPIO ручний запуск, 32 GPIO ручний відбій повітряної тривоги  ( ставиш кнопку , треба замикати на мінус ) |


P.S. є ще проміжні версії в який я в основному виправляю баги, то там нічого цікавого.
