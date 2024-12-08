# GPT-PHD

## **How to Run TobIAS...**

### **...locally?**

**Step 1**: Certify that there are no **.env** or **pycache** folders in your working directory, as it could create conflicts.

**Step 2**: It is recommended you create a virtual environment. If you are on Vscode simply do **CTRL+SHIFT+P** and select the virtual environment option.

**Step 3**: It should ask to select a dependency file, select the **requirements.txt**. If it doesn't ask for it, then run the command  **pip install -r requirements.txt** before you go to the next step.

**Step 4**: Run the command **chainlit run app.py -w** in the terminal. It should ask for a Groq API key, you can use the one below. After the key is inserted, a web page with the tool's chat should open on your browser.

**Step 5**: Enjoy our tool.


### **...online?**

**Step 1**: First create a account on [render](https://render.com/).

**Step 2**: After that chose the **Web Services** option and chose [this github repository](https://github.com/JoaoTML/GPT-PHD).

**Step 3**: In the settings, on the start command insert **uvicorn runner:app --host 0.0.0.0 --port 80**.

**Step 4**: Then go to the enviroment variables and put the **GROP_API_KEY** variable and the respective value.

**Groq API key**: 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
