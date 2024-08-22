# relA
relA gene analysis

# Métodos

O complexo NF-κB foi analisado utilizando a estrutura 1NFI do PDB para marcar o local da mutação na subunidade NFKBIA, enquanto a estrutura da subunidade RelA inteira (p65) foi obtida do AlphaFold. A visualização foi realizada para destacar as subunidades p65, p50 e NFKBIA e identificar o contexto estrutural da mutação. Os dados de fosforilação foram integrados a partir do banco de dados UniProt. As pontuações de patogenicidade foram calculadas usando o AlphaMissense com o intuito de avaliar a essencialidade das regiões afetadas pelos novos códons de parada introduzidos, que podem resultar na perda de regiões críticas da proteína.

<div style="display: flex; justify-content: center;">
  <img src="https://github.com/izzetbiophysicist/relA/blob/main/Slide1.PNG" style="width: 80%; max-width: 400px;" />
</div>

Figura 1. Contexto estrutural da mutação. (A) Representação estrutural do complexo NF-κB mostrando as subunidades p65 (verde), p50 (amarelo) e NFKBIA (vermelho). O local da mutação em NFKBIA está destacado com um círculo tracejado. (B) Estrutura proteica predita pelo AlphaFold colorida de acordo com os valores de pLDDT (predicted Local Distance Difference Test), variando de baixa (vermelho, <50) a alta (azul, 100).


<div style="display: flex; justify-content: center;">
  <img src="https://github.com/izzetbiophysicist/relA/blob/main/Slide2.PNG" style="width: 80%; max-width: 400px;" />
</div>

Figura 2. Mapeamento de essencialidade. O mapa de calor mostra as pontuações de patogenicidade do AlphaMissense por posição para cada resíduo de aminoácido ao longo da sequência proteica. O eixo y representa os 20 aminoácidos padrão, e o eixo x representa o índice dos resíduos. Pontos verdes indicam resíduos anotados como fosforilados.


# Resultados / Discussão

Ao analisar os dados cristalográficos, o códon de parada parece não interferir na interação entre a p65 e as outras subunidades do complexo NF-κB. A introdução do códon de parada resulta na perda de uma região da subunidade p65 que é predita com baixo grau de confiança pelo AlphaFold, sugerindo que essa região pode ser inerentemente desordenada ou difícil de modelar com precisão.
Apesar da baixa confiança na predição, foram avaliadas a essencialidade e a patogenicidade da região truncada. Dados de fosforilação, obtidos da UniProt, indicam que existem diversos sítios de fosforilação nas regiões afetadas pelo códon de parada, as regiões também parecem ser essenciais, uma vez que apresentam faixas de mutações provavelmente patogênicas. A perda desses sítios de fosforilação pode ter implicações significativas para a regulação da atividade da p65 e suas interações dentro do complexo NF-κB. A introdução do códon de parada provavelmente perturba domínios funcionais chave.
