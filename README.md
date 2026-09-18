# ADS — Slides de Aula

Repositorio de slides interativos para o curso de **Analise e Desenvolvimento de Sistemas** da FAMAC / Unopar.

## Acesso

Abra o [`index.html`](index.html) no navegador ou acesse via GitHub Pages.

## Estrutura

```
index.html                                         # Pagina inicial (hub de navegacao)
poll.html                                          # Pagina de votacao ao vivo (alunos)
Unidade1_Seguranca_Informacao_Slides.html          # Slides da Unidade 1 (Seg. Auditoria)
Unidade2_Politica_Cultura_Seguranca_Slides.html    # Slides da Unidade 2 (Seg. Auditoria)
Unidade3_Componentes_Computador_Slides.html        # Slides da Unidade 3 (Arq. Computadores)
Unidade4_Algebra_Booleana_Slides.html              # Slides da Unidade 4 (Arq. Computadores)
Unidade1_Interface_Usabilidade_Slides.html         # Slides da Unidade 1 (Interface e Usabilidade)
Unidade1_Introducao_Linguagem_Python_Slides.html   # Slides da Unidade 1 (Linguagem de Programacao)
Unidade2_Explorando_Recursos_Python_Slides.html    # Slides da Unidade 2 (Linguagem de Programacao)
Unidade3_Introducao_Analise_Dados_Python_Slides.html # Slides da Unidade 3 (Linguagem de Programacao)
assets/                                            # Logos e imagens
```

## Disciplinas

### Arquitetura e Organizacao de Computadores

| Unidade | Tema | Slides |
|---------|------|--------|
| 3 | Componentes Basicos de um Computador | 39 |
| 4 | Algebra Booleana e Logica Digital | 26 |

### Seguranca e Auditoria de Sistemas

| Unidade | Tema | Slides |
|---------|------|--------|
| 1 | Seguranca da Informacao | 26 |
| 2 | Politica e Cultura de Seguranca | 28 |

**Conteudo da Unidade 3:**

- **Aula 1** — CPU: organizacao, registradores, barramentos, clock, CISC vs RISC, ciclo de instrucao
- **Aula 2** — Memoria Principal e Cache: hierarquia, RAM, ROM, SRAM vs DRAM, niveis e mapeamento de cache
- **Aula 3** — Memoria Secundaria: disco magnetico, HDD vs SSD, Flash, midias opticas, padroes de interface
- **Aula 4** — Dispositivos de E/S: perifericos, E/S programada, interrupcao, DMA, canais de E/S

**Conteudo da Unidade 4:**

- **Fundamentos** — Algebra booleana, variaveis binarias, operacoes AND, OR, NOT
- **Tabelas Verdade** — Tabelas para AND, OR, NOT com exemplos praticos
- **Portas Logicas** — NAND, XOR, NOR, XNOR, portas universais e simplificacao de circuitos
- **Propriedades** — Comutatividade, associatividade, distributividade, De Morgan
- **Exercicio Pratico** — Projeto de seguranca residencial com sensores + simulador interativo

**Conteudo da Unidade 1 (Seguranca):**

- **Fundamentos** — Principios CID, autenticidade, nao repudio, legalidade e ativos
- **Riscos e Controles** — Mapeamento, matriz de riscos e contramedidas
- **Seguranca de Redes** — Vulnerabilidades, ataques e protecao em camadas
- **Criptografia** — Historia, tecnicas principais e aplicacoes
- **Estudo de Caso** — Maximus Financeira (cenario e solucao)

**Conteudo da Unidade 2 (Seguranca):**

- **Aula 1** — SGSI, PSI, ciclo PDCA, aspectos fisico/humano/natural, familia ISO 27000 e LGPD
- **Aula 2** — Cultura de seguranca, desenvolvimento seguro, etica, aspectos legais, tendencias (IA, Quantica, Blockchain, 5G/IoT) e ameacas emergentes
- **Aula 3** — Modelos de controle de acesso (DAC, MAC, RBAC, ABAC), autenticacao, MFA/2FA, biometria e IAM

