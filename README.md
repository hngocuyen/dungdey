# dungdey
ct cxc
an = a+(n-1)*d
bns
def s(a,x):
    l = 0
    r = len(a)-1
    while l<=r:
        m = (l + r) // 2
        if a[m] == x:
            return m
        if a[m] < x:
            l = m + 1
        else:
            r = m - 1
    return -1
snt 
def s(n):
    p = [True] * (n+1)
    for i in range(2, int(n**0.5)+1):
        if p[i]:
            for j in range(i**2, n+1, i):
                p[j] = False
    return [i for i in range(2, n+1) if p[i]]
n = 100
r = s(n)
print(r)

