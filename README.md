# various-Networks-Separation-index
The subsequent code implementation delineates the functionalities of the Ranking Model and the Evaluation-wise Layer, two pivotal components within the realm of neural network architecture.

Within each code segment, a neural network instantiation procedure is conducted leveraging the Fashion MNIST dataset. Specifically, the instantiated networks are constructed utilizing two prominent architectures: ResNet18 and EfficientNetB0.

For the layer antecedent to the classifier, an intricate analysis involving the computation of five distinct geometric branches has been undertaken. These branches encompass methodologies such as Center-Based, High Order Soft SI (2), High Order SI (2), First Order SI, and SI Anti (2), each geared towards augmenting the network's feature extraction capabilities.

Now, let us delve deeper into the salient features of the principal components:

Ranking Model: A pivotal construct in machine learning, the Ranking Model assumes significance in contexts where the ranking of instances or items based on predefined features or criteria is imperative. This model often harnesses the power of neural networks to discern intricate patterns within the data, subsequently facilitating informed ranking decisions.

Evaluation-wise Layer: This architectural facet signifies the incorporation of a dedicated layer within the neural network framework, specifically tailored to the evaluation phase. Tasked with computing pertinent metrics or scores indicative of model performance, this layer serves as a critical cog in the iterative process of model refinement and validation.

Fashion MNIST Dataset: Renowned for its utility as a standardized benchmark dataset within the domain of computer vision, the Fashion MNIST dataset encapsulates grayscale images depicting various fashion items, including apparel and accessories. Its widespread adoption stems from its ability to effectively evaluate the efficacy of machine learning algorithms across diverse classification tasks.

Neural Network Architectures: The utilization of ResNet18 and EfficientNetB0 architectures underscores a commitment to leveraging state-of-the-art methodologies for image classification tasks. ResNet18, characterized by its incorporation of residual connections, and EfficientNetB0, acclaimed for its efficiency in balancing model size and performance, represent pillars of contemporary deep learning research.

Geometric Branches: These branches epitomize the multifaceted nature of feature extraction techniques employed within neural networks. By computing specific geometric properties or transformations of input data, these branches facilitate nuanced representations conducive to enhanced classification accuracy and generalization performance.

In summary, the amalgamation of these components within the codebase delineates a rigorous and academically grounded approach to constructing and evaluating neural network models tailored to the nuances of the Fashion MNIST dataset. Through the judicious selection of architectures and methodologies, the endeavor seeks to advance the frontier of machine learning research with a focus on principled model development and empirical validation.

Accuracy and separation index of ResNet18: 
![image](https://github.com/fmirzadeh99/various-Networks-Separation-index/assets/169579231/9c8408de-ab0e-4357-8ad3-e05b0ae553e5)


Accuracy and separation index of EfficientnetB0: 
![image](https://github.com/fmirzadeh99/various-Networks-Separation-index/assets/169579231/5b2d6e35-f8a2-4984-bd0c-6ba18dfe9671)