### Interface e Usabilidade

| Unidade | Tema | Slides |
|---------|------|--------|
| 1 | Fundamentos de Interface e Usabilidade | 31 |

**Conteudo da Unidade 1 (Interface e Usabilidade):**

- **Aula 1** — Introducao ao DCU: historia da usabilidade, linha do tempo interativa, beneficios e atividade pratica
- **Aula 2** — Usabilidade e UX: dimensoes da usabilidade, simulador de jornada do usuario, componentes de interface, ciclo PCU
- **Aula 3** — Ergonomia e Design: ergonomia cognitiva, affordances (quiz interativo), ISO 25010, usabilidade como qualidade
- **Aula 4** — Heuristicas de Nielsen: 10 heuristicas com flash cards, principios Gestalt, atividade de analise
- **Enquete ao Vivo** — QR code para votacao em tempo real com grafico de resultados (Firebase ou modo demo)
- **`poll.html`** — Pagina mobile-first para os alunos votarem; suporta Firebase REST API e previne duplo voto (localStorage)

### Linguagem de Programacao

| Unidade | Tema | Slides |
|---------|------|--------|
| 1 | Introducao a Linguagem Python | 34 |
| 2 | Explorando Recursos do Python | 35 |
| 3 | Introducao a Analise de Dados com Python | 34 |

**Conteudo da Unidade 1 (Linguagem de Programacao):**

- **Aula 1** — A linguagem Python: historia, ferramentas e interpretadores (PyCharm, VSCode, Anaconda/Jupyter, Google Colab), variaveis, tipos de dados, entrada/saida e formatacao com f-string
- **Aula 2** — Estruturas condicionais: operadores relacionais, operadores logicos (and, or, not) e estruturas if, elif e else
- **Aula 3** — Estruturas de repeticao: for, while, a funcao range() e controle de fluxo com break e continue
- **Aula 4** — Funcoes em Python: funcoes built-in, funcoes definidas pelo usuario (parametros e retorno) e expressoes lambda
- **Encerramento** — Assimile (infografico-resumo), estudo de caso integrador (calculadora de desconto) e referencias

**Conteudo da Unidade 2 (Linguagem de Programacao):**

- **Aula 1** — Estruturas de dados I: sequencias, strings, listas, list comprehensions e as funcoes map() e filter()
- **Aula 2** — Estruturas de dados II: conjuntos (set), dicionarios (dict) e arrays da biblioteca NumPy
- **Aula 3** — Classes e metodos: orientacao a objetos, criacao de classes, atributos, metodos e heranca
- **Aula 4** — Bibliotecas e modulos: modulos built-in, de terceiros e proprios, e a biblioteca Matplotlib
- **Encerramento** — Assimile, estudo de caso integrador (catalogacao de livros) e referencias

**Conteudo da Unidade 3 (Linguagem de Programacao):**

- **Aula 1** — Aplicacao de banco de dados com Python: SQL (DDL/DML/DCL), conexao com SGBD e o modelo CRUD com sqlite3
- **Aula 2** — Introducao a biblioteca pandas: DataFrames, Series e leitura de dados estruturados (read_html)
- **Aula 3** — Manipulacao de dados em pandas: metodos de leitura/escrita, captura, transformacao e extracao de informacoes
- **Aula 4** — Visualizacao de dados: Matplotlib, o metodo plot() do pandas e a biblioteca Seaborn
- **Encerramento** — Assimile, estudo de caso integrador (cadastro de funcionarios em SQLite) e referencias

## Tutor

**Joao Batista** — Eng. de Software
`joao@famac.com.br`

## Tecnologias

- HTML/CSS/JS puro (sem frameworks)
- Fontes: [Outfit](https://fonts.google.com/specimen/Outfit) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
- Navegacao por teclado, touch e indice lateral (TOC)
