# pillrec

## Overview
Pillrec is a recommendation system designed to suggest similar medicines based on their compositions. It leverages natural language processing techniques to analyze the compositions of medicines and recommend alternatives that have similar properties. This can be particularly useful for pharmacists, healthcare providers, and patients looking for equivalent medications.

## Features
- **Medicine Similarity**: Recommends similar medicines based on their compositions.
- **Price and Manufacturer Information**: Provides details about the price and manufacturer of the recommended medicines.
- **Efficient Search**: Uses advanced techniques like TF-IDF vectorization and dimensionality reduction for efficient similarity search.
- **Handles Missing Data**: Robust handling of missing data in medicine compositions.

## Installation
To install the necessary dependencies, run:
```bash
pip install -r requirements.txt
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)
- [faiss](https://github.com/facebookresearch/faiss)
- [tqdm](https://tqdm.github.io/) 