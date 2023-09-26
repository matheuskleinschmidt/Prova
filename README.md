1- 
a)
Uma descrição de requisitos do usuário é um breve relato das necessidades do cliente em relação a um produto ou recurso, redigida sob a perspectiva do usuário final. Esse método é empregado no desenvolvimento ágil de software para documentar as especificações do produto e assegurar que ele satisfaça os requisitos do usuário.
Exemplos de objetivos:

Transmitir as especificações do produto à equipe de desenvolvimento e aos clientes.
Garantir a adequação do produto às necessidades do usuário.
Fomentar a colaboração entre equipes de desenvolvimento e clientes.
b)

Como um cliente, desejo a capacidade de buscar produtos por nome.
O cliente pode inserir o nome do produto na barra de pesquisa na página inicial da loja online.
O cliente pode acionar o botão "Buscar" para iniciar a pesquisa.
Os resultados da pesquisa podem ser apresentados em uma lista, incluindo o nome do produto, uma imagem, preço e uma breve descrição.

c)

História de usuário 1:

Como um cliente, quero ser capaz de filtrar produtos por categoria para encontrar itens relacionados aos meus interesses.

Critérios de aceitação:

O cliente deve ter a opção de selecionar uma categoria de produto na barra de pesquisa.
Os resultados da pesquisa devem ser exibidos em uma lista, ordenados por relevância.
O cliente deve ser capaz de clicar em um resultado para visualizar informações detalhadas sobre o produto.

História de usuário 2:

Como um cliente, desejo poder filtrar produtos por faixa de preço para encontrar itens que se encaixem no meu orçamento.

Critérios de aceitação:

O cliente deve ter a opção de selecionar uma faixa de preço na barra de pesquisa.
Os resultados da pesquisa devem ser exibidos em uma lista, ordenados por preço.
O cliente deve ser capaz de clicar em um resultado para visualizar informações detalhadas sobre o produto.
Essas duas histórias de usuário agregam funcionalidades adicionais à busca básica por nome. A primeira história de usuário permite que os clientes filtrem produtos por categoria, o que pode ser útil para encontrar itens relacionados aos seus interesses. A segunda história de usuário permite que os clientes filtrem produtos por faixa de preço, o que pode ser útil para encontrar itens dentro de seu orçamento.

História de usuário 1:

O cliente pode selecionar uma categoria de produto na barra de pesquisa na página inicial da loja online.
O cliente pode acionar o botão "Buscar" para iniciar a pesquisa.
Os resultados da pesquisa podem ser apresentados em uma lista, incluindo o nome do produto, uma imagem, preço e uma breve descrição.

História de usuário 2:

O cliente pode selecionar uma faixa de preço na barra de pesquisa na página inicial da loja online.
O cliente pode acionar o botão "Buscar" para iniciar a pesquisa.
Os resultados da pesquisa podem ser apresentados em uma lista, incluindo o nome do produto, uma imagem, preço e uma breve descrição.

d)

História de usuário:
O relatório deve conter informações sobre vendas de todos os produtos vendidos durante o mês.
O relatório deve ser gerado automaticamente no final de cada mês.
O relatório deve ser exportável para formatos de arquivo comuns, como PDF, CSV e Excel.
O relatório deve ser categorizado por produto, categoria e região.
O relatório deve incluir informações de vendas, como quantidade vendida, receita e margem de lucro.


Esses critérios de aceitação garantem que o relatório de vendas atenda às necessidades do gerente de vendas. Eles são específicos, mensuráveis, alcançáveis, relevantes e limitados no tempo.

Os dados de vendas podem ser obtidos de um banco de dados de vendas.
O relatório pode ser personalizado para atender às necessidades específicas do gerente de vendas.
O relatório pode ser gerado usando uma ferramenta de análise de dados.

A implementação dos critérios de aceitação dependerá dos requisitos particulares do sistema de vendas.

O relatório deve ser visualmente atrativo.
O relatório deve ser protegido contra acesso não autorizado.
O relatório deve ser de fácil compreensão e interpretação.

2)

a)
```python
def test_empty_string():
    s = ""
    expected = ""
    actual = string_invert(s)
    assert expected == actual
```
b)
```python
def test_single_character_string():
    s = "a"
    expected = "a"
    actual = string_invert(s)
    assert expected == actual
```
c)
```python
def test_multiple_character_string():
    s = "hello"
    expected = "olleh"
    actual = string_invert(s)
    assert expected == actual
```
3-a)

```python
def contarCaracteres(str):
    quantidade_de_caracteres = 0
    for caractere in str:
        quantidade_de_caracteres += 1
    return quantidade_de_caracteres
```

Essa função funciona iterando sobre a string “str” e contando o número de caracteres.



b)
```python
def test_contarCaracteres_stringVazia():
    str = ""
    resultado = contarCaracteres(str)
    assert resultado == 0
```
Esse teste verifica se a função retorna 0 para uma string vazia.
