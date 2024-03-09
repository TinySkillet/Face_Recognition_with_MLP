# Face Recognition with MLP

A face recognition machine learning model was developed using the scikit-learn library in Python. The hyperparameters were manually adjusted, foregoing the utilization of search algorithms such as GridSearch. I opted for this approach to evaluate the achievable accuracy without relying on automation.

## Installing Libraries

I utilized the Jupyter extension in VSCode instead of the Jupyter notebook itself. Ensure you set up a virtual environment before installing any libraries. You can use the `python-dotenv` library for this purpose. Install the library with pip from the terminal and execute:

```bash
python -m venv your_virtual_env_name
```

Afterwards, activate the virtual environment. On Windows, execute:

```bash
your_virtual_env_name\Scripts\activate
```

On Linux and Mac, use:

```bash
source your_virtual_env_name/bin/activate
```

Switch to the interpreter in your virtual environment folder and, in the project terminal, run:

```bash
pip install -r requirements.txt
```

This will download and install all the necessary libraries. If you are using the Jupyter notebook, you can install them manually.

Ensure to replace "your_virtual_env_name" with the actual name you choose for your virtual environment.
