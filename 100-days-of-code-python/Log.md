# 100 Days Of Code Python - Log

### Dia 0: 15 de novembro de 2021

**Progresso do dia:** 

Revisei os cursos concluídos da formação (Python3 - Parte 1 e 2) e dei continuidade na aula 03 do curso Python3 Introdução a Orientação a Objetos.

**Aprendizados:** 

Python3 parte 1

Nesse curso revi os conceitos iniciais da programação: instalar e rodar um projeto por meio de uma IDE, utilizar a função ```print```, trabalhar com variáveis e tipo de dados. Avançando nos principais temas da programação: comparação de tipos e diferenças da linguagem nas versões 2 e 3. Testando valores com as condicionais. Utilização de laço de repetição e iteradores. Importação de módulos (bibliotecas) e funções ```built-in``` (biblioteca padrão). Analisando diferenças entre interpretadores e compiladores.


Python3 parte 2

Nesse curso aperfeiçoei o conhecimento fundamental na linguagem Python. Trabalhei na prática a manipulação dos dados, comparando e iterando em laços. Aprendi nova estrutura de dados: Coleções (Listas, Tuplas e um pouco de Set (lista que não permite elementos duplicados) e Dicionários). Aprendi também a realizar leitura e escrita em arquivo.


Python3 Introdução a OO

Na aula 01 foi revisado os temas Dicionários, Funções e Encapsulamento. Foi explanada as motivações para a abordagem OO e a diferença entre o paradigma procedural.

Na aula 02 foram apresentados: classes, objetos, função construtora, endereços e referência de objetos, atributos de classe e como acessá-los por meio dos objetos e pela referência ```self```.

Na aula 03 foi explanado o que é e como criar métodos (comportamento da classe), como chamar métodos por meio dos objetos e pela referência ```self```. Foi apresentado o conceito de Garbage Colector do Python e o tipo ```None``` (valor nulo para variáveis).

**Link do trabalho:** 

