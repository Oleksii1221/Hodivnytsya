Годівниця для домашніх улюбленців з використанням Arduino
Цей проект створений для автоматизації процесу годування тварин. Коли тваринка підходить до годівниці, датчик виявляє її присутність і відкриває заслонку, щоб корм висипався в миску на певний час.

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

В даному проекті є два файли з кодом на вибір(В двох файлах код індентичний): Hodivnytsya.txt та Hodivnytsya.ino

Hodivnytsya.ino це файл який одразу можна використовувати для Arduino IDE.

Hodivnytsya.txt це ткстовий файл який містить в собі виключно код який потрібно перенести в ваше середовище програмування.

Посилання на віртуальну схему проекту з можливісту симуляції:

https://www.tinkercad.com/things/3QaXRRv9XuL-swanky-lahdi/editel?sharecode=ecfY98B4SHbGsR7fAVU1DnZwitdccpik92JTuMZohis


English version


Feeder for Pets Using Arduino This project is designed to automate the feeding process for pets. When the pet approaches the feeder, a sensor detects its presence and opens the flap to dispense food into the bowl for a certain amount of time.

Connections and Setup

Component Connections

An additional photo with the connection diagram is in a separate file

Servo:

Black/Brown wire - GND

Red wire - 5V

Orange wire - D11

Distance Sensor HC-SR04:

VCC - 5V

Trig Pin: Pin 10 Arduino

Echo Pin: Pin 9 Arduino

GND - GND

Power Source:

Power source voltage - 5-9V

To reduce noise, a capacitor can be connected parallel to the power supply (optional)

Minus - GND

Plus - VCC

Setup:

Distance: Distance in centimeters when the sensor triggers.

pos0 and pos1: Servo position (closed/open).

doza: Time for which the flap opens.

kd: Interval between feeding portions in seconds.

Usage Instructions

Upload the code to your Arduino.

Connect all necessary components according to the diagram.

Start Arduino. It will be ready to use.

In this project, there are two files with the code to choose from (the code in both files is identical): Hodivnytsya.txt and Hodivnytsya.ino

Hodivnytsya.ino is a file that can be directly used for Arduino IDE.

Hodivnytsya.txt is a text file that contains only the code that needs to be transferred to your programming environment.

Link to the virtual project scheme with simulation capability:

https://www.tinkercad.com/things/3QaXRRv9XuL-swanky-lahdi/editel?sharecode=ecfY98B4SHbGsR7fAVU1DnZwitdccpik92JTuMZohis

