# ENGG 6600 Cyber Security for Engineers

Welcome to the GitHub repository for the two-day introductory workshop on 'ENGG 6600 Cyber Security for Engineers.' This repository serves as a supplementary resource for beginners to get acquainted with Jupyter Notebooks and explore AI sample models, offering an accessible entry point into the world of machine learning.
## Table of Contents

1. [Repository Structure](#repository-structure)
2. [Getting Started](#getting-started)
3. [Contributing](#contributing)

## Repository Structure

The repository is organized into folders and files as follows:

- `notebooks/`: This folder contains Jupyter Notebook files (.ipynb) for various tutorials and sample models.
- `tutorials/`: This folder holds Markdown files for tutorials. The tutorials are numbered for easy navigation (e.g., `00-Installing-Conda.md`, `01-Introduction-to-Jupyter-Notebooks.md`, etc.).

## Getting Started

### Prerequisites

Before you begin, make sure you have installed:

- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Anaconda](https://www.anaconda.com/products/distribution#download-section), [Conda](https://conda.io/projects/conda/en/latest/user-guide/getting-started.html) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html). (Search the differences and choose one)

### Steps

1. **Clone the Repository**: Clone this repository to your local machine.

    ```bash
    git clone https://github.com/threemmm/ENGG-6600-Cyber-Security-for-Engineers.git
    ```

2. **Navigate to the Repository**: Use the terminal to navigate to the directory where you cloned the repository.

    ```bash
    cd ENGG-6600-Cyber-Security-for-Engineers
    ```

3. **Understanding Environments**: In the context of Python programming and data science, an "environment" refers to a named, isolated, working copy of Python that maintains its own files, directories, and paths. This allows you to work with specific versions of libraries and Python itself, without interfering with other projects.

    - **Create a New Environment**: Create a new Conda environment and name it (replace `your_env_name` with the name you want).

        ```bash
        conda create --name your_env_name python=3.8
        ```

    - **Viewing Conda Environments**: To view the list of environments, run:

        ```bash
        conda env list
        ```

    - **Activate the Environment**: To activate the newly created environment, run:

        ```bash
        conda activate your_env_name
        ```

    - **Accessing Environment in Jupyter**: If you want to use this environment in Jupyter Notebook, you can install the `ipykernel` package and create a new kernel based on this environment.

        ```bash
        conda install -n your_env_name ipykernel
        python -m ipykernel install --user --name your_env_name --display-name "Python (your_env_name)"
        ```
      - The command `python -m ipykernel install --user --name your_env_name --display-name "Python (your_env_name)"` is used to install a Jupyter kernel associated with a specific Conda environment. Here's an academic explanation of each part of the command:

      - `python`: This part of the command invokes the Python interpreter.

      - `-m ipykernel install`: This part of the command uses the `ipykernel` module to install a new Jupyter kernel.

      - `--user`: This flag specifies that the kernel should be installed for the current user only. It places the kernel in the user's Jupyter directory, making it available for personal use.

      - `--name your_env_name`: This flag specifies the name of the Conda environment for which you want to create the Jupyter kernel. Replace `your_env_name` with the actual name of the Conda environment you want to use with Jupyter.

      - `--display-name "Python (your_env_name)"`: This flag sets the display name for the Jupyter kernel. It's the name that will appear in the Jupyter Notebook interface when you choose a kernel for your notebook. The display name is typically set to "Python (your_env_name)" to indicate that this kernel is associated with the specified Conda environment.


4. **Launch Jupyter Notebook**: To start Jupyter Notebook, run:

    ```bash
    jupyter notebook
    ```

    This will open Jupyter Notebook in your web browser. Navigate to the `notebooks/` folder to access the notebook files.







## Contributing

We welcome contributions to improve the repository. Feel free to:

- Report issues
- Open pull requests
- Suggest new features or tutorials

To contribute, please fork the repository and create a pull request with your changes.
For accepted pull request contributions, a small bonus may be awarded as a token of appreciation

---

Thank you. Happy Learning!
