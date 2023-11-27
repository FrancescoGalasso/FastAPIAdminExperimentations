### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your_username/FastAPIAdminExperimentations.git
    cd FastAPIAdminExperimentations/starlette-admin
    ```

2. **Set up a virtual environment**:
    ```bash
    virtualenv -p /usr/bin/python3 venv
    ```

3. **Activate the virtual environment**:

   - For MacOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### Run

1. **Start the application with the command**:
    ```bash
    uvicorn main:app --reload
    ```

2. **Open admin dashboard**:
    ```bash
    http://localhost:8000/admin
    ```
