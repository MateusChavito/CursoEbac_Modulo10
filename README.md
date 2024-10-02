📝 Projeto: Calculadora de Média com Status de Aprovação
Este projeto realiza o cálculo da média de quatro notas e imprime o status final do aluno: Aprovado, Recuperação, ou Reprovado, com base na média final.

✨ Funcionalidade
O programa:

Lê quatro notas de alunos.
Calcula a média aritmética simples dessas notas.
Exibe a média e o status do aluno (Aprovado, Recuperação ou Reprovado) com base na média calculada.

🧮 Como o código funciona

Entrada: Quatro notas são fornecidas diretamente no código.

Cálculo: A média aritmética é calculada dividindo a soma das notas por 4.

Saída: O resultado é exibido, e o status do aluno é determinado:

Aprovado: Média maior ou igual a 7.

Recuperação: Média entre 5 e 7 (não incluído).

Reprovado: Média abaixo de 5.

🔍 Nota sobre o uso de float
No código, utilizei o float para calcular a média. Como as notas são int, o cálculo pode acabar sendo inteiro, então é recomendável usar pelo menos um dos números com float, como 4.0f, para garantir precisão no cálculo.
