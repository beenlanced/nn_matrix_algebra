# Understanding Neural Network Matrix Algebra and Notation - (note Repo is in Progress)

<p>
  <img alt="Neural Network Matrix Algebra" src="imgs/lstm_intro.png"/>
</p>

[img source]()

## Project Description

This project was constructed as a "Learning Tuesday" learning module for fellow data science engineers and artificial intelligence (AI) ethusiasts. It's goal is to explain some of the types of matrix algebra encountered in Neural Networks (NN) and especially to explain the terminology found when reading NN documentation, Python code, or deep learning/AI research papers.

### What this Project Does Specifically (i.e., the Problem)

In this repo, you will find several Python code Jupyter notebooks that will show examples of typical NN matrix equations and how you might find the equations expressed in formulas and actual Python code.

The general idea is to help explain how the compact equation you might read in a paper are translated into actual mathematics and implemented in code form.

Fun, right!

### My Solution

The Jupyter notebooks,

- Notebook x - TBD

---

## Objective

The project contains the key elements:

- `Deep Learning` for neural networks building,
- `Git` (version control),
- `Jupyter` python coded notebooks,
- `Matrix Alegbra` performing operations on vectors, matrices, and tensors,
- `Python` the standard modules,
- `PyTorch` Machine Learning framework to train our deep neural network,
- `Neural Network (RNN)` feedback loop neural networks to process sequential data,
- `Tensors` mathematical objects that generalize scalars, vectors, and matrices into higher dimensions. A multi-dimensional array of numbers,
- `uv` package management including use of `ruff` for linting and formatting

---

## Tech Stack

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## Getting Started

Here are some instructions to help you set up this project locally.

---

## Prerequisites

- Knowledge of Python
- Knowledge of Neural Networks (though most of the emphasis here is on the matrices and vectors mathematic operations to be reviewed)

## Installation Steps

The Python version used for this project is `Python 3.12` to be compatible with `PyTorch`.

Follow the requirements for [Using uv with PyTorch](https://docs.astral.sh/uv/guides/integration/pytorch/)

- Make sure to use python versions `Python 3.12`
- pip version 19.0 or higher for Linux (requires manylinux2014 support) and Windows. pip version 20.3 or higher for macOS.
- Windows Native Requires Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017 and 2019

### Clone the Repo

1. Clone the repo (or download it as a zip file):

   ```bash
   git clone https://github.com/beenlanced/ltsm_project_pytorch.git
   ```

2. Create a virtual environment named `.venv` using `uv` Python version 3.12:

   ```bash
   uv venv --python=3.12
   ```

3. Activate the virtual environment: `.venv`

   On macOS and Linux:

   ```bash
   source .venv/bin/activate #mac
   ```

   On Windows:

   ```bash
    # In cmd.exe
    venv\Scripts\activate.bat
   ```

4. Install packages using `pyproject.toml` or (see special notes section)

   ```bash
   uv pip install -r pyproject.toml
   ```

### Install the Jupyter Notebook(s)

1. **Run the Project**

   - Run the Jupyter Notebook(s) in the Jupyter UI or in VS Code.

---

### Final Words

Thanks for visiting.

Give the project a star (⭐) if you liked it or if it was helpful to you!

You've `beenlanced`! 😉

---

## Acknowledgements

I would like to extend my gratitude to all the individuals and organizations who helped in the development and success of this project. Your support, whether through contributions, inspiration, or encouragement, have been invaluable. Thank you.

Specifically, I would like to acknowledge:

- [Joshua Starmer - StatQuest](https://www.youtube.com/watch?v=ZTt9gsGcdDo&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=27). This project was inspired by his "Essential matrix alegebra for Neural Networks, Clearly explained!!!" video. Thanks!

- (https://github.com/greyhatguy007/Mathematics-for-Machine-Learning-and-Data-Science-Specialization-Coursera/blob/main/C1/w1/lab/C1_W1_Lab_1_introduction_to_numpy_arrays.ipynb)

- https://www.youtube.com/watch?v=per7w0-RAys

- https://github.com/ArenaHernandez?tab=repositories

- [Hema Kalyan Murapaka](https://www.linkedin.com/in/hemakalyan) and [Benito Martin](https://martindatasol.com/blog) for sharing their README.md templates upon which I have derived my README.md.

- The folks at Astral for their UV [documentation](https://docs.astral.sh/uv/)

---

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details
