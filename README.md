<h1>Predição de Perdas de Água em Municípios Brasileiros</h1>

<p>
    Este repositório contém o código e a documentação do projeto de pesquisa desenvolvido durante minha bolsa de pesquisa na UDESC. O trabalho foi premiado com o 1º lugar no 34º Seminário de Iniciação Científica da universidade.
</p>

<h3>O Problema:</h3>
<p>
    O Brasil perde cerca de 40% da água potável durante a distribuição antes mesmo de chegar às residências. O objetivo deste estudo foi entender quais fatores (demográficos, econômicos ou operacionais) mais impactam esse desperdício e criar um modelo matemático capaz de prever essas perdas com precisão.
</p>

<h3>O que foi feito:</h3>
<p>
    Utilizei dados públicos do SNIS (Sistema Nacional de Informações sobre Saneamento) e do IBGE para analisar quase 4 mil municípios. A abordagem técnica envolveu:
</p>
<p>
    1- Limpeza e tratamento de dados com Python.<br>
    2- Análise estatística inicial (Correlação de Pearson e Regressão Linear), que se mostrou insuficiente para a complexidade do problema (R-quadrado de apenas 0.08).<br>
    3- Implementação e otimização de algoritmos de Machine Learning (Random Forest e Gradient Boosting) para capturar padrões não lineares.
</p>

<h3>Resultados:</h3>
<p>
    A principal conquista deste projeto foi a otimização dos modelos. Saímos de uma capacidade de explicação inicial muito baixa para um modelo robusto. O algoritmo Gradient Boosting, após o ajuste de hiperparâmetros, atingiu um R-quadrado de 0.735.<br>
    As análises mostraram que variáveis operacionais, como a extensão da rede e o volume de água produzido, influenciam muito mais nas perdas do que fatores econômicos, como o PIB do município.
</p>

<h3>Como utilizar:</h3>
<p>
    Na pasta notebooks você encontrará os códigos com o passo a passo da análise, desde a exploração dos dados até a otimização final dos modelos. Na pasta docs está disponível o artigo completo (PDF) com todo o embasamento teórico e a metodologia detalhada.
</p>

<h3>Tecnologias:</h3>
<p>
    O projeto foi desenvolvido inteiramente em Python, utilizando principalmente as bibliotecas Pandas para manipulação de dados e Scikit-learn para a modelagem preditiva.
</p>
