from math import erf, sqrt

if __name__ == '__main__':
    samples = int(input())
    mean = int(input())
    stdt_dev = int(input())
    perc = float(input())
    z = float(input())

    stdt_sample = stdt_dev / sqrt(samples)
   
    print(round(mean - stdt_sample * z, 2))
    print(round(mean + stdt_sample * z, 2))
