# Meu_primeiro_projeto_Python

# Meu_primeiro_projeto_Python


#Projeto de calculo para bonificação de funcionários a partir de mates alcançadas.


# Foi criado um programa para calculo de bônus para funcionários, seguindo as seguintes regras:

#A meta dos funcionários é 1000 vendas. 

#Se o valor de vendas for maior ou igual a meta, o valor do bônus do funcionário é 10% do valor de vendas.

#Caso contrário o valor de bônus do funcionário é 0. # O funcionário não recebá o bônus.

#Por último será printado os bônus refentes ao desempenho dos funcionários.

vendas_funcionario_1 = 1010 
vendas_funcionario_2 = 850 
vendas_funcionario_3 = 2350


if vendas_funcionario_1 >= 1000:
    print('O funcionário 1 ganhou {} de bônus'.format(vendas_funcionario_1 * 0.1))

if vendas_funcionario_2 >= 1000:
    bonus = vendas_funcionario_2 * 0.1
else:
    bonus = 0
print('O funcionário 2 ganhou {} de bônus'.format(bonus))

if vendas_funcionario_3 >= 1000:
    bonus = vendas_funcionario_3 * 0.1
else:
    bonus = 0
print('O funcionário 3 ganhou {} de bônus'.format(bonus))
