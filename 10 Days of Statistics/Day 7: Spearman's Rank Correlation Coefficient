if __name__ == '__main__':
    n = int(input())
    X = list(map(float, input().split()))
    Y = list(map(float, input().split()))

    rank_x = [(sorted(X).index(j)) + 1 for i in X
                                       for j in sorted(X)
                                       if (i == j)]

    rank_y = [(sorted(Y).index(j)) + 1 for i in Y
                                       for j in sorted(Y)
                                       if (i == j)]

    r_xy = 1 - 6*sum([(rank_x[i] - rank_y[i]) ** 2 for i in range(n)])/(n ** 3 - n)

    print(round(r_xy, 3))
