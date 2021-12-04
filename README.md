# Rede_Neural_fundo
códigos utilizados para o trabalho final da disciplina de Redes Neurais 



## Objetivo do Trabalho 
 O então trabalho tem como objetivo utilizar uma rede neural do tipo MLP (Multilayer Perceptron)  para a avaliação de compra de um fundo imobiliário, assim sendo, o principal objetivo é a análise risco benefício do ativo financeiro. Desta forma, a rede neural deverá analisar alguns parâmetros importantes na análise de um fundo, tal como Dividend Yield, variação do preço, e assim expor se o ativo é promissor ou não.  


## Metodologia 
### Base de Dados 
Atualmente a bolsa de valores brasileira conta com cerca de 386 fundos imobiliários. Para o estudo foram capturadas 55 amostras, correspondendo a cerca de 21% do espaço amostral total.

### Tratamento Prévio dos dados. Antes mesmo de tratar os dados para o treinamento, foi necessário realizar a conversão de tipos, substituir vírgula por pontos e eliminar o cifrão dos dados.


## Métricas
Cada ativo possui algumas informações importantes que podem ser utilizadas para a obtenção de uma classificação. Obtendo os dados da plataforma www.fundsexplorer.com.br podemos utilizar alguns dados para a classificação, sendo estes: 

- Para a classificação dos fundos, utilizou-se o último dividendo obtido pelo fundo. Sendo classificado em duas categorias: Lucro( para dividendos acima de R$1.00) e Prejuízo ( para dividendos abaixo de R$1.00)
Já para os parâmetros, as métricas utilizadas foram:
	
- Vacância Física: Quantidade de imóveis do fundo desocupados. 
- Patrimônio líquido: Soma do valor em caixa mais a soma de todos os ativos, subtraído da obrigação do fundo. - ok
- Variação Patrimonial: Fator que representa o quanto um ativo oscila, com base em sua média - ok   
- Preço Atual: O valor da cota atual 
- Variação do Preço: É a variação que o valor da cota sofreu durante os dois últimos meses.
- P/VPA: É o preço da ação dividido pelo valor patrimonial. 
