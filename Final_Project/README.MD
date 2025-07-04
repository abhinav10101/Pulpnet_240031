So, the jupyter notebook named Final_Project can be run on Google Colab. 
Here, I have extracted my dataset from the ICS website.

First run the cells for webscraping and creating the Chroma vector store. 

You will need to generate a API Key from Google AI studio to run the gemini-1.5-flash model and for the GoogleGenerativeAIEmbeddings. Store it in the secret keys associated to the google colab notebook under the name GOOGLE_API_KEY. Also create an NGORK authentication token and store it in the google secret keys under the name NGORK. 

Then you can run the streamlit file which creates the app.py file and then run the cell below it to generate url to the bot and you can start asking questions. 
