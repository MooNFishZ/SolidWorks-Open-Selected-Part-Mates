# SolidWorks-Open-Selected-Part-Mates
Для SolidWorks 2021 SP5.1 (и вероятно другие версии).

Открывает кастомное окно сопряжений именно выделенной детали или подсборки, достаточно любую грань объекта и нажать горячую клавишу.

<img width="370" height="461" alt="2026-08-05_11-35-46" src="https://github.com/user-attachments/assets/5cdd2015-7fe7-4bd9-a97a-091e38675eef" />

--------


Как установить

1. Сохрани OpenSelectedPartMates.swp в любой папке.

2. Инструменты → Настройка → Клавиатура (Customize → Keyboard), найди категорию макросов, назначь горячую клавишу на этот файл. Например Shift + Q.


--------


Важные нюансы

Если у SW не подключены ссылки на библиотеки типов (обычно подключаются автоматически при создании макроса), а константы вроде swDocASSEMBLY, swSelSHEETS, swDontRebuildActiveDoc не распознаются — открой в редакторе VBA Tools → References и убедись, что отмечены SldWorks 2021 Type Library и SolidWorks 2021 Constant type library.



--------

eng

For SolidWorks 2021 SP5.1 (and likely other versions).

Opens a custom mating window for the selected part or subassembly. Simply select any face of the object and press the hotkey.
