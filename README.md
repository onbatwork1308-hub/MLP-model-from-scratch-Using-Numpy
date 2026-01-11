<h1>MLP Model From Scratch Using NumPy (MNIST)</h1>
<p>
  This repository contains a fully from-scratch implementation 
  of a Multilayer Perceptron (MLP) trained on the MNIST handwritten
  digit dataset, implemented entirely using NumPy.
  <b><h3>Overview</h3></b>
  No deep learning frameworks (PyTorch, TensorFlow, Keras) were used for:
  <ul type='bullet'>
    <li>Forward propagation</li>
    <li>Backward propagation</li>
    <li>Loss computation</li>
    <li>Optimization</li>
    <li>Early stopping</li>
  </ul>
</p>
<p>
  <b><h3>Key Objectives</h3></b>
  <ul>
  <li>Implement a neural network without using any machine learning frameworks</li>
  <li>Understand the mathematics of backpropagation</li>
  <li>Manually implement:
    <ul>
      <li>Weight initialization</li>
      <li>Gradient computation</li>
      <li>Parameter updates</li>
      <li>Training loop</li>
    </ul>
  </li>
  <li>Validate performance on a real-world dataset (MNIST)</li>
</ul>
</p>
<p>
  <b><h3>Features Implemented</h3></b>
<ul>
  <li>Forward propagation</li>
  <li>Backward propagation (gradient computation)</li>
  <li>Loss functions (e.g. cross-entropy)</li>
  <li>Weight initialization(Xavier normal, kaiming normal)</li>
  <li>Activation functions (ReLU, Softmax, etc.)</li>
  <li>Optimizers (e.g. gradient descent)</li>
  <li>Mini-batch training</li>
  <li>Early stopping</li>
  <li>Accuracy evaluation</li>
  <li>Numerical stability handling</li>
</ul>
</p>
<p>
  <b><h3>Training Details</h3></b>
  <ul>
  <li><strong>Dataset:</strong> MNIST</li>
  <li><strong>Input size:</strong> 784 (28×28 flattened images)</li>
  <li><strong>Hidden layers:</strong> Fully connected</li>
  <li><strong>Output size:</strong> 10 (digits 0–9)</li>
  <li><strong>Optimization:</strong> Gradient Descent</li>
  <li><strong>Loss:</strong> Cross-Entropy</li>
  <li><strong>Early stopping:</strong> Based on validation loss</li>
</ul>
</p>
<p>
  <b><h3>Results</h3></b>
  <ul>
  <li>Training accuracy: ~99%</li>
  <li>Validation accuracy: ~97–98%</li>
  <li>Testing accuracy: ~98%</li>
  <li>Stable convergence without exploding or vanishing gradients</li>
</ul>

</p>
