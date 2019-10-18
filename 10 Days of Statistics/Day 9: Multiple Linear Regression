import numpy as np

if __name__ == '__main__':
    m, n = list(map(int, input().split()))
    X, Y = [], []

    for i in range(n):
        data = input().split()
        X.append(data[:m])
        Y.append(data[m:])
    X = np.asarray(X,float)
    Y = np.asarray(Y,float)

    q = int(input())
    X_ = []
    for x in range(q):
        X_.append(input().split())

    X_ = np.asarray(X_, float)

    X_cen = X - np.mean(X)
    Y_cen = Y - np.mean(Y)

    b = np.dot(np.linalg.inv(np.dot(X_cen.T, X_cen)), np.dot(X_cen.T, Y_cen))

    X_cen = X_- np.mean(X)
    Y_cen = np.dot(X_cen, b)
    Y = Y_cen + np.mean(Y)

    for i in Y:
        print(round(float(i), 2))
