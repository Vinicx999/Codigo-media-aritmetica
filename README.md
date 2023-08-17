# Codigo-media-aritmetica
Código funcional para cálculo da média de notas de um aluno, com classificação de aprovados e reprovados

bim1 = float (input ("Digite a nota do Bimestre 1:"))
bim2 = float (input ("Digite a nota do Bimestre 2:"))
bim3 = float (input ("Digite a nota do Bimestre 3:"))
bim4 = float (input ("Digite a nota do Bimestre 4:"))
media = (bim1 + bim2 + bim3 + bim4) / 4

if media >= 9:
   print ("APROVADO COM LOUVOR!")
elif media >= 7:
   print ("APROVADO")
elif media < 7:   
   print ("REPROVADO")
 
print ("Média:",media)

