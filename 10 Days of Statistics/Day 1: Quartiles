from statistics import median

if __name__ == '__main__':
    n = int(input())
    X = sorted(list(map(int, input().split())))

    if (n % 2 == 0):
        Q_l = X[:n//2]
        Q_h = X[n//2:]

    else:
        Q_l = X[:n//2]
        Q_h = X[n//2 + 1:]

    print(int(median(Q_l)), int(median(X)), int(median(Q_h)), sep = '\n')