1. [Python3 Parte 1: Inrodução à nova versão da linguagem - Certificado](https://cursos.alura.com.br/user/samuel-apls/course/python-3-introducao-a-nova-versao-da-linguagem/formalCertificate)
2. [Python3 Parte 2: Avançando na linguagem - Certificado](https://cursos.alura.com.br/user/samuel-apls/course/python-3-avancando-na-linguagem/formalCertificate)
3. [Python3: Introdução a Orientação a objetos - Aula 03](https://github.com/samuel-apls/alura-formacao-python/commit/f8236f818e96692bc2b48b93e2c37c8573b93b5a#diff-db236ecce453bc7f47859772cf2f6f1899d0c97e3231311db782ac0aecf47a2c)

----
### Dia 1: 16 de novembro de 2021

**Progresso do dia:** 

Estudei sobre encapsulamento, prorpiedades dos atributos da classe e coesão de código. Pratiquei no arquivo da aula 04 do curso [Python3 Introdução a Orientação a Objetos](https://cursos.alura.com.br/course/python-3-intro-orientacao-objetos).

**Aprendizados:** 

Na aula 04 foi demonstrado na prátrica o conceito de encapsulamento (pincípio de design de código, pilar da Orientação a Objetos). Foi possível observar as vantagens do uso, como por exemplo, fácil manutenção e reutilização de código, em consequência do baixo acoplamento de código. Além disso, foi demonstrada a importância da coesão no código, ou seja, os métodos de responsabilidade da Classe devem ser divididos em classes de forma que contribuam também para os benefícios do encapsulamento. Por fim, foi explando como restringir a visibilidade dos atributos. No entanto, em Python, a visibilidade dos atributos é uma convenção, onde cabe ao desenvolvedor adotar ou não as melhores práticas (a linguagem não irá impedir totalmente de um atributo privado ser acessado. Por exemplo, pode ser acessado da seguinte maneira: ```self.Classe.atributo```).

**Link do trabalho:** 

1. [Python3: Introdução a Orientação a objetos - Aula 04](https://github.com/samuel-apls/alura-formacao-python/commit/2e8fde1f52746dbbcae666fb1d70489556ecac3e)

----
### Dia 2: 17 de novembro de 2021

**Progresso do dia:** 

Estudei sobre métodos de leitura de atributos (```getters```), método de alteração de atributos (```setters```) e a como aplicar esses conceitos de manipulação de atributos utilizando ```@property```. Pratiquei no arquivo da aula 05 do curso [Python3 Introdução a Orientação a Objetos](https://cursos.alura.com.br/course/python-3-intro-orientacao-objetos).

**Aprendizados:** 

Na aula 05 foi demonstrado o uso de ```getter``` e ```setter```. Tal como na linguagem Java, é uma boa prática como estebeler padrão de design de código de acordo com a Orientação a Objeto. Foi aprosentado o uso de ```@property```, que é uma implmentação de método que se referencia diretamente ao atributo da Classe, que deve estar na condição privada, (cuja assinatura do método corresponde à mesma nomenclatura do atributo):

~~~python
@property
def nome_do_atributo(self):
    return codigo

@nome_do_atributo.setter
def nome_do_atributo(self):
    return codigo
~~~

Isso faz com que o método seja chamado sem necessáriamente apresentar os parênteses, característicos de método. Por exemplo: ```self.atributo``` para ```@property``` e ```self.atributo = valor``` para ```@nome_atributo.setter```

**Link do trabalho:** 

1. [Python3: Introdução a Orientação a objetos - Aula 05](https://github.com/samuel-apls/alura-formacao-python/commit/5c1c4d56ad552cdf43fea2ce12bd952dd7e9252d)

----
### Dia 3: 18 de novembro de 2021

**Progresso do dia:** 

Estudei sobre métodos privados e métodos estáticos (métodos da classe). Pratiquei no arquivo da aula 06 do curso [Python3 Introdução a Orientação a Objetos](https://cursos.alura.com.br/course/python-3-intro-orientacao-objetos). Finalizei o curso em questão.


**Aprendizados:** 

Na aula 06 foi a aplicabtilidade de método privado, que limita o uso à outros métodos <ins>dentro da classe<\ins>, mas a linguagem não impede de invocar o método estático diretamente pela classe. Porém, ao fazer isso, o desenvolvedor está explicitamente fugindo do padrão OO.

Foi explanado sobre a utlização de método estático (método da classe), que permite a invocação do método diretamente pelo nome da classe (sem referência). Isso serve para acessar dados que não estão explícitos como atributos da classe, mas que é uma característica da própria classe.

~~~python
@staticmethod
def nome_do_metodo():
    return codigo

>>> Classe.metodo_estatico()
~~~


**Link do trabalho:** 
1. [Python3: Introdução a Orientação a objetos - Aula 06](https://github.com/samuel-apls/alura-formacao-python/commit/be49d77e949c1d501f00130d52da03a38f2a6f00)
2. [Python3: Introdução a Orientação a objetos - Certificado](https://cursos.alura.com.br/user/samuel-apls/course/python-3-intro-orientacao-objetos/formalCertificate)

----
### Dia 4: 19 de novembro de 2021

**Progresso do dia:** 

Estudei sobre classes, atributos e métodos, revisando os principais conceitos para avançar na Orientação a Objetos. Pratiquei no arquivo da aula 01 do curso [Python 3: Avançando na orientação a objetos](https://cursos.alura.com.br/course/python-3-avancando-orientacao-objetos).


**Aprendizados:** 

Na aula 01 foi revisado o conceito de encapsulamento, demonstrando o uso de atributos (privados ou não) e métodos (```@property``` como ```getter```; e ```setter```).

Adicionamelmente foi apresentando como um atributo pode estar ligado à instância ou à classe e como pode ser acessado caso seja necessário declarar um atributo a ser compartilhado entre várias classes. De forma versátil, a linguagem permite que atributos não declarados na classe por meio do método construtor ```__init__``` possam ser criados após o objeto instanciado.

~~~python
>>> self.nome_atributo #atributo ligado à instância

>>> __class__.nome_atributo #atributo ligado à classe
~~~


**Link do trabalho:** 
1. [Python 3: Avançando na orientação a objetos - Aula 01](https://github.com/samuel-apls/alura-formacao-python/commit/33f4bfae8a6aef72fe936d24011a2a7262fe5287)

----
### Dia 5: 20 de novembro de 2021

**Progresso do dia:** 

Estudei sobre encapsulamento e herança por meio da aula 02 do curso [Python 3: Avançando na orientação a objetos](https://cursos.alura.com.br/course/python-3-avancando-orientacao-objetos).

**Aprendizados:** 

Criar classe genérica (generalização) de modo que seja possível herdar os atributos e métodos da superclasse (herança);

~~~python
class Nome_da_Classe(Superclasse)
~~~

Utilizar o construtor, reutilizando o construtor da superclasse, assim, seus atributos e métodos passarão a ficar acessíveis para a classe-filha, sem a necessidade de reescrever código;

~~~python
super().__init__(parametro1, parametro2, etc)
~~~

Criar métodos da classe (especialização): método da classe e método estático.

~~~python
#Método de classe
@classmethod
def funcao(cls):
    return cls.atributo

#cls é convencional assim como self
#Método de classe que pode ser utilizado por todoas as classes sendo permitido utilizar os atributos da classe ou da instância
~~~

~~~python
#Método estático
@staticmethod
def funcao():
    return codigo

#Método de classe que pode ser utilizado por todoas as classes, porém não sendo permitido utilizar os atributos da classe ou da instância. Nesse caso, não é necessário passar nenhum parâmetro.
~~~

**Link do trabalho:** 
1. [Python 3: Avançando na orientação a objetos - Aula 02](https://github.com/samuel-apls/alura-formacao-python/commit/56cc2474fa8e2441a934dc1f034c18685a26a01c)

----
### Dia 6: 22 de novembro de 2021

**Progresso do dia:** 
Estudei sobre polimorfismo, relacionamento "é um" e formas de apresentação textual e de representação do objeto. Capítulo 03 do curso [Python 3: Avançando na orientação a objetos](https://cursos.alura.com.br/course/python-3-avancando-orientacao-objetos).

**Aprendizados:** 

Utilizar o polimorfismo, criando a sobrescrita de método, onde o método da classe filha, que é uma especificação da classe principal ("é um"), tem a mesma assinatura do método na classe principal. Na chamada do método, prevalece a execução do método na classe filha.

Apresentar objetos como ```string```, de forma que é de responsabilidade da classe em imprimir seus atributos, encapsulando, assim, em um método que representa os objetos como ```string```.

~~~python
def __str__(self):
    return f'Atributo1: {self.atributo1} Atributo2: {self.atributo2}'

str(variavel1)
#gera saída para usuário
~~~

~~~python
def __repr__(self):
    return variavel

repr(variavel1)
#gera saída para desenvolverdor (utilizado para debug)
~~~

**Link do trabalho:**
1. [Python 3: Avançando na orientação a objetos - Aula 03](https://github.com/samuel-apls/alura-formacao-python/commit/83972f3900be4453397b172e7eff74d092f4baca)

----
### Dia 7: 23 de novembro de 2021

**Progresso do dia:** 
Herança de classe do tipo ```built-in```, suas vantagens e desvantagens. Capítulo 04 do curso [Python 3: Avançando na orientação a objetos](https://cursos.alura.com.br/course/python-3-avancando-orientacao-objetos).

**Aprendizados:** 

Utilizar a herança do tipo ```buit-in``` (pacote nativo), sendo a vantagem principal, o polimorfismo. A classe herdada é a ```List```, cujo objetivo é iterar sobre o objeto ```iterable```. A desvantagem, consiste em herdar uma classe desconhecida, podendo gerar complexidade e acoplamento ao código.

**Link do trabalho:**
1. [Python 3: Avançando na orientação a objetos - Aula 04](https://github.com/samuel-apls/alura-formacao-python/commit/6f5b1ab0b2e1a6eb9691383145e934611b48ff12)

----
### Dia 8: 24 de novembro de 2021

**Progresso do dia:** 
Duck typing, Python data model, dunder methods e uso do classe absrata com ABC (abstract base class). Capítulo 05 do curso [Python 3: Avançando na orientação a objetos](https://cursos.alura.com.br/course/python-3-avancando-orientacao-objetos).

**Aprendizados:** 
Utilizar o polimorfismo sem necessariamente herdar uma classe, mas utilizando de métodos mágicos (magic methods), que são definidos no Python Data Model. Por exemplo, têm caracteristicas de ```dunder``` (double enderscore):

~~~Python
def __getitem__(self, atributo2):
    return self._atributo1[atributo2]
~~~

Duck typing é uma forma comum em Python para se referir aos magics methods.

Em caso de necessidade que uma classe implemente métodos obrigatoriamente, basta importar o múdulo ABC, Por exemplo:

~~~Python
from collections.abc import MutableSequence

class Classe(MutableSequence):
    pass
~~~

Como Python é uma linguagem dinâmica, a obrigaroriedade de implementação vai acontecer somente em tempo de instanciação, onde o compilador irá informar quais métodos estão faltanto ser implementados:

~~~Python
objeto = Classe()
print(objeto)
~~~

**Link do trabalho:**
1. [Python 3: Avançando na orientação a objetos - Aula 05](https://github.com/samuel-apls/alura-formacao-python/commit/6f5b1ab0b2e1a6eb9691383145e934611b48ff12)

----
### Dia 9: 25 de novembro de 2021

**Progresso do dia:** 

Herança múltipla, ordem de chamada de métodos e ```Mixins```. Capítulo 06 do curso [Python 3: Avançando na orientação a objetos](https://cursos.alura.com.br/course/python-3-avancando-orientacao-objetos).

**Aprendizados:** 

Herdar múltiplas classes (herança múltipla) e entender a ordem de precedência que é conforme declaração (esquerda > direita) *, sendo separada por vírgula:

~~~Python
class Classe(Superclasse1, Superclasse2):
    pass
~~~

**Há um algoritmo no Python (```MRO - Method Resolution Order```) que define qual a melhor classe mãe a ser percorrida na busca do método a ser executado: boa cabeça (```good head```). Dependendo, pode haver uma hieráquia a mais que definirá a melhor classe para o método ser executado.*

Usar classes que podem ser herdadas mas que não precisam ser instanciadas são conhecidas como ```Mixins```. São usados desta forma pois o seu comportamento normalmente não precisa ser de responsabilidade da classe filha, pois esta é mais específica.

**Link do trabalho:**

1. [Python 3: Avançando na orientação a objetos - Aula 06](https://github.com/samuel-apls/alura-formacao-python/commit/97d19fb5ac1cd1373b28019fbe32a4abd45dd117)
2. [Python 3: Avançando na orientação a objetos - Certificado](https://cursos.alura.com.br/user/samuel-apls/course/python-3-avancando-orientacao-objetos/formalCertificate)

----
### Dia 10: 07 de dezembro de 2021

**Progresso do dia:** 

Introdução ao fatiamento (slicing) de String. Capítulo 01 do curso [String em Python: Extraindo informações de uma URL](https://cursos.alura.com.br/course/string-python-extraindo-informacoes-url).

**Aprendizados:** 

As URLs têm basicamente duas estruturas: base da URL e parâmetros da URL.

As strings são como listas, que não podem ter suas posições alteradas (imutáveis) e podem ser percorridas por posições (inciando em zero até n-1). Sendo o operador de fatiamento: ```string[indice1 : indice2]```. No ```indice1```, à esquerda, a posição é inclusiva (n+1). No ```indice2```, à direita, a posição é exclusiva (n-1).

**Link do trabalho:**

1. [String em Python: Extraindo informações de uma URL - Aula 01](https://github.com/samuel-apls/alura-formacao-python/commit/0b28b877318093cf2d41b99e4020e94404904dd7)

----
### Dia 11: 08 de dezembro de 2021

**Progresso do dia:** 

Utilizando método de String. Capítulo 02 do curso [String em Python: Extraindo informações de uma URL](https://cursos.alura.com.br/course/string-python-extraindo-informacoes-url).

**Aprendizados:** 

Omitir o primeiro ou o segundo argumento do operador de fatiamento para fatiar uma string do início até um certo índice, ou a partir de um índice até o final: ```str[a:]``` ou ```str[:b]```.

Utilizar o método ```str.find(palavra, inicio)``` para buscar o índice de palavra a partir de inicio. Caso ```palavra``` não seja encontrada, o método ```find``` retorna -1.

O método ```len(string)``` retorna o tamanho (ou seja, a quantidade de caracteres) da nossa string.

**Link do trabalho:**

1. [String em Python: Extraindo informações de uma URL - Aula 02](https://github.com/samuel-apls/alura-formacao-python/commit/f07f0b467d06f353af513fd8b148323993e10ca0)

----
### Dia 12: 09 de dezembro de 2021

**Progresso do dia:** 

Aplicação de Orientação a Objetos no projeto. Capítulo 03 do curso [String em Python: Extraindo informações de uma URL](https://cursos.alura.com.br/course/string-python-extraindo-informacoes-url).

**Aprendizados:** 

Utilizar a palavra reservada ```raise``` para lançar uma ```Excecption``` no programa, informando uma mensagem do erro.

Utilizar métodos da classe ```String```: ```str.replace``` e ```str.strip```.

Como transformar o projeto em classe com atributos e métodos.

Lidar com comparação, utilizando o operador ```not``` com diferentes tipo de valores nulos: ```None```, ```' '```, ```0```

**Link do trabalho:**

1. [String em Python: Extraindo informações de uma URL - Aula 03](https://github.com/samuel-apls/alura-formacao-python/commit/ab962ed2813251d6265db221287ee3a5fea7cf04)

----
### Dia 13: 10 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão da aula sobreexpressoões regulares. Capítulo 04 do curso [String em Python: Extraindo informações de uma URL](https://cursos.alura.com.br/course/string-python-extraindo-informacoes-url).

**Aprendizados:** 

Construir e utilizar expressoões regulares (```RegEx```) importando o módulo ```re``` do Python.

Entender o método ```search``` para o módulo ```re```: consiste em buscar um padrão dentro de uma sstring.

Entender o método ```match``` para o módulo ```re```: consiste em comparar um padrão completo de uma string.

Diferenciar o uso de ```parênteses``` e ```colchetes``` na elaboração de ```RegEx```: enquanto o ```colchetes``` especificar intervalo de caracteres que podem variar naquela expressão, os ```parênteses``` especifica uma string que não se altera.

**Link do trabalho:**

1. [String em Python: Extraindo informações de uma URL - Aula 04](https://github.com/samuel-apls/alura-formacao-python/commit/3ad68ac43d9efdd4533c842180776e1baf5bd945)

----
### Dia 14: 12 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão da aula sobre métodos especiais. Conclusão do curso. Capítulo 05 do curso [String em Python: Extraindo informações de uma URL](https://cursos.alura.com.br/course/string-python-extraindo-informacoes-url).

**Aprendizados:** 

Implementar métodos especiais nas classes para criar comportamentos dustomizados (rescrita de método):

~~~Python
__len__ #tamanho
__str__ #impressao
__eq__ #comparação
~~~

Comparar com operador ```==``` (iguadade) e ```is``` (identidade).

**Link do trabalho:**

1. [String em Python: Extraindo informações de uma URL - Aula 05](https://github.com/samuel-apls/alura-formacao-python/commit/e04e07cfd75b97c1f6253894784401d925de1ebc)
2. [String em Python: Extraindo informações de uma URL - Certificado](https://cursos.alura.com.br/user/samuel-apls/course/string-python-extraindo-informacoes-url/formalCertificate)

----
### Dia 15: 14 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão da aula sobre listas e operações: capítulo 01 do curso [Python Collections Parte 1: Listas e tuplas](https://cursos.alura.com.br/course/python-collections-listas-e-tuplas).

**Aprendizados:** 

Collections é uma biblioeta Python que permite armazenar dados em estruturas específicas e pacíveis de acesso/consulta/manipulação. ```Listas``` e ```tuplas``` são as mais comuns.

Criação de lista (```lista = [valor1, valor2, ...]```), verificação de tipo de lista (```type(lista)```) e tamanho da lista (```len(lista)```), valor conforme posição (```lista[posicao]```), alterar valores que estão dentro da lista (```lista[posicao] = valor```), adicionar valores no final da lista (```lista.append(vslor)```), inserir valores em posição específica (```lista.insert(posicao, valor)```), percorrer a lista (```for elemento in lista```), remover elemento da lista (```lista.remove(valor)```), remover todos elementos da lista (```lista.clear()```), verificar se o elemento está dentro da lista (```elemento in lista```).

Utilizar um ```list comprehension``` (sintaxe curta para criar e manipular lsitas):
~~~Python
[expressao for item in lista]
#retorna a EXPRESAO
#em cada ITEM da
#LISTA
~~~

Fazer filtragens (utilizando ```list comprehension```):
~~~Python
[expressao for elemento in lista if elemento == valor]
#executa a EXPRESSAO
#para todo ELEMENTO na
#LISTA SE CONDIÇÃO for satisfeita
~~~ 

Criar uma função e deixar um valor padrão (```def nome_da_funca (lista = None)```) e os problemas da mutabilidade, que permite que alterações sejam feitas sem que se saiba onde/quando/quem o fez, trazendo consequências imprevisiveis para o código.

**Link do trabalho:**

1. [Python Collections Parte 1: Listas e tuplas - Aula 01](https://github.com/samuel-apls/alura-formacao-python/commit/78e82de6a06aaa280510732b681be849b738e47a)

----

### Dia 16: 15 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão da aula sobre tuplas: capítulo 02 do curso [Python Collections Parte 1: Listas e tuplas](https://cursos.alura.com.br/course/python-collections-listas-e-tuplas).

**Aprendizados:** 

Lidar com referências. Listas são mutáveis, ou seja, pode haver elementos dentro de uma lista e ainda de tipos diferentes, onde a lista aceita receber novos elementos. Conceito de imutabilidade.

Tupla é um tipo de lista na qual não permite a mutação. Nesse caso, deverá ser criada uma nova tupla para agregar um novo elemento.

A diferença entre programação orientada é que, na programação funcional, trata-se de valores e funções, separando o comportamento dos dados. Já na origramação orientação objetos é evitado o comportamento "anêmico": que não tem o comportamento atrelado aos dados.

**Link do trabalho:**

1. [Python Collections Parte 1: Listas e tuplas - Aula 02](https://github.com/samuel-apls/alura-formacao-python/commit/680bb82a3d5b71d1eac8d65edb414ba6ff18c701)
----

### Dia 17: 16 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão das aulas de Polimorfismo e arrays; e igualdade: capítulos 03 e 04 do curso [Python Collections Parte 1: Listas e tuplas](https://cursos.alura.com.br/course/python-collections-listas-e-tuplas).

**Aprendizados:** 

Aplicar os conceito de herança e polimorfismo utilizando listas: atributos privados, classes herdando da classe-mãe, métodos sobrescritos (polimorfismo) de acordo com as especificações de suas classes com base na classe-mãe.

Entender o que o ```duck typing```: se o meu método (que foi rescrito na minha classe), que ele execute o que está na minha classe!

Fazer um array no Python, que exige que seja trabalhado com um tipo definido:

~~~Python
import array as arr
arr.array('d',[])
#Onde 'd' é o tipo do array, que não recebe outros tipos
~~~

Forçar a implementação de um método abstrato na instanciação da classe, parametrizando a classe-mãe com:
~~~Python
from abc import ABCmeta, abstraticmethod

class NomeClasse(metaclass=ABCmeta)
    
    @abstraticmethod
    def nome_metodo(self):
        pass
~~~

O método especial ```__eq__``` é importante para implementação de comparação quando se deseja realizar comparações específicas, não somente comparações baseadas em referências utilizando o operador ```==```

1. [Python Collections Parte 1: Listas e tuplas - Aula 03 e 04](https://github.com/samuel-apls/alura-formacao-python/commit/73ea9296e655dbb015aed049463cbd1b67c54c9a)
----

### Dia 18: 17 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão das aulas de métodos built-in de ordenação: capítulos 05 e 06 do curso [Python Collections Parte 1: Listas e tuplas](https://cursos.alura.com.br/course/python-collections-listas-e-tuplas).

**Aprendizados:** 

Percorrer lista e gerar tuplas associando seus pindices (posições) com seus respectivos valres. Utilizar método específico para essa finalidade ```list(enumerate(lista))``` ou apenas ```enumerate(lista)``` quando aplicada em um ```for```.

Desempacotar tuplas utilizando recurso de especidicar as posições da tupla:
~~~Python
for valor1, valor2, ... in enumerate(lista):
    instrucao...
~~~

Ordenar lista com método ```sorted(lista)``` utilizando parâmetro ```reverse``` (```sorted(lista, reverse=True)```) para inversão de ordem. 

Ordenar a lista na referência do objeto utilzando ```lista.sort()```. Retorna ```None```.

1. [Python Collections Parte 1: Listas e tuplas - Aula 05 e 06](https://github.com/samuel-apls/alura-formacao-python/commit/c52e3f3f8387bb8d7b25938c8ed375a84da41361)
----

### Dia 19: 19 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão das aulas de ordenação customizada e ordenação total; e conclusão do curso. Capítulos 07 e 08 do curso [Python Collections Parte 1: Listas e tuplas](https://cursos.alura.com.br/course/python-collections-listas-e-tuplas).

**Aprendizados:** 

Entender como o Python trata a ordema natural nas comparações (valores e strings), utilizanddo funções dentro do método ```sorted```:

a) Implementação por méio de função:
~~~Python
def metodo_de_comparacao(self, valor)
    return ...

for elemento in sorted(lista, metodo_de_comparacao(valor)):
    return ...
~~~

b) Implementação por meio de atributo importado, podendo ser utilizado mais de um em caso de necessidade de utilizar níveis de comparação:
~~~Python
from operator import attrgetter

for elemento in sorted(lista, key=attrgetter('_atributo1, _atributo2, ...')):
    return ...
~~~

Implementar um ```magic method``` ```__lt__``` (less than) para comparações mais customizadas:

~~~Python
def __lt__(self, outro):
    return ...
~~~

Utilizar o ```total_ordering``` com o objetivo de obter comparações excepcionais como ```<=```ou ```>=```, sendo que a implementeção do ```__eq__``` e ```__lt__``` é um requisito na classe. Nesse sentido a ```anotação``` do método ```@total_ordering``` é suficiente para a compração acontecer implicitamento (caso contrário, retornaria um erro):

~~~Python
from functools import total_ordering

@total_ordering
class NomeDaClasse:
    pass
~~~

1. [Python Collections Parte 1: Listas e tuplas - Aula 07 e 08](https://github.com/samuel-apls/alura-formacao-python/commit/bf12dc5c6c333714539b3fb41381470e029d252d)
2. [Python Collections Parte 1: Listas e tuplas - Certificado](https://cursos.alura.com.br/user/samuel-apls/course/python-collections-listas-e-tuplas/formalCertificate)
----

### Dia 20: 28 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão das aulas de Conjuntos e Operações com Conjuntos. Capítulos 01 e 02 do curso [Python Collections Parte 2: Conjuntos e Dicionários](https://cursos.alura.com.br/course/python-collections-conjuntos-e-dicionarios).

**Aprendizados:** 

Criar conjuntos diretamente ```set(lista)``` e transformando uma ```lista```, na qual se transformará em uma sequência mutável que não permite elementos repetidos (nem mesmo do tipo ```string```):

~~~Python
lista =[]
conjunto = {}
conjunto = lista.copy()

conjunto = set(lista)
~~~

Operações com conjuntos (necessitam ser do tipo ```set``` para realizar as operações em conjuntos):

União exclusiva ```|```
~~~Python
conjunto3 = conjunto1 | conjunto2
~~~

União exclusiva (mantém dados iguais) ```&```
~~~Python
conjunto3 = conjunto1 & conjunto2
~~~

União exclusiva (remove dados repetidos) ```-```
~~~Python
conjunto3 = conjunto1 - conjunto2
~~~

Intersecção (remover dados repetidos em ambos conjuntos) ```^```
~~~Python
conjunto3 = conjunto1 ^ conjunto2
~~~

Adicionar elementos ao conjunto, que possui natureza mutável
~~~Python
conjunto4 = conjunto3.add(valor)
~~~

Congelar conjunto (impedir inclusão remoção da elementos)
~~~Python
conjunto4 = frozenset(conjunto4)
~~~

1. [Python Collections Parte 2: Conjuntos e Dicionários - Aulas 01 e 02](https://github.com/samuel-apls/alura-formacao-python/commit/9fd4ca133972f8492b6b4e8387bb0807e7f20a36)
----

### Dia 21: 29 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão das aulas de Dicionários e Variações de Dicionários. Capítulos 03 e 04 do curso [Python Collections Parte 2: Conjuntos e Dicionários](https://cursos.alura.com.br/course/python-collections-conjuntos-e-dicionarios).

**Aprendizados:** 

Entender a diferença entre dicionário (```dict```), listas e conjuntos, assim como a aplicabilidade dos conceitos de chave e valor que compõe o dicionário

Criar dicionários pelo uso de chaves ```{}```ou ```dict```.
~~~Python
#Criando um dicionário diretamente pelo uso de chaves
dicionario = {'chave1': valor1, 'chave2': valor2, ...}

#Criando um dicionario com o uso do dict,
dicionario1 = dict(chave1 = valor1, chave2 = valor2, ...)

dicionario2 = dict([('chave1', valor1), ('chave2', valor2), ...])
~~~

Verificar e manipular elementos dos dicionários:

a) Adicionando elemento por método ```dicionario.get('chave1')``` ou diretamente pela chave ```dicionario['chave1'] = valor```

b) Removendo elemento do dicionario: ```del dicionario['chave1']```

Mostrar elementos dentro do dicionário iterando sobre o dicionario e/ou utilizando métodos como ```keys()``` para pegar as chaves, ```values()``` para pegar os valores e ```items()``` para linha (chave e valor correspondente)

Contar elementos dento de um dicionário:
~~~Python
from typing import Counter
dicionario = Counter(texto.split())
~~~

Atribuir valores padrão em um dicionário:
~~~Python
from collections import defaultdict
dicionario = defaultdict(int)
~~~

1. [Python Collections Parte 2: Conjuntos e Dicionários - Aulas 03 e 04](https://github.com/samuel-apls/alura-formacao-python/commit/e8e38973fcaa1ced5e92a724eacd8a81c4cb5da4)
----

### Dia 22: 30 de dezembro de 2021

**Progresso do dia:** 

Início e conclusão da aula de Praticando Dicionários, capítulos 05; e conclusão do curso [Python Collections Parte 2: Conjuntos e Dicionários](https://cursos.alura.com.br/course/python-collections-conjuntos-e-dicionarios).

**Aprendizados:** 

Realizar uam análise de um texto, aplicando o conhecimento de dicionário e seus métodos, para obter uma visão de quantidade de palavras e como é a frequência de palavras no texto. Para alcançar o resultdo foram percorridasd as seguintes etapas:

* Criado um dicionário que calcula a frequência de palavras em minúsculo e separadas por espaços

* Criada uma lista de tuplas com cada palavra identificada com a sua frequência

* Lista de tupl`a transformada em dicionário

* Método do ``` Counter``` utilizado para obter as 10 maiores ocorrências (```dicionario.most_commom(10))```

1. [Python Collections Parte 2: Conjuntos e Dicionários - Aula 05](https://github.com/samuel-apls/alura-formacao-python/commit/78ae902bea96ee22dbeac5c43b97fb91bfa1cfd9)
2. [Python Collections Parte 2: Conjuntos e Dicionários - Certificado](https://cursos.alura.com.br/user/samuel-apls/course/python-collections-conjuntos-e-dicionarios/formalCertificate)
----
