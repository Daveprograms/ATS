

# ATS (Applicant Tracking System) Web Application

This web application allows users to enhance their resumes by evaluating them against a provided job description. It utilizes Streamlit for the user interface and Python for backend processing.

## Running the Application

To run the application, you need to have Python installed along with the necessary dependencies. You can install the dependencies using the following command:

```bash
pip install -r requirements.txt
```

Before running the application, you need to obtain an API key from [AI Studio by Google](https://aistudio.google.com/) to enable content generation. Once you have the API key, create a `.env` file in the project directory and store your API key in it:

```
GOOGLE_API_KEY=your_api_key_here
```

Now, you can run the application using the following command:

```bash
streamlit run Ats.py
```

This command will start a local development server, and you can access the application in your web browser at `http://localhost:8501`.

## File Structure

- `Ats.py`: Contains the main Python code for the application.
- `.env`: File to store your Google API key.
- `requirements.txt`: Lists the Python dependencies required for the application.
- `README.md`: This file, providing information about the project.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. All contributions are welcome!




