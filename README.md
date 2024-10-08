# TECHFUSION_TECH-A-THON_2024
    **Mental Health Chat Bot**
**Introduction**

The Mental Health Chat Bot is a web application built with Streamlit that aims to support mental well-being by providing users with personalized relaxation tips and stress relief techniques. Leveraging the capabilities of the Ollama language model, the chatbot generates actionable advice based on user-provided mood or stress level inputs.

**Features**

•	Personalized Relaxation Tips: Offers tailored advice for stress relief based on user input.
•	Interactive Interface: Simple text input to describe mood or stress level.
•	Real-Time Responses: Provides immediate feedback and suggestions.
Requirements

To run this application, ensure you have the following:

•	Python 3.8+: The application is compatible with Python 3.8 and above.

•	Streamlit: For creating the web app interface.

•	LangChain Core: Core library for building language model chains.

•	LangChain Community: Community extensions and tools for language models.

•	Ollama: Language model used to generate responses.

**Installation**

Follow these steps to set up the environment and run the app:

**1.	Clone the Repository:**

git clone <repository_url>

cd <repository_directory>

**2.	Set Up the Virtual Environment:**

Create and activate a virtual environment:

python -m venv venv

source venv/bin/activate

**3.	Install Dependencies:**

Install the required Python packages:

pip install streamlit langchain-core langchain-community

**4.	Configuration:**

If the Ollama model requires API keys or special configurations, ensure they are set up properly. Refer to the Ollama documentation for details on configuration.

**Usage**

**1.	Start the Application:**

Run the Streamlit app with the following command:

streamlit run app.py

Replace app.py with the filename of your Streamlit script if different.

**2.	Interacting with the Chat Bot:**

o	Enter Mood/Stress Level: Type in your mood or stress level into the input box.

o	Receive Tips: The chatbot will generate and display personalized relaxation tips and stress relief strategies.

**3.	Examples of User Input:**

o	"I'm feeling very stressed about work."

o	"I've been anxious lately and need some advice."

o	"I am in a good mood but want to maintain it."

**Code Overview**

•	Prompt Template: Configures how the chat bot interacts with the language model. It guides the model to focus on providing actionable stress relief techniques.

•	Model Initialization: Uses the Ollama model to process user inputs and generate responses.

•	Output Parsing: Converts the raw output from the model into a readable string format for the user.

•	User Interaction: Processes and handles user inputs, and displays the generated advice on the interface.

**Troubleshooting**

•	Model Initialization Errors: Ensure you have the correct model name and verify that the model is properly configured.

•	Dependency Issues: Confirm all required libraries are installed and compatible with your Python version.

•	Connection Problems: If using a model that requires internet access, ensure your network connection is stable.

**Advanced Configuration**

•	Customizing Prompts: Modify the prompt template in the code to change the style or type of responses generated by the model.

•	Model Parameters: Adjust model parameters or switch models based on performance and response quality.

**Contributing**

Contributions are welcome! To contribute:

1.	Fork the Repository: Create your own copy of the repository on GitHub.
   
2.	Create a Branch: Develop features or fix bugs on a separate branch.
   
3.	Submit a Pull Request: Provide a clear description of changes and submit your pull request.
   
**License**

This project is licensed under the MIT License.

**Contact**

For questions or support:

•	Email: 23i351@psgtech.ac.in, 23i366@psgtech.ac.in

**Acknowledgements**

•	Streamlit: For the framework used to build the interactive web app.

•	LangChain: For the tools and libraries used to integrate language models.

•	Ollama: For the powerful language model providing responses.
