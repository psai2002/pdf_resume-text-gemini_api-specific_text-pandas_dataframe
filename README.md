## Resume parser using Gemini API
### Description:
Give a resume(.pdf) as input in the code. The given resume is converted into text data. The textual resume data is then passed to Gemini API. Extract name, email, phone, college, skills from the data passed to Gemini API. Finally, displays the extracted output in pandas dataframe.

- The code is written in python.
- Install [python](https://www.python.org) in your system.

Go to [Gemini API](https://ai.google.dev/) website. Login with your account and create API key.  
Copy the API key. Add the API key that you have coppied to your system environment variables:  
- In *Ubuntu or MAC* open ``~/ .bashrc`` and add a line ``export "GEMINI_API_KEY=<your_api_key>"``.  
After adding your API key save and exit the file.
- In *Windows* open *cmd(command prompt)* and type ``setx GEMINI_API_KEY “<yourkey>”``

**Import python modules:**  
pandas  
requests  
google-generativeai  
pypdf  
json  
os
