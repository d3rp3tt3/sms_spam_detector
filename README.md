# SMS Spam Detector

This project includes a Support Vector Classification (SVC) model that predicts whether a SMS (text message) is spam.

It also includes a Gradio user interface (UI), which you can use to enter example text messages to test the model.

## Running the project

### Accessing the code

1. Clone this repository.
2. Open the [project's Jupyter Notebook](/gradio_sms_text_classification.ipynb) and run it with a Jupyter server or IDE with Jupyter integration. Recommnded: VSCode

### Running the user interface

The user interface (UI) was built with Gradio. When you run the Jupyter Notebook, it instantiates a local Gradio server. Two URLs should be written out in the Terminal or inline in the notebook: One for the local address and the other for a shareable address/URL. Note: The shareable URL points to the server running on your machine. The UI is NOT hosted on Gradio's servers.

![Spam Detector Gradio UI](/Resources/spam_ham_gradio_ui.png)