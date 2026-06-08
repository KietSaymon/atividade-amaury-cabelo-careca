# atividade-amaury-cabelo-careca

Grupo: Jose Saymon pimentel Mendonca / Pedro Lucas lima cavalcante


cadastro = []

Aqui você cria uma lista vazia que vai funcionar como um banco de dados simples.

cadastro = []

Tudo que for cadastrado vai ser guardado dentro dela.

Exemplo depois de alguns clientes:

cadastro = [
    {"nome": "João", "servico": "Corte", "valor": 25},
    {"nome": "Pedro", "servico": "Platinado", "valor": 120}
]
def

def significa definir uma função.

É como criar um bloco de código que você pode chamar quando precisar.

def adicionar_cliente():

Você está criando uma função chamada adicionar_cliente.

Quando o usuário escolher a opção 1:

adicionar_cliente()

Todo o código dentro dela será executado.

input()

Serve para receber informações do usuário.

nome = input("Digite o nome do cliente: ")

Se o usuário digitar:

José

A variável fica:

nome = "José"
print()

Mostra informações na tela.

print("1 - Corte")

Resultado:

1 - Corte

Você usou isso para criar o menu de serviços.

if, elif e else

São as condições.

Você está perguntando:

if opcao == "1":

Se a opção for 1:

servico = "Corte"
valor = 25

Se não for:

elif opcao == "2":

E assim por diante.

O else é o plano B:

else:
    print("Serviço inválido!")

Executa quando nenhuma opção foi escolhida corretamente.

Variáveis

São caixas que guardam informações.

Exemplo:

nome = "José"
valor = 25

Depois você pode usar essas informações em qualquer parte da função.

Dicionário {}

Você criou um dicionário para guardar os dados do cliente.

cliente = {
    "nome": nome,
    "servico": servico,
    "valor": valor
}

Na prática fica assim:

cliente = {
    "nome": "José",
    "servico": "Corte",
    "valor": 25
}

É parecido com uma ficha de cadastro.

append()

Serve para adicionar algo no final de uma lista.

cadastro.append(cliente)

Se a lista estava vazia:

[]

Depois:

[
    {"nome": "José", "servico": "Corte", "valor": 25}
]
return

Você usou:

return

Quando o serviço é inválido.

Ele interrompe a função imediatamente.

Exemplo:

else:
    print("Serviço inválido!")
    return

Se o usuário digitar uma opção errada, o cadastro para ali e volta para o menu principal.

len()

Conta quantos itens existem numa lista.

len(cadastro)

Exemplo:

cadastro = ["João", "Pedro", "José"]

Resultado:

3

Você usa isso para verificar se existe algum cliente cadastrado.

if len(cadastro) == 0:
for

Serve para percorrer uma lista.

for cliente in cadastro:

É como falar:

Para cada cliente dentro da lista cadastro.

Se tiver:

cadastro = [
    {"nome":"João"},
    {"nome":"Pedro"}
]

Primeira volta:

cliente = {"nome":"João"}

Segunda volta:

cliente = {"nome":"Pedro"}
Acessando dados do dicionário

Você faz:

cliente['nome']

Isso pega o valor da chave "nome".

Exemplo:

cliente = {
    "nome": "José",
    "servico": "Corte"
}

Resultado:

cliente['nome']

Retorna:

José
Acumulador (total)

Você criou:

total = 0

Para somar o valor de todos os serviços.

Depois:

total += cliente["valor"]

É a mesma coisa que:

total = total + cliente["valor"]

Exemplo:

25 + 120 + 55

Resultado:

200
while True

Cria um loop infinito.

while True:

O sistema continua funcionando até alguém mandar sair.

Por isso o menu aparece várias vezes.

break

Serve para encerrar o loop.

elif opcao == "3":
    break

Quando o usuário escolhe sair:

3

O programa para.
