Projeto Cifra de Cesar em C
Projeto desenvolvido para a disciplina de Algoritmo e Pensamento Computacional, sob a orientação do Professor Francisco de Assis Cavallaro 

## Autores:
Felipe de Oliveira Brito 
Victor Correa

## Sobre o Projeto
Este sistema desenvolvido em linguagem C tem como objetivo unificar os conceitos de criptografia simples e matemática aplicada, promovendo um aprendizado ativo através da taxonomia de Bloom

O programa implementa um algoritmo de encriptação que atua com base em duas camadas de segurança:
**Camada 1:** Cifra de César, aplicando um deslocamento (SHIFT) fixo escolhido pelo usuario
**Camada 2:** Deslocamento dinâmico por letra, iterando sobre os valores de uma sequência matemática.

As opções de sequências matemáticas disponíveis no menu são:
1. Progressão Aritmética (PA(
2. Progressão Geométrica
3. Série de Fibonacci
4. Números Primos

## Como Executar
1. Compile o ficheiro `criptografia.c` num compilador C padrão (como o GCC).
2. Execute o programa no terminal.
3. Introduza uma palavra secreta com o máximo de 15 letras, sem acentos ou caracteres especiais.
4. Insira um número inteiro para o valor do SHIFT base.
5. Selecione no menu o número correspondente à sequência matemática pretendida.

## Saída de Dados
Após o processamento das duas camadas de deslocamento sobre cada letra da palavra original, o programa exibe o resultado no ecrã e gera automaticamente um ficheiro de registo. Toda a documentação e os detalhes da codificação (palavra codificada, valor do SHIFT, tipo de sequência e número de letras) ficam gravados no ficheiro `resultado_criptografia.txt` gerado na mesma pasta do executável.
