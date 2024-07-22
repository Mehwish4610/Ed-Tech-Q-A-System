
# Ed-Tech QA using LangChain and Google Palm

This is an End-toEnd LLM project using LangChain framework, HuggingFace, Streamlit, FAISS and Google Palm. I have built a question and answer system for a real e-learning company(no toy datasets).

![App Screenshot](https://github.com/Mehwish4610/Ed-Tech-Q-A-System/blob/main/cbqap.png)



## Project Requirements
1. langchain==0.0.284
2. python-dotenv==1.0.0
3. streamlit==1.22.0
4. tiktoken==0.4.0
5. faiss-cpu==1.7.4
6. protobuf~=3.19.0
7. google-generativeai
8. PyCharm IDE (any ide of your choice)
9. Q&A dataset




## Installation

1. Install the requirements from requirement.txt by running
       
        pip install -r requirements.txt

2. Create a file and save it as " .env ".

3. Store your accquired API Key from Google in a file called ".env".

You can get your free api key from " makersuites.google.com "

4. Complete the codes for langchain.py and main.py 

    
## Usage

1. Run the Streamlit app by executing:
    
        streamlit run main.py

2. The web app will open in your browser.

- To create a knowledebase of FAQs, click on Create Knolwedge Base button. It will take some time before knowledgebase is created so please wait.

- Once knowledge base is created you will see a directory called faiss_index in your current folder

- Now you are ready to ask questions. Type your question in Question box and hit Enter



## Running Tests

You can start questioning by prompting your requireed query. Here are some sample questions you can ask:

     1. Do you guys provide internship and also do you offer EMI payments?
     2. Do you have javascript course?
     3. Should I learn power bi or tableau?
     4. I've a MAC computer. Can I use powerbi on it?
     5. I don't see power pivot. how can I enable it?

