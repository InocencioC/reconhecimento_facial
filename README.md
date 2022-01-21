#Reconhecimento_facial

É uma aplicação para reconhecimento de rostos faciais, consumindo uma api(face api), ela usa modelos de rostos já treinados para uma melhor identificação.

#Modelos de detecção de rosto

Para detecção de face, este projeto implementa um SSD (Single Shot Multibox Detector) baseado em MobileNetV1.
A rede neural calculará as localizações de cada face em uma imagem e retornará as caixas delimitadoras junto com sua probabilidade da face. 
Este detector de face visa obter alta precisão na detecção de caixas delimitadoras de face em vez de baixo tempo de inferência.

![Captura de ecrã de 2022-01-21 16-02-24](https://user-images.githubusercontent.com/34503843/150554658-a9562e4e-4b14-4471-b6c9-5b596647dadd.png)

#Modelo de reconhecimento de expressão facial

O modelo de reconhecimento de expressão facial é leve, rápido e oferece uma precisão razoável. O modelo tem um tamanho de aproximadamente 310kb e emprega convoluções separáveis em profundidade e blocos densamente conectados. Ele foi treinado em uma variedade de imagens de conjuntos de dados disponíveis publicamente, bem como imagens extraídas da internet. Observe que o uso de óculos pode diminuir a precisão dos resultados da previsão. E com este modelo é possível reconhecer se a pessoa está triste, alegre, com raiva e uma expressão neutra. 

![Captura de ecrã de 2022-01-21 16-03-21](https://user-images.githubusercontent.com/34503843/150554672-5affa0a9-7d3a-495a-acf2-22dd33099970.png)
