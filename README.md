# 🧠🤖 Deep Learning - Classificação de Imagens 

Este projeto  utiliza a combinação das bibliotecas ImageAI e TensorFlow para criar um modelo de deep learning capaz de classificar imagens de pulmões em três categorias: normal, pneumonia viral e coronavírus.

## 📋Requisitos
Certifique-se de ter as seguintes dependências instaladas em seu ambiente de desenvolvimento:

- [Python 3.x](https://www.python.org/downloads/)
- [TensorFlow](https://www.tensorflow.org/?hl=pt-br)
- [ImageAI](https://github.com/OlafenwaMoses/ImageAI)
- [NumPy](https://numpy.org)
- [OpenCV](https://docs.opencv.org/4.x/)

Você pode instalá-las executando o comando abaixo:

``` 
 pip install tensorflow imageai numpy opencv-python jupyter

```

## 📁 Estrutura do Projeto:

 - data/: Aqui você encontrará as imagens de treinamento e teste organizadas por classe.<br>
 - data/models/: arquivo json com as classes e os modelos que foram treinados<br>
         -  normal/: Imagens de pulmões normais.<br>
         -  pneumonia/: Imagens de pulmões com pneumonia.<br>
         -  coronavirus/: Imagens de pulmões com coronavírus.<br>
train.ipynb: Use esse notebook Jupyter para treinar o modelo de classificação de imagens.<br>
predict.ipynb: Use esse notebook Jupyter para fazer previsões e classificar novas imagens.<br>

## 🚀 Treinando o Modelo:

Certifique-se de que suas imagens de treinamento e teste estejam organizadas corretamente dentro da pasta data/.
Abra o notebook train.ipynb em sua IDE preferida, utilizei o Jupyter Notebook.
Execute cada célula do notebook para carregar as imagens, criar o modelo de classificação e iniciar o treinamento.
Ao final do treinamento, seu modelo será salvo na pasta data/models/.

## 🔍 Fazendo Previsões/Classificações:

Tenha em mãos uma imagem de pulmão que deseja classificar.
Você pode abrir o notebook predict.ipynb em uma IDE como o Jupyter Notebook.
Execute cada célula do notebook para carregar o modelo treinado e abrir a interface. Faça uploud de uma imagem para fazer a previsão/classificação da imagem e exibir o resultado.

### [🔗 Covid-19 Image Dataset](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset)
