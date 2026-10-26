# My Deep Learning Journey

Welcome to my deep learning learning journey.

This repository is my collection of notes, experiments, mistakes, and
practice notebooks while learning how neural networks work. I started with
the basic perceptron and gradually moved toward dense neural networks,
computer vision, natural language processing, and recurrent neural networks.

I am keeping this repository as a record of my progress. Each phase represents
one step in my learning path, and the notebooks are meant to be read,
executed, changed, and improved rather than treated as finished projects.

## What I am learning

- How a perceptron learns simple decision boundaries
- How dense neural networks solve classification and regression problems
- How forward propagation and backpropagation work
- How to train models effectively and avoid overfitting
- How convolutional neural networks understand images
- How transfer learning can reuse existing visual features
- How text is converted into numbers for machine learning
- How embeddings and recurrent networks work with sequences
- How to experiment with model architecture and hyperparameters

## My learning path

### 1. Starting with perceptrons

I began by learning how a perceptron separates data into classes. The first
experiment uses AND, OR, and XOR data to make the idea of a decision boundary
more concrete.

- [L7 - Perceptron and decision boundaries](./1first_phase/L7.ipynb)

### 2. Building my first neural networks

After understanding the perceptron, I moved to multilayer networks. In this
phase I practiced MNIST classification, regression, dense layers, and
backpropagation. I also started implementing the learning process from
scratch to understand what frameworks do behind the scenes.

- [L12 - MNIST classification](./2sec_phase/L12.ipynb)
- [L13 - Multilayer perceptron for regression](./2sec_phase/L13.ipynb)
- [L14](./2sec_phase/L14.ipynb) · [L15](./2sec_phase/L15.ipynb)
- [L16 - Backpropagation for regression from scratch](./2sec_phase/L16.ipynb)
- [L16b - Backpropagation for classification from scratch](./2sec_phase/L16b.ipynb)
- [L17](./2sec_phase/L17.ipynb) · [L18](./2sec_phase/L18.ipynb)
- [L19](./2sec_phase/L19.ipynb) · [L20](./2sec_phase/L20.ipynb)

### 3. Understanding how models learn better

A model that can fit training data is not automatically a good model. I
explored scaling, early stopping, dropout, L2 regularization, and weight
initialization to understand how training can be made more stable and how
overfitting can be reduced.

- [L22 - Early stopping](./3third_phase/L22.ipynb)
- [L23 - Feature scaling](./3third_phase/L23.ipynb)
- [L24](./3third_phase/L24.ipynb)
- [L25 - Dropout](./3third_phase/L25.ipynb)
- [L26 - L2 regularization](./3third_phase/L26.ipynb)
- [L29 - Weight initialization with tanh and ReLU](./3third_phase/L29.ipynb)
- [L29b - Zero initialization with sigmoid](./3third_phase/L29b.ipynb)
- [L30 - Choosing initial weights](./3third_phase/L30.ipynb)

### 4. Improving training and tuning models

In this phase I continued experimenting with training behavior. I learned
about batch normalization and hyperparameter tuning, and used the remaining
notebooks for additional practice with neural networks.

- [L31 - Batch normalization](./4fourth_phase/L31.ipynb)
- [L32](./4fourth_phase/L32.ipynb) · [L33](./4fourth_phase/L33.ipynb)
- [L34](./4fourth_phase/L34.ipynb) · [L35](./4fourth_phase/L35.ipynb)
- [L36](./4fourth_phase/L36.ipynb) · [L37](./4fourth_phase/L37.ipynb)
- [L38](./4fourth_phase/L38.ipynb)
- [L39 - Hyperparameter tuning](./4fourth_phase/L39.ipynb)
- [L40](./4fourth_phase/L40.ipynb)

### 5. Moving into computer vision

Once I had a foundation in dense networks, I started learning how
convolutional neural networks process images. I practiced convolution,
padding, strides, pooling, and image classification using datasets such as
MNIST. I also worked toward a cat-versus-dog classifier.

