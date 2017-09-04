# Laços

## While

```
1. Iniciar variável de controle (VC)
2. Enquanto (teste com VC) faça
  início
    3. Bloco do enquanto
    4. Atualização da VC
  fim
```

Exemplo 1 em Python:
```python
i = 1
while i<=100:
  print(i, end=' ')
  i += 1
```
Exemplo 2 em Python:
```python
k = int(input('Limite: '))
i = 2
while i<= k:
  print(i, end=' ')
  i += 2
```

Exemplo 3 em Python:
```python
menu = '''

  Sistema de Cadastro de Estudantes
  =================================

     1. Adicionar
     2. Excluir
     3. Listar
     4. Pesquisar
     5. Sair

    Entre com sua opção: '''

op = int(input(menu))

while op != 5:
    print('Opção escolhida:', op)
    op = int(input(menu))
```

## Para

```python
for cidade in 'Parnamirim', 'Goianinha', 'Macaíba':
  print(cidade)
```

```python
# Obs.: Favor consultar as siglas corretas.
for sigla,cidade in ('PAR', 'Parnamirim'), ('GHA', 'Goianinha'), ('MAC', 'Macaíba'):
  print(sigla, cidade)
```

* `var`: identificador de sua variável
* `vf`: valor final
* `vi`: valor inicial
* `passo`: valor que incrementará o valor inicial (vi)

for var in range(vf+1):
```python
```

for var in range(vi, vf+1):
```python
```
for var in range(vi, vf+1, passo):
```python
```



  
