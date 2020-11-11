import math

tam= 10 #tamanho da matriz
matriz=[] #matriz gerada aleatoriamente
for i in range(tam): #pecorrendo a matriz
    linha=[]
    for j in range(tam):
        coluna=[]
        while True:
            num=random.randint(0,100) #proteção de dados pra numeros positivos
            if (num >=0):
                break
        linha.append(num)
    matriz.append(linha)

print("\nMatriz\n") #print matriz 10x10
for i in range (tam):
    for j in range (tam):
         print(f"{matriz[i][j]}", end = "\t")

    print("\n")


listapar=[]
vetpar=0
print("\nLISTA PAR\n") #selecionando os numeros pares da matriz linha por linha
for i in range (tam):
    for j in range(tam):
        if matriz[i][j]% 2 ==0:
            print(f"{matriz[i][j]}", end ="\t" )

        matriz.append(linha)
    listapar.append(vetpar)
    print("\n")





print("\nLISTA IMPAR\n") #selecionando os numeros impares
for i in range (tam):
    for j in range(tam):
        if matriz[i][j]% 2 ==1:
            print(f"{matriz[i][j]}", end ="\t" )
    matriz.append(coluna)

    print("\n")
