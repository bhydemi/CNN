<!-- # Building a Complete CNN: Understanding Convolutional Neural Networks from Input to Output -->

## Introduction :pencil2:

This activity will help you practice and assess the knowledge and skills you just learned about convolutional neural networks (CNNs). By using an interactive CNN visualization tool, you will explore how different layers—input, convolutional, activation functions, pooling, flattening, and fully connected layers—work together to classify images.

During this exercise, you will delve deeper into the operations of each layer within a CNN, understand how images are transformed at each step, and observe how the network learns to recognize patterns and features essential for classification tasks.

We encourage you to further explore the tool after completing this activity to solidify your understanding and discover more about CNNs.

**Note:** There is no predefined solution for this activity. The objective is to interact with the CNN Explainer tool and gain a comprehensive understanding of how CNNs function.

It is important to understand the reasoning behind each operation in order to improve your own understanding and problem-solving abilities.

<br>

## Exploring a Complete CNN Model with CNN Explainer

### Instructions

<br>

Learn about [Convolutional Neural Networks](https://poloclub.github.io/cnn-explainer/) by interacting with the CNN Explainer tool.

<br>

<details style="font-size: 14px; cursor: pointer; outline: none;">
<summary> Click for Solution </summary>

This activity involves exploring the CNN Explainer tool; there is no single solution. Engage with each layer to understand its function.

</details>

<br>

## Understanding Each Layer of a CNN

### Instructions

1. **Visit the CNN Explainer Tool:** Navigate to the [CNN Explainer](https://poloclub.github.io/cnn-explainer/) to begin your exploration.

2. **Select an Image:** Choose one of the preloaded images (e.g., lifeboat, ladybug, pizza) or upload your own image to see how the CNN processes it from input to output.

3. **Examine the Input Layer:**
   - Observe how the input image is represented in terms of its RGB channels.
   - Click on the **Input Layer** to see the separate Red, Green, and Blue channels.
   - Notice how each channel contributes to the overall image.

4. **Explore Convolutional Layers:**
   - Click on the **Convolutional Layers** (e.g., `conv_1_1`, `conv_1_2`) to see how kernels are applied to the input.
   - Observe the kernels (filters) used and how they detect features like edges, textures, and patterns.
   - Hover over the links between layers to see the kernels' weights and biases.
   - Use the **Interactive Formula View** by clicking on a convolutional neuron to see the convolution operation step-by-step.

5. **Understand Activation Functions (ReLU):**
   - Click on the **ReLU Activation Layers** (e.g., `relu_1_1`, `relu_1_2`) to see how the activation function is applied.
   - Notice how ReLU sets negative values to zero, introducing non-linearity.
   - Observe the effect of ReLU on the activation maps.

6. **Investigate Pooling Layers:**
   - Click on the **Max Pooling Layers** (e.g., `max_pool_1`) to understand how they reduce the spatial dimensions.
   - Observe how max pooling retains the most important features while reducing the size of the data.
   - Use the **Interactive Formula View** to see how the max pooling operation selects the maximum value in each region.

7. **Examine the Flatten Layer:**
   - See how the multi-dimensional data is flattened into a one-dimensional vector to be fed into the fully connected layers.
   - Understand why flattening is necessary before classification.

8. **Explore the Output Layer:**
   - Click on the **Output Layer** to see how the network produces a probability distribution over the possible classes using the Softmax function.
   - Observe the logits (unscaled outputs) before softmax and how they are converted into probabilities.
   - Use the **Interactive Formula View** to see the Softmax calculation.

9. **Interactive Features:**
   - Experiment with changing the activation map color scales to better understand the activations at different layers.
   - Use the **Network Details** icon to view detailed information about each layer, including dimensions and hyperparameters.
   - Click on the **Play** button to simulate the network operations step-by-step.
   - Try uploading your own image using the **Upload Image** button to see how the CNN classifies it.

<br>

<details style="font-size: 14px; cursor: pointer; outline: none;">
<summary> Click for Tips </summary>

1. In the convolutional layers, pay attention to how different kernels detect various features in the image.
2. Notice the importance of non-linearity introduced by the ReLU activation function.
3. Observe how max pooling layers help in reducing overfitting by discarding less important activations.
4. Understand how the Softmax function in the output layer converts logits into probabilities for classification.

</details>

<br>

## Reflecting on Your CNN Exploration

### Instructions

1. **Analyze Each Layer's Role:**
   - Write down your observations on how each layer transforms the input data.
   - How do convolutional layers contribute to feature extraction?
   - What is the impact of the ReLU activation function on the data?
   - How do pooling layers help in reducing computational complexity and overfitting?
   - Why is the flattening step necessary before the fully connected layers?
   - How does the Softmax function in the output layer help in classification?

2. **Evaluate the Network's Performance:**
   - Did the CNN correctly classify the image? What class did it predict?
   - What were the confidence levels (probabilities) for each class?
   - How does the network's architecture (e.g., number of layers, kernel sizes) affect its classification ability?

3. **Document Your Findings:**
   - Provide a brief report summarizing your exploration.
   - Include screenshots of key stages (e.g., convolutional layers, pooling layers, output layer).
   - Explain how the CNN processes an image from input to output, highlighting the key transformations at each layer.

<br>

<details style="font-size: 14px; cursor: pointer; outline: none;">
<summary> Click for Example Analysis </summary>

Upon examining the CNN using the image of a "pizza," I observed the following:

- **Convolutional Layers:** The convolutional layers applied multiple kernels to detect edges and patterns in the image. The kernels highlighted features such as the circular shape of the pizza and the textures of the toppings.
- **ReLU Activation:** The ReLU layers introduced non-linearity by setting negative values to zero, which helped in emphasizing important features and discarding irrelevant ones.
- **Pooling Layers:** The max pooling layers reduced the spatial dimensions of the data, making the network more computationally efficient. Despite the reduction, key features like the pizza's outline remained prominent.
- **Flatten Layer:** The data was flattened into a one-dimensional vector, preparing it for the fully connected output layer.
- **Output Layer:** The Softmax function converted the logits into probabilities. The network predicted the image as "pizza" with a confidence level of 98%, correctly classifying the image.

Overall, each layer played a crucial role in transforming the input image into a set of features that could be used for accurate classification.

</details>

<!-- keep adding as many as you find suitable -->
