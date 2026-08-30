[README.txt](https://github.com/user-attachments/files/31621577/README.txt)
<div align="center">
  <h1>Curso Avançado de Python</h1>
  <p><strong>Material de estudo e códigos desenvolvidos com base no curso da Hashtag Treinamentos.</strong></p>
</div>

<br>

## Sobre o Repositório

Bem-vindo ao repositório de Python do [N3ylim](https://github.com/N3ylim). Este espaço foi estruturado para organizar os códigos, exercícios e materiais de estudo obtidos através do curso avançado de Python da **Hashtag Treinamentos**. O objetivo é documentar a jornada de aprendizado e fornecer exemplos práticos cobrindo conceitos de alto nível da linguagem.

---

## Índice

- [Sobre o Repositório](#sobre-o-repositório)
- [Módulos do Curso](#módulos-do-curso)
- [Estrutura de Diretórios](#estrutura-de-diretórios)
- [Como Utilizar](#como-utilizar)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Licença](#licença)

---

## Módulos do Curso

O conteúdo aborda diversos tópicos avançados estudados ao longo das aulas da Hashtag Treinamentos:

### 1. Orientação a Objetos Avançada
* Herança múltipla e Method Resolution Order (MRO)
* `Magic Methods` (Dunder methods) e sobrecarga de operadores
* Metaclasses e tipagem dinâmica
* Encapsulamento avançado (`property`, getters e setters)

### 2. Programação Funcional e Decoradores
* Expressões Lambda, `map`, `filter` e `reduce`
* Closures e funções de alta ordem
* Criação de Decoradores (com e sem argumentos)
* Utilização de `itertools` e `functools`

### 3. Iteradores e Geradores
* O protocolo de Iteração (`__iter__` e `__next__`)
* Funções geradoras com `yield` e `yield from`
* Expressões geradoras para otimização de memória

### 4. Concorrência e Paralelismo
* Diferença entre Threads, Processos e Asyncio
* Multithreading (`threading`) para tarefas I/O Bound
* Multiprocessing (`multiprocessing`) para tarefas CPU Bound
* Programação Assíncrona com `asyncio`

### 5. Design Patterns
* Padrões de Criação (Singleton, Factory)
* Padrões Estruturais e Comportamentais aplicados em Python

### 6. Testes e Qualidade de Código
* Testes unitários utilizando `pytest`
* Utilização de Mocks
* Type Hinting avançado para checagem estática

---

## Estrutura de Diretórios

Organização básica dos arquivos do repositório:

```text
📁 Python/
│
├── 📂 01_oop_avancada/           # Códigos e anotações do módulo de OOP
├── 📂 02_decoradores/            # Exemplos de programação funcional
├── 📂 03_geradores_iteradores/   # Scripts de otimização de memória
├── 📂 04_concorrencia/           # Exemplos com asyncio e multithreading
├── 📂 05_design_patterns/        # Padrões de projeto implementados
├── 📂 06_testes/                 # Casos de teste com Pytest
│
├── 📄 requirements.txt           # Dependências do projeto
└── 📄 README.md                  # Documentação principal
```

---

## Como Utilizar

### Pré-requisitos
* Python 3.10+ instalado.
* Gerenciador de pacotes `pip`.

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/N3ylim/Python.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd Python
   ```

3. **Crie e ative um ambiente virtual:**
   ```bash
   # Linux/macOS
   python3 -m venv venv
   source venv/bin/activate

   # Windows
   python -m venv venv
   venv\Scriptsctivate
   ```

4. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

---

## Tecnologias Utilizadas

Principais ferramentas e bibliotecas abordadas no material:
* [Pytest](https://docs.pytest.org/)
* [Asyncio](https://docs.python.org/3/library/asyncio.html)

---

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

<div align="center">
  <small>Conteúdo baseado nas aulas da Hashtag Treinamentos | Desenvolvido por <a href="https://github.com/N3ylim">N3ylim</a></small>
</div>
