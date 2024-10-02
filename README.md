# AI-Powered Sentiment Analysis Tool

This project is an AI-powered sentiment analysis tool that performs real-time sentiment analysis on user-input text. It can analyze sentiments in tweets, reviews, or any text input to determine whether the sentiments are positive, negative, or neutral.

## Features

- **Real-Time Analysis:** The tool utilizes an efficient JavaScript AI library to process and analyze text in real-time as the user types.
- **Sentiment Score:** It provides a sentiment score alongside the classification, giving a numerical representation of the sentiment intensity.
- **Interactive UI:** The user interface is simple and responsive, allowing users to input text and displaying both the sentiment classification and score dynamically.
- **Visualization:** A graphical representation of sentiment scores is included using a lightweight JavaScript charting library to visualize sentiment trends over the text.
- **Support for Multiple Languages:** The tool implements basic multilingual support using a pre-trained model that can handle various languages, increasing its versatility.

## Technical Stack

- **TensorFlow.js:** TensorFlow.js is used for running a pre-trained sentiment analysis model directly in the browser.
- **Universal Sentence Encoder:** The Universal Sentence Encoder is employed to generate embeddings of the input text.
- **Text Classification Model:** A pre-trained text classification model is utilized for sentiment analysis.
- **HTML/CSS:** The front-end interface is built using HTML and CSS.
- **Chart.js:** Chart.js is used to create dynamic charts for sentiment visualization.

## Getting Started

To run the AI-Powered Sentiment Analysis Tool locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/jayinmt/ai-powered-sentiment-analysis.git
   ```

2. Open the `index.html` file in a web browser.

3. Start analyzing sentiments by entering text in the provided textarea.

## Usage

1. Open the AI-Powered Sentiment Analysis Tool in a web browser.

2. Enter the text you want to analyze in the textarea provided.

3. As you type, the tool will perform real-time sentiment analysis and display the sentiment label (Positive or Negative) along with the sentiment score.

4. The sentiment scores will be visualized in a line chart, showing the sentiment trends over time.

## Contributing

Contributions to the AI-Powered Sentiment Analysis Tool are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The sentiment analysis model used in this tool is based on the pre-trained model provided by TensorFlow.js.
- The Universal Sentence Encoder is developed by Google and is used for generating text embeddings.
- Chart.js is an open-source JavaScript library used for creating the sentiment visualization.

## Disclaimer

Please note that the sentiment analysis provided by this tool is based on a pre-trained model and may not be 100% accurate in all cases. The results should be used as a general indication of sentiment and not as a definitive classification.
