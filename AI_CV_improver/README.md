# CV Improvement with Artificial Intelligence

This Python project leverages the power of Artificial Intelligence, specifically the ChatGPT API by OpenAI, to enhance the quality of your Curriculum Vitae (CV). It offers two main applications:

## Application 1: Streamlit-based CV Improvement App

### Prerequisites
Before running the application, ensure you have the following:
- Python 3.x installed
- [Streamlit](https://streamlit.io/) installed via `pip install streamlit`
- An OpenAI API key (Refer to [OpenAI blogpost](https://openai.com/blog/openai-api/) to obtain one)

### Usage
1. Download this project folder and install the required dependencies using `pip install -r requirements.txt`.
2. Replace `constants.py` with your OpenAI API key (Note: Never share your API key online).
3. Run the Streamlit app by executing `streamlit run app.py`.
4. Follow the prompts within the app to enhance your CV:
   - Download the provided `cv_template.txt` file and fill it with your CV details.
   - Add, update, or delete work experiences.
   - Update your CV summary.
5. The app will display the changes made to your CV summary and work experiences, and you can download the improved CV as a downloadable file.

## Application 2: Efficient Command-line CV Analyzer

### Prerequisites
Before running this script, ensure you have the following:
- Python 3.x installed
- An OpenAI API key (Refer to [OpenAI blogpost](https://openai.com/blog/openai-api/) to obtain one)

### Usage
1. Download this project folder and install the required dependencies using `pip install -r requirements.txt`.
2. Replace `constants.py` with your OpenAI API key (Note: Never share your API key online).
3. Open `main.py` and change the `uploaded_file` variable to specify the CV file you want to analyze.
   ```python
   uploaded_file = open('cv_example.txt', 'r')
