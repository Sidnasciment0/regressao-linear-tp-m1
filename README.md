# 📈 Trabalho Prático - Módulo 01
Algoritmo de regressão linear para prever o valor da diária de um imóvel baseado no número de pessoas.

 - Coletar e inserir o arquivo custo_diaria.csv na plataforma;
 - Analisar os dados coletados;
 - Avaliar a relação entre as variáveis;
 - Criar algoritmo de regressão linear;
 - Responder as questões teóricas e práticas do trabalho

## 🔎 Case - Regressão Linear Simples

Uma empresa do ramo imobiliário quer criar um modelo preditivo que utiliza os **dados de valor do custo da diária e quantidade de pessoas**. Ela possui uma base de dados histórica que contém a quantidade pessoas e o valor cobrado no custo da diária.

Diante disso, a empresa contratou uma consultoria de tecnologia para auxiliar no processo de predição. Os analistas perceberam que a melhor abordagem para esse problema é criar um algoritmo de **Machine Learning de regressão linear** para predizer o **valor da diária do imóvel baseado na quantidade de pessoas que realizaram a diária.**

## Regressão Linear
É um algoritmo de **Machine Learning** para aprendizado supervisionado. A análise de regressão linear é usada para prever o valor de uma variável com base no valor de outra. A variável que deseja prever é chamada de variável dependente (y )e a variável que é usada para prever o valor de outra variável é chamada de variável independente (X).

*Fórmula* </br>
![Equação](https://github.com/Sidnasciment0/regressao-linear-tp-m1/blob/main/img/equa%C3%A7%C3%A3o_rl.png)
</br>

Onde: </br>
yi: Variável explicada (dependente); representa o que o modelo tentará prever; </br>
a: É uma constante, que representa a interceptação da reta com o eixo vertical; </br>
β: Representa a inclinação (coeficiente angular) em relação à variável explicativa; </br>
Xi: Variável explicativa (independente); </br>
ε: Representa todos os fatores residuais mais os possíveis erros de medição. É um termo erro aleatório com média μ zero e variância ơ2 constante. </br>

## Insights
O gráfico abaixo representa os valores cobrados no custo da diária. Notamos que não existe um padrão para cobranças, uma vez que a relação entre pessoa e custo não é sempre proporcional. Pois, existem casos onde um número menor de pessoas paga mais caro que outro grupo com mais pessoas.

![Plot](https://github.com/Sidnasciment0/regressao-linear-tp-m1/blob/main/img/newplot.png)
</br>

Após realizarmos a previsão é encontrado uma proporcionalidade entre os valores cobrados e o número de pessoas, ao analisar, podemos recomendar uma adequação nos valores cobrados, possibilitando uma cobrança mais justa para os cliente.

![Plot Previsão](https://github.com/Sidnasciment0/regressao-linear-tp-m1/blob/main/img/newplot_previs%C3%A3o.png)
</br>
