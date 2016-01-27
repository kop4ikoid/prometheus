def karatsuba(x,y):
    deviderx = int(len(str(x)) /2)
    devidery = int(len(str(y)) /2)
    if int(len(str(y)))==1 or int(len(str(y)))==1  or int(len(str(x)))==0 or int(len(str(y)))==0:
        return(x*y)
    a = x// (10 ** deviderx)
    b = x% (10 ** deviderx)
    c = y// (10 ** devidery)
    d = y% (10 ** devidery)
    res1 = karatsuba(a, c)
    res2 = karatsuba(a, d)
    res3 = karatsuba(b, c)
    res4 = karatsuba(b, d)
    return ((10 ** (deviderx*2))* res1) + ((10**deviderx)*(res2 + res3)) + res4


