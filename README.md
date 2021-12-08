

<h3 align='center'> Варіант №4 </h3>

___

Розробити програму, яка б надавала інформацію про персонажів
комп’ютерної гри. Вони бувають трьох видів: 
1. Люди (фізично найслабші),
2. Тролі (середні).
3. Орки (найсильніші). 

Кожен з персонажів має рівень захисту та
силу. Сила залежить від початкової величини та він того, яким озброєнням
володіє персонаж (луки, мечі, булава, кинджали, сокири). Персонаж може
заволодіти будь-яким видом озброєння. Рівень захисту залежить від
одягу (обладунки) та щитів(дерев’яні, металеві). Програма повинна
створювати персонажів усіх видів. Для вибраного героя здійснювати
перевірку, чи є хтось сильніший за нього, та чи є персонажі, яких він може
побити за 1, 5 чи 10 ударів (чи перевищує сила його удару чи групи ударів
чийсь захист). При розробці скористатись шаблонами [Facade](https://refactoring.guru/design-patterns/facade/csharp/example) та [Decorator](https://metanit.com/sharp/patterns/4.1.php).

---

UML Diagram (Class Diagram):

![image](https://user-images.githubusercontent.com/55552780/144760931-ee1d01d2-092a-4002-b446-cd626c28b179.png)   
Додаткові класи (в тому числі й Фасад):       
![image](https://user-images.githubusercontent.com/55552780/144760992-95141022-eed1-458d-9125-830b727ecd9a.png)

---

Початковий вигляд UI:
![image](https://user-images.githubusercontent.com/55552780/144746805-e5dee9f1-076f-4adb-95ed-7f920f0fe2d0.png)

Основні контролери створення персонажа:  
![overview1](https://user-images.githubusercontent.com/55552780/144762183-2ad13722-e501-48a2-aec3-b35b10565e4a.gif)   
Функціонал стовпчикової діаграми:   
![overview2](https://user-images.githubusercontent.com/55552780/144762640-5d95263d-0d0a-4f26-8a62-2c57376780b2.gif)   
Спливаюче вікно при некоректній спробі додати нового персонажа:    
![overview3](https://user-images.githubusercontent.com/55552780/144763232-3e664e5a-c218-4c5b-9343-2ad1a2c8ddc8.gif)   
Створення нового воїна (персонажа, героя) і відображення його деталей, - хто дужчий за нього, а хто слабший:    
![overview4](https://user-images.githubusercontent.com/55552780/144764360-7a20f460-514e-4e2f-8d29-807b460e80c3.gif)   