- [L41](./5fifth_phase/L41.ipynb) · [L42](./5fifth_phase/L42.ipynb)
- [L43 - Convolution, padding, and strides](./5fifth_phase/L43.ipynb)
- [L44 - Pooling](./5fifth_phase/L44.ipynb)
- [L45](./5fifth_phase/L45.ipynb) · [L46](./5fifth_phase/L46.ipynb)
- [L47](./5fifth_phase/L47.ipynb) · [L48](./5fifth_phase/L48.ipynb)
- [L49 - Cat-versus-dog classifier](./5fifth_phase/L49.ipynb)
- [L50](./5fifth_phase/L50.ipynb)

### 6. Exploring transfer learning and text

My learning then expanded in two directions. For computer vision, I explored
visualizing CNN layers, VGG16, transfer learning, and the Keras functional
API. For NLP, I learned tokenization, integer encoding, embeddings, and
sentiment analysis with the IMDB dataset.

- [L51](./6six_phase/L51.ipynb)
- [L52 - Visualizing CNN layers with VGG16](./6six_phase/L52.ipynb)
- [L53 - Transfer learning](./6six_phase/L53.ipynb)
- [L54 - Nonlinear functional model](./6six_phase/L54.ipynb)
- [L55](./6six_phase/L55.ipynb)
- [L57 - Sentiment analysis with integer encoding](./6six_phase/L57.ipynb)
- [L57b - Sentiment analysis with embeddings](./6six_phase/L57b.ipynb)
- [L58](./6six_phase/L58.ipynb) · [L59](./6six_phase/L59.ipynb)
- [L60](./6six_phase/L60.ipynb)

### 7. Learning sequence models

In this phase I started working with sequential data. I practiced text
tokenization, next-word prediction, sentiment analysis, and deeper recurrent
neural networks.

- [L61](./7seven_phase/L61.ipynb) · [L62](./7seven_phase/L62.ipynb)
- [L63 - Next-word prediction](./7seven_phase/L63.ipynb)
- [L64](./7seven_phase/L64.ipynb)
- [L65 - Deep RNN](./7seven_phase/L65.ipynb)
- [L66](./7seven_phase/L66.ipynb) · [L67](./7seven_phase/L67.ipynb)
- [L68](./7seven_phase/L68.ipynb) · [L69](./7seven_phase/L69.ipynb)
- [L70](./7seven_phase/L70.ipynb)

### 8. Continuing the journey

The eighth phase contains my later experiments. The notebooks from L71 to
L80 do not currently have descriptive titles inside them, so I am keeping
their names simple until I document what I learn from each one.

- [L71](./8eight_phase/L71.ipynb) · [L72](./8eight_phase/L72.ipynb)
- [L73](./8eight_phase/L73.ipynb) · [L74](./8eight_phase/L74.ipynb)
- [L75](./8eight_phase/L75.ipynb) · [L76](./8eight_phase/L76.ipynb)
- [L77](./8eight_phase/L77.ipynb) · [L78](./8eight_phase/L78.ipynb)
- [L79](./8eight_phase/L79.ipynb) · [L80](./8eight_phase/L80.ipynb)

## Tools and technologies

Throughout this journey I have used:

- Python
- Jupyter Notebook
- NumPy and pandas
- Matplotlib and Seaborn
- scikit-learn
- TensorFlow and Keras
- mlxtend for visualizing decision regions

## How to explore this repository

The best way to use this repository is to follow the phases in order:

1. Open a notebook.
2. Read the explanations and inspect the code.
3. Run the cells yourself.
4. Change the model, data, or hyperparameters.
5. Record what worked, what failed, and what you learned.

To prepare a Python environment, install the main packages with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras mlxtend jupyter
```

Some notebooks use datasets that are outside this repository, including:

- `ML/datasets/add_pred.csv`
- `ML/datasets/sal_par.csv`
- `ML/datasets/placement.csv`
- `datasets/concentric_circle.csv`

Those files need to be available at the paths expected by the notebooks.
Some notebooks download datasets such as MNIST and IMDB through Keras.

## A work in progress

This repository is not meant to show only perfect results. It shows the
process of learning: starting with simple ideas, making experiments, finding
mistakes, and gradually understanding more advanced models.

I will continue adding explanations, improving old notebooks, and documenting
new discoveries as my deep learning journey continues.
