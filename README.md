**📧 Cold Mail Generator**

This tool leverages Groq, LangChain, and Streamlit to help services-based companies craft personalized cold emails. 

 Users simply input the URL of a company's careers page, and the tool automatically extracts job listings from that page. It then generates tailored cold emails, embedding relevant portfolio links retrieved from a vector database, aligning them with the specific job descriptions.

 **Imagine a scenario**

 **1. Nike's Situation:**

Actively seeking a Principal Software Engineer.

Investing significant resources in recruitment, onboarding, and training.

**2. Atliq's Offering:**

Atliq is a leading software development firm.

Offers a unique solution by providing a dedicated software engineer to Nike.

**3. Mohan's Role:**

Mohan, a business development executive at Atliq, uses the tool to draft a personalized cold email.

The email emphasizes Atliq’s expertise and aligns their services with Nike’s specific hiring needs.

Ensures a direct and effective pitch to Nike.

![image](https://github.com/user-attachments/assets/7614bafe-a7e8-4a49-b81c-4710a3dcb92e)

**Architecture Diagram**

![image](https://github.com/user-attachments/assets/a425a385-2618-438e-ad8e-ed6d27a71dc2)

**Set-up**

1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside app/.env update the value of GROQ_API_KEY with the API_KEY you created.

2. To get started, first install the dependencies using:

   pip install -r requirements.txt

3. Run the streamlit app:

   streamlit run app/main.py


