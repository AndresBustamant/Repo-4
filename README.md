## Repo-4 
Hola buenas noches este es el repositorio con la solucoon del reto 4
#Notebook con las soluciones: https://colab.research.google.com/drive/10Aze5SarbjRhR0vQyFlxIYTgp332N-m6?usp=sharing

1.para el primer ejercicio tome como punto de partida el codigo ASCII donde a cada caracter se le asigna un valor de indetificacion numerico, teniendo esto en cuenta tome como referencia los valores correspondientes a la vocales minusculas (97,101,105,111,117) para plantear un programa, el cual al incertar un valor mostrara de manera especifica si dicho valor corresponde a un vocal minuscula y a cual.(de otra manera mostrara que no es una vocal minuscula) (el programa corresponde a el primer ejercicio del notebook)

```pseudocode
digito:int
digito=int(input("ingrese un digito: "))
if digito==97:
        print("el digito"+str(digito)+"corresponde a la vocal minuscula a")
elif digito==101:
        print("el digito"+str(digito)+"corresponde a la vocal minuscula e")
elif digito==105:
        print("el digito"+str(digito)+"corresponde a la vocal minuscula i")
elif digito==111:
        print("el digito"+str(digito)+"corresponde a la vocal minuscula o")
elif digito==117:
        print("el digito"+str(digito)+"corresponde a la vocal minuscula u")
else:
        print("el digito no corresponde a una vocal minuscula")
```
2.para el segundo ejercicio inicie solicitando la cadena de longitud 1, declarandola como un string, esto con el objetivo de aplicar la funcion "ord()" como medio para convertir la cadena de 1 caracter en un valor numerico en codigo ASCII, para finalizar plantee un condicional el cual realizara el modulo de el valor obtenido entre dos con el fin de solucionar el ejercicio indicando si el valor es par o impar el valor.(el programa corresponde a el segundo ejercicio del notebook)

```pseudocode
letra:str
letra=(input("ingrese un caracter: "))
y=ord(str(letra))
if y % 2==0:
    print("el caracter corresponde a un par en codigo ASCCI")
else:
    print("el caracter corresponde a un impar en codico ASCCI")
```
3.el tercer ejercicio me parecio un poco mas simple, ya que el programa podia empezar solicitando un caracter y despues se podia utilizar la funcion .isdigit() para saber si es un digito o no, dando por solucionado el ejercicio.(el programa corresponde a el tercer ejercicio del notebook)

```pseudocode
caracter:str
caracter=(input("ingrese una letra: "))
if caracter.isdigit():
    print("el caracter corresponde a un digito")
else:
    print("el caracter no corresponde a un digito")
```
4. en el cuarto ejercicion realize un programa el cual solicitara un numero real cualquiera y que a partir de tres condicionales determinara si es mayor, menor o igual a 0 emplenado la simbologia propia de los operadores logicos.(el programa corresponde a el cuarto ejercicio del notebook)

```pseudocode
x:float
x=float(input("colocar un numero: "))
y:float=0
if x < y:
    print("El número x es negativo")
elif x > y:
    print("El número x es positivo")
elif x == y:
    print("El número x es el neutro para la suma")
```
5. el quinto ejercico fue un poco mas complejo ya que para desarrollarlo se debe entender la circunferencia a partir de una formula, pero al ver como se desarrollaba a partir de ejemplos fue mas facil determinar las variables de entradas necesarias y las operaciones necesarias para solucionar el ejercicio.(el programa corresponde a el quinto ejercico del notebook)

```pseudocode
R:float
R=(input("ingresa el radio en x de la circunferencia: "))
Cx:float
Cx=(input("ingreasa las cordenadas del centro de la circunferencia en x"))
Cy:float
Cy=(input("ingreasa las cordenadas del centro de la circunferencia en y"))
Cxe:float
Cxe=(input("selecciona un valor para un punto en x"))
CYe:float
CYe=(input("selecciona un valor para un punto en y"))
if ((Cxe-Cx)**2+(CYe-Cy)**2)< R**2:
    print("el punto esta dentro de la circunferencia")
elif ((Cxe-Cx)**2+(CYe-Cy)**2)== R**2:
    print("el punto esta en la circunferencia")
elif ((Cxe-Cx)**2+(CYe-Cy)**2)> R**2:
    print("el punto esta fuera de la circunferencia")
```
6. para el ultimo punto me base en el teorema de desigualdad de los triangulos donde se plantean tres condiciones para poder construir un triangulo, las condiciones las plantee dentro del programa a partir del uso de condicionales para determina si la construccion de un triangulo a partir de cirtas medida es posible.(el programa corresponde a el sexto ejercicio en el notebook)

```pseudocode
l1:float
l1=float(input("ingrese la medida del primer lado: "))
l2:float
l2=float(input("ingrese la medida del segundo lado: "))
l3:float
l3=float(input("ingrese la medida del tercer lado: "))
if (l1+l2)>l3 and (l1+l3)>l2 and (l2+l3>l1):
    print("con las longitudes se pudede crear un triangulo")
else:
    print("con las longitudes no se puede crear un triangulo")
```   
gracias por leer hasta aqui =)
