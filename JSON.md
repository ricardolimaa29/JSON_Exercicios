# 🧪 Exercícios de JSON com Python

Neste módulo, vamos praticar a manipulação de dados no formato JSON usando Python. Você verá como converter entre strings JSON e dicionários Python com `json.loads()` e `json.dumps()`.

---

## 📘 Exercício 1 — Convertendo JSON para dicionário

### Enunciado:

Dado o seguinte código:

```python
import json

dados_json = '{"produto":"Caderno", "preco": 12.5, "estoque": 30}'
```
Tarefa:
1. Converta a string dados_json em um dicionário Python.
2. Acesse e imprima o nome do produto e o valor do preço com a seguinte saída:
Saída esperada:
  Produto: Caderno
  Preço: 12.5

## 📘 Exercício 2 — Convertendo dicionário para JSON (json.dumps)
### Enunciado:
Você tem o seguinte dicionário Python:
```
import json

aluno = {
    "nome": "Lucas",
    "idade": 16,
    "aprovado": True
}
```
Tarefa:
1. Converta o dicionário aluno para uma string JSON usando json.dumps().
2. Imprima o resultado na tela.

Saída esperada:
    {"nome": "Lucas", "idade": 16, "aprovado": true}


## 📘 Exercício 3 — Salvando um dicionário JSON formatado (indentado)
### Enunciado:
Você possui o seguinte dicionário:
```
dados = {
    "filme": "Matrix",
    "ano": 1999,
    "genero": "Ficção Científica"
}
```
Tarefa:

1.Converta esse dicionário para uma string JSON formatada com indentação de 4 espaços.

2.Imprima o JSON formatado.

Saída esperada:
```
{
    "filme": "Matrix",
    "ano": 1999,
    "genero": "Ficção Científica"
}
```

### 💡 Dica: use json.dumps(dados, indent=4)
