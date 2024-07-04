# Leveraging Physics-Informed Neural Architectures as Solar Wind Forecasting Models

This repository consolidates the source code and experimental results for two distinct approaches developed as part of my master thesis, "Leveraging Physics-Informed Neural Architectures as Solar Wind Forecasting Models."

## PiNN Approach

### Overview

The PiNN (Physics-Informed Neural Networks) approach integrates physics-informed techniques with neural networks for efficient solar wind forecasting. It aims to improve prediction accuracy while reducing computational complexity compared to traditional methods.

### Structure

- **src/**: Contains the source code for implementing the PiNN approach.
- **results/**: Contains visualizations and summaries of experimental results obtained during the study.

### Data

The PiNN model utilizes data derived from magnetogram observations and solar wind parameters processed through the MULTI-VP model. Please note that due to data privacy and licensing constraints, the dataset used in the study is not publicly available in this repository. For access to the data or further inquiries, please contact the authors directly.

## PiNO Approach

### Overview

The PiNO (Physics-Informed Neural Operator) approach explores neural operators for solar wind forecasting, incorporating domain-specific knowledge to enhance prediction accuracy while maintaining computational efficiency.

### Structure

- **src/**: Contains the source code for implementing the PiNO approach.
- **results/**: Contains visualizations and summaries of experimental results obtained during the study.

### Data

Similar to the PiNN approach, the PiNO model utilizes data processed through the MULTI-VP model. The specific dataset details are subject to the same privacy and licensing restrictions mentioned earlier.

## Installation and Usage

### Cloning the Repository

To clone this repository and initialize submodules:

```
git clone --recursive [https://github.com/yourusername/master-thesis-solar-wind-forecasting.git](https://github.com/biromiro/pi-multivp)
cd pi-multivp
```

### Running Experiments

Each submodule (PiNN and PiNO) has its own set of instructions for setup and execution, detailed in their respective README files located in `src/`.

### Citation

If you use any part of this work in your research, please cite the corresponding master thesis:

```
@mastersthesis{costa2024pinnpinosolarwind,
  author       = {Nuno Costa},
  title        = {Leveraging Physics-Informed Neural Architectures as Solar Wind Forecasting Models},
  school       = {University of Porto},
  year         = {2024},
  address      = {Porto, Portugal},
  month        = {July},
}
```

### License

This project is licensed under the MIT License - see the LICENSE.md file for details.
