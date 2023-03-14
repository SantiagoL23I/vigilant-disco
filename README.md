

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
  [![](https://mermaid.ink/img/pako:eNp1lmtu4zYQgK9C6E93gWywdh61vUABxXYdBYkd2Mk-QufHSGJsbiVSS4pOnCCH6QH6o-gRcrEOpVhiuqwBCxyKH2c4L-opSGTKgkFwl8n7ZA2qJFejT0tB8Be-iwRPuHxPPnz4jZw8RWKlmAZFjCAFcE1SRiBniifw_IqQpagHJ8iQxctfFfo7XaKaTOYxh2Vwi3M4eU5juZLly5-35JPDaF4hEwpqxUTJBdy-vj6lsWFCagIczWipFopowZTZrZ_Uek5fxagWz2jG82bP6lnbGlVbPKCpRpmVgW1j6VeaS1GyDU-Z3Kl1ma093ppnrCG-UQ1oO6y86x9xfaxA86wBbmg9wcEH3FtAZnzjuO8L1SZRzLe8xOUbJtijYVkLXNEEFCSgfUiBiDYKvZ03wCUtEMhB8dh7DBAI2WOis8iWxKBik7b6wildABclOZNr8YtXawz2YLBGJbrhTkIqQGswPmLFkUB9JcvBOdskoglH5alNyea1X6WqdKoYUukqnWMEeLpipbwXXpBZjmU8acN8MqY4k8sCvEhij5eAAMcrw5DKsoR7r3GJrApFl0BsUbXQzOYT-S61N96JsZiJHeCaZkDWEKNyH5Hbw-TsgSeyYS7Gjg_rdz5UpYgqVpgYXQEklTnHJoF6mo3moyr7Zf3upxKwS1J70B3agKMZVXhEf-RZgghLDIZNNcR4SH8YXnoNZZkFMqIh27yFzitv7uZ9rNE2dAwDgUmC7Y67uXK9COk96DWerZRij4z2h_veXFV2E3y-SYDJPET1ti5WTGKL81fG2jpoLUVqlFMapzNaspVJ-AqywhvYlanqY-vGY3JNa1X_l9pra-caeMlbTSEtDFMYxAJbcMILb-J9t-B3rF43imch_QNdo9E3PkbYCrZhV4CF2lDTiOZoNE5525NVVNRI25cvQwraoHV-TUXVoPCJBjrM1Enz-qUP1hVs8yRRXJcv_8SQYZMTnG1YG5AF7hZjs2IlU_5ebCuh3giLOsPQgQvbnqxLxZk3CfTm1YQNNh28gFB_BprUGYWt2rHj887n_gijCtwKn5jJePItKWWMl1N7N8yjXbyZLuDl7598Mp3VN3l4TqPpZD5ejMn1FL0ZLchoTMKL8TwahrdVU6w4XIjCRb3Jt3Z40w6v2uGXdnjZDsNpOx7O2vFJ2I4nkTs_d4SxA9dAfdsPrx3hYuwI1WM0c2bGQ1c4dwRsAo6ERe1Ip-4WE1fdqbvszBWmkSNchm-EqSMt_itdueJnR8CYOhL52rqDnDpjJ0zkzBlfvLvj4v3r55x9BHt4Yyis9RS_Fp_sDGbUmuV4HQ5wmLI7MFm5DJbiGZeCKeViK5JgcAeZZnuBKVK8lkf4TYTfFM0sFuCNlCiXytRiMHgKHoJBt9PZx3__oNM9POh1P_b6e8E2GBwd7R93ekfHh8fHH7u9o18Pn_eCx2qDzn6_f9TtHvf6B71Ot9_tHD7_C8L3EDo?type=png)](https://mermaid.live/edit#pako:eNp1lmtu4zYQgK9C6E93gWywdh61vUABxXYdBYkd2Mk-QufHSGJsbiVSS4pOnCCH6QH6o-gRcrEOpVhiuqwBCxyKH2c4L-opSGTKgkFwl8n7ZA2qJFejT0tB8Be-iwRPuHxPPnz4jZw8RWKlmAZFjCAFcE1SRiBniifw_IqQpagHJ8iQxctfFfo7XaKaTOYxh2Vwi3M4eU5juZLly5-35JPDaF4hEwpqxUTJBdy-vj6lsWFCagIczWipFopowZTZrZ_Uek5fxagWz2jG82bP6lnbGlVbPKCpRpmVgW1j6VeaS1GyDU-Z3Kl1ma093ppnrCG-UQ1oO6y86x9xfaxA86wBbmg9wcEH3FtAZnzjuO8L1SZRzLe8xOUbJtijYVkLXNEEFCSgfUiBiDYKvZ03wCUtEMhB8dh7DBAI2WOis8iWxKBik7b6wildABclOZNr8YtXawz2YLBGJbrhTkIqQGswPmLFkUB9JcvBOdskoglH5alNyea1X6WqdKoYUukqnWMEeLpipbwXXpBZjmU8acN8MqY4k8sCvEhij5eAAMcrw5DKsoR7r3GJrApFl0BsUbXQzOYT-S61N96JsZiJHeCaZkDWEKNyH5Hbw-TsgSeyYS7Gjg_rdz5UpYgqVpgYXQEklTnHJoF6mo3moyr7Zf3upxKwS1J70B3agKMZVXhEf-RZgghLDIZNNcR4SH8YXnoNZZkFMqIh27yFzitv7uZ9rNE2dAwDgUmC7Y67uXK9COk96DWerZRij4z2h_veXFV2E3y-SYDJPET1ti5WTGKL81fG2jpoLUVqlFMapzNaspVJ-AqywhvYlanqY-vGY3JNa1X_l9pra-caeMlbTSEtDFMYxAJbcMILb-J9t-B3rF43imch_QNdo9E3PkbYCrZhV4CF2lDTiOZoNE5525NVVNRI25cvQwraoHV-TUXVoPCJBjrM1Enz-qUP1hVs8yRRXJcv_8SQYZMTnG1YG5AF7hZjs2IlU_5ebCuh3giLOsPQgQvbnqxLxZk3CfTm1YQNNh28gFB_BprUGYWt2rHj887n_gijCtwKn5jJePItKWWMl1N7N8yjXbyZLuDl7598Mp3VN3l4TqPpZD5ejMn1FL0ZLchoTMKL8TwahrdVU6w4XIjCRb3Jt3Z40w6v2uGXdnjZDsNpOx7O2vFJ2I4nkTs_d4SxA9dAfdsPrx3hYuwI1WM0c2bGQ1c4dwRsAo6ERe1Ip-4WE1fdqbvszBWmkSNchm-EqSMt_itdueJnR8CYOhL52rqDnDpjJ0zkzBlfvLvj4v3r55x9BHt4Yyis9RS_Fp_sDGbUmuV4HQ5wmLI7MFm5DJbiGZeCKeViK5JgcAeZZnuBKVK8lkf4TYTfFM0sFuCNlCiXytRiMHgKHoJBt9PZx3__oNM9POh1P_b6e8E2GBwd7R93ekfHh8fHH7u9o18Pn_eCx2qDzn6_f9TtHvf6B71Ot9_tHD7_C8L3EDo)
