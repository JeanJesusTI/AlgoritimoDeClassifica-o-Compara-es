# Algoritimos De Classificação - Comparações
  Neste repositório está armazenado um arquivo do tipo Jupyter Notebook utilizando a linguagem Python, onde será realizado a comparação entre 3 algoritimos de classificação, sendo eles:  
  
  * DecisionTreeClassifier 
  * RandomForestClassifier 
  * ExtraTreesClassifier.

### DecisionTreeClassifier
  As árvores de decisão são estruturas que podem ser utilizadas para classificação de dados ou para a realização de previsões, também podem ser consideradas como uma ferramenta de apoio da decisão; pois, através da definição de algumas regras, a arvore consegue inferir a decisão que deve ser tomada. A DecisioTree apresenta o formato de uma arvore de cabeça para baixo, onde sua raíz está no topo e suas folhas ficam na parte inferior.


### RandomForestClassifier
  As Random Forest são denominadas um método ensamble *(Método que utiliza a combinação de multiplos modelos para produzir um modelo mais preciso)*, que são utilizadas para classificação, regressão e outros. De modo geral, as Random Forest combinam um conjunto de **árovres de decisão** para se obter um melhor resultado.
  
  
### ExtraTreesClassifier
  A ExtraTreeClassifier é um método de aprendizagem baseado em Decision Tree, utilizando a randomização nas decisões para se obter um melhor aprendizado.


### Método de Análise

#### Módulos Utilizados
  Para realizarmos essa comparação, utilizamos os seguintes módulos:
  *from sklearn.cross_validation import cross_val_score
    * Utilizamos cross_validation para se obter o score dos modelos criados
      
  *from sklearn.ensemble import ExtraTreesClassifier
      * Utilizamos o ExtraTreesClassifier para criação do Modelo
      
  *from sklearn.tree import DecisionTreeClassifier
    * Utilizamos o DecisionTreeClassifier para criação do Modelo
      
  *from sklearn.ensemble import RandomForestClassifier
    * Utilizamos o RandomForestClassifier para criação do Modelo
      
  *from sklearn.datasets import load_digits
    * Utilizamos o load_digits para carregar os dados sobre os quais serão realizados a análise
      
  *from sklearn.preprocessing import scale
    * Utilizamos o módulo scale para colocar os dados das variáveis preditoras em uma mesma escala (para melhorar a performance dos algoritimos)
 
