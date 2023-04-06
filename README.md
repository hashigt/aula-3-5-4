# aula-3-5-4
fsd
numero = int(input("Digite um numero : "))
if(numero <= 10):
 print(f"f1: numero {numero} menor que 10 ")
elif (numero >= 10 and numero < 100):
     print(f"f2: numero {numero} maior que 10  e menor que 100 ")
else:
     print(f"f3: numeoro {numero} maior que 100  ") 

ORDEM CRESCENTE

num1 = int(input("Digite um numero : "))
num2 = int(input("Digite um numero : "))
num3 = int(input("Digite um numero : "))
if(num3 > num2 > num1):
    print(f"a ordem é {num3},{num2},{num1}")
elif(num1 > num2 > num3):
    print(f"a ordem é {num1},{num2},{num3}")
elif(num2 > num1 > num3):
    print(f"a ordem é {num2},{num1},{num3}")
