[DS-README.md](https://github.com/user-attachments/files/28098644/DS-README.md)
# Data Science Projects

A collection of machine learning and data science projects covering computer vision, time series forecasting, graph neural networks, OCR, and regression from scratch.

## Projects

| File | Topic | Approach / Tools |
|------|-------|------------------|
| `Car with SGD.py` | Predicting car fuel efficiency (km/l) from features like horsepower, weight, and cylinders | Linear regression trained from scratch with gradient descent (NumPy) |
| `FashionMnist.ipynb` | Image classification on the Fashion-MNIST dataset | Neural network in PyTorch |
| `G_Pachis_Sunspots_.ipynb` | Time series forecasting of sunspot activity | ARIMA, VAR, and LSTM/RNN models (statsmodels, TensorFlow/Keras) |
| `G_Pachis_PubMed(Graph_NN).ipynb` | Node classification on the PubMed citation graph | Graph Convolutional Network (PyTorch Geometric) |
| `Handwritten_names_Recognition_OCR_.ipynb` | Recognizing handwritten names from images | CNN + RNN with CTC loss (PyTorch) |

## Getting started

```bash
git clone https://github.com/GREG-PACHIS/Data-Science-projects.git
cd Data-Science-projects
```

The notebooks were written for **Google Colab** and run cleanly there. To run locally, install the dependencies for the project you want (e.g. `torch`, `torchvision`, `torch_geometric`, `tensorflow`, `statsmodels`, `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `opendatasets`) and open the notebook in Jupyter.

A few notebooks download their datasets from Kaggle via `opendatasets`, which will prompt for your Kaggle username and API key on first run. `Car with SGD.py` expects local `car_train.txt` / `car_test.txt` files — update the file paths near the top of the script before running.

## Author

Grigorios Pachis
