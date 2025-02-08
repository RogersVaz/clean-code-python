# Aprendendo Python

Este repositório é um guia para iniciantes aprenderem Python e seus conceitos fundamentais. Python é uma linguagem de programação poderosa, flexível e fácil de aprender. Vamos passar por conceitos básicos e avançados com exemplos de código em Python.

## Introdução ao Python

Python é uma linguagem de programação de alto nível, orientada a objetos e com uma sintaxe simples. É muito utilizada em diversas áreas, como análise de dados, desenvolvimento web, automação e muito mais.

### Instalando o Python

Para começar a programar em Python, primeiro você precisa instalar a linguagem em sua máquina. Você pode baixar a versão mais recente do Python [aqui](https://www.python.org/downloads/).

Verifique se o Python foi instalado corretamente digitando no terminal:

```bash
python --version

# Variáveis e Tipos de Dados
nome = "João"       # String
idade = 30          # Inteiro
altura = 1.75        # Float
ativo = True         # Booleano


# Lista
frutas = ["maçã", "banana", "laranja"]
print(frutas[0])  # Acessa o primeiro item da lista

# Dicionário
pessoa = {
    "nome": "João",
    "idade": 30
}
print(pessoa["nome"])  # Acessa o valor associado à chave 'nome'


# Função simples
def saudacao(nome):
    return f"Olá, {nome}!"

print(saudacao("João"))  # Chama a função e imprime a saudação


# Estruturas Condicionais
idade = 18

if idade >= 18:
    print("Você é maior de idade.")
else:
    print("Você é menor de idade.")


# Loop com for
for i in range(5):
    print(i)  # Imprime os números de 0 a 4

# Loop com while
contador = 0
while contador < 5:
    print(contador)
    contador += 1


# Definindo uma classe
class Carro:
    def __init__(self, modelo, cor):
        self.modelo = modelo
        self.cor = cor

    def ligar(self):
        return f"O {self.modelo} está ligado."

# Criando um objeto
meu_carro = Carro("Fusca", "azul")
print(meu_carro.ligar())  # Chama o método ligar


# Lendo um arquivo
with open("meuarquivo.txt", "r") as arquivo:
    conteudo = arquivo.read()
    print(conteudo)

# Escrevendo em um arquivo
with open("meuarquivo.txt", "w") as arquivo:
    arquivo.write("Olá, mundo!")


# Importando um módulo
import math

# Usando uma função do módulo
print(math.sqrt(16))  # Imprime 4.0


meu_projeto/
│
├── variaveis.py
├── listas_dicionarios.py
├── funcoes.py
├── condicionais.py
├── loops.py
├── classes.py
├── manipulacao_arquivos.py
└── modulos.py


---

### Como organizar seus arquivos Python:

1. **Crie um repositório no GitHub**.
2. **Adicione os arquivos Python** que mencionei no guia, criando os seguintes arquivos:
    - `variaveis.py`
    - `listas_dicionarios.py`
    - `funcoes.py`
    - `condicionais.py`
    - `loops.py`
    - `classes.py`
    - `manipulacao_arquivos.py`
    - `modulos.py`
3. **Copie o conteúdo de cada bloco de código** e cole nos arquivos correspondentes.


