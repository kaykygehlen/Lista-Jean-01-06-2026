#### 1\)

numero = int(input("Digite um numero inteiro: "))



primo = True



if numero <= 1:



primo = False



else:



for i in range(2, numero):



if numero % i == 0:



primo = False



if primo:



print("é primo")



else:



print("não é primo")



#### 2\)

numero = int(input("Digite um numero inteiro: "))



primo = True



divisores = \[]



if numero <= 1:



primo = False



else:



for i in range(2, numero):



if numero % i == 0:



primo = False



divisores.append(i)



if primo:



print("é primo")



else:



print("não é primo")



if len(divisores) > 0:



print("é divisivel por:", divisores)



#### 3\)

n = int(input("Digite um numero: "))



divisoes = 0



print("Numeros primos entre 1 e", n, ":")



for num in range(2, n + 1):



primo = True



for i in range(2, num):



divisoes += 1



if num % i == 0:



primo = False





if primo:



print(num)



print("numeros de divisoes feitas:", divisoes)



#### 4\)

n = int(input("Quantas notas serao informadas? "))



soma = 0



for i in range(n):



nota = float(input(f"Digite a {i+1}ª nota: "))



soma += nota



media = soma / n



print("Media aritmetica: ", media)



#### 5\)

quantidade = int(input("Quantas pessoas há na turma? "))



soma\_idades = 0



for i in range(quantidade):

&#x20;   idade = int(input(f"Digite a idade da {i + 1}ª pessoa: "))

&#x20;   soma\_idades += idade



media = soma\_idades / quantidade



print(f"\\nMédia de idade: {media:.2f}")



if media <= 25:

&#x20;   print("A turma é jovem.")

elif media <= 60:

&#x20;   print("A turma é adulta.")

else:

&#x20;   print("A turma é idosa.")

#### 6\)

eleitores = int(input("Digite o número total de eleitores: "))



Bozo = 0

Lula = 0

Ciro = 0



for i in range(eleitores):

&#x20;   print("Eleitor", i + 1)

&#x20;   voto = int(input("Vote (1, 2 ou 3): "))



&#x20;   if voto == 1:

&#x20;       Bozo += 1

&#x20;   elif voto == 2:

&#x20;       Lula += 1

&#x20;   elif voto == 3:

&#x20;       Ciro += 1



print("Resultado da eleição:")

print("Bozo:", Bozo, "votos")

print("Lula:", Lula, "votos")

print("Ciro:", Ciro, "votos")

#### 7\)

turmas = int(input("Digite a quantidade de turmas: "))



total\_alunos = 0



for i in range(turmas):

&#x20;   alunos = int(input("Digite a quantidade de alunos da turma: "))



&#x20;   while alunos > 40:

&#x20;       print("A turma não pode ter mais de 40 alunos.")

&#x20;       alunos = int(input("Digite a quantidade de alunos da turma: "))



&#x20;   total\_alunos = total\_alunos + alunos



media = total\_alunos / turmas



print("Número médio de alunos por turma:", media)

#### 8\)

quantidade = int(input("Digite a quantidade de CDs: "))



total = 0



for i in range(quantidade):

&#x20;   valor = float(input("Digite o valor do CD: "))

&#x20;   total = total + valor



media = total / quantidade



print("Valor total investido:", total)

print("Valor médio gasto por CD:", media)

#### 9\)

preco = 1.99



print("Lojas Quase 2")

print("Tabela de preços")



for quantidade in range(1, 51):

&#x20;   valor = quantidade \* preco

&#x20;   print(quantidade, "- R$", valor)

#### 10\)

preco = float(input("preço do pao: R$ "))



print("Panificador Pão de Ontem")

print("Tabela de preços:")



for quantidade in range(1,51):

&#x20;   valor = quantidade \* preco

&#x20;   print(quantidade, "- R$ ", valor)

#### 11\)

print("Lojas Tabajara")



total = 0

produto = 1



preco = float(input("produto " + str(produto) + ": R$ "))



while preco != 0:

&#x20;   total = total + preco

&#x20;   produto = produto + 1

&#x20;   preco = float(input("produto " + str(produto) + ": R$ "))



print("total: R$", total)

dinheiro = float(input("Dinheiro: R$ "))

troco = dinheiro - total

print("Troco: R$", troco )

#### 12\)

numero = int(input("Digite um numero:"))



fatorial = 1



print("Fatorial de:", numero)



for i in range (numero, 0,-1):

&#x20;   fatorial = fatorial \* i

&#x20;   print(i, end="")

&#x20;   

&#x20;   if i > 1:

&#x20;       print(" . ", end="")

print(" =", fatorial)

#### 12+1)

soma = 0

quantidade = 0



temperatura = float(input("Digite uma temperatura (-999 para encerrar): "))



maior = temperatura

menor = temperatura



while temperatura != -999:

&#x20;   soma = soma + temperatura

&#x20;   quantidade = quantidade + 1



&#x20;   if temperatura > maior:

&#x20;       maior = temperatura



&#x20;   if temperatura < menor:

&#x20;       menor = temperatura



&#x20;   temperatura = float(input("Digite uma temperatura (-999 para encerrar): "))



media = soma / quantidade



print("Maior temperatura:", maior)

print("Menor temperatura:", menor)

print("Média das temperaturas:", media)

#### 14\)

numero = int(input("Digite um numero inteiro: "))



primo = True



if numero <= 1:

&#x20;   primo = False



else:

&#x20;   for i in range(2, numero):

&#x20;       if numero % i == 0:

&#x20;           primo = False



if primo:

&#x20;   print("é primo")



else:

&#x20;   print("não é primo")

#### 15\)

