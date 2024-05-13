# MLflow Tutorial
## Setup

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/yehoon17/mlflow-tutorial.git .
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set environment variable
    - Create `.env` file
        ```
        MLFLOW_TRACKING_URI=file:///path/to/your/root/mlruns
        ```

        Example directory: `file:///C:/Users/.../mlflow-tutorial/mlruns`

## Run MLflow
```
mlflow ui
```

