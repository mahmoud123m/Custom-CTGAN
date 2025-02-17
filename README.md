# CTGAN: Conditional Tabular GAN for Synthetic Data Generation

## Overview
This project implements a **custom Conditional Tabular GAN (CTGAN)** using **Keras and TensorFlow** to generate synthetic tabular data. The goal is to explore how GANs can be used to balance imbalanced datasets as an alternative to traditional oversampling methods like SMOTE.

## Features
- **Custom-built CTGAN**: Implemented using TensorFlow and Keras (not an off-the-shelf package).
- **Synthetic Data Generation**: Generates tabular data that resembles real-world distributions.
- **Handling Imbalanced Data**: Can be used to create synthetic samples for minority classes.
- **Feature Conditioning**: Incorporates categorical variables into the GAN training process.

## Installation
Ensure you have the required dependencies installed:

```bash
pip install pandas numpy tensorflow keras matplotlib scikit-learn tqdm seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CTGAN.git
   cd CTGAN
   ```

2. Run the Jupyter Notebook:
   - Open `CTGAN.ipynb` in Jupyter Notebook or Google Colab.
   - Follow the steps to preprocess the data, train the GAN, and generate synthetic data.

## Expected Output
- A synthetic dataset with similar statistical properties to the original dataset.
- Improved class balance in imbalanced datasets.
- Visualizations comparing real and synthetic distributions.

## Notes
- This project does **not** use an existing `ctgan` package. Instead, it is a **custom-built GAN model** implemented from scratch.
- The model is still experimental and may require tuning for different datasets.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the model.

## License
This project is licensed under the MIT License.


