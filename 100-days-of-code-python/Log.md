# 100 Days Of Code Python - Log

### Dia 0: 15 de novembro de 2021

**Progresso do dia:** 

Revisei os cursos concluídos da formação (Python3 - Parte 1 e 2) e dei continuidade na aula 03 do curso Python3 Introdução a Orientação a Objetos.

**Aprendizados:** 

Python 3 parte 1

Nesse curso revi os conceitos iniciais da programação: instalar e rodar um projeto por meio de uma IDE, utilizar a função print, trabalhar com variáveis e tipo de dados. Avançando nos principais temas da programação: comparação de tipos e diferenças da linguagem nas versões 2 e 3. Testando valores com as condicionais. Utilização de laço de repetição e iteradores. Importação de módulos (bibliotecas) e funções built-in (biblioteca padrão). Analisando diferenças entre interpretadores e compiladores.


Python 3 parte 2

Nesse curso aperfeiçoei o conhecimento fundamental na linguagem Python. Trabalhei na prática a manipulação dos dados, comparando e iterando em laços. Aprendi nova estrutura de dados: Coleções (Listas, Tuplas e um pouco de Set (lista que não permite elementos duplicados) e Dicionários). Aprendi também a realizar leitura e escrita de arquivo.


Python 3 Introdução a OO

Na aula 01 foi revisado os temas Dicionários, Funções e Encapsulamento. Foi explanada as motivações para a abordagem OO e a diferença entre o paradigma procedural.
Na aula 02 foram apresentados: classes, objetos, função construtora, endereços e referência de objetos, atributos de classe e como acessá-los por meio dos objetos e da referência "self"

Na aula 03 foi explanado o que é e como criar métodos (comportamento da classe), como chamar métodos por meio dos objetos e da referência "self". Foi apresentado o conceito de Garbage Colector do Python e o tipo None (valor nulo para variáveis)

**Link do trabalho:** 

1. [Python3 Parte 1: Inrodução à nova versão da linguagem](https://cursos.alura.com.br/user/samuel-apls/course/python-3-introducao-a-nova-versao-da-linguagem/formalCertificate)
2. [Python3 Parte 2: Avançando na linguagem](https://cursos.alura.com.br/user/samuel-apls/course/python-3-avancando-na-linguagem/formalCertificate)
3. [Python3: Introdução a Orientação a objetos (aula 03)](https://github.com/samuel-apls/alura-formacao-python/commit/f8236f818e96692bc2b48b93e2c37c8573b93b5a#diff-db236ecce453bc7f47859772cf2f6f1899d0c97e3231311db782ac0aecf47a2c)


### Dia 1: 16 de novembro de 2021

**Progresso do dia:** 

Estudei sobre encapsulamento, prorpiedades dos atributos da classe e coesão de código. Pratiquei no arquivo da aula 04 do curso [Python3 Introdução a Orientação a Objetos](https://cursos.alura.com.br/course/python-3-intro-orientacao-objetos).

**Aprendizados:** 

Na aula 04 foi demonstrado na prátrica o conceito de encapsulamento (pincípio de design de código, pilar da Orientação a Objetos). Foi possível observar as vantagens do uso, como por exemplo, fácil manutenção e reutilização de código, em consequência do baixo acoplamento de código. Além disso, foi demonstrada a importância da coesão no código, ou seja, os métodos de responsabilidade da Classe devem ser divididos em classes de forma que contribuam também para os benefícios do encapsulamento. POr fim, fopi explando como restringir a visibilidade dos atributos. No entanto, em Python, é visibilidade dos atributos é uma convenção, onde cabe ao desenvolvedor adotar ou não as melhores práticas (a linguagem não irá impedir totalmente de um atributo privado ser acessado. Por exemplo, pode ser acessaod da seguinte maneira: 'self.Classe.atributo').

**Link do trabalho:** 

1. [Python3: Introdução a Orientação a objetos (aula 04)](https://github.com/samuel-apls/alura-formacao-python/commit/2e8fde1f52746dbbcae666fb1d70489556ecac3e)


### Dia 2: 17 de novembro de 2021

**Progresso do dia:** 

Estudei sobre métodos de leitura de atributos (getters), método de alteração de atributos (setters) e a como aplicar esses conceitos de manipulação de atributos utilizando Propriedades. Pratiquei no arquivo da aula 05 do curso [Python3 Introdução a Orientação a Objetos](https://cursos.alura.com.br/course/python-3-intro-orientacao-objetos).

**Aprendizados:** 

Na aula 05 foi demonstrado o uso de getter e setter. Tal como na linguagem Java, é uma boa prática como estebeler padrão de design de código de acordo com a Orientação a Objeto. Foi aprosentado o uso de Propriedade, que é uma implmentação de método que se referencia diretamente ao atributo da Classe, que deve estar na condição privada, (cuja assinatura do método corresponde à mesma nomenclatura do atributo). Implementação:

~~~python
@property
def nome_do_atributo(self):
    return codigo

@nome_do_atributo.setter
def nome_do_atributo(self):
    return codigo
~~~

Isso faz com que o método seja chamado sem necessáriamente apresentar os parênteses, característicos de método. Por exemplo: 'self.atributo' para @property e 'self.atributo = valor' para @setter

**Link do trabalho:** 

1. [Python3: Introdução a Orientação a objetos (aula 05)](https://github.com/samuel-apls/alura-formacao-python/commit/5c1c4d56ad552cdf43fea2ce12bd952dd7e9252d)


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
1. [Python3: Introdução a Orientação a objetos (aula 06](https://github.com/samuel-apls/alura-formacao-python/commit/be49d77e949c1d501f00130d52da03a38f2a6f00)
