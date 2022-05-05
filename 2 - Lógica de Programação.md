## Lógica de Programação

> Forma de pensamento para resolução de problema.

> Organização e planejamento das instruções, assertivas em um algoritmo, a fim de viabilizar a implantação de um programa.

### Técnicas
- Linear: modelo tradicional, associada a matemática. Execução sequenciadas com recursos limitados. 
Ex.: Acordar, levantar, ir para cozinha, preparar café e tomar café.

- Estruturada: organização, disposição e ordem dos elementos essenciais que compõem um corpo. Pode ter mais de uma opção.
Ex.: Acordar, levantar, ir para cozinha, preparar café OU suco e tomar café OU suco.

- Modular: controlados por um conjunto de regras. Modelo padrão: dados de entrada, processamento e dados de saída. 
- Ex.: Módulo acordar (Acordar, levantar), Módulo preparar bebida (preparar a bebida selecionada), Módulo café da manhã (comer/beber o que foi preparado)


## Fundamentos de Algoritmos

### Variáveis
Variáveis podem ser mutáveis, portanto são instáveis. São dados que podem ser do tipo:
- Numéricos: inteiros e reais.
- Caractéres: letras e símbolos.
- Lógico: true (1) ou false (0).

🔒As variáveis estão restrita ao seu tipo. 


### Instruções primitivas
Ações a ser executados em sima dos nossos dados. Operadores binário (*, /, %, +, -, ...) e unário (+, -).

    Nota1 = 5
    Nota2 = 8
    Resultado = 0
    
    Resultado = (Nota1 + Nota2) / 2


### Estruturas condicionais
Dado uma condição sendo satisfeita, eu executo algo, ou caso não seja satisfeita, acarreta outra execução ou mesmo uma exceção.

**Operadores Relacionais:** (=, <>, <, >, <=, >=)
**Operadores Lógicos:** (AND, OR, NOT)



### Estruturas de repetição
Trecho do programa que precisa ser executados *n* vezes ou em loop até certa condição ser satisfeita.

***Enquanto... faça
Repita... até
Para... de... até... faça***

**Exemplo:**
Enquanto houver páginas em um livro, leiae passe para a próxima página.

    enquanto (página)
    	leia (página)
    	passar página



### Vetores e matrizes
**Vetor:** sequência de dados. Variável com uma sequência. Unidimensional.
**Matriz:** é uma tabela organizada em linhas e colunas. Vetor bidimensional.

Exemplo:

    notas_alunos = [10, 9.5, 8, 10, 7, 6, 2, 8]
    notas = [10, 2, 4, 8, 10]["Pedro", "Maria", "José", "Paula", "Paulo"]

notas_alunos é um exemplo de vetor.
notas é um exemplo de matriz. Sua representação seria:

| Pedro 	| 10 |

| Maria 	| 2 |

| José 		| 4 |

| Paula 	| 8 |

| Paulo 	| 10 |



### Funções
São blocos e instruções que realizam tarefas específicas (decomposição de algoritmo). São identificados por nomes e parâmetros.

    função mediaAluno (nota1, nota2)
    	resultado = 0
    	resultado = (nota1 + nota2) / 2
    
	    retornar resultado

	media aluno(10, 8) // retorna 9.0






