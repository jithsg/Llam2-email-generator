# Llam2-email-generator
 
![Front End](https://github.com/jithsg/Llam2-email-generator/blob/main/email.png)

This repository hosts a Streamlit application that leverages Llam2-7B-Chat and LangChain's capabilities to generate emails based on user inputs. It integrates Llam2-7B through the CTransformers library from LangChain, providing an efficient and effective way to generate contextually relevant email texts.

### Features

- **Streamlit Interface:** Easy-to-use web interface for inputting email details and generating content.
- **LangChain Integration:** Utilizes the LangChain library to interact with language models effectively.
- **Customizable Email Generation:** Allows users to specify the email topic, sender, recipient, and writing style.
- **LLM Utilization:** Employs a large language model for generating contextually relevant and styled email content.

### How it Works

1. **Streamlit UI:** Users input the email topic, sender and recipient names, and select a writing style through a Streamlit-based interface.
2. **Email Generation:** Upon clicking the 'Generate' button, the app calls the `getLLMResponse` function, which formats the input and sends it to the LLM for processing.
3. **Response Handling:** The app retrieves the generated email content from the LLM and displays it in the Streamlit interface.

### Installation and Usage

1. Clone the repository.
2. Install required packages: `pip install -r requirements.txt`.
3. Run the Streamlit app: `streamlit run app.py`.
4. Access the web interface, input your details, and generate emails.

### Technologies Used

- **Streamlit:** For creating the web interface.
- **LangChain:** For handling interactions with language models.
- **CTransformers:** A LangChain library for efficient language model interfacing.


Distributed under the MIT License. See `LICENSE` for more information.

