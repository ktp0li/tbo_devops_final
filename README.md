### Шаги решения:
1. Видим, что g++ не делает никакой полезной работы. Смотрим положение бинарника через which, смотрим исходники бинарника, запускаем g++ с правильными флагами (или через ln создаем симлинк на g++)
2. Меняем в app.cpp количество требуемых аргументов для вывода справки (с 4 на 1)
3. Меняем в Math.cpp в вычитании “+” на “-”
4. При умножении звёздочку нужно эскейпить (пример: ./out 2 \* 3 либо ./out 2 “*” 3)
