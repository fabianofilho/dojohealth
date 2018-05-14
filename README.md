# Dojo Heath
Repositório do evento Dojo Heath

## O que tem por aqui?
- Machine Learning
- Neural Network
- Data Integration
- Tools

## O que preciso fazer?
Ler os seguintes links que vou disponibilizar nas próximas linhas juntinho de você

### Aqui tem código?
Siiiim!

Você vai encontrar dois modelos de RNA e alguns algoritmos mais simples

### Como vou entender a base de dados?
Calma meu jovem Padawan, o caminho é longo e as pernas são curtas...

[Aqui](pdf/) o caminho encontrar, você irá...

### O que você quer que eu faça?
Deposite R$ 120.000,00 na minha cont... opa, aqui não.

Esperamos que você desenvolva uma ferramenta ou uma metodologia para integração e análise de dados voltado para recém nascidos.

Em português: Queremos que você descubra algo interessante e útil analisando a base de dados disponibilizada, e que essa coisa super legal que você vai criar, seja voltada para materno infantil.

### Como farei?
Dê uma boa lida nos [dicionários de dados](pdf/), reflita sobre a vida o universo e tudo mais, aprecie um delicioso café e leia novamente os dicionários de dados.

Após ter certeza que leu, tente relacionar as variáveis nos diferentes bancos que possam fazer sentido juntas ou para o problema em questão.

Bole um plano de dominação do mundo, leia o resto desta página e mãos ao código.

## Vamos ao conteúdo
A maioria das ferramentas apresentadas aqui são em [Python](https://www.python.org/downloads/), então já sabe o que fazer...
### Libs
- Pandas

Utilizado para leitura e manipulação de dados

```
pip install pandas
```

- Numpy

Utilizado para otimização

```
pip install numpy
```
- SciPy

Conjunto de libs

```
pip install scipy

```
- SciKit Learn

Conjunto de ferramentas para *Machine Learning*

```
pip install -U scikit-learn
```

### Ferramentas
- [Regressão composta](src/regressao_composta.py)

Cria regressão não linear por método Neural para predição de novos valores.

Ou seja, serve para descobrir o próximo valor, dado uma sequência.

- [Rede Neural Classificadora](src/rna_sklearn.py)

Rede Neural para classificação (Básica) usando a ferramenta sciKit Learn

- [Rede Neural Classificadora Sem Lib](src/rna_without_lib.py)

Rede Neural para classificação (3 camadas) sem usar lib, somente com numpy

- [Arquivo com 3 RNA de classificação](src/rna_bagunca.py)

Arquivo com 3 redes Neurais implementadas, bem bagunçado, mas tem umas funções interessantes... boa sorte!

- [Integração de dados no ultimo BlueHack](src/data_integration_blhack.py)

Integração de dados entre duas bases sem conexão aparente (Desenvolvido durante o evento *Blue Hack 2017 Curitiba*)

- [Quer algo mais parrudo?](https://github.com/joaopandolfi/crfasrnn)
Rede Neural baseada na Caffe para segmentação semântica (Ok,eu sei é p processamento de image, mas eu n sei o que você vai fazer né *:D* )
