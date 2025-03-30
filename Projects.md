# Projects

This is where I have organized my projects, which contains a compilation of various coding and research endeavors, showcasing work in machine learning, numerical methods, optimization, and other computational fields.

## Research Projects

These projects showcase research I have conducted independently or in collaboration with others. They primarily involve in-depth explorations of complex topics, often involving novel methodologies or advanced techniques in machine learning, signal processing, and mathematical modeling.

<table>
  <thead>
    <tr>
      <th width=275>Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/seon9cho/SourceSeparation">Source Separation</a></td>
      <td>Unsupervised source separation of music recordings by learning the timbre of different instruments and reconstructing to match the original audio</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/ImageEncoder">Language Image Encoder</a></td>
      <td>End-to-end autoencoder model using the transformer, with an encoder that can encode sentences into fixed-length latent vectors and a decoder that can reconstruct the sentences using image representations.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/ActiveListener">Active Listener</a></td>
      <td>A voice assistant that improves accuracy by asking clarifying questions before responding to user queries. The system learns unsupervised, requiring only user queries to generate clarifications dynamically. This approach reduces errors and ambiguity, enhancing user interactions without relying on predefined intent-response pairs.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/DeepfakeDetection">Deepfake Detection</a></td>
      <td>The goal of this work is to reliably distinguish deepfaked videos from untampered videos. To improve coverage and accuracy, multiple approaches to deepfake detection are used&mdash;such as image classification of video frames and analyzing lip sync between audio and video).</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/SemisupervisedTranslation">Semi-supervised Translation</a></td>
      <td>With recent advancements in semi-supervised and unsupervised learning methods, this project aims to explore training a semi-supervised machine translation system by first independently training language models for two different languages and then aligning them using a small number of supervised examples.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/speech2phone">speech2phone</a></td>
      <td>This work extends speech recognition problem by converting raw audio into discrete phonemes instead of direct language transcription. For classifying phonemes, several classical machine learning techniques such as dimensionality reduction is used with deep neural nets. Phoneme segmentation of raw audio is approached with reinforcement learning model.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/EigenvalueApproximation">Eigenvalue Approximation</a></td>
      <td>This research explores a novel approach to approximating eigenvalues by leveraging Isospectral Matrix Reduction and Gershgorin’s Circle Theorem. By reducing a matrix while preserving its spectral properties and refining eigenvalue estimates using Gershgorin regions, this method offers an alternative perspective to traditional eigenvalue-solving algorithms.</td>
    </tr>
  </tbody>
</table>





***

## Small Projects

These are smaller-scale projects focused on implementing and applying existing methods and models. Each project is built from the ground up and serves as a reference for more advanced research topics. The work primarily involves developing deep learning models, various machine learning algorithms, and physical system modeling.

<table>
  <thead>
    <tr>
      <th width=275>Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/seon9cho/COVID-DataAssimilation">COVID Data Assimilation</a></td>
      <td>Predict COVID with data assimilation techniques. The data is modeled as an SIR model, which is then assimilated with the adjoint method using calculus of variation.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/4D-Var">4D-Var</a></td>
      <td>Simulate Lorenz-63 model by derivation of strong-constraint 4D-Var algorithm. It is then applied to predict real world weather data with temperature, humidity, and pressure.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/WildFire">Wildfire Modeling</a></td>
      <td>Model the behavior and spread of wildfire using the Crank-Nicholson Scheme.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/IMDbScorePrediction">IMDb Score Prediction</a></td>
      <td>Predict IMDb score of movies using concrete data such as gross revenue, genre, and budget of the movie.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/EulerMaruyama">Stochastic Differential Equations Modeling</a></td>
      <td>Predict the future value of the stock using the model $\frac{dS}{S} = \mu dt + \sigma dW$ with the Euler-Maruyama method and the Milstein method.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/BVPSolverCollocation">Boundary Value Problem Solver using Collocation</a></td>
      <td>Solve Boundary Value Problem, an ODE problem with boundary conditions, by using collocation at Chebyshev nodes.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/ProximalPolicyOptimization">Proximal Policy Optimization</a></td>
      <td>Implementation of the Proximal Policy Optimization model as described in <a href="https://arxiv.org/abs/1707.06347">this paper</a>. The model is trained to learn <a href="https://www.gymlibrary.dev/environments/classic_control/cart_pole/">CartPole from the gym library</a>, a classical control problem.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/GenerativeAdversarialNetworks">Generative Adversarial Networks</a></td>
      <td>Implementation of the Generative Adversarial Networks as described from <a href="https://arxiv.org/abs/1406.2661">this paper</a>. The generative and discrimative models are trained on CelebA data, after which the generative model is used to generate new faces.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/Transformer">Transformer</a></td>
      <td>Implementation of the <a href="https://arxiv.org/abs/1706.03762">Transformer</a> architecture, following the <a href="https://nlp.seas.harvard.edu/2018/04/03/attention.html">Annotated Transformer</a>. The model is trained to translate between English and Spanish using General Conference data.</td>
    </tr>
    <tr>
      <td><a href="#">RNN Text Generator</a></td>
      <td>Training recurrent neural nets, specifically the <a href="https://arxiv.org/abs/1412.3555">Gated Recurrent Unit (GRU)</a> to predict the next token. For this project, the text corpus consists of Unicode characters, and character-level tokenization is used.</td>
    </tr>
    <tr>
      <td><a href="#">Style Transfer</a></td>
      <td>Implementation of style transfer as outlined by <a href="https://arxiv.org/abs/1508.06576">this paper</a>. The artistic style of a painting is transferred to a real-world photo using a pre-trained CNN.</td>
    </tr>
    <tr>
      <td><a href="#">Cancer Detection</a></td>
      <td>Using a convolutional U-net to mask areas of cellular images that are tumorous. The model is trained using a labeled cancer dataset.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/MLP-Backprop">MLP Backpropagation</a></td>
      <td>Ground-up implementation of the forward-propagation and backward-propagation algorithm for a simple feedforward multi-layer perceptron with two hidden layers and sigmoid activation.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/DecisionTree">Decision Tree</a></td>
      <td>Ground-up implementation of a decision tree model that uses the ID3 algorithm to calculate information gain to split at each stage.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/Clustering">Clustering</a></td>
      <td>Ground-up implementation of the K-Means algorithm and the Hierarchical Agglomerative Clustering algorithm.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/K-NearestNeighbors">K-Nearest Neighbors</a></td>
      <td>Ground-up implementation of the K-Nearest Neighbors algorithm.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/Perceptron">Perceptron</a></td>
      <td>Ground-up implementation of the perceptron model, which is the foundation for deep neural networks.</td>
    </tr>
  </tbody>
