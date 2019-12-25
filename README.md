# fashionMNIST-with-julia-fastAI
Tackling the [FashionMNIST](https://github.com/zalandoresearch/fashion-mnist) dataset with a simple multilayer perceptron and a pre-trained ResNet34 model as part of a [task](https://codein.withgoogle.com/dashboard/task-instances/5002280944795648/) in *The Julia Programming Language* during Google Code-in

Extensive explaination in the notebooks.

## Results

| Model                 	| Accuracy 	| Training Time 	| Edit 	|
|-----------------------	|----------	|:-------------:	|------	|
| Flux: 2-layer NN      	| 0.8287   	|    0:16:03    	|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PseudoCodeNerd/fashionMNIST-with-julia-fastAI/blob/master/flux-FMNIST-detailed.ipynb)|
| pyTorch: ResNet34 CNN 	| 0.8565   	|    0:03:19    	|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PseudoCodeNerd/fashionMNIST-with-julia-fastAI/blob/master/FashionMNIST-resnet34.ipynb)|
| Flux: ConvNet (3C,3MP,1D,1Sm)|0.9022|1:07:34|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PseudoCodeNerd/fashionMNIST-with-julia-fastAI/blob/master/flux-FMNIST-detailed.ipynb)|
