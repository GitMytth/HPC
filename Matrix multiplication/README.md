Был реализован ijk-алгоритм умножения матриц. При реализации варианта для GPU считалось, что каждый поток вычисляет свой элемент результирующей матрицы, т.е поток с глоабльным индексом (i, j) вычисляет элемент C(i, j) результирующей матрицы. Было проведено сравнение времени выполнения умножения матриц на GPU и CPU. Для вычислений на CPU использовалось два подхода: с использование JIT компилятора и без. Результаты представлены на графиках ниже.

![Mat_mul (1)](https://github.com/user-attachments/assets/a19af420-ef06-426b-994c-657c2adec2b8)


![Mat_mul (2)](https://github.com/user-attachments/assets/2f06748d-d729-421d-a245-239af6230414)
