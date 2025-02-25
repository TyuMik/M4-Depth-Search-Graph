Задача 1. Обход в глубину
В этом задании нужно реализовать обход графа в глубину.

Граф представлен матрицей смежности размерностью N x N — это двумерный массив, содержащий N строчек и N столбцов.

N — это количество вершин графа. Все вершины графа пронумерованы, то есть имеют уникальный индекс от 1 до N включительно.

Значение, находящееся в ячейке матрицы смежности, говорит о наличии или отсутствии связи между вершинами, индексы которых соответствуют номеру строчки и номеру столбца этой ячейки. Если значение в ячейке равно 1, то связь между вершинами есть. Если значение равно 0, то связи между вершинами нет. В ячейках с одинаковыми номерами столбца и строки всегда находится 0.

Ваша задача — имея предоставленную матрицу смежности, произвести обход графа, представленного этой матрицей, в глубину. При посещении каждой следующей ячейки ваша программа должна вывести на консоль индекс посещаемой ячейки.

Матрица смежности будет задаваться в текстовом файле в формате: первым числом в файле идёт количество вершин графа (N). Далее располагаются N строчек, каждая из которых содержит N чисел — 1 или 0.

Обход графа начинается с первой вершины с индексом 1.