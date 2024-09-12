# Colleague On-Boarding Application
This web application is built using python, streamlit, python enabled html.



![overview_of_app.png](assets%2Fimages%2Foverview_of_app.png)

## Features
 
1) The Application has 2 pages Colleague On-Boarding App Home page and Data Load Page 
2) Home Page helps user to interact with the data availabe at the Data Bank.
3) User can upload, user details and data to data to data bank.
4) The app shows the question answer mode in deatil with questions and respective answers

## How to use the Repository
To start using the repository, first clone the project into your local pc

```
git clone https://github.com/arunnaray/llm-poc-hub.git
```

Next, open the file location in any Python IDE, I highly recommend PyCharm. 
Then, navigate to the folder > .streamlit (as shown in the picture below), create a file called secrets.toml

![add_secrets_toml.png](assets%2Fimages%2Fadd_secrets_toml.png)

Within secrets.toml file add your OpenAI API key into the file (as shown below). This will allow streamlit to pick up the secrets.

```
gpt_secret = "<YOUR-API-KEY>"
```

Once done, install the requirements for the project.

```
pip install -r requirements.txt
```

To run the application. Within the terminal of the IDE do:

```
streamlit run Home.py
```

Access the site using: http://localhost:8501

## Contribution
Please feel free to contribute to the repository.

Fork the application, make edits and perform a pull request. 