limite = int(input("Digite um número inteiro: "))



for numero in range(2, limite + 1):

&#x20;   primo = True



&#x20;   for i in range(2, numero):

&#x20;       if numero % i == 0:

&#x20;           primo = False



&#x20;   if primo:

&#x20;       print(numero)

#### 16\)

numero = int(input("Montar a tabuada de: "))

inicio = int(input("Começar por: "))

fim = int(input("Terminar em: "))



if fim < inicio:

&#x20;   print("O valor final não pode ser menor que o inicial.")



else:

&#x20;   print("Vou montar a tabuada de", numero, "começando em", inicio, "e terminando em", fim)



&#x20;   for i in range(inicio, fim + 1):

&#x20;       resultado = numero \* i

&#x20;       print(numero, "x", i, "=", resultado)

#### 17\)

codigo = int(input("Digite o código do cliente: "))



soma\_altura = 0

soma\_peso = 0

quantidade = 0



while codigo != 0:

&#x20;   altura = float(input("Digite a altura: "))

&#x20;   peso = float(input("Digite o peso: "))



&#x20;   if quantidade == 0:

&#x20;       mais\_alto = altura

&#x20;       codigo\_alto = codigo



&#x20;       mais\_baixo = altura

&#x20;       codigo\_baixo = codigo



&#x20;       mais\_gordo = peso

&#x20;       codigo\_gordo = codigo



&#x20;       mais\_magro = peso

&#x20;       codigo\_magro = codigo



&#x20;   if altura > mais\_alto:

&#x20;       mais\_alto = altura

&#x20;       codigo\_alto = codigo



&#x20;   if altura < mais\_baixo:

&#x20;       mais\_baixo = altura

&#x20;       codigo\_baixo = codigo



&#x20;   if peso > mais\_gordo:

&#x20;       mais\_gordo = peso

&#x20;       codigo\_gordo = codigo



&#x20;   if peso < mais\_magro:

&#x20;       mais\_magro = peso

&#x20;       codigo\_magro = codigo



&#x20;   soma\_altura = soma\_altura + altura

&#x20;   soma\_peso = soma\_peso + peso

&#x20;   quantidade = quantidade + 1



&#x20;   codigo = int(input("Digite o código do cliente: "))



media\_altura = soma\_altura / quantidade

media\_peso = soma\_peso / quantidade



print("Cliente mais alto:")

print("Código:", codigo\_alto)

print("Altura:", mais\_alto)



print("Cliente mais baixo:")

print("Código:", codigo\_baixo)

print("Altura:", mais\_baixo)



print("Cliente mais gordo:")

print("Código:", codigo\_gordo)

print("Peso:", mais\_gordo)



print("Cliente mais magro:")

print("Código:", codigo\_magro)

print("Peso:", mais\_magro)



print("Média das alturas:", media\_altura)

print("Média dos pesos:", media peso)

#### 18\)

salario = float(input("Digite o salário inicial: "))



percentual = 1.5



for ano in range(1996, 2027):

&#x20;   salario = salario + (salario \* percentual / 100)

&#x20;   percentual = percentual \* 2



print("Salário atual: R$", salario)

#### 19\)

for i in range(10):

&#x20;   numero = int(input("Digite o número do aluno: "))

&#x20;   altura = float(input("Digite a altura em cm: "))



&#x20;   if i == 0:

&#x20;       maior\_altura = altura

&#x20;       numero\_maior = numero



&#x20;       menor\_altura = altura

&#x20;       numero\_menor = numero



&#x20;   if altura > maior\_altura:

&#x20;       maior\_altura = altura

&#x20;       numero\_maior = numero



&#x20;   if altura < menor\_altura:

&#x20;       menor\_altura = altura

&#x20;       numero\_menor = numero



print("Aluno mais alto:")

print("Número:", numero\_maior)

print("Altura:", maior\_altura, "cm")



print("Aluno mais baixo:")

print("Número:", numero\_menor)

print("Altura:", menor\_altura, "cm")

#### 20\)

soma\_veiculos = 0



soma\_acidentes\_menor2000 = 0

cidades\_menor2000 = 0



for i in range(5):

&#x20;   codigo = int(input("Código da cidade: "))

&#x20;   veiculos = int(input("Número de veículos: "))

&#x20;   acidentes = int(input("Número de acidentes: "))



&#x20;   indice = acidentes / veiculos



&#x20;   if i == 0:

&#x20;       maior\_indice = indice

&#x20;       codigo\_maior = codigo



&#x20;       menor\_indice = indice

&#x20;       codigo\_menor = codigo



&#x20;   if indice > maior\_indice:

&#x20;       maior\_indice = indice

&#x20;       codigo\_maior = codigo



&#x20;   if indice < menor\_indice:

&#x20;       menor\_indice = indice

&#x20;       codigo\_menor = codigo



&#x20;   soma\_veiculos = soma\_veiculos + veiculos



&#x20;   if veiculos < 2000:

&#x20;       soma\_acidentes\_menor2000 = soma\_acidentes\_menor2000 + acidentes

&#x20;       cidades\_menor2000 = cidades\_menor2000 + 1



media\_veiculos = soma\_veiculos / 5



if cidades\_menor2000 > 0:

&#x20;   media\_acidentes = soma\_acidentes\_menor2000 / cidades\_menor2000

else:

&#x20;   media\_acidentes = 0



print("Maior índice de acidentes:", maior\_indice)

print("Cidade:", codigo\_maior)



print("Menor índice de acidentes:", menor\_indice)

print("Cidade:", codigo\_menor)



print("Média de veículos:", media\_veiculos)



print("Média de acidentes nas cidades com menos de 2000 veículos:")

print(media\_acidentes)







