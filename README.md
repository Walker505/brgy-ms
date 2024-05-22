# Barangay Management System
This repo will contain the source code for the Barangay management system Django App

### Instructions to contribute to the codebase

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Walker505/brgy-ms.git
    cd brgy-ms
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # For MacOS/Unix
    
    # On Windows use:
    .venv\Scripts\Activate.ps1
    ```

3. **Install Dependencies**:
    ```bash
    cd brgy_ms
    pip install -r requirements.txt
    ```

4. **Make Your Changes**:
    - Start Django Server 
    ```bash
    python manage.py runserver
    ```

5. **Update Static Files**:
    ```bash
    # Close the terminal used to run the server
    python manage.py collectstatic
    ```

5. **Update `requirements.txt`** (if you add new dependencies):
    ```bash
    pip freeze > requirements.txt
    ```

6. **Commit and Push Your Changes**:
    ```bash
    git add .
    git commit -m "Your detailed commit message"
    git push <your_branch>
    ```

7. **Create a Pull Request**:
    - Go to the repository on GitHub.
    - Create a new Pull Request from your branch to the main branch.
    - Provide a detailed description of the changes you made.

9. **Code Review**:
    - Respond to any feedback or requested changes from the code reviewers promptly.

10. **Merge the Pull Request**:
    - Once approved, merge the pull request as per the project's guidelines.
