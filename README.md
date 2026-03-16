# Estrutura de Dados 2

Este repositório contém materiais, códigos e projetos desenvolvidos na disciplina de Estrutura de Dados 2.

## 🎯 Objetivo Geral

Capacitar os alunos a compreender, projetar e implementar estruturas e algoritmos fundamentais, com foco na análise de complexidade e na aplicação prática de manipulação de listas, árvores, grafos e demais estruturas de dados.  
  
**Habilidades Desenvolvidas:**

- Análise de algoritmos e avaliação de desempenho (Big O, casos melhores, piores e médios);
- Implementação prática de estruturas dinâmicas e manipulação de ponteiros;
- Construção, manipulação e balanceamento de árvores (Árvores Binárias, BST, AVL, B-Trees e Heaps) e grafos;
- Aplicação de técnicas de otimização em problemas reais.

## 📚 Metodologia

- **Aulas Expositivas e Discussões Teóricas:** Revisão e aprofundamento dos principais conceitos de estruturas de dados e algoritmos.
- **Atividades Práticas:** Implementação dos algoritmos e estruturas em linguagens como Python ou Java, com ênfase em exercícios de análise de complexidade e comparação de desempenho.
- **Projetos Práticos:** Desenvolvimento de soluções integradas utilizando as estruturas estudadas, aplicadas em problemas reais.
- **Seminários:** Apresentações e debates sobre temas atuais e casos de uso práticos (ex: comparação entre estruturas de dados e aplicações).

## 🗓️ Estrutura do Curso

A disciplina é dividida em 23 semanas, com aulas semanais, distribuídas conforme a seguinte programação:

| Sem | Tópico | Descrição e Objetivos | 🛠️ Material |
| :-: | :--- | :--- | :--- |
| **01** | **Introdução a Árvores** | **Conteúdo:** Conceitos básicos, terminologia (Raiz, Folha, Altura, Grau) e aplicações.<br>**Obj:** Entender estruturas hierárquicas e o abandono da linearidade. | [Notebook](Semana_01.ipynb) |
| **02** | **Árvores Binárias (Parte 1)** | **Conteúdo:** Representação na memória e noções de recursão estrutural.<br>**Obj:** Criação de nós e manipulação de ligações esquerda/direita. | [Notebook](Semana_02.ipynb) |
| **03** | **Árvores Binárias (Parte 2)** | **Conteúdo:** Percursos em profundidade (Pré, Em e Pós-ordem) e em largura.<br>**Obj:** Navegação e extração de dados de forma sistemática. | [Notebook](Semana_03.ipynb) |
| **04** | **Revisão e Prática I** | **Atividade:** Resolução de lista de exercícios focada em recursão e ponteiros em árvores.<br>**Foco:** Preparação para a prova. | [Lista 01](Lista_01.pdf) |
| **05** | **🛡️ PROVA 1** | **Avaliação:** Fundamentos de Árvores e Árvores Binárias (Estrutura e Percursos). | -- |
| **06** | **Árvores Binárias de Busca (BST)** | **Conteúdo:** Regras fundamentais, busca, inserção e remoção.<br>

[Image of binary search tree data structure]
<br>**Obj:** Garantir a propriedade de ordenação e integridade após modificações. | [Notebook](Semana_06.ipynb) |
| **07** | **Árvores AVL (Parte 1)** | **Conteúdo:** Fator de balanceamento e Rotações Simples (LL, RR).<br><br>**Obj:** Identificar o desbalanceamento e aplicar correções básicas. | [Notebook](Semana_07.ipynb) |
| **08** | **Árvores AVL (Parte 2)** | **Conteúdo:** Rotações Duplas (LR, RL) e balanceamento contínuo.<br>**Obj:** Garantir busca em tempo O(log n) em todos os casos. | [Notebook](Semana_08.ipynb) |
| **09** | **Revisão e Prática II** | **Atividade:** Exercícios de rastreamento de rotações AVL no papel e no código.<br>**Foco:** Fixação de regras de balanceamento. | [Lista 02](Lista_02.pdf) |
| **10** | **🛡️ PROVA 2** | **Avaliação:** Árvores Binárias de Busca (BST), Árvores AVL e Balanceamento. | -- |
| **11** | **Heaps e B-Trees** | **Conteúdo:** Filas de Prioridade (Binary Heaps) e introdução a Árvores B (armazenamento em disco).<br>**Obj:** Aplicações em ordenação e bancos de dados. | [Notebook](Semana_11.ipynb) |
| **12** | **Hashing (Tabelas Hash)** | **Conteúdo:** Funções de Hash, Tabelas de Dispersão e Tratamento de Colisões (Encadeamento vs End. Aberto).<br>**Obj:** Acesso direto O(1). | [Notebook](Semana_14.ipynb) |
| **13** | **Grafos: Intro e Travessias** | **Conteúdo:** Representação (Matriz/Lista Adjacência), Busca em Largura (BFS) e Profundidade (DFS).<br><br>**Obj:** Modelar relacionamentos e percorrer grafos. | [Notebook](Semana_15.ipynb) |
| **14** | **Revisão e Prática III** | **Atividade:** Problemas de cálculo de hash e desenho de travessias em grafos.<br>**Foco:** Preparação para a prova. | [Lista 03](Lista_03.pdf) |
| **15** | **🛡️ PROVA 3** | **Avaliação:** Hashing e Fundamentos de Grafos (Conceitos + BFS/DFS). | -- |
| **16** | **Caminhos Mínimos** | **Conteúdo:** Algoritmos de Dijkstra (Guloso) e Bellman-Ford (Pesos negativos).<br>**Obj:** Encontrar rotas de menor custo em grafos ponderados. | [Notebook](Semana_18.ipynb) |
| **17** | **Topologia e MST** | **Conteúdo:** Árvore Geradora Mínima (Prim/Kruskal) e Ordenação Topológica.<br>**Obj:** Conectividade de redes e resolução de dependências. | [Notebook](Semana_19.ipynb) |
| **18** | **Revisão e Prática IV** | **Atividade:** Resolução de problemas complexos de grafos (estilo Maratona de Programação).<br>**Foco:** Identificar qual algoritmo usar. | [Lista 04](Lista_04.pdf) |
| **19** | **🛡️ PROVA 4** | **Avaliação:** Caminhos Mínimos, MST e Ordenação Topológica. | -- |
| **20** | **🚀 PROJETO 2** | **Entrega:** Sistema de Detecção de Outliers e Anomalias: Identificar lesões raras que não se agrupam em clusters conhecidos. | -- |

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
