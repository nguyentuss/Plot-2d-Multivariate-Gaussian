---
title: Multivariate Gaussian Visualization
---

This project provides an interactive visualization of a 2D Multivariate
Gaussian distribution using Python, Matplotlib, and `ipywidgets`. You
can adjust the mean, covariance, and correlation parameters using slider
bars in both 2D contour and 3D surface plots.

# Features

-   **Interactive 2D Contour Plot:** Adjust the mean, standard
    deviations, and correlation with sliders.

-   **Interactive 3D Surface Plot:** Visualize the 2D Gaussian
    distribution as a 3D surface.

-   **Works in Jupyter Notebook, JupyterLab, and VS Code Interactive
    Window.**

# Prerequisites

-   Python 3.7 or later

# Installation

## Using Conda

1.  **Create and Activate a Conda Environment:**

        conda create -n gauss_env python=3.9
        conda activate gauss_env

2.  **Install Required Packages:**

        conda install -c conda-forge notebook jupyterlab ipywidgets matplotlib numpy

3.  **Enable the ipywidgets Extension:**

    -   For JupyterLab (v3 or later), ipywidgets should work out of the
        box.

    -   For older versions of JupyterLab, run:

            jupyter labextension install @jupyter-widgets/jupyterlab-manager

    -   For classic Jupyter Notebook:

            jupyter nbextension enable --py --sys-prefix widgetsnbextension

## Using pip

1.  **Create and Activate a Virtual Environment (Optional but
    Recommended):**

        python -m venv venv
        source venv/bin/activate  # On Windows: venv\Scripts\activate

2.  **Install Required Packages:**

        pip install notebook jupyterlab ipywidgets matplotlib numpy

3.  **Enable the ipywidgets Extension:**

    -   For Jupyter Notebook:

            jupyter nbextension enable --py --sys-prefix widgetsnbextension

    -   For older versions of JupyterLab:

            jupyter labextension install @jupyter-widgets/jupyterlab-manager

# Running the Project

## In JupyterLab or Jupyter Notebook

1.  **Launch your environment:**

        jupyter lab  # or
        jupyter notebook

2.  **Open the provided notebook file** (or create a new one) and copy
    the interactive code into a cell.

3.  **Run the cell** to see the interactive slider bars and the
    visualization.

## In VS Code

1.  **Install the Jupyter Extension for VS Code:**

    -   Open VS Code and install the official [Jupyter
        extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter).

2.  **Open a Notebook or Python Interactive Window:**

    -   Create a new `.ipynb` notebook, or add a code cell in a Python
        file (using `# %%` to create a cell).

3.  **Ensure the Correct Python Environment is Selected:**

    -   Make sure the environment you configured (conda or virtual
        environment) is selected in VS Code.

4.  **Run the Code Cell:**

    -   Execute the cell to see the interactive widgets and
        visualization.

# Troubleshooting

-   **Interactive Widgets Not Showing:**

    -   Ensure `ipywidgets` and the corresponding Jupyter extensions are
        installed.

    -   Confirm you are running the code in an interactive environment
        (Jupyter Notebook, JupyterLab, or VS Code Interactive Window).

    -   Restart your environment if changes do not appear.

-   **Extension Issues in JupyterLab:**

    -   For JupyterLab v2, you may need to run the labextension install
        command.

    -   For JupyterLab v3 and later, ipywidgets are enabled by default.

# License

This project is open source and available under the [MIT
License](LICENSE).

# Acknowledgments

-   [ipywidgets Documentation](https://ipywidgets.readthedocs.io/)

-   [JupyterLab Documentation](https://jupyterlab.readthedocs.io/)

-   [Matplotlib Documentation](https://matplotlib.org/)
