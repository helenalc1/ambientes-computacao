## Este é um trabalho apresentado à disciplina de Ambientes em Computação do programa de blá blá ...
Alunos: Fabiano, Helena, Rossana e Thaiane  
Algoritmo implementado: Algoritmo de sequênciamento de Needleman Wunch  

## Como baixar e rodar o repositório

Para baixar e rodar o repositório, siga os seguintes passos:

Clone o repositório usando o comando: git clone <URL_do_repositório>.  
Navegue até o diretório do repositório clonado: cd <nome_do_repositório>.  
Certifique-se de que você possui o Python instalado. Para rodar o programa, utilize o comando:  
```sh 
python needleman_wunsch.py
```

## Funcionamento do algoritmo
O alinhamento de sequências permite comparar duas ou mais sequências, o que permite a análise de padrões e homologias entre diferentes organismos. Tais padrões podem estar relacionados a diferenciadas funções dos genes, podem relacionar-se com similaridade entre os organismos, evidenciando relacionamento evolutivo, dentre outros. As sequências podem ser alinhadas de forma local ou global. No caso do alinhamento global, busca-se a maior sub-sequencia comum entre as duas sequências, permitindo inserções e deleções e fazendo com que o alinhamento se extenda para todo o comprimento das sequências. 

As sequências biológicas são analisadas na forma de strings e, portanto, tais dados devem ser comparados por meio da função score, que determina as semelhanças ou diferenças entre as sequências. A partir da determinação da estrutura da função score e seus pesos é necessária a utilização de técnicas computacionais para obtenção de um alinhamento entre as sequências que otimize a função score. Um dos algoritmos mais tradicionais para a finalidade de alinhamento global é o Needleman-Wunsch. Ele utiliza técnicas de programação dinâmica, com custo de ordem O(n 2), pela sua complexidade quadrática.

O presente script contém o algoritmo Needleman-Wunsch para comparação de diferentes sequências.


