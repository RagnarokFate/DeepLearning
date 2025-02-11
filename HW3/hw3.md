CS University of Haifa

Deep Learning HW3

Text Generation & Latent Space Visualization

This assignment explores two fascinating aspects of deep learning, using sequential models for text generation in natural language processing (NLP) and visualizing latent representations in generative models. Through this assignment, you will gain hands-on experience with key concepts in sequence learning and a taste of generative AI, helping you build an intuitive understanding of model capabilities and representations.

Part 1: (Song Lyrics Generation)

The first task you are going to tackle is associated with text generation. The first step is to download the data from the website. The data is given as a csv file which contains the artist name, song name, and song lyrics.

1. Study the data:

- Import the file into your notebook and showcase a couple of rows from it.

- Print all of the artist’s names and show how many songs are associated with each artist.

- Print the size of the dataset and how many songs are there.

- Print the average number of characters and words of a song for all songs lyrics in the dataset (the average length of a song).

- A nice way to visualize text data with repeated words is by using a word cloud image.

- Go over all the songs lyrics and print the top 3 most used words in the songs.

Part 2: (Latent Space Visualization)

In deep learning, the latent space represents a compressed, abstract representation of input data learned by a model. Exploring this latent space helps us understand how models learn and group similar data points.

In this assignment, you will train an autoencoder to project the MNIST images into a lower-dimensional latent space, and visualize the generations as a function of latent codes. You will then explore how these representations capture the structure of the data, and visualize the linear interpolation between different digits. By the end of this assignment, you will better understand how neural networks encode meaningful features of input data.

To start, download the given notebook from the website.

Tasks for Part 2:

1. Implement the following:

- The Encoder

- The Decoder

- The Variational AutoEncoder

- The Following Loss Function from scratch:

- L(x,x^,μ,σ)=BCE(x^,x)+21​∑(1+logσ2−μ2−exp(logσ2))

- A function to generate and plot a handwritten digit.

- A function to plot the latent space.

- A linear interpolation function between 2 randomly selected digits.

2. The training loop is set for 50 epochs; you should modify it and add a piece of code that generates an image for the digit 8 and the digit 6 every 10 epochs, allowing you to see how the model is learning and generating better images each time.

3. Running the code with your implementations should get you 2 latent space visualizations with different scalabilities. In the end result, you should see linear interpolations between different digits, clearly visualizing where each digit class is clustered in the space.

Final Submission Requirements:

- For this assignment, make sure your submission is clear and well-organized.

- Include a notebook for each part of the assignment with all code cells run and explained.

- Submit your 2 ipynb files with their names being HW3_PT1_ID1_ID2.ipynb & HW3_PT2_ID1_ID2.ipynb.

- Add text cells to introduce each section, explaining what you did and why. Keep your notebooks tidy and easy to follow, with the names of all group members at the top.

- Include comments in your code and use text to describe what you’re doing in each section. Visualize your results with plots that help explain the data and model performance.

- Print each model you use, showing the layer details and the total number of parameters.

Note on Libraries:

Only the PyTorch library can be used as a deep learning tool to work with the models; you can’t use Keras or TensorFlow under any circumstances. You may use other libraries for manipulating the dataset and preprocessing as long as it doesn’t affect the model definition within PyTorch.

TA: Jerry Abu Ayoub Winter 2024
