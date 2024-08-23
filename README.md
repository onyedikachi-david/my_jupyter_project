# Jupyter Notebook Data Science Project

This project sets up a Jupyter Notebook environment for data science work, utilizing Docker for easy setup and reproducibility.

## Project Structure

- `notebooks/`: Contains Jupyter notebooks
  - `first_notebook.ipynb`: An example notebook demonstrating basic Python, matplotlib, and numpy usage
- `requirements.txt`: Lists Python package dependencies
- `.devcontainer/`: Contains configuration for Visual Studio Code's Remote - Containers feature
  - `devcontainer.json`: Specifies the development container configuration

## Getting Started

### Prerequisites

- Docker
- Visual Studio Code (recommended)
- Visual Studio Code Remote - Containers extension (recommended)

### Setup

1. Clone this repository
2. Open the project folder in Visual Studio Code
3. When prompted, click "Reopen in Container" to build and start the development container
4. Once the container is built, you can access Jupyter Notebook at `http://localhost:8888`

## Example Notebook

The `first_notebook.ipynb` demonstrates:

1. Basic Python printing and arithmetic
2. Importing libraries (matplotlib and numpy)
3. Creating a simple sine wave plot

## Dependencies

This project uses the following main Python packages:

- numpy (1.21.0)
- matplotlib (3.4.2)
- pandas (1.3.0)
- scikit-learn (0.24.2)

For a complete list, see `requirements.txt`.

## Development Container

This project uses a development container based on the `jupyter/datascience-notebook` image. It includes:

- Jupyter Notebook
- Python 3
- Common data science libraries

The container is configured to:

- Forward port 8888 for Jupyter Notebook access
- Install dependencies from `requirements.txt`
- Set up Python and Jupyter extensions in VS Code

## Contributing

Feel free to fork this repository and submit pull requests for any improvements or additional examples.
