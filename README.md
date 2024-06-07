# Engenheiro_de_Desafios-Parte_Dois-Python_APIs
# Mirar 

Faça uma análise da oferta/janela de opções de produtos que respondem às diferentes pesquisas no site Mercadolibre.com.ar  utilizando a linguagem Python e as bibliotecas que considerar necessárias. 

# 1) Digitalize uma lista de mais de 150 IDs de itens no serviço público:
https://api.mercadolibre.com/sites/MLA/search?q=chromecast&limit=50#json 

Neste caso particular e apenas a título de exemplo, são resultados da pesquisa “ chromecast” , mas deve escolher outros termos para a experiência que lhe permitam enriquecer a análise num dashboard hipotético (por exemplo Google Home, Apple TV, Amazon Fire TV, ou para poder comparar dispositivos portáteis, ou escolha 3 outros que lhe interessam para comparar).
# 2) Para cada resultado, realize o GET by Item_Id correspondente ao recurso público:
https://api.mercadolibre.com/items/{Item_Id}
# 3) Escreva os resultados:
Escreva os resultados em um arquivo simples delimitado por vírgulas, desnormalizando o JSON obtido na etapa anterior, em quantos campos forem necessários para salvar as variáveis ​​que você tem interesse em modelar.  
# 4) Preparar o desenho e documentação da solução:
Apresente uma solução para este cenário criando um diagrama de alto nível da solução e documentando as etapas necessárias para atingir esse objetivo.
# 5) Análise exploratória:
Realize uma análise exploratória com as variáveis ​​selecionadas para o modelo através de um notebook Jupyter.
