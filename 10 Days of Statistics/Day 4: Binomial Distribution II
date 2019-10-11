from math import factorial

def nCr(n, r):
    return factorial(n)/(factorial(n - r) * factorial(r))

def bin_dist(x, n, p):
    return nCr(n, x) * (p ** x) * ((1 - p) ** (n - x))

if __name__ == '__main__':
    print(round(sum([bin_dist(x, 10, 0.88) for x in range(8, 11)]), 3))
    print(round(sum([bin_dist(x, 10, 0.12) for x in range(2, 11)]), 3))
