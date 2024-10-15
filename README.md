# infafafa
## **ВОПРОСЫ И ЗАДАНИЯ**
1) Процессор — это основной компонент вычислительных устройств, выполняющий обработку данных и управление всеми задачами системы. Его ещё называют центральным процессором, так как он выполняет основную работу в компьютере.

2) В состав центрального процессора (ЦП) входят следующие узлы:

Арифметико-логическое устройство (АЛУ) — выполняет основные математические и логические операции.
 
Управляющее устройство (УУ) — от него зависит согласованность работы компонентов ЦП и его связь с другими устройствами.
 
Шины данных и адресные шины.
 
Регистры, в которых временно хранится текущая команда, исходные, промежуточные и конечные данные (результаты вычислений АЛУ).
 
Счетчики команд.
 
Кэш-память — хранит часто используемые данные и команды.
АЛУ (арифметико-логическое устройство) выполняет все арифметические и логические операции. УУ (устройство управления) координирует взаимодействие различных частей компьютера. Оно формирует и подаёт во все блоки машины сигналы, в которых описан алгоритм действий. 

3) Арифметико-логическое устройство (АЛУ) — блок процессора, который под управлением устройства управления служит для выполнения арифметических и логических преобразований (начиная от элементарных) над данными, называемыми в этом случае операндами. Сумматор используется в арифметико-логическом устройстве (АЛУ) для выполнения операции арифметического сложения чисел, представленных в двоичных кодах. 

4) Автоматическое сравнение результата действия с нулём в АЛУ (арифметико-логическом устройстве) позволяет выдавать флаги, сообщающие о свойствах результата.

5) Чтобы установить факт равенства или неравенства нулю сумматора с помощью логических операций с его битами, нужно:

Определить, какие биты представляет собой сумматор. Обычно в нём используются биты для слагаемых, бит для переноса и бит для суммы. 

Применить логические операции к этим битам. 

Для проверки равенства нулю сумматора использовать операцию логического И (AND). Для этого необходимо выполнить логическое И между всеми битами сумматора. Если результат операции равен 0, то сумматор равен нулю. 

Для проверки неравенства нулю сумматора использовать операцию логического ИЛИ (OR). Для этого необходимо выполнить логическое ИЛИ между всеми битами сумматора. Если результат операции не равен 0, то сумматор не равен нулю.

6) Математический сопроцессор служит для расширения командного множества центрального процессора и обеспечения его функциональностью модуля операций с плавающей запятой.

7) Устройство управления (УУ) играет важную роль в автоматическом выполнении программ. Оно обеспечивает последовательность циклов исполнения команд.

8) Микрокоманда

9) Генератор тактовых импульсов нужен для синхронизации различных процессов в цифровых устройствах — ЭВМ, электронных часах, таймерах и других.

10) РОН (регистры общего назначения) — это часть устройства обработки данных, которая может использоваться для следующих целей: 
 
 • Хранение данных, полученных в процессе вычислений. 
 
 • Формирование адреса внешнего устройства или ячейки памяти искомого операнда или команды. 
 
 • Выполнение функций специальных регистров (сброс, инкремент, декремент и т. д.). 

11) -

12) Тактовая частота — частота синхронизирующих импульсов синхронной электронной схемы, то есть количество синхронизирующих тактов, поступающих извне на вход схемы за одну секунду. Обычно термин употребляется применительно к компонентам компьютерных систем.

С увеличением тактовой частотыпроцессора увеличивается и числоопераций, совершаемых компьютеромза одну секунду, а следовательно,возрастает и скорость работыкомпьютера.

13) Нет, равенство тактовых частот двух процессоров, изготовленных фирмами Intel и AMD, не означает, что их быстродействие одинаково

14) Применение конвейера влияет на количество команд, выполняемых за один такт, следующим образом:
Конвейеризация заставляет модули процессора работать параллельно над разными инструкциями. Это увеличивает пропускную способность процессора(количество команд, завершающихся в единицу времени). 

15) Разрядность процессора в первуюочередь влияет на скорость работыпроцессора с данными, потому что узким местом, сдерживающим рост скорости работы процессора, оказалась скорость передачи данных между процессором и памятью.

16) В систему команд любого процессора входят четыре основные группы операций: 
 
 1 Команды пересылки данных. Операнды просто пересылаются (точнее, копируются) из источника в приёмник. 1

 2 Арифметические команды. Выполняют операции сложения, вычитания, умножения, деления, увеличения на единицу (инкрементирования), уменьшения на единицу (декрементирования). 

 3 Логические команды. Производят над операндами логические операции, например, логическое И, логическое ИЛИ, исключающее ИЛИ, очистку, инверсию, разнообразные сдвиги. 

 4 Команды переходов. Предназначены для изменения обычного порядка последовательного выполнения команд. С их помощью организуются переходы на подпрограммы и возвраты из них, циклы, ветвления программ, пропуски фрагментов программ. 

17) RISC — это архитектура процессоров, которая предусматривает упрощение аппаратного обеспечения за счёт использования инструкций, состоящих из нескольких простых шагов (операций): хранения, загрузки и оценки.
CISC — это архитектура вычислений со сложным набором команд, которая позволяет сократить количество инструкций, выполняемых запущенным программным обеспечением. Подобный результат достигается за счёт объединения множества простых инструкций в одну, но сложную.

18) Арифметико-логическое устройство;

Регистр;

Устройство управления.

## **ЗАДАЧИ**
1) а) Z or N;    
   б) not (Z or N) = not Z and not N 
2) 60⋅109 
3) – 
4) 232‐1 = 4 294 967 295 
5) 4 
6) 64 Гб
