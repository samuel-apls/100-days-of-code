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


### Dia 1: 16 de novembro de 2021

**Progresso do dia:** 

Estudei sobre encapsulamento, prorpiedades dos atributos da classe e coesão de código. Pratiquei no arquivo da aula 04 do curso [Python3 Introdução a Orientação a Objetos](https://cursos.alura.com.br/course/python-3-intro-orientacao-objetos).

**Aprendizados:** 

Na aula 04 foi demonstrado na prátrica o conceito de encapsulamento (pincípio de design de código, pilar da Orientação a Objetos). Foi possível observar as vantagens do uso, como por exemplo, fácil manutenção e reutilização de código, em consequência do baixo acoplamento de código. Além disso, foi demonstrada a importância da coesão no código, ou seja, os métodos de responsabilidade da Classe devem ser divididos em classes de forma que contribuam também para os benefícios do encapsulamento. Por fim, foi explando como restringir a visibilidade dos atributos. No entanto, em Python, a visibilidade dos atributos é uma convenção, onde cabe ao desenvolvedor adotar ou não as melhores práticas (a linguagem não irá impedir totalmente de um atributo privado ser acessado. Por exemplo, pode ser acessado da seguinte maneira: ```self.Classe.atributo```).

**Link do trabalho:** 

1. [Python3: Introdução a Orientação a objetos - Aula 04](https://github.com/samuel-apls/alura-formacao-python/commit/2e8fde1f52746dbbcae666fb1d70489556ecac3e)


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


### Dia 7: 23 de novembro de 2021

**Progresso do dia:** 
Herança de classe do tipo ```built-in```, suas vantagens e desvantagens. Capítulo 04 do curso [Python 3: Avançando na orientação a objetos](https://cursos.alura.com.br/course/python-3-avancando-orientacao-objetos).

**Aprendizados:** 

Utilizar a herança do tipo ```buit-in``` (pacote nativo), sendo a vantagem principal, o polimorfismo. A classe herdada é a ```List```, cujo objetivo é iterar sobre o objeto ```iterable```. A desvantagem, consiste em herdar uma classe desconhecida, podendo gerar complexidade e acoplamento ao código.

**Link do trabalho:**
1. [Python 3: Avançando na orientação a objetos - Aula 04](https://github.com/samuel-apls/alura-formacao-python/commit/6f5b1ab0b2e1a6eb9691383145e934611b48ff12)

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

### Dia 10: 07 de dezembro de 2021

**Progresso do dia:** 

Introdução ao fatiamento (slicing) de String. Capítulo 01 do curso [String em Python: Extraindo informações de uma URL](https://cursos.alura.com.br/course/string-python-extraindo-informacoes-url).

**Aprendizados:** 

As URLs têm basicamente duas estruturas: base da URL e parâmetros da URL.

As strings são como listas, que não podem ter suas posições alteradas (imutáveis) e podem ser percorridas por posições (inciando em zero até n-1). Sendo o operador de fatiamento: ```string[indice1 : indice2]```. No ```indice1```, à esquerda, a posição é inclusiva (n+1). No ```indice2```, à direita, a posição é exclusiva (n-1).

**Link do trabalho:**

1. [String em Python: Extraindo informações de uma URL - Aula 01](https://github.com/samuel-apls/alura-formacao-python/commit/0b28b877318093cf2d41b99e4020e94404904dd7)


### Dia 11: 08 de dezembro de 2021

**Progresso do dia:** 

Utilizando método de String. Capítulo 02 do curso [String em Python: Extraindo informações de uma URL](https://cursos.alura.com.br/course/string-python-extraindo-informacoes-url).

**Aprendizados:** 

Omitir o primeiro ou o segundo argumento do operador de fatiamento para fatiar uma string do início até um certo índice, ou a partir de um índice até o final: ```str[a:]``` ou ```str[:b]```.

Utilizar o método ```str.find(palavra, inicio)``` para buscar o índice de palavra a partir de inicio. Caso ```palavra``` não seja encontrada, o método ```find``` retorna -1.

O método ```len(string)``` retorna o tamanho (ou seja, a quantidade de caracteres) da nossa string.

**Link do trabalho:**

1. [String em Python: Extraindo informações de uma URL - Aula 02](https://github.com/samuel-apls/alura-formacao-python/commit/f07f0b467d06f353af513fd8b148323993e10ca0)


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
