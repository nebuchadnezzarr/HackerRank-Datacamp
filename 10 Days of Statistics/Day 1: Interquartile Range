from statistics import median

if __name__ == '__main__':
    n = int(input())
    X = list(map(int, input().split()))
    F = list(map(int, input().split()))

    S = []
    for i in range(n):
        S += [X[i]] * F[i]


    S = sorted(S)
    if (n % 2 == 0):
        Q1 = median(S[:sum(F)//2])
        Q3 = median(S[sum(F)//2:])
    else:
        Q1 = median(S[:sum(F)//2])
        Q3 = median(S[sum(F)//2 + 1:])

    print(round(float(Q3 - Q1), 1))
