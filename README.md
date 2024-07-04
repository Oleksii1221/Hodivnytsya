Кормушка для тварин з використанням Arduino
Цей проект створений для автоматизації процесу годування тварин. Коли тваринка підходить до кормушки, датчик виявляє її присутність і відкриває заслонку, щоб корм висипався в миску на певний час.

Підключення та налаштування

З'єднання компонентів

Додаткове фото зі схемою з'єднання є в віддільному файлі

Сервопривід: 

Чорний/коричновий провід - GND

Червоний провід - 5V

Оранджевий провід - D11

Датчик відстані HC-SR04:

VCC - 5V

Trig Pin: Пін 10 Arduino.

Echo Pin: Пін 9 Arduino.

GND - GND

Джерело живлення:

Напруга джерела живлення - 5-9V

Для зменшення шумів може бути підключений конденсатор перелельно до живлення(Не обов'язково)

Мінус - GND

Плюс - VCC

Налаштування:

Dystantsiya: Відстань у сантиметрах, коли датчик спрацьовує.

pos0 та pos1: Положення сервопривода (закрито/відкрито).

doza: Час, на який відкривається заслонка.

kd: Перерва між кормленими порціями в секундах.



Інструкції щодо використання

Завантажте код на вашу Arduino.

Підключіть всі необхідні компоненти згідно схеми.

Запустіть Arduino. Він буде готовий до використання.

Посилання на віртуальну схему проекту з можливісту симуляції:
https://www.tinkercad.com/things/3QaXRRv9XuL-swanky-lahdi/editel?sharecode=ecfY98B4SHbGsR7fAVU1DnZwitdccpik92JTuMZohis
