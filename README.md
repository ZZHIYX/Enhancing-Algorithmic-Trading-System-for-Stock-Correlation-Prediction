# Setup

* Note: Recommend in Windows OS. Packages Not Found error may ocurr in other OS, in which case you could manually install missing packages. 

- 1. install miniconda
- 2. create an new environment inside conda based on the given environment file ***environment.yml***
    ```sh
    conda env create -f environment.yml
    ```
- 3. go inside the environment
    ```sh
    conda activate aps1052
    ```

# Run

- 1. Train the model, by running ***train.ipynb***
- 2. Run baseline model, by running ***baseline.ipynb***
- 3. Use the trained model to see its performance in different strategies, by running ***ARIMA+LSTM.ipynb***. This step will use baseline model output for comparison purpose.
