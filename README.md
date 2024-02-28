# ChatCSV-Streamlit-App
An LLM powered ChatCSV Streamlit app so you can chat with your CSV files.

<h1> How to run the app?</h1>
<p> 1. create virtual env : python -m venv <nameofvirtualenv> <br>
  2. activate this virtual env : <nameofvirtualenv>\Scripts\activate<br>
3. install required libraries : pip install -r requirements.txt <br>
4. streamlit run app.py <br>
5. Interact with your csv :) </p>
 
 Generate your OpenAI API key here: <a href="https://platform.openai.com/account/api-keys"> Click Here </a>
<br>
<h2> Run locally </h2>
<p> If you are running the app locally, then you can freely use the API key. <br>
  in app.py, line 9: <br>
  
  ```
  
  openai_api_key = 's#-#####################fr'
  
  #can set the API key directly, if running locally.
  
  ```
 
 Else if you want to keep the key private, store it in an environment variable named "OPENAI_API_KEY" by adding set OPENAI_API_KEY = "" in your OS and then refer the key in app.py by:
 
  ```
  from dotenv import load_dotenv
  load_dotenv()
  openai_api_key = os.getenv("OPENAI_API_KEY")
 
  ```
  
