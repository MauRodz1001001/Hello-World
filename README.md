# Hello-World
MyFirstProject
#print("Ingresa un numero:")
#numero=int(input())
numero=0
while numero!=100:
    numero=numero+1
    lista=[]
    cont=0
    while cont!=numero:
        cont=cont+1
        p=numero%cont
        lista.append(p)
    #print(lista)
    ceros=lista.count(0)
    #print(lista.count(0))
    if ceros==2:
        print(numero)        
     #   print("No es Primo")
    #else:
     #   print("Es primo")
