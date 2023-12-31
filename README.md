# Moffat-Bay CSD 460 Capstone

## Setup and Run

1. **Configuration**: Before you start, make sure to update the `CHANGE_ME.env` file with your database username and password. Once updated, rename the file to `.env`.

2. **Installation**: To run the project, follow these steps:

   a. Install the required packages:
      ```
      pip install -r requirement.txt
      ```

   b. Initialize the Database: Run the following command to set up the database and tables:
      ```
      python run.py --init
      ```

3. **Running the Project**: After completing the steps above, you can now run the Flask application locally:
   a. To run the project without debug mode:
      ```
      python run.py
      ```
   b. To run the project with debug mode turned on, and the toolbar activated:
      ```
      python run.py --debug
      ```
