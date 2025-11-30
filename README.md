🏆 Super Trunfo de Cidades (Nível Aventureiro)

 Sobre o Projeto

Este projeto é uma implementação em linguagem C do jogo de cartas Super Trunfo, focado em dados de cidades. O objetivo deste nível foi introduzir a interatividade via menu switch e implementar uma lógica de comparação complexa (if-else aninhado) que lida com diferentes regras de vitória para cada atributo.

O código permite o cadastro de duas cartas e a realização de uma única batalha interativa.

✨ Funcionalidades

  Cadastro de Cartas: Permite a entrada de dados como População, Área, PIB e Pontos Turísticos para duas cidades.

  Cálculos Automáticos: Calcula a Densidade Demográfica e o PIB Per Capita.

  Menu de Batalha: Interface simples via console (switch) para escolher o atributo de comparação.

  Lógica de Comparação:

  Maior Vence: Para População, Área, PIB e Pontos Turísticos.

  Menor Vence: Para a Densidade Demográfica (Regra Inversa).

  Resultado: Exibe claramente a cidade vencedora ou se houve empate.

🛠️ Tecnologias Utilizadas

Ferramenta	Descrição
Linguagem C	Linguagem principal do projeto.
GCC (ou similar)	Compilador C necessário para construir o executável.

🚀 Como Compilar e Executar

Siga os passos abaixo para rodar o jogo em seu ambiente local (Terminal, CMD, PowerShell ou Git Bash).

Pré-requisitos

Certifique-se de ter um Compilador C (como GCC) instalado em sua máquina.

1. Compilação

    Salve o arquivo de código-fonte (o código C completo) no seu diretório local, por exemplo, como super_trunfo.c.

    Abra o terminal na pasta onde o arquivo foi salvo.

    Use o GCC para compilar o código e gerar um executável:
    Bash

    gcc super_trunfo.c -o super_trunfo

2. Execução

Execute o arquivo gerado:
Bash

./super_trunfo

3. Jogo

O programa o guiará pelas seguintes etapas:

  Entrada de dados para a Carta 1.

  Entrada de dados para a Carta 2.

  Exibição do menu de batalha.

  Escolha um número de 1 a 5 para iniciar a comparação.


Autor: Bruno Mazini de Almeida

Data: 29 de Novembro de 2025
