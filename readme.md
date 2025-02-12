# Basic Calculator

## Setup Instructions

1. **Clone the Repository:**  
   ```sh
   git clone git@github.com:kovinaveenkumar/calculator-homework3.git
   ```
2. **Navigate to the Project Directory:**  
   ```sh
   cd homework3
   ```
3. **Create a Python Virtual Environment:**  
   ```sh
   python -m venv venv
   ```
4. **Activate the Virtual Environment:**  
     ```sh
     source venv/bin/activate
     ```
5. **Install Dependencies:**  
   ```sh
   pip install -r requirements.txt
   ```
6. **Open the Code in VS Code:**  
   ```sh
   code .
   ```
7. **Run the Calculator Program:**  
   ```sh
   python calculator/calculator.py
   ```
8. **Available Operations:**  
   - Add
   - Subtract
   - Multiply
   - Divide
   - Check Calculation History
   - Check Last Calculation
   - Clear History
   - Use Last Result in a New Calculation
   - Exit

## Running Tests

9. **Run Unit Tests:**  
   ```sh
   pytest tests/test_calculator.py
   ```
10. **Run Detailed Test Output:**  
    ```sh
    pytest -v
    ```
11. **Check Test Coverage:**  
    ```sh
    pytest --cov
    ```
