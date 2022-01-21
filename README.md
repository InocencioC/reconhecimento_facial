#Reconhecimento_facial

É uma aplicação para reconhecimento de rostos faciais, consumindo uma api(face api), ela usa modelos de rostos já treinados para uma melhor identificação.

#Modelos de detecção de rosto

Para detecção de face, este projeto implementa um SSD (Single Shot Multibox Detector) baseado em MobileNetV1.
A rede neural calculará as localizações de cada face em uma imagem e retornará as caixas delimitadoras junto com sua probabilidade da face. 
Este detector de face visa obter alta precisão na detecção de caixas delimitadoras de face em vez de baixo tempo de inferência.
