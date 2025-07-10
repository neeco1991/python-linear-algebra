# Python Linear Algebra

This repository tries to replicate the core concepts expressed in [3Blue1Brown's Essence of linear algebra playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) with Python, showcasing the power of Numpy.

## Getting Started

This project uses `uv` for dependency management and environment setup.

### Prerequisites

Make sure you have `uv` installed. If not, you can install it by following the instructions on the [uv documentation](https://docs.astral.sh/uv/).

### Environment Setup

After cloning the repository, set up your development environment:

**Install dependencies and create virtual environment:**

```bash
uv sync
```

This command reads `pyproject.toml` and `uv.lock` to create a virtual environment (`.venv`) and install all the required packages (e.g., `numpy`). It will also ensure the correct Python version (as specified in `.python-version`) is used.

### Running the Project

To activate the virtual environment and run Python scripts or Jupyter notebooks:

1.  **Activate the virtual environment:**

    ```bash
    source .venv/bin/activate
    ```

2.  **Run Jupyter Notebooks:**

    launch Jupyter Lab:

    ```bash
    jupyter lab
    ```

    You can then open `01_vectors.ipynb` in your browser.
