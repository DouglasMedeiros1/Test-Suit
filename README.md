## Este repositório contém uma suíte de testes unitários robusta desenvolvida para garantir a correta implementação e o comportamento das classes CustomStack (Pilha de Capacidade Fixa) e NumberAscOrder (Algoritmo de Ordenação).

### Esta suíte de testes valida:

O tratamento de Exceções Personalizadas (StackFullException, StackEmptyException).
A integridade das operações LIFO (Last-In, First-Out) da pilha.
A funcionalidade do algoritmo de ordenação de números.

### 🚀 Guia de Configuração e Instalação

Siga os passos abaixo para configurar seu ambiente de desenvolvimento e preparar a execução dos testes.

1. Clonagem e Navegação(Assumindo que você já clonou o repositório.)
2. Navegue para o diretório raiz do projeto

cd ./Test_Suit-Douglas/Atv

3. Instalação de Dependências
   
*É recomendado o uso de um ambiente virtual para isolar as dependências do projeto.

Instalação: pip install -r requirements.txt
Instala todas as dependências do projeto (incluindo pytest e pytest-cov).✅

### Execução dos Testes e Relatório de Cobertura
A execução dos testes é realizada usando a biblioteca pytest, garantindo que todas as condições de teste (incluindo as de exceção) sejam avaliadas.


## Test Execution

Utilize o comando abaixo para executar todos os testes presentes no diretório ./test/ e, simultaneamente, gerar um relatório de cobertura de código.

python -m pytest ./test/* --cov
