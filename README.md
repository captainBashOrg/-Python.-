print("Матрица воплоти")


def get_matrix (x, y, val):
    matrix = []

    for i in range (0, x ):
        m1 = []
        for j in range(0, y):
            m1.append(val)
        #print(m1)
        matrix.append(m1)

    return matrix




result1 = get_matrix(2, 2, 10)
result2 = get_matrix(3, 5, 42)
result3 = get_matrix(4, 2, 13)
print(result1)
print(result2)
print(result3)
