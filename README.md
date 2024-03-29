# Trabalho 3 - Máquinas de Turing e Computabilidade

## Linguagens Formais e Autômatos - Bach. Sistemas de Informação
## Autor: Ewerson Vieira Nascimento

### Ferramentas utilizadas
Trabalho realizado utilizando [Graphviz Online](https://dreampuf.github.io/GraphvizOnline/) para construção dos diagramas de Máquina de Turing e [Turing Machine Simulator (Morphett)](http://morphett.info/turing/turing.html) para simulação do funcionamento das Máquinas de Turing propostas em cada resolução.

### Descrição geral do do trabalho
Cada diretório relativo à resolução de questões envolvendo a elaboração do diagrama da Máquina de Turing e o código do simulador Morphett contém um arquivo com o código do diagrama no Graphviz, a imagem do diagrama e o código do simulador Morphett. A exceção é a Questão 10, pois o formato de sua resolução difere das demais. Assim, os arquivos deste trabalho estão estruturados da seguinte maneira:

```
Questao-01
|_ diagrama-questao-01.png
|_ diagrama-questao-01.txt
|_ morphett-questao-01.txt
Questao-02
|_ diagrama-questao-02.png
|_ diagrama-questao-02.txt
|_ morphett-questao-02.txt
...
Questao-09
|_ diagrama-questao-09.png
|_ diagrama-questao-09.txt
|_ morphett-questao-09.txt
Questao-10
|_ Resposta.txt
```

### Questão 1

![questao-01](Questao-01/diagrama-questao-01.png)

[Código do Simulador Morphett](Questao-01/morphett-questao-01.txt)

### Questão 2

![questao-02](Questao-02/diagrama-questao-02.png)

[Código do Simulador Morphett](Questao-02/morphett-questao-02.txt)

### Questão 3

![questao-03](Questao-03/diagrama-questao-03.png)

[Código do Simulador Morphett](Questao-03/morphett-questao-03.txt)

### Questão 4

![questao-04](Questao-04/diagrama-questao-04.png)

[Código do Simulador Morphett](Questao-04/morphett-questao-04.txt)

### Questão 5

![questao-05](Questao-05/diagrama-questao-05.png)

[Código do Simulador Morphett](Questao-05/morphett-questao-05.txt)

### Questão 6

![questao-06](Questao-06/diagrama-questao-06.png)

[Código do Simulador Morphett](Questao-06/morphett-questao-06.txt)

### Questão 7

![questao-07](Questao-07/diagrama-questao-07.png)

[Código do Simulador Morphett](Questao-07/morphett-questao-07.txt)

### Questão 8

![questao-08](Questao-08/diagrama-questao-08.png)

[Código do Simulador Morphett](Questao-08/morphett-questao-08.txt)

### Questão 9

![questao-09](Questao-09/diagrama-questao-09.png)

[Código do Simulador Morphett](Questao-09/morphett-questao-09.txt)

### Questão 10

#### Resposta:
É uma máquina de turing que aceita apenas cadeias iniciadas com 0 seguidas de um ou mais 1, produzindo uma cadeia de saída composta somente por 1.

Exemplo:

Entrada|Saída  |
-------|-------|
0      |1
011    |111
0111111|1111111