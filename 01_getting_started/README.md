# Getting Started

## Software installation and account set up

Before you get started in the course, you will need to install some software and set up/login a couple of accounts. Below are step-by-step instructions for each program and license. These instructions are tailored to students at the University of Alabama, but should be adaptable for students at other universities.

### GitHub and GitHub Copilot 

GitHub is a platform for version control and collaboration. It is where you will find many of the course materials. GitHub provides free access to it's AI tools for educational users (shout out to GitHub!). You will need to sign up for a GitHub account and apply for educational access. **Please note** that this process can take a few days, so it is best to start this as soon as possible!

1. To get set up on GitHub, start by going here: <a href="https://github.com/education/students" target="_blank">GitHub Education</a>. Then select **Join GitHub education** and then **create an account**.
2. Enter your **crimson.ua.edu email** and select a password and username.
3. Complete human verification (if necessary) and input the verification code from your email.
4. Login to your newly created account:
   1. Under **billing and licensing** select **payment information**. Or go to [billing information](https://github.com/settings/billing/payment_information). Ensure your name is listed exactly as it is on your university records.
   2. Enter billing information consistent with your university records (you do not need to enter any payment information). 
   3. Under **password and authentication** enable two-factor authentication. Or go to [password and authentication](https://github.com/settings/security). You will need to use an authenticator app on your phone or SMS messaging.
5. Under **billing and licensing** select **education benefits**. Or go to [education benefits](https://github.com/settings/education/benefits). Then start an application. Ensure "student" is selected as well as “University of Alabama – Tuscaloosa” at the bottom of the page and click continue.
6. To verify your status as a student, GitHub needs proof of enrollment. Login to <a href="https://mybama.ua.edu" target="_blank">MyBama</a> and search/select “Enrollment Verification.” Ensure that all relevant boxes are checked (name, term, current semester, graduation date).
7. Select **save and print** and save the generated PDF to your computer. Next, take a snapshot (screen grab) or a picture of the document and upload to GitHub for verification. 
   1. *In some cases, this may take a couple of tries. Some students have reported success with uploading a zoomed-in and clear picture from their phone. Other students have reported success uploading a screenshot of their student ID from the ACT Card/eAccounts mobile app. It can also help to be connected to the UA campus network.*
8. During verification, you may be asked to share your location. If you are not on campus yet, select "classes haven't started yet." Then submit your enrollment verification as evidence.
9. GitHub should respond within a week with access to the education package. If you receive an instant email rejection, try to follow the instructions on the rejection email to troubleshoot.

### Python

In this course, we will rely primarily on Python for data analysis.

1. To install Python for this course, start by going here: <a href="https://www.python.org/downloads/" target="_blank">Python</a>. 
2. Select **Download Python** for the latest release (e.g., version 3.14) for your operating system (e.g., Windows).
3. Open the file from your downloads and follow installation instructions (leaving default options where applicable). 

### Visual Studio Code (VS Code)

Visual Studio Code is a free, popular code editor made by Microsoft. It has excellent support for Python, Jupyter notebooks, and data science workflows through extensions.

#### Download and install VS Code
1. To download VS Code, start by going here: <a href="https://code.visualstudio.com/" target="_blank">Visual Studio Code</a>.
2. Select **Download** for your operating system (e.g., Windows).
3. Open the installer from your downloads and follow the prompts to install VS Code (using default options where applicable).

#### Install extensions
1. Once installed, open VS Code. It may prompt you to log in to GitHub. If so, log in with your GitHub account created above. This will allow you to use GitHub Copilot and sync your settings across devices.
2. Select the **Extensions** icon on the left sidebar (or press `Ctrl+Shift+X` on Windows / `Cmd+Shift+X` on Mac).
3. Search for and install the following extensions:
   1. **Python** (by Microsoft) — provides Python language support, debugging, and more.
   2. **Jupyter** (by Microsoft) — enables Jupyter notebook support directly in VS Code.
   3. **Data Wrangler** (by Microsoft) — lets you browse, sort, and filter a dataframe in a spreadsheet-like view. We use this in later modules.
   4. **GitHub Copilot** — AI-powered code suggestions. This may already be installed. Once installed, you will be prompted to log into GitHub and link your account. This requires you to have a GitHub account (see above).

### Claude

Claude is an AI assistant made by Anthropic. We will use Claude as an AI tool throughout the course. You should get an invitation to the MAcc program subscription. Make sure to follow the instructions in the invitation email to activate your account.

Claude is available as a desktop app and as a VS Code extension.

1. To download the Claude desktop app, go here: <a href="https://claude.com/download" target="_blank">Claude Download</a>. Select your operating system and follow the prompts to install.
2. To install the Claude Code extension in VS Code, go to the **Extensions** sidebar (`Ctrl+Shift+X` on Windows / `Cmd+Shift+X` on Mac) and search for **Claude Code** (by Anthropic). Install the extension.

**If you made it here, you are ready to start the course! On the first day, we will run through the [Getting Started](course_intro.ipynb) exercise.**

## Datasets

The datasets used in this module are stored in this folder alongside the notebook, so the notebook loads them by filename (e.g., `pd.read_pickle('anscombe.pkl')`).

### Anscombe's Quartet (anscombe.pkl)

Anscombe’s Quartet is a classic illustrative dataset consisting of four small datasets with identical or nearly identical summary statistics, including means, variances, correlations, and linear regression lines. Despite these similarities, each dataset exhibits a distinct underlying data pattern when visualized.

Source: Seaborn package