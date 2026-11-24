# keras

Keras / TensorFlow learning exercises implemented as Jupyter notebooks.
Each exercise builds on the previous one, progressing from environment setup
to building and training a neural network.

## Exercises

| Exercise | Notebook | Description |
|----------|----------|-------------|
| ex00 | [Notebook_ex00.ipynb](ex00/Notebook_ex00.ipynb) | Environment check: print versions of Python, NumPy, Keras, Jupyter, pandas |
| ex01 | [Notebook_ex01.ipynb](ex01/Notebook_ex01.ipynb) | Create a `Sequential` model |
| ex02 | [Notebook_ex02.ipynb](ex02/Notebook_ex02.ipynb) | Configure `Dense` layers (input, hidden, output) and inspect their configs |
| ex03 | [Notebook_ex03.ipynb](ex03/Notebook_ex03.ipynb) | Build a multi-layer `Sequential` model and print its summary |
| ex04 | [Notebook_ex04.ipynb](ex04/Notebook_ex04.ipynb) | Train a binary classifier on the breast cancer dataset; compare unscaled vs scaled data |

## Requirements

- Python 3
- See [ex00/requirements.txt](ex00/requirements.txt) for Python dependencies:
  - pandas
  - numpy
  - keras
  - jupyter
  - scikit-learn (used in ex04)

Install dependencies:

```bash
pip install -r ex00/requirements.txt
```

## Usage

Launch Jupyter and open a notebook:

```bash
jupyter notebook ex00/Notebook_ex00.ipynb
```