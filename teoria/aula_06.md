# Association analysis 
> Antes de termos o exame a professora vai nos dar uma lista de exercicios e o sumário do que demos, LEMBRAR A PROFESSORA DE FAZER ISTO CASO ELA SE ESQUEÇA
 
> NOTA APARTE: A PROFESSORA RECOMENDOU VER OS CAPITULOS DOS LIVROS ASSOCIADOS AOS SLIDES


## Association rule mining 

* É um unsupervide machine learning method 

* ver slides

* A figura representa transações, e o os itens que foram compradas nas transações

* Os exemplos de regras de associação indicam, por exemplo, quando compro 'Diaper' eu compro 'Beer' ({Diaper} -> {Beer})
* As métricas que vamos usar são
    * Support
    * Confidence
    * Lift

* Implication means co-occurrence, not causality!

> No package que vamos usar em python, ele só aceita datasets booleanos, portanto para este exemplo passariamos cada item para uma coluna (em que indicariamos a presença do item se colocassemos true na respetiva coluna desse item)

### Definition: Frequent Itemset

* ver slides (perceber cada um)


### Definition: Association rule 

* ver slides

* Exemplo de association rule
    * {Milk, Diaper} -> {Beer}
        * Quando compro Milk e Diaper tipicamente compro também Beer

* Ver exemplo de calculo de confidence e support


### Association Rule Mining Task

* ver slide (dá a tarefa de Association rule mining e uma aproximação Brute force para executar essa tarefa)


#### Computational Complexity
* Mostra a complexidade associada com Association Rule Mining Task dado d itens únicos 

> Só é relevante saber que é computacionalmente dispendioso seguir a aproximação brute force


#### Mining Association Rule (I)

* Ver slides (temos uma 'otimização'), perceber 

#### Mining Association Rule (II)

* Ver slides, que dão-nos uma aproximação para fazer a 'otimização'


#### Frequent Itemset Generation (I)

* Mostra um exemplo de geração de itemset para d itens

> Temos dois tipos de algoritmos que fazem isto, APRIORIe FP-GROWTH (professora recomendou ver o pseudocódigo do algoritmp que está no livro)


#### Frequent Itemset Generation (II)

* Ver slides com aproximação brute force

#### Frequent Itemset Generation Strategies

> Ver slides 


##### Reducing Number of Candidates (M)

> Ver slides com Aprior principle (perceber)

###### Illustrating Apriori Principle

> Ver os diferentes slides, e perceber o que esta a fazer em cada passo 

##### Apriori Algorithm

> Ver os slide com algorithm 


#### Candidate Generation: Brute-force method

> Ver slides com exemplo 


#### Candidate Generation: Merge Fk-1 and F1 itemsets

> Ver slides com exemplo (otimização de candidate generation), perceber

##### Candidate Generation: Fk-1 x Fk-1 Method

> ver slides e perceber


##### Candidate Pruning

> ver slides e perceber 


#### Candidate Generation: Fk-1 x Fk-1 Method

> Ver slides com exemplo (otimização de candidate generation), perceber


##### Illustrating Apriori Principle

> ver slides e perceber 


#### Alternate Fk-1 x Fk-1 Method

> ver slides e perceber 

##### Candidate Pruning for Alternate Fk-1 x Fk-1 Method

> ver slides e perceber 


#### Support Counting of Candidate Itemsets (I)

> ver slides e perceber 

#### Support Counting of Candidate Itemsets (II)

> ver slides e perceber

##### Support Counting: An Example

> ver slides e perceber

#### Support Counting Using a Hash Tree

> ver slides e perceber

> tem varios slides (a professora passou a frente mas disse para ver)


#### Rule Generation 

> ver slides e perceber (são dois slides )

##### Rule Generation for Apriori Algorithm

> ver slides e perceber 

* Ao descobrir um nó com pouca confidence, posso eleminar-lo eliminar os repsetivos descendentes 

## Association Analysis: Basic Concepts and Algorithms


### Factors Affecting Complexity of Apriori
> ver slides (são varios e a explicação de cada ponto é feita em slides diferentes )


### Compact Representation of Frequent Itemsets

> Professora saltou varios slides 

### Maximal vs Closed Itemsets

> ver figura, apontar apenas o que é cada um deste itens e para que servem 


#### Example question

> para fazer estes slides é precisso ver os slides que a professora saltou


### Pattern Evaluation

> ver slides 


### Computing Interestingness Measure

> ver slides e perceber 

### Drawback of Confidence

> ver slides e perceber (são vários slides )

> mas as regras devem fazer sentido para o dataset em questão 


### Measure for Association Rules

> ver slides 

> ficamos neste slide

> A professora não acabou estes slides 