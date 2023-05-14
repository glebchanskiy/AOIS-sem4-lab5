# LR5

## Таблица истинности (переходов)

![table](./sreens/table.png)

h1: (!A&!B&!C&!D&V)|(A&B&C&D&V)|(!A&B&C&D&V)|(A&!B&C&D&V)|(!A&!B&C&D&V)|(A&B&!C&D&V)|(!A&B&!C&D&V)|(A&!B&!C&D&V)|(!A&!B&!C&D&V)|(A&B&C&!D&V)|(!A&B&C&!D&V)|(A&!B&C&!D&V)|(!A&!B&C&!D&V)|(A&B&!C&!D&V)|(!A&B&!C&!D&V)|(A&!B&!C&!D&V)
-> V

h2: (!A&!B&!C&!D&V)|(!A&B&C&D&V)|(!A&!B&C&D&V)|(!A&B&!C&D&V)|(!A&!B&!C&D&V)|(!A&B&C&!D&V)|(!A&!B&C&!D&V)|(!A&B&!C&!D&V)
-> (V&!A)

h3: (!A&!B&!C&!D&V)|(!A&!B&C&D&V)|(!A&!B&!C&D&V)|(!A&!B&C&!D&V)
-> (V&!B&!A)

h4: (!A&!B&!C&!D&V)|(!A&!B&!C&D&V)
-> (V&!C&!B&!A)

### Пример минимализации

h2:
![h2](./sreens/part2.png)
h3:
![h3](./sreens/part3.png)
h4:
![h4](./sreens/part4.png)

(E = V)
