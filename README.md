# Calculator-windowsforms

<img src = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/1.png?raw=true" alt = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/1.png?raw=true">
Сalculator windows forms.
<br>
Калькулятор используется для вычисления арифметических операций, таких как сложение, вычитание, умножение и деление. Добавлена кнопка +/- и удалена кнопка "," т.к. заказчик изменил требования и он не будет работать с дробными числами.
<br>
Для удобства заказчику нужна кнопка для изменения отрицательности числа (+/-).
<br>
После запуска калькулятора, вы можете вводить числа, менять их знак. После ввода первого числа выражения, нажмите кнопку нужного вам знака +,-,x,/ Если был выбран не тот знак, просто нажмите на другой.
<br>
<img src = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/2.png?raw=true" alt = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/2.png?raw=true">
<br>
Введите второе число. Затем для завершения вычисления кнопку =, либо продолжите используя занака +,-,x,/.
<br>
<img src = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/3.png?raw=true" alt = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/3.png?raw=true">
<br>
После нажатия кнопки = результат выведется в поле.
<br>
Если вы нажали не кнопку = , а кнопку знака, то новые вычисления начнутся автоматически, первым числом будет число после вычисления, второе число введите в поле и нажмите равно или кнопку знака +,-,х,/ и так далее.
<br>
Если вам нужно сбросить все вычисления нажмите кнопку С.
<img src = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/4.png?raw=true" alt = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/4.png?raw=true">
<br>
Для изменения знака перед числом используйте кнопку +/-.
<img src = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/5.png?raw=true" alt = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/5.png?raw=true">
<br>
<br>
Описание классов и методов:
<br>
В проекте используются два класса: Util - для вычисления, Form1 - для создания графического интерфейса. Также в проекте присутствует класс для Unit тестов.
<br>
Все методы для вычисления собраны в классе Util:
<br>
Метод formload используется для кнопки сброса. Также используется при запуске калькулятора.
<br>
Метод Sign используется для кнопок знаков (+,-,х,/). Происходит выбор знака для вычисления.
<br>
Метод Number используется для введения чисел. Для кнопок от 0 до 9.
<br>
Метод Ask используется для вызова метода для ответа. Для кнопки =.
<br>
Метод Num используется для конвертации строк в числа.
<br>
Метод Askmet используется для вывода ответа в поле в методе Ask.
<br>
Метод Calculate используется для вычисления ответа.
<br>
Метод PlusMinus используется для изменения знака перед числом. Для кнопки +/-. 
<br>
В классе Form1 собраны все кнопки используемые в калькуляторе. 
<br>
Юнит тесты представлены на картинке
<img src = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/6.png?raw=true" alt = "https://github.com/ArtemmSukach/Calculator-windowsforms/blob/master/6.png?raw=true">
