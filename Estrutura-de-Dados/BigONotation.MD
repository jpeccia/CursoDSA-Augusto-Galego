# Big O Notation - Complexidade de Algoritmos

A notação **Big O** descreve como um algoritmo escala com o tamanho da entrada.  
Ela não mede diretamente a performance, mas sim o crescimento do tempo de execução à medida que os dados aumentam.  

## Conceitos Fundamentais

- **Big O não significa velocidade absoluta:**  
  Dois algoritmos podem ter complexidades diferentes, como `O(n)` e `O(n²)`, mas não podemos afirmar que um será sempre mais rápido que o outro sem uma análise detalhada.  
- **Escalabilidade é o foco:**  
  Embora `O(n)` seja geralmente preferível a `O(n²)`, a importância real está em entender como cada algoritmo se comporta conforme o tamanho da entrada aumenta.

## Principais Classes de Complexidade

| Notação  | Descrição |
|----------|-------------------------------------------|
| `O(1)`   | **Tempo constante** – Independe do tamanho da entrada. |
| `O(log n)` | **Crescimento logarítmico** – Aumenta lentamente conforme a entrada cresce. |
| `O(n log n)` | **Crescimento log-linear** – Comum em algoritmos eficientes de ordenação(sorting, divide and conquer). |
| `O(n²)` | **Crescimento quadrático** – O tempo de execução cresce exponencialmente com a entrada. |
| `O(2^n)` | **Crescimento exponencial** – O tempo dobra a cada incremento da entrada. |

## Conclusão

A notação Big O ajuda a comparar algoritmos em termos de eficiência e escalabilidade.  
Ela é essencial para escolher a melhor solução para um problema, especialmente quando lidamos com grandes volumes de dados.

---
