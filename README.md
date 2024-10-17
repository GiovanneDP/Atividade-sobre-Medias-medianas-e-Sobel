# Atividade-sobre-Medias-medianas-e-Sobel
*Nessa atividade, vou destacar as principais diferencas entre os filtros de media e mediana, alem de explicar para qual situacao seria melhor utilizar esses filtros e responder as respectivas perguntas*


a) Como a imagem original mudou após a aplicação de cada filtro?
R: Aplicando o filtro de Media, podemos perceber que a imagem foi suavizada de modo que fosse definido uma media entre os pixels vizinhos.
O filtro de mediana faz com que uma maior parte dos pixels encontrem a media e definam um tom de cinza em comum. 
Ja o filtro de Sobel aplicou um destaque, fazendo com que fique mais facil a visualizacao das bordas.

b) Qual filtro foi mais eficaz para suavizar a imagem?
R: O filtro mais eficaz foi o de mediana, que fez uma suavizacao mais precisa.

c) E qual foi mais eficaz para destacar as bordas?
R: Para destacar as bordas, o filtro de Sobel foi mais eficaz.

d) Quais situações podem exigir o uso de cada tipo de filtro em um projeto real?
R: As situacoes pode ser adversas, porem se pudesse destacar uma para cada, para o filtro de media, poderia ser usado para suavizar imagens com muito ruido, para a mediana, podemos colocar uma foto e suavizar a partir do fundo, assim nao gerando efeitos nas bordas, e por fim o Sobel, pode ser usado para destacar ou destinguir certos objetos, arestas ou ate dar destaque ao que realmente queremos ver, como uma placa, onde o fundo e o que esta escrito quase tem a mesma tonalidade, auxiliando na leitura.

4. Experimentar:
1. Experimentar diferentes tamanhos de kernel nos filtros de média e
mediana (por exemplo, (3, 3), (5, 5), etc.) e observar como isso afeta a
suavização da imagem.
R: Realizando esse experimento podemos destacar o quanto a media tende a suavizar quase juntando os pixels, tornando quase uma tonalidade soh, ja o mediana eh suavizado de modo que fique mais equilibrado, sem perder muito o foco da imagem
