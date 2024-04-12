Favelas e comunidades urbanas possuem uma dinâmica própria de expansão e esta dinâmica traz consigo uma demanda por políticas públicas específicas para essas áreas. Para garantir políticas públicas adequadas é importante acompanhar as modificações ocorridas ao longo do tempo, 
inclusive a sua expansão ou retração. O trabalho propõe o uso de múltiplas técnicas e algoritmos de machine learning para a identificação de favelas e comunidades urbanas do bairro da Pavuna, na cidade do Rio de janeiro, além de avaliar a possibilidade de expandir a aplicação para outras áreas do município.

![Imagem de satélite e máscara](imagem original.jpeg)


O pré-processamento da imagem utiliza algoritmos baseados em segmentação de superpixel pelos métodos de Felzenszwalbs e SLIC, adicionando a média, mediana e desvio padrão das bandas para cada método de superpixel à imagem original. Além da adição de medidas representativas das distribuições espectrais dos superpixels, 
foi o índice de forma espacial (SSI) à imagem original, totalizando sete novas características além do RGB natural da imagem.

Os seguintes algoritmos foram selecionados para teste: LightGBM, MLP Classifier, Random Forest, Gradient Boosting, K-Means, Naive-Bayes e Logistic-regression.

