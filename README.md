# Rede Neural Didática
Uma página interativa para brincar com uma rede neural de 2 camadas (5 neurônios) para fins didáticos.

DESCRIÇÃO
Essa é uma rede pensada para identificar frutas entre maçãs e laranjas.
Os 3 neurônios da primeira camada são sensores: cor amarela, cor vermelha e rugosidade da casca.
Os 2 neurônios da segunda camada são as saídas, indicando a chance de ser uma maçã e uma laranja.
Você pode mexer em todos os parâmetros das conexões entre os neurônios:
	Cada conexão tem um parâmetro w ("weights" ou pesos)
	Cada neurônio da segunda camada tem um parâmetro b ("bias" ou limiar)
O valor de ativação de cada neurônio da segunda camada é simplesmente:
	S = Amarelo*w1 + Vermelho*w2 + Rugosidade*w3 + b
Ou seja, cada entrada (Amarelo, Vermelho e Rugosidade) recebe um peso dado pelo W da conexão e é somada ao limiar b do neurônio.

INSTALAÇÃO
Baixe o conteúdo, coloque tudo numa pasta, e clique em index.html