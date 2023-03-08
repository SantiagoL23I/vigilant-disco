

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
```pseudocode
a:float
b:float
c:float
d:float
e:float
a=float(input("digite el primer número"))
b=float(input("digite el segundo número"))
c=float(input("digite el tercer número"))
d=float(input("digite el cuarto número"))
e=float(input("digite el quinto número"))
f= a+b+c+d+e
g= f/5
print ("el promedio es "+str(g))

if a<b<c<d<e:
    print("la mediana es "+str(c))
elif b<a<c<d<e:
    print("la mediana es "+str(c))
elif c<a<b<d<e:
    print("la mediana es "+str(b))
elif d<a<b<c<e:
    print("la mediana es "+str(b))
elif e<a<b<c<d:
    print("la mediana es "+str(b))
elif a>b>c>d>e:
    print("la mediana es "+str(c))
elif b>a>c>d>e:
    print("la mediana es "+str(c))
elif c>a>b>d>e:
    print("la mediana es "+str(b))
elif d>a>b>c>e:
    print("la mediana es "+str(b))
elif e>a>b>c>d:
    print("la mediana es "+str(b))
elif b<c<d<e<a:
    print("la mediana es "+str(d))
elif c<d<e<a<b:
    print("la mediana es "+str(e))
elif d<e<a<b<c:
    print("la mediana es "+str(a))
elif b>c>d>e>a:
    print("la mediana es "+str(d))
elif c>d>e>a>b:
    print("la mediana es "+str(e))
elif d>e>a>b>c:
    print("la mediana es "+str(a)) a>b<c b
elif 
    print("la mediana es "+str(c)) 
```
```pseudocode
Pais= (input("Ingrese un país de américa en minúscula"))
match Pais:
  case "colombia":
        print("bogota")
  case "argentina":     
        print("buenos aires")
  case "uruguay":
      print("montevideo")
  case "chile":
      print("santiago")    
  case "peru":
      print("lima")
  case "brasil":
      print("brasilia")
  case "bolivia":
      print("sucre") 
  case "venezuela":
      print("caracas") 
  case "surinam":
      print("paramaribo")
  case"antigua y barbuda":
      print ("Saint John's")
  case "bahamas":
      print ("nassau")
  case "guatemala":
      print("ciudad de guatemala")
  case "barbados":
      print("bridgetown")
  case "belice":
      print("belmopan")
  case "canada":
      print("ottawa")
  case "costa rica":
      print("san jose")
  case "cuba":
      print("la habana")
  case "mexico":
      print("ciudad de mexico")
  case "republica dominicana":
      print("santo domingo")
  case "dominica":
      print("roseau")
  case "ecuador":
      print("quito")
  case "el salvador":
        print("san salvador")
  case "estados unidos":
        print("washington, D.C.") 
  case "granada":
        print("saint george's")
  case "honduras":
        print("tegucigalpa")
  case "guyana":
        print("georgetown") 
  case "haiti":
        print("puerto ptincipe")
  case "jamaica":
        print("kingston")
  case "nicaragua":
        print("managua")
  case "paraguay":
        print("asuncion")
  case "panama":
        print("ciudad de panama")
  case "san cristóbal y nieves":
        print("basseterre")
  case "santa lucia":
        print("castries")
  case "san vicente y las granadinas":
        print("kingstown")
  case "trinidad y tobago":
        print("puerto españa")      
  case _: print(str(Pais)+" no es un país de américa")      
  ```
