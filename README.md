# Middlesex College Machine Learning Club

This repository hosts notebooks, datasets, and supporting materials for the Middlesex College Machine Learning Club. Our goal is to help students build practical and mathematical understanding of machine learning through guided, hands-on study.

## Teaching philosophy

The club emphasizes a first-principles approach: we start from core mathematics and Python fundamentals, then build up to modern machine learning workflows and neural networks. The focus is understanding *why* methods work, not only how to run libraries.

## Preliminary semester curriculum

> This outline is preliminary and may be adjusted as the semester progresses.

| Meeting | Topic | Directory |
|---|---|---|
| 1 | Introduction, Linear Regression & Ordinary Least Squares | [meetings/01-linear-regression-ols](meetings/01-linear-regression-ols/) |
| 2 | Gradient Descent & Logistic Regression | [meetings/02-gradient-descent-logistic-regression](meetings/02-gradient-descent-logistic-regression/) |
| 3 | Classical Machine Learning | [meetings/03-classical-machine-learning](meetings/03-classical-machine-learning/) |
| 4 | Neural Networks & PyTorch | [meetings/04-neural-networks-pytorch](meetings/04-neural-networks-pytorch/) |
| 5 | Backpropagation From First Principles | [meetings/05-backpropagation](meetings/05-backpropagation/) |

## Running notebooks

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open a notebook from a meeting folder, for example:
   `meetings/01-linear-regression-ols/notebooks/`

## Python dependencies

This repository uses a minimal educational stack listed in `requirements.txt`:

- NumPy
- pandas
- Matplotlib
- Jupyter
- scikit-learn
- PyTorch

## Additional resources

Supplementary references and study guides are in [`resources/`](resources/):

- [mathematics.md](resources/mathematics.md)
- [python.md](resources/python.md)
- [machine-learning.md](resources/machine-learning.md)

## Contributing

Club members are welcome to contribute by adding notebooks, exercises, datasets, and clarifications.

1. Open an issue describing the proposed addition.
2. Keep notebook and dataset paths inside the relevant `meetings/<topic>/` folder.
3. Use clear file names and include short README updates when adding materials.

## Development status

Some notebooks, datasets, and exercises are still under development. Folder structure and README files are prepared so materials can be added progressively throughout the semester.
