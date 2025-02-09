**Cold Mail Generator**  
Cold email generator is a tool developed using groq, langchain and streamlit. It allows user to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions.


**Set-up**
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside app/.env update the value of GROQ_API_KEY with the API_KEY you created.

2. To get started, first install the dependencies using:
    pip install -r requirements.txt
   
4. Run the streamlit app:
    streamlit run app/main.py
