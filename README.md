# python-matrix-addition

# Python program to implement matrix addition

X = [
    [8, 5, 1],
    [9, 3, 2],
    [4, 6, 3]
]

Y = [
    [8, 5, 3],
    [9, 5, 7],
    [9, 4, 1]
]

# Initialize result matrix with zeros
result = [
    [0, 0, 0],
    [0, 0, 0],
    [0, 0, 0]
]

# Add corresponding elements of the matrices
for i in range(len(X)):
    for j in range(len(X[0])):
        result[i][j] = X[i][j] + Y[i][j]

# Print the result matrix
print("Result of matrix addition is:")
for row in result:
    print(row)


OUTPUT:

Result of matrix addition is:
[16, 10, 4]
[18, 8, 9]
[13, 10, 4]

