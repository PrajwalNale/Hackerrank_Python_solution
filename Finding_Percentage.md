# Hackerrank_Python_solution
Finding Percentage

n=int(input())
a={}
for i in range(0,n):
    s=input()
    sp=s.split(" ")
    n=sp[0]
    m1=float(sp[1])
    m2=float(sp[2])
    m3=float(sp[3])
    m_avg=(m1+m2+m3)/3.0
    a[n]="%.2f" % m_avg
s_name=input()
print(a[s_name])
