# Calcular-m2-parede
calcular altura e largura da parede para saber quantos litros de tinta usar.

alt = int(input("Qual a altura: "))
larg = int(input("Qual a largura: "))

area = alt * larg
tint = area / 2
print("O tamanho da parede é  {:.2f}m2\nA quantidade de tinta a ser usada é {:.1f} litros ".format(area,tint))