</table>

***

## Foundational Work

These repositories showcase much of the lab work I completed while learning to code in school. Some projects helped build a foundation in fundamental computer science concepts, such as data structures, while most others focused on applying programming to applied mathematics.

<table>
  <thead>
    <tr>
      <th width=275>Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/seon9cho/PhysicalModels">Physical Models</a></td>
      <td>Implementation of various physical models, including (but not limited to):
        <ul>
          <li>IVP</li>
          <li>Inverted Pendulum</li>
          <li>Diffusion model</li>
          <li>SIR model</li>
          <li>Finite Element</li>
          <li>Heat Flow</li>
          <li>Lorenz Equations</li>
          <li>Poisson Equations</li>
          <li>Wave Equations</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/MachineLearning">Machine Learning</a></td>
      <td>Implementation of various machine learning algorithms, including (but not limited to):
        <ul>
          <li>Reinforcement Learning</li>
          <li>Speech Recognition</li>
          <li>Markov Chains</li>
          <li>Nearest Neighbors</li>
          <li>K-Means</li>
          <li>Gibbs sampling and Linear Discriminant Analysis</li>
          <li>Principal Component Analysis</li>
          <li>PageRank Algorithm</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/SignalProcessing">Signal Processing</a></td>
      <td>Repo containing work related to signal processing, such as implementing Discrete Fourier Transform to convert signal data from time domain to frequency domain, and wavelets to process images. </td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/Optimization">Optimization</a></td>
      <td>Implementation of various optimization methods, such as:
        <ul>
          <li>Gaussian Quadratures</li>
          <li>Linear and Quadratic Linear Point method</li>
          <li>Gradient method</li>
          <li>Simplex algorithm</li>
          <li>Newton's method</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/NumericalMethods">Numerical Methods</a></td>
      <td>Implementation of various numerical methods, such as:
        <ul>
          <li>Iterative solvers</li>
          <li>Differentiation</li>
          <li>Integration</li>
          <li>Drazin Inverse</li>
          <li>Conditioning and stability of numerical methods</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/DataStructures">Data Structures</a></td>
      <td>Implementation of various data structures, such as:
        <ul>
          <li>Linked Lists</li>
          <li>Binary Search Tree</li>
          <li>AVL Tree</li>
          <li>Quicksort algorithm</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/DiscreteMath">Discrete Math</a></td>
      <td>Repo containing lab work done from class CS 236 - Discrete mathematics.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/DataScienceEssentials">Data Science Essentials</a></td>
      <td>Basic usage of Pandas framework, webscraping, and databases.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/LinearAlgebra">Linear Algebra</a></td>
      <td>Python implementation of basic linear algebra algorithms, such as:
        <ul>
          <li>Computing eigenvalues</li>
          <li>QR Decomposition</li>
          <li>Singular Value Decomposition</li>
          <li>Least squares</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/seon9cho/Tutorials">Tutorials</a></td>
      <td>Basic Python usage tutorial and its essential libraries, such as NumPy and Matplotlib.</td>
    </tr>
  </tbody>
</table>



***
