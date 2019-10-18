from math import erf, sqrt

if __name__ == '__main__':
    avail = int(input())
    num = int(input())
    mean = float(input())
    stdt_dev = float(input())

    CDF = lambda x, mean, stdt_dev : 1/2 * (1 + erf((x - mean)/(stdt_dev * sqrt(2))))

    print(round(CDF(avail, num * mean, sqrt(num) * stdt_dev), 4))
