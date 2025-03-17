# Projeto Herança Múltipla, Modelos e Mutable Sequence

## Descrição
Este projeto explora conceitos importantes de programação orientada a objetos em Python, como **herança múltipla**, **modelos de objetos**, **sequências mutáveis personalizadas**, além de demonstrar a utilização de propriedades e encapsulamento de dados.

## Estrutura do Projeto

```
Projeto-Heranca-Modelos/
│── heranca_multipla.py   # Demonstração de herança múltipla e sobrescrita de métodos
│── modelos.py            # Exemplos de modelos e objetos
│── testeAbc.py           # Implementação de MutableSequence
│── README.md             # Documentação do projeto
```

## Arquivos e Funcionalidades

### 📌 `heranca_multipla.py` (Herança Múltipla e Sobrescrita de Métodos)
Este arquivo demonstra como implementar herança múltipla em Python, permitindo que uma classe herde de várias outras. Também mostra a sobrescrita de métodos em classes filhas.

**Funcionalidades:**
- **Herança múltipla** entre as classes `Funcionario`, `Caelum`, `Alura`, `Hipster`, `Junior`, `Pleno`.
- **Sobrescrita de métodos** nas classes filhas.
- Demonstra a relação entre classes e como o polimorfismo pode ser usado para modificar o comportamento de métodos.

---

### 📌 `modelos.py` (Modelos de Objetos e Sobrescrita de Métodos)
Este arquivo contém exemplos de classes e objetos, demonstrando como definir modelos, inicializar instâncias e modificar comportamentos através de métodos. Além disso, utiliza conceitos como **encapsulamento** e **propriedades**.

**Funcionalidades:**
- **Classe `Programa`**: Representa um programa com nome, ano e likes. Possui métodos para manipulação de likes e validação do nome do programa.
- **Classe `Filme` e `Serie`**: São subclasses de `Programa`, representando filmes e séries com suas respectivas características (duração e temporadas).
- **Classe `Playlist`**: Cria uma lista de programas e permite iteração sobre ela.

---

### 📌 `testeAbc.py` (Implementação de MutableSequence)
Este arquivo demonstra a criação de uma sequência mutável personalizada utilizando a classe abstrata `MutableSequence` da biblioteca `collections.abc`. A classe `MinhaListinhaMutavel` é criada, mas ainda não implementa os métodos necessários para funcionar corretamente.

**Funcionalidades:**
- A classe `MinhaListinhaMutavel` herda de `MutableSequence` e precisa implementar os métodos fundamentais para manipulação de itens em uma lista personalizada, como `__getitem__`, `__setitem__`, `__delitem__`, `insert()`, entre outros.

---

## Conclusão
Este projeto oferece exemplos de como utilizar conceitos fundamentais de programação orientada a objetos em Python, como **herança**, **polimorfismo**, **encapsulamento**, e **sequências mutáveis personalizadas**. Além disso, ele oferece insights sobre como trabalhar com classes e objetos, modificando comportamentos e implementando soluções flexíveis e reutilizáveis.

