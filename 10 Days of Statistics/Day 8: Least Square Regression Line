if __name__ == '__main__':
    X, Y = [], []
    for _ in range(5):
        x, y = list(map(int, input().split()))
        X.append(x);Y.append(y)
    
    n = len(X)
    x_mean = sum(X)/ len(X)
    y_mean = sum(Y)/ len(Y)

    x_squared = sum([i ** 2 for i in X])
    xy = sum([X[i] * Y[i] for i in range(len(X))])

    b = (n * xy - sum(X) * sum(Y))/ (n * x_squared - sum(X) ** 2)
    a = y_mean - b * x_mean

    print(round(a + b * 80, 3))
