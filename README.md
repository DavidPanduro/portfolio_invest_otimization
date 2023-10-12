# Projeto: Portfolio Otimization through deep learning and otimization algorithms
Por David Panduro 💻<br><br>
![image](https://github.com/DavidPanduro/portfolio_invest_otimization/assets/45201867/1ff6e2db-01b1-47f0-b125-a2b674c0581a)<br>

Contexto:<br>
Desenvolvemos a otimização de três (03) portfólios composto por ações de três (03) empresas (que no inicio do 2023 foram sugeridos por reconhecidos Investidores Brasileiros, que não serão explícitamente mencionados 👀) da bolsa brasileira 🇧🇷, aplicando algoritmos de otimização e aprendizagem profunda em cenários de risco não sistemático, analisando os riscos e procurando maximizar os rendimentos do portfólio ao final do período. <br> <br>
Bases: <br> 
No estudo, consideramos dados de movimentações da Bolsa Brasileira, no período desde 2018-01-01 até 2023-06-30. Totalizando cinco (05) anos, mais os restantes seis (06) meses do 2023.<br><br>
Portfólios:<br> Os portfólios estão compostos pelas seguintes empresas:<br>
1. Portfólio_LB. [BB Seguridade, Banco do Brasil, Cosan].<br>
   ![image](https://github.com/DavidPanduro/portfolio_invest_otimization/assets/45201867/6f6e98f8-dbdd-484f-8a7e-89030a2c8ff1)<br><br>

2. Portfólio_TN. [RAPT3, RANI3, LEVE3]<br>
   ![image](https://github.com/DavidPanduro/portfolio_invest_otimization/assets/45201867/cc524e0e-a471-4054-b6e6-e3334131f632)<br><br>

3. Portfólio_BP. [Itausa, Vivo, Sanepa]<br>
   ![image](https://github.com/DavidPanduro/portfolio_invest_otimization/assets/45201867/7cf26b33-d09e-45ef-a594-4ca32014a2fa)<br><br>


Portfólio LB:<br>
Podemos observar os portfólios para ter uma visão mais clara do comportamento das ações de empresas que o conformam.<br>
![image](https://github.com/DavidPanduro/portfolio_invest_otimization/assets/45201867/62460459-8cde-4074-9b01-98fff842f959)<br>
A primeira vista, as ações da BBAS3 mostram-se com melhor rendimento ao longo do periodo.<br><br>
Mas, percebe-se que as linhas tem diferenças significativas, básicamente, porque não estão na mesma escala. Vamos tentar resolver isso, e observar que os comportamentos se mostram de manera diferente, porem, agora sim mostram a realidade e podem ser comparados.<br>
   ![image](https://github.com/DavidPanduro/portfolio_invest_otimization/assets/45201867/800a6b54-174e-4bf5-a4ad-5038dd354589)<br>
   Agora sim, com a apresentação na mesma escala, podemos comparar entre elas. E percebemos que a que obteve melhores resultados foi a CSAN3.



Algoritmos de Otimização:<br>
No estudo, aplicaremos os seguintes métodos:
1. Aleátorização.
2. Hill Climb.
3. Simulated Anneling

Previsão de Preços:<br>
Neste ponto aplicaremos tanto a simulação de Monte Carlo e Arima para comparação de resultados com o algoritmo de aprendizagem profunda Long Short Term Memory. 

Finalmente, apresentaremos um quandro de resumo contendo os resultados obtidos assim como os gráficos dos nossos rendimentos simulados.
