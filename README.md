# FIA - Introdução ao Big Data

Fiz o versionamento dos Notebooks feitos em Jupyter, Apostila do Curso em PDF.

Abaixo um resumo do que esta na apostila e no aprendizado do curso.


## Tema da Aula: Introdução ao Python

### Prof.: Dino Magri

## Introdução

## História do Python

## Por que utilizar Python ?

## Por que Python para Big Data ?

* Qualidade de Software
* Produtividade no desenvolvimento
* Bibliotecas Incluídas
* Roda em diversas plataformas

## Cases de Sucesso

## Instalação

## Como conversar com Python?

* Modo Interativo
* Modo Editor

## IDE

* Nuvem: Google Colab, Jupyter, DataBricks
* Local: IDLE, PyCharm

## Objetos Pythônicos

* Escalar - não podem ser subdivididos
* Não-escalar - tem uma estrutura interna que pode ser acessada.

### Objeto Escalar

* Int, float, bool, None.

None - ausência de valor.

Função Interna do Python ** type ** retorna um tipo de um objeto.
>>> type(3)
<type 'int'>
>>> type(3.0)
<type 'float'>

### Objeto Não-Escalar

'abc'

### Conteúdo Programático do Curso

* A identação é obrigatória
* Identificadores e atribuições
* Expressões: + - * / % **
* Operadores Condicionais: > >=  < <= == !=
* Operadores Lógicos: not, and e or
* Bibliotecas de terceiros: import minhas_funcoes as mf
* Strings e Listas
* Indexar Strings e Fatiar.
* Tuplas e Dicionários
* Estruturas de Controle (If, elif, else) e Repetição (For, While, break)


# Documentação Python

* [Fonte](https://docs.python.org/2/faq/general.html#why-is-it-called-python)
* [Pypi](https://pypi.org/): Encontre, instale e publique pacotes Python co o Python Package Index.
* [Cases de Sucesso](https://www.botreetechnologies.com/blog/top-10-python-use-cases-and-applications)
* [Python](https://www.python.org/)
* [Library](https://docs.python.org/3/library/)
* [String Methods](https://docs.python.org/3/library/stdtypes.html#string-methods)
* [Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
* [Tuples](https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences)
* [Dictionaries](https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences)
* [Referências de Links Utilizados](http://urls.dinomagri.com/refs
* [Material de Apoio](https://pt.slideshare.net/marcelobarrosalmeida/python-para-desenvolvedores-material-apoio-parte-i)


# Exemplos de IDEs:

* IDLE (já vem junto instaldo com o Python")
* Sublime Text: [Sublime Text](http://www.sublimetext.com/)
* Ninja IDE: [Ninja IDE](https://ninja-ide.org/)
* PyCharm: [PyCharm](https://www.jetbrains.com/pycharm/)
* Jupyter: [Jupyter] (http://jupyter.org/).

```

$ pip install jupyter

```

O Jupyter é aberto um servidor via prompt de comando e utilizado em um Browser.

```

$ cd  estudo\cursopythondino

$ jupyter notebook

```

[Jupyter] (http://localhost:8888/notebooks/).

O Jupyter não consegue navegar por pastas, a pasta que ele vai mostrar é a corrente.

# Strings

* Indexar (index) e fatiar (slice) strings.
![Indexar (index) e fatiar (slice) strings.](/imagens/IndexarStrings.jpg "IndexarStrings.jpg")

# Tuplas

* Tuplas constroem grupos simples de objetos.
* Elas trabalham exatamente como listas, exceto que tuplas não podem ser modificadas (são imutáveis) e são normalmente escritas como uam série de itens entre parênteses, não entre colchetes.
* Os itens das tuplas são acessados via índice.
* ** Não suporta operações de alteração.
* Pode se criar uma tupla vazia (mesmo sem ter sentido): t1 = ()
* t2 = (1,)
* numeros = (1, 2, 3, 4, 5, 6)
* Podemos concatenar tuplas
* Podemos multiplicar seus valores
* POdemos indexar e fatiar tuplas.

# Dicionários

* É uma coleção de elementos onde é possível utilizar um índice de qualquer tipo imutável.
* Dicionários são indexados por chaves (keys), que podem ser de qualquer tipo imutável (strings e números).
* O dicionário é um conjunto de chave : valor (key : value) não ordenado, com o requerimento que a chave deve ser única.
	* chave é o índice
	* valor é a informação correspondente a chave.
	* { } é utilizado para iniciar um dicionário vazio.
	* : separa os pares índice-valor por vírgula.





