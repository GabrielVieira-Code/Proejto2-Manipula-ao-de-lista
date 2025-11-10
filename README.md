Claro! Aqui está o **README.md completo**, formatado e pronto para você copiar e colar direto no seu repositório GitHub 👇

---

# 🧾 Projeto de Manipulação de Listas em Python

## 📘 Descrição

Este projeto tem como objetivo **praticar operações básicas de manipulação de listas em Python**, como **adição, inserção, remoção e armazenamento de elementos**.
A atividade parte de uma lista inicial e, através de etapas simples, demonstra como modificar seu conteúdo dinamicamente.

---

## 🎯 Objetivo

Trabalhar os conceitos fundamentais de **listas (arrays)** em Python, compreendendo:

* Como adicionar novos elementos.
* Como inserir valores em posições específicas.
* Como remover itens pelo valor.
* Como capturar e armazenar o último elemento de uma lista.

---

## 💡 Enunciado

Dada a lista inicial:

```python
lista = [10, 20, 30, 40, 50]
```

Realize as seguintes operações:

1. **Adicione** `60` no final da lista.
2. **Insira** `15` na posição `1`.
3. **Remova** o elemento `30`.
4. **Remova o último elemento** e **guarde-o** em uma variável.

---

## 🧮 Solução em Python

```python
# Lista inicial
lista = [10, 20, 30, 40, 50]

# 1. Adiciona 60 no final
lista.append(60)

# 2. Insere 15 na posição 1
lista.insert(1, 15)

# 3. Remove o elemento 30
lista.remove(30)

# 4. Remove o último elemento e guarda em uma variável
ultimo = lista.pop()

# Exibe os resultados
print("Lista final:", lista)
print("Elemento removido:", ultimo)
```

---

## 🧠 Resultado Esperado

```bash
Lista final: [10, 15, 20, 40, 50]
Elemento removido: 60
```

---

## 🧩 O que você aprendeu

* Uso de `append()` para adicionar elementos ao final da lista.
* Uso de `insert(posição, valor)` para inserir em um índice específico.
* Uso de `remove(valor)` para excluir um elemento pelo conteúdo.
* Uso de `pop()` para remover e retornar o último item da lista.

---

## 🏁 Conclusão

Este exercício reforça o entendimento de como **listas são estruturas dinâmicas** em Python, permitindo **inserir, remover e acessar elementos facilmente**.
É uma base essencial para trabalhar com **estruturas de dados mais complexas** em projetos maiores.

---

## ✍️ Autor


**🧠 Linguagem:** Python

---
