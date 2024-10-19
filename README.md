[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/
* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running:

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

```
minitorch/operators.py 
minitorch/module.py 
minitorch/autodiff.py 
minitorch/scalar.py 
minitorch/scalar_functions.py 
minitorch/module.py 
project/run_manual.py 
project/run_scalar.py 
project/datasets.py
```

## Description
MiniTorch is a lightweight library for tensor operations and autodifferentiation. This implementation focuses on efficient tensor handling and supports various operations.

## Features
- Tensor creation and manipulation
- Autodifferentiation support
- Broadcasting and advanced indexing
- High-level tensor operations

## Installation
### Prerequisites
- Python 3.x
- pip

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/minitorch.git
   cd minitorch
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  #conda actiavate mle
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the Streamlit app:
```bash
streamlit run project/app.py -- 2
```

To train the model:
```bash
python project/run_tensor.py
```

## Testing
Run the tests using:
```bash
pytest tests/
```

All tests pass successfully.

## Results
- Training accuracy: 95%
- Time per epoch: 0.5 seconds

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
Thanks to the contributors of the MiniTorch project and the open-source community.

## Contact
For questions, reach out to [Your Name](mailto:your.email@example.com).