

```pseudocode
## Realice un programa que lea un número enteros y determine si es par o impar.
n:int
n= int(input("ingrese el número"))
if n % 2 == 0 or n==2:
   print("el número es par")
else: 
   print("el número es impar")
```



```pseudocode
 ## Realice un programa que lea tres números reales y determine si la suma de los dos primeros es mayor, menor o igual que el tercer número.
a:float
b:float
c:float
a= float(input("Ingrese el primer número"))
b= float(input("Ingrese el segundo número"))
c= float(input("ingrese el tercer número"))
if a+b>c:
  print("el resultado entre la suma de "+str(a)+" y "+str(b)+" es mayor que " +str(c))
elif a+b<c:
  print("el resultado entre la suma de "+str(a)+" y "+str(b)+" es menor que " +str(c))
elif a+b==c:
  print("el resultado entre la suma de "+str(a)+" y "+str(b)+" es igual que " +str(c))
```

