🧮 Calculadora de Bhaskara em C++

Este projeto é uma calculadora simples desenvolvida em C++ para calcular as raízes de uma equação do segundo grau utilizando a fórmula de Bhaskara.

📌 Sobre o projeto

O programa recebe os valores de A, B e C de uma equação do segundo grau:

ax² + bx + c = 0


A partir desses valores, o programa calcula o Delta (Δ) e verifica se a equação possui raízes reais.

📐 Fórmula utilizada

O Delta é calculado pela fórmula:

Δ = b² - 4ac


Quando existem raízes reais, elas são calculadas pela fórmula:

x₁ = (-b + √Δ) / 2a

x₂ = (-b - √Δ) / 2a

🔎 Funcionamento

O programa verifica três situações:

Δ < 0: a equação não possui raízes reais.

Δ = 0: a equação possui apenas uma raiz real.

Δ > 0: a equação possui duas raízes reais.

Também é verificado se A é igual a zero. Nesse caso, a equação não é de segundo grau.

🛠️ Tecnologias utilizadas

C++

Biblioteca <iostream>

O projeto não utiliza a biblioteca <cmath>.

📂 Estrutura do projeto
calculadora-bhaskara/
│
├── main.cpp
└── README.md

▶️ Como executar
Compilar

Utilizando o compilador g++:

g++ main.cpp -o calculadora

Executar

No Windows:

calculadora.exe


No Linux/macOS:

./calculadora

💻 Exemplo

Para a equação:

x² - 5x + 6 = 0


Os valores são:

A = 1
B = -5
C = 6


O resultado esperado é:

Delta = 1

X1 = 3
X2 = 2

🎯 Objetivo

O objetivo do projeto é praticar conceitos básicos de C++, como:

Variáveis;

Entrada de dados com cin;

Saída de dados com cout;

Estruturas condicionais;

Operações matemáticas;

Resolução de equações através de programação.

👨‍💻 Autor

Projeto desenvolvido para fins de estudo e aprendizado em C++.
