# 📘 Projeto de Estudos – Contador de Divisores

Este projeto implementa um programa em Python que **lê um número inteiro positivo** informado pelo usuário e calcula **quantos divisores** esse número possui.

O exercício foi desenvolvido a partir de um fluxograma e reescrito utilizando **funções** para organizar melhor o código.

---

## 🚀 Estrutura do Programa

O programa é dividido em três partes principais:

### 1. Função de Entrada (`ler_numero`)
- Solicita ao usuário um número inteiro positivo.  
- Valida a entrada: se o número for menor ou igual a zero, pede novamente.  
- Retorna o número válido.  

### 2. Função de Cálculo (`contar_divisores`)
- Recebe o número informado.  
- Percorre todos os valores de 1 até `n`.  
- Verifica se cada valor é divisor (`n % divisor == 0`).  
- Conta quantos divisores existem.  
- Retorna a quantidade de divisores.  

### 3. Programa Principal (`main`)
- Chama a função de entrada para obter o número.  
- Chama a função de cálculo para contar os divisores.  
- Exibe o resultado formatado na tela.  

---
