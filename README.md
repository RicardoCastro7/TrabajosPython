# TrabajosPython
m=  int (input ('Digite el total de elementos : '))
n= int (input  ('Digite el total de combinaciones : '))
factorial1 = 1
factorial2 = 1
factorial3 = 1
diferencia = m - n

for i in range(m):
    factorial1 = factorial1 *m
    m -= 1

for i in range(n):
    factorial2 = factorial2 *n
    n -=1

for i in range(diferencia):
    factorial3 = factorial3*diferencia
    diferencia -=1
       
print ("Total de combinaciones:",factorial1/(factorial2*factorial3))
