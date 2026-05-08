# Processador MIPS 8-bits (Monociclo) no Logisim

## Descrição Resumida do Projeto
Este projeto consiste na concepção e implementação de uma versão simplificada da arquitetura MIPS de 8 bits. Trata-se de um processador monociclo, onde cada instrução é executada em um único ciclo de clock, sem a utilização de pipeline. O caminho de dados foi totalmente implementado no Logisim e é composto por módulos fundamentais, incluindo: Contador de Programa (PC), Memória de Instruções, Unidade de Controle, Banco de Registradores, ULA, Memória de Dados e lógicas combinacionais de desvio e salto.

## Integrantes do Grupo - EC6
* Beatriz Carvalho Sousa (RA: 082230027 - Turma: EC6)
* Fernando Montanher da Cruz (RA: 082230010)
* Lucas da Silva Macêdo (RA: 082230037)
* Rhyú Costa de Souza (RA: 082230023)
* Yuri Villaço de Souza (RA: 082230036)

## Instruções para Execução do Circuito
1. Faça o download do arquivo `circuitoMIPS.circ` e abra-o no Logisim.
2. No circuito `main`, localize o módulo de **Memória de Instruções**.
3. Clique com o botão direito sobre a Memória de Instruções e selecione a opção para carregar o arquivo hexadecimal de testes contendo o código de máquina desejado.
4. Antes de iniciar, acione o sinal de `Clear` / `Reset` do PC para garantir que o processador inicie do endereço correto (0x00).
5. Ative a simulação do Clock (Ctrl+K ou via menu *Simulate > Ticks Enabled*) ou dê pulsos manuais no clock para visualizar a execução de cada instrução ciclo a ciclo.

## Link para o Vídeo Explicativo
https://youtu.be/43owFhYddug

## Diagrama de Blocos
<img width="1600" height="1051" alt="diagrama de blocos" src="https://github.com/user-attachments/assets/9b58ae0f-4e94-4c7d-aa4d-0b3fca98b9c1" />
