# GPT-PHD

## **Detailed tutorial to run app.py**

**Step 1**: Certify that there are no **.env** or **pycache** folders in your working directory, as it could create conflicts.

**Step 2**: It is recommended you create a virtual environment. If you are on Vscode simply do **CTRL+SHIFT+P** and select the virtual environment option.

**Step 3**: It should ask to select a dependency file, select the **requirements.txt**. If it doesn't ask for it, then run the command  **pip install -r requirements.txt** before you go to the next step.

**Step 4**: Run the command **chainlit run app.py -w** in the terminal. It should ask for a Groq API key, you can use the one below. After the key is inserted, a web page with the tool's chat should open on your browser.

**Step 5**: Enjoy our tool.

**Groq API key**: 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


# How to put online.

First create a account on render.

After that chose the website option and chose this github

In the settings, on start command put uvicorn runner:app --host 0.0.0.0 --port 80

Then go to the enviroment option and put the groq_api_key
