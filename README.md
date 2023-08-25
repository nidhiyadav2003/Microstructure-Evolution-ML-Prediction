## Description

This repository presents an innovative approach for accelerated prediction of microstructure evolution through a machine-learned surrogate model. The technique used is convolutional long short-term memory (ConvLSTM) to accurately forecast microstructural changes without sacrificing resolution. The model can predict future frames based on prior ones by training on phase-field-generated microstructures across various compositions, offering a rapid alternative to time-consuming simulations.

## Repository Contents

- `code/`: Contains Python scripts for implementing the ConvLSTM model and the microstructure dataset.
- `examples/`: Includes example microstructure evolution images and their predictions using the trained model.
- `results/`: Stores the outcomes of the prediction model, including comparison images and accuracy metrics.
- `README.md`: The document you are currently reading, providing an overview of the technique, repository structure, and usage instructions.

## Getting Started

1. Clone the repository to your local machine.
2. Navigate to the `code/` directory and run the provided Python scripts sequentially.
3. Follow the script instructions to load the dataset, train the ConvLSTM model, and make predictions.

## Dependencies

- Python 
- Tensorflow 
- Numpy 
- Matplotlib 

## Usage

1. Prepare your phase-field-generated microstructure dataset in the required format.
2. Follow the steps in the provided Python scripts to preprocess the data and train the ConvLSTM model.
3. Execute the scripts to generate predictions for future microstructure frames based on prior frames.

## Contributing

Contributions are welcome! Please create a pull request or submit issues for improvements, bug fixes, or additional features.

## Contributors

- [NIDHI](https://github.com/nidhiyadav2003)
  
## License

---

