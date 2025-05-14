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

| Semana | Tópico & Descrição | Objetivos | 🛠️ Ferramentas/Técnicas | Material de Apoio |
| :----: | ------------------ | --------- | ----------------------- | ----------------- |
| **1**  | **Recapitulação de Complexidade Algorítmica** <br> **Descrição:** Revisão dos conceitos de análise de algoritmos, notação Big O, uso de tempo e espaço, com ênfase na comparação entre algoritmos iterativos e recursivos, por meio de exercícios práticos. | - Relembrar conceitos fundamentais de complexidade.<br>- Comparar desempenho de soluções recursivas vs. iterativas.<br>- Exercitar análise de casos melhores, piores e médios. | Exercícios práticos, análise de algoritmos | [Notebook](Semana_01_(ED2).ipynb) |
| **2**  | **Merge Sort** <br> **Descrição:** Apresentação do paradigma de divisão e conquista aplicado no Merge Sort, com detalhes de implementação, análise de complexidade e comparação com outros métodos de ordenação. | - Compreender o funcionamento do Merge Sort (dividir, conquistar e mesclar).<br>- Implementar o algoritmo e analisar sua complexidade.<br>- Comparar com métodos como Insertion Sort e Selection Sort. | Python/Java, algoritmos de ordenação | [Notebook](Semana_02_(ED2).ipynb) |
| **3**  | **Ǫuick Sort** <br> **Descrição:** Estudo do Ǫuick Sort, destacando a escolha de pivô, métodos de partição e otimizações, com análise de casos extremos e comparações com o Merge Sort. | - Entender a lógica de partição e a influência da escolha do pivô.<br>- Otimizar o algoritmo para evitar o pior caso.<br>- Comparar uso de memória e velocidade com o Merge Sort. | Python/Java, análises comparativas | [Notebook](Semana_03_(ED2).ipynb) |
| **4**  | **Listas Simples (Encadeadas)** <br> **Descrição:** Introdução à estrutura de listas encadeadas, com a implementação das operações básicas (inserção, remoção, busca) e discussão das vantagens em relação aos arrays. | - Construir e manipular listas simples.<br>- Compreender cenários onde listas encadeadas são mais apropriadas que arrays.<br>- Explorar inserção e remoção em diferentes posições. | Python/Java, estrutura de dados | [Notebook](Semana_04_(ED2).ipynb) |
| **5**  | **Listas Duplamente Encadeadas** <br> **Descrição:** Expansão do conceito de lista encadeada, permitindo operações bidirecionais, com foco em aplicações como histórico de navegação e caches. | - Implementar nós com referências para próximo e anterior.<br>- Facilitar operações de remoção no meio da lista.<br>- Analisar cenários práticos de uso. | Python/Java, manipulação de ponteiros | [Notebook](Semana_05_(ED2).ipynb) |
| **6**  | **Listas Circulares + Operações Avançadas** <br> **Descrição:** Implementação de listas circulares (simples e duplas) e operações avançadas, como inversão, detecção/correção de ciclos e concatenação, aplicáveis em buffers e escalonamento de processos. | - Construir listas circulares e compreender a estrutura “volta ao início”.<br>- Implementar rotinas de inversão de listas.<br>- Detectar e corrigir ciclos (ex: algoritmo de Floyd).<br>- Praticar concatenação e ordenação in-place. | Python/Java, algoritmos avançados em listas | [Notebook](Semana_06_(ED2).ipynb) |
| **7**  | **Revisão Geral (Semanas 1–6)** <br> **Descrição:** Recapitulação dos principais conceitos de complexidade, ordenação e estruturas de listas, com exercícios de fixação e resolução de dúvidas. | - Reforçar tópicos-chave de análise de algoritmos e ordenação.<br>- Revisitar a implementação de listas encadeadas em suas variantes.<br>- Revisar técnicas de otimização e operações avançadas. | Exercícios práticos, revisão teórica | Apostila, Notebooks |
| **8**  | **Prova 1** <br> **Avaliação:** Conteúdo das semanas 1–6, incluindo teoria e resolução de problemas práticos. | - Avaliar o domínio dos conceitos de complexidade, algoritmos de ordenação e manipulação de listas. | Prova teórica e prática | [Prova 1](Prova_1_Semana_08_(ED2).pdf) |
| **9**  | **Seminário 1 - Hashing** <br> **Quarta:** Grupos 1 (Fundamentos/Funções) e 2 (Colisões/Encadeamento). <br> **Sexta:** Grupos 3 (End. Aberto) e 4 (Análise/Aplicações). | Abordagem completa de Hashing via apresentações autogeridas pelos alunos. | Apresentação, debates, pesquisa | [Orientações](Seminário1.pdf) |
| **10** | **Projeto 1 - HashTablePy** <br> Implementar Tabela Hash em Python com Encadeamento Separado para colisões.	| - Construir uma classe HashTable funcional (put, get, delete). <br> - Compreender na prática hashing e tratamento de colisões.	| Python 3, Listas (list), Classes, Função Hash (hash(), %), Encadeamento Separado. | [Orientações](Semana_10_(ED2).pdf) |
| **11** | **Conceitos Básicos de Árvores** <br> **Descrição:** Introdução aos conceitos fundamentais de árvores (raiz, folhas, altura e níveis) e aos percursos básicos (pré-ordem, em-ordem, pós-ordem) utilizando exemplos de árvores binárias. | - Compreender a terminologia e representação de árvores.<br>- Implementar percursos básicos para manipulação e exibição de dados.<br>- Identificar cenários onde árvores são preferíveis a listas. | Python/Java, algoritmos de percurso | Apostila, Notebooks |
| **12** | **Árvores Binárias de Busca (BST)** <br> **Descrição:** Estudo aprofundado das BSTs, com ênfase em inserção, remoção e busca ordenada, e discussão sobre problemas de desbalanceamento. | - Construir e manipular BSTs para ordenação e busca.<br>- Reconhecer os desafios de chaves ordenadas (ex: árvores degeneradas).<br>- Preparar o estudo de soluções de balanceamento. | Python/Java, algoritmos de busca | Apostila, Notebooks |
| **13** | **Árvores AVL** <br> **Descrição:** Introdução ao balanceamento de árvores com rotações simples e duplas, comparando o desempenho entre BSTs simples e árvores AVL. | - Implementar rotações para manter a árvore balanceada.<br>- Analisar o impacto do balanceamento na eficiência das operações.<br>- Entender aplicações em sistemas críticos e bancos de dados. | Python/Java, algoritmos de rotação | Apostila, Notebooks |
| **14** | **B-Trees e Heaps** <br> **Descrição:** Apresentação das B-Trees, focando em armazenamento em disco e alta capacidade de nós, além da introdução dos Heaps para uso em filas de prioridade e no Heap Sort. | - Conhecer e implementar B-Trees.<br>- Aplicar Heaps em algoritmos de fila de prioridade.<br>- Comparar a aplicabilidade de B-Trees e Heaps em diferentes contextos. | Python/Java, estruturas de dados avançadas | Apostila, Notebooks |
| **15** | **Grafos – Conceitos e Primeiros Algoritmos (BFS/DFS)** <br> **Descrição:** Introdução aos conceitos de grafos (vértices, arestas, direcionados e não direcionados), com representação por matrizes ou listas de adjacência e estudo dos algoritmos de busca em largura (BFS) e profundidade (DFS). | - Diferenciar formas de representação de grafos.<br>- Implementar BFS e DFS para exploração de nós.<br>- Analisar complexidade e aplicações práticas (ex: redes de computadores, modelagem de relacionamentos). | Python/Java, algoritmos de busca | Apostila, Notebooks |
| **16** | **Caminhos Mínimos** <br> **Descrição:** Estudo dos algoritmos para encontrar trajetos de custo mínimo, incluindo Dijkstra (para pesos positivos) e Bellman-Ford (para pesos negativos), além de discussão sobre outras abordagens (ex: Floyd-Warshall). | - Compreender as diferenças entre os algoritmos de caminho mínimo.<br>- Implementar Dijkstra e Bellman-Ford em cenários práticos.<br>- Discutir limitações e extensões dos algoritmos. | Python/Java, algoritmos de caminhos | Apostila, Notebooks |
| **17** | **Revisão Geral (Semanas 11–16)** <br> **Descrição:** Recapitulação dos principais conceitos relacionados a árvores (BST, AVL, B-Trees, Heaps) e grafos (representações, BFS, DFS, caminhos mínimos), com resolução de exercícios e esclarecimento de dúvidas. | - Reforçar tópicos de árvores e grafos.<br>- Consolidar o entendimento através de exemplos práticos.<br>- Revisar aplicações reais das estruturas estudadas. | Exercícios práticos, revisão teórica | Apostila, Notebooks |
| **18** | **Prova 2** <br> **Avaliação:** Conteúdo das semanas 11–16, abordando tanto os aspectos teóricos quanto a aplicação prática de problemas envolvendo árvores e grafos. | - Avaliar o domínio dos conceitos de árvores e grafos.<br>- Testar a capacidade de implementar e otimizar essas estruturas. | Prova teórica e prática | Material de apoio disponibilizado |
| **19** | **Seminário 2** <br> **Temas Sugeridos:** <br>- "Árvores AVL em Bancos de Dados"<br>- "Grafos em Sistemas de Navegação (ex: GPS)" | - Discutir pesquisas e aplicações empresariais envolvendo árvores e grafos.<br>- Apresentar estudos de caso e desafios de implementação. | Apresentação, debates, pesquisa | Apostila, Notebooks |
| **20** | **Projeto 2** <br> **Tema:** Desenvolvimento de um sistema de recomendação (ou outra aplicação integradora) que utilize grafos (ex: conexões entre usuários) e tabelas de hash para armazenamento eficiente. | - Integrar conceitos de árvores, grafos e hashing em um projeto final.<br>- Demonstrar a capacidade de criar soluções otimizadas para problemas reais. | Projeto prático, desenvolvimento de código | Apostila, Notebooks |

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
