<h1>
  <span class="headline">Python Fundamentals Review Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

Before starting the lab, make sure your environment is set up correctly:

1. **Create a GitHub Repository and Clone It:**

   - Go to [GitHub](https://github.com/) and log in to your account.
   - Click on the **`+`** icon in the upper right corner and select **`New repository`**.
   - Name your repository appropriately, such as `python-fundamentals-review`.
   - Do not initialize the repository with a `README` or `.gitignore`—you can add these later.
   - Once the repository is created, copy the URL provided.
   - In your terminal, navigate to the directory where you want to store the repository (ex: `~/code/ga/labs/`).
   - Clone the repository to your local machine:
     ```bash
     git clone <your-repo-url>
     ```
   - Navigate into the cloned repository:
     ```bash
     cd python-fundamentals-review
     ```

2. **Create a New Jupyter Notebook in the Repository:**

   - Open **Visual Studio Code**.
   - Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (Windows/Linux) or <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (macOS) to open the Command Palette.
   - Type `Jupyter: Create New Blank Notebook` and select it.
   - Save the notebook in the cloned repository directory with an appropriate name, such as `python_fundamentals_review.ipynb`.

3. **Start Your Virtual Environment:**

   - In your terminal, activate your `ga-env` environment by running the following command:
     ```bash
     conda activate ga-env
     ```
   - Ensure that `(ga-env)` appears at the beginning of your terminal prompt, indicating that the environment is active.

4. **Remember to Save and Push Your Work:**

   - Regularly save your work in the Jupyter Notebook.
   - When you're ready to push your changes to GitHub:
     ```bash
     git add .
     git commit -m "Work in progress"
     git push origin main
     ```
   - Share the link to your GitHub repository with your instructor for review.

You're now ready to start the lab. Make sure your notebook is open, your environment is active, and your GitHub repository is set up before proceeding with the exercises.
