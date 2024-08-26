
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>
  <h1>Cryptocurrency Prediction with GRU Neural Network (v3.0)</h1>

  <h2>Project Overview</h2>
  <p>
    This project demonstrates a cryptocurrency prediction model using a GRU (Gated Recurrent Unit) neural network. It builds upon previous versions that utilized LSTM and RNN architectures. The model is designed to predict future cryptocurrency prices, specifically Bitcoin (BTC), with high accuracy.
  </p>

  <h2>Key Features</h2>
  <ul>
    <li><strong>GRU Neural Network:</strong> Employs a GRU architecture, known for its efficiency and performance in sequential data like cryptocurrency prices.</li>
    <li><strong>Custom Algorithms:</strong> The project incorporates custom algorithms for GRU implementation and neural network visualization.</li>
    <li><strong>High Accuracy:</strong> Achieved a remarkable 99.54% accuracy in a March 27 BTC forecast (**Disclaimer: Past performance is not indicative of future results**).</li>
    <li><strong>Open-Source:</strong> The project is available as open-source for community contributions and experimentation.</li>
  </ul>

  <h2>Project Structure</h2>
  <pre>
project_folder/
├── data/
│   └── bitcoin_data.csv
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── neural_network_visualization.py
│   └── predictions.py
├── README.md
├── requirements.txt
  </pre>

  <h2>Dependencies</h2>
  <p>
    To run this project, you'll need the following Python libraries installed:
  </p>
  <ul>
    <li>TensorFlow: For building and training the neural network.</li>
    <li>Keras: A high-level API for TensorFlow, simplifying model creation.</li>
    <li>NumPy: For numerical operations.</li>
    <li>PyDot: For visualizing the neural network structure.</li>
    <li>Matplotlib: For plotting and visualization.</li>
    <li>Scikit-learn (SKLEARN): For data preprocessing and evaluation.</li>
  </ul>
  <p>
    You can install these dependencies using pip:
  </p>
  <pre>
  pip install tensorflow keras numpy pydot matplotlib scikit-learn
  </pre>

  <h2>Usage</h2>
  <p>
    Follow these steps to use the project:
  </p>
  <ol>
    <li><strong>Prepare Data:</strong> Place your Bitcoin historical data in the `data/bitcoin_data.csv` file with appropriate columns (e.g., date, open, high, low, close, volume).</li>
    <li><strong>Run Data Preprocessing:</strong> Execute the `data_preprocessing.py` script to preprocess the data (normalization, feature engineering).</li>
    <li><strong>Train the Model:</strong> Run the `model_training.py` script to train the GRU model on the preprocessed data.</li>
    <li><strong>Make Predictions:</strong> Use the `predictions.py` script to generate predictions for future Bitcoin prices.</li>
    <li><strong>Visualize the Model:</strong> The `neural_network_visualization.py` script will automatically visualize the trained GRU neural network.</li>
  </ol>

</body>
</html>
