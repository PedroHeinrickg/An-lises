# MODELO DE PREDIÇÃO PARA MÚSICAS DO SPOTIFY
Este notebook tem como objetivo criar um modelo de análise preditiva para classificar músicas em lenta ou agitada utilizando a base de dados "Spotify Tracks Dataset" do Kaggle.

O Primeiro passo do projeto foi conhecer os dados e a estrutura das tabela:
De acordo com a regra da empresa, uma medida de 0,0 a 1,0 que descreve a positividade musical transmitida por uma faixa. Faixas com alta valência soam mais positivas, enquanto faixas com baixa valência soam mais negativas. Para criar um modelo preditivo, utilizei a coluna "valence" para ser nosso critério de músicas agitadas ou lentas, adotando o critério de valence >0.5 = agitada e valence < 0.5 = lenta.

Após analisar os dados e identificar o melhor método de análise de predição e aplica-lo, foi feito a avaliação dos dados relativos para verifcar  e comparar a taxa de erros e acertos, comparando as variáveis 'popularity', 'duration_ms', 'danceability', 'energy', 'loudness', 'acousticness', 'instrumentalness', 'liveness' com a variável 'valence'. A taxa de sucesso é de 90.27%.
