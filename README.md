<h1>Face Mask Detection using CNN</h1>

<h2>📌 Objective</h2>
<p>To develop a Convolutional Neural Network (CNN) model that accurately detects whether a person is wearing a face mask or not from an image.</p>

<hr>

<h2>🛑 Problem Statement</h2>
<p>In the context of public health and safety, especially during pandemics, automated face mask detection can assist in enforcing mask-wearing protocols. This project aims to classify facial images into two categories: <strong>With Mask</strong> and <strong>Without Mask</strong>.</p>

<hr>

<h2>📊 Dataset</h2>
<ul>
  <li><b>Source:</b> Public dataset from Kaggle or open-source repositories</li>
  <li><b>Classes:</b> Mask, No Mask</li>
  <li><b>Images:</b> Thousands of labeled facial images across both categories</li>
</ul>

<hr>

<h2>⚙️ Methodology</h2>

<h3>1. Data Preprocessing</h3>
<ul>
  <li>Image resizing and normalization</li>
  <li>Label encoding</li>
</ul>

<h3>2. Model Architecture</h3>
<ul>
  <li>Convolutional layers for feature extraction</li>
  <li>MaxPooling layers for downsampling</li>
  <li>Dense layers for classification</li>
  <li>Activation: ReLU, Sigmoid</li>
</ul>

<h3>3. Training</h3>
<ul>
  <li>Loss Function: Sparse Categorical Crossentropy</li>
  <li>Optimizer: Adam</li>
  <li>Metrics: Accuracy</li>
</ul>

<h3>4. Evaluation</h3>
<ul>
  <li>Test accuracy: 93%</li>
  <li>Confusion matrix, classification report, and sample predictions</li>
</ul>

<hr>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>TensorFlow / Keras</li>
  <li>OpenCV</li>
  <li>Matplotlib, NumPy</li>
</ul>

<hr>

<h2>✅ Results</h2>
<ul>
  <li>High-accuracy classification between masked and unmasked faces</li>
  <li>Supports real-time detection through webcam integration (optional)</li>
</ul>

<hr>

<h2>📝 Conclusion</h2>
<p>This project demonstrates the effectiveness of CNNs in face mask detection and can be extended into real-time surveillance or integrated into safety systems.</p>

<hr>

<h2>🔮 Future Enhancements</h2>
<ul>
  <li>Deploy as a web/mobile application</li>
  <li>Real-time detection using webcam or CCTV feeds</li>
  <li>Expand dataset with diverse demographics and environments</li>
</ul>
