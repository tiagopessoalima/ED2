# Estrutura de Dados 2

Este repositório contém materiais, códigos e projetos desenvolvidos na disciplina de Estrutura de Dados 2.

## 🎯 Objetivo Geral

Capacitar os alunos a compreender, projetar e implementar estruturas e algoritmos fundamentais, com foco na análise de complexidade e na aplicação prática de técnicas de ordenação, manipulação de listas, árvores, grafos e demais estruturas de dados.  
  
**Habilidades Desenvolvidas:**

- Análise de algoritmos e avaliação de desempenho (Big O, casos melhores, piores e médios);
- Implementação prática de algoritmos de ordenação e estruturas de listas (simples, duplas e circulares);
- Construção e manipulação de árvores (BST, AVL, B-Trees e Heaps) e grafos;
- Aplicação de técnicas de busca e otimização em problemas reais.

## 📚 Metodologia

- **Aulas Expositivas e Discussões Teóricas:** Revisão e aprofundamento dos principais conceitos de estruturas de dados e algoritmos.
- **Atividades Práticas:** Implementação dos algoritmos e estruturas em linguagens como Python ou Java, com ênfase em exercícios de análise de complexidade e comparação de desempenho.
- **Projetos Práticos:** Desenvolvimento de soluções integradas utilizando as estruturas estudadas, aplicadas em problemas reais.
- **Seminários:** Apresentações e debates sobre temas atuais e casos de uso práticos (ex: comparação entre algoritmos de ordenação e aplicações de listas encadeadas).

## 🗓️ Estrutura do Curso

A disciplina é dividida em 20 semanas, com aulas semanais, distribuídas conforme a seguinte programação:

| Sem | Tópico | Descrição e Objetivos | 🛠️ Material |
| :-: | :--- | :--- | :--- |
| **01** | **Algoritmos de Busca** | **Conteúdo:** Busca Linear, Binária (Iterativa/Recursiva) e Interpolada.<br>**Obj:** Entender limitações de vetores e a necessidade de dados ordenados. | [Notebook](Semana_01.ipynb) |
| **02** | **Árvores Binárias e BST** | **Conteúdo:** Conceitos (Raiz, Folha, Altura), Percursos (Pré/Em/Pós-ordem) e operações em BST.<br>**Obj:** Implementar recursão e operações de CRUD em árvores. | [Notebook](Semana_02.ipynb) |
| **03** | **Revisão e Prática I** | **Atividade:** Resolução de lista de exercícios focada em recursão e manipulação de ponteiros em BST.<br>**Foco:** Preparação para a prova. | [Lista 01](Lista_01.pdf) |
| **04** | **🛡️ PROVA 1** | **Avaliação:** Algoritmos de Busca e Árvores Binárias de Busca (BST). | -- |
| **05** | **Árvores AVL (Balanceamento)** | **Conteúdo:** Fator de balanceamento, Rotações Simples (LL, RR) e Duplas (LR, RL).<br>**Obj:** Garantir busca em tempo $O(\log n)$ no pior caso. | [Notebook](Semana_05.ipynb) |
| **06** | **Heaps e B-Trees** | **Conteúdo:** Filas de Prioridade (Binary Heaps) e introdução a Árvores B (armazenamento em disco).<br>**Obj:** Aplicações em ordenação e bancos de dados. | [Notebook](Semana_06.ipynb) |
| **07** | **Revisão e Prática II** | **Atividade:** Exercícios de rastreamento de rotações AVL e simulação de operações em Heaps.<br>**Foco:** Fixação de regras de balanceamento. | [Lista 02](Lista_02.pdf) |
| **08** | **🛡️ PROVA 2** | **Avaliação:** Árvores AVL, Heaps e Conceitos de B-Trees. | -- |
| **09** | **🗣️ Seminário 1** | **Tópicos Extras:** <br> 1. Árvores Rubro-Negras (Red-Black Trees); <br> 2. Tries (Árvores de Prefixo) e Huffman; <br> 3. Árvores Splay ou Skip Lists. | [Diretrizes](Seminario_01.pdf) |
| **10** | **🚀 PROJETO 1** | **Entrega:** Implementação de um Indexador/Dicionário utilizando Árvores (BST/AVL ou Tries). | [Spec Projeto](Projeto_01.pdf) |
| **11** | **Hashing (Tabelas Hash)** | **Conteúdo:** Funções de Hash, Tabelas de Dispersão e Tratamento de Colisões (Encadeamento vs End. Aberto).<br>**Obj:** Acesso direto $O(1)$. | [Notebook](Semana_11.ipynb) |
| **12** | **Grafos: Intro e Travessias** | **Conteúdo:** Representação (Matriz/Lista Adjacência), Busca em Largura (BFS) e Profundidade (DFS).<br>**Obj:** Modelar relacionamentos e percorrer grafos. | [Notebook](Semana_12.ipynb) |
| **13** | **Revisão e Prática III** | **Atividade:** Problemas de cálculo de hash e desenho de travessias em grafos.<br>**Foco:** Preparação para a prova. | [Lista 03](Lista_03.pdf) |
| **14** | **🛡️ PROVA 3** | **Avaliação:** Hashing e Fundamentos de Grafos (Conceitos + BFS/DFS). | -- |
| **15** | **Caminhos Mínimos** | **Conteúdo:** Algoritmos de Dijkstra (Guloso) e Bellman-Ford (Pesos negativos).<br>**Obj:** Encontrar rotas de menor custo em grafos ponderados. | [Notebook](Semana_15.ipynb) |
| **16** | **Topologia e MST** | **Conteúdo:** Árvore Geradora Mínima (Prim/Kruskal) e Ordenação Topológica.<br>**Obj:** Conectividade de redes e resolução de dependências. | [Notebook](Semana_16.ipynb) |
| **17** | **Revisão e Prática IV** | **Atividade:** Resolução de problemas complexos de grafos (estilo Maratona de Programação).<br>**Foco:** Identificar qual algoritmo usar. | [Lista 04](Lista_04.pdf) |
| **18** | **🛡️ PROVA 4** | **Avaliação:** Caminhos Mínimos, MST e Ordenação Topológica. | -- |
| **19** | **🗣️ Seminário 2** | **Tópicos Extras (Não vistos em aula):** <br> 1. Algoritmos de Fluxo Máximo (Ford-Fulkerson); <br> 2. Busca Heurística A* (A-Star); <br> 3. Filtros de Bloom (Bloom Filters) e HyperLogLog. | [Diretrizes](Seminario_02.pdf) |
| **20** | **🚀 PROJETO 2** | **Entrega:** Sistema de Rotas ou Recomendação (Integração Hash + Grafos). | [Spec Projeto](Projeto_02.pdf) |

## 💡 Como Utilizar Este Repositório

- **Estudo e Implementação:** Explore os códigos e implementações disponíveis para entender cada algoritmo e estrutura de dados.
- **Exercícios e Projetos:** Utilize os exemplos práticos para testar e validar seu entendimento, além de desenvolver projetos que integrem os conceitos estudados.
- **Pesquisa e Discussão:** Contribua com melhorias, participe de seminários e debates, e colabore para o avanço do conhecimento na área de Estrutura de Dados.

## 🤝 Contribuição

Sinta-se à vontade para contribuir com pull requests e participar de discussões para aprimorar os modelos, códigos e a documentação.  
  
**Como Contribuir:**

- Adicione novas implementações e algoritmos.
- Melhore a documentação e os exercícios.
- Compartilhe pesquisas e estudos de caso sobre as estruturas abordadas.
