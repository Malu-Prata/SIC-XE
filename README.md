# 🖥️ Simulador SIC/XE - Sistema de Computador Hipotético

Este projeto consiste na implementação de um simulador completo para o computador hipotético **SIC/XE**, baseado na arquitetura de **Leland L. Beck**. O sistema integra processamento de macros, montagem, ligação e uma interface visual para execução. Trabalho realizado na disciplina de Programação de Sistemas no semestre 2026/1.

---

## 🚀 Funcionalidades Implementadas

### 🛠️ Conjunto de Instruções (ISA)
O simulador suporta as seguintes instruções implementadas em Java:
* **Aritméticas:** `ADD`, `ADDR`, `SUB`, `SUBR`, `MUL`, `MULR`, `DIV`, `DIVR`.
* **Lógicas e Comparação:** `AND`, `OR`, `COMP`, `COMPR`, `TIX`, `TIXR`.
* **Carga e Armazenamento:** `LDA`, `LDB`, `LDCH`, `LDL`, `LDS`, `LDT`, `LDX`, `STA`, `STB`, `STCH`, `STL`, `STS`, `STT`, `STX`.
* **Desvio e Controle:** `J`, `JEQ`, `JGT`, `JLT`, `JSUB`, `RSUB`, `RMO`, `CLEAR`, `SHIFTL`, `SHIFTR`.

### 📂 Módulos do Sistema
1. **Processador de Macros:** Processamento de macros aninhadas em uma única passagem (Saída: `MASMAPRG.ASM`).
2. **Montador:** Duas passagens para tradução de código assembly para objeto.
3. **Ligador e Relocador:** Duas passagens para resolução de referências externas e ajuste de endereços de carga.
4. **Executor e Interface:** Interface gráfica para monitoramento de registradores, memória e ciclo de instrução.

---

## 📝 Documentação e Avaliação
O projeto inclui:
* Código-fonte completo das instruções e módulos.
* Documentação formal das estruturas de dados e estratégias de projeto.
* Foco em correção, autenticidade e boas técnicas de programação.

---

## 👥 Alunos (Grupo)
* Bernardo Simões Pires Robaina
* Diogo Krüger Souto
* Gustavo Ulyssea Estivalet
* Kananda Barbosa Winter
* Maria Luiza Batista Prata
* Pedro Vergara Mota
* William de Almeida Pavinato

---
*Trabalho Prático - Programação de Sistemas - 2026*
