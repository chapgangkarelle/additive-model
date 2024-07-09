

## Introduction

This project is designed to perform data preparation and analysis for sales data, specifically focusing on sales of swimwear. It includes functionalities to preprocess the data, split it into training and testing sets, and visualize sales trends over time.

## Installation

To get started with this project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
```

## Usage

To use this project, follow the steps below:

1. Prepare your dataset in CSV format, ensuring it has the required columns (`Years` and `Sales`).
2. Place the dataset in the project directory and update the `csv_path` variable in `main.py` with the correct file name.
3. Run the `main.py` script to preprocess the data and perform the analysis.

```bash
python main.py
```

### Example

Here's an example of how to run the project:

```python
from data_preparation import DataPreparation
from additif import Additif

csv_path = "vente_maillots_de_bain.csv"
data_preparation_object = DataPreparation(csv_path)
additif_object = Additif(data_preparation_object)

# Uncomment the following line to display the sales trend graph
# data_preparation_object.show_graph()
```

## Files

- `data_preparation.py`: Contains the `DataPreparation` class which handles data loading, preprocessing, and splitting.
- `main.py`: Main script to run the data preparation and additional processing.
- `additif.py`: (Assumed to exist) Contains the `Additif` class for additional data manipulation or analysis.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to reach out to chapgangkarelle24@gmail.com

