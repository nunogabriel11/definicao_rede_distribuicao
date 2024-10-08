# Definição de uma rede de distribuição
O projeto em questão centrou-se na definição da rede de distribuição de uma organização. Tendo por base as suas duas instalações produtivas em cidades portuguesas, os mercados inserida (Portugal, Espanha, França, Alemanha e Itália), limitações de produção fabril e procura dos seus clientes, analisou-se a opção mais económica entre:
1.	Abertura de um centro logístico em cada um dos países de mercado inserida (obtidas através do método de centro de gravidade).
2.	Abertura apenas de dois armazéns com capacidade XL, em Espanha e na Alemanha.<br /><br />


<p align="center">
  <img src="https://github.com/nunogabriel11/definicao_rede_distribuicao/blob/main/imgs/table1.png?raw=true" width="400" />
</p>


<p align="center">
<i>Figura 1: Figura ilustrativa da contabilização dos armazéns para o caso 1</i>
</p><br />


<p align="center">
  <img src="https://github.com/nunogabriel11/definicao_rede_distribuicao/blob/main/imgs/table2.png?raw=true" width="400" />
</p>


<p align="center">
<i>Figura 2: Figura ilustrativa da contabilização dos armazéns para o caso 2</i>
</p><br />


O recurso da extensão “Solver” do Excel permitiu, mediante a variação da capacidade dos centros logísticos e procura por parte dos clientes, obter quais os armazéns a considerar para ambos os casos 1 e 2.<br />
A seguinte imagem retrata as quantidades a produzir de cada centro de produção para cada um dos centros logísticos XL, como também as quantidades a distribuir de este últimos para cada cliente final (exemplo para o caso 2)<br /><br />


<p align="center">
  <img src="https://github.com/nunogabriel11/definicao_rede_distribuicao/blob/main/imgs/results.png?raw=true" width="650" />
</p>

<p align="center">
<i>Figura 3: Figura ilustrativa da produção detalhada de cada fábrica e distribuição de cada centro logístico, para o caso 2</i>
</p><br />



De maneira a facilitar a interação do utilizador, foi criado um menu interativo, com auxílio de programação no Excel, de forma a permitir criar diferentes cenários ao selecionar quais dos 2 casos considerar, como também alterar a procura e capacidades logísticas atuais.<br />
Desta forma, a partir da criação de Macros, desenvolveu-se o botão “Atualiza valores” que permite a iniciação do menu para manipulação análise de diferentes possíveis cenários.<br /><br />

<p align="center">
  <img src="https://github.com/nunogabriel11/definicao_rede_distribuicao/blob/main/imgs/demo.gif?raw=true" width="250" />
</p><br />

Por outro lado, este menu ainda permite uma seleção personalizada dos armazéns a desconsiderar (ver figura 4) permitindo ir mais longe com o desenvolvimento deste projeto.<br /><br />



<p align="center">
  <img src="https://github.com/nunogabriel11/definicao_rede_distribuicao/blob/main/imgs/menu.png?raw=true" width="250" />
</p>

<p align="center">
<i>Figura 4: Figura ilustrativa da funcionalidade de desconsideração de centros logísticos personalizada, proveniente do menu desenvolvido</i>
</p><br />




Os resultados são apresentados numa das folhas do Excel em que é possível observar, mediante o caso selecionado, quais os armazéns a serem abertos, que quantidades cada centro fabril vai produzir para armazém a ser aberto, e que quantidades cada armazém irá distribuir para cada o cliente final (figura 3).<br />

Além disso, foram realizados 5 análises distintas de cenários com manipulação de centros logísticos a desconsiderar, de variação na procura por parte dos clientes e de variação na capacidade dos armazéns considerados. 
De forma a facilitar a perceção visual destes cenários, produziu-se, com o recurso da funcionalidade “3D Map” do Excel, a rede de distribuição da empresa a partir das localizações geográficas de centros fabril, logísticos e de clientes, como se pode observar pelo seguinte exemplo:<br /><br />



<p align="center">
  <img src="https://github.com/nunogabriel11/definicao_rede_distribuicao/blob/main/imgs/map.png?raw=true" width="400" />
</p>

<p align="center">
<i>Figura 5: Figura ilustrativa da rede de distribuição logística considerando a disponibilidade de todos os armazéns (dos dois casos) e uma diminuição da procura em 20 %</i>
</p><br />




O exemplo anterior retrata um caso específico ao analisar um caso de consideração de todos os centros logísticos ao invés dos realizados para o caso 1 e 2, pelo que, para este exemplo, os centros logísticos são o de Portugal, Espanha e Ávila XL.<br /><br />


<p align="center">
  <img src="https://github.com/nunogabriel11/definicao_rede_distribuicao/blob/main/imgs/table3.png?raw=true" width="450" />
</p>

<p align="center">
<i>Figura 6: Figura ilustrativa dos centros logísticos a serem abertos com uma diminuição da procura em 20 %</i>
</p>

