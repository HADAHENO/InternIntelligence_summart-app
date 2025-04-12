# Text Summarization App using T5

This application is a simple web interface that utilizes the T5 model to summarize text. It's built with Streamlit to easily create web UIs for machine learning applications.

## Features

* Automatic text summarization using the T5 model.
* Simple and user-friendly interface.
* Responsive design for various screen sizes.
* Dark and light mode support.
* A "Refresh" button to clear the text box and summary.

## Requirements

* Python 3.7+
* The libraries listed in `requirements.txt` (install with `pip install -r requirements.txt`).

## How to Run

1.  Clone the repository:

    ```bash
    git clone [repository link]
    cd [folder name]
    ```

2.  Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3.  Run the app:

    ```bash
    streamlit run app.py
    ```

4.  The application will open in your web browser.

## How to Use

1.  Enter the text you want to summarize in the text box.
2.  Click the "Generate Summary" button.
3.  The generated summary will be displayed below the text box.
4.  Click the "Refresh" button to clear the text and summary.

## Notes

* Summary generation time may vary depending on the length of the text and the model size.
* The application's design can be customized by editing the `app.py` file and modifying the CSS variables.
* The color theming of the app can be modified by editing the st.set_page_config theme values.

## License

This project is licensed under the \[License Name] license.

## Author

\[InternIntelligence_ProjectName, Huda Maher]

## Links
* [\[Hugging Face Spaces link (if deployed)](https://huggingface.co/spaces/hadheedo/Summary)]
