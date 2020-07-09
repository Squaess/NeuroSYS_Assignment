# NeuroSYS assignment

## Repository structure:
```
.
├── README.md           # description
├── assignment.ipynb    # problem solution
├── requirements.txt    # contains packages needed to install
└── result.png          # final plot
```

If you want to run [assignment.ipynb](./assignment.ipynb) file, you'll need:
1. Database file: `database_1.db`, located in the same directory as `assignment.ipynb` file.
2. Python virtual environment with needed packages installed. They are listed in `requirements.txt` file.

To create virtual environment using pip:
* Windows: 
   ```
    python -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt
    ```
* Linux and OSX:
   ```
    python -m venv venv
    venv/bin/activate
    pip install -r requirements.txt
    ```

## The final plot from the assignment.

![smiley_plot](result.png)
