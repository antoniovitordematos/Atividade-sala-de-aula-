# Atividade-sala-de-aula-]
Antonio vitor de Matos Cruz 
Atividade de Python


1)
def dias_de_vida(idade):
    return idade * 365


idade = 20
resultado = dias_de_vida(idade)
print(resultado)


2)
def aplicar_desconto(valor, porcentagem):
    desconto = valor * porcentagem / 100
    return valor - desconto


valor = 100
porcentagem = 15


resultado = aplicar_desconto(valor, porcentagem)
print(resultado)


3)
def e_par(numero):
  return numero % 2 == 0


print(e_par(10))
print(e_par(7))


4)
def situação_aluno(n1, n2, n3):
  media = (n1 + n2 + n3)/3


  if media >= 7:
    status = "aprovado"
  else:
    status = "reprovado"


  return  media, status


print(situação_aluno(8, 7, 6))


5)
from IPython.core.interactiveshell import no_op
def gerar_email(nome, Sobrenome):
  return f"{nome}.{Sobrenome}@escola.com".lower()


nome = input("digite o nome:")
sobrenome = input("digite o sobrenome:")


email = gerar_email(nome, sobrenome)
print("email gerado:", email)


