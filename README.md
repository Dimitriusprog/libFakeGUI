# libFakeGUI

1.Иницифлизируем матрицу с помощью класса BoxPanel, которая выполняет функцию панели виджетов(кнопок).


2.Каждой кнопке(элементу матрицы) присваиваем через метод Set значения положения, размеров, цвета, названия(положения элементов матрицы должны соответствовать их графическому положению).


3.Создаём функции, которые будут выполняться на выбранной кнопке и вписываем указатель на каждую их них в определенный элемент матрицы с помощью метода SetFunc.


4.C помощию цикла обрабатываем нажатия клавиш, которые мы сами задаём.При нажатии вверх должен вызываться метод box->Ymi(); вниз - box->Ypl();влево - box->Xmi();вправо - box->Xpl();.


5.Необязательная модификация: метод box->Update(10); , который перемещает печатную вагонку на указанную координату по Oy.


6.Радуемся жизни.
